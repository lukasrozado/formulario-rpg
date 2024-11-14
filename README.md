
##  A RPG Game Survey Form

This project is a survey form designed to collect information from RPG players about their game preferences. The form uses HTML and inline CSS to provide a simple, pleasant interface.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Technologies Used](#technologies-used)
4. [How to Use](#how-to-use)
5. [Features](#features)
6. [HTML Structure](#html-structure)
7. [CSS Styling](#css-styling)
8. [Usage Example](#usage-example)
9. [Contributing](#contributing)
10. [License](#license)
11. [Authors and Acknowledgments](#authors-and-acknowledgments)

---

## Introduction

The **A RPG Game Survey Form** allows users to provide basic information, select their game preferences, and share opinions about their favorite types of RPGs. The CSS is embedded directly in the HTML file, eliminating the need for an external CSS file.

This form is designed to be responsive and mobile-friendly, ensuring a good experience across different devices.

## Project Structure

This project consists of a single HTML file that includes embedded CSS for styling. This setup makes the project easy to transfer and use anywhere without additional dependencies.

### File Structure` 

├── main.html # Main HTML file with embedded CSS └── README.md # Project documentation

markdown

Copiar código

 `## Technologies Used

- **HTML5**: For semantic content structure.
- **CSS3**: For form styling, embedded directly within the HTML.

## How to Use

1. Clone the repository or download the project:
   ```bash
   git clone https://github.com/your-username/your-repository.git` 

2.  Open the `main.html` file in a browser of your choice to view and interact with the form.

## Features

-   **Input Fields**:
    -   First and last name.
    -   Age (minimum of 12, maximum of 120).
    -   Email (required field).
    -   Referrer (selection of where they heard about the game).
-   **Radio Buttons**:
    -   RPG type options: tabletop or online.
-   **Textarea**:
    -   Field for users to describe their game preferences.
-   **Checkboxes**:
    -   Options to accept terms and choose to receive email updates.
-   **Submit Button**:
    -   A styled button that submits the form information.

## HTML Structure

The form is structured using HTML5 and includes the following main elements:

-   `<h1 id="title">`: Main title of the form.
-   `<p id="description">`: Short description explaining the purpose of the form.
-   `<form id="survey-form">`: Main survey form with fields organized inside a `<fieldset>`:
    -   **Text fields**: First and last name.
    -   **Numeric field**: Age.
    -   **Email field**: Email.
    -   **Dropdown (`<select>`)**: Referrer.
    -   **Radio buttons**: Preferred RPG type.
    -   **Textarea**: For additional comments from the user.
    -   **Checkboxes**: Accept terms and opt-in for updates.
    -   **Submit button (`<input type="submit">`)**.

## CSS Styling

The embedded CSS defines the layout and appearance of the form with the following main rules:

-   **Basic Reset**: Removes default margins and paddings and sets a default font.
-   **Body**: Centers content with a light gray background.
-   **Title and Description**: Centered with adequate spacing for visual separation.
-   **Form**: White background with rounded borders and a slight shadow to make it stand out.
-   **Input Fields**: Full width with borders and padding for user-friendly interaction.
-   **Submit Button**: Green background with a hover effect that darkens when the mouse hovers over it.

## Usage Example

Below is a preview of the complete form:

Users can fill out the form with their information and preferences. By clicking "Submit," the information will be submitted (no back-end processing in this project).

## Contributing

Contributions are welcome! To contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your changes (`git checkout -b my-new-feature`).
3.  Commit your changes (`git commit -am 'Add new feature'`).
4.  Push to the branch (`git push origin my-new-feature`).
5.  Open a Pull Request for review.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author

-   **Author**: [Lukas Rozado](https://github.com/lukasrozado/)`
