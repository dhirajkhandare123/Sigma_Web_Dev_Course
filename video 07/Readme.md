# 📌 HTML Form Elements

---

## 📖 Introduction
**HTML Forms** are used to collect user input on a webpage.  

They allow users to enter data like **name, email, password, feedback, etc.** and send it to a server for processing.

👉 **Why Forms are important?**
- Collect user data 📋  
- Enable login & signup 🔐  
- Allow user interaction 💬  

---

## ✨ Key Features / Concepts

| Element | Description |
|--------|------------|
| `<form>` | Container for all form elements |
| `<input>` | Used to take input (text, password, etc.) |
| `<label>` | Describes input fields |
| `<textarea>` | Multi-line input |
| `<select>` | Dropdown list |
| `<option>` | Items inside dropdown |
| `<button>` | Submit or perform actions |

---

## 🧠 Syntax / Basic Structure

```html
<form action="server_url" method="POST">
    
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <button type="submit">Submit</button>

</form>