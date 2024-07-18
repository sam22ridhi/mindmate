MindMate: Your Personal Mental Health Companion
Overview
Welcome to MindMate, a comprehensive mental health chatbot designed to provide emotional support, practical advice, and resources for individuals seeking mental well-being. Built using Streamlit and Azure's OpenAI, MindMate offers a variety of therapist personas to cater to different needs, from general support to cognitive behavioral therapy.

Features
Interactive Chat: Engage in meaningful conversations with MindMate, designed to offer empathy, support, and guidance.
Multiple Therapist Personas: Choose from different therapist templates like Counsellor, Cognitive Behavioral Therapist, Student Counsellor, Psychologist, and Best Friend.
Session Management: Save, load, and delete sessions, ensuring your conversations are accessible whenever you need them.
Multilingual Support: Communicate in various languages, making mental health support accessible to a broader audience.
Conversation Insights: Generate insights and summaries from your sessions, helping you track progress and understand your mental health journey better.
Secure and Private: All conversations are stored securely, respecting user privacy and confidentiality.
Setup
Prerequisites
Python 3.8 or higher
Streamlit
Azure OpenAI credentials
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/mindmate.git
cd mindmate
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the root directory with the following content:

env
Copy code
AZURE_BASE_URL=your_azure_base_url
AZURE_DEPLOYMENT_NAME=your_azure_deployment_name
AZURE_OPEN_API_KEY=your_azure_open_api_key
Running the Application
Run the Streamlit application:

sh
Copy code
streamlit run app.py
Usage
Navigation
MindMate provides a sidebar for easy navigation through different sections:

Today: Overview and daily mental health tips.
Sessions: Manage your chat sessions, including starting new ones, loading existing ones, and deleting sessions.
Tools: Access various mental health tools and resources.
Therapists: Choose from different therapist personas to guide your conversations.
Insights: Generate and view insights from your sessions.
Settings: Customize your MindMate experience.
How to use?: Instructions on how to use MindMate effectively.
Starting a Session
Select "Sessions" from the sidebar.
Click "Start a new session" to begin a conversation.
Choose a therapist persona and language for the session.
Engage in a meaningful conversation with MindMate.
Managing Sessions
Load Sessions: Automatically load previously saved sessions upon startup.
Save Sessions: Your session is saved automatically after each interaction.
Delete Sessions: Remove unwanted sessions from the database.
Therapist Personas
Choose from various therapist personas to customize your experience:

Counsellor: Compassionate and empathetic, providing emotional support.
Cognitive Behavioral Therapist: Specialized in cognitive-behavioral techniques.
Student Counsellor: Assists students with academic, social, and emotional challenges.
Psychologist: Provides evidence-based psychological support.
Best Friend: Offers a casual, friendly, and comforting presence.
Generating Insights
Select "Insights" from the sidebar.
Choose a session to analyze.
View a summary of the conversation and mood analysis.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Streamlit
Azure OpenAI
Contact
For any questions or support, please reach out to [your-email@example.com].

Thank you for using MindMate. We hope it brings you the support and comfort you need on your mental health journey.
