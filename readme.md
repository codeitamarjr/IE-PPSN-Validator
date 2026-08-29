# PPSN Validator

[![Latest GitHub Action](https://github.com/codeitamarjr/IE-PPSN-Validator/actions/workflows/static.yml/badge.svg)](https://github.com/codeitamarjr/IE-PPSN-Validator/actions/workflows/static.yml)
[![Latest Release](https://img.shields.io/github/v/release/codeitamarjr/IE-PPSN-Validator)](https://github.com/codeitamarjr/IE-PPSN-Validator/releases/latest)

## Overview

The PPSN Validator is a simple web application designed to validate Irish Personal Public Service Numbers (PPSNs). The validator checks if a PPSN is correctly formatted and calculates the check digit to ensure its validity. This tool is useful for anyone who needs to verify PPSNs, whether for personal use or as part of a larger software system.

![PPSN Validator Screenshot](https://github.com/codeitamarjr/IE-PPSN-Validator/blob/main/assets/PPSN-Validator-Validate-Irish-Personal-Public-Service-Numbers.png?raw=true)

## Features

- **Real-time Validation**: As users enter their PPSN, the tool checks for the correct format and validates the check digit.
- **Responsive Design**: The application is designed to be mobile-friendly, ensuring a seamless experience across devices.
- **User-Friendly Interface**: The validator features a clean and intuitive interface, making it easy to use for everyone.

## How to use

You can open the PPSN Validator at [https://codeitamarjr.github.io/IE-PPSN-Validator](https://codeitamarjr.github.io/IE-PPSN-Validator/)

Save it on your favourites for future use :D

## How It Works

The validator performs the following checks:

Format Check: Ensures the PPSN is in the correct format, consisting of 7 digits followed by 1 or 2 letters.
Check Digit Calculation: Calculates the expected check character using a weighted sum of the digits and a modulus 23 calculation.
Second Character Validation: If a second character exists, it checks that it is one of the allowed characters (A, B, W, X, T, Z).
The application uses JavaScript to perform these validations in real-time.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any questions, feedback, or collaboration inquiries, please feel free to reach out to the project maintainer:

- **Name**: Itamar Junior
- **Email**: [hello@itjunior.dev](mailto:hello@itjunior.dev)
- **Website**: [itjunior.dev](https://itjunior.dev)
- **LinkedIn**: [Itamar Junior on LinkedIn](https://www.linkedin.com/in/itamarjr)
- **GitHub**: [Itamar Junior on GitHub](https://github.com/codeitamarjr)

## Acknowledgements

- The design is powered by [Tailwind CSS](https://tailwindcss.com/).

## Support

If you find this tool useful, please consider giving the repository a star ⭐ on [GitHub](https://github.com/codeitamarjr/IE-PPSN-Validator). Your support is greatly appreciated!
