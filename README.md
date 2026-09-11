# MLCoE Recruitment Registration Form

A modern, cyberpunk-inspired recruitment registration page for the
**Machine Learning Centre of Excellence (MLCoE)**. The project is built
using **HTML and CSS** and provides a responsive-looking registration
interface with event details, domain selection, and a futuristic visual
design.

## 📌 Project Overview

This project is a recruitment registration form designed for the MLCoE
recruitment event. It combines:

-   A dark futuristic/cyber-themed UI
-   MLCoE branding and navigation
-   Event information section
-   Student registration form
-   Gender selection
-   Date of birth, branch, and residence fields
-   Domain selection
-   Declaration checkbox
-   Registration button
-   Cyber-themed footer

## 🛠️ Technologies Used

-   **HTML5** -- Page structure and form elements
-   **CSS3** -- Styling, layout, backgrounds, gradients, blur effects,
    and responsive UI
-   **Local Assets** -- MLCoE logo and background image

## 📂 Project Structure

``` text
project-folder/
│
├── index.html
├── style.css
│
└── assets/
    ├── nav-logo.png
    └── bgimg.png
```

> Make sure the `assets` folder contains the required images and that
> the file names match the paths used in `index.html`.

## ✨ Main Features

### 1. Navigation Header

The header contains:

-   MLCoE logo
-   Contact link

The navigation uses a dark, minimal design that matches the overall
theme.

### 2. Event Information

The left section presents:

-   Event title
-   Recruitment domains
-   Date
-   Time
-   Venue

Current event details shown in the page:

**Date:** 26th July 2026\
**Time:** 4:00 PM\
**Venue:** CSE Labs, 4th Floor, CSIT

### 3. Recruitment Domains

The available domains are:

-   **Machine Learning**
    -   Gen AI
    -   Agentic AI
-   **Web Development**
    -   Frontend
    -   Backend
-   **Designing**
    -   UI
    -   Motion

### 4. Registration Form

The form collects:

-   Full Name
-   Student Number
-   Roll Number
-   College Email
-   Phone Number
-   Gender
-   Date of Birth
-   Branch
-   Residence
-   Domain Applying For
-   Declaration/Agreement

### 5. Futuristic UI

The design uses:

-   Dark background
-   Blue and purple accent colors
-   Transparent backgrounds
-   Blur effects
-   Gradient registration button
-   Rounded cards
-   Letter spacing and uppercase labels
-   Cyber/neural-themed footer

## 🎨 Design Highlights

The page uses CSS features such as:

``` css
backdrop-filter: blur(10px);
```

for the glass-like form container, along with gradients such as:

``` css
background: linear-gradient(90deg, #668cff, #9149d5);
```

for the registration button.

The background image is applied using:

``` css
background-image: url("assets/bgimg.png");
background-size: cover;
background-position: center;
background-attachment: fixed;
```

## 🚀 How to Run

### Option 1: Open Directly

1.  Download or clone the project.
2.  Make sure `index.html`, `style.css`, and the `assets` folder are in
    the correct locations.
3.  Open `index.html` in a web browser.

### Option 2: Using VS Code

1.  Open the project folder in **Visual Studio Code**.
2.  Install the **Live Server** extension if you have it.
3.  Right-click `index.html`.
4.  Select **Open with Live Server**.

The registration page will open in your browser.

## ⚠️ Current Limitations

The current project is primarily a **frontend UI**.

The form currently does not include:

-   Backend/database integration
-   Form submission API
-   Input validation logic
-   Actual gender/domain state handling
-   Authentication
-   Email verification
-   Persistent storage

The buttons and form fields can be connected to JavaScript and a backend
later.

## 🔮 Future Improvements

Possible improvements include:

-   Add JavaScript form validation
-   Make gender buttons selectable
-   Make domain cards selectable
-   Add required-field validation
-   Connect the form to a backend
-   Store registrations in a database
-   Add success/error messages
-   Add loading animation during submission
-   Improve mobile responsiveness
-   Add accessibility improvements
-   Add a working Contact page
-   Add form submission using an API

## 👨‍💻 Author

**Ashish Kumar**

Developed as an MLCoE recruitment registration frontend project.
