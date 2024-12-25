# Sentiment Text Analysis Platform

This project is a **Sentiment Text Analysis Platform** designed to analyze the sentiment of user-provided text inputs using the Hugging Face Inference API. The platform is built with a Flask backend, React frontend, and styled with Tailwind CSS. It offers a seamless and efficient way to classify sentiments in real-time.

## Features

- **Real-Time Sentiment Analysis**: Processes text inputs to determine sentiment with high accuracy.
- **Responsive User Interface**: Built with React and Tailwind CSS for an intuitive user experience.
- **Efficient Backend**: Flask backend integrates with the Hugging Face Inference API to handle requests and responses.
- **Optimized Performance**: Delivers results with response times under 100ms per request.

---

## Tech Stack

### Frontend
- **React.js**
- **Tailwind CSS**

### Backend
- **Flask**
- **Hugging Face Inference API**


---

## Installation

Follow these steps to run the project locally:

### Backend
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-platform.git
   cd sentiment-analysis-platform/backend
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask server:
   ```bash
   flask run
   ```

### Frontend
1. Navigate to the frontend folder:
   ```bash
   cd sentiment-analysis-platform/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

---

## Screenshots

### Home Page
![Home Page](https://res.cloudinary.com/dqm8rxpzq/image/upload/v1735116678/te1_y18q3f.png)

### Sentiment Analysis Input
![Sentiment Analysis Input](https://res.cloudinary.com/dqm8rxpzq/image/upload/v1735117001/te2_nx6ver.png)

### Analysis Results
![Analysis Results](https://res.cloudinary.com/dqm8rxpzq/image/upload/v1726409994/Screenshot_2024-09-15_194840_o3n1hz.png)

---

## API Workflow
1. **User Input**: Text is input into the frontend.
2. **API Request**: The Flask backend sends the text to the Hugging Face Inference API.
3. **API Response**: The sentiment analysis result is returned to the backend.
4. **Frontend Display**: The result is displayed to the user in a user-friendly format.

---

## Example Usage
Input Text:
> "This is the best day of my life!"

Output Sentiment:
> **Positive**

---

## Future Enhancements
- Add support for multiple languages.
- Provide more detailed sentiment insights.
- Integrate additional NLP models for advanced text analysis.

---



---

## Acknowledgments
- Hugging Face for their Inference API and pre-trained models.
- Tailwind CSS for styling.

---

For any questions or feedback, please feel free to contact me via email at [amartyapaul252@gmail.com].

