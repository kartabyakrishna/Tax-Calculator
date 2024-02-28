# Tax-EMI Calculator App

Welcome to the Tax-EMI Calculator app repository! This simple Android app allows users to calculate their income tax based on income input and also estimate their monthly loan EMI. Below, you'll find information on the app's features, logic for income tax calculation, EMI calculation, and how to use it.

## Features

- **Income Tax Calculation:** Input your annual income, and the app will calculate the applicable income tax based on predefined slabs.
- **EMI Calculation:** Estimate your monthly loan EMI by providing the principal amount, interest rate, and loan tenure in years.

## How to Use

### Income Tax Calculation
1. Enter your annual income in the provided field.
2. Click the "Calculate" button.
3. The app will display the calculated tax and total income (including tax).

### EMI Calculation
1. Enter the principal amount, interest rate, and loan tenure in years.
2. Click the "Calculate EMI" button.
3. The app will display the calculated EMI and total interest paid over the loan tenure.

## Logic

### Income Tax Calculation
- The income tax is calculated based on predefined slabs:
  - 5% for income between 200,000 and 1,000,000.
  - 10% for income between 1,000,000 and 2,000,000.
  - 15% for income between 2,000,000 and 3,000,000.
  - 20% for income between 3,000,000 and 4,000,000.
  - 25% for income between 4,000,000 and 5,000,000.
  - 30% for income between 5,000,000 and 7,000,000.
  - 35% for income between 7,000,000 and 10,000,000.
  - 40% for income exceeding 10,000,000.

### EMI Calculation
- The EMI is calculated using the formula for Equated Monthly Installment (EMI): 
  `EMI = [P * r * (1 + r)^n] / [(1 + r)^n - 1]`
  where P is the principal amount, r is the monthly interest rate, and n is the number of monthly installments.

## Installation

- The latest APK can be found in the `apks` folder. Download and install it on your Android device.

## Demo Video

- Here's a quicl demonstration of the app,
![Demo](https://github.com/kartabyakrishna/KartabyaKrishna/blob/main/Assets/tax-calculator/taxCal%20-%20Demo.gif | width=400)

Feel free to use, contribute, and provide feedback! If you encounter any issues or have suggestions, please open an issue in the repository.

Happy calculating! 🧮📱