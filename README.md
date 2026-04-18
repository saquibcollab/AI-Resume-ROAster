# 🔥 AI Resume Roaster

> Paste or upload your resume. Get roasted, scored, and ranked. 💀

![Demo](public/demo.gif)

---

## 🚀 What is this?

**AI Resume Roaster** is an AI-powered tool that:

* 📄 Analyzes your resume (paste or PDF upload)
* 🎯 Gives you a **score out of 100**
* 💀 Roasts you (or gives professional feedback)
* 🏆 Ranks you on a **public leaderboard**

No fluff. Just honest, useful feedback.

---

## ⚡ Try it in 10 seconds

1. Paste your resume *or upload a PDF*
2. Click **Analyze Resume**
3. See your score + feedback
4. Check if you made it to the **Most Roasted leaderboard**

---

## 🎯 Features

* 🔥 **Roast Mode** (brutal + funny)
* 💼 **Professional Mode** (clean + constructive)
* 📄 **PDF Upload Support**
* 🎯 **Resume Score (0–100)**
* 📊 **Detailed Breakdown**

  * Content
  * Clarity
  * Impact
  * Formatting
* 🏆 **Leaderboard (Most Roasted Resumes)**
* ⚡ Instant AI feedback

---

## 🧠 Example Output

```json id="k8z1qw"
{
  "score": 42,
  "sections": {
    "content": 45,
    "clarity": 40,
    "impact": 38,
    "formatting": 50
  },
  "feedback": "This resume reads like it was written at 2AM..."
}
```

---

## 🏆 Leaderboard

See how you compare with others:

* 💀 Lowest scores rank highest
* 📉 Real anonymous resume data
* 🔥 Perfect for sharing with friends

> “I ranked #2 on the AI Resume Roaster 💀”

---

## 🛠️ Tech Stack

* **Next.js (App Router)**
* **OpenAI API**
* **Prisma + SQLite**
* **pdf-parse**

---

## 📦 Run Locally

```bash id="t3v9kl"
git clone https://github.com/your-username/ai-resume-roaster.git
cd ai-resume-roaster
npm install
```

Create `.env.local`:

```env id="p4x7mz"
OPENAI_API_KEY=your_api_key_here
```

Run:

```bash id="s2n8wd"
npx prisma migrate dev
npm run dev
```

---

## 🌍 Live Demo

👉 *Add your deployed link (Vercel recommended)*

---

## 📸 Screenshots

![Screenshot](assets/screenshots/chatgpt.png)

---

## 🧨 Why people share this

* It’s brutally honest
* It gives a real score
* It’s fun + slightly painful
* The **leaderboard makes it competitive**
* Perfect for: “look what AI said about me 💀”

---

## 🗺️ Roadmap

* [ ] PDF → improved resume download
* [ ] Shareable result pages
* [ ] Weekly leaderboard reset
* [ ] AI resume rewrite
* [ ] Public profiles (optional)

---

## 🤝 Contributing

PRs welcome.
Ideas to make it more useful (or more savage) are encouraged.

---

## ⭐ Support

If this roasted you (or helped you), give it a ⭐
It helps others discover it.

---

## ⚠️ Disclaimer

* Resumes are processed for analysis and leaderboard ranking
* Avoid uploading sensitive personal data
* Roasts may hurt your feelings (temporarily)

---

## 📄 License

MIT License

---

> Built to make resumes better — one roast at a time.
