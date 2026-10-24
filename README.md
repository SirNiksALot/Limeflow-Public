# Limeflow Recruit 🚀

> **Building an Ecosystem of Enterprise Apps Powered by Agentic AI**

Limeflow Recruit is an intelligent, AI-powered interview platform designed to simulate hyper-realistic technical and behavioral interviews. By leveraging advanced context engineering and a universal context management system, Limeflow evaluates candidate problem-solving journeys, intellectual agility, and collaboration skills—moving beyond static pass/fail testing.

---

## 🎬 Demo Video

[![Limeflow Demo Video](https://img.shields.io/badge/Watch%20Demo-Video-brightgreen?style=for-the-badge&logo=playstation)](https://github-production-user-asset-6210df.s3.amazonaws.com/83578131/683579249-3f991428-4e2f-4a1c-997f-0505c4c8310c.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20261024%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20261024T113953Z&X-Amz-Expires=300&X-Amz-Signature=f9e93b7598419d133e2cb2efab9a5d589bcc1974540fba2b52a074f2fc818b84&X-Amz-SignedHeaders=host&response-content-type=video%2Fmp4)

---

## 💡 The Problem

Preliminary technical hiring is systematically broken:
* **For Candidates:** High anxiety, lack of actionable feedback (the #1 frustration for 52% of candidates), process fatigue, and disconnect from real-world workflows.
* **For Organizations:** High engineering costs spent on screening, inconsistent evaluations, bias, and costly bad hires (30–50% of 1st-year salary).
* **The Core Flaw:** Existing testing tools (e.g., HackerRank, Codility) test *what* the final answer is (binary pass/fail), completely missing *how* a candidate thinks, communicates, and approaches problems.

---

## ✨ Key Features & Solution

### 🧠 1. Context-Aware AI Interactivity
* **Personalized & Contextual:** Dynamically crafts interviews tailored to Job Descriptions (JDs), candidate resumes, and company background.
* **Human-like Conversational AI:** Creates a fair, low-stress environment where candidates can explain their thought processes and receive real-time guidance.

### 💻 2. Live Coding & Interactive-Canvas Rounds
* **Real-time Collaboration:** Evaluates candidate articulation, visual conceptualization, coachability, and reaction to hints/guidance.

### 📊 3. Human-Centric Evaluation & Proctoring
* **Intellectual Journey Scoring:** Scores communication, problem-solving methodology, and decision-making logic rather than binary outputs.
* **Proctoring Engine:** Enhanced video proctoring to accurately detect malpractice and ensure integrity at scale.

### 🎯 Dual-Use Ecosystem

* **For Candidates (Practice & Feedback Engine):**
  * Unlimited practice rounds to reduce anxiety.
  * Actionable, skill-by-skill feedback reports post-interview.
* **For Organizations & Institutions (Scalable Screening):**
  * Asynchronous screening for hundreds of candidates simultaneously.
  * Data-driven dashboard with candidate side-by-side comparison and export capabilities.
  * Ideal for universities and placement institutes for training at scale.

---

## 📊 Feature Comparison Matrix

| Feature | **Limeflow** | HireVue | ZappyVue | Incruiter | HackerEarth |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Context-Aware Personalization (JD / Resume)** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Behavioral & Technical Simulation** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Live Coding + Interactive Canvas** | ✅ | ❌ | ❌ | ❌ | ✅ |
| **Human-like Conversational AI** | ✅ | ❌ | ✅ | ❌ | ❌ |
| **Actionable Feedback per Skill** | ✅ | Limited | Limited | Limited | Limited |
| **Evaluates Decision-Making Process** | ✅ | Limited | ❌ | ❌ | ❌ |
| **Advanced Video Proctoring** | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Integrated Platform (Practice + Screen)**| ✅ | ❌ | ❌ | ❌ | ❌ |

---

## 💼 Business Model

1. **B2C (Individuals):** Tiered Subscription (`Free`, `Pro`, `Premium`).
2. **B2B (Organizations):** Hybrid Model (Annual Platform Fee per seat + Consumption-based Interview Credits).
3. **B2B2C (Institutions):** Flat-rate annual license based on student enrollment.

---

## 📌 Getting Started

### Prerequisites
* Node.js (>= 18.x) / Python (>= 3.10)
* API Key credentials for LLM services and audio streaming backends.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-org/limeflow.git
   cd limeflow
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory:
   ```env
   AGENT_API_KEY=your_agent_api_key
   PROCTORING_SERVICE_URL=your_proctoring_url
   DATABASE_URL=your_database_url
   ```

4. **Run the Application:**
   ```bash
   npm run dev
   ```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).