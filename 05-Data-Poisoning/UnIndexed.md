# 🗂️ UnIndexed — TryHackMe Room

**Platform:** TryHackMe  
**Path:** AI Security  
**Module:** Data Poisoning  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/unindexedchallenge  
**Status:** ✔ Completed

---

# 🧠 Room Overview

This challenge focuses on one of the most overlooked AI security risks—improperly indexed data. You audit an internal AI assistant to determine whether confidential documents have accidentally become searchable. The room demonstrates how weak retrieval boundaries and poor indexing practices can expose sensitive organizational data.

---

# 🎯 Learning Objectives

- Understand unintended data exposure in AI systems
- Identify improperly indexed sensitive documents
- Test retrieval boundaries in RAG applications
- Assess access control weaknesses
- Discover hidden information through normal AI queries
- Understand secure indexing strategies

---

# 📌 Room Summary

### Task 1 — Challenge

Acted as a security consultant auditing **Cloudwright Labs'** internal AI assistant, **Atlas**.

The challenge involved:

- Investigating whether confidential documents were unintentionally indexed
- Testing if normal employee queries could retrieve restricted information
- Exploring weaknesses in retrieval boundaries
- Identifying over-permissioned knowledge sources
- Demonstrating how indexing mistakes lead to information disclosure
- Successfully locating the hidden flag through authorized security testing

---

# 🔍 Key Concepts Learned

- Improper Data Indexing
- Sensitive Information Disclosure
- Retrieval Boundary Failures
- RAG Security
- Access Control
- AI Data Exposure
- Principle of Least Privilege
- Secure Document Indexing
- AI Security Auditing
- Information Leakage

---

# 🛡️ AI Security Relevance

One of the biggest risks in enterprise AI systems is **indexing everything instead of only what should be searchable**. If confidential documents, internal credentials, board reports, or private repositories are accidentally indexed, an attacker may retrieve them using completely normal prompts without exploiting the model itself.

Proper indexing, permission-aware retrieval, and document classification are critical to preventing AI-driven information disclosure.

---

# 💬 Key Takeaway

> "If sensitive documents are indexed, the AI doesn't need to be hacked—it only needs to be asked."

---

# 🚀 Next Steps

- Practice advanced RAG security assessments
- Learn secure document indexing techniques
- Study permission-aware retrieval systems
- Explore vector database security
- Continue building hands-on AI security skills
