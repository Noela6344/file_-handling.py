# File Reader and Modifier (Python Script
Overview
This Python script allows you to:
- Read the contents of a text file.
- Handle errors gracefully (e.g., file not found, permission issues).
- Convert the content to **uppercase**.
- Save the modified version into a **new file** prefixed with `modified_`.

This is a beginner-friendly project demonstrating **file handling, error handling, and string manipulation** in Python.

---

## 🚀 How It Works
1. The program asks you to **enter a filename**.
2. It attempts to open and read the file:
   - If the file is missing or inaccessible, an error message is displayed.
3. The content is **converted to uppercase**.
4. A new file named `modified_<original_filename>` is created.
5. The modified content is saved in this new file.

---

 Example Usage
```bash
$ python file_modifier.py
Enter the file name to read: notes.txt
 Modified file has been saved as 'modified_notes.txt'
If the file doesn’t exist:

bash
Copy
Edit
$ python file_modifier.py
Enter the file name to read: missing.txt
 Error: The file does not exist.
 File Structure
bash
Copy
Edit
project-folder/
│── file_modifier.py   # The main script
│── notes.txt          # Example input file (optional)
│── modified_notes.txt # Output after running the script
⚡ Features
Error handling for:

Missing file (FileNotFoundError)

Permission issues (PermissionError)

Other unexpected errors

Easy-to-understand and extendable code.

Creates a safe copy instead of overwriting the original file.

🔧 Requirements
Python 3.6+

No external libraries are required.

 How to Run
Save the script as file_modifier.py.

Open a terminal or command prompt.

Run:

bash
Copy
Edit
python file_modifier.py
🛠️ Possible Improvements
Add more content modifications (e.g., lowercase, word count, replace words).

Allow saving to a custom output filename.

Add a menu for multiple text transformations.

 Author
Noela Kipchumba
A mechanical technologist & software engineering learner passionate about solving problems through tech + creativity.
