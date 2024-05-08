# Speech-to-Transcript
Speech to Transcript using Python and Flask.

This is an example of [TheCodex project code for speech recognition](https://github.com/TheCodex-Me/Projects)
<br></br>

---
### To run (Personally used Visual Studio Code but should not matter on the IDE):
* Clone the project
* Ensure you set up a virtual environment
  * Navigate to the project directory if not already in it within the terminal/comand prompt
  * Initialize the virtual environment:
    * Windows (PowerShell):
      * `python -m venv env`
    * macOS or Linux:
      * `python3 -m venv env`
  * Activate the virtual environment:
    * Windows (Command Prompt):
      * `.\env\Scripts\activate`
    * Windows (PowerShell):
      * `.\env\Scripts\Activate.ps1`
    * macOS or Linux:
      * `source env/bin/activate`
* Install packages in the terminal/comand prompt:
  * `pip install Flask`
  * `pip install SpeechRecognition`
* Run as a local server with `flask run`
  * You should be given a localhost link to open in your browser and view the program.

 ---
 ### Upload audio files in .wav
 Use this converter from mp3 to wav if needed: https://cloudconvert.com/mp3-to-wav
