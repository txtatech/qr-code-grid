# qr-code-grid

A Python script that generates a 3D grid of QR codes with associated information and creates an HTML page to visualize the grid using the X3D format.

## Features

- Generates a grid of QR codes with coordinates and neighbor information.
- Saves QR code images as PNG files, ASCII art TXT files and the corresponding QR code information as a JSON file.
- Creates an interactive 3D representation of the grid using X3D and displays the QR code images on textured boxes.

## Requirements

- Python 3.x
- qrcode module (`pip install qrcode`)
- x3dom library (included via CDN in the generated HTML page)

## Usage

1. Clone the repository or download the script file (`qr-code-grid.py`).
2. Install the required Python packages: `pip install qrcode`.
3. Run the script: `python qr-code-grid.py`.
4. The script will generate the QR code images, save them in PNG and TXT format, and create an HTML page (`index.html`).
5. Open the `index.html` file in a web browser to view the 3D grid of QR codes.

## Customization

- Adjust the `grid_size` variable in the script to change the size of the grid.
- Modify the appearance of the QR codes by adjusting the parameters in the `generate_qr_with_info` function.
- Customize the generated HTML page by modifying the `generate_x3dom_page` function.

- ![Image alt text](.qr-code-grid
/qr-code-grid.png)

