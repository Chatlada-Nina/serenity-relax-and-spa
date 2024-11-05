# Serenity Relax&Spa - Testing

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [HTML](#w3c-validator)
  * [CSS](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Full Testing](#full-testing)

## AUTOMATED TESTING

### HTML 
- I used [W3C Markup Validation Service](https://validator.w3.org/) to check and validate the HTML code.

  - [index.html](/documentation/readme/index-validator-results.png) - Passed.
  - [programs.html](/documentation/readme/programs-validator-results.png) - Passed.
  - [booking.html](/documentation/readme/Booking-validator-results.png) - Passed.
  - [success.html](/documentation/readme/success-validator-results.png) - Passed.

### CSS 
- I used [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) to check and validate the CSS code.

  - [style.css](/documentation/readme/CSS-validator-results.png) - Passed, no errors found.

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility and best practices of the website.

![index.html]()

![programs.html]()

![booking.html]()

![success.html]()

## MANUAL TESTING

### Full Testing

Full testing was performed on the following devices:

* Laptop:
  * Macbook Air 2021 13 inch screen
* Mobile Devices:
  * iPhone 13
  * Samsung galaxy 

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Firefox

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites logo | Link directs the user back to the home page | Clicked logo | Home page reloads | Pass |
| How to play button | Displays the modal with the instructions on how to play the game | Clicked on button | Modal with instructions on how to play opens | Pass |
| Modal close button | Closes the modal | Clicked on close button | Modal closed | Pass |
| Play Button | Directs the user to the game page | Clicked on button | Game page opens to display the difficulty selections | Pass |
| High Scores Button | Directs the user to the high scores page | Clicked on button | Directs to the high scores page | Pass |
| All buttons - hover effect | All black buttons with white text should change to white with black text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| 🍺 Cursor | The 🍺 should display when a user moves the mouse over a button | Moved the mouse over each button to check the cursor changed upon entering the button | The cursor changed from the arrow cursor to the 🍺 cursor | Pass |