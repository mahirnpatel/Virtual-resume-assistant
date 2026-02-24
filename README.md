# Career Agent – Virtual Assistant for Resume & LinkedIn

A personal career agent that allows anyone to ask questions about my professional background — my resume and LinkedIn — and receive contextual, human-like responses.  

Instead of static resumes or profiles, this agent provides **interactive, conversational access** to my career information, making it feel like you are chatting with me directly.  

---

## Demo

You can try the live version deployed on Hugging Face:  
[Career Agent Demo](https://lnkd.in/g4JgmH-5)  

---

## Features

- **Conversational Career Agent:**  
  Ask questions about my resume and LinkedIn profile and get precise, contextual answers.  

- **Gradio Chat Interface:**  
  Minimalistic and clean UI focused on logic, flow, and user experience.  

- **Contact Capture Tool:**  
  Users can optionally share their contact info with the agent.  

- **Notification via Pushover API:**  
  I receive instant notifications on my phone when:
  - Someone voluntarily shares contact info  
  - The agent encounters unknown or interesting questions  

- **Unknown Question Logging:**  
  Unanswered or ambiguous questions are logged for continuous improvement of the agent.  

---

## How It Works

1. **User Interaction:**  
   The user asks questions about my background through the Gradio chat interface.  

2. **LLM + Tools:**  
   The agent leverages a language model to interpret questions and retrieve relevant information from my resume and LinkedIn.  

3. **Information Flow:**  
   - Known questions are answered contextually  
   - Unknown questions are logged for review  
   - Contact info submissions trigger Pushover notifications  

4. **Agent Behavior:**  
   - Acts as an assistant, not just a chatbot  
   - Maintains conversational context for a human-like experience  

---

## Tech Stack

- **Frontend / Chat Interface:** Gradio  
- **Backend / Agent Logic:** Python + LLM  
- **Notifications:** Pushover API  
- **Deployment:** Hugging Face Spaces  

---

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/yourusername/virtual-resume-assistant.git
cd virtual-resume-assistant
```

2.	Install dependencies:
```bash
pip install -r requirements.txt
```

3.	Create a .env file and add your API keys:
```bash
OPENAI_API_KEY=<your_openai_key>
PUSHOVER_API_TOKEN=<your_pushover_token>
```

4.	Run the agent:

---

## Future Improvements
- Add dynamic LinkedIn API integration for live profile updates
-	Improve handling of complex or multi-part questions
-	Expand notification options and logging analytics
-	Enhance UI for mobile-friendly experience

---

## What I Learned
- Designing agentic workflows: integrating tools, notifications, and conversational AI
- Thinking through information flow and handling unknown queries gracefully
- Combining AI + practical user tools to create a real-world assistant