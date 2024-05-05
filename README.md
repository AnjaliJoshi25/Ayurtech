# AyurTech Medicine Recommender
This Streamlit web application recommends medicines based on selected symptoms. It utilizes similarity vectors calculated from medicine data to provide relevant recommendations.

Features
Select symptoms from a dropdown menu.
Click "Recommend Medicine" to see the top 5 recommended medicines along with their dosage, contraindications, and Ayurvedic names.
Save recommendations to a CSV file.
Background image for the sidebar.
Installation
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/ayurtech-medicine-recommender.git
Navigate to the project directory:
bash
Copy code
cd ayurtech-medicine-recommender
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:
bash
Copy code
streamlit run app.py
Usage
After running the app, select your symptoms from the dropdown menu.
Click "Recommend Medicine" to view the top 5 recommended medicines.
Optionally, click "Save Recommendations to CSV" to save the recommendations to a CSV file named 'recommendations.csv'.
Files
app.py: Main Python script containing the Streamlit application.
data - Sheet1.csv.df.pkl: Pickled dataframe containing medicine data.
similarity.pkl: Pickled similarity vectors.
css/style.css: External CSS file for custom styling.
images/ayurveda.jpg: Background image for the sidebar.
Requirements
Python 3.x
Streamlit
Pandas
Pillow
Pickle
Base64
License
This project is licensed under the MIT License - see the LICENSE file for details.
