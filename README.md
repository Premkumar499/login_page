# 🛍️ Shop - Login & Registration Page

A clean, responsive shopping authentication interface built using **HTML, CSS, and JavaScript**. ShopPi provides a simple user interface for signing in, creating an account, toggling password visibility, and accessing a password-reset flow.

## 📌 Overview

ShopPi is a frontend project designed to demonstrate the fundamentals of building an authentication interface for an e-commerce website. It features a modern card layout, a shopping-themed background, styled form controls, and interactive login and registration forms.

## ✨ Features

- **Login Form** — Enter an email address and password.
- **User Registration** — Collect first name, last name, email, and password.
- **Password Visibility Toggle** — Show or hide password fields.
- **Password Confirmation** — Check whether the password and confirmation match.
- **Form Validation** — Use HTML validation and JavaScript checks for required fields and minimum password length.
- **Forgot Password Interface** — Simulate a password-reset request.
- **Form Switching** — Switch between login and registration without reloading the page.
- **Modern UI** — Rounded corners, subtle shadows, transitions, and a shopping-themed design.

## 🧰 Tech Stack

- **HTML5** — Page structure and form elements.
- **CSS3** — Styling, layout, background image, and hover effects.
- **JavaScript** — Form interactions, validation, and password visibility.
- **Font Awesome 6** — Password visibility icons.
- **Unsplash** — Background image.

## 📂 Project Structure

```text
ShopPi/
├── index.html
├── login.css
├── login.js
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- A code editor such as Visual Studio Code.
- Optional: the Live Server extension for VS Code.

### 1. Clone the repository

Replace the placeholder URL with your actual GitHub repository URL.

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### 2. Open the project

Make sure the HTML, CSS, and JavaScript files are in the same directory.

```text
index.html
login.css
login.js
```

### 3. Run the application

Open `index.html` directly in your browser, or use the Live Server extension in VS Code.

No build tools or package installation are required for this frontend-only version.

## 🖥️ How to Use

1. Open the page to access the login form.
2. Enter your email and password.
3. Select the eye icon to toggle password visibility.
4. Click **Sign Up** to open the registration form.
5. Enter your first name, last name, email, password, and password confirmation.
6. Submit the form to test the registration interaction.
7. Use **Sign In** to return to the login form.
8. Select **Forgot your password?** to test the password-reset prompt.

## 🎨 UI Design

The interface includes:

- A coral-red header and action buttons.
- A centered authentication card.
- A shopping-themed background image.
- Styled input fields with focus effects.
- Interactive password visibility icons.
- Separate login and registration views.

## 🔒 Security Notes

This project currently demonstrates **frontend authentication UI only**.

- Login and registration submissions are handled on the client side.
- No backend authentication or database integration is included in the provided code.
- Passwords are not securely authenticated or stored.
- The password-reset interaction only simulates a request.
- Do not use this implementation to protect real user accounts without a secure backend.

For production use, integrate a backend authentication service, securely hash passwords, validate inputs on the server, use HTTPS, and implement a real password-reset workflow.

## 🛣️ Future Improvements

- Integrate a backend using Node.js and Express or Spring Boot.
- Add database support using PostgreSQL or MongoDB.
- Implement secure user registration and login.
- Add email verification and password-reset functionality.
- Display inline validation and error messages.
- Improve mobile responsiveness and accessibility.
- Add automated frontend and authentication tests.

## 👨‍💻 Author

**Prem Kumar**

B.Tech — Artificial Intelligence and Data Science

GitHub: [@Premkumar499](https://github.com/Premkumar499)

## 📄 License

No license has been specified. Add a `LICENSE` file if you intend to distribute this project under an open-source license.

---

⭐ If you find this project useful, consider starring the repository!
