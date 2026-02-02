# qr-code-generator
A simple Python program to generate QR codes from URLs
# QR Code Generator (Python)

Super simple Python script that turns any URL you give it into a QR code. Scan it with your phone and boom—straight to the link.

## How it works
1. Type in a URL (like https://youtube.com or whatever)
2. It spits out a QR code image 
3. Saves it as qrcode.png in the same folder

That's it. 10 seconds tops.

## Tech
- Python 3.x
- qrcode library (with PIL for image support)

## Setup
pip install qrcode[pil]


## Run it
python qr_generator.py

## Example
Enter URL: https://instagram.com/yourprofile
[QR code generates and saves as qrcode.png]

Done. Check your folder.


Pro tip: Works with any URL—YouTube, Instagram, LinkedIn profiles, whatever. Great for business cards or posters.😎
