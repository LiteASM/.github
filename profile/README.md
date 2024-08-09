# LiteASM

LiteASM is a beginner-friendly assembly-like language designed for ease of use and learning. It supports basic arithmetic and logical operations, as well as reusable code in the form of functions.

## Example Program

```
; Calculate the sum of two numbers
MAIN:
    INPUT A        ; Read first number
    INPUT B        ; Read second number
    CALL SUM       ; Call SUM function
    PRINT Z        ; Print result
    JMP END

SUM:
    ADD Z, A, B    ; Z = A + B
    RET            ; Return to caller

END:
    ; Program ends here
```

## License
LiteASM is licensed under the MIT License.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
