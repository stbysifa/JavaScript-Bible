
# ✅ Topic 1: JavaScript Syntax and Comments

### 🎯 Interview-Focused Questions Only

---

### 1. **What are the basic syntax rules in JavaScript?**

*Expected Answer:* Statements usually end with a semicolon, JavaScript is case-sensitive, and white space is ignored (used for readability).

---

### 2. **What is the difference between single-line and multi-line comments in JavaScript?**

*Expected Answer:*

* Single-line: `// comment`
* Multi-line: `/* comment */`

---

### 3. **Why are comments important in JavaScript code?**

*Expected Answer:*
Comments make code readable, help explain logic, assist in debugging, and are used for documentation and collaboration.

---

### 4. **Can comments affect JavaScript execution?**

*Expected Answer:*
No. Comments are ignored during execution; they are not parsed or run by the JavaScript engine.

---

### 5. **What happens if you put a comment inside a string or a code block incorrectly?**

*Expected Answer:*
It could result in a syntax error if placed incorrectly, such as inside a string without proper syntax or breaking code logic.

---

### 6. **Is it necessary to use semicolons in JavaScript? Why or why not?**

*Expected Answer:*
Semicolons are optional due to automatic semicolon insertion (ASI), but it's recommended to use them consistently to avoid unexpected bugs.

---

### 7. **Give an example where omitting a semicolon causes an unexpected result.**

*Example:*

```js
let x = 10
let y = 20
let z = x + y
(function() {
  console.log("Surprise!");
})()
// This runs immediately due to ASI interpreting it as a function call
```

---

### 8. **Can you comment out part of a line in JavaScript?**

*Expected Answer:*
Yes, using `//` after the code:

```js
let name = "John"; // This is a comment
```

---

### 9. **What are valid variable naming rules in JavaScript?**

*Expected Answer:*

* Must begin with a letter, `$`, or `_`
* Cannot be a reserved keyword
* Can contain letters, numbers, `$`, or `_`
* Is case-sensitive

---

### 10. **What will happen if you use a multi-line comment inside another multi-line comment?**

*Expected Answer:*
JavaScript **does not support nested multi-line comments**, and this will result in a syntax error.

