````markdown
# 🏛️ Roman Numeral Converter

This is a simple web application that converts Arabic numerals (integers) into Roman numerals, following the standard Roman numeral rules. Built to fulfill FreeCodeCamp’s certification project requirements.

## 📋 Features

- Input a number from **1 to 3999**.
- Converts to accurate **Roman numeral** format.
- Handles edge cases and invalid inputs.
- Instant feedback displayed on screen.
- Lightweight UI with clear, responsive elements.

## 📦 Technologies Used

- **HTML5** – semantic structure
- **CSS3** – basic styling and layout
- **JavaScript (ES6)** – DOM manipulation and logic

## 🚀 Live Demo

👉 [Try it here](https://roman-numeral-converter.freecodecamp.rocks)

## ✅ User Stories (Requirements)

- [x] You should have an input element with an id of `number`.
- [x] You should have a button element with an id of `convert-btn`.
- [x] You should have a div, span, or p element with an id of `output`.
- [x] If the input is empty, the output should be `"Please enter a valid number"`.
- [x] If input is `< 1`, the output should be `"Please enter a number greater than or equal to 1"`.
- [x] If input is `≥ 4000`, the output should be `"Please enter a number less than or equal to 3999"`.
- [x] Input `9` → output `"IX"`
- [x] Input `16` → output `"XVI"`
- [x] Input `649` → output `"DCXLIX"`
- [x] Input `1023` → output `"MXXIII"`
- [x] Input `3999` → output `"MMMCMXCIX"`

## 💻 How to Use

1. Clone this repository or download the `index.html` file:
   ```bash
   git clone https://github.com/yourusername/roman-numeral-converter.git
```

2. Open `index.html` in any modern browser.
3. Enter a number in the input field and click **Convert**.

## 📁 File Structure

```
roman-numeral-converter/
│
├── index.html        # Main application file
├── README.md         # Project documentation
```

## 📜 Roman Numeral Mapping

| Roman | Value |
| ----- | ----- |
| M     | 1000  |
| CM    | 900   |
| D     | 500   |
| CD    | 400   |
| C     | 100   |
| XC    | 90    |
| L     | 50    |
| XL    | 40    |
| X     | 10    |
| IX    | 9     |
| V     | 5     |
| IV    | 4     |
| I     | 1     |

## 🤝 Contributing

Contributions are welcome! Fork the repo, make your changes, and submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Built with 💻 by Jordan Leturgez

```

---

### ✅ Next Steps:
- Replace `https://github.com/yourusername/...` with your actual GitHub repo URL.
- Add your name in the footer.
- Include a `LICENSE` file if you want to officially license the project.
