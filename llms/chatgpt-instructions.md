# 📘 What is a `.chatgpt-instructions` file

In some of the files you might find reference to such a file, notice it's only for ChatGPT.

## ❓ What is it?

The `.chatgpt-instructions` file is **not yet a native config file** recognized by the ChatGPT desktop or web client.

It is a **convention** introduced to define **custom behavior guidelines** for ChatGPT in a specific project context — similar in spirit to `.editorconfig` or `.vscode/settings.json`, but currently **manual** in usage.

So, it's totally optional as of today.

---

## ✅ Purpose

- Acts as a **human-readable guide** for how ChatGPT should behave in this project.
- Can be **shared with teammates** to ensure consistent prompt behavior.
- Ideal for **documenting AI-specific preferences**, such as language style, coding practices, or platform-specific considerations.
- It can be created in json or txt format.

---

## ⚙️ How to Use It Today

Since the `.chatgpt-instructions` file is not auto-loaded, follow one of these workflows:

### Option 1: Manual Copy

1. Open the `.chatgpt-instructions` file in your project.
2. Copy its contents.
3. Paste it into the **"Custom Instructions"** section in ChatGPT OR send it in a new conversation with the assistant.

### Option 2: Prompt Reference

Start a session with:

> “Use the instructions defined in `.chatgpt-instructions` from this project.”

Then paste the contents or summarize them briefly.

---

## 🔮 Future Possibilities

OpenAI may integrate this convention into:

- ChatGPT’s **Projects** feature (experimental/preview).
- Native IDE workflows or plugins.
- Automatic project-scoped assistant behavior.

---

## 🧪 Bonus: Advanced Workflows

You can also create a local helper script or alias that copies the contents into your clipboard:

```bash
alias loadgpt='cat .chatgpt-instructions | pbcopy && echo "Instructions copied to clipboard!"'
```

> On macOS: `pbcopy`
> On Linux: Use `xclip -sel clip`
> On Windows (PowerShell): `Get-Content .chatgpt-instructions | Set-Clipboard`

---

## 📂 Recommended Usage

Always store `.chatgpt-instructions` in the **root** of your project repository. That way, contributors or future sessions with ChatGPT can stay consistent.

## sample

```text
You're helping someone who builds AI automation agencies using ChatGPT and other tools.

Follow these principles when responding:

GENERAL:
- Assume the user is building or operating a productized service agency using AI and automation.
:
```
