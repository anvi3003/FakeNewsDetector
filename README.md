# FakeNews Detector Web App
This project is a fork of [SachinNinja/FakeNewsDetector](https://github.com/SachinNinja/FakeNewsDetector), originally built using Flask and machine learning models to classify news articles as real or fake. I have adapted it as part of my personal learning journey.

This is a web application called FakeNews, which is designed to detect and classify fake news articles. The app is built using Flask, a Python web framework, and utilizes a machine learning model trained on four different algorithms to achieve an accuracy of approximately 94%. The model uses four features to classify news articles as either real or fake.

## 🌟 Why I Chose This Project

Fake news is a real problem — especially on platforms like WhatsApp — and it disproportionately affects vulnerable groups like the elderly and children. I want to explore how computer science can be used to **flag misinformation, build awareness**, and create **safer digital spaces**.
This project reflects my interest in:
- Social impact through technology
- Natural language processing (NLP)
- Real-world applications of AI

  
  ## 🛠️ Current Progress

While I'm still learning Python and ML, here’s what I’ve done so far:
- Forked an open-source Fake News Detector
- Studied how text is converted into features (TF-IDF)
- Understood how logistic regression models classify news
- Modified the README to reflect my purpose

  I plan to:
- Build a feature that simulates detecting WhatsApp-forwards
- Add a basic warning message for flagged items
- Customize the UI for Indian users in multiple languages


## 🧠 What I’m Learning
- Python
- Flask for basic web apps
- How classifiers are trained using real data


## Installation

To run the FakeNews web app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```bash
   cd FakeNews
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask development server:
   ```bash
   flask run
   ```

5. Open your web browser and access the app at `http://localhost:5000`.

## Project Structure

The project has the following structure:

- `static/`: This directory contains static files such as CSS stylesheets and client-side JavaScript files.
- `templates/`: This directory contains the HTML templates used by the Flask app for rendering the web pages.
- `DtModel.pkl`: A machine learning model file trained on the Decision Tree algorithm.
- `GBModel.pkl`: A machine learning model file trained on the Gradient Boosting algorithm.
- `LrModel.pkl`: A machine learning model file trained on the Logistic Regression algorithm.
- `vectorizer.pkl`: A pickle file containing the trained TF-IDF vectorizer used for text preprocessing.
- `Fake_new_detection.ipynb`: Jupyter Notebook file containing the code for training the machine learning models and performing analysis.
- `LICENSE`: The license file for the project.
- `README.md`: This file, providing information about the FakeNews web app.

## Usage

The FakeNews web app offers the following functionalities:

- **Check Latest News**: View the latest news articles and their classification as real or fake.
- **Check Fake News**: Enter a news article URL or text to check if it is real or fake.
- **Check Recent Fake News**: View the most recently detected fake news articles.
- **Report Fake News**: Report any suspicious news articles that you believe are fake.

## Contributing

Contributions to the FakeNews web app are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use, modify, and distribute the code for personal or commercial purposes.
## This project is in progress and reflects my willingness to learn, adapt, and build real solutions

## Acknowledgments

The FakeNews web app and machine learning models were developed by Hare Krishna.
