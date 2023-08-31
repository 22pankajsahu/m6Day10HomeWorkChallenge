# Background Color Changer

This is a basic website that demonstrates how JavaScript functionality is utilized to change the background color of a webpage by clicking a button. The webpage consists of a single button that triggers the color change when clicked.

## Table of Contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Author](#author)
- [License](#license)

## Introduction

The **Background Color Changer** is a simple web application that allows users to change the background color of the webpage by clicking a button. The webpage utilizes HTML, CSS, and JavaScript to achieve this functionality.

## Demo

You can see a live demo of the project [here](https://22pankajsahu.github.io/m6Day10HomeWorkChallenge/).

## Screenshots

Include relevant screenshots of the application here.

![image](https://github.com/22pankajsahu/m6Day10HomeWorkChallenge/assets/135128502/ad80b546-0491-4d14-928d-243e40a5630a)

![image](https://github.com/22pankajsahu/m6Day10HomeWorkChallenge/assets/135128502/63278959-2535-4de9-bb2f-717d4c7f3d61)



## Technologies Used

- HTML
- CSS
- JavaScript

## How It Works

1. The HTML structure includes a `<button>` element with the id `colorButton`. This button is responsible for triggering the background color change.

2. The CSS styles define the appearance of the button and the layout of the webpage. The button is initially styled with a background color of `#2c3e50` and changes to a slightly darker shade with a subtle scale effect when hovered over.

3. The JavaScript code is enclosed within a `DOMContentLoaded` event listener to ensure that the code runs after the DOM is fully loaded.

4. The `generateRandomColor()` function generates a random color by selecting six random characters from the set of letters and numbers (`0123456789ABCDEF`) used in hexadecimal color codes. It then appends these characters to the `"#"` symbol to form a valid color code.

5. When the `colorButton` is clicked, the `generateRandomColor()` function is called to generate a random color. The generated color is then applied as the background color of the `document.body` element using the `document.body.style.backgroundColor` property.

## Author

My name is PANKAJ SAHU i am the owner of this repository. It is My geekster's m6 Day9 Class Challenge Project.

If you have any questions, suggestions, or feedback, you can reach out to the project maintainer:

 Name : [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu-) <br>
 Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)


## License

This project is licensed under the [MIT License](LICENSE).
