# AI-Powered Custom Resume Builder for Job Applications

AI-Powered Custom Resume Builder for Job Applications is a Python-based tool designed to help job seekers create tailored resumes for specific job postings. Using the Groq API and the Mixtral-8x7b model, it analyzes your existing resume and a job description to generate a customized resume that highlights your most relevant skills and experiences. This tool streamlines the application process, ensuring your resume stands out to hiring managers and increases your chances of securing interviews.

---

## Features

- **Custom Resume Generation**: Tailors your resume to match specific job descriptions.
- **AI-Powered Analysis**: Utilizes the Groq API and Mixtral-8x7b model for intelligent resume customization.
- **Easy to Use**: Simply provide your resume and job description, and let the tool do the rest.
- **Timestamped Output**: Generates a uniquely named resume file for each job application.

---

## Prerequisites

Before using this tool, ensure you have the following:

1. **Python 3.x** installed on your system.
2. A **Groq API Key**. You can obtain one by signing up at [Groq's website](https://groq.com/).
3. A `.env` file to store your API key securely.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/iammkullah/AI-Powered-Custom-Resume-Builder-for-Job-Applications.git

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt

3. Create a .env file in the root directory and add your Groq API key:
    ```bash
    GROQ_API_KEY=your_api_key_here

3. Place your resume in a file named resume.txt and the job description in a file named jobDescription.txt in the root directory.

## Usage
Ensure your resume.txt and jobDescription.txt files are ready.

Run the script:

    ```bash
    python main.py

The tool will generate a custom resume in Markdown format with a timestamped filename (e.g., resume_20231010120000.md).


## .gitignore
To ensure sensitive information like your .env file is not tracked by Git, include the following in your .gitignore file:
    ```bash
    # Ignore .env file (contains sensitive information)
    .env

    # Ignore Python compiled files
    __pycache__/
    *.pyc
    *.pyo
    *.pyd

    # Ignore virtual environments
    venv/
    env/

    # Ignore IDE-specific files
    .vscode/
    .idea/

    # Ignore system files
    .DS_Store

## Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:
- Fork the repository.
- Create a new branch for your feature or bugfix.
- Commit your changes.
- Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Groq for providing the API and tools.
- Mixtral-8x7b for the powerful language model.

## Contact
For questions or feedback, feel free to reach out:
- Email: iammkullah@gmail.com
- GitHub: iammkullah

