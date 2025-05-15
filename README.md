# LLM Instructions & Rules Archive

Thank you for your interest. This project collects high-quality, topic-specific custom **instructions** and/or **rules** to be used with LLMs or AI Apps' in their User and/or Projects sections.

Serves as a curated collection for a wide variety of technical domains, including but not limited to:

- 🐚 Script Development (sh, bash, zsh, PowerShell, cmd.exe)
- 💻 C/C++ Development
- 🧠 AI Prompt Engineering
- 🌐 Networking & Protocols
- 🔐 Cybersecurity & Pentesting
- 📊 Data Analysis & Visualization
- 🛠 DevOps & Automation
- 📦 Package Management & Dependency Handling
- 🧪 Testing & QA
- 📱 Mobile and Web Development

## 📖 Usage

Each file is intended to define clear, focused behavioral rules for the LLM in a specific context. Find the Instructions file of your preferred topic under [./topics](./topics/).

You can **Copy/Paste the plain text** into your user or project section of your AI App.

- ChatGPT > Project and add it under Instructions.
  - Check also [.chatgpt-instructions](./llms/chatgpt-instructions.md) for this new proposal from OpenAi
- Cursor > Cursor full settings > User or Project Rules
- :

---

## ✍️ Contribution Guidelines

To contribute a new instruction set:

1. **Create a folder** under `/topics/<your-topic-name>/`.
2. Add one or more files named `<your-name-here>.md` containing your custom instructions in plain text, shortly explain the purpose and usage.
3. Optionally add a general `README.md`
4. Keep instructions **precise**, **actionable**, and **relevant** to the topic. Ensure grammar, formatting, and markdown are clean and consistent.
5. Include a section with your example using the code ticks

---

## 📂 Folder Structure

```shell
/topics/
  ├── dev.scripting/
  │   ├── shell.scripts.md
  │   ├── powershell.md
  │   ├── :
  │   └── README.md
  ├── ai/
  ├── cpp-development/
  ├── prompt-engineering/
  ├── networking/
  └── ...
```

---

## 💬 Discussions & Requests

Want to request a topic? Have feedback on an existing instruction set?
Open a discussion or issue and let’s improve the archive together.

Happy prompting! 🚀
