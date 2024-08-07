# FIT-TRACK
FitTrack is a web application built with Streamlit that calculates your BMI and provides personalized diet and workout recommendations. The recommendations are generated using Google’s Generative AI (Gemini API).

# Features:
BMI Calculation
BMI Categorization (underweight, normal weight, overweight, obese)
Ideal Weight Range Determination
Personalized Diet and Workout Recommendations
Additional Health Tips

# Technologies Used:
Python
Streamlit
Google Generative AI
dotenv

# Installation:
1. Clone the repository: git clone https://github.com/your-username/fittrack.git
2. Install the required packages: pip install streamlit python-dotenv google-generativeai
3. Create a .env file and add your Google API key: make a file with your api key --> API_KEY=your_google_api_key_here
4. Run the application: streamlit run app.py

# Usage:
Enter your name, age, height, and weight.
Click "Calculate BMI and Get Recommendations" to see your BMI, ideal weight range, and personalized health recommendations.
