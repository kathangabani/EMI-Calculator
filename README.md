
# EMI Calculator

This project provides an EMI (Equated Monthly Installment) calculator using HTML, CSS, JavaScript, and Vue.js. It allows users to calculate the EMI for various loan parameters such as loan amount, interest rate, and tenure.

## Features
- Calculate EMI based on loan amount, interest rate, and tenure.
- Display EMI amount, total interest, and total payment over the loan period.
- Simple and user-friendly interface built using HTML, CSS, and JavaScript.

## Setup & Installation

### Prerequisites
- A modern web browser (Google Chrome, Firefox, etc.)

### Running the Application
1. **Clone the repository:**
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/kathangabani/EMI-Calculator.git
   cd EMI-Calculator-main
   ```

2. **Open in Browser:**
   - Open the `index.html` file in your preferred web browser.
   
   ```bash
   open index.html
   ```

   The application should now be accessible in your browser.

## Code Overview

### Files
- **index.html**: The main HTML file for the EMI calculator interface.
- **styles.css**: The CSS file for styling the application.
- **app.js**: The JavaScript file containing the logic for EMI calculation.
- **EMI-Logo.png**: Logo image for the application.
- **EMI.mp4**: A demo video of the EMI calculator.
- **LICENSE**: The license file for the project.
- **README.md**: The markdown file you are reading.

### Core Functionality
1. **EMI Calculation**: The application calculates the EMI using the formula:
   \[
   EMI = rac{{P 	imes r 	imes (1 + r)^n}}{{(1 + r)^n - 1}}
   \]
   Where:
   - \(P\) = Loan amount
   - \(r\) = Monthly interest rate (annual rate / 12)
   - \(n\) = Number of months (loan tenure)

2. **Result Display**: The application displays the EMI, total interest, and total payment.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
