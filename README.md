🎧 AI Lecture Support Assistant

Overview:
This project builds an AI system that converts lecture audio into useful study materials.
The system takes an audio file as input, converts it into text, and generates a summary, key points, and study questions.

Features:
- Converts audio to text using Whisper
- Generates summary, key points, and questions using FLAN-T5
- Works with different audio formats (.mp4, .wav, .mp3)
- Supports GPU for faster execution

Technologies Used:
- Python
- Transformers (Hugging Face)
- Whisper-small (speech-to-text)
- FLAN-T5 (text generation)
- PyTorch

Project Structure:
main.py → main program
audio.mp4 → input audio file
output.txt → generated results

How to Run:
1. Install dependencies:
   pip install transformers torch sentencepiece

2. Add your audio file:
   Place your audio file in the project folder and name it "audio.mp4"

3. Run the code:
   python main.py

Output:
The system generates:
- Transcription
- Summary
- Key points
- Study questions
- Latency
Results are saved in "output.txt"

Limitations:
- Summary may be too short
- Key points may miss details
- Few questions generated sometimes
- Latency increases with long audio

Future Improvements:
- Improve summary quality
- Use larger models
- Reduce latency
- Build a user interface

AI Tools Used:
- ChatGPT → coding help
- Hugging Face → AI models

Conclusion:
This project demonstrates a complete AI pipeline from audio input to structured study materials, helping students review lectures efficiently.
