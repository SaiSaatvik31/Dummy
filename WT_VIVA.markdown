### **I. HTML & CSS (Static Web Development)**

**Q1: What is the difference between a Static and a Dynamic website?**
[cite_start]**Ans:** A static website displays the same content for every visitor and is built using only HTML and CSS[cite: 36, 62]. [cite_start]A dynamic website generates content in real-time based on user interaction or database data, typically using JavaScript and server-side technologies[cite: 40, 351].

---

**Q2: What is the purpose of the `<!DOCTYPE html>` declaration?**
[cite_start]**Ans:** It informs the web browser about the version of HTML being used (HTML5) to ensure the page renders correctly[cite: 64]. It is not an HTML tag but an instruction to the browser.

---

**Q3: What is the difference between `class` and `id` in CSS?**
[cite_start]**Ans:** An `id` is unique and can only be used once per page to identify a single element (e.g., `id="username"`)[cite: 203]. [cite_start]A `class` can be reused on multiple elements to apply the same styling rules to all of them (e.g., `class="form-group"`)[cite: 318].

---

**Q4: Explain the "Box Model" in CSS.**
**Ans:** The Box Model is a container that wraps every HTML element. [cite_start]It consists of the actual content, padding (space inside the border) [cite: 75][cite_start], border (the edge) [cite: 89][cite_start], and margin (space outside the border)[cite: 74].

---

### **II. JavaScript (Dynamic Web Development)**

**Q5: What is DOM (Document Object Model) manipulation?**
**Ans:** The DOM is a tree-like representation of the web page structure. [cite_start]DOM manipulation allows JavaScript to access, change, or delete HTML elements and attributes dynamically to update the content without reloading the page[cite: 44, 780].

---

**Q6: What is the difference between `==` and `===` in JavaScript?**
**Ans:** The `==` operator checks for value equality but performs type conversion if necessary (loose equality). The `===` operator checks for both value and data type equality (strict equality), which is generally safer to use.

---

**Q7: How do you validate a form in JavaScript?**
[cite_start]**Ans:** We access form values using `document.getElementById().value` and check them against conditions (e.g., regex for email, length for passwords)[cite: 456]. [cite_start]If a condition fails, we display an error message and return `false` to prevent submission[cite: 461, 464].

---

**Q8: What is an Event Listener?**
**Ans:** An event listener is a procedure in JavaScript that waits for a specific event to occur (like a click). [cite_start]When the event fires, it executes a callback function to perform an action[cite: 797].

---

### **III. Node.js (Server-Side Programming)**

**Q9: What is Node.js and why is it used?**
[cite_start]**Ans:** Node.js is a runtime environment that allows you to execute JavaScript on the server side, outside the browser[cite: 45, 811]. It is used to build scalable, high-performance backend services.

---

**Q10: What is the purpose of `package.json`?**
[cite_start]**Ans:** It is the manifest file for a Node.js project created by `npm init`[cite: 819]. It holds metadata like the project name and the list of dependencies (libraries) required to run the project.

---

**Q11: Explain the role of the `fs` module in Node.js.**
[cite_start]**Ans:** The `fs` (File System) module allows Node.js to interact with the computer's file system[cite: 853]. [cite_start]It provides methods to read (`readFile`), write (`writeFile`), append, and delete files on the server[cite: 857, 866, 878].

---

**Q12: What is Express.js?**
[cite_start]**Ans:** Express.js is a minimal and flexible web application framework for Node.js[cite: 936]. [cite_start]It simplifies tasks like setting up the server, managing routing (URLs), and handling HTTP requests and responses[cite: 953].

---

**Q13: What are `req` and `res` objects?**
[cite_start]**Ans:** `req` (Request) represents the HTTP request and contains data sent by the client[cite: 1054]. [cite_start]`res` (Response) represents the HTTP response and is used to send data (like HTML, JSON) back to the client[cite: 1055].

---

### **IV. MVC Architecture & REST APIs**

**Q14: What is MVC Architecture?**
[cite_start]**Ans:** MVC stands for Model-View-Controller[cite: 1147].
* [cite_start]**Model:** Manages data logic (e.g., `userModel.js`)[cite: 1170].
* [cite_start]**View:** Handles the display/UI (e.g., `index.ejs`)[cite: 1190].
* [cite_start]**Controller:** Processes user requests, talks to the Model, and updates the View[cite: 1211].

---

**Q15: What is a REST API?**
[cite_start]**Ans:** REST (Representational State Transfer) is an architectural style for creating web services[cite: 1293]. A REST API exposes resources via unique URLs and uses standard HTTP methods to perform operations.

---

**Q16: Explain the HTTP methods GET, POST, PUT, and DELETE.**
**Ans:**
* [cite_start]**GET:** Retrieve data from the server[cite: 1350].
* [cite_start]**POST:** Send new data to create a resource[cite: 1361].
* [cite_start]**PUT:** Update an existing resource[cite: 1371].
* [cite_start]**DELETE:** Remove a resource[cite: 1379].

---

### **V. React.js (Frontend Framework)**

**Q17: What is JSX?**
[cite_start]**Ans:** JSX (JavaScript XML) is a syntax extension for JavaScript used in React[cite: 53]. [cite_start]It allows you to write HTML-like code directly inside JavaScript files[cite: 1444].

---

**Q18: What are Props in React?**
[cite_start]**Ans:** Props (short for properties) are used to pass data from a parent component to a child component[cite: 1528]. [cite_start]They are read-only and help make components reusable[cite: 54].

---

**Q19: What is `useState` hook used for?**
[cite_start]**Ans:** `useState` is a React Hook that lets you add state variables to functional components[cite: 1571]. It is used to store data that changes over time, causing the component to re-render when updated.

---

**Q20: What is a Single Page Application (SPA)?**
[cite_start]**Ans:** An SPA is a web application that loads a single HTML page and dynamically updates content as the user interacts with the app, without reloading the entire page[cite: 55].

---

### **VI. MongoDB (Database)**

**Q21: What is the difference between SQL and NoSQL databases?**
**Ans:** SQL databases are relational and use tables. [cite_start]NoSQL databases (like MongoDB) are non-relational and store data in flexible formats like collections of documents[cite: 57, 58].

---

**Q22: What is Mongoose?**
[cite_start]**Ans:** Mongoose is a library for MongoDB and Node.js[cite: 1810]. [cite_start]It manages relationships between data, provides schema validation, and translates code objects into representations in MongoDB[cite: 1819].

---

**Q23: How do you connect Node.js to MongoDB?**
[cite_start]**Ans:** We use the `mongoose.connect()` method, passing the database connection string (URI)[cite: 1814]. This returns a promise that resolves when the connection is successful.
