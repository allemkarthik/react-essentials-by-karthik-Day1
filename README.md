# react-essentials-by-karthik-Day1
# 🚀 React Fundamentals Series

Welcome to the **React Fundamentals Series** — a simple and practical guide to understanding the core concepts of React.  
This series is designed to help anyone build a solid foundation in React, one day at a time.

---

## 📚 Day 1: React Basics

### Topics Covered
1️⃣ Integrating React into a Project  
2️⃣ Understanding CORS  
3️⃣ Introduction to CDN  
4️⃣ Rendering in React  
5️⃣ Working with Props  

---

### 💡 Overview

- **Integrating React:** Learn how to add React to a simple HTML project using CDN links.  
- **CORS:** Understand why browsers restrict cross-origin requests and how React handles them.  
- **CDN:** Explore how CDNs help in faster and efficient delivery of libraries like React.  
- **Rendering:** See how React renders components efficiently in the browser.  
- **Props:** Pass data between components and make them reusable.

---

### 🧠 Example Snippet

```html
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

<div id="root"></div>

<script>
  function Welcome(props) {
    return React.createElement("h2", {}, `Hello, ${props.name}!`);
  }

  const root = ReactDOM.createRoot(document.getElementById("root"));
  root.render(React.createElement(Welcome, { name: "Karthik" }));
</script>

