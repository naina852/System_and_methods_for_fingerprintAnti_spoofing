# System and Methods for Fingerprint Anti-Spoofing

## Overview
This project implements a Raspberry Pi-based fingerprint recognition system with advanced anti-spoofing technology using Convolutional Neural Networks (CNN). It was developed as a summer internship project at IIT Kanpur under the mentorship of Professor Tushar Sandhan.

## Installation
1. **Hardware Requirements:**
   - Raspberry Pi board
   - Adafruit ST7735 TFT display
   - Fingerprint sensor (specific model)
   
2. **Software Requirements:**
   - Python 3.x
   - TensorFlow (for CNN models)
   - Adafruit CircuitPython libraries (for TFT display)

3. **Installation Steps:**
   - Clone the repository: `git clone https://github.com/yourusername/your-repository.git`
   - Navigate to the project directory: `cd your-repository`
   - Install dependencies: `pip install -r requirements.txt`

## Usage
- Connect the Raspberry Pi to the fingerprint sensor and TFT display.
- Run `python main.py` to start the system.
- Follow on-screen instructions for fingerprint authentication.

## Features
- Implemented Raspberry Pi software for fingerprint recognition.
- Utilized CNN to distinguish between live and fake fingerprints.
- Optimized fingerprint images through resizing, cropping, and normalization for CNN and GNN models.
- Integrated Adafruit ST7735 TFT display for real-time feedback, enhancing user interaction.
- Efficiently interfaced GPIO/SPI for TFT display integration on Raspberry Pi.

## Results (Optional)
- Designed a compact and portable device suitable for various applications.
- Achieved an 80% accuracy rate in detecting fake fingerprints when tested against proposed molds.

## Contributions
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, feel free to reach out:
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/yourprofile)

## Acknowledgments
Special thanks to Professor Tushar Sandhan for mentorship and guidance during this project.
