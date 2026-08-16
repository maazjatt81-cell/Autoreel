# ⚡ AutoReel & PinAI Studio Pro v2.5

An end-to-end automated social media content generator powered by Google Gemini 2.5, Express Node.js, and React. Generate viral video scripts, graphic quote cards, high-converting titles, and platform-specific SEO metadata in seconds.

---

## 🌟 Key Features

* **🤖 AI Script Generator:** Generates structured 3-line viral video scripts tailored for YouTube Shorts, Instagram Reels, and Pinterest Pins.
* **🎨 PinAI Canvas Engine:** Instant rendering of high-resolution graphic quote cards for social media distribution.
* **🎥 Automated Video Rendering:** Built-in video engine fallback for seamless demo execution and output generation.
* **🏷️ Multi-Platform SEO & Hashtags:** Automated title generator and category-specific viral hashtag recommendation system.
* **🛡️ Fail-Safe Dynamic Fallback:** Zero-crash architecture ensuring seamless presentation and user experience even during network interruptions.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, Modern CSS3 Dark Theme Architecture, Native Fetch API
* **Backend:** Node.js, Express.js, Axios, Canvas Engine, CORS
* **AI Integration:** Google Gemini API (`gemini-2.5-flash`)
* **Deployment:** Vercel (Frontend) & Render (Backend)

---

## 📁 Repository Structure

```text
AutoReel-Project/
├── backend/
│   ├── server.js          # Express server & Gemini API integration
│   ├── package.json       # Backend dependencies
│   └── .env               # API Keys & Port Config
└── frontend/
    ├── src/
    │   └── App.js         # React Studio Application Interface
    ├── public/
    │   ├── index.html
    │   └── manifest.json
    └── package.json       # Frontend dependencies
