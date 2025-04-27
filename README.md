# AI-Powered-Music-Therapist

# AI-Powered Therapist:Chatbot and Music Generation System


## Project Overview
This project is a Flask-based web application that simulates a therapeutic chatbot and generates personalized music to enhance user mood. Developed as a Master’s-level project, it integrates multiple AI technologies:

- **Therapist Chatbot**: Powered by Ollama’s gemma3:4b model, it engages users in empathetic dialogue, saving messages to `user.txt`.
- **Music Preferences Input**: Users specify genres/artists via a modal, saved to `final.txt`.
- **Facial Sentiment Analysis**: Uses the Facial Expression Recognition (FER) library to detect emotions from uploaded images, appending results to `final.txt`.
- **Music Generation**: Generates music prompts with Ollama’s gemma2:2b model, creates WAV tracks via the Beatoven API, and plays them in the browser.

The system, built with HTML, JavaScript, Tailwind CSS, and Python, demonstrates natural language processing (NLP), computer vision, and generative AI, showcasing their potential in mental health support and creative expression. Files (`user.txt`, `final.txt`) are cleared after successful music generation, ensuring a clean state for new interactions.


## Installation Steps
To set up the project, follow these steps:
1. Clone the Repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>

## Set Up Python Environment:
- Use Python 3.8-3.10.
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install Dependencies:
3. Install required Python libraries:
```bash
pip install flask fer opencv-python requests tensorflow
Note: fer requires TensorFlow. If installation issues occur, ensure compatibility or install TensorFlow separately: pip install tensorflow

