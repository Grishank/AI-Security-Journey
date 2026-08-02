# 🔒 Sensitive Information Disclosure — TryHackMe Room

**Platform:** TryHackMe  
**Path:** AI Security  
**Module:** Data Poisoning  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/sensitiveinformationdisclosure  
**Status:** ✔ Completed

---

# 🧠 Room Overview

This room explores how AI systems—particularly Retrieval-Augmented Generation (RAG) applications—can unintentionally expose sensitive information through insecure retrieval mechanisms, weak access controls, and improperly protected vector databases. It also introduces OWASP LLM02 and practical methods to reduce information disclosure risks.

---

# 🎯 Learning Objectives

- Understand AI sensitive information disclosure risks
- Learn the OWASP LLM02 vulnerability
- Explore common disclosure scenarios
- Identify attacks targeting vector databases
- Understand RAG retrieval failures
- Implement secure access controls and safeguards

---

# 📌 Room Summary

### Task 1 — Introduction
Introduced how AI systems can unintentionally reveal confidential information through insecure retrieval pipelines and weak security controls.

### Task 2 — OWASP LLM02
Learned about **OWASP LLM02: Sensitive Information Disclosure**, covering the risks of exposing secrets, credentials, internal documents, and private user data through AI applications.

### Task 3 — Common Disclosure Scenarios
Explored real-world examples where AI systems leaked confidential information due to improper prompt handling, indexing mistakes, or excessive permissions.

### Task 4 — Attacks on Vector Databases
Studied how attackers abuse vector databases to retrieve confidential documents or manipulate semantic search results.

### Task 5 — RAG Retrieval Failures
Examined retrieval failures where AI models returned sensitive information because of poor document filtering, retrieval ranking, or trust boundary violations.

### Task 6 — Access Control & Data Segmentation
Learned how role-based access control (RBAC), document segmentation, and permission-aware retrieval reduce exposure risks.

### Task 7 — Best Practices & Safeguards
Reviewed defensive measures including least privilege, secure indexing, retrieval filtering, encryption, monitoring, and continuous auditing.

### Task 8 — Practical
Applied techniques to identify sensitive information disclosure issues and practiced securing AI retrieval workflows.

### Task 9 — Conclusion
Summarized the importance of protecting confidential data throughout the AI retrieval pipeline using layered security controls.

---

# 🔍 Key Concepts Learned

- OWASP LLM02
- Sensitive Information Disclosure
- RAG Security
- Vector Database Security
- Semantic Search Risks
- Retrieval Failures
- Access Control
- Data Segmentation
- Least Privilege
- Secure AI Retrieval

---

# 🛡️ AI Security Relevance

Modern AI systems frequently access external knowledge sources. Without proper access controls, retrieval filtering, and secure vector databases, they may unintentionally expose confidential business information, credentials, customer data, or internal documentation. Protecting sensitive information requires enforcing least privilege, validating retrieval results, and continuously monitoring AI knowledge sources.

---

# 💬 Key Takeaway

> "An AI system should retrieve only what a user is authorized to see—security begins with controlling access to knowledge."

---

# 🚀 Next Steps

- Study advanced RAG security architectures
- Learn secure vector database management
- Explore AI authorization and identity controls
- Practice securing enterprise AI retrieval systems
- Continue with advanced AI security modules
