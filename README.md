# VIRTUAL-MOBILE-SIMULATOR
This project is a **Virtual Mobile Simulator** built using web technologies that mimics a mobile interface and provides multiple functional apps inside it, including:

✅ Calculator  
✅ Stopwatch  
✅ To-Do List  
✅ Live Clock  
✅ Calendar UI (optional page)

The goal of the project is to simulate a basic smartphone environment in the browser with interactive utilities.

---

## 🌐 Live Features

The simulator includes:

### 🧮 Calculator
A basic calculator that supports:
- Addition
- Subtraction
- Multiplication
- Division
- Clear screen
- Instant evaluation using `eval()`

### ⏱️ Stopwatch
A fully working stopwatch featuring:
- Milliseconds, seconds, minutes tracking
- Start
- Pause
- Reset

Runs using `setInterval()` every 10ms.

### 📝 To-Do List
A simple task management tool:
- Add items
- Edit items
- Delete individual items
- Delete all items

Uses DOM manipulation to dynamically update the list.

### 🕒 Live Clock
Displays the current system time and updates every second.

---

## 🧰 Technologies Used

- HTML
- CSS
- JavaScript (DOM Manipulation)
- setInterval / timers
- Event handling
- Local UI styling

---

## 📂 Project Structure

index.html
calculator.html
stopwatch.html
todo.html
style.css
app.js


`index.html` acts as the main **mobile home screen**, with each widget opening a separate page.

---

## 🚀 How to Run

Simply open:

index.html


in any modern browser.

No installation or server required.

---

## 🖼️ UI Preview

📱 Mobile simulator layout with widgets  
🧮 Functional calculator interface  
⏱️ Stopwatch counters  
📝 Editable task list

---

## 💡 JavaScript Highlights

- `eval()` used for calculator computations
- DOM creation for To-Do items:
```js
var li = document.createElement('li');
var delBtn = document.createElement("button");
Stopwatch timing logic:

js
Copy code
interval = setInterval(timer, 10)
Live clock:

js
Copy code
setInterval(updateTime, 1000)
🚧 Future Improvements
Mobile animations & transitions

Local storage for To-Do list

Scientific calculator mode

UI themes (dark/light mode)

Drag to reorder tasks

App launcher animation
```
📜 License
This project is open-source and free to use.
