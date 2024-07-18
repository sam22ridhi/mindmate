Here is a shortened version of your MindMate README file:

---

# MindMate: Your Personal Mental Health Companion

## Overview
MindMate is a comprehensive mental health chatbot built with Streamlit and Azure OpenAI. It offers emotional support, practical advice, and resources through various therapist personas.

## Features
- **Interactive Chat**: Engage in supportive conversations.
- **Multiple Therapist Personas**: Choose from Counsellor, Cognitive Behavioral Therapist, Student Counsellor, Psychologist, and Best Friend.
- **Session Management**: Save, load, and delete sessions.
- **Multilingual Support**: Communicate in multiple languages.
- **Conversation Insights**: Generate summaries and insights.
- **Secure and Private**: Ensures user privacy and confidentiality.

## Setup
### Prerequisites
- Python 3.8 or higher
- Streamlit
- Azure OpenAI credentials

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/mindmate.git
    cd mindmate
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
3. Set up environment variables:
    Create a `.env` file in the root directory with:
    ```env
    AZURE_BASE_URL=your_azure_base_url
    AZURE_DEPLOYMENT_NAME=your_azure_deployment_name
    AZURE_OPEN_API_KEY=your_azure_open_api_key
    ```

### Running the Application
Run the Streamlit application:
```sh
streamlit run app.py
```

## Usage
### Navigation
- **Today**: Daily mental health tips.
- **Sessions**: Start, load, and manage chat sessions.
- **Tools**: Access mental health tools and resources.
- **Therapists**: Choose therapist personas.
- **Insights**: View session insights.
- **Settings**: Customize your experience.
- **How to use?**: Instructions for effective use.

### Starting a Session
1. Go to "Sessions".
2. Click "Start a new session".
3. Choose a therapist persona and language.

### Managing Sessions
- **Load**: Automatically load previous sessions.
- **Save**: Sessions are saved automatically.
- **Delete**: Remove unwanted sessions.

### Therapist Personas
- **Counsellor**: Compassionate and empathetic support.
- **Cognitive Behavioral Therapist**: Specialized techniques.
- **Student Counsellor**: Academic and social support.
- **Psychologist**: Evidence-based psychological support.
- **Best Friend**: Friendly and comforting presence.

### Generating Insights
1. Go to "Insights".
2. Select a session to analyze.
3. View the summary and mood analysis.

## Contributing
Fork the repository and submit a pull request with your changes.

## License
Licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- Streamlit
- Azure OpenAI

## Contact
For support, email [your-email@example.com].

Thank you for using MindMate. We hope it brings you support and comfort on your mental health journey.

---

You can customize this template further based on your preferences.
