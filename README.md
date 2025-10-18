# Interactive Contact Form & To-Do List (HTML, CSS, JavaScript)
## Project Overview

This project demonstrates how to build a responsive web page using HTML, CSS (Flexbox & Grid), and JavaScript.
It includes a Contact Form with input validation and a Dynamic To-Do List that allows users to add and remove tasks interactively.

This is an ideal beginner-friendly project for learning frontend web development, DOM manipulation, and responsive design.

 ## Objectives

The project is divided into structured learning objectives and practical tasks:

🧩 Task 1: Create a Contact Form

Objective:
Build a contact form with various input fields.

Actions:

Use HTML to create form fields (Name, Email, Message).

Apply CSS for layout, padding, and design styling.

🧠 Task 1.1: Add JavaScript Form Validation

Objective:
Ensure form data is valid before submission.

Actions:

Check if all fields are filled.

Validate email format using a regular expression.

Display appropriate error messages.

🧱 Task 2: Create a Responsive Layout using Flexbox & CSS Grid

Objective:
Design a layout that adapts to different screen sizes.

Actions:

Use Flexbox for navigation alignment.

Use CSS Grid for organizing content areas.

Apply media queries to make the page mobile-friendly.

⚙️ Task 3: DOM Manipulation with JavaScript

Objective:
Learn how to dynamically modify the webpage using JavaScript.

Actions:

Create a To-Do List that allows adding and removing tasks.

Handle dynamic UI updates using DOM manipulation.

🗓️ Project Timeline (9 Days Plan)
Day	Focus	Description
Day 1-2	HTML	Create webpage structure and contact form.
Day 3-4	CSS	Style form, navigation, and sections.
Day 5	Responsive Design	Add Flexbox, Grid, and media queries.
Day 6-7	JavaScript	Implement form validation logic.
Day 8-9	DOM Manipulation	Build the interactive To-Do List feature.
🛠️ Technologies Used

HTML5 – For structure and layout.

CSS3 (Flexbox & Grid) – For styling and responsive design.

JavaScript (ES6) – For form validation and dynamic DOM updates.

📁 Project Structure
📦 interactive-contact-todo
│
├── index.html            # Main HTML file
├── style.css             # CSS styling (if separated)
├── script.js             # JavaScript validation & DOM logic
└── README.md             # Project documentation

🚀 Steps to Create This Project
Step 1: Setup the Project Folder

Create a new folder, e.g., interactive-contact-todo.

Inside it, create the following files:

index.html

style.css

script.js

Step 2: Build the HTML Structure

Create a header and navigation bar using <header> and <nav>.

Add two sections inside <main>:

Contact Form Section

To-Do List Section

Use semantic HTML tags like <form>, <input>, <textarea>, and <button>.

Step 3: Style with CSS

Use Flexbox to align navigation items horizontally.

Use CSS Grid to place contact form and to-do list side by side.

Style input fields, buttons, and sections for a clean look.

Add media queries for smaller screens.

Example snippet:

main {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}
@media (max-width: 768px) {
  main {
    grid-template-columns: 1fr;
  }
}

Step 4: Add Form Validation (JavaScript)

Prevent form submission if fields are empty.

Use a regex pattern to check valid email format.

Display error messages if validation fails.

Example snippet:

if (!email.match(/^[^ ]+@[^ ]+\.[a-z]{2,3}$/)) {
  errorMsg.textContent = "⚠️ Invalid email format!";
  return;
}

Step 5: Implement To-Do List (DOM Manipulation)

Select input and button elements using document.getElementById().

Create new <li> elements dynamically using document.createElement().

Append new tasks to the list and allow deletion using remove().

Example snippet:

const li = document.createElement('li');
li.textContent = taskText;
const deleteBtn = document.createElement('button');
deleteBtn.textContent = "Delete";
deleteBtn.onclick = () => li.remove();
li.appendChild(deleteBtn);
todoList.appendChild(li);

Step 6: Make it Interactive and Responsive

Test on different devices (mobile, tablet, desktop).

Adjust grid and flex layouts with media queries.

Refine the design and test validation messages.

🌟 Features

✅ Responsive layout using Flexbox and Grid
✅ Validated contact form with real-time feedback
✅ Interactive To-Do list using DOM manipulation
✅ Clean UI and mobile-friendly design
✅ Beginner-friendly and fully documented

🧠 Learning Outcomes

By completing this project, you’ll understand:

How to structure webpages using semantic HTML.

How to design flexible, responsive layouts using CSS Grid and Flexbox.

How to validate form data using JavaScript.

How to manipulate the DOM to build dynamic interfaces.
