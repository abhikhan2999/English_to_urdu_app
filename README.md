# English_to_urdu_app
Here's a detailed and impressive README for your code:

---

# English to Urdu Translation App

## Overview

The English to Urdu Translation App is a powerful and user-friendly application that allows users to translate English videos, audio, and text into Urdu. Utilizing state-of-the-art machine learning models and natural language processing techniques, this app extracts audio from videos, transcribes the audio, translates the text into Urdu, and generates an Urdu audio file. Finally, it combines the Urdu audio with the original video, producing a seamless translated video.

## Features

- **Video Translation**: Upload or record an English video and get it translated into Urdu.
- **Audio Translation**: Upload an English audio file and convert it into an Urdu audio file.
- **Text Translation**: Enter English text or upload a text file and translate it into Urdu audio.
- **Real-time Video Recording**: Record a video using your webcam and translate it directly within the app.

## Technologies Used

- **Streamlit**: For creating the web interface.
- **MoviePy**: For video and audio processing.
- **PyTorch**: For utilizing pre-trained machine learning models.
- **Transformers (Hugging Face)**: For transcription and translation.
- **gTTS**: For generating Urdu audio.
- **OpenCV**: For handling video frames.
- **Streamlit-webrtc**: For real-time video recording.

## Installation

To run this app locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/english-to-urdu-translation-app.git
    cd english-to-urdu-translation-app
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

### Video Translation

1. **Upload Video**: Select the "Upload Video" option and choose a video file (mp4, avi, mov).
2. **Record Video**: Select the "Record Video" option to record a video using your webcam.
3. Click on "Translate Video" to process and translate the video. The translated video will be displayed on the screen.

### Audio Translation

1. Select the "Upload Audio" option and choose an audio file (mp3, wav).
2. Click on "Translate Audio" to process and translate the audio. The translated audio will be available for playback.

### Text Translation

1. **Enter Text**: Select the "Enter Text" option and input your English text.
2. **Upload Text File**: Select the "Upload Text File" option and choose a text file (txt).
3. Click on "Translate Text" to process and translate the text. The translated audio will be available for playback.

## Special Tributes to My Mentors

I would like to express my gratitude to the following mentors who have greatly influenced my journey:

- [Andrew Ng](https://learn.deeplearning.ai/): For his invaluable contributions to AI education.
- [Irfan Malik](https://www.youtube.com/channel/UCKc0J2A7znmiFwIjXUvmdvw): For his insightful YouTube tutorials.
- [Ammar Tufail](https://www.youtube.com/@Codanics): For his excellent coding tutorials on Codanics.

Their guidance and resources have been instrumental in my learning journey.

## Creator

- **Abbas Khan**
    - Email: [abhikhan2999@gmail.com](mailto:abhikhan2999@gmail.com)
    - LinkedIn: [Abbas Khan](https://www.linkedin.com/in/abhi-khan-71467526b/)

---

Feel free to customize this README further to suit your needs!
