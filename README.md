# GNF Notation Tool – Greibach Normal Form Validator

## 📌 Project Description
The GNF Notation Tool is an educational web application designed to help students understand and validate Greibach Normal Form (GNF) in Theory of Computation. It provides theoretical explanations, rules, examples, and an interactive grammar validator to check whether given productions follow GNF rules.

## 🎯 Objectives
- Understand the concept of Greibach Normal Form.
- Learn the basic rules and conditions of GNF.
- Identify valid and invalid grammar productions.
- Validate Context-Free Grammar productions easily.
- Provide a simple and interactive learning experience.

## ✨ Features
- **Home Page:** Introduction to Greibach Normal Form.
- **GNF Theory:** Explanation of GNF and its components.
- **GNF Rules:** Important rules for converting grammar into GNF.
- **Examples:** Valid and invalid GNF production examples.
- **GNF Validator:** Enter grammar productions and check their validity.
- **Load Example:** Automatically loads a sample grammar.
- **Clear Option:** Clears the entered grammar and results.
- **Validation Results:** Displays valid or invalid status with explanations.
- **Responsive Design:** Supports different screen sizes.

## 🛠️ Technologies Used
- HTML – Structure of the website.
- CSS – Styling and responsive layout.
- JavaScript – Grammar validation and interactive functionality.

## 📖 What is GNF?
Greibach Normal Form (GNF) is a special form of Context-Free Grammar (CFG) in which every production starts with a terminal symbol.

**General Production Rule:**

`A → aα`

Where:
- A – Non-terminal symbol.
- a – Terminal symbol.
- α – Zero or more non-terminal symbols.

## 💻 Sample Grammar

### Valid GNF Grammar
```text
S -> aAB
A -> bB
B -> c
```

### Invalid GNF Grammar
```text
S -> AB
A -> a
B -> b
```

The production `S -> AB` is invalid because it starts with a non-terminal symbol instead of a terminal.

## 🚀 How to Run the Project
1. Download or clone this repository.
2. Open the project folder.
3. Locate the `gnf.html` file.
4. Open the file in any modern web browser.
5. Navigate through the Theory, Rules, and Examples sections.
6. Enter grammar productions in the Validator section.
7. Click **Check GNF** to view the validation result.
8. Use **Load Example** to test the sample grammar or **Clear** to reset the input.

No additional software installation or server setup is required.

## 📂 Project Structure
```text
GNF-Notation-Tool/
│
├── gnf.html
└── README.md
```

## 🎓 Applications
- Theory of Computation learning.
- Understanding Context-Free Grammars.
- Practicing GNF production rules.
- Academic and laboratory demonstrations.

## 🔮 Future Enhancements
- Automatic conversion of CFG into GNF.
- Support for more complex grammar productions.
- Step-by-step grammar conversion explanations.
- Improved grammar validation and error handling.

## 👩‍💻 Project Information
**Project Name:** GNF Notation Tool  
**Domain:** Theory of Computation  
**Project Type:** Educational Web Application  
**Technologies:** HTML, CSS, JavaScript

## 📜 License
This project is developed for educational and academic purposes.
