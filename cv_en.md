
# KuoChing Chang

## **Profile**

Research-oriented candidate focusing on **long-context LLMs, trustworthy medical AI, multi-agent reinforcement learning, and large-scale decision-making systems**. Strong engineering foundation (distributed training, model deployment, hospital systems integration) with cross-domain collaboration experience. Aiming to build scalable, robust, and interpretable intelligence for real-world environments.

---

## **Education**

**Kyoto University, Graduate School of Informatics**
Ph.D. in Informatics (2025– )
Advisor: Prof. Takayuki Ito
Research: Multi-Agent RL, Mechanism Design, Safe Decision Systems, LLM Agents

**Kyoto University**
M.Sc. in Informatics (2023–2025)
Research: Clinical NLP, Long-Context Modeling, LLM Summarization

---

## **Research Experience**

### **1. Long-Context Clinical Summarization with NBCE (First Author)**

* Developed *Neighbor-Based Context Expansion (NBCE)* to enable 7B LLMs to process >40k-token clinical records without scaling up model size.
* Designed a TF-IDF + semantic alignment mechanism, improving decoding efficiency by **1.8×** and summary consistency by **+14.2 ROUGE-L**.
* Implemented a multi-GPU inference pipeline using PyTorch DDP to serve 30+ departments in a university hospital.
* Applied to daily progress notes and discharge summary generation.

---

### **2. Multi-Agent RL for Nurse Scheduling (Real Hospital Deployment)**

* Built a MARL system for **200+ nurses across 12 wards**, optimizing workload balance and continuity constraints.
* Trained PPO/Actor-Critic agents on **30k+** real scheduling records.
* Achieved **80 ms** decision latency (CPU-only) and **37%** reduction in scheduling conflicts.
* Integrated with the hospital HIS through REST APIs.

---

### **3. Semantic-Constrained RL for Safe LLM Agents (Ongoing Project)**

* Proposed “Holy Code,” a semantic constraint framework using an LLM-Critic to enforce symbolic ethical rules over agent actions.
* Created a benchmark with 20+ ethical conflict scenarios for medical triage and staffing tasks.
* Preliminary results show **>70%** reduction in severe violations with minimal performance loss.

---

### **4. Multi-Modal Medical AI (Imaging + EHR)**

* Built BERT/ClinicalBERT + ResNet/ViT fusion models for patient outcome prediction.
* Trained on 120k+ multimodal samples, achieving **+6% AUC** over baselines.

---

## **Work Experience**

### **MsunHealth｜AI R&D Intern**

* Built EMR data pipelines and deployed summarization models into hospital systems.
* Reduced inference latency by **63%** through model optimization and serving improvements.
* Collaborated with HIS engineers to deliver production-ready APIs.

### **Whale Cloud｜Technical Operations Intern**

* Supported China Mobile cloud storage infrastructure; responsible for service stability tests and issue diagnosis.
* Automated scripts improved operational efficiency by **30%+** across a 100+ server fleet.

---

## **Technical Skills**

**Languages:** Python, C++, Java
**Frameworks:** PyTorch, TensorFlow, HuggingFace, DeepSpeed, Ray
**Systems:** Linux, Docker, CUDA, Git, PostgreSQL
**Expertise:** RL / MARL, Transformers, LLM Fine-tuning, Long-context modeling, Retrieval-based methods
**Other:** Distributed training, large-scale data processing, model serving

---

## **Highlights**

* Strong ability to convert **ideas → algorithms → systems → real-world deployment**.
* Unique cross-domain strength: medical AI × LLMs × RL × multi-agent systems.
* Emphasis on safety, interpretability, and robustness in high-stakes environments.

---
