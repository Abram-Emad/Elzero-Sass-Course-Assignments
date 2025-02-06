# Elzero Sass Course Assignments

![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

This repository contains solutions to assignments from the **Elzero Sass Course**, demonstrating practical implementations of Sass (Syntactically Awesome Style Sheets) concepts. The assignments focus on leveraging Sass features to create maintainable and efficient CSS workflows.

## 📌 Overview

The project includes multiple assignments covering fundamental to intermediate Sass topics such as:
- Variables, nesting, and operators
- Mixins, functions, and control directives
- Modular architecture with partials
- Advanced features like maps and loops

Each assignment is a self-contained project with HTML and Sass (SCSS) files, showcasing real-world applications of Sass in web development.

## ✨ Features

- **Sass-Powered Styling**: Utilizes Sass features for cleaner and DRY (Don't Repeat Yourself) CSS.
- **Responsive Design**: Assignments include responsive layouts using modern techniques.
- **Modular Structure**: Organized with partials and separated components.
- **Dynamic Styling**: Demonstrates dynamic theming, conditional styling, and reusable mixins.
- **Build Tools**: Integrated with `node-sass` for compiling SCSS to CSS.

## 🛠 Technologies

- **HTML5**: Semantic markup for all assignments.
- **Sass (SCSS)**: Primary styling preprocessor.
- **npm Scripts**: Automated Sass compilation via `node-sass`.
- **Git**: Version control and workflow management.

## 📦 Installation

1. **Clone the Repository**:
   bash
   git clone https://github.com/Abram-Emad/Elzero-Sass-Course-Assignments.git
   cd Elzero-Sass-Course-Assignments
   

2. **Install Dependencies**:
   bash
   npm install
   

3. **Compile Sass**:
   - Run the watch script to automatically compile SCSS to CSS:
     bash
     npm run watch
     

## 🚀 Usage

1. After running `npm run watch`, any changes to `.scss` files in the `scss` directory will compile to `css/styles.css`.
2. Open the HTML files directly in a browser (e.g., using VS Code's Live Server extension) to view assignments:
   - **Assignment 01**: `assignment-01/index.html`
   - **Assignment 02**: `assignment-02/index.html`
   - *(Continue for other assignments)*

## 📂 Project Structure


- Elzero-Sass-Course-Assignments/
- ├── assignments/              # Individual assignments
- │   ├── assignment-01/        # Assignment 1 files
- │   │   ├── index.html
- │   │   └── scss/
- │   ├── assignment-02/
- │   │   ├── index.html
- │   │   └── scss/
- │   └── ...                   # Additional assignments
- ├── css/                      # Compiled CSS
- │   └── styles.css
- ├── scss/                     # Global Sass source files
- │   ├── _variables.scss
- │   ├── _mixins.scss
- │   └── styles.scss
- ├── package.json
- └── README.md


## 📚 Assignments List

- | Assignment | Topics Covered                                                                 |
- |------------|--------------------------------------------------------------------------------|
- | 01         | Sass basics: variables, nesting, and file structure                           |
- | 02         | Mixins, operators, and responsive design                                      |
- | 03         | Advanced functions and control directives (`@if`, `@for`)                     |
- | 04         | Modular architecture with partials and component-based styling                |
- | 05         | Dynamic theming using maps and loops                                          |
- | ...        | *(Additional assignments as per course progression)*                          |

## 🤝 Contributing

Contributions are welcome! If you find issues or have improvements:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/improvement`).
3. Commit changes (`git commit -m 'Add improvement'`).
4. Push to the branch (`git push origin feature/improvement`).
5. Open a Pull Request.

## 🙏 Credits

- **Elzero Web School**: Original course and assignments ([YouTube Channel](https://www.youtube.com/c/ElzeroInfo)).
- **Abram Emad**: Assignment solutions and repository maintenance.

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
