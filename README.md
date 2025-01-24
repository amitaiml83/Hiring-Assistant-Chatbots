# Technical Interview Evaluation System Chatbots using AI

## Overview
The **Technical Interview Evaluation System** is a Streamlit-based web application designed to streamline the technical interview process. It collects candidate details, generates technical questions based on their chosen tech stack, evaluates their responses using AI, provides feedback, assigns scores, and saves all responses in a structured format.

## Features
- **Candidate Data Collection:** Inputs for name, email, phone number, experience, desired position, location, and tech stack.
- **AI-Generated Technical Questions:** Uses the Hugging Face model `Mistral-7B-Instruct-v0.3` to generate relevant questions.
- **Automated Answer Evaluation:** Evaluates candidate responses using AI, providing feedback and scores.
- **Score Calculation:** Assigns scores based on answer correctness and depth.
- **JSON Data Storage:** Saves responses and scores for record-keeping.
- **Streamlit UI:** Simple and interactive user interface for seamless interview assessment.

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python
- **AI Model:** Mistral-7B-Instruct-v0.3 (Hugging Face)
- **Database:** JSON file storage

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Streamlit
- Hugging Face Transformers
- JSON handling libraries

### Setup
```sh
# Clone the repository
git clone <repository-url>
cd technical-interview-evaluation

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

## Usage
1. Open the web application in a browser after running the Streamlit app.
2. Enter candidate details.
3. The system generates technical questions based on the tech stack.
4. Candidates submit their responses.
5. AI evaluates answers, provides feedback, and assigns scores.
6. The results are stored in a JSON file.

## Folder Structure
```
📂 technical-interview-evaluation
│-- 📜 app.py                 # Main Streamlit application
│-- 📜 requirements.txt       # Dependencies
│-- 📜 README.md              # Project Documentation
│-- 📂 data                   # Stores JSON responses
│-- 📂 models                 # AI model integration (if applicable)
```

## Future Enhancements
- **Database Integration:** Move from JSON to SQL/NoSQL database.
- **Admin Dashboard:** Add analytics for interview performance tracking.
- **Multiple AI Models:** Option to switch between different AI models.

## Contributing
Contributions are welcome! Feel free to fork the repo and submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
**Amit Kumar**  
[LinkedIn](https://www.linkedin.com/in/amit-kumar83/)  
[GitHub](https://github.com/amitaiml83/)
