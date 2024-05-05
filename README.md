# AyurTech Medicine Recommender

This Streamlit web application recommends medicines based on selected symptoms. It utilizes similarity vectors calculated from medicine data to provide relevant recommendations.

## Features

- Select symptoms from a dropdown menu.
- Click "Recommend Medicine" to see the top 5 recommended medicines along with their dosage, contraindications, and Ayurvedic names.
- Save recommendations to a CSV file.
- Background image for the sidebar.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/ayurtech-medicine-recommender.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ayurtech-medicine-recommender
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## Usage

1. After running the app, select your symptoms from the dropdown menu.
2. Click "Recommend Medicine" to view the top 5 recommended medicines.
3. Optionally, click "Save Recommendations to CSV" to save the recommendations to a CSV file named 'recommendations.csv'.

## Files

- `app.py`: Main Python script containing the Streamlit application.
- `data - Sheet1.csv.df.pkl`: Pickled dataframe containing medicine data.
- `similarity.pkl`: Pickled similarity vectors.
- `css/style.css`: External CSS file for custom styling.
- `images/ayurveda.jpg`: Background image for the sidebar.

## Requirements

- Python 3.x
- Streamlit
- Pandas
- Pillow
- Pickle
- Base64

