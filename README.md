# SakhiAI

SakhiAI is an AI-powered financial empowerment platform designed to address the unique financial literacy challenges faced by rural women in India, combining advanced AI with gamification for an engaging and interactive experience. The platform offers localized, voice-driven financial education with tutorials in regional languages, simple visuals, and gamified modules on budgeting, savings, and loans. It includes AI-powered financial tools like micro-investment options, expense tracking, loan assistance with visual EMI calculators, and personalized financial goal-setting. 

Furthermore, SakhiAI integrates secure, easy-to-use banking features, such as single-tap UPI transactions and voice-activated banking. The platform also incorporates a personalized gamification interface, where users can engage in stock price analysis games, form two-player teams for collaborative problem-solving, and earn rewards for completing tasks. A rewards system boosts confidence and increases engagement, with achievements unlocking skins, potions, and a competitive leaderboard. The platform includes expert-led sessions, live Q&A, and financial blogs to provide continuous learning. Users can also access a real-time dashboard for tracking progress with visual charts and a daily to-do list featuring quizzes and tasks based on financial articles and random topics. 

Additionally, SakhiAI supports seamless user assistance with a personalized chatbot powered by Mistral, financial document chat support for uploading and analyzing financial documents, and a stock market analysis game designed to help users with no prior finance knowledge improve their investment skills. The platform uses RAG and Qdrant vector DB for efficient data handling and enables community support through virtual mentorship, peer groups, and AI-based advisor matching. With offline accessibility, biometric authentication, and blockchain-based transaction logging for security, SakhiAI is built on a robust technology stack, including cloud hosting and regional language support. It is scalable, with plans to expand to other regions and a sustainable revenue model based on premium features and partnerships with banks and financial institutions. SakhiAI’s impact is measured by the number of rural women onboarded, growth in micro-investments, reduction in financial fraud, and increased savings and income stability for users.

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
