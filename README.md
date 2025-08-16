video :

# crop_sell
🌱 Smart Crop Price Advisor – Agriculture-G-AI

A Streamlit web app powered by Google Gemini AI that helps farmers and agri-businesses analyze crop price trends across regions and get best selling time recommendations for maximum profit.

🚀 Features

✅ AI-powered crop price analysis (MSP, wholesale, retail, private buyers).

✅ Location-based predictions (City/District/State).

✅ 6-month future trend forecast.

✅ Comparative price table with insights.

✅ Suggests best time to sell for maximum profit.

✅ Modern UI with custom theme (green & agri-friendly).

🛠️ Tech Stack

Python 3.11.0

Streamlit – Web UI framework

Google Generative AI – Gemini API for price predictions

HTML/CSS – Custom styling

📂 Project Structure
Smart-Crop-Price-Advisor/
│── app.py               # Main Streamlit app  
│── requirements.txt      # Dependencies  
│── README.md             # Project documentation  

📦 Installation

Clone the repository

git clone https://github.com/your-username/Smart-Crop-Price-Advisor.git
cd Smart-Crop-Price-Advisor


Create a virtual environment (Recommended)

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt


Set up Gemini API Key

Go to Google AI Studio.

Create an API Key.

Create a .env file in the project root:

GEMINI_API_KEY=your_api_key_here

▶️ Run the App
streamlit run app.py

📌 Example Workflow

Select a crop (e.g., Wheat, Rice, Maize).

Enter a location (City/District/State).

Click 📊 Analyze Prices & Recommend Best Selling Time.

Get:

📈 Price comparison table (MSP, Market, Private buyers).

🔮 AI-predicted 6-month price trend.

🌾 Recommendation on best time to sell.

✅ Requirements File (requirements.txt)
streamlit==1.37.0
google-generativeai==0.7.2
python-dotenv==1.0.1

🎯 Future Improvements

Add real-time mandi price API integration.

Multi-language support (English, Hindi, Kannada, etc.).

Farmer login dashboard with saved analyses.

Graph visualization of price trends.

🙌 Acknowledgements

Google Gemini API

Streamlit Community

Farmers & Agri Innovators 🌱
