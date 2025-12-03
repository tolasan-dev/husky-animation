# Live Sass Compiler Setup Guide

## 1️⃣ Install the Live Sass Compiler Extension

Inside **VS Code**:

1. Click the **Extensions** icon (left sidebar).
2. In the search bar, type:

```
Live Sass Compiler
```

3. Install this extension:

- **Author:** Ritwick Dey  
- **Logo:** Blue-purple  
- **Name:** *Live Sass Compiler*  

---

## 2️⃣ Rename Your CSS File to SCSS

If your file is:

```
styles.css
```

Rename it to:

```
styles.scss
```

**How to rename:**

- Right-click the file → **Rename**
- Change `.css` → `.scss`

---

## 3️⃣ Start the SCSS Compiler

After installing the extension:

- Look at the **bottom status bar** in VS Code.
- You will see a button:

```
Watch Sass
```

Click it.

---

## 4️⃣ VS Code Automatically Creates CSS Output

After clicking **Watch Sass**, two new files are generated:

```
styles.css
styles.css.map
```

### ✔ What these files mean:

- **styles.css** → The compiled CSS used in your HTML  
- **styles.css.map** → Used for debugging  
- VS Code watches your SCSS and updates CSS automatically on save.

---

## 5️⃣ Link the Compiled CSS in Your HTML

Use this in your HTML:

```html
<link rel="stylesheet" href="styles.css">
```

---

You're all set! 🎉  
SCSS → CSS automatically every time you save.

