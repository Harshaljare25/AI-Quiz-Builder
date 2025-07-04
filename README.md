# AI Quiz Builder

## Project Description

The AI Quiz Builder is a web application that uses Artificial Intelligence to create custom multiple-choice quizzes on any topic. Users input a topic, and the application connects to the Google Gemini API to fetch relevant questions, which are then shown interactively on the page.

This project highlights modern web development practices, such as responsive design, asynchronous API communication, and organized data handling from AI models.

## Features

* **AI-Powered Question Generation:** It generates multiple-choice quiz questions based on user-provided topics using the Google Gemini API.
* **Structured Output:** The Gemini API's `responseSchema` ensures questions, options, and correct answers are returned in a consistent JSON format.
* **Intuitive User Interface:** A clean, responsive design built with Tailwind CSS provides a smooth user experience on various devices.
* **Real-time Feedback:** It shows a loading spinner during AI processing and delivers clear error messages for any issues.
* **Dynamic Content Display:** Questions are rendered on the fly, with correct answers highlighted for easy review.
* **Lightweight & Self-Contained:** The entire application is in a single HTML file, making it easy to deploy and run.

## Technologies Used

* **HTML5:** For the basic structure of the web page.
* **CSS3 (Tailwind CSS):** A utility-first CSS framework for quick and responsive styling.
* **JavaScript (ES6+):** For all interactive functions, API calls, and DOM manipulation.

## How to Run Locally

To set up this project on your local machine, follow these steps:

1. **Obtain a Google Gemini API Key:**
   * Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
   * Sign in with your Google account.
   * Create a new API key. This key is crucial for the application to communicate with the Gemini AI.

2. **Save the Code:**
   * Create a new file on your computer, for example, `index.html`.
   * Copy and paste the entire HTML code (provided in the previous responses) into this `index.html` file.

3. **Insert Your API Key:**
   * Open the `index.html` file in a text editor (like VS Code, Notepad++, Sublime Text, etc.).
   * Find the JavaScript section (within the `<script>` tags).
   * Locate the line:
        ```javascript
        const apiKey = "YOUR_API_KEY_HERE";
        ```
   * Replace `"YOUR_API_KEY_HERE"` with the actual API key you received from Google AI Studio. Make sure to keep the quotes around your key.

4. **Open in Browser:**
   * **Method A (Recommended for VS Code users):**
       * If you're using VS Code, install the "Open in Browser" extension (search for it in the Extensions view).
       * Right-click anywhere in the `index.html` editor and select "Open in Default Browser."
   * **Method B (Manual):**
       * Go to the folder where you saved `index.html` using your file explorer.
       * Double-click the `index.html` file. It will open in your default web browser.

You should now see the AI Quiz Builder running in your browser.

## Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE). Note: You might want to create a `LICENSE` file in your project directory if you want to formally specify a license.

---

Note: This application relies on the Google Gemini API. Ensure you follow Google's terms of service and usage policies when using the API key.
