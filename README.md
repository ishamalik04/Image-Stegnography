# Image Stegnography Tool

This is a simple steganography tool written in Python using Tkinter and the stegano library. It allows you to hide and reveal secret text messages within images.

## Usage

1. Clone the repository:

    git clone https://github.com/yourusername/Image-Stegnography.git
   
    cd Image-Stegnography

2. Run the script:

   python main.py

3. The main window will appear with options to open an image file, hide data within the image, reveal hidden data from the image, and save the modified image.

4. Click on the "Open Image" button to select an image file.

5. Enter the text message you want to hide in the image in the text area provided.

6. Click on the "Hide Data" button to hide the text message within the image.

7. To reveal the hidden message from the modified image, click on the "Show Data" button.

8. You can also save the modified image with the hidden data using the "Save Image" button.

## Requirements
- Python 3.x
- Tkinter (usually included in Python standard library)
- stegano library (install using pip install stegano)

  


## Note

- Ensure that you remember the image file path where you hide the data if you want to reveal it later.
- Be cautious while hiding sensitive information within images, as the steganographic techniques used might not provide absolute security.
- Always test the tool with different images and text to ensure proper functionality and concealment.
