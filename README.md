# Email Validation Form

A simple HTML, CSS, and JavaScript project that demonstrates client-side email validation.  
The form checks whether the entered email matches a regex pattern and provides instant feedback.

---

## 🚀 Features
- Responsive form layout with a centered container.
- Clean separation of concerns: HTML for structure, CSS for styling, JavaScript for validation.
- Styled input field and submit button with hover effects.
- Real-time email validation using JavaScript and Regular Expressions.
- Error message displayed in red when the email is invalid.
- Success alert and form reset when the email is valid.

---

## 📂 Project Structure
project-root/
│
├── index.html            # Main HTML file (structure + script)
├── style.css              # External CSS file (styling)
└── README.md              # Documentation

Код

---

## 🛠️ Technologies Used
- **HTML5** for structure
- **CSS3** for styling
- **JavaScript (ES6)** for validation logic

---

## 📋 How It Works
1. User enters an email address in the input field.
2. On clicking **Submit**, the JavaScript intercepts the form submission.
3. The email is tested against a regex pattern:
/^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$/

Код
4. If the email is valid:
- Error message is hidden.
- An alert appears: *"Form submitted!"*.
- The form resets.
5. If the email is invalid:
- Error message is displayed in red: *"Please enter valid email"*.

---

## ▶️ Usage
1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Enter an email and test the validation.

---


## 📜 License
This project is open-source and available under the MIT License.
