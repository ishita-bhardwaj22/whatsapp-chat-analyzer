whatsapp-chat-analysis

A streamlit app to analyze your whatsapp chats

Team Members Vandana — 2401560070
Ishita Bhardwaj — 2401560055 Pallavi Kumari — 2401560084

Description A WhatsApp Chat Analyzer is a tool designed to process and analyze WhatsApp chat logs to extract meaningful insights. Using Python, it can parse exported .txt chat files, identify patterns, and generate statistics on user interactions. Key Features:

    Message Frequency Analysis: Tracks how often messages are sent and received.
    Word Usage Statistics: Identifies the most frequently used words in a conversation.
    Time-Based Trends: Visualizes peak chatting hours.
    Sentiment Analysis: Detects emotional tone in messages using NLP.
    Chat Participant Activity: Breaks down conversation contributions by user.

Technologies used

Programming Language: Python 3.9+ – Core programming language used for backend logic, data processing, and visualization.

🧰 Libraries and Frameworks: Streamlit – To create the interactive web application interface. pandas – For structured data manipulation and analysis. matplotlib – To generate static visualizations like bar and line charts. seaborn – For enhanced statistical data visualizations (e.g., heatmaps). wordcloud – For generating word cloud graphics of frequent words. emoji – For parsing and analyzing emoji usage. urlextract – For extracting URLs shared in messages. re (Regular Expressions) – For parsing chat formats and cleaning text.

🛠️ Additional Tools: ChromeDriver + Selenium (optional for Android-based parsing) – For handling dynamic content (not active in the current version). Text editors & IDEs – VS Code, Jupyter Notebook, or any Python-supported IDE. Git/GitHub – For version control and collaboration (optional).

steps to run project Prerequisites Make sure you have the following installed:

Python 3.9+

pip (Python package manager)

Virtual environment (optional but recommended)

🧱 1. Set Up the Project Directory bash Copy Edit mkdir whatsapp-chat-analyzer cd whatsapp-chat-analyzer Place these files into the directory:

app.py (main Streamlit app)

helper.py (analytics functions)

preprocessor.py (chat data parser)

stop_hinglish.txt (stop words list)

📦 2. Install Required Libraries Create a virtual environment (optional):

bash Copy Edit python -m venv venv source venv/bin/activate # or venv\Scripts\activate on Windows Then install dependencies:

bash Copy Edit pip install streamlit pandas matplotlib seaborn wordcloud urlextract emoji 🚀 3. Run the Streamlit App In your terminal or command prompt, execute:

bash Copy Edit streamlit run app.py This will:

Start the Streamlit server.

Open your browser at http://localhost:8501.

📁 4. Upload WhatsApp Chat File Open WhatsApp → Chat → More → Export Chat → Without Media → Save .txt file.

Upload the .txt file using the sidebar file uploader in the app.

📊 5. Explore the Analysis The app will display:

Message stats

Activity timelines

Busiest users

WordClouds

Most common words

Emoji usage

Weekly heatmaps
