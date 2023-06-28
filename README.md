# Speech-to-Text and Text-to-Speech Python Program

This Python program allows you to convert speech to text and text to speech using the SpeechRecognition and pyttsx3 libraries. It utilizes the microphone as the input source to capture speech and performs speech recognition to convert it into text. It also provides the capability to convert text into speech by using text-to-speech synthesis.

## Prerequisites

To run this program, you need to have the following installed:

- Python (version 3.0 or above)
- SpeechRecognition library
- pyttsx3 library

You can install the required libraries using the following pip command:
pip install SpeechRecognition pyttsx3


## Usage

1. Run the Python script using a Python interpreter.
2. The program will continuously listen to your speech through the microphone.
3. After a brief moment of ambient noise adjustment, it will convert your speech into text using Google's speech recognition service.
4. The recognized text will be printed on the console, and the program will also convert it back to speech and play it using the default audio output device.
5. You can speak any phrase or sentence, and the program will process it accordingly.

## Customization

You can customize the program according to your needs:

- Adjust the duration parameter in the `r.adjust_for_ambient_noise(source2, duration=0.2)` line to change the time duration for adjusting the ambient noise threshold.
- Modify the speech synthesis engine settings in the `SpeakText()` function to alter the voice, speed, volume, and other characteristics of the generated speech.
- Extend the program's functionality by incorporating additional speech recognition engines or using different text-to-speech libraries.

## Dependencies

The program relies on the following libraries:

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/): Provides support for multiple speech recognition engines, including Google's Web Speech API.
- [pyttsx3](https://pypi.org/project/pyttsx3/): Enables text-to-speech synthesis using different speech synthesis engines.

Make sure to check the official documentation of these libraries for more details on their usage and customization options.

## Limitations

- The accuracy and performance of speech recognition may vary depending on the surrounding noise level, microphone quality, and speech characteristics.
- The availability and reliability of text-to-speech synthesis depend on the chosen synthesis engine and the capabilities of the audio output device.

## Resources

For more information about the libraries used in this program and speech-related functionalities in Python, refer to the following resources:

- [SpeechRecognition Documentation](https://pypi.org/project/SpeechRecognition/)
- [pyttsx3 Documentation](https://pypi.org/project/pyttsx3/)
- [Python Official Website](https://www.python.org/)

## License

This program is released under the [MIT License](LICENSE).

Feel free to modify and distribute it according to your needs.
