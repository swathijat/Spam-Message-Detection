# Spam Message Detector using Streamlit

This project is a spam message detector implemented using machine learning techniques and served as a
web application using Streamlit. It utilizes the NLTK library for natural language processing tasks and
pickle for model persistence. The project owner is Swathija T, a B.Tech AML (Applied Machine Learning) student.

## Overview

This project aims to classify messages as either spam or non-spam (ham) using machine learning algorithms.
It provides a user-friendly interface built with Streamlit, allowing users to input text messages and get instant
predictions on whether the message is spam or not.

## Dependencies

- Python 3.x
- Streamlit
- NLTK
- Pickle

## Usage

1. Install the required dependencies:

```bash
pip install streamlit nltk
```

2. Clone this repository:

```bash
git clone https://github.com/yourusername/spam-message-detector.git
cd spam-message-detector
```

3. Run the Streamlit app:

```bash
streamlit run main.py
```

4. Open your web browser and navigate to the provided URL (usually `http://localhost:8501`)
to access the web interface.

## Components

- `main.py`: Contains the Streamlit application code for the web interface.
- `model.pkl`: Serialized machine learning model trained for spam message classification.
- `README.md`: Documentation file providing information about the project.

## Credits

- **Swathija T**: Project owner, B.Tech AML student

## License

This project is licensed under the [MIT License](LICENSE).