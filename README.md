# Transcribe-

A simple single-page tool to transcribe video or audio files using OpenAI's speech API.
The page now supports uploading any common audio or video format and allows you to
specify how many speakers are present along with their names.

Open `index.html` in a browser, paste your API key, choose your file, select a language (or use Auto) and click **Transcribe**. The app uses the `gpt-4o-transcribe` model with word-level timestamps and speaker diarization. When done a text file of the transcript can be downloaded.
