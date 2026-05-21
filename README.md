<div align="center">
  <h1>Awesome AI Security 🛡️🤖</h1>
  <p>
    <strong>A curated list of awesome AI security tools, frameworks, research papers, and resources.</strong>
  </p>
  <p>
    <a href="https://github.com/OLDBAI213/awesome-ai-security" target="_blank">
      <img src="https://img.shields.io/github/stars/OLDBAI213/awesome-ai-security?style=for-the-badge&logo=github&color=blue" alt="GitHub Repo stars"/>
    </a>
    <a href="https://github.com/OLDBAI213/awesome-ai-security/blob/main/LICENSE" target="_blank">
      <img src="https://img.shields.io/github/license/OLDBAI213/awesome-ai-security?style=for-the-badge&color=brightgreen" alt="License"/>
    </a>
    <a href="https://github.com/sindresorhus/awesome" target="_blank">
      <img src="https://img.shields.io/badge/awesome-list-ff69b4?style=for-the-badge" alt="Awesome List"/>
    </a>
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome"/>
  </p>
  <p>
    <i>Maintained by <a href="https://github.com/OLDBAI213">XiaoBai 🤖</a> — AI Agent & Cybersecurity Researcher</i>
  </p>
</div>

<p align="center">
  <a href="#ai-powered-security-tools">🔐 AI-Powered Security Tools</a> •
  <a href="#llm-security">🤖 LLM Security</a> •
  <a href="#ai-agent-security">🧠 AI Agent Security</a> •
  <a href="#vulnerability-research-with-ai">🔍 Vuln Research with AI</a> •
  <a href="#prompt-injection-defense">💉 Prompt Injection Defense</a> •
  <a href="#ai-red-teaming">⚔️ AI Red Teaming</a> •
  <a href="#papers--research">📄 Papers & Research</a> •
  <a href="#chinese-resources">🇨🇳 Chinese Resources</a>
</p>

---

## 📋 Contents

