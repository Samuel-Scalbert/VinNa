
---

# 📘 `README.md`


---

## 🚀 Getting Started

### 1️⃣ Prerequisites

Make sure you have **Node.js (LTS)** installed:

```bash
node -v
npm -v
```

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/Samuel-Scalbert/VinNa.git
cd VinNa
```

---

### 3️⃣ Install Dependencies

```bash
npm install
```

This installs:

* `tailwindcss`
* `@tailwindcss/cli`

---

### 4️⃣ Build Tailwind CSS

Run Tailwind in watch mode:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

This will:

* Compile Tailwind CSS
* Automatically rebuild on file changes

Leave this running while developing.

---

### 5️⃣ Open the Website

Open `src/index.html` in your browser
(or use **Live Server** in VS Code).

---

## 🎨 Tailwind Setup (v4)

### `src/input.css`

```css
@import "tailwindcss";
```

Tailwind v4 does **not** require a config file by default.

---

## 🌍 Deployment

This site is fully static and can be deployed on:

---

## 📝 License

This project is private and intended for personal use.

````