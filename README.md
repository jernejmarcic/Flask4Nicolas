
# How to Run the Web Application

This guide provides detailed steps on how to set up and run the web application. Follow each step carefully to ensure successful setup and execution.

## Prerequisites

Ensure that Python is installed on your system. If it's not installed, follow the installation instructions below.

### Installing Python

1. **Windows Users:**
   - Visit [python.org](https://www.python.org/downloads/windows/) to download the Python installer.
   - Execute the downloaded file.
   - Follow the installation prompts. Remember to select "Add Python to PATH" during the installation process.

2. **macOS/Linux Users:**
   - Typically, Python comes pre-installed on macOS and Linux.
   - Check if Python is installed by typing `python --version` or `python3 --version` in your terminal.
   - If Python is not installed, download it from [python.org](https://www.python.org/downloads/) or use a package manager (e.g., Homebrew for macOS: `brew install python`, or apt for Ubuntu: `sudo apt-get install python3`).

## Installing Project Dependencies

After installing Python, install the project's dependencies:

```bash
git clone [Your Repository URL]
cd [Your Project Directory]
pip install -r requirements.txt
```

## Setting Up SCSS with File Watcher in PyCharm

Follow these steps to work with SCSS:

1. **Install SCSS:**
   - Ensure Node.js is installed (download from [nodejs.org](https://nodejs.org/) if not).
   - Install SCSS globally using npm: `npm install -g sass`

2. **Configure File Watcher in PyCharm:**
   - Open your project in PyCharm.
   - Navigate to `File` -> `Settings` -> `Tools` -> `File Watchers`.
   - Click the `+` icon to add a new watcher.
   - Select `<custom>` template.
   - Set up the File Watcher for SCSS. Detailed steps can be found in the [PyCharm File Watcher tutorial](https://www.jetbrains.com/help/pycharm/using-file-watchers.html).

## Running the Application

To run the application:

```bash
python app.py
```

This command starts the web server. Access the application through your web browser at `http://localhost:5000` or the address specified in your terminal.

## Troubleshooting

- Ensure all paths and commands are correct for your system and project.
- If you encounter errors, review the console output for troubleshooting clues.

For further assistance, reach out to the project maintainers or refer to the README file.


