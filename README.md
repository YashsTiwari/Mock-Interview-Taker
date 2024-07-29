# Mock Interview Taker with Gradio and Google PaLM

This project is a mock interview application that leverages Gradio for the user interface and Google PaLM API for generating interview questions and providing feedback. The application allows users to simulate interviews for various roles, such as Software Engineers, by asking predefined questions, collecting user responses, and offering feedback on the answers.

## Features

- **Role-Based Questions:** Generates interview questions based on the role entered by the user.
- **Feedback Mechanism:** Provides feedback on user answers to help improve responses.
- **Sequential Questioning:** Moves through questions one by one, updating the user with feedback and the next question.

## Requirements

- Python 3.7 or higher
- Gradio
- Google Generative AI (PaLM API)
- Internet connection for API calls

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/mock-interview-taker.git
   cd mock-interview-taker

2. **Configure your Google PaLM API key:**

   ```bash
   palm.configure(api_key="YOUR_API_KEY_HERE")
