# CV Generator

## Overview
CV Generator generates a CV document based on user input. The CV includes sections for a profile picture, contact details, professional profile, technical skills, work experience, and a footer.

## Features
- **Text-to-Speech Guidance**: Guides users through the CV generation process with text-to-speech functionality.
- **Profile Picture**: Allows users to add their profile picture to the CV.
- **Contact Details**: Collects the user's full name, email address, and LinkedIn URL.
- **Professional Profile**: Enables users to add a professional profile summary.
- **Technical Skills**: Allows users to add technical skills with a bullet-point format.
- **Work Experience**: Enables users to add their work experience, including company name, start and end dates, and a description of their role.
- **Footer**: Adds a standard footer to the CV document.

## Usage
1. Ensure your CV headshot is saved as headshot.png in the project directory.
2. Launch the CV Generator application:
```python
python main.py
```
3. Follow the on-screen prompts to input your details and customise your CV.
4. Once finished, your CV will be saved as cv.docx in the project directory.

## Installation
1. Clone the repository to your local machine using Git:
```
git clone https://github.com/your_username/CV-Generator.git
```
Replace `your_username` with your GitHub username.

2. Install the required Python dependencies. You can use pip for this:
```
pip install -r requirements.txt
```
3. Run the application:
```
python main.py
```

## Dependencies
- `pyttsx3`: Used for text-to-speech functionality.
- `docx`: Used for generating Word documents.
