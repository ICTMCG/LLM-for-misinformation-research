# LLM-for-misinformation-research
A curated paper list of misinformation research using (multi-modal) large language models, i.e., (M)LLMs.

## Methods for Detection and Verification

### As an Information/Feature Provider, Data Generator, and Analyzer

> An LLM can be seen as a (sometimes not reliable) knowledge provider, an experienced expert in specific areas, and a relatively cheap data generator (compared with collecting from the real world). For example, LLMs could be a good analyzer of social commonsense/conventions.

- **Cheap-fake Detection with LLM using Prompt Engineering**[[paper]](https://arxiv.org/abs/2306.02776) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2023.06-blue)
- **Bad Actor, Good Advisor: Exploring the Role of Large Language Models in Fake News Detection**[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30214) ![](https://img.shields.io/badge/AAAI%202024-orange) ![](https://img.shields.io/badge/2023.09-blue)
- **Detecting Misinformation with LLM-Predicted Credibility Signals and Weak Supervision**[[paper]](https://arxiv.org/abs/2309.07601) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2023.09-blue)
- **FakeGPT: Fake News Generation, Explanation and Detection of Large Language Model**[[paper]](https://arxiv.org/abs/2210.05046) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **Fighting Fire with Fire: The Dual Role of LLMs in Crafting and Detecting Elusive Disinformation**[[paper]](https://aclanthology.org/2023.emnlp-main.883/) ![](https://img.shields.io/badge/EMNLP%202023-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **Language Models Hallucinate, but May Excel at Fact Verification**[[paper]](https://arxiv.org/abs/2310.14564) ![](https://img.shields.io/badge/NAACL%202024-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **Clean-label Poisoning Attack against Fake News Detection Models**[[paper]](https://doi.org/10.1109/BigData59044.2023.10386777) ![](https://img.shields.io/badge/BigData%202023-orange)  ![](https://img.shields.io/badge/2023.12-blue)
- **Rumor Detection on Social Media with Crowd Intelligence and ChatGPT-Assisted Networks**[[paper]](https://doi.org/10.18653/v1/2023.emnlp-main.347) ![](https://img.shields.io/badge/EMNLP%202023-orange) ![](https://img.shields.io/badge/2023.12-blue)
- **LLMs are Superior Feedback Providers: Bootstrapping Reasoning for Lie Detection with Self-Generated Feedback**[[paper]](https://tanushreebanerjee.github.io/pdfs/diplomacy_main.pdf) ![](https://img.shields.io/badge/2024.01-blue)
- **FACT-GPT: Fact-Checking Augmentation via Claim Matching with LLMs**[[paper]](https://arxiv.org/abs/2402.05904) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **Can Large Language Models Detect Rumors on Social Media?**[[paper]](https://arxiv.org/abs/2402.03916) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **TELLER: A Trustworthy Framework for Explainable, Generalizable and Controllable Fake News Detection**[[paper]](https://arxiv.org/abs/2402.07776) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **DELL: Generating Reactions and Explanations for LLM-Based Misinformation Detection**[[paper]](https://arxiv.org/abs/2402.10426) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **Enhancing large language model capabilities for rumor detection with Knowledge-Powered Prompting**[[paper]](https://doi.org/10.1016/j.engappai.2024.108259) ![](https://img.shields.io/badge/EAAI-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **RumorLLM: A Rumor Large Language Model-Based Fake-News-Detection Data-Augmentation Approach**[[paper]](https://doi.org/10.3390/app14083532) ![](https://img.shields.io/badge/Applied%20Science-orange) ![](https://img.shields.io/badge/2024.04-blue)
- **Explainable Fake News Detection With Large Language Model via Defense Among Competing Wisdom**[[paper]](https://doi.org/10.1145/3589334.3645471) ![](https://img.shields.io/badge/WWW%202024-orange) ![](https://img.shields.io/badge/2024.05-blue)

### As a Tool User

> Let an LLM be an agent that has access to external tools like search engines, deepfake detectors, etc.

- **Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models**[[paper]](https://arxiv.org/abs/2305.14623) ![](https://img.shields.io/badge/NAACL%202024%20Findings-orange) ![](https://img.shields.io/badge/2023.05-blue)
- **FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios**[[paper]](https://arxiv.org/abs/2307.13528) ![](https://img.shields.io/badge/NAACL%202024%20Findings-orange) ![](https://img.shields.io/badge/2023.07-blue)
- **FactLLaMA: Optimizing Instruction-Following Language Models with External Knowledge for Automated Fact-Checking**[[paper]](https://arxiv.org/abs/2309.00240) ![](https://img.shields.io/badge/APSIPA%20ASC%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)
- **Explainable Claim Verification via Knowledge-Grounded Reasoning withLarge Language Models**[[paper]](https://aclanthology.org/2023.findings-emnlp.416) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)
- **Language Models Hallucinate, but May Excel at Fact Verification**[[paper]](https://arxiv.org/abs/2310.14564) ![](https://img.shields.io/badge/NAACL%202024-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method**[[paper]](https://aclanthology.org/2023.ijcnlp-main.64) ![](https://img.shields.io/badge/AACL%202023-orange) ![](https://img.shields.io/badge/2023.11-blue)
- **Evidence-based Interpretable Open-domain Fact-checking with Large Language Models**[[paper]](https://arxiv.org/abs/2312.05834) ![](https://img.shields.io/badge/NAACL%202024%20Findings-orange) ![](https://img.shields.io/badge/2023.12-blue)
- **TELLER: A Trustworthy Framework for Explainable, Generalizable and Controllable Fake News Detection**[[paper]](https://arxiv.org/abs/2402.07776) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **LEMMA: Towards LVLM-Enhanced Multimodal Misinformation Detection with External Knowledge Augmentation**[[paper]](https://arxiv.org/abs/2402.11943) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **Can Large Language Models Detect Misinformation in Scientific News Reporting?**[[paper]](https://arxiv.org/abs/2402.14268) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **The Perils and Promises of Fact-Checking with Large Language Models**[[paper]](https://doi.org/10.3389%2Ffrai.2024.1341697) ![](https://img.shields.io/badge/Frontiers%20in%20AI-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **SNIFFER: Multimodal Large Language Model for Explainable Out-of-Context Misinformation Detection**[[paper]](https://arxiv.org/abs/2403.03170) ![](https://img.shields.io/badge/CVPR%202024-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **Re-Search for The Truth: Multi-round Retrieval-augmented Large Language Models are Strong Fake News Detectors**[[paper]](https://arxiv.org/abs/2403.09747) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **MMIDR: Teaching Large Language Model to Interpret Multimodal Misinformation via Knowledge Distillation**[[paper]](https://arxiv.org/abs/2403.14171) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **Reinforcement Retrieval Leveraging Fine-grained Feedback for Fact Checking News Claims with Black-Box LLM**[[paper]](https://arxiv.org/abs/2404.17283) ![](https://img.shields.io/badge/COLING%202024-orange) ![](https://img.shields.io/badge/2024.04-blue)
- **TrumorGPT: Query Optimization and Semantic Reasoning over Networks for Automated Fact-Checking**[[paper]](https://doi.org/10.1109/CISS59072.2024.10480162) ![](https://img.shields.io/badge/CISS%202024-orange) ![](https://img.shields.io/badge/2024.04-blue)
- **Large Language Model Agent for Fake News Detection**[[paper]](https://arxiv.org/abs/2405.01593) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.05-blue)
- **Argumentative Large Language Models for Explainable and Contestable Decision-Making**[[paper]](https://arxiv.org/abs/2405.02079) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.05-blue)

### As a Decision Maker/Explainer

> An LLM can directly output the final prediction and (optional) explanations.

- **Large Language Models Can Rate News Outlet Credibility**[[paper]](https://arxiv.org/abs/2304.00228) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.04-blue)
- **Towards Reliable Misinformation Mitigation: Generalization, Uncertainty, and GPT-4**[[paper]](https://arxiv.org/abs/2305.14928) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.05-blue)
- **Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models**[[paper]](https://arxiv.org/abs/2305.14623) ![](https://img.shields.io/badge/NAACL%202024%20Findings-orange) ![](https://img.shields.io/badge/2023.05-blue)
- **News Verifiers Showdown: A Comparative Performance Evaluation of ChatGPT 3.5, ChatGPT 4.0, Bing AI, and Bard in News Fact-Checking**[[paper]](https://arxiv.org/abs/2306.17176) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.06-blue)
- **Explainable Claim Verification via Knowledge-Grounded Reasoning withLarge Language Models**[[paper]](https://aclanthology.org/2023.findings-emnlp.416) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)
- **Language Models Hallucinate, but May Excel at Fact Verification**[[paper]](https://arxiv.org/abs/2310.14564) ![](https://img.shields.io/badge/NAACL%202024-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **FakeGPT: Fake News Generation, Explanation and Detection of Large Language Model**[[paper]](https://arxiv.org/abs/2310.05046) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.10-blue)
- **DELL: Generating Reactions and Explanations for LLM-Based Misinformation Detection**[[paper]](https://arxiv.org/abs/2402.10426) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **A Revisit of Fake News Dataset with Augmented Fact-checking by ChatGPT**[[paper]](https://arxiv.org/abs/2312.11870) ![](https://img.shields.io/badge/arXiv-orange)  ![](https://img.shields.io/badge/2023.11-blue)
- **Are Large Language Models Good Fact Checkers: A Preliminary Study**[[paper]](https://arxiv.org/abs/2311.17355) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2023.11-blue)
- **Can Large Language Models Detect Rumors on Social Media?**[[paper]](https://arxiv.org/abs/2402.03916) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **FACT-GPT: Fact-Checking Augmentation via Claim Matching with LLMs**[[paper]](https://arxiv.org/abs/2402.05904) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **Assessing the Reasoning Abilities of ChatGPT in the Context of Claim Verification**[[paper]](https://arxiv.org/abs/2402.10735) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **LEMMA: Towards LVLM-Enhanced Multimodal Misinformation Detection with External Knowledge Augmentation**[[paper]](https://arxiv.org/abs/2402.11943) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **Can Large Language Models Detect Misinformation in Scientific News Reporting?**[[paper]](https://arxiv.org/abs/2402.14268) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **The Perils and Promises of Fact-Checking with Large Language Models**[[paper]](https://doi.org/10.3389%2Ffrai.2024.1341697) ![](https://img.shields.io/badge/Frontiers%20in%20AI-orange) ![](https://img.shields.io/badge/2024.02-blue)
- **FakeNewsGPT4: Advancing Multimodal Fake News Detection through Knowledge-Augmented LVLMs**[[paper]](https://arxiv.org/abs/2403.01988) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **SNIFFER: Multimodal Large Language Model for Explainable Out-of-Context Misinformation Detection**[[paper]](https://arxiv.org/abs/2403.03170) ![](https://img.shields.io/badge/CVPR%202024-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **Multimodal Large Language Models to Support Real-World Fact-Checking**[[paper]](https://arxiv.org/abs/2403.03627) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **MMIDR: Teaching Large Language Model to Interpret Multimodal Misinformation via Knowledge Distillation**[[paper]](https://arxiv.org/abs/2403.14171) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)
- **Argumentative Large Language Models for Explainable and Contestable Decision-Making**[[paper]](https://arxiv.org/abs/2405.02079) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.05-blue)
- **Exploring the Potential of the Large Language Models (LLMs) in Identifying Misleading News Headlines**[[paper]](https://arxiv.org/abs/2405.03153) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.05-blue)

## Check-worthy Claim Detection
- **Are Large Language Models Good Fact Checkers: A Preliminary Study**[[paper]](https://arxiv.org/abs/2311.17355) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2023.11-blue)
- **Claim Check-Worthiness Detection: How Well do LLMs Grasp Annotation Guidelines?**[[paper]](https://arxiv.org/abs/2404.12174) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.04-blue)

## Post-hoc Explanation Generation
- **Are Large Language Models Good Fact Checkers: A Preliminary Study**[[paper]](https://arxiv.org/abs/2311.17355) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2023.11-blue)
- **JustiLM: Few-shot Justification Generation for Explainable Fact-Checking of Real-world Claims**[[paper]](https://arxiv.org/abs/2401.08026) ![](https://img.shields.io/badge/TACL-orange) ![](https://img.shields.io/badge/2024.01-blue)
- **Can LLMs Produce Faithful Explanations For Fact-checking? Towards Faithful Explainable Fact-Checking via Multi-Agent Debate**[[paper]](https://arxiv.org/abs/2402.07401) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.02-blue)

## Other Tasks
- **[Fake News Propagation Simulation] From Skepticism to Acceptance: Simulating the Attitude Dynamics Toward Fake News**[[paper]](https://arxiv.org/abs/2403.09498) ![](https://img.shields.io/badge/arXiv-orange) ![](https://img.shields.io/badge/2024.03-blue)

## Resources
- [**Combating Misinformation in the Age of LLMs: Opportunities and Challenges**](llm-misinformation.github.io): A survey of the opportunities (can we utilize LLMs to combat misinformation) and challenges (how to combat LLM-generated misinformation) of combating misinformation in the age of LLMs.
- [**ARG**](https://github.com/ICTMCG/ARG): A Chinese & English fake news detection dataset with adding rationales generated by GPT-3.5-Turbo.
- [**MM-Soc**](https://arxiv.org/abs/2402.14154): A benchmark for multimodal language models in social media platforms, containing a misinformation detection task.
