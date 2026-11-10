 💰 Finance Assistance Agent

An AI-powered conversational finance assistant built using **Python, Google Agent Development Kit (ADK), and Gemini 3.5 Flash Lite**. The project aims to make everyday financial information more accessible through a simple, interactive AI agent.

The Finance Assistance Agent helps users understand general financial concepts, organize their monthly budgets, develop saving habits, and think through their personal financial goals. It uses Google's Gemini model to understand natural-language questions and generate friendly, relevant responses.

✨ Key Features

- **Conversational Financial Assistance:** Answers general questions related to personal finance.
- **Monthly Budget Planning:** Helps users understand how to organize income and expenses.
- **Savings Guidance:** Provides general suggestions for building consistent saving habits.
- **Financial Goal Planning:** Assists users in thinking through short-term and long-term financial goals.
- **Natural Language Interaction:** Allows users to communicate with the agent using everyday language.
- **AI-Powered Responses:** Uses Gemini to generate contextual responses to user queries.

🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Google ADK | AI agent development and orchestration |
| Gemini 3.5 Flash Lite | Language model powering the assistant |
| Google AI Studio API | Gemini API access |
| python-dotenv | Environment variable management |

🏗️ Project Structure

```text
ADK_FINANCE_ASSISTANCE_AGENT/
│
├── finance_assistance_agent/
│   ├── __init__.py
│   └── agent.py
│
├── .env
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```

 ⚙️ Installation and Setup

 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd ADK_FINANCE_ASSISTANCE_AGENT
```

2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

 4. Configure the API key

Create a `.env` file and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_google_api_key
```

Get your API key from [Google AI Studio](https://aistudio.google.com/apikey).

5. Run the application

From the parent directory containing `finance_assistance_agent`, execute:

```bash
adk web
```

Open the local URL displayed in the terminal to interact with the Finance Assistance Agent.

💡 Example Queries

Users can interact with the assistant using questions such as:

- How can I create a monthly budget?
- What is an emergency fund?
- How can I develop a regular saving habit?
- How should I plan my financial goals?
- What are the basic financial concepts I should understand?

🎯 Project Objective

The primary objective of this project is to explore the development of AI-powered agents using Google's Agent Development Kit and Gemini models, while applying conversational AI to a practical personal finance use case.

🔮 Future Enhancements

- Expense tracking and categorization.
- Personalized budget recommendations.
- Integration with financial data sources.
- Interactive financial reports and visualizations.
- Persistent conversation and user preference management.

 ⚠️ Disclaimer

This project is intended for educational purposes and provides general financial information only. It does not replace professional financial, investment, tax, or legal advice.

---

**Built with Python, Google ADK, and Gemini AI.**

