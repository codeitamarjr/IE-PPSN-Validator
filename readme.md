# PPSN Validator

## Overview

The PPSN Validator is a simple web application designed to validate Irish Personal Public Service Numbers (PPSNs). The validator checks if a PPSN is correctly formatted and calculates the check digit to ensure its validity. This tool is useful for anyone who needs to verify PPSNs, whether for personal use or as part of a larger software system.

![PPSN Validator Screenshot](https://github.com/codeitamarjr/IE-PPSN-Validator/blob/main/assets/PPSN-Validator-Validate-Irish-Personal-Public-Service-Numbers.png?raw=true)

[![Latest GitHub Action](https://github.com/codeitamarjr/IE-PPSN-Validator/actions/workflows/static.yml/badge.svg)](https://github.com/codeitamarjr/IE-PPSN-Validator/actions/workflows/static.yml)

## Features

- **Real-time Validation**: As users enter their PPSN, the tool checks for the correct format and validates the check digit.
- **Responsive Design**: The application is designed to be mobile-friendly, ensuring a seamless experience across devices.
- **User-Friendly Interface**: The validator features a clean and intuitive interface, making it easy to use for everyone.

## Demo

You can see the PPSN Validator in action [here](https://codeitamarjr.github.io/IE-PPSN-Validator/).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/codeitamarjr/IE-PPSN-Validator.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd ppsn-validator
   ```

3. **Open the index.html file in your web browser**:

   ```bash
   open index.html
   ```

   Alternatively, you can use a local server to serve the file. For example, using Python's built-in HTTP server:

   ```bash
   python3 -m http.server
   ```

   Then navigate to [http://localhost:8000](http://localhost:8000) in your web browser.

## Usage

To validate a PPSN:

Enter the PPSN into the input field.
Click the "Validate" button.
The tool will alert you whether the PPSN is valid or invalid based on the format and check digit calculation.

## How It Works

The validator performs the following checks:

Format Check: Ensures the PPSN is in the correct format, consisting of 7 digits followed by 1 or 2 letters.
Check Digit Calculation: Calculates the expected check character using a weighted sum of the digits and a modulus 23 calculation.
Second Character Validation: If a second character exists, it checks that it is one of the allowed characters (A, B, W, X, T, Z).
The application uses JavaScript to perform these validations in real-time.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

Contact
For any questions or feedback, please feel free to contact the project maintainer:

Name: Itamar Junior
Email: <hello@itjunior.dev>
Website: itjunior.dev
Acknowledgements
The design is powered by Tailwind CSS.
If you find this tool useful, please consider giving the repository a star ⭐ on GitHub. Your support is greatly appreciated!
