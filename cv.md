
# KuoChing Chang

## **个人简介**

专注于 **大模型长文本理解、可信医疗 AI、多智能体强化学习与决策系统** 的研究型候选人。具备系统级工程能力（分布式训练、模型部署、医院信息系统对接）与跨学科协作经验。目标是在真实场景中构建可扩展、鲁棒且具解释性的智能系统。

---

## **教育背景**

**京都大学（Kyoto University）｜信息学研究科**
博士（在读）｜2025–
导师：Prof. Takayuki Ito（群体智能、多智能体机制设计）
研究方向：Multi-Agent RL、可信决策系统、大语言模型协作机制
DoGS SPRING Program Fellow

**京都大学｜信息学硕士**
2023–2025
研究方向：医疗 NLP、长文本建模、LLM-Summarization

---

## **研究项目与成果（按 Top Seed 偏好方式改写）**

### **1. Long-Context Clinical Summarization with NBCE Mechanism（第一作者）**

* 构建基于 *Neighbor-Based Context Expansion (NBCE)* 的长上下文摘要框架，使 7B 级模型在无需扩模的情况下处理 >40k tokens 医疗记录。
* 基于 TF-IDF + semantic alignment 的 “片段—摘要” 动态匹配方法，使解码效率提升 **1.8×**，摘要一致性提升 **+14.2 ROUGE-L**（内部数据）。
* 设计可扩展的多 GPU 推理 pipeline（PyTorch DDP），支持院内 30+ 科室的结构化 EMR 输入。
* 应用场景：临床病程总结、出院小结自动生成。

---

### **2. Multi-Agent Reinforcement Learning for Nursing Scheduling（医院真实数据）**

* 针对 **真实医院 200+ 护士、12 个病区**的排班需求，构建基于 MARL 的多智能体调度系统，实现工作负荷平衡与连续性约束。
* 采用自定义环境 + PPO/Actor-Critic，在 30,000+ 真实班次数据上训练。
* 决策延迟低于 **80ms**（CPU 环境），在离线评估中减少排班冲突 **37%**。
* 完成 HIS 对接与 API 部署，形成实际落地的原型系统。

---

### **3. Semantic-Constrained RL for Safe LLM Agents（在研）**

* 提出 “Holy Code” 语义约束框架：使用 LLM-Critic 对 agent 生成的行动进行符号化风险检查与语义约束校正。
* 针对医疗 triage 与护理调度任务，构建一个包含 20+ 伦理冲突场景的安全测试集。
* 初步结果表明：在不牺牲性能前提下，严重伦理违规率降低 **>70%**。

---

### **4. Multi-Modal Medical AI (Imaging + EHR)**

* 使用 BERT/ClinicalBERT + ResNet/ViT 构建病理与结构化 EHR 融合模型，用于疾病预测。
* 对 120k+ 多模态样本进行训练，AUC 提升 **+6%** 相较 baseline。

---

## **工作与实习经历**

### **MsunHealth｜医疗 AI 研发实习生**

* 负责构建院内 EMR 数据处理 pipeline、模型部署及优化。
* 设计临床摘要生成系统，部署后单文档推理延迟减少 **63%**。
* 与医院信息科合作完成 API 对接与测试。

### **Whale Cloud（杭州）｜技术运营实习生**

* 支撑中国移动云存储项目，负责 Web 服务端稳定性测试与问题定位。
* 维护近百台服务器的运行状态并编写自动化脚本，提高运维效率 **30%+**。

---

## **技能**

**语言**：Python、C++、Java
**框架**：PyTorch、TensorFlow、HuggingFace、DeepSpeed、Ray
**系统**：Linux、Docker、CUDA、Git、PostgreSQL
**方法**：RL / MARL、Transformer、LLM Finetuning、Retrieval-Augmented Methods
**其他**：大规模数据处理、分布式训练、模型部署
