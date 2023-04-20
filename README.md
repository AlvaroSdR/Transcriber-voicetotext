# Audio Transcription Program
This program transcribes audio files in MP3 format to text using the SpeechRecognition library and the Google Web Speech API. The program can handle large audio files by splitting them into smaller chunks and transcribing each chunk separately. The transcribed text is saved to a Word document (.docx) for further use.

## Prerequisites
- Python 3.x installed on your system
- SpeechRecognition library installed (can be installed using `pip install SpeechRecognition`)
- docx library installed (can be installed using `pip install python-docx`)
- pydub library installed (can be installed using `pip install pydub`)

## Usage
1. Place the audio file you want to transcribe in the same directory as the script file.
2. Update the filename in the script to match the name of your audio file, including the file format (e.g., "notes.mp3").
3. Run the script using a Python interpreter.
4. The transcribed text will be saved to a Word document named "text.docx" in the same directory as the script file.

## Error Handling
The script includes basic error handling for common issues, such as unknown value error and speech recognition request failure. However, you may need to further customize the error handling based on the specific speech recognition API you are using or other potential issues that may arise during runtime.

## Note
- The accuracy of the speech-to-text transcription may vary depending on the quality of the audio file, background noise, and the performance of the speech recognition API.
- The program expects the input audio file to be in MP3 format and named notes.mp3.
- Make sure to comply with the terms of use and privacy policies of the speech recognition API you are using.
- This script is provided as-is and may require modifications or updates based on your specific requirements.

## Disclaimer
This script is provided as is and without any warranty. Use it at your own risk.

## Contributing
If you would like to contribute to this project, please contact in advance. Any contributions are welcome!

## License
This project is licensed under the My License. In case of use, please contact in advance.

## Contact
If you have any questions or suggestions, feel free to contact me at asanchezdrio@gmail.com.

Thanks for using the voice to text trasncriber!
