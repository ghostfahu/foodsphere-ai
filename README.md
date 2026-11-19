# 🛒 FoodSphere AI · Bazar Budget

**Nutrition intelligence for Bangladesh's everyday bazar.**
Plan healthy, affordable meals using real market prices from official government sources.

🔗 **Live demo:** https://bazarbudgetbd.netlify.app/
🏆 Built for the **CloudCamp International AI Builders Congress**

---

## 🌾 The Problem

Food prices in Bangladesh change constantly, and for students, low-income families and young professionals, the hardest question is simple: *"What can I eat today that is nutritious and fits my budget?"*

Price data is scattered across government portals, and nutrition data lives in long technical tables. Almost nobody has time to combine the two.

## 💡 The Solution

**Bazar Budget** brings prices and nutrition together in one simple, bilingual (বাংলা / English) tool. It helps people:

- Find the **cheapest sources of protein** for their money
- Build a **daily food plan** that fits a budget
- Compare foods side by side by **cost vs. nutrition**
- Stay up to date with **latest official market prices**

## ✨ Features

| Feature | What it does |
|---|---|
| 🎓 **Student mode** | Budget-friendly meal planning for students |
| 💪 **Protein finder** | Shows low-cost protein options |
| 📋 **Daily plan** | Builds a food plan based on budget |
| ⚖️ **Compare foods** | Side-by-side comparison of foods |
| 💰 **Live price refresh** | Fetches the latest prices from the official source |
| 🌐 **Bilingual** | Bangla and English interface |
| 🤖 **AI assistance** | Powered by Google Gemini through secure serverless functions |

## 📊 Data Sources

- **Department of Agricultural Marketing (DAM)**: https://market.dam.gov.bd/ (market prices)
- **Trading Corporation of Bangladesh (TCB)**: https://tcb.gov.bd (reference prices)
- **FAO / INFS Food Composition Table for Bangladesh**: https://www.fao.org/fileadmin/templates/food_composition/documents/FCT_10_2_14_final_version.pdf (nutrition values)

## 🧱 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (single-page app)
- **Hosting:** Netlify
- **Backend:** Netlify Functions (serverless)
- **AI:** Google Gemini API
- **Security:** API keys are stored as Netlify environment variables and are never exposed in the frontend code

## 🚀 Run Locally

```bash
git clone https://github.com/ghostfahu/foodsphere-ai.git
cd foodsphere-ai
```

Open `index.html` in your browser to view the interface.
AI features need a Gemini API key set as the `GEMINI_API_KEY` environment variable and the Netlify Functions running (e.g. with `netlify dev`).

## 🧪 For Judges

No login or account is needed. Just open the live demo link above and start using it.

## 👥 Team

**Team name:** _Code Hunter_
**Members:** _Fahim,parvez,Nibir_

## 📄 License

MIT License. Free to use and learn from.

