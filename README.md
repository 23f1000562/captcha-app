# Captcha Solver Frontend Demo

This project provides a simple, single-page web application to simulate a captcha solver interface. It's designed to demonstrate basic HTML, CSS (using Tailwind CSS), and client-side JavaScript for form interaction.

## Features

-   Displays a static captcha image (`sample.png`).
-   An input field for users to enter the captcha text.
-   A submit button to check the entered text against a predefined correct value.
-   Provides instant feedback on whether the captcha was solved correctly or not.
-   Responsive design ensures usability across various screen sizes.

## Technologies Used

-   **HTML5**: For the basic structure of the web page.
-   **Tailwind CSS**: A utility-first CSS framework for rapid and responsive UI development.
-   **JavaScript**: For handling user input, form submission, and displaying feedback.

## Setup and Usage

1.  **Clone the repository (or save the files locally)**:
    If you received these files directly, ensure `index.html`, `README.md`, and `sample.png` are in the same directory.

2.  **Open `index.html`**: Simply open the `index.html` file in your web browser. There's no build step or server required, as it's a pure client-side application.

3.  **Interact with the Captcha**: Look at the image, type what you perceive to be the text into the input field, and click the "Solve Captcha" button. The correct captcha text for this demo is "ADORS".

## Project Structure

-   `index.html`: The main HTML file containing the application's structure, styling (via Tailwind CDN), and JavaScript logic.
-   `sample.png`: The captcha image displayed on the page.
-   `README.md`: This file, providing information about the project.
-   `LICENSE`: The MIT License file.

## Customization

-   **Captcha Image**: Replace `sample.png` with your own image and update the `src` attribute in `index.html` if desired.
-   **Correct Captcha Value**: Modify the `correctCaptcha` variable in the JavaScript section of `index.html` to change the expected solution.
-   **Styling**: All styling is done with Tailwind CSS classes directly in `index.html`. You can easily adjust colors, sizes, and layouts by modifying these classes.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.