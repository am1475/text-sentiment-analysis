Sentiment Text Analysis Platform

This project is a Sentiment Text Analysis Platform designed to analyze the sentiment of user-provided text inputs using the Hugging Face Inference API. The platform is built with a Flask backend, React frontend, and styled with Tailwind CSS. It offers a seamless and efficient way to classify sentiments in real-time.

Features

Real-Time Sentiment Analysis: Processes text inputs to determine sentiment with high accuracy.

Responsive User Interface: Built with React and Tailwind CSS for an intuitive user experience.

Efficient Backend: Flask backend integrates with the Hugging Face Inference API to handle requests and responses.

Optimized Performance: Delivers results with response times under 100ms per request.

Tech Stack

Frontend

React.js

Tailwind CSS

Backend

Flask

Hugging Face Inference API

Deployment

Hosted on Vercel (Frontend)

Backend hosted on Heroku or similar platform.

Installation

Follow these steps to run the project locally:

Backend

Clone the repository:

git clone https://github.com/your-username/sentiment-analysis-platform.git
cd sentiment-analysis-platform/backend

Install dependencies:

pip install -r requirements.txt

Run the Flask server:

flask run

Frontend

Navigate to the frontend folder:

cd sentiment-analysis-platform/frontend

Install dependencies:

npm install

Start the development server:

npm start

Screenshots

Home Page



Sentiment Analysis Input



Analysis Results



API Workflow

User Input: Text is input into the frontend.

API Request: The Flask backend sends the text to the Hugging Face Inference API.

API Response: The sentiment analysis result is returned to the backend.

Frontend Display: The result is displayed to the user in a user-friendly format.

Example Usage

Input Text:

"This is the best day of my life!"

Output Sentiment:

Positive

Future Enhancements

Add support for multiple languages.

Provide more detailed sentiment insights.

Integrate additional NLP models for advanced text analysis.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Hugging Face for their Inference API and pre-trained models.

Tailwind CSS for styling.

For any questions or feedback, please feel free to contact me via email at [your-email@example.com].

