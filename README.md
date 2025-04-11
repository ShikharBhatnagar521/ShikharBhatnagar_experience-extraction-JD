# 🧠 AI/ML Task – Experience Extraction from Job Descriptions

## 🔍 Objective
Extract the required **years of experience** from job descriptions using multiple NLP techniques and identify the best performing model.

---

## ✅ Techniques Used
1. **Keyword Heuristic** – Rule-based string match
2. **spaCy NER** – Named Entity Recognition with pattern filtering
3. **MiniLM QA** – Lightweight transformer-based QA model (`deepset/minilm-uncased-squad2`)
4. **T5-small QA** – Generative QA model
5. **Custom Rule-based Fallback** – Heuristic search around experience keywords

---

## 📝 Output
The results are stored in:  
📄 `experience_extraction_fast_5_miniLM.xlsx`  
Each row contains predictions from all 5 techniques.

---

## 💡 Best Model Recommendation
**MiniLM** provided the best balance of **accuracy and speed**, consistently extracting experience values more accurately than keyword-only or rule-based models, and faster than heavier transformer models.

---

## ⚙️ How to Run (Google Colab)
1. Upload `Job Descriptions.xlsx` to `/content/`
2. Run `main.ipynb` in Google Colab
3. Outputs will be generated and saved automatically

---

## 📎 Contact
Shikhar Bhatnagar  
[LinkedIn](https://www.linkedin.com/in/bhatnagarshikhar) | [GitHub](https://github.com/ShikharBhatnagar521)
