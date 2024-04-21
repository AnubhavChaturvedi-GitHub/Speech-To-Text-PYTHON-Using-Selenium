# Advanced Speech to Text Recognition using Selenium

![Output](https://github.com/AnubhavChaturved1/Python-STT/blob/main/Screenshot%202024-04-13%20151959.png)

This Python script utilizes Selenium to perform advanced speech to text recognition. It interacts with a specific website to transcribe speech input from the user and save it to a text file.

## Prerequisites

- Python 3.11.4
- Selenium
- Chrome WebDriver
- Chrome Browser
- Webdriver Manager
- Operating System: Windows (for file path handling)

## Installation

1. Install Python (if not already installed) from [python.org](https://www.python.org/).
2. Install required Python packages using pip:
   ```
   pip install selenium webdriver-manager
   ```
3. Download and install the Chrome WebDriver compatible with your Chrome browser version. You can also use the `ChromeDriverManager` provided by `webdriver-manager` to automatically manage WebDriver installation.

## Usage

1. Clone or download this repository to your local machine.
2. Navigate to the directory containing the script.
3. Ensure your Chrome browser is installed and up-to-date.
4. Run the script using the following command:
   ```
   python speech_to_text.py
   ```
5. Once the script is running, it will open a Chrome browser window and navigate to the specified website.
6. Click on the "Start" button on the website to activate speech recognition.
7. Speak into your microphone when prompted.
8. The recognized text will be displayed in the console and saved to a text file named `INPUT_TEXT.txt` in the `DATA` directory.

## Configuration

- Modify the `website` variable in the script to specify the URL of the website hosting the speech recognition interface.
- Ensure the Chrome browser options (`chrome_options`) are configured according to your requirements. Currently, it is set to run in headless mode and enable fake UI for media stream.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
