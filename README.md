# 🏗 Kanban Task Manager

## 📌 Overview

This project is a **Kanban-style task manager** that enables users to track tasks efficiently. Initially designed with **Tailwind CSS**, it now includes **JavaScript-powered dynamic task input**,and status validation.

---

## 🎨 UI/UX Development (Last Week)

### **🔹 Tailwind CSS Integration**

- **Responsive Design:** Optimized for **desktop & mobile** with utility classes.
- **Interactive Hover Effects:** Used `hover:scale-101` and `transition-all duration-300` for UI enhancements.
- **Status Indicators:** Color-coded task categories (`TODO`, `DOING`, `DONE`) using `bg-[#49C4E5]`, `bg-[#8471F2]`, and `bg-[#67E2AE]`.
- **Icon & Typography Setup:** Integrated Google Fonts (`Plus Jakarta Sans`) and SVG icons for branding.

### **🔹 Structure & Components**

- **Navbar with Board Navigation**
- **Task Columns grouped by status**
- **Button to trigger task input prompt**

---

## 💻 JavaScript Functionality (Current Update)

### **🔹 Task Input System**

Users can **add new tasks step-by-step** via **Google Chrome prompts**:

- **Title:** Enter task name.
- **Status:** Choose `TODO`, `DOING`, or `DONE` (validation enforced).

### **🔹 Status Validation & Dynamic Task Placement**

- Status **auto-converts to lowercase** for consistency.
- Tasks **appear dynamically** in their respective columns.
- If a status is invalid, users must **re-enter a valid status**.

### **🔹 Local Storage Persistence**

- **Tasks are saved automatically** in `localStorage`.
- When the page reloads, tasks **reappear in their correct columns**.
- Console logs `"No Tasks Completed, let's get to work."` if no tasks are marked `"done"`.

---

## 🛠 Technologies Used

- **HTML5 & Tailwind CSS** → UI Styling & Layout
- **JavaScript** → Task management & local storage
- **Local Storage API** → Data persistence

---

## 📌 Future Improvements

🔹 **Drag-and-Drop Functionality** for moving tasks.  
🔹 **Task Editing & Deletion** options for flexibility.  
🔹 **Backend Integration** for saving tasks permanently.

---

## 🎯 How to Run the Project

1️⃣ **Clone the repository**:

```sh
git clone https://github.com/Sbubz-XI/JSL_02_SBANKO25128_fto2502_b2_Sbabalo-NKompela_JSL02.git
```

2️⃣ Open `index.html` in a browser to test the Kanban board.
