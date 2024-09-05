
# Fake News Detection 

A brief description of what this project does and who it's for


## Table of Contents

Project Overview
Project Structure
Installation
Usage
Model Details
Data
Contributing
License
Contact
## Project Overview
Fake News Detection is a machine learning project aimed at classifying news articles as either real or fake. The project uses natural language processing techniques to clean and vectorize the text data, and a machine learning model is trained to make predictions based on these features. The project includes a Streamlit web application that allows users to input news content and receive a prediction on its authenticity.
## Project Structure

fake_news_detection/
│
├── data/
│   ├── train.csv              # Training dataset with labeled news articles
│
├── models/
│   ├── model.pkl              # Trained Decision Tree model
│   ├── vector.pkl             # TF-IDF Vectorizer
│
├── notebooks/
│   ├── Model_Training.ipynb   # Jupyter notebook with model training process
│
├── app.py                     # Streamlit web application
└── README.md                  # Project documentation (this file)
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Data

The dataset consists of 20,800 news articles, with labels indicating whether the article is real (0) or fake (1). The dataset is stored in train.csv.
## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Installation

To run this project locally, you need Python installed. Follow these steps:

Clone the repository:

git clone https://github.com/HaroonRasheed-ui/Fake_News_detection.git
cd fake_news_detection
Install the required packages:

pip install -r requirements.txt
    
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Usage
To launch the Streamlit app, navigate to the project directory and run:

streamlit run app.py
This will open the app in your web browser. Enter the news content you want to verify, and the app will tell you whether it's reliable or unreliable.
## Contact
For questions or inquiries, please contact Haroon Rasheed.

