# File-Organizer-Using-Python
File Organizer with GUI
Project Overview
This Python application organizes files in the current directory based on their file extensions into categorized folders. It also provides a GUI to display the total number of files organized.

Features
Automatic File Organization:
Scans the current directory for files.
Moves files into categorized folders (e.g., HTML, IMAGES, DOCUMENTS, etc.) based on their file extensions.
File Count Display:
Counts the number of files organized.
Displays the count in a simple GUI built using Tkinter.
File Categories
The application categorizes files into the following directories:

HTML
IMAGES
VIDEOS
DOCUMENTS
ARCHIVES
AUDIO
PLAINTEXT
PDF
PYTHON
XML
EXE
SHELL
C-LANG
CPP
JAVA
Each category has a list of file extensions it recognizes.

Dependencies
Python 3.x
Tkinter (included with Python's standard library)
How to Run
Clone or download the project to your local machine.
Ensure Python 3.x is installed.
Open a terminal and navigate to the project directory.
Run the script using:
bash
Copy code
python <script_name>.py
Replace <script_name> with the name of the Python file.
How it Works
Organize Files:
The script uses os and pathlib to scan the directory, identify file extensions, and move files to corresponding folders.

Count Files:
The empty_junk() function counts the total number of files that match the defined categories.

GUI Display:
The Tkinter GUI shows the total number of files organized.

Folder Structure
After running the script, the directory will be organized into categorized folders:
css
Copy code
├── HTML
├── IMAGES
├── VIDEOS
├── DOCUMENTS
├── ...
└── Remaining uncategorized files
Limitations
Files in subdirectories are not processed.
Only file extensions listed in the DIRECTORIES dictionary are organized.
The GUI is minimal and only shows the total file count.
Customization
To add support for additional file types, update the DIRECTORIES dictionary by adding the new file type and its corresponding extensions.
Contribution
Feel free to fork this repository and submit pull requests with improvements or additional features.

License
This project is open-source and distributed under the MIT License.