Text and Image Translator

This Python project is a text and image translation tool that utilizes the TextBlob library, NLP translation API, and other modules to provide text translation services. It includes a fun animation and a colorful command-line interface for a more interactive experience.

Features

	•	Text Translation: Translate user-input text into multiple languages such as Spanish, French, and Latin using TextBlob and external translation APIs.
	•	Colorful CLI Interface: The interface provides colored text outputs for enhanced readability and user interaction.
	•	Rocket Animation: A simple animated rocket graphic is displayed for a fun, dynamic startup.
	•	Multiple Language Support: The program supports translation between several languages including English, Spanish, French, and Latin.
	•	Error Handling: Provides exception handling to capture translation and runtime errors gracefully.

Prerequisites

Before running the program, ensure you have the following dependencies installed:

Dependencies

	•	Python 3.x
	•	requests
	•	textblob
	•	translate
	•	IPython
	•	Pillow

Installing Dependencies

To install the required libraries, you can use pip:

```bash pip install requests textblob translate pillow```
or install from the requirements.txt file:

```bash pip install -r requirements.txt```

Usage
You will also need an API key for the NLP translation service (as seen in the code). Replace the placeholder key with your own valid API key to run the translation service.

How to Run the Program

	1.	Clone the Repository: Download or clone this repository to your local machine.
	2.	Run the Program:
Use the following command to run the program:

```bash python translator.py```
    3.	Follow the on-screen instructions to input text and select the desired language for translation.


3.	Text Translation:
	•	Once the program starts, input the text you want to translate when prompted.
	•	The program will automatically translate the text into the default target language (Spanish in this case).
	•	It will display the translation results on the screen.
	4.	Language Options:
	•	The user can choose to translate the text to Spanish, French, or Latin.

Code Overview

Key Classes and Functions

	•	TextTranslate Class: This class handles text translation functionality using TextBlob and external APIs.
	•	translate_text(): Translates user-input text to English by default.
	•	translate_to_spanish(): Translates the input text to Spanish.
	•	translate_to_french(): Translates the input text to French.
	•	translate_to_latin(): Translates the input text to Latin.
	•	animate_Rocket(): A fun animation of a rocket moving up the console, displayed before the main program starts.
	•	period_wait(): A function to create a wait period with a dot animation to simulate a loading or delay effect.
	•	Colors Class: A utility class for creating colored text output in the terminal.

Example Output:
    
```
        [+]-[+] Img-Txt Translator [+]-[+]
        [+] Input the text for translation:
        Hello, how are you?
        Detected Language: English
        Translating... --> Hola, ¿cómo estás?
        [+] Translation: Hola, ¿cómo estás?
        [+] Translation to Spanish: Hola, ¿cómo estás?
        [+] Translation to French: Bonjour, comment ça va?
        [+] Translation to Latin: Salve, quomodo vales?
   ``` 


Customization

	•	You can easily modify the target languages by adjusting the parameters in the Translator() class or TextBlob methods.
	•	The rocket animation, color schemes, and other visual elements can be tweaked within the animate_Rocket() and Colors class.

License

This project is open-source and free to use under the MIT License. Feel free to contribute and make improvements.

This project showcases basic text translation functionalities with a user-friendly, colorful terminal experience. It’s perfect for practicing Python’s translation libraries, working with APIs, and creating simple animations.