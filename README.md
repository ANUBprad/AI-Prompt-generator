🚀 AI Prompt Generator – n8n Workflow

Turn simple ideas into production-ready AI prompts through an interactive and conversational workflow built entirely using n8n + Gemini.

This automation asks targeted questions, understands context, constraints, tools, tone, and expected output — and automatically generates a structured, high-quality AI prompt that follows a professional prompt engineering framework.

✨ Features

🧠 AI-driven question refinement
📋 Multi-step form workflow with UX-optimized UI
🔁 Dynamic follow-up questions based on user intent
🤖 Google Gemini powered prompt generation
📦 Returns a final, clean, ready-to-use prompt
🎨 Custom UI styling for a premium form experience


🔍 How it Works (Workflow Logic)

1. User starts the form and enters the basic information:
    -What they want to build
    -Tools available
    -Expected input & output
2. AI analyzes the answers and generates relevant clarifying questions.
3. The user answers those extra dynamic questions.
4. All collected data is merged & processed.
5. Gemini creates the final structured prompt using:
    -Role
    -Inputs
    -Tools
    -Instructions
    -Constraints
    -Conclusions
6. The final output is shown to the user in a copy-ready message UI.

🛠 Requirements

-n8n (self-hosted or cloud)
-Google Gemini or PaLM API credentials configured in n8n
-Ability to import workflow JSON (n8n → import → workflow.json)

📦 Installation & Usage

1. Clone this repository
```
git clone https://github.com/yourname/ai-prompt-generator-n8n.git
```
2. Open n8n
3. Import the JSON workflow
4. Add Gemini credentials
5. Activate webhook
6. Open the public form URL to start generating prompts

🧩 Customization

You can modify:
-Form questions
-Styling (customCss)
-Prompting logic
-Models (Switch to OpenAI, Groq, Claude, or Ollama)
-Output formatting

📸 Screenshots (Optional)
Add screenshots here of:
1️⃣ Main form
2️⃣ Follow-up questions
3️⃣ Final output screen

🙌 Contribution

Feel free to open issues, suggest improvements, or submit PRs.

⭐ Support

If you found this helpful, please star the repo 🌟
and share it with other automation / AI builders!
