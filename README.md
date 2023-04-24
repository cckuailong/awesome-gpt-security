# Awesome GPT + Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome security tools, experimental case or other interesting things with LLM or GPT.

## Contents

- [Tools](#tools)
    - [Audit](#audit)
    - [Reconnaissance](#reconnaissance)
    - [Offensive](#offensive)
    - [Detecting](#detecting)
    - [Preventing](#preventing)
    - [Social Engineering](#social-engineering)
    - [Reverse Engineering](#reverse-engineering)
    - [Fix](#fix)
    - [Report](#report)
- [Cases](#cases)
    - [Experimental](#experimental)
    - [Academic](#academic)
    - [Blogs](#blogs)
    - [Fun](#fun)
- [GPT Security](#gpt-security)
    - [Bypass Security Policy](#bypass-security-policy)
    - [Bug Bounty](#bug-bounty)
- [Contributing](#contributing)

---
## Tools

🧰 

### Audit

* [SourceGPT](https://github.com/NightmareLab/SourceGPT) - prompt manager and source code analyzer built on top of ChatGPT as the oracle
* [ChatGPTScanner](https://github.com/YulinSec/ChatGPTScanner) - A white box code scan powered by ChatGPT
* [chatgpt-code-analyzer](https://github.com/MilindPurswani/chatgpt-code-analyzer) - ChatGPT Code Analyzer for Visual Studio Code
* [hacker-ai](https://hacker-ai.ai/#hacker-ai) - An online tool using AI to detect vulnerabilities in source code

### Reconnaissance

* [GPT_Vuln-analyzer](https://github.com/morpheuslord/GPT_Vuln-analyzer) - Uses ChatGPT API, Python-Nmap, DNS Recon modules and uses the GPT3 model to create vulnerability reports based on Nmap scan data, and DNS scan information. It can also perform subdomain enumeration to a great extent
* [SubGPT](https://github.com/s0md3v/SubGPT) - SubGPT looks at subdomains you have already discovered for a domain and uses BingGPT to find more.
* [Navi](https://github.com/SSGOrg/Navi) - A QA based Reconnaissance Tool with GPT

### Offensive

* [burpgpt](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform an additional passive scan for discovering highly bespoke vulnerabilities, and enables running traffic-based analysis of any type.
* [ReconAIzer](https://github.com/hisxo/ReconAIzer) - A Burp Suite extension to add OpenAI (GPT) on Burp and help you with your Bug Bounty recon to discover endpoints, params, URLs, subdomains and more!
* [PassGAN](https://github.com/brannondorsey/PassGAN) - A Deep Learning Approach for Password Guessing. [HomeSecurityHeroes land a Product](https://www.homesecurityheroes.com/ai-password-cracking/), and you can test how much time an AI would need to crack your password here.

### Detecting

* [k8sgpt](https://github.com/k8sgpt-ai/k8sgpt/) - a tool for scanning your Kubernetes clusters, diagnosing, and triaging issues in simple English.
* [cloudgpt](https://github.com/ustayready/cloudgpt) - Vulnerability scanner for AWS customer managed policies using ChatGPT
* [IATelligence](https://github.com/fr0gger/IATelligence) - About
IATelligence is a Python script that will extract the IAT of a PE file and request GPT to get more information about the API and the ATT&CK matrix related

### Preventing

### Social Engineering

* [ChatGPT-Web-Setting-Funny-Abuse](https://github.com/Esonhugh/ChatGPT-Web-Setting-Funny-Abuse) - Play with ChatGPT-Web and found the HTML rendering in description settings.

### Reverse Engineering

* [gpt-wpre](https://github.com/moyix/gpt-wpre) - Whole-Program Reverse Engineering with GPT-3
* [G-3PO](https://github.com/tenable/ghidra_tools/tree/main/g3po) - A Script that Solicits GPT-3 for Comments on Decompiled Code

### Fix

* [wolverine](https://github.com/biobootloader/wolverine) - Auto fix the bugs in your Python Script/Code

### Report

* [falco-gpt](https://github.com/Dentrax/falco-gpt) - AI-generated remediations for Falco audit events

---
## Cases

🌰 

### Experimental

* [Lost in ChatGPT's memories: escaping ChatGPT-3.5 memory issues to write CVE PoCs](https://tin-z.github.io/chatgpt/go/cve/2023/04/14/escaping_chatgpt_memory.html)
* [I built a Zero Day virus with undetectable exfiltration using only ChatGPT prompts](https://www.forcepoint.com/blog/x-labs/zero-day-exfiltration-using-chatgpt-prompts)
* [Experimenting with GPT-3 for Detecting Security Vulnerabilities in Code](https://github.com/chris-koch-penn/gpt3_security_vulnerability_scanner)
* [We put GPT-4 in Semgrep to point out false positives & fix code](https://semgrep.dev/blog/2023/gpt4-and-semgrep-detailed)
* [A Practical, AI-Generated Phishing PoC With ChatGPT](https://curtbraz.medium.com/a-practical-ai-generated-phishing-poc-f81d3c3da76b)

### Academic

* [More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models](https://arxiv.org/abs/2302.12173)

### Blogs

* [Dissecting redis CVE-2023-28425 with chatGPT as assistant](https://tin-z.github.io/redis/cve/chatgpt/2023/04/02/redis-cve2023.html)
* [Security Code Review With ChatGPT](https://research.nccgroup.com/2023/02/09/security-code-review-with-chatgpt/)
* [ChatGPT happy to write ransomware, just really bad at it](https://www.malwarebytes.com/blog/news/2023/03/chatgpt-happy-to-write-ransomware-just-really-bad-at-it?utm_source=blueshift&utm_medium=email&utm_campaign=b2c_pro_oth_20230403_aprilweeklynewsletter_v1_168025968119&utm_content=chatgpt_ransomware)

### Fun

* [shortest prompt that will enable GPT to protect the secret key](https://gpd.43z.one/)
* [a CTF-like game that teaches how to bypass LLM using language hacks](https://doublespeak.chat/#/)

---
## GPT Security

🚨

### Bypass Security Policy

* [Chat GPT "DAN" (and other "Jailbreaks")](https://gist.github.com/coolaj86/6f4f7b30129b0251f61fa7baaa881516)
* [ChatGPT Prompts for Bug Bounty & Pentesting](https://github.com/TakSec/chatgpt-prompts-bug-bounty)

### Bug Bounty

* [LangChain vulnerable to code injection -- CVE-2023-29374](https://github.com/advisories/GHSA-fprp-p869-w6q2)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cckuailong/awesome-gpt-security/blob/master/CONTRIBUTING.md) first.

- - -

If you have any question about this opinionated list, do not hesitate to open an issue on GitHub.
