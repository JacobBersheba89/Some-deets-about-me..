# ⚡ Welcome to My GitHub! ⚡

## About Me
Hello, I am an enthusiastic beginner data analyst passionate about programming and exploring new technologies. My main interests include Python and JC, but I am open to learning new programming languages and technologies. I am looking for opportunities where I can apply and expand my knowledge in data analysis and software development.

## What I Do
- **Python Programming**: I focus on creating clean and efficient code. 😄
- **Learning New Languages**: Besides Python and JC, I also explore other programming languages. 🌱
- **Collaborating on Projects**: I enjoy participating in new projects where I can contribute and learn from others.

## Projects
For more information about my projects, please visit [my repositories](https://github.com/JacobBersheba89?tab=repositories). 👀

## Contact Me
If you are interested in collaborating or sharing new opportunities, please do not hesitate to contact me.

Thank you for visiting my profile!👋


# Simple Python script to display Fibonacci sequence

def fibonacci(n):
    a, b = 0, 1
    result = []
    while len(result) < n:
        result.append(a)
        a, b = b, a + b
    return result

# Change the number 10 to how many Fibonacci numbers you want to generate
fib_sequence = fibonacci(10)
print("Fibonacci sequence:", fib_sequence)

