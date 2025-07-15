# GenAI Reddit Persona Generator

This project analyzes Reddit users and generates personality profiles using LLMs (Cohere).

## 🧠 Technologies
- PRAW (Reddit API)
- Cohere `command-r-plus` model
- Python 3.12
- dotenv for API key management

## 📂 Project Structure
GEN AI Project/
├── data/ # Raw Reddit JSON data
├── outputs/ # Final generated persona profiles
├── reddit_scraper.py # Main script
├── .env # API key (Cohere only)
├── requirements.txt
└── README.md


## ✅ Usage

1. Add your Cohere API key to `.env`:
COHERE_API_KEY=your_api_key

2. Run the script:
```bash
python reddit_scraper.py

3. Persona results will be saved to outputs/username_persona.txt

👤 Users Analyzed
kojied

Hungry-Move-6603


✨ Output
Each file contains:

Tone & writing style

Beliefs & values

Hobbies and subreddit behavior

## 📸 Sample Output

Here’s a generated persona preview for user `kojied`:

![Kojied Preview](https://raw.githubusercontent.com/Rushikesh1912/reddit-persona-genai/main/Images/kojied.jpg)

Here’s a generated persona preview for user `Hungry-Move-6603`:


## 🧪 Sample Hungry Preview

<img src="https://github.com/Rushikesh1912/reddit-persona-genai/blob/main/Images/Hungry-Move.jpg" alt="Hungry Preview" width="400"/>

