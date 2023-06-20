# Drink Water Tracker

This project is a simple web page that helps you track your water intake by allowing you to select and track the number of glasses of water you have consumed. The goal is to drink 2 liters of water per day.

![Drink Water Tracker](/assets/drink-water.gif)
![WaterImage](/assets/drink-water.png)

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone <https://github.com/hikmetuygur/drink-water.git>`
2. Open the `index.html` file in a web browser.

## Description

The `index.html` file contains the structure of the web page. It includes HTML elements such as `h1`, `h3`, `div`, `p`, and `script` to display the drink water tracker and interactive features.

The CSS styles are defined in the `style.css` file. It sets the background color, font family, and layout properties for the web page. It also includes styles for the cup elements, highlighting them based on the user's interaction.

The JavaScript code in the `script.js` file is responsible for the tracking functionality. It updates the big cup, the remaining amount of water, and the percentage filled based on the cups selected by the user.

## Usage

- The main heading displays "Drink Water" to indicate the purpose of the web page.
- The goals section states the target amount of water to be consumed, which is 2 liters.
- The big cup represents the total amount of water consumed. It shows the remaining amount in liters and a percentage bar that visually indicates the progress.
- The small cups represent individual glasses of water. By clicking on a cup, it fills up and contributes to the total amount consumed. Clicking on a filled cup will empty it.
- The text below the cups instructs the user to select the glasses they have drunk.

## Customization

You can customize the following aspects of the project according to your needs:

- Modify the target amount of water by changing the value in the `<h3>` element.
- Adjust the number of small cups by adding or removing the corresponding HTML elements in the `<div class="cups">` section.
- Customize the styling by modifying the CSS in the `style.css` file.

## Credits

The drink water tracker concept and code implementation were inspired by various online tutorials and examples.

## License

This project is licensed under the [MIT License](LICENSE).

Made from <a href="https://twitter.com/iamleviyn">Leviyn</a> with :heart:
