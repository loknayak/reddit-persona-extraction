# 🤖 Reddit User Persona Generator

This project was created as part of an AI/LLM Engineer Internship assignment for BeyondChats.

---

## 📌 Objective

To build a script that:
- Takes a Reddit username
- Scrapes their posts and comments
- Generates a **User Persona**
- Cites which posts/comments were used for each trait

Due to Reddit’s scraping restrictions (403/401 errors), real-time data scraping could not be performed. This notebook simulates the process using **realistic mock Reddit data**, preserving the structure and outcome of the task.

---

## 💡 Notes

**- Reddit blocked scraping/API access during development
- OpenAI made free API keys unavailable to deploy
- Project adapted to showcase prompt engineering, LLM use, and fallback logic
- This structure can be reconnected to PRAW once Reddit re-allows public scraping**

---

## ✅ Features

- 🧠 **User Persona Generation** using GPT-style prompts
- 💬 **Source Citation** for each trait (e.g., “Post 2”, “Comment 4”)
- 📄 **Persona Export** to `.txt` file
- 🚫 Handled API limitations with fallback strategy
- 🧪 Clean, documented code with prompt generation logic

---

## 🧪 Technologies Used

- Python
- Google Colab
- GPT-based Persona Generation
- Markdown + `.txt` Export

---

## 📁 Files Included

| File                         | Description                                 |
|------------------------------|---------------------------------------------|
| `Reddit_Persona_Extraction.ipynb` | Main Jupyter Notebook with all code steps |
| `reddit_user_persona.txt`        | Final generated persona from mock data     |
| `README.md`                      | This file                                   |

---

## 🛠️ How to Use

1. Open the Colab notebook
2. Review the mock Reddit-style posts & comments
3. Use the generated GPT prompt (or replace with your own)
4. Paste into [chat.openai.com](https://chat.openai.com) to generate the persona
5. Save the output in `.txt` via the notebook

---

## 👨‍💻 Author

**Lok Nayak Jaivardhan Tiwari**  
[LinkedIn](https://linkedin.com/in/loknayak) | [GitHub](https://github.com/loknayak)

---

## 📬 Contact

Feel free to connect or ask questions — happy to chat about AI, LLMs, or this project.
