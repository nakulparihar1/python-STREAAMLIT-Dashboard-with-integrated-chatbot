# VGU Streamlit Dashboard with Gemini Chatbot

This project is an interactive Streamlit-based dashboard that allows users to input personal details, view visual data representations, and chat with an integrated AI assistant powered by Google Gemini 2.5 Flash. It combines UI components, charts, tables, and an embedded chatbot to create a functional demo suitable for learning, academic projects, or college showcases.

🚀 Features

✅ Streamlit UI with inputs (name, age, course)
✅ Display table of marks
✅ Line chart and bar chart visualization
✅ Pie chart for subject-wise distribution
✅ Integrated AI chatbot using Gemini 2.5 Flash
✅ Real-time responses inside the dashboard
✅ Button interaction and clean layout

🧰 Tech Stack
Component	Technology
Frontend UI	Streamlit
AI Model	Gemini 2.5 Flash
Charts	Matplotlib & Streamlit charts
Data Handling	Pandas
📦 Installation
1. Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

2. Install dependencies
pip install streamlit pandas matplotlib google-generativeai

3. Add your Gemini API Key

Replace:

genai.configure(api_key="YOUR_API_KEY")


with your actual key.

▶️ Run the Application
streamlit run app.py


The dashboard will open in your browser automatically.

🧑‍💻 Usage

Enter your name, age, and course

View data table and charts

Ask questions in chatbot section

See instant AI responses

Click interactive UI elements

📁 Project Structure
├── app.py
├── README.md
└── requirements.txt (optional)

🤖 Chatbot Model

This project uses:

model = genai.GenerativeModel("gemini-2.5-flash")


You may swap to another model if needed.

🌱 Future Improvements (optional)

✅ Persistent chat history
✅ Student performance analytics
✅ Voice-enabled chatbot
✅ Dark/light theme toggle
✅ Database storage

📜 License

This project is free to use for learning and academic purposes.
