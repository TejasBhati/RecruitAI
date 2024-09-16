# RecruitAI: An AI Interviewer

RecruitAI is an AI-powered autonomous interview system designed to streamline the traditional interview process. The project leverages modern AI technologies to conduct interviews, evaluate responses, and provide objective feedback. By automating interviews, RecruitAI reduces operational costs, increases fairness, and improves scalability in talent evaluation.

## Features
- **Autonomous Interviewing**: The system conducts interviews without human intervention.
- **Objective Evaluation**: AI algorithms ensure consistent and fair assessment of candidates.
- **Multimodal Interaction**: Supports both spoken and written responses using speech recognition and text input.
- **Technical Competency Assessment**: Includes coding evaluations with real-time feedback.
- **Modern Technology Stack**: Built using Python, Django, OpenAI API, Elevenlabs API, and Postman.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [System Architecture](#system-architecture)
- [Testing](#testing)
- [Future Extensions](#future-extensions)
- [Contributors](#contributors)
- [License](#license)

## Introduction
RecruitAI aims to solve the inefficiencies of traditional interviewing, such as high resource use, subjectivity, and lack of scalability. The project introduces an AI interviewer capable of assessing both technical and behavioral competencies in candidates.

## Technologies Used
- **Backend**: Python, Django
- **APIs**: OpenAI API, Elevenlabs API, Postman
- **Frontend**: Angular (optional for frontend modifications)
- **Database**: MySQL (or any compatible SQL database)
- **Cloud Services**: Azure Functions, Google Cloud Speech-to-Text
- **Testing**: Postman, JMeter, Selenium, Pytest

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/recruitai.git
    cd recruitai
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up the database:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

4. Configure API keys in `.env`:
    ```bash
    OPENAI_API_KEY=your_openai_key
    ELEVENLABS_API_KEY=your_elevenlabs_key
    ```

5. Run the server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. **Login/Register**: Users (students) can create accounts or log in to take interviews.
2. **Start Interview**: Once logged in, click "Start Interview" to begin the session.
3. **Provide Responses**: Answer questions via text or voice. Responses are processed and evaluated in real-time.
4. **View Results**: After completing the interview, users can view their scores and feedback.
5. **Admin Functions**: Admins can configure interview questions, manage users, and monitor system performance.

## System Architecture

The system is built using a modular architecture, divided into several components:

- **Frontend**: Provides the user interface for candidates and administrators.
- **Backend**: Handles API requests, database interactions, and logic for scoring and feedback.
- **Database**: Stores user data, interview results, and coding solutions.
- **Speech Recognition**: Converts spoken responses to text via Google Cloud APIs.
- **Code Execution**: Executes and evaluates coding questions through a secure environment.

## Testing

The project includes comprehensive testing to ensure system reliability:

- **Unit Tests**: Test individual components using `pytest`.
- **Integration Tests**: Ensure smooth interaction between backend and frontend components.
- **System Testing**: Full interview sessions are tested using Selenium.
- **Performance Testing**: JMeter is used to test system load with up to 100 simultaneous users.

## Future Extensions

1. **Improved Speech Recognition**: Integrate NLU for better understanding and scoring of spoken answers.
2. **Machine Learning Feedback**: Use ML models to generate personalized feedback.
3. **VR Interviews**: Implement virtual reality scenarios for immersive interview experiences.
4. **Mobile Application**: Develop a mobile app for on-the-go interview sessions.

## Contributors

- **Tejas Bhati** - Project Lead
- **Ms. Shruti Jain** - Project Mentor


