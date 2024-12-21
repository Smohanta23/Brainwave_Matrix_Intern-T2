
# Voice-Based Train Enquiry System 🚆🎤
The Voice-Based Train Enquiry System is a Python-based application designed to operate using voice commands. Users can interact with the system through voice input to receive train-related information. The system processes voice inputs, converts them into text, and fetches the relevant details from a database. It also supports voice output to enhance user experience.

This project is built using Python, SQLite for database management, and Google’s Speech-to-Text API for speech recognition. A microphone is required for capturing user voice inputs.

# 📋 Features
1. Accepts voice commands for train enquiries.
2. Converts speech to text using Google’s Speech-to-Text API.
3. Provides information in text format and optionally as voice responses.
4. Includes an administration panel for managing the train database.
5. Utilizes Python's Tkinter library for the graphical user interface (GUI).

# 📦 Prerequisites
1. Basic knowledge of Python programming.
2. Understanding of database operations (CRUD: Create, Read, Update, Delete).
3. Familiarity with Tkinter for building GUIs.

# 🛠️ Project Setup
1. Clone the repository to your local system.
2. Install required Python libraries: pip install -r requirements.txt
3. Ensure you have train.db (a sample database) available in the project directory.

# 🚀 Execution Steps
1. Run the FRONT.py module using any Python IDE or terminal: python FRONT.py
2. Use the Administration Tab to access the database management interface. Modify train records as needed.
3. Click on the "Give Command in Speech" tab to activate the speech recognition module. Provide your query using keywords like from, to, <source_name>, <destination_name>, or <date>.
4. The system will process the query and provide the necessary train information.

# 🛠️ Tools and Technologies
1. Python: Core programming language.
2. SQLite: Lightweight database for managing train information.
3. Tkinter: For GUI implementation.
4. Google Speech-to-Text API: For converting speech input into text.

# 📂 Project Structure

/project-root
│
├── FRONT.py                # Main entry point for the application
├── train.db                # Sample database file
├── requirements.txt        # List of required Python packages
└── README.md               # Project documentation

# ✨ Future Enhancements
1. Add support for multiple languages.
2. Enhance database management features.
3. Introduce voice-based output for train enquiries.