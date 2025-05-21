# 🚀 Revisly – Code Reviewsreinvented by AI

_Revisly_ is your **AI-powered code review buddy**. It reads your code, detects bad practices, suggests cleaner alternatives, and drops insightful comments — just like a senior dev on a good day (but faster and less sarcastic).

Built with 💡 in LATAM, and designed for dev teams everywhere who want **automated, context-aware pull request feedback** directly inside their IDE.

> “Less yak-shaving, more code shipping.”

---

## ✨ What is Revisly?

Revisly is a **VSCode extension** (JetBrains coming soon) that integrates with the **Anthropic Claude API** to perform real-time, AI-powered code reviews.

Whether you're pushing to main or mentoring juniors, Revisly makes sure your codebase stays **clean, sharp, and production-ready** — without slowing you down.

---

## 🔍 Features

- 🧠 **Smart Code Reviews** – Identifies anti-patterns, logic bugs, and design flaws.
- 📐 **Refactor Suggestions** – Cleaner code proposals with explanations.
- 🗣️ **Adaptive Tone** – Choose between _junior-friendly_ guidance or _senior-level_ feedback.
- 📘 **Style Guide Awareness** – Custom guidelines? Revisly adjusts.
- ⚡ **Inline or Sidebar Feedback** – See suggestions where they matter.
- 🧪 **MVP Status** – We’re just getting started. Expect fast iterations and spicy features.

---

## 🧑‍💻 How It Works

1. Highlight some code or open a file in VSCode.
2. Run the command: `Revisly: Run Code Review`.
3. Revisly sends your code (securely) to Claude.
4. Claude returns comments, refactors, and insights like a thoughtful PR reviewer.
5. You review, accept, edit, or ignore — you're still the boss. 🫡

---

## 📦 Installation

_(Coming soon to the VSCode Marketplace)_

In the meantime:

```bash
git clone https://github.com/holasoymalva/revisly.git
cd revisly
npm install
code .
# Press F5 to run the extension in VSCode Extension Dev Host
````

---

## 🧠 Prompt Example (What we send to Claude)

```text
You are a senior software engineer and code reviewer.

Review the following code and:
- Identify bugs, code smells, or bad practices.
- Suggest improvements and explain why.
- Be concise and clear.
- Adapt tone for a {seniority_level} developer.
- Follow these team guidelines: {team_guidelines} (if any).

Code:
{code_snippet}
```

---

## 🌎 Made in LATAM

We’re a devtools startup proudly built from LATAM for the world.
Why? Because smart code doesn’t care about borders.
And neither should productivity.

---

## 🛣️ Roadmap

* [x] MVP: VSCode plugin + Claude API
* [ ] JetBrains plugin support
* [ ] Multi-file review
* [ ] Review history + diff suggestions
* [ ] Claude 3 integration
* [ ] Org/team collaboration features

---

## 🤝 Contribute / Collaborate / Invest

> We’re not (yet) open source, but we are open to ideas, feedback, and pilot users.

💌 Reach out: `founders@revisly.dev`
🐦 Twitter: [@revisly\_ai](https://twitter.com/revisly_ai)
📬 Join the waitlist: [revisly.dev](https://revisly.dev) (soon)

---

## 🪪 License

Not open source (yet). Reach out for partnership, early access or enterprise trials.

---

## ⚠️ Disclaimer

Revisly is an MVP and still learning. Don’t deploy to prod without reviewing the reviewer. 😄
