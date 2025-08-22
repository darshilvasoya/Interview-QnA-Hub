# Interview-QnA-Hub

# Coding Interview Questions & Answers 💡

A community-driven collection of interview questions & answers.  
Anyone can contribute by adding questions they know, or by answering existing ones.  

---

## 🚀 How to Contribute

1. Fork this repo  
2. Create a new branch  
3. Add your question file in the correct folder  
4. Commit & push  
5. Open a Pull Request  

Check [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## ✅ Example Question File
```
## Question
What is a Python decorator?

## Answer
- A decorator is a function that modifies another function.  
- It allows adding extra functionality without changing the original code.
```
```python
def decorator(func):
    def wrapper():
        print("Before function call")
        func()
        print("After function call")
    return wrapper

@decorator
def hello():
    print("Hello World")

hello()
```

---

## 📌 Categories

- Coding Questions (Python, Java, C++, etc.)  
- System Design  
- DBMS & SQL  
- Miscellaneous (HR, OS, Networking, etc.)

---

## 🤝 Contributing

We welcome contributions!  
Follow the steps in [CONTRIBUTING.md](./CONTRIBUTING.md) to add your questions.
