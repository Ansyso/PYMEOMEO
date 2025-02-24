# PYMEOMEO

PYMEOMEO is a powerful Python code obfuscator designed to protect your Python scripts by making them difficult to reverse-engineer. It supports multiple layers of obfuscation and is compatible with Python 3.11, 3.12, and 3.13. This version of PYMEOMEO does not use command-line arguments (`args`) and instead relies on interactive input for ease of use.

---

## Features

- **Multi-Layer Obfuscation**: Apply multiple layers of obfuscation to your code for enhanced security.
- **Cross-Version Compatibility**: Supports Python 3.11, 3.12, and 3.13.
- **Interactive Input**: No need for command-line arguments; the script will prompt you for inputs.
- **File Handling**: Automatically saves the obfuscated code with a modified filename.
- **Error Handling**: Provides clear error messages if the obfuscation process fails.

---

## Files

1. **_bes313.py**: Obfuscator script for Python 3.13.
2. **_bes312.py**: Obfuscator script for Python 3.12.
3. **_bes311.py**: Obfuscator script for Python 3.11.

---

## Installation

### Prerequisites

- Python 3.11, 3.12, or 3.13 installed on your system.
- `pystyle` library for styling the banner and text.

### Steps

1. **Install `pystyle`**:
   Run the following command to install the required library:

   ```bash
   pip install pystyle
   ```

2. **Download the Obfuscator**:
   Download the appropriate version of the obfuscator for your Python version:
   - `_bes313.py` for Python 3.13
   - `_bes312.py` for Python 3.12
   - `_bes311.py` for Python 3.11

---

## Usage

### Running the Obfuscator

1. **Run the Script**:
   Execute the appropriate script for your Python version (e.g., `_bes312.py` for Python 3.12):

   ```bash
   python _bes312.py
   ```

2. **Interactive Prompts**:
   The script will prompt you for the following inputs:
   - **Enter File**: Provide the path to the Python file you want to obfuscate.
   - **Enter Layers**: Specify the number of obfuscation layers to apply (default is 1).

3. **Output**:
   The obfuscated code will be saved in a new file with the suffix `_ob.py` (e.g., `example_ob.py`).

---

## Example Workflow

1. **Prepare Your Script**:
   Save your Python script as `example.py`.

2. **Run the Obfuscator**:
   ```bash
   python _bes312.py
   ```

3. **Follow the Prompts**:
   - **Enter File**: `example.py`
   - **Enter Layers**: `3`

4. **Check the Output**:
   The obfuscated code will be saved as `example_ob.py`.

---

## Cross-Platform Support

PYMEOMEO is designed to work seamlessly on all major operating systems:

### Windows
- Use `python` or `py` to run the script.
- Example:
  ```cmd
  python _bes312.py
  ```

### macOS/Linux
- Use `python3` to run the script.
- Example:
  ```bash
  python3 _bes312.py
  ```

---

## Notes

- **Backup Your Code**: Always keep a backup of your original code before obfuscating.
- **Error Handling**: If the obfuscation process encounters an error, it will exit with an appropriate error message.
- **Performance**: Applying multiple layers of obfuscation may increase the size of the output file and the time required for obfuscation.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

- **WGeorgeCode**
- **Ansyso**

---

## Disclaimer

This tool is intended for educational and personal use. The authors are not responsible for any misuse of this software. Use it responsibly.

---

For any issues or feature requests, please open an issue on the [GitHub repository](https://github.com/Ansyso/PYMEOMEO).
