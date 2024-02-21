# Note-Taking and Learning Assistant
Welcome to the Note-Taking and Learning Assistant! This tool helps you extract and analyze text from different file types, generate quiz questions, and even create audio files for your study sessions.
## Features
- Extract text from PDF, PPT, TXT files, or provide your own paragraph.
- Generate quiz questions related to the extracted content.
- Optionally, create an audio file from the extracted text or quiz questions.
## Getting Started
**Install Dependencies**
- pip install nltk
- import nltk
- nltk.download('stopwords')
- nltk.download('punkt')
- pip install random2
- pip install python-pptx
- pip install PyMuPDF
- pip install gtts
- pip install gtts
- pip install tts-tokenizer
- pip install pyaudio
## Run the file(ipynb given)
Follow the Prompts
Choose the file type (PDF, PPT, TXT) or enter your own paragraph (topic).
Provide the file path or paragraph content as instructed.
Review extracted text and answer quiz questions.
## Example Usage
- Enter 'pdf', 'ppt', 'txt', 'topic', or 'exit': pdf
- Enter the path to the PDF file: your_file.pdf
- Do you want to answer questions about PDF content? (yes/no): yes
...
- Do you want to generate an audio file from the extracted words? (yes/no): yes
- Enter the path to save the audio file (including filename and extension): output/audio.pdf.mp3
