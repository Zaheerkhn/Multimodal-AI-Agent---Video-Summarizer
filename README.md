# Multimodal AI Agent - Video Summarizer

## Overview
The **Multimodal AI Agent - Video Summarizer** is a Streamlit-based application powered by **Gemini AI**. It enables users to upload video files and ask questions related to the video content. The AI agent processes the video, performs supplementary web research using **DuckDuckGo**, and generates insightful responses.

## Features
- 📹 **Upload and analyze videos** (MP4, MOV, AVI formats)
- 🧠 **AI-powered video understanding** using Google's Gemini
- 🔍 **Web search integration** for enhanced context
- 💡 **Detailed, user-friendly insights** based on video content

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- Python 3.8+
- pip
- Streamlit
- Docker (if using PostgreSQL for data storage)

### Clone the Repository
```sh
git clone https://github.com/Zaheerkhn/Multimodal-AI-Agent---Video-Summarizer
cd multimodal-ai-video-summarizer
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Environment Variables
Create a `.env` file in the project root directory and add your **Google API Key**:
```sh
GOOGLE_API_KEY=your_google_api_key
```

## Usage
### Run the Application
```sh
streamlit run app.py
```

### Using the App
1. Upload a video file (MP4, MOV, AVI formats).
2. Enter your question or query about the video content.
3. Click **Analyze Video**.
4. The AI agent will process the video and provide an insightful response.

## Technologies Used
- **Streamlit** - UI framework for the application
- **Google Gemini AI** - AI model for video analysis
- **DuckDuckGo** - Web search tool for additional insights
- **PostgreSQL (Optional)** - Data storage using pgvector

## License
This project is open-source and available under the **Apache License 2.0**.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Contact
For any questions, feel free to reach out or create an issue in the repository.

