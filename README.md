# SakhiAI

# SakhiAI

## Overview
SakhiAI is an innovative and interactive platform designed to enhance financial literacy and promote economic empowerment. By integrating advanced AI technologies, gamified experiences, and real-time assistance, SakhiAI ensures users can learn and apply financial concepts effectively. This platform is particularly focused on addressing the financial literacy gap in rural and underprivileged communities, with a user-friendly interface tailored for accessibility.

---

## Tech Stack
- **Frontend Development Framework**: React.js
- **Backend Development Frameworks**: Node.js, Express.js, Flask, FastAPI
- **Video Streaming and Live Q&A**: WebRTC, TypeScript
- **Financial Data Integration**: `yfinance` (for fetching the latest stock market information)
- **Natural Language Processing and Query Resolution**:
  - Mistral 8x7B LLM: For natural language understanding and conversational AI.
  - Retrieval-Augmented Generation (RAG): For generating context-aware responses.
  - QDrant Vector DB: Used with RAG for real-time and efficient query resolution.
- **Daily Quiz Generation**: NLP techniques for generating engaging financial quizzes.

---

## Features
### Gamified Financial Learning
- **Visually Appealing Interface**: A game-like design to make financial education enjoyable.
- **Stock Market Analysis Game**: Learn investment strategies with simulated stock market activities.
- **2-Player Gaming Parties**: Team-based tasks encouraging collaborative learning.
- **Reward System**: Earn and redeem rewards for completing activities.
- **Interactive Gaming**: Battle monsters and complete tasks to enhance learning.
- **Competitive Leaderboard**: Track progress and foster healthy competition among users.

### Educational Tools
- **Expert Sessions**: Live interactive webinars with financial experts, including polls and Q&A.
- **Blogs and Articles**: A curated library of financial education resources.
- **Daily Quizzes and Tasks**: Regular assessments derived from blogs and random questions to reinforce learning.
- **Resource Library**: Videos, articles, and tools to support financial education.

### AI-Powered Assistance
- **Personal Assistant Chatbot**: Powered by Mistral 8x7B, offering real-time support and answering queries.
- **Financial Document Chat Support**: Upload documents for insights and explanations, with stored chat history for reference.
- **Personalized Financial Advice**: Tailored recommendations based on user data and goals.

### Financial Management Tools
- **Budgeting Tools**: Set budgets, track spending, and receive alerts for over-budget scenarios.
- **Investment Insights**: Guidance on portfolio management and risk assessment.
- **Expense Tracking**: Log daily expenses and visualize spending through charts.
- **Goal Setting**: Define financial objectives and actionable steps to achieve them.

### Accessibility and Engagement
- **Voice-to-Text and Text-to-Voice**: Enhancing accessibility for differently-abled users.
- **Real-Time User Support**: Seamless assistance for any user issues.

---

## Installation Steps

### Prerequisites
- Node.js and npm installed.
- Python 3.8 or above installed.
- `yfinance` and other dependencies for backend.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/sakhiAI.git
   cd sakhiAI
   ```

2. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

3. **Backend Setup**
   - Flask/FastAPI Setup:
     ```bash
     cd backend
     pip install -r requirements.txt
     python app.py
     ```
   - Node.js Backend:
     ```bash
     cd backend
     npm install
     npm start
     ```

4. **Database Setup**
   - Configure QDrant Vector DB for RAG implementation.
   - Connect Firebase for storing user data and images.

5. **Run the Application**
   - Start the frontend and backend servers.
   - Access the platform via `http://localhost:3000`.
