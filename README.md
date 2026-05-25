COMPANY : CODE IT SOLUTIONS

NAME : SANGABATTUNI AAKASH

INTERN ID : CTIS8970

DOMAIN : CYBERSECURITY AND ETHICAL HACKING

DURATION : 8 WEEKS

INTERNSHIP PERIOD : 17 May 2026 - 12 July 2026

MENTOR : Neela Santhosh Kumar

FILE_INTEGRITY_CHECKER_TOOL
A TOOL TO MONITOR CHANGES
IN FILES BY CALCULATING AND
COMPARING HASH VALUES
A Python tool to detect file changes (added, modified, or deleted) in a directory using SHA‑256 hashing.
This script helps track integrity of files and monitor changes over time.

🚀 Features
Calculates SHA‑256 hashes for all files in a directory.

Detects:

⚠️ Modified files

➕ Newly added files

❌ Deleted files

Stores hash records in a JSON file (file_hashes.json) for future comparisons.

Provides a clear summary report of changes.


🛠️ How It Works
Hashing: Each file’s SHA‑256 hash is computed.

Storage: Hashes are saved in file_hashes.json.

Comparison: On each run, the script compares new hashes with old ones.

Reporting: Prints a summary of modified, added, or deleted files.

Updating: Saves the latest hashes for the next run.


📦 Requirements
Python 3.7+
Standard libraries (os, hashlib, json, pathlib) — no external dependencies.


🔒 Use Cases
Detect unauthorized file changes.

Monitor project directories for accidental edits.

Track integrity of configuration files or logs.


⚠️ Notes
Large directories may take longer to scan.

Only tracks files accessible to the script (no hidden system files).

JSON file (file_hashes.json) must remain in the same directory as the script.

In this project, the intern will develop a Python script that:

Allows users to select one or more files.

Calculates and stores the original hash values in a secure manner.

Periodically (or manually) recalculates hash values and compares them with the originals.

Notifies the user if any discrepancy is found, signaling a potential unauthorized change.


DISCRIPTION :

This task promotes the understanding of fundamental cybersecurity concepts such as data integrity, hashing algorithms, and change detection. It also involves basic file handling, user interaction via the command line or GUI, and efficient data comparison methods. The script can be extended to monitor folders, generate logs, or send alerts via email—opening up many creative possibilities for enhancement.

Ultimately, the deliverable is a functional Python script that helps detect unauthorized or accidental modifications in files, ensuring their integrity over time. This task not only enhances the intern's Python programming skills but also introduces them to the practical applications of cryptographic functions in real-world scenarios—an invaluable step for anyone looking to grow in the field of software development or cybersecurity.

#OUT-PUT
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/b6bbf28d-abb3-4ccc-9077-7cce0730473d" />