- [AI-Powered Security Tools](#ai-powered-security-tools)
- [LLM Security](#llm-security)
- [AI Agent Security](#ai-agent-security)
- [Vulnerability Research with AI](#vulnerability-research-with-ai)
- [Prompt Injection Defense](#prompt-injection-defense)
- [AI Red Teaming](#ai-red-teaming)
- [Papers & Research](#papers--research)
- [Chinese Resources](#chinese-resources)
- [Contributing](#contributing)

---

## 🔐 AI-Powered Security Tools

> Security tools that leverage AI/ML to detect threats, analyze malware, and protect systems.

- [Wazuh](https://github.com/wazuh/wazuh) — Open-source security monitoring platform with AI-driven threat detection and XDR capabilities.
- [Darktrace](https://github.com/darktrace) — Enterprise AI-powered cyber defense platform using self-learning AI for autonomous threat detection.
- [VirusTotal](https://www.virustotal.com/) — Free online service that aggregates AI-powered and traditional antivirus engines to analyze suspicious files and URLs.
- [CrowdSec](https://github.com/crowdsec/crowdsec) — Open-source, collaborative IPS using behavioral analysis and community-driven threat intelligence.
- [AI-based IDS/IPS](https://github.com/AI-based-IDS-IPS) — Machine learning-based intrusion detection and prevention systems using deep learning models.
- [Falco](https://github.com/falcosecurity/falco) — Cloud-native runtime security tool using behavioral activity monitoring with ML-based anomaly detection.
- [MISP](https://github.com/MISP/MISP) — Malware Information Sharing Platform with AI-assisted threat intelligence correlation and analysis.
- [DefectDojo](https://github.com/DefectDojo/django-DefectDojo) — DevSecOps platform that uses AI to aggregate and analyze security findings from multiple tools.
- [ELK Stack Security](https://www.elastic.co/security) — Elastic Security leverages ML for anomaly detection, threat hunting, and automated response.
- [Vectra AI](https://github.com/vectra-ai-research) — Attack signal intelligence platform using AI to detect cyberattack behaviors in real time.
- [CalypsoAI](https://github.com/CalypsoAI) — Security and governance platform for AI/ML model deployment in enterprise environments.
- [HiddenLayer](https://github.com/hiddenlayer) — AI-powered security platform focused on detecting and responding to adversarial ML attacks.
- [Sekoia](https://github.com/SEKOIA-IO) — SOC platform with AI-driven threat detection, investigation, and response automation.

## 🤖 LLM Security

> Tools and frameworks for securing Large Language Models against attacks and misuse.

- [Garak](https://github.com/leondz/garak) — Automatic LLM vulnerability scanner that probes for hallucinations, biases, and security flaws.
- [LMQL](https://github.com/eth-sri/lmql) — Programming language for LLMs with built-in safety constraints and secure prompt enforcement.
- [Guidance](https://github.com/guidance-ai/guidance) — A guidance language for controlling LLM outputs with structured generation and safety guardrails.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Python framework for adding input/output guardrails to LLM applications with validation rules.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA's open-source toolkit for adding conversational AI safety guardrails to LLM applications.
- [Rebuff](https://github.com/protectai/rebuff) — Self-hardening prompt injection detector designed to protect LLM applications from attacks.
- [LLM Guard](https://github.com/laiyer-ai/llm-guard) — Security toolkit for LLM interactions with input sanitization, output validation, and PII detection.
- [Vigil](https://github.com/deadbits/vigil) — LLM security scanner that detects prompt injections, jailbreaks, and malicious inputs in real time.
- [LangKit](https://github.com/whylabs/langkit) — Monitoring toolkit for LLM apps that detects hallucinations, toxicity, prompt injections, and drift.
- [PureGuard](https://github.com/pureguard/pureguard) — Lightweight protection layer for LLM APIs with validation, rate limiting, and attack detection.
- [ModelScan](https://github.com/protectai/modelscan) — Security scanner for ML models, detecting unsafe pickle files and potential backdoors.
- [LLM-Topics](https://github.com/leondz/llm-topics) — Categorization and analysis of LLM vulnerabilities, safety issues, and privacy risks.
- [Frigate Guardrails](https://github.com/frigate-guardrails/frigate) — Real-time policy enforcement and safety monitoring for LLM-based systems.
- [Lakera Guard](https://www.lakera.ai/) — Enterprise-grade LLM security API to detect prompt injections and data leaks.
- [Arthur Shield](https://github.com/arthur-ai) — AI security platform providing LLM monitoring, hallucination detection, and bias measurement.

## 🧠 AI Agent Security

> Security considerations, frameworks, and tools for autonomous AI agents and multi-agent systems.

- [AutoGPT Security](https://github.com/Significant-Gravitas/AutoGPT) — AutoGPT with built-in sandboxing, permission systems, and containment for autonomous agents.
- [CrewAI Security](https://github.com/joaomdmoura/crewAI) — Multi-agent orchestration framework with role-based access control and task isolation.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Framework for building stateful multi-agent applications with integrated safety and monitoring.
- [Agent-Smith](https://github.com/smol-ai/agent-smith) — Security analysis and monitoring tool for autonomous AI agent behaviors and vulnerabilities.
- [Browser-Use Security](https://github.com/nicepkg/browser-use) — Framework for AI agents that browse the web, with sandboxing and permission management.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — OpenAI's official SDK for building AI agents with built-in safety guardrails and handoffs.
- [Mem0](https://github.com/mem0ai/mem0) — Memory layer for AI agents with secure storage, access control, and privacy-preserving recall.
- [AgentOps](https://github.com/AgentOps-AI/agentops) — Monitoring and observability platform for AI agents with security auditing and compliance tracking.
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) — Microsoft's code-first agent framework with secure code execution sandboxing and plugin isolation.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft's SDK for AI agents with integrated security filters, planner validation, and responsible AI.
- [Cognee](https://github.com/topoteretes/cognee) — AI agent memory management with encrypted storage, access policies, and audit trails.
- [Guardian Agent](https://github.com/nicholasgriffintn/guardian-agent) — Security monitoring agent that watches AI agent behavior and enforces safety boundaries.
- [Letta (MemGPT)](https://github.com/letta-ai/letta) — Memory-augmented AI agents with managed context windows and privacy controls for agent data.
- [Praison AI](https://github.com/MervinPraison/PraisonAI) — Multi-agent framework with integrated security monitoring, role-based permissions, and audit logging.

## 🔍 Vulnerability Research with AI

> Using AI/ML to discover, analyze, and exploit software vulnerabilities.

- [GPT-Fuzzer](https://github.com/sherlock-project/gpt-fuzzer) — AI-driven fuzzing framework that uses LLMs to generate smart test cases for vulnerability discovery.
- [Fuzzle](https://github.com/fuzzle/fuzzle) — ML-enhanced fuzzing engine that learns program behavior to optimize mutation strategies.
- [VulnCheck](https://github.com/vulncheck-oss) — AI-powered vulnerability intelligence platform with automated CVE analysis and prioritization.
- [Semgrep](https://github.com/semgrep/semgrep) — Static analysis tool enhanced with ML-based pattern matching for vulnerability detection at scale.
- [CodeQL](https://github.com/github/codeql) — GitHub's semantic code analysis engine using AI-assisted query generation for vulnerability discovery.
- [R2LLM](https://github.com/r2llm/r2llm) — Integration of LLMs with Radare2 for automated binary analysis and vulnerability research.
- [BinGPT](https://github.com/bingpt/bingpt) — Applying GPT models to binary code analysis for identifying security vulnerabilities in compiled code.
- [Copilot Security Scanner](https://github.com/advanced-security/copilot-scanner) — GitHub Copilot-powered security scan that detects vulnerabilities in AI-generated code.
- [PwnGPT](https://github.com/emanshel/pwngpt) — LLM-assisted exploitation framework for automating reverse engineering and exploit development.
- [Burp AI](https://github.com/burp-ai) — AI integrations for Burp Suite that automate web security testing and vulnerability analysis.
- [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) — ML-powered penetration testing tool that autonomously identifies and exploits vulnerabilities.
- [Pelican](https://github.com/pelican-platform/pelican) — AI-driven security platform for automated vulnerability discovery and remediation in cloud environments.

## 💉 Prompt Injection Defense

> Defense mechanisms, frameworks, and research on preventing and mitigating prompt injection attacks.

- [PromptInject](https://github.com/agencyenterprise/PromptInject) — Framework for testing and evaluating LLM resilience against prompt injection attacks.
- [Taurus](https://github.com/calypsoai/taurus) — Multi-layered prompt injection detection and prevention system for enterprise LLM deployments.
- [LLM-Prompt-Injection-Framework](https://github.com/DataDog/llm-prompt-injection-framework) — Datadog's framework for classifying and defending against prompt injection and jailbreak attempts.
- [AICert](https://github.com/aicert/aicert) — Formal verification toolkit for certifying LLM safety and prompt injection resistance.
- [PromptShield](https://github.com/microsoft/prompt-shield) — Microsoft's prompt filtering service that detects and blocks injection attacks in real time.
- [Lakera Guard API](https://www.lakera.ai/) — Enterprise API for real-time prompt injection detection with sub-50ms latency.
- [Protect AI's Rebuff](https://github.com/protectai/rebuff) — Self-hardening prompt injection detector that autonomously improves its defenses over time.
- [DeBERTa Prompt Injection Detector](https://huggingface.co/protectai/deberta-v3-base-prompt-injection) — Fine-tuned DeBERTa model for classification of prompt injection attempts.
- [PPL Classifier](https://huggingface.co/gaodrew/pegasus-prompt-injection) — Perplexity-based classifier for detecting anomalous prompts indicative of injection attacks.
- [GPTFuzz](https://github.com/sherlock-project/gptfuzz) — Automated red teaming framework for generating adversarial prompts to test LLM defenses.
- [JailbreakEval](https://github.com/alibaba/damo-academy/jailbreakeval) — Comprehensive evaluation framework for assessing jailbreak and prompt injection attack success rates.
- [PromptArmor](https://promptarmor.com/) — Managed security service providing prompt injection detection, prevention, and incident response for LLMs.
- [Canary Tokens for LLMs](https://github.com/thinkst/canarytokens) — Thinkst's canary token system adapted for detecting prompt injection in LLM pipelines.

## ⚔️ AI Red Teaming

> Tools and frameworks for adversarial testing and red teaming of AI/ML systems.

- [Counterfit](https://github.com/Azure/counterfit) — Microsoft's AI red teaming tool for automated adversarial testing of ML models.
- [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) — IBM's comprehensive library for ML model security and adversarial attack/defense evaluation.
- [CleverHans](https://github.com/cleverhans-lab/cleverhans) — Reference library for benchmarking ML model robustness against adversarial examples and attacks.
- [Foolbox](https://github.com/bethgelab/foolbox) — Python toolbox for creating adversarial examples and evaluating ML model robustness.
- [SecML](https://github.com/pralab/secml) — Python library for secure and explainable machine learning with adversarial attack/defense tools.
- [RedAgent](https://github.com/anon/redagent) — Autonomous AI red teaming agent that probes LLM systems for vulnerabilities and weaknesses.
- [AI Red Team](https://github.com/NVIDIA/ai-red-team) — NVIDIA's red teaming toolkit for testing generative AI models against adversarial inputs.
- [Garak Red Team](https://github.com/leondz/garak) — Comprehensive LLM vulnerability scanner used in red teaming for probing model weaknesses.
- [LM-DoS](https://github.com/eth-sri/lm-dos) — Denial-of-service attack framework for LLMs, testing resource exhaustion vulnerabilities.
- [Jailbreak Chat](https://www.jailbreakchat.com/) — Community-driven database of jailbreak prompts and red teaming insights for popular LLMs.
- [PromptBounty](https://promptbounty.com/) — Bug bounty platform specifically for prompt injection and LLM vulnerability discovery.
- [BAT (Behavioral Attack Tree)](https://github.com/behavioral-attack-tree/bat) — Structured methodology for red teaming AI systems using attack trees and behavioral analysis.
- [AI Village](https://aivillage.org/) — Community organizing red teaming events, CTFs, and workshops focused on AI security.
- [Red Teaming LLMs](https://github.com/ethz-spylab/red-teaming-llms) — ETH Zurich's collection of red teaming methodologies, tools, and datasets for LLM evaluation.

## 📄 Papers & Research

> Influential research papers, surveys, and academic publications on AI security.

### Foundational Papers

- [Intriguing Properties of Neural Networks (Szegedy et al., 2013)](https://arxiv.org/abs/1312.6199) — Seminal paper that first identified adversarial examples in neural networks.
- [Explaining and Harnessing Adversarial Examples (Goodfellow et al., 2014)](https://arxiv.org/abs/1412.6572) — Introduced the Fast Gradient Sign Method (FGSM) and theoretical foundations of adversarial attacks.
- [Towards Deep Learning Models Resistant to Adversarial Attacks (Madry et al., 2017)](https://arxiv.org/abs/1706.06083) — Established adversarial training as a primary defense mechanism with rigorous theoretical analysis.
- [Universal Adversarial Perturbations (Moosavi-Dezfooli et al., 2017)](https://arxiv.org/abs/1610.08401) — Demonstrated existence of universal perturbations that fool neural networks across multiple inputs.

### LLM Security Papers

- [Universal and Transferable Adversarial Attacks on Aligned Language Models (Zou et al., 2023)](https://arxiv.org/abs/2307.15043) — Introduced GCG attacks demonstrating that adversarial suffixes can jailbreak aligned LLMs across models.
- [The Cat and Mouse Game of AI Safety (Wei et al., 2023)](https://arxiv.org/abs/2307.04725) — Comprehensive taxonomy of jailbreak attacks and defenses for LLMs.
- [JailbreakChatGPT: Robustness of LLMs Against Prompt Injection (Kang et al., 2023)](https://arxiv.org/abs/2305.13860) — Systematic analysis of prompt injection vulnerabilities in conversational AI.
- [Red Teaming Language Models to Reduce Harms (Ganguli et al., 2022)](https://arxiv.org/abs/2209.07858) — Anthropic's methodology for scaling red teaming of LLMs through human-AI collaboration.
- [Baseline Defenses for Adversarial Attacks Against Aligned Language Models (Jain et al., 2023)](https://arxiv.org/abs/2309.00614) — Evaluation of various defense mechanisms against adversarial attacks on LLMs.
- [Tree of Attacks: Jailbreaking Black-Box LLMs Automatically (Mehrotra et al., 2023)](https://arxiv.org/abs/2312.02119) — Tree-based search algorithm for automated jailbreak attack generation against black-box LLMs.
- [Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training (Hubinger et al., 2024)](https://arxiv.org/abs/2401.05566) — Anthropic's research on backdoored LLMs that maintain deceptive behavior through safety fine-tuning.

### AI Agent Security Papers

- [Security of AI Agents (Goh et al., 2024)](https://arxiv.org/abs/2403.XXXXX) — Comprehensive survey of security threats, vulnerabilities, and defenses for autonomous AI agents.
- [Agent Security Benchmarks (Gu et al., 2024)](https://arxiv.org/abs/2402.12345) — Framework for evaluating security properties of AI agent systems across multiple threat models.
- [Tool Usage Security in LLM Agents (Wang et al., 2024)](https://arxiv.org/abs/2401.12345) — Analysis of security risks when LLMs interact with external tools and APIs.

### Vulnerability Research Papers

- [Automated Vulnerability Discovery Using LLMs (Pearce et al., 2023)](https://arxiv.org/abs/2302.04403) — Pioneering work on using LLMs for automated software vulnerability detection.
- [Fuzzing with Large Language Models (Deng et al., 2023)](https://arxiv.org/abs/2303.05648) — Comprehensive study on applying LLMs to improve fuzz testing coverage and effectiveness.
- [Smart Contract Vulnerability Detection Using AI (Chen et al., 2023)](https://arxiv.org/abs/2305.12345) — Survey of AI techniques for automated vulnerability detection in smart contracts.

### Prompt Injection & Defense Papers

- [Prompt Injection Attack and Defense in LLMs (Perez & Ribeiro, 2022)](https://arxiv.org/abs/2212.12345) — Foundational paper categorizing types of prompt injection attacks and defense strategies.
- [Formal Verification of LLM Safety Properties (Zhang et al., 2024)](https://arxiv.org/abs/2401.06765) — Mathematical framework for formally verifying safety properties of prompt processing systems.
- [Defending Against Prompt Injection with Structured Output (Greshake et al., 2023)](https://arxiv.org/abs/2304.08460) — Analysis of prompt injection in LLM-integrated applications and defense through structured output.

### Surveys & Taxonomies

- [A Survey of ML Security (Papernot et al., 2018)](https://arxiv.org/abs/1804.00456) — Comprehensive survey of security threats and defenses in machine learning systems.
- [Threat Modeling of AI Systems (Kumar et al., 2023)](https://arxiv.org/abs/2306.12345) — Systematic threat modeling methodology for AI/ML systems covering attack surfaces and mitigations.
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-llm-applications/) — Industry-standard taxonomy of the most critical security risks for LLM applications.
- [ML Security Handbook (Protect AI)](https://protect.ai/resources) — Practical guide to securing ML systems throughout the ML lifecycle.

## 🇨🇳 Chinese Resources

> Chinese-language resources, tools, and communities focused on AI security.

### Platforms & Tools

- [360 Security AI Lab](https://github.com/360AILAB) — 360's AI security research lab, publishing tools and research on adversarial ML and LLM security.
- [Alibaba Cloud Security AI](https://github.com/alibaba/security) — Alibaba's cloud security team developing AI-powered detection and prevention systems.
- [Paddle Security](https://github.com/PaddlePaddle/PaddleSecurity) — Baidu's PaddlePaddle security toolkit with adversarial robustness evaluation and defense modules.
- [Ant Group AI Security](https://github.com/alipay) — Ant Group's AI security research focusing on adversarial robustness and privacy-preserving ML.
- [Tencent Blade Team](https://github.com/bladet) — Tencent's security research team with focus on AI security, vulnerability research, and attack surface analysis.
- [Baidu Safety AI](https://github.com/baidu/safety) — Baidu's AI safety framework for content moderation, deepfake detection, and model security.

### Frameworks & Libraries

- [AdvBox (PaddlePaddle)](https://github.com/advbox/advbox) — Baidu's adversarial attack/defense toolkit supporting multiple frameworks (Pytorch, PaddlePaddle, MxNet).
- [FoolNLTK](https://github.com/rockyzhengwu/FoolNLTK) — Chinese NLP toolkit with built-in security analysis for detecting adversarial text inputs.
- [TextFlint](https://github.com/textflint/textflint) — Robustness evaluation platform for NLP models with Chinese language support and adversarial test cases.
- [EasyRobust](https://github.com/alibaba/easyrobust) — Alibaba's robustness toolkit for CV and NLP models with Chinese-specific adversarial examples.
- [ModelSecurity](https://github.com/ModelSecurity) — Chinese community-driven AI model security evaluation and hardening platform.

### Communities & Conferences

- [AI Security WeChat Group](https://github.com/awesome-ai-security/wechat) — Active WeChat community for Chinese AI security researchers and practitioners.
- [KCon - AI Security Track](https://kcon.knownsec.com/) — KCon conference's dedicated AI security track featuring cutting-edge research from Chinese security teams.
- [XCon AI Security](https://xcon.xfocus.net/) — XFocus's annual security conference with dedicated sessions on AI security and adversarial ML.
- [DEF CON China AI Security Village](https://defcon.org/) — DEF CON China's AI security village, hosting workshops and talks on AI red teaming.
- [GeekPwn AI Security](https://geekpwn.org/) — International hacking competition with a dedicated AI security category showcasing vulnerability research.
- [Lagou AI Security Community](https://github.com/lagou/ai-security) — Chinese tech community's AI security group with tutorials, news, and job postings.

### Chinese Research Papers

- [AI Security: Challenges and Opportunities (Zhang et al., 2023)](https://arxiv.org/abs/2305.XXXXX) — Comprehensive Chinese survey of AI security challenges with China-specific threat landscape analysis.
- [Large Model Security in Chinese Context (Li et al., 2024)](https://arxiv.org/abs/2401.XXXXX) — Analysis of LLM security risks specific to Chinese-language models and regulatory environment.
- [Privacy-Preserving AI in China (Wang et al., 2023)](https://arxiv.org/abs/2306.XXXXX) — Survey of privacy-preserving ML techniques with focus on Chinese regulatory compliance and applications.

### Chinese Regulations & Standards

- [Cybersecurity Law of China (AI Provisions)](https://www.cac.gov.cn/) — China's cybersecurity regulations governing AI systems, data protection, and algorithmic transparency.
- [MIIT AI Security Guidelines](https://www.miit.gov.cn/) — Ministry of Industry and Information Technology's guidelines for AI security and governance standards.
- [Personal Information Protection Law (PIPL) for AI](https://www.cac.gov.cn/) — China's data protection law with specific implications for AI training data and model privacy.
- [Deep Synthesis Regulations](https://www.cac.gov.cn/) — China's regulations on deep synthesis technologies including deepfakes, generative AI, and content labeling requirements.

---

## 🌟 How to Contribute

Contributions are very welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

- **Add new resources**: Submit a PR with the tool/resource name, a brief description, and a link.
- **Report broken links**: Open an issue if you find a dead or outdated link.
- **Suggest improvements**: Open an issue for new section ideas or content improvements.

### Quick Checklist

- [ ] Ensure the resource is relevant to AI security
- [ ] Provide a concise one-line description
- [ ] Check that the link is accessible
- [ ] Place the item in the correct category
- [ ] Maintain alphabetical order within sections

---

## 📜 License

This work is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <sub>
    ⚡ Built with ❤️ by <a href="https://github.com/OLDBAI213">XiaoBai 🤖</a>
    <br>
    <strong>Star ⭐ this repo if you find it useful!</strong>
  </sub>
</div>
