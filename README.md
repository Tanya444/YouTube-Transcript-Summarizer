# YouTube-Transcript-Summarizer Project
This project is a Chrome extension that allows users to summarize the transcript of YouTube videos using text summarization techniques.
# Features
-Extracts transcript from YouTube videos.
-Utilizes Hugging face transformers-based NLP model- BART(Bidirectional and Auto-Regressive Transformers) for text summarization.
-Provides a user-friendly popup interface for summarization.
-Displays summarized content in the popup.
# Setup
-Clone the repository:
git clone https://github.com/your-username/YouTube-Transcript-Summarizer.git
-Set up the local server:
Install required Python packages: pip install flask youtube_transcript_api transformers
Run the server: python app.py
-Load the Chrome extension:
Open Chrome and go to chrome://extensions/.
Enable "Developer mode".
Click "Load unpacked" and select the extension folder.
# Usage
-Click on the extension icon in the Chrome toolbar to open the popup.
-Click the "Summarise" button to initiate the summarization process.
-The extension will fetch the active tab's URL and send a request to the local server.
-The summarized content will be displayed in the popup when the response is received.
# Contributing
Contributions are welcome! If you find a bug or have an enhancement idea, please open an issue or submit a pull request.
