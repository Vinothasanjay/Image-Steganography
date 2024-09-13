

# Image Steganography

Welcome to the Image Steganography project! This tool allows you to hide and reveal messages within images using Python and Tkinter. The graphical user interface (GUI) simplifies the process of encoding and decoding messages in images.

## Features

- **Open Image**: Load an image file to work with.
- **Hide Message**: Encode a message within the selected image.
- **Reveal Message**: Decode and display the hidden message from the selected image.
- **Clear Text Area**: Automatically clear the text area when a new image is opened.

## Requirements

- Python 3.x
- Tkinter (included with Python)
- Pillow (PIL Fork) - For image handling

Install the necessary libraries using pip:

```bash
pip install pillow
```

## Usage

1. **Launch the GUI**: Run the main Python script to start the application.

    ```bash
    python main.py
    ```

2. **Open an Image**: Click the "Open Image" button to load an image file.

3. **Hide a Message**: Enter your message in the text area and click "Hide Message" to encode it into the image.

4. **Reveal a Message**: Open the image with the hidden message and click "Reveal Message" to display the encoded message.

5. **Clear Text Area**: The text area will be cleared when you open a new image.


## Example

To use the application:

1. Click "Open Image" to select an image.
2. Enter your message into the text area.
3. Click "Hide Message" to embed the message in the image.
4. To decode the message, open the image and click "Reveal Message."
   ## GUI
   ![image](https://github.com/user-attachments/assets/4551ec44-dcbf-4634-b6be-dc58c02cdcca)

## Notes

- The GUI components are designed to be clearly visible and free from unwanted whitespace or color issues.
- The buttons for hiding and revealing messages are conveniently placed below the "Open Image" button.
- The text area is long and scrollable, accommodating longer messages.

## Contributing

Contributions are welcome! Please open issues or submit pull requests with any improvements or bug fixes.
