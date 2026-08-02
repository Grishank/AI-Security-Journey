# 🧪 Data Poisoning in RAG Systems — TryHackMe Room

**Platform:** TryHackMe  
**Path:** AI Security  
**Module:** Data Poisoning  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/datapoisoninginragsystems  
**Status:** ✔ Completed

---

# 🧠 Room Overview

This room explores how attackers poison the data sources used by Retrieval-Augmented Generation (RAG) systems. Instead of attacking the model directly, adversaries manipulate training datasets, embeddings, vector databases, or document ingestion pipelines to influence retrieval results and AI responses.

---

# 🎯 Learning Objectives

- Understand data poisoning attacks in AI systems
- Learn how poisoned training data affects model behavior
- Explore attacks against embeddings and vector databases
- Identify vulnerabilities in RAG ingestion pipelines
- Study detection and mitigation techniques

---

# 📌 Room Summary

### Task 1 — Introduction
Introduced the concept of data poisoning and how attackers manipulate AI knowledge sources instead of directly attacking the model.

### Task 2 — Training Data Poisoning
Learned how malicious or manipulated training data can alter model behavior, create hidden biases, or introduce backdoors.

### Task 3 — Embeddings and Vector Databases
Explored how poisoned embeddings and compromised vector databases can influence document retrieval in RAG systems.

### Task 4 — Ingestion Pipeline Attacks
Studied attacks targeting document ingestion pipelines where malicious content is inserted before indexing into the knowledge base.

### Task 5 — Impact on Model Behavior
Observed how poisoned data affects retrieval quality, AI reasoning, response accuracy, and trustworthiness.

### Task 6 — Detection & Mitigation Techniques
Reviewed defensive strategies including dataset validation, embedding verification, trusted data sources, anomaly detection, and continuous monitoring.

### Task 7 — Practical
Applied detection and analysis techniques to identify poisoned data within a simulated RAG environment.

### Task 8 — Conclusion
Summarized how protecting data integrity throughout the AI lifecycle is essential for maintaining secure and reliable RAG systems.

---

# 🔍 Key Concepts Learned

- Data Poisoning
- Training Dataset Poisoning
- RAG Security
- Embedding Poisoning
- Vector Database Security
- Ingestion Pipeline Attacks
- Retrieval Manipulation
- AI Backdoors
- Data Integrity
- Detection & Mitigation

---

# 🛡️ AI Security Relevance

RAG systems depend on trusted external knowledge. If attackers successfully poison datasets, embeddings, or indexed documents, the AI can generate misleading, biased, or malicious responses without modifying the underlying model. Protecting every stage of the data pipeline is therefore a critical component of AI security.

---

# 💬 Key Takeaway

> "In AI security, protecting the model is not enough—protecting the data that shapes its knowledge is equally important."

---

# 🚀 Next Steps

- Learn advanced AI data validation techniques
- Explore secure vector database management
- Practice defending RAG ingestion pipelines
- Study AI model backdoor attacks
- Continue with advanced AI security modules
