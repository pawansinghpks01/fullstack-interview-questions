# JavaScript based (Node + React) Fullstack Interview Questions
[Skip to Topics](#topics) || [Bottom of the Page](#bottom)

<p align="center">
  <a href=https://github.com/pawansinghpks01/fullstack-interview-questions?utm_source=github&utm_medium=sponsor&utm_campaign=fullstack-interview-questions>
    <img src=https://github.com/pawansinghpks01/fullstack-interview-questions/blob/master/Assets/FSIQ.jpg alt="REPO Home Logo" width="200" height="100">
  </a>
</p>

Answers to some common JS Full stack interview questions + some short coding questions (Created for self preparation and with a hope that this may help someone else too!)

> Click :star:if you like the project.

> Follow :+1: me for more

<!-- Go to [Coding Exercise](#coding-exercise) for coding specific questions
## Download PDF/Epub formats
You can download the PDF and Epub version of this repository from the latest run on the [actions tab](https://github.com/sudheerj/JavaScript-Interview-Questions/actions). -->

---
<p align="center">
  <p>Take a look at a few repositories I have created!</p>
  <p align="center">
    <ol>
     <li>A <a href=https://github.com/pawansinghpks01/html-about-me/>Web Page</a> for self using only HTML. See the <a href=https://pawansinghpks01.github.io/html-about-me/>Github Page</a> for this Project.</li>
    <li>A <a href=https://github.com/pawansinghpks01/html-css-about-me/>Web Page</a> for self using just html and CSS. See the <a href=https://pawansinghpks01.github.io/html-css-about-me/>Github Page</a> for this Project.</li>
    </ol>
  </p>
</p>

---
---

### Topics

|No.| Topic |
|-- | ------- |
|1  | [React](#table-of-contents---react) |
|2  | [JavaScript](#table-of-contents---javascript)|

---
---

### Table of Contents - React

| No. | Questions | Type |
|-- | --------- | ---------------- |
|1  | [What are the possible ways to create objects in JavaScript](#what-are-the-possible-ways-to-create-objects-in-javascript) | Subjective |
|2  | [What is the output of below equality check](#what-is-the-output-of-below-equality-check)| MCQ |
---

### Answers - React
---

1. ### What are the possible ways to create objects in JavaScript

   There are many ways to create objects in javascript as below

   1. **Object constructor:**

      The simplest way to create an empty object is using the Object constructor. Currently this approach is not recommended.

      ```javascript
      var object = new Object();
      ```

   2. **Object's create method:**

      The create method of Object creates a new object by passing the prototype object as a parameter

      ```javascript
      var object = Object.create(null);
      ```

   3. **Object literal syntax:**

      The object literal syntax is equivalent to create method when it passes null as parameter

      ```javascript
      var object = {};
      ```
      
**[⬆ Back to Table of Contents](#table-of-contents---react)** || **[⬆ Back to Top (Answers)](#answers---react)**
       
2. #### What is the output of below equality check

```javascript
console.log(0.1 + 0.2 === 0.3);
```

- 1: false
- 2: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

This is due to the float point math problem. Since the floating point numbers are encoded in binary format, the addition operations on them lead to rounding errors. Hence, the comparison of floating points doesn't give expected results.
You can find more details about the explanation here [0.30000000000000004.com/](https://0.30000000000000004.com/)

</p>
</details>

**[⬆ Back to Table of Contents](#table-of-contents---react)** || **[⬆ Back to Top (Answers)](#answers---react)**


---
---

### Table of Contents - JavaScript

| No. | Questions | Type |
|-- | --------- | ---------------- |
|1  | [What are the possible ways to create objects in JavaScript](#what-are-the-possible-ways-to-create-objects-in-javascript) | Subjective |
|2  | [What is the output of below equality check](#what-is-the-output-of-below-equality-check)| MCQ |
---

### Answers - JavaScript
---

1. ### What are the possible ways to create objects in JavaScript

   There are many ways to create objects in javascript as below

   1. **Object constructor:**

      The simplest way to create an empty object is using the Object constructor. Currently this approach is not recommended.

      ```javascript
      var object = new Object();
      ```

   2. **Object's create method:**

      The create method of Object creates a new object by passing the prototype object as a parameter

      ```javascript
      var object = Object.create(null);
      ```

   3. **Object literal syntax:**

      The object literal syntax is equivalent to create method when it passes null as parameter

      ```javascript
      var object = {};
      ```
      
**[⬆ Back to Table of Contents](#table-of-contents---javascript)** || **[⬆ Back to Top (Answers)](#answers---javascript)**
       
2. #### What is the output of below equality check

```javascript
console.log(0.1 + 0.2 === 0.3);
```

- 1: false
- 2: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

This is due to the float point math problem. Since the floating point numbers are encoded in binary format, the addition operations on them lead to rounding errors. Hence, the comparison of floating points doesn't give expected results.
You can find more details about the explanation here [0.30000000000000004.com/](https://0.30000000000000004.com/)

</p>
</details>

**[⬆ Back to Table of Contents](#table-of-contents---javascript)** || **[⬆ Back to Top (Answers)](#answers---javascript)**

---
---

### bottom
