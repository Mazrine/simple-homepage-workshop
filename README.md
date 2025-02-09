# **README.md**

````md
# (✿◕‿◕) Simple Homepage Workshop

Welcome to this beginner-friendly workshop! Here, you will learn the basics of **HTML** and **CSS** by creating a simple homepage. Let's get started! (＾ ▽ ＾)

---

## 📌 Workshop Overview

By the end of this workshop, you will have built a simple webpage with:

- A structured HTML layout ٩(｡•́‿•̀｡)۶
- Basic CSS styling (ノ ◕ ヮ ◕)ノ\*:・゚ ✧
- A navigation menu ┐(￣ヮ￣)┌
- A footer section (￣ ω ￣)

---

## 🛠️ Setup Instructions

### 1️⃣ **Clone this repository**

Open your terminal or command prompt and run:

```sh
git clone https://github.com/YOUR-USERNAME/simple-homepage-workshop.git
cd simple-homepage-workshop
```
````

ヾ(＾ ∇ ＾)

## 2️⃣ **Open the project in a code editor**

We recommend using [VS Code](https://code.visualstudio.com/). (¬‿¬)

### 3️⃣ **Open `index.html` in a browser**

- Double-click the `index.html` file, or
- Use VS Code Live Server (if installed).  
  ヽ(•‿•)ノ

---

## 📄 File Structure

```text
simple-homepage-workshop/
├── index.html   # Main HTML file
├── styles/
│   ├── style.css  # CSS styles for the homepage
├── images/  # (Optional) Folder for images
├── README.md  # This file
```

(─‿‿─)

---

## 🏗️ Step-by-Step Guide

## 📌 1. Creating the HTML Structure

Open `index.html` and write the following code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Homepage</title>
    <link rel="stylesheet" href="styles/style.css" />
  </head>
  <body>
    <header>
      <h1>Welcome to My Homepage</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

    <main>
      <section>
        <h2>About Me</h2>
        <p>This is a simple homepage created using HTML and CSS.</p>
      </section>
    </main>

    <footer>
      <p>© 2025 My Homepage</p>
    </footer>
  </body>
</html>
```

(ノ^\_^)ノ

### 🔹 What’s happening here?

- **`<html>`**: The root of the document. (๑•́ ₃ •̀๑)
- **`<head>`**: Contains metadata like the page title. ヽ( ￣ д ￣)ノ
- **`<body>`**: The visible part of the webpage. (¬‿¬)
- **`<header>`**: Contains the website title. ᕙ(⇀‸↼‶)ᕗ
- **`<nav>`**: Navigation bar with links. (￣ o ￣) . z Z
- **`<main>`**: Main content section. (▰˘◡˘▰)
- **`<footer>`**: Footer with copyright info. ヽ( °◇°)ノ

---

## 🎨 2. Styling with CSS

Now, open `styles/style.css` and add the following styles:

```css
/* Apply styles to the whole page */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

/* Header styles */
header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

/* Navigation menu */
nav ul {
  list-style: none;
  padding: 0;
  text-align: center;
  background-color: #444;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
}

/* Main content */
main {
  padding: 20px;
  text-align: center;
}

/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
  position: absolute;
  width: 100%;
  bottom: 0;
}
```

＼(￣ ▽ ￣)／

### 🔹 What’s happening?

- We style the **body** with a background color. (ʘ‿ʘ)
- The **header** and **footer** have a dark background with white text. (─‿‿─)
- The **nav bar** has links styled without underlines. ( ͡° ͜ʖ ͡°)
- The **main section** has some padding for readability. (¬‿¬)

---

## 🌟 3. Adding Interaction (Optional)

You can add a simple hover effect to highlight navigation links: (¬‿¬)

```css
nav a:hover {
  color: yellow;
}
```

Or a **button** that shows an alert when clicked: (∩^o^)⊃━☆

```html
<button onclick="alert('Hello!')">Click Me</button>
```

---

## 🌐 4. Hosting with GitHub Pages

Want to put your homepage online? Follow these steps:

1. Go to your **GitHub repository**.
2. Navigate to **Settings > Pages**.
3. Under "Source," select the `main` branch and click **Save**.
4. Your website will be available at:

   ```text
   https://your-username.github.io/simple-homepage-workshop/
   ```

(⌐■_■)

---

## 🎯 Next Steps

- Try changing the **colors** and **fonts**. (づ￣ ³ ￣)づ
- Add an **image** to your homepage. (─‿‿─)
- Experiment with **CSS animations**. (＾ ▽ ＾)

Happy coding! ヾ(≧▽≦\*)o
