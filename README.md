# **VELOS AI v1.3** - Next-Generation Intelligent Assistant  

[![Version](https://img.shields.io/badge/Version-1.3-green)](https://github.com/epfklipteam/VELOS-AI.git)  
🚀 **Upgraded from VELOS AI v0.5** | 🤖 **Markov-Based AI** | 🔥 **Dynamic Response Generation**  

---

## **📌 What is VELOS AI?**
VELOS AI is an **open-source intelligent assistant**, originally developed in **VELOS AI v0.5**, and now **enhanced in v1.3** with **better response prediction, improved accuracy, and faster execution**.

**🔄 Version Upgrade:**  
VELOS AI **v1.3** is a major update over **VELOS AI v0.5** [(GitHub Link)](https://github.com/epfklipteam/VELOS-AI.git), focusing on **more dynamic and intelligent responses**.

---

## **🚀 What's New in VELOS AI v1.3?**
### **Compared to VELOS AI v0.5**:
| Feature               | VELOS AI v0.5 | VELOS AI v1.3 (New) |
|----------------------|--------------|------------------|
| **Prediction Model** | Basic Markov Chain | **Enhanced Markov Chain + Dynamic Response** |
| **Handling Typos** | No support | ✅ **Levenshtein Distance (Fuzzy Matching)** |
| **Response Variation** | Repeats same response | ✅ **Generates unique responses dynamically** |
| **Dataset Used** | `qa.json` + `text.txt` | ✅ **Only `qa.json` for optimized learning** |
| **Speed & Performance** | Slower execution | ✅ **Optimized for Termux & mobile devices** |

---

## **🎯 Features of VELOS AI v1.3**
✅ **Smart Response Generation** – Uses **Markov chain prediction** to generate unique responses.  
✅ **Handles Typos & Variations** – **Fuzzy matching (Levenshtein Algorithm)** finds the best match.  
✅ **No More Repeating Answers** – Every response is **slightly different**, making it feel more **human-like**.  
✅ **Optimized for Termux & Low-resource Devices** – **Fast execution, minimal memory usage**.  
✅ **Lightweight & Easy to Modify** – Uses a simple **JSON-based Q&A dataset (`qa.json`)** for customization.  

---

## **📦 Installation**
### **1️⃣ Install Node.js (if not installed)**
For **Termux**:
```bash
pkg install nodejs
```
For **Linux/macOS**:
```bash
sudo apt install nodejs -y
```
For **Windows**:  
[Download Node.js](https://nodejs.org/)

---

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/VELOS-AI.git
cd VELOS-AI
```

---

### **3️⃣ Run VELOS AI**
```bash
node ai.js
```

---

## **📖 How VELOS AI v1.3 Works**
1. **Loads the Q&A dataset** from `qa.json` (no extra training files needed).  
2. **Uses Fuzzy Matching** to find the closest matching question (even with typos).  
3. **Applies a Markov Model** to **generate a unique response** instead of repeating fixed answers.  
4. **Outputs a natural-sounding AI-generated response**.

---

## **💻 Example Usage**
```plaintext
> What is AI?
VELOS: Artificial Intelligence (AI) is the field of computer science that enables learning, reasoning, and problem-solving.

> What is AI?
VELOS: Artificial Intelligence is designed to help systems learn, adapt, and process information efficiently.

> What is Alhorithms?
VELOS: Algorithms are structured steps that machines use to solve problems and process data.

> What is Advanced?
VELOS: Advanced concepts include high-level techniques that enhance knowledge and innovation.

> I don’t need your name
VELOS: I understand! Let me know how else I can assist you today.
```

---

## **⚙️ Customizing the Q&A Dataset**
To **add more questions and answers**, simply edit the `qa.json` file. Example:
```json
[
  {
    "question": "What is Machine Learning?",
    "answer": "Machine Learning is a subset of AI that enables systems to learn from data and improve over time."
  },
  {
    "question": "What is Python?",
    "answer": "Python is a high-level programming language widely used in AI and data science."
  }
]
```

---

## **🛠️ Contributing**
VELOS AI is **open-source**! Contributions are welcome. To contribute:
1. **Fork** the repository.
2. **Make your changes** (improve AI, add features, or expand `qa.json`).
3. **Submit a Pull Request**.

---

## **📄 License**
This project is licensed under the **MIT License**.  
**Feel free to modify, distribute, and use it for your projects!** 🎉

---

## **📩 Contact & Support**
**Original Creator:** [epfklipteam](https://github.com/epfklipteam)  
**Updated & Maintained by:** DOSaAI
**GitHub:** [https://github.com/epfklipteam]  
**Email:** dosaai356@gmail.com

---

🚀 **VELOS AI v1.3 is the future of lightweight AI assistants.**  
🔥 **Download, customize, and start using today!**  
