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

## Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE). Note: You might want to create a `LICENSE` file in your project directory if you want to formally specify a license.

---

Note: This application relies on the Google Gemini API. Ensure you follow Google's terms of service and usage policies when using the API key.
