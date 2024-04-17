
# Calorific Value Calculator With Palm API

## Overview

This application is a Q&A chatbot that utilizes the `gemini-pro-vision` model from Google's generative AI to analyze images and provide information about the calorific value of food items depicted in the image.

## Prerequisites

- Python 3.6 or higher
- Streamlit
- Google's generativeai library
- dotenv
- PIL (Python Imaging Library)

## Installation

1. Clone the repository to your local machine.
2. Install the required packages using `pip install -r requirements.txt`.

## Configuration

Create a `.env` file in the root directory of the project and add your `GOOGLE_API_KEY` as follows:

```python
GOOGLE_API_KEY='your_api_key_here'
```

## Usage

To start the application, run the following command:

```python
streamlit run app.py
```

Navigate to the provided localhost URL to interact with the application.

## Features

- Image upload functionality for analyzing food items.
- Calorific value calculation based on the uploaded image.
- Detailed breakdown of calories for each food item identified.

## How It Works

1. The user uploads an image of food via the Streamlit interface.
2. The `get_gemini_response` function processes the image and input prompt to generate a response.
3. The response includes a detailed analysis of the food items and their respective calorific values.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

Please replace `'your_api_key_here'` with your actual Google API key. Ensure that you have the necessary permissions and rights to use the `gemini-pro-vision` model for your intended purposes.
