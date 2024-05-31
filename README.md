# QR Code Generator

This Python script generates a QR code containing a link to a specific website. It utilizes the `qrcode` library to create the QR code and the `PIL` library to save it as an image file.

## Installation

To use this QR code generator, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/pinkikumari1/QR-Code-Generator.git
```
2. Install the required dependencies using pip:
```bash
pip install qrcode
pip install pillow
```
## Usage
1. Open the terminal or command prompt.
2. Navigate to the directory where you cloned the repository.
3. Run the script generate_qr_code.py using the following command:
```bash
python generate_qr_code.py
```
4. Once the script runs successfully, you will find the generated QR code image named Kerala_Treval.png in the same directory.
## Customization
You can customize the generated QR code by modifying the following parameters in the generate_qr_code.py script:

* version: The size of the QR code (1 to 40). Larger values provide higher capacity.
* error_correction: The error correction level. Options are ERROR_CORRECT_L, ERROR_CORRECT_M, ERROR_CORRECT_Q, and ERROR_CORRECT_H.
* box_size: The number of pixels for each box in the QR code.
* border: The number of white boxes around the QR code.
* fill_color: The color of the QR code.
* back_color: The background color of the QR code.
* data: The URL to encode in the QR code. Replace "https://pinkikumari1.github.io/Kerala_Trip/" with your desired URL.
## License
* This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
* This project utilizes the qrcode library. More information can be found here.
* The image manipulation is handled by the PIL library. More information can be found here.
