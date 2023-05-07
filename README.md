# Youtube summarizer

This is a Streamlit application that uses OpenAI's Language Model to summarize YouTube videos by generating transcripts and summarizing them into key points.

## Features

- Enter a YouTube video URL and receive a summarized transcript.
- Uses YouTube Transcript API to generate video transcripts.
- Leverages OpenAI's Language Model for summarizing the content.

## Installation

Clone this repository:
```
git clone https://github.com/G12c4/ai-self-learning-teacher.git
```

Navigate to the repository folder and install the required packages:
```
cd your-repo-name
pip install -r requirements.txt
```

Replace your-api-key with your actual OpenAI API key in the following line of code:
```
os.environ["OPENAI_API_KEY"] = "your-api-key"
```

Run the Streamlit app:
```
streamlit run app.py
```

Open the app in your browser at http://localhost:8501

## Usage
- Enter a YouTube video URL in the text input field.
- Click the "GO!" button to generate a summarized transcript.
- Review the summarized transcript displayed on the screen.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
