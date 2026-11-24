# AI Video and Meeting Assistant

A Python application that converts video or meeting audio into text, summaries and useful notes.

## About the Project

Watching long videos or listening to complete meeting recordings can take a lot of time.

This project helps users understand recordings more quickly. It converts speech into text, generates summaries and allows users to ask questions about the transcript.

## How It Works

1. Provide a supported YouTube link or local media file.
2. Extract the audio from the recording.
3. Convert the audio into a suitable format.
4. Split long audio into smaller sections.
5. Convert speech into text using speech recognition.
6. Generate a summary using a language model.
7. Extract important points, decisions and action items.
8. Store transcript sections in a vector database.
9. Allow users to ask questions about the recording.

## Technologies Used

- Python
- Streamlit
- Whisper
- Sarvam AI
- Mistral AI
- LangChain
- Hugging Face
- ChromaDB
- FFmpeg
- Pydub
- yt-dlp

## Main Features

- Audio and video processing
- Speech-to-text conversion
- Automatic summaries
- Meeting notes
- Action item extraction
- Important decision extraction
- Transcript-based question answering
- Semantic search using embeddings

## What I Learned

I learned how speech recognition works, how to process audio files, how language models generate summaries and how vector databases can be used to search through text.

I also learned how to connect different AI services in one application.

## Future Improvements

- Support more languages.
- Improve transcription quality.
- Add speaker identification.
- Allow direct file uploads.
- Improve summary generation.
- Add export options for meeting notes.
- Improve error handling.

## Note

The quality of the transcript and summary depends on audio clarity, speech recognition and the language model. API access may be required for some features.
