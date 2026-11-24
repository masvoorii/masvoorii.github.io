# Nathan Game Palembang — Interactive Digital Game Catalog 🎮

[![Live Demo](https://img.shields.io/badge/Live_Site-masvoorii.github.io-2563EB?style=flat-square&logo=githubpages&logoColor=white)](https://masvoorii.github.io)
![HTML5](https://img.shields.io/badge/HTML5-Single_File_App-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

A fast, zero-build, serverless **digital game catalog and storage estimator web application** built for **Nathan Game Palembang** (live at **[masvoorii.github.io](https://masvoorii.github.io)**). Powered by a **Google Apps Script** backend and enriched with live **Wikidata/Wikipedia** metadata, it lets users browse titles, calculate total drive capacity requirements, and send formatted game lists directly via WhatsApp.

---

### ✨ Key Features

- **🔍 Smart Alias Search Engine:** Supports common gaming abbreviations and acronyms (e.g., `gta sa`, `pes`, `re4`, `gow`, `rdr2`, `dmc 5`, `uns`) alongside standard title and genre matching.
- **🎛️ Multi-Criteria Filtering & Sorting:**
  - Dynamic platform tabs with live item counters.
  - Auto-populated genre dropdown filter.
  - Sort by **Newest**, **Oldest**, **Alphabetical (A–Z / Z–A)**, or **File Size (Smallest / Largest)**.
- **💾 Real-Time Storage Capacity Estimator:** Interactive selection cart that automatically parses `MB` and `GB` sizes to calculate total storage requirements on the fly.
- **📖 Automated Indonesian Game Synopsis Modal:** Fetches game descriptions dynamically via the **Wikidata** and **Wikipedia (ID/EN) APIs** upon clicking any game card, complete with automatic Indonesian translation fallback and in-memory caching.
- **📲 One-Click WhatsApp Order Formatting:** Generates a clean, itemized summary of selected titles, platforms, and total estimated storage ready to send to the admin via WhatsApp.
- **☁️ Serverless Headless Architecture:** Fetches live catalog updates from a Google Apps Script JSON endpoint without requiring a traditional backend server or build step.

---

### 🛠️ Tech Stack

- **Frontend:** Semantic HTML5, Vanilla JavaScript (ES6+), Tailwind CSS
- **Data & External APIs:** Google Apps Script (JSON REST Endpoint), Wikidata API, Wikipedia REST/Action API
- **Hosting:** GitHub Pages

---

### 🚀 Local Usage

Since this is a self-contained static web application with zero build dependencies:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/masvoorii/masvoorii.github.io.git](https://github.com/masvoorii/masvoorii.github.io.git)
   cd masvoorii.github.io
   ```

2. **Open in browser:**
   Simply open `index.html` directly in any modern web browser or serve it using a local static server (e.g., VS Code Live Server).
