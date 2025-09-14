#  Restaurant Name Generator  

A fun AI-powered app that generates **fancy restaurant names** and **creative menu items** based on your chosen cuisine.  
Built with **Streamlit**, **LangChain**, and **Google Generative AI (Gemini)**.  

---

##  Features
-  Fancy restaurant name suggestions  
-  Auto-generated menu items based on the restaurant name  
-  Interactive **Streamlit UI**  
-  Uses **LangChain SequentialChain** with two LLM chains  
-  API key management with `.env` file  

---

<p align="center">
  <img src="assets/flochart.png" alt="App Flowchart" width="500"/>
</p>


##  Project Structure
restaurant-name-generator/
│── main.py # Streamlit UI
│── langchain_helper.py # LangChain logic (chains + prompts)
│── requirements.txt # Python dependencies
│── .env # API key (ignored in GitHub)
│── README.md # Documentation
│── flo.png

## ⚙️ Installation & Setup

Install dependencies

pip install -r requirements.txt


Set up environment variables

Create a .env file in the root directory:

GOOGLE_API_KEY=your_api_key_here

Run the App
streamlit run main.py

Requirements

Python 
Streamlit
LangChain
langchain-google-genai
python-dotenv

##  Security
- `.env` file is added to `.gitignore`  

##  Example
**Cuisine chosen:** *Italian*  

-  **Restaurant Name:** La Bella Tavola  
-  **Menu Items:** Bruschetta, Margherita Pizza, Risotto alla Milanese, Tiramisu  

##  Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.  

##  License
MIT License © 2025 **Yogesh Dantkale**  