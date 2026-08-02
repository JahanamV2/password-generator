# 🔐 Python Password Generator

A simple and secure password generator built with Python.

This project generates random passwords while guaranteeing at least one:

- 🔢 Number
- 🔡 Lowercase letter
- 🔠 Uppercase letter
- 🔣 Special character

The password is shuffled before being returned to avoid predictable character placement.

---

## Features

- Generate passwords of any length (minimum length: 4)
- Input validation
- Guaranteed strong character diversity
- Clean and modular code
- Beginner-friendly implementation

---

## Requirements

- Python 3.x

No external libraries are required.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/JahanamV2/password-generator.git
```

Move into the project folder:

```bash
cd password-generator
```

Run the program:

```bash
python password_generator.py
```

---

## Example

```
Enter the password length: 16

Generated password:
m!9AxQ#7uZ1@Lp5%
```

---

## Future Improvements

- Use Python's `secrets` module for cryptographically secure randomness.
- Command-line arguments with `argparse`.
- Password strength estimation.
- Copy generated password to clipboard.
- GUI version using Tkinter.
- Export passwords to a file.

---

## Learning Goals

This project was created to practice:

- Functions
- Loops
- Input validation
- String manipulation
- Python standard library
- Code organization

---

## License

This project is licensed under the MIT License.

## 👨‍💻 Author

Made with ❤️ by **JahanamV2**
