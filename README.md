# 📧 Email Analyzer

A Python-based tool to extract information and attachments from `.msg` and `.eml` email files and organize them in a structured way.

---

## 🔍 Overview

The **Email Analyzer** processes `.msg` (Microsoft Outlook) and `.eml` (standard format) files, automatically extracting metadata, message content, and attachments. It is lightweight, simple to use, and requires minimal setup.

---

## ✨ Features

- 📂 **Multi-format Support**: Handles both `.msg` and `.eml` files.
- 📎 **Attachment Extraction**: Automatically saves all email attachments to a local directory.
- ⚙️ **Simple CLI Usage**: Easy to run from the terminal with just one command.
- 📁 **Organized Output**: Extracted data is structured and stored for further use.

---

## 📦 Prerequisites

- **Python 3.x**
- Install dependencies via pip:

```bash
pip install colorama extract_msg
Absolutely! Here's the **complete `README.md` in one single Markdown block** — ready to copy-paste directly into your GitHub project (`email-analyzer`) as-is:

---

````

* Required libraries:

  * `email`
  * `os`
  * `sys`
  * `re`
  * `colorama`
  * `extract_msg`

---

## 🚀 Installation

1. Clone or download the repository:

   ```bash
   git clone https://github.com/SarvXs/email-analyzer.git
   ```
2. Install dependencies (see above).
3. Place `.msg` or `.eml` files in the same directory as the script, or use the full path when executing.

---

## ⚙️ Usage

Run the script from the command line:

```bash
python email-analyzer.py <email_file>
```

**Example:**

```bash
python email-analyzer.py example.msg
```

---

## 📂 Output

* A folder named `Attachments/` will be created if it doesn’t exist.
* All extracted attachments from the email will be saved there.
* Terminal will show progress and info messages via `colorama`.

---

## 📝 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for full details.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo, open an issue, or submit a pull request.

---

## 📫 Contact

For questions, ideas, or collaborations:
**GitHub**: [SarvXs](https://github.com/SarvXs)
**Email**: [k.s.sarvesvaraan@gmail.com](mailto:k.s.sarvesvaraan@gmail.com)



```




