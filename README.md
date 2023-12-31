# Image to Song Lyrics AI Project

The "Image to Song Lyrics AI Project" is a web application that uses Artificial Intelligence (AI) to generate personalized song lyrics from uploaded images. This creative project combines cutting-edge technologies, including image captioning, natural language models, and audio synthesis, to provide a unique and engaging user experience.

## Project Overview

This project's main goal is to explore the intersection of art and technology by converting images into song lyrics. Users can upload their favorite images, and the AI algorithms will generate song lyrics based on the content and emotions conveyed by the pictures.

The generated song lyrics are further transformed into audio using text-to-speech technology, allowing users to listen to their personalized songs. The project also provides a simple and visually appealing web interface for users to interact with the application.

## Features

- Upload images and receive personalized song lyrics based on the visual content.
- Experience a unique blend of visuals and music through AI-generated lyrics.
- Listen to the generated song lyrics in audio format.
- Simple and user-friendly web interface.
- Built-in playback controls for audio.

## Technologies Used

- Flask: Web framework for handling requests and rendering templates.
- OpenAI API: generate text lyrics that match the description of the image.
- hugging face model: leverage the "Salesforce/blip-image-captioning-base" model for highly accurate image captioning.
- gTTS (Google Text-to-Speech): Transforming generated lyrics into audio.
- HTML: Styling and structuring the web interface.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/h93n/image-to-song-lyrics-AI-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd image-to-song-lyrics-AI-project
   ```

3. Run the application:

   ```bash
   python app.py
   ```

4. Open your web browser and visit http://127.0.0.1:5000 to access the application.

## Future Enhancements

The "Image to Song Lyrics AI Project" has exciting potential for growth:

- Enhanced user interface and design improvements.
- Integration with popular music platforms for sharing generated songs.
- Fine-tuning AI algorithms to enhance the quality of generated lyrics.
- Collecting user feedback to drive improvements and updates.

