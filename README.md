# PYMEOMEO

PYMEOMEO is a Python code obfuscator designed to protect your Python scripts by making them difficult to reverse-engineer. It supports multiple layers of obfuscation and is compatible with Python 3.11, 3.12, and 3.13. The obfuscator uses a combination of compression and encoding techniques to obscure the code, making it challenging for unauthorized users to understand or modify.

## Features

- **Multi-Layer Obfuscation**: Apply multiple layers of obfuscation to your code for enhanced security.
- **Cross-Version Compatibility**: Supports Python 3.11, 3.12, and 3.13.
- **File Handling**: Automatically saves the obfuscated code with a modified filename.
- **Error Handling**: Provides clear error messages if the obfuscation process fails.

## Files

1. **_bes313.py**: Obfuscator script for Python 3.13.
2. **_bes312.py**: Obfuscator script for Python 3.12.
3. **_bes311.py**: Obfuscator script for Python 3.11.

## Usage

1. **Run the Obfuscator**:
   - Execute the appropriate script for your Python version (e.g., `_bes312.py` for Python 3.12).

2. **Input File**:
   - When prompted, enter the path to the Python file you want to obfuscate.

3. **Select Layers**:
   - Specify the number of obfuscation layers you want to apply. More layers increase the complexity of the obfuscated code.

4. **Output**:
   - The obfuscated code will be saved in a new file with the suffix `_ob.py` (e.g., `script_ob.py`).

## Example

```bash
python _bes312.py
```

- **Enter File**: `example.py`
- **Enter Layers**: `3`

The obfuscated code will be saved as `example_ob.py`.

## Requirements

- Python 3.11, 3.12, or 3.13
- `pystyle` library (for styling the banner and text)

## Installation

To install the required `pystyle` library, run:

```bash
pip install pystyle
```

## Notes

- **Compatibility**: Ensure you are using the correct version of the obfuscator for your Python version.
- **Error Handling**: If the obfuscation process encounters an error, it will exit with an appropriate error message.
- **Backup**: Always keep a backup of your original code before obfuscating.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- **WGeorgeCode**
- **Ansyso**

## Disclaimer

This tool is intended for educational and personal use. The authors are not responsible for any misuse of this software. Use it responsibly.

---

For any issues or feature requests, please open an issue on the [GitHub repository](https://github.com/Ansyso/PYMEOMEO).
