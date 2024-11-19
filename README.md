# Multilanguage-code-assistant-using-Gradio-and-code-Llama

## Table of Contents
1. [Project Title](#project-title)
2. [Project Description](#project-description)
3. [Key Features](#key-features)
4. [Tech Stack](#tech-stack)
5. [Setup Instructions](#setup-instructions)
    - [Prerequisites](#prerequisites)
    - [Installation Steps](#installation-steps)
6. [Usage](#usage)
7. [File Structure](#file-structure)
8. [Future Enhancements](#future-enhancements)
9. [License](#license)
10. [Contributors](#contributors)
11. [Acknowledgments](#acknowledgments)

---

## Project Title
**Multilanguage Code Assistant NLP Project Using Gradio and Code Llama**

---

## Project Description
This project is an interactive **Multilanguage Code Assistant** built using **Gradio** and **Code Llama**. It enables users to input prompts in natural language, generates programming code based on the input, and displays the output directly. The assistant is designed to support multiple programming languages, making it a valuable tool for developers, students, and researchers seeking quick and accurate code generation.

---

## Key Features
1. **Natural Language to Code Conversion**:
   - Accepts user prompts in plain text and generates relevant programming code.

2. **Multilanguage Support**:
   - Capable of generating code in multiple programming languages based on user input.

3. **Interactive Interface**:
   - Built with Gradio for an easy-to-use, interactive UI.

4. **History Tracking**:
   - Maintains a history of prompts to provide context for better code generation.

5. **Seamless Integration**:
   - Communicates with a backend API powered by the `codesensei` model for code generation.

---

## Tech Stack
- **Frontend**: Gradio
- **Backend**: Python
- **Model**: Code Llama (powered by `codesensei`)
- **API**: RESTful API for generating responses
- **Libraries**:
  - `requests` (for API communication)
  - `json` (for handling API data)

---

## Setup Instructions

### Prerequisites
1. Install Python 3.8 or later.
2. Ensure the following Python libraries are installed:
   - `gradio`
   - `requests`
   - `json`

3. Ensure the backend API (running Code Llama or `codesensei`) is set up and available at `http://localhost:11434/api/generate`.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multilanguage-code-assistant.git
   cd multilanguage-code-assistant
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

---

## Usage
1. **Start the Application**:
   - Launch the application using the provided command.
   - Open the Gradio interface in your browser.

2. **Input a Prompt**:
   - Enter a natural language prompt in the text box (e.g., *"Generate a Python function to calculate factorial"*).
   - Submit the prompt.

3. **View Generated Code**:
   - The application will display the generated code based on your input.

---

## File Structure
```
├── app.py                # Main application script
├── requirements.txt      # Required libraries
├── README.md             # Project documentation
```

---

## Future Enhancements
1. **Cloud Integration**:
   - Host the application on cloud platforms for wider accessibility.

2. **Advanced Language Support**:
   - Expand to support more programming languages and frameworks.

3. **Enhanced Prompt Engineering**:
   - Improve context handling for complex code generation.

4. **User Authentication**:
   - Add authentication to secure the API and usage.

5. **Error Handling**:
   - Implement robust error-handling mechanisms for API failures.

---

## **Contributors**

- **Rishikesh**  
- LinkedIn: www.linkedin.com/in/rishikesh-a12090285
- Email: rishikesh23@kgpian.iitkgp.ac.in


---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
