# LedgerFlow
LedgerFlow is a personal finance management tool that allows users to manually input income and expense data. The application will use the Gemini API to categorize each transaction into predefined categories (e.g., “Utilities”, “Food”, “Entertainment”). When these transactions are categorized, they will be used to create insightful data visualizations that show spending trends to the user. AI can also be used for personalized financial advice and future planning.  

# How to run
My proof of concept is available at: https://github.com/loganckrause/LedgerFlow/

1. **Install Python dependencies**

   Make sure you have Python 3.13.7 or newer installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. **Create a `.env` file**

   In the root of the project, create a file named `.env` and add your Gemini API key:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

3. **Run the application with Streamlit**

   Start the app using Streamlit:
   ```bash
   streamlit run src/ledgerflow/main.py
   ```

# Required Resources
* **Backend:**
  * Python, Django, Django REST Framework, SQLite
* **Frontend:**
  * React, JavaScript, HTML/CSS, Chart.js
* **AI/ML:**
  * Google Gemini API
* **Development:**
  * Git, GitHub, Virtual Environments, VS Code
* **Hardware:**
  * Standard Computer  

