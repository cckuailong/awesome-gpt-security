# Awesome GPT + Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome security tools, experimental case or other interesting things with LLM or GPT.

## Contents

- [Tools](#tools)
  - [Integrated](#integrated)
  - [Audit](#audit)
  - [Reconnaissance](#reconnaissance)
  - [Offensive](#offensive)
  - [Detecting](#detecting)
  - [Preventing](#preventing)
  - [Social Engineering](#social-engineering)
  - [Reverse Engineering](#reverse-engineering)
  - [Investigation](#investigation)
  - [Fix](#fix)
  - [Assessment](#assessment)
- [Cases](#cases)
  - [Experimental](#experimental)
  - [Academic](#academic)
  - [Blogs](#blogs)
  - [Fun](#fun)
- [GPT Security](#gpt-security)
  - [Standard](#standard)
  - [Bypass Security Policy](#bypass-security-policy)
  - [Bug Bounty](#bug-bounty)
  - [Crack](#crack)
  - [Plugin Security](#plugin-security)
- [Contributing](#contributing)

![](./media/aigc.png)

## Attention

Here is [A nice tool](https://github.com/cckuailong/SuperAdapters) to Finetune ALL LLMs with ALL Adapeters on ALL Platforms! 

## Tools

🧰 

### Integrated

* [SecGPT](https://github.com/ZacharyZcR/SecGPT) - SecGPT aims to make further contributions to network security by combining LLM, including penetration testing, red-blue confrontations, CTF competitions, and other aspects.
* [AutoAudit](https://github.com/ddzipp/AutoAudit) - An LLM for Cyber Security
* [secgpt](https://github.com/Clouditera/secgpt) - Cyber security LLM(Lora finetuned with baichuan-13B using some material of cyber security)
* [HackerGPT-2.0](https://github.com/Hacker-GPT/HackerGPT-2.0) - HackerGPT is your indispensable digital companion in the world of hacking. 

### Audit

* [SourceGPT](https://github.com/NightmareLab/SourceGPT) - prompt manager and source code analyzer built on top of ChatGPT as the oracle
* [vulnhuntr](https://github.com/protectai/vulnhuntr) - Zero shot vulnerability discovery using LLMs
* [ChatGPTScanner](https://github.com/YulinSec/ChatGPTScanner) - A white box code scan powered by ChatGPT
* [chatgpt-code-analyzer](https://github.com/MilindPurswani/chatgpt-code-analyzer) - ChatGPT Code Analyzer for Visual Studio Code
* [hacker-ai](https://hacker-ai.ai/#hacker-ai) - An online tool using AI to detect vulnerabilities in source code
* [audit_gpt](https://github.com/fuzzland/audit_gpt) - Fine-tuning GPT for Smart Contract Auditing
* [vulchatgpt](https://github.com/ke0z/vulchatgpt) - Use IDA PRO HexRays decompiler with OpenAI(ChatGPT) to find possible vulnerabilities in binaries
* [Ret2GPT](https://github.com/DDizzzy79/Ret2GPT) - Advanced AI-powered binary analysis tool leveraging OpenAI's LangChain technology, revolutionizing CTF Pwners' experience in binary file interpretation and vulnerability detection.
* [AuthzAI](https://github.com/ngalongc/AuthzAI) - An automated tool to test and analyze API endpoints for potential permission model violations using OpenAI structured outputs.
* [SinkFinder](https://github.com/Phelaine/SinkFinder) - Semi-automatic vulnerability mining tool for closed-source systems, static code analysis for jar/war/zip, adding LLM large model capability to verify path accessibility, LLM determines the trust score of the path based on the context code environment

### Reconnaissance

* [CensysGPT Beta](https://gpt.censys.io) - The tool enables users to quickly and easily gain insights into hosts on the internet, streamlining the process and allowing for more proactive threat hunting and exposure management
* [GPT_Vuln-analyzer](https://github.com/morpheuslord/GPT_Vuln-analyzer) - Uses ChatGPT API, Python-Nmap, DNS Recon modules and uses the GPT3 model to create vulnerability reports based on Nmap scan data, and DNS scan information. It can also perform subdomain enumeration to a great extent
* [SubGPT](https://github.com/s0md3v/SubGPT) - SubGPT looks at subdomains you have already discovered for a domain and uses BingGPT to find more.
* [Navi](https://github.com/SSGOrg/Navi) - A QA based Reconnaissance Tool with GPT
* [ChatCVE](https://github.com/jasona7/ChatCVE) - The ChatCVE Lang Chain App is an AI-powered devSecOps application 🔍, for oganizations triaging and aggregating CVE (Common Vulnerabilities and Exposures) information.
* [ZoomeyeGPT](https://github.com/knownsec/ZoomeyeGPT) - ZoomEyeGPT browser extension is a GPT-based Chrome browser extension designed to bring AI-assisted search experience to ZoomEye users.
* [uncover-turbo](https://github.com/zt2/uncover-turbo) - Realize a general-purpose natural language surveying and mapping engine, and open up the last mile from natural language to surveying and mapping grammar.
* [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) - AI-Driven Software Development Automation Solution

### Offensive

* [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A GPT-empowered penetration testing tool
* [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT): LLMs x PenTesting, focus on linux priv-esc adn web/web-api pentesting
* [burpgpt](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform an additional passive scan for discovering highly bespoke vulnerabilities, and enables running traffic-based analysis of any type.
* [ReconAIzer](https://github.com/hisxo/ReconAIzer) - A Burp Suite extension to add OpenAI (GPT) on Burp and help you with your Bug Bounty recon to discover endpoints, params, URLs, subdomains and more!
  * [Cochise](https://github.com/andreashappe/cochise/): LLM-agent performing autonomous penetration test against Microsoft Windows Active Directory (using [GOAD](https://github.com/Orange-Cyberdefense/GOAD) as testbed).
* [CodaMOSA](https://github.com/microsoft/codamosa) - CodaMOSA is the paper code of CodaMOSA: Escaping Coverage Plateaus in Test Generation with Pre-trained Large Language Models. It implements a fuzzer combined with OpenAI API, aiming to alleviate the problem of stagnant coverage in traditional fuzz.
* [PassGAN](https://github.com/brannondorsey/PassGAN) - A Deep Learning Approach for Password Guessing. [HomeSecurityHeroes land a Product](https://www.homesecurityheroes.com/ai-password-cracking/), and you can test how much time an AI would need to crack your password here.
* [nuclei-ai-extension](https://github.com/projectdiscovery/nuclei-ai-extension) - Official by Nuclei Team. Browser Extension for Rapid Nuclei Template Generation.
* [nuclei_gpt](https://github.com/sf197/nuclei_gpt) - Only need to submit the relevant Request and Response and the description of the vulnerability to generate a Nuclei PoC.
* [Nuclei Templates AI Generator](https://templates.nuclei.sh/) -- Create Nuclei templates by textual description (e.g., vulnerability scanners by PoC).
* [hackGPT](https://github.com/NoDataFound/hackGPT) - Leverage OpenAI and ChatGPT to do hackerish things
* [AutorizePro](https://github.com/sule01u/AutorizePro) - AutorizePro is a authorization enforcement detection extension for burp suite. By adding Ai-assisted analysis, it significantly reduces the false positive rate and improves the efficiency of vulnerability detection.

### Detecting

* [k8sgpt](https://github.com/k8sgpt-ai/k8sgpt/) - a tool for scanning your Kubernetes clusters, diagnosing, and triaging issues in simple English.
* [cloudgpt](https://github.com/ustayready/cloudgpt) - Vulnerability scanner for AWS customer managed policies using ChatGPT
* [IATelligence](https://github.com/fr0gger/IATelligence) - About
IATelligence is a Python script that will extract the IAT of a PE file and request GPT to get more information about the API and the ATT&CK matrix related
* [rebuff](https://github.com/protectai/rebuff) - Prompt Injection Detector.
* [Callisto](https://github.com/JetP1ane/Callisto) - An Intelligent Automated Binary Vulnerability Analysis Tool.
* [LLMFuzzer](https://github.com/mnns/LLMFuzzer) - LLMFuzzer is the first open-source fuzzing framework specifically designed for Large Language Models (LLMs), especially for their integrations in applications via LLM APIs.
* [Vigil](https://github.com/deadbits/vigil-llm) - Prompt injection detection and LLM prompt security scanner

### Preventing

### Social Engineering

* [ChatGPT-Web-Setting-Funny-Abuse](https://github.com/Esonhugh/ChatGPT-Web-Setting-Funny-Abuse) - Play with ChatGPT-Web and found the HTML rendering in description settings.

### Reverse Engineering

* [LLM4Decompile](https://github.com/albertan017/LLM4Decompile) - Reverse Engineering: Decompiling Binary Code with Large Language Models
* [Gepetto](https://github.com/JusticeRage/Gepetto) - About
IDA plugin which queries OpenAI's gpt-3.5-turbo language model to speed up reverse-engineering
* [gpt-wpre](https://github.com/moyix/gpt-wpre) - Whole-Program Reverse Engineering with GPT-3
* [G-3PO](https://github.com/tenable/ghidra_tools/tree/main/g3po) - A Script that Solicits GPT-3 for Comments on Decompiled Code

### Investigation

* [beelzebub](https://github.com/mariocandela/beelzebub) - Go-Based Low-Code Honeypot Framework with Enhanced Security, Leveraging GPT-3 for System Virtualization

### Fix

* [wolverine](https://github.com/biobootloader/wolverine) - Auto fix the bugs in your Python Script/Code

### Assessment

* [falco-gpt](https://github.com/Dentrax/falco-gpt) - AI-generated remediations for Falco audit events
* [selefra](https://github.com/selefra/selefra) - an open-source policy-as-code software that provides analytics for multi-cloud and SaaS.
* [openai-cti-summarizer](https://github.com/EC-DIGIT-CSIRC/openai-cti-summarizer) - openai-cti-summarizer is a tool for generating threat intelligence summary reports based on OpenAI's GPT-3.5 and GPT-4 API

---
## Cases

🌰 

### Experimental

* [Lost in ChatGPT's memories: escaping ChatGPT-3.5 memory issues to write CVE PoCs](https://tin-z.github.io/chatgpt/go/cve/2023/04/14/escaping_chatgpt_memory.html)
* [I built a Zero Day virus with undetectable exfiltration using only ChatGPT prompts](https://www.forcepoint.com/blog/x-labs/zero-day-exfiltration-using-chatgpt-prompts)
* [Experimenting with GPT-3 for Detecting Security Vulnerabilities in Code](https://github.com/chris-koch-penn/gpt3_security_vulnerability_scanner)
* [We put GPT-4 in Semgrep to point out false positives & fix code](https://semgrep.dev/blog/2023/gpt4-and-semgrep-detailed)
* [A Practical, AI-Generated Phishing PoC With ChatGPT](https://curtbraz.medium.com/a-practical-ai-generated-phishing-poc-f81d3c3da76b)
* [Capturing the Flag with GPT-4](https://micahflee.com/2023/04/capturing-the-flag-with-gpt-4/)
* [I Used GPT-3 to Find 213 Security Vulnerabilities in a Single Codebase](https://betterprogramming.pub/i-used-gpt-3-to-find-213-security-vulnerabilities-in-a-single-codebase-cc3870ba9411)
* [Using ChatGPT to generate encoder and supporting WebShell](https://mp.weixin.qq.com/s/I9IhkZZ3YrxblWIxWMXAWA)
* [Using OpenAI Chat to Generate Phishing Campaigns](https://www.richardosgood.com/posts/using-openai-chat-for-phishing/) -- Include Phishing Platform
* [Chat4GPT Experiments for Security](https://github.com/mesutgungor/ChatGPT4Security)
* [GPT-3 use cases for Cybersecurity](https://github.com/sophos/gpt3-and-cybersecurity)
* [AI-Powered Fuzzing: Breaking the Bug Hunting Barrier](https://security.googleblog.com/2023/08/ai-powered-fuzzing-breaking-bug-hunting.html)

### Academic

* [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) -- OpenAI's own security assessment and mitigation of the model
* [Ignore Previous Prompt: Attack Techniques For Language Models](https://arxiv.org/pdf/2211.09527.pdf) -- Pioneering work of Prompt Injection
* [More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models](https://arxiv.org/abs/2302.12173)
* [RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models](https://arxiv.org/pdf/2009.11462.pdf)
* [Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks](https://arxiv.org/pdf/2302.05733.pdf)
* [Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/pdf/2209.07858.pdf)
* [Can We Generate Shellcodes via Natural Language? An Empirical Study](https://link.springer.com/article/10.1007/s10515-022-00331-3)

### Blogs

* [Dissecting redis CVE-2023-28425 with chatGPT as assistant](https://tin-z.github.io/redis/cve/chatgpt/2023/04/02/redis-cve2023.html)
* [Security Code Review With ChatGPT](https://research.nccgroup.com/2023/02/09/security-code-review-with-chatgpt/)
* [ChatGPT happy to write ransomware, just really bad at it](https://www.malwarebytes.com/blog/news/2023/03/chatgpt-happy-to-write-ransomware-just-really-bad-at-it?utm_source=blueshift&utm_medium=email&utm_campaign=b2c_pro_oth_20230403_aprilweeklynewsletter_v1_168025968119&utm_content=chatgpt_ransomware)
* [Create ATT&CK Groups Knowledge Base](https://otrf.github.io/GPT-Security-Adventures/experiments/ATTCK-GPT/notebook.html)
* [Model Confusion - Weaponizing ML models for red teams and bounty hunters](https://5stars217.github.io/2023-08-08-red-teaming-with-ml-models/)
* [Using LLMs to reverse JavaScript variable name minification](https://thejunkland.com/blog/using-llms-to-reverse-javascript-minification)
* [CircleGuardBench - A full-fledged benchmark for evaluating protection capabilities of AI models](https://huggingface.co/blog/whitecircle-ai/circleguardbench)

### Fun

* [shortest prompt that will enable GPT to protect the secret key](https://gpd.43z.one/)
* [a CTF-like game that teaches how to bypass LLM using language hacks](https://doublespeak.chat/#/)
* [ai-goat](https://github.com/dhammon/ai-goat) - Learn AI security through a series of vulnerable LLM CTF challenges.

---
## GPT Security

🚨

### Standard

* [modelscan](https://github.com/protectai/modelscan) - Protection against Model Serialization Attacks
* [promptfoo](https://github.com/promptfoo/promptfoo) - LLM red teaming and evaluation framework. Includes modelaudit for scanning ML models for malicious code, backdoors, and serialization attacks. CI/CD integration
* [ATT&CK for LLM Apps](https://atlas.mitre.org/)
* [The OWASP Top 10 for Large Language Model Applications project](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [Google AI Red Team](https://services.google.com/fh/files/blogs/google_ai_red_team_digital_final.pdf)
* [PurpleLlama](https://github.com/facebookresearch/PurpleLlama) - Empowering developers, advancing safety, and building an open ecosystem
* [agentic_security](https://github.com/msoedov/agentic_security) - Agentic LLM Vulnerability Scanner
* [garak](https://github.com/NVIDIA/garak) - LLM vulnerability scanner
* [inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) - Inspect: A framework for large language model evaluations
* [TrustGate](https://github.com/NeuralTrust/TrustGate) - Generative Application Firewall (GAF). Detects and blocks attacks against GenAI Applications
* [TrustTest](https://docs.neuraltrust.ai/trusttest/getting-started/overview) - LLM and agent red teaming automation tool. Evaluation framework



### Bypass Security Policy

* [Chat GPT "DAN" (and other "Jailbreaks")](https://gist.github.com/coolaj86/6f4f7b30129b0251f61fa7baaa881516)
* [ChatGPT Prompts for Bug Bounty & Pentesting](https://github.com/TakSec/chatgpt-prompts-bug-bounty)
* [promptmap](https://github.com/utkusen/promptmap) - automatically tests prompt injection attacks on ChatGPT instances
* [Use "Typoglycemia" to Bypass the LLM's Security Policy](https://mp.weixin.qq.com/s?__biz=MzkwNDI1NDUwMQ==&mid=2247486630&idx=1&sn=814af2fb7a06e5283b026c6483c47b07)
* [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://llm-attacks.org/)
* [promptbench](https://github.com/microsoft/promptbench) - A robustness evaluation framework for large language models on adversarial prompts
* [jailbreak_llms](https://github.com/verazuo/jailbreak_llms) - A dataset consists of 15,140 ChatGPT prompts from Reddit, Discord, websites, and open-source datasets (including 1,405 jailbreak prompts).

### Bug Bounty

* [Building A Virtual Machine inside ChatGPT](https://www.engraved.blog/building-a-virtual-machine-inside/) - deprecated but interesting
* [LangChain vulnerable to code injection -- CVE-2023-29374](https://github.com/advisories/GHSA-fprp-p869-w6q2)
* [ai-exploits](https://github.com/protectai/ai-exploits) - A collection of real world AI/ML exploits for responsibly disclosed vulnerabilities

### Crack

* [gpt4free](https://github.com/xtekky/gpt4free) - Just API's from some language model sites.
* [EdgeGPT](https://github.com/acheong08/EdgeGPT) - Reverse engineered API of Microsoft's Bing Chat AI
* [GPTs](https://github.com/linexjlin/GPTs) - leaked prompts of GPTs

### Plugin Security

* [SecureGPT](https://escape.tech/securegpt) – Dynamically test the security of your ChatGPT Plugins APIs (Free DAST for ChatGPT Plugins).

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cckuailong/awesome-gpt-security/blob/master/CONTRIBUTING.md) first.

- - -

If you have any question about this opinionated list, do not hesitate to open an issue on GitHub.

<p align="center">
<a href="https://github.com/cckuailong/awesome-gpt-security/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cckuailong/awesome-gpt-security&max=100">
</a>
</p>


Thanks again for your contribution and keeping this community vibrant. :heart:
