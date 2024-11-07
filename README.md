> # <img src="https://github.com/user-attachments/assets/3c74ba02-76ee-4bba-901e-7de522a8bd32" width="100"/> <img src = "https://github.com/user-attachments/assets/051a5685-a42b-48f4-a8ec-5b5321cd46fb" width="600"/>
Model of Learning Ecosystem Platform integrate with Coding & AI for Youth

## Who am I?🧐
- **My name is**  Jadesadakorn Kamolvimutsarn
- **Age**: 15 years old
- **School**: Debsirin School

I have enjoyed programming since two years ago, back when I was in Mattayom 2. I want to explore various fields in programming to help me identify the area I truly want to pursue. Recently, I’ve grown more interested in AI, and I see competitions as a great stepping stone for honing my skills and advancing in this field.

## Content❗

### Prerequisites
1. **Python 3.6+** is required.
2. Install the following libraries using `pip`:
``` bash
  pip install qrcode[pil] Pillow tkinter
  ```
* Warning: For some device, Tkinter may already be installed, so you can remove tkinter from command.

**How to Run**
* Download the project files.
* Ensure you have installed all required libraries.
* Detect file location (with cd)
* Run the script using the following command:
``` bash
python QRCode_generator.py
```
**How it Works**

1. Input Field: Users can enter a text or URL in the input field to generate a QR code. The application checks if the input field is not empty before proceeding.

2. Generate QR Code: Once the user clicks the "Generate QR Code" button, the app creates a QR code from the provided text or URL:

  * The QR code is generated with a version size, box size, and border width predefined in the code.
  * The QR code is displayed as an image on the GUI.
    
3. Upload Logo: Optionally, users can upload a logo to place at the center of the QR code. Here’s how it works:

  * The logo is resized to fit within the QR code.
  * The app creates a circular white background behind the logo for a cleaner look.
  * The logo is then placed at the center of the QR code with proper alignment.
    
4. Save QR Code: The user can save the QR code in one of the following formats:

  * PNG: The QR code is saved as a PNG image file.
