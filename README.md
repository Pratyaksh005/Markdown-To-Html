
# Markdown to HTML Converter

This is a simple Python script that converts Markdown files (.md) into HTML files using the `markdown` library. The project also includes a GUI built with `tkinter`, making it easy for users to select a Markdown file and convert it to HTML with a few clicks.

## Features

- **Markdown to HTML Conversion**: Convert `.md` files to `.html`.
- **Simple GUI**: Built with `tkinter` for an easy-to-use graphical interface.
- **File Selection**: Choose the input Markdown file and specify the output HTML file location.
- **Status Notifications**: Display status updates and success/error messages.

## Requirements

To run the project, you'll need to have the following Python packages installed:

- `markdown`: For converting Markdown to HTML.
- `tkinter`: For the GUI (usually comes pre-installed with Python).
- `messagebox`: For pop-up notifications.

You can install the required dependencies using `pip`:

```bash
pip install markdown
```

## Installation

1. Clone the repository or download the files to your local machine.

   ```bash
   git clone https://github.com/Pratyaksh005/markdown-to-html-converter.git
   ```

2. Install the required dependencies:

   ```bash
   pip install markdown
   ```

3. Run the GUI by executing `gui.py`:

   ```bash
   python gui.py
   ```

## Usage

1. When you launch the GUI, click on the **Convert Markdown to HTML** button.
2. Select the Markdown file (.md) that you want to convert.
3. Choose a location to save the resulting HTML file.
4. The status will update to reflect the progress of the conversion.
5. Once the conversion is complete, a success message will be displayed.

You can also use the **Clear Selection** button to reset the selection and start over.

## File Structure

```
/markdown-to-html-converter
    ├── gui.py              # The main GUI script
    ├── main.py # Script that handles the conversion logic
    └── README.md           # Project documentation
```

## Sample Images
<img width="604" alt="Gui" src="https://github.com/user-attachments/assets/8447e64f-b8ef-474d-ae40-f8837cb8bdb4">
<img width="604" alt="Convert file" src="https://github.com/user-attachments/assets/0a465bf4-3b73-44e7-8016-bd270465a27b">

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The `markdown` library is used for converting Markdown files to HTML.
- `tkinter` is used for creating the graphical user interface.

## Contact

If you have any questions or suggestions, feel free to open an issue or reach out to [pratyaksh6941@gmail.com].
