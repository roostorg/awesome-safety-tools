# awesome-safety-tools

A collection of open source tools for online safety

Inspired by prior work like [Awesome Redteaming](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming/) and [Awesome Phishing](https://github.com/PhishyAlice/awesome-phishing). This list is not an endorsement, but rather an attempt to organize and map the available technology. ❤️

Help contribute by opening a pull request to add more resources and tools!


## Hash Matching

* [Altitude by Jigsaw](https://github.com/jigsaw-code/altitude)
  * web UI and hash matching for violent extremism and terrorism content
* [Hasher Matcher Action (HMA) by Meta](https://github.com/facebook/ThreatExchange/tree/main/hasher-matcher-actioner)
  * hashing algorithm, matching function, and ability to hook into actions
* [Hasher-Matcher-Actioner (CLIP demo)](https://github.com/juanmrad/HMA-CLIP-demo)
  * HMA extension for CLIP as reference for adding other format extensions
* [hma-matrix by the Matrix.org Foundation](https://github.com/matrix-org/hma-matrix)
  * Matrix-specific extensions to HMA for (primarily) the Matrix ecosystem
* [Lattice Extract by Adobe](https://github.com/adobe/lattice_extract)
  * grid and lattice detection to guard against FP in hash matching
* [MediaModeration (Wiki Extension)](https://github.com/wikimedia/mediawiki-extensions-MediaModeration?tab=readme-ov-file)
  * CSAM hash matching for Wikimedia
* [PDQ by Meta](https://github.com/facebook/ThreatExchange/tree/main/pdq)
  * perceptual hash algorithm for images
* [Perception by Thorn](https://github.com/thorn-oss/perception)
  * provides a common wrapper around existing, popular perceptual hashes (such as those implemented by ImageHash)
* [RocketChat CSAM](https://github.com/prostasia/rocketchatcsam)
  * CSAM hash matching for RocketChat
* [TMK by Meta](https://github.com/facebook/ThreatExchange/tree/main/tmk)
  * visual similarity match for videos
* [VPDQ by Meta](https://github.com/facebook/ThreatExchange/tree/main/vpdq)
  * visual similarity match for videos using PDQ algorithm


## Classification

* [CoPE by Zentropi](https://huggingface.co/zentropi-ai/cope-a-9b)
  * small language model trained for accurate, fast, steerable content classification based on developer-defined content policies
* [Detoxify by Unitary AI](https://github.com/unitaryai/detoxify)
  * detects and mitigates generalized toxic language (including hate speech, harassment, bullying) in text
* [gpt-oss-safeguard by OpenAI](https://github.com/openai/gpt-oss-safeguard)
  * open-weight reasoning model to classify text content based on provided safety policies
* [NSFW Keras Model](https://github.com/GantMan/nsfw_model)
  * convoluted neural network (CNN) based explicit image ML model
* [NSFW Filtering](https://github.com/nsfw-filter/nsfw-filter)
  * browser extension to block explicit images from online platforms; user facing
* [OSmod by Jigsaw](https://github.com/conversationai/conversationai-moderator)
  * toolkit of machine learning (ML) tools, models, and APIs that platforms can use to moderate content
* [Perspective API by Jigsaw](https://github.com/conversationai/perspectiveapi)
  * machine learning-powered tool that helps platforms detect and assess the toxicity of online conversations
* [Private Detector by Bumble](https://github.com/bumble-tech/private-detector)
  * pretrained model for detecting lewd images
* [Roblox Voice Safety Classifier](https://github.com/Roblox/voice-safety-classifier)
  * machine learning model that detects and moderates harmful content in real-time voice chat on Roblox; focuses on spoken language detection
* [Sentinel by Roblox](https://github.com/Roblox/Sentinel/tree/main)
  * Python library designed specifically for realtime detection of extremely rare classes of text by using contrastive learning principles
* [Toxic Prompt RoBERTa by Intel](https://huggingface.co/Intel/toxic-prompt-roberta)
  * BERT-based model for detecting toxic content in prompts to language models


## AI-powered Guardrails

* [Guardrails AI](https://github.com/guardrails-ai/guardrails)
  * Python framework that helps build safe AI applications checking input/output for predefined risks
* [Kanana Safeguard By Kakao](https://huggingface.co/kakaocorp/kanana-safeguard-8b)
  * harmful content detection model based on Kanana 8B
* [Llama Guard by Meta](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard3)
  * AI-powered content moderation model to detect harm in text-based interactions
* [Llama Prompt Guard 2 by Meta](https://github.com/meta-llama/PurpleLlama/blob/main/Llama-Prompt-Guard-2/86M/MODEL_CARD.md)
  * Detects prompt injection and jailbreaking attacks in LLM inputs
* [OpenGuardrails](https://github.com/openguardrails/openguardrails)
  * Security Gateway providing a transparent reverse proxy for OpenAI apis with integrated safety protection
* [Purple Llama by Meta](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard3)
  * set of tools to assess and improve LLM security. Includes Llama Guard, CyberSec Eval, and Code Shield
* [RoGuard](https://github.com/Roblox/RoGuard-1.0)
  * LLM that helps safeguard unlimited text generation on Roblox
* [ShieldGemma by Google DeepMind](https://www.kaggle.com/code/fernandosr85/shieldgemma-web-content-safety-analyzer?scriptVersionId=198456916)
  * AI safety toolkit by Google DeepMind designed to help detect and mitigate harmful or unsafe outputs in LLM applications


## Privacy Protection

* [Fawkes Facial De-Recognition Cloaking](https://github.com/Shawn-Shan/fawkes)
  * Code and binaries to confuse AIs when trying to match identity to photos, such as [Clearview](https://www.theverge.com/23919134/kashmir-hill-your-face-belongs-to-us-clearview-ai-facial-recognition-privacy-decoder)
  * Many other great tools at github.com/Shawn-Shan, MIT researcher
* [Presidio by Microsoft](https://github.com/microsoft/presidio)
  * toolset for detecting Personal Identifiable Information (PII) and other sensitive data in images and text


## Core Infrastructure

* [AbuseIO](https://github.com/AbuseIO/AbuseIO)
  * abuse management platform designed to help organizations handle and track abuse complaints related to online content, infrastructure, or services
* [Access by Discord](https://github.com/discord/access)
  * centralized portal for managing access to internal systems within any organization
* [Mjolnir by Matrix](https://github.com/matrix-org/mjolnir)
  * moderation bot for the Matrix protocol that automatically enforces content policies
* [Open Truss by GitHub](https://github.com/open-truss/open-truss)
  * framework designed to help users create internal tools without needing to write code
 

## Redteaming Tools

* [Aymara](https://github.com/aymara-ai/aymara-sdk-python)
  * Automated eval tools for AI safety, accuracy, and jailbreak vulnerability
* [Counterfit by Microsoft](https://github.com/Azure/counterfit/)  
  * Automation tool for assessing AI model security and robustness
* [Garak by NVIDIA](https://github.com/NVIDIA/garak)  
  * Framework for adversarial testing and model evaluation
* [LLM Canary](https://github.com/LLM-Canary/LLM-Canary)  
  * AI benchmarking tool that evaluates models for security vulnerabilities and adversarial robustness
* [Prompt Fuzzer](https://github.com/prompt-security/ps-fuzz)  
  * Tool for testing prompt injection vulnerabilities in AI systems
* [Promptfoo](https://github.com/promptfoo/promptfoo)
  * Automated LLM evaluations, report generations, several ready-to-use attack strategies
* [PyRIT](https://github.com/Azure/PyRIT)  
  * Microsoft’s Python-based tool for AI red teaming and security testing
* [Socketteer](https://github.com/socketteer?tab=repositories)
  * Allows AI models to interact, helping test conversational weaknesses


## Clustering

* [bogofilter](https://bogofilter.sourceforge.io/)
  * spam filter that classifies text using Bayesian statistical analysis; able to learn from classifications and corrections
* [scikit-learn](https://github.com/scikit-learn/scikit-learn)
  * python library including clustering through various algorithms, such as K-Means, DBSCAN, and hierarchical clustering
* [SpamAssassin by Apache](https://spamassassin.apache.org)
  * anti-spam platform that uses a variety of techniques, including text analysis, Bayesian filtering, and DNS blocklists, to classify and block unsolicited email


## Rules Engines

* [Druid by Apache](https://github.com/apache/druid)
  * high performance real-time analytics database
* [Marble](https://github.com/checkmarble/marble)
  * real-time fraud detection and compliance engine tailored for fintech companies and financial institutions
* [Osprey by ROOST](https://github.com/roostorg/osprey)
  * high-performance rules engine for real-time event processing at scale, designed for Trust & Safety and anti-abuse work
* [RulesEngine by Microsoft](https://microsoft.github.io/RulesEngine/)
  * library for abstracting business logic, rules, and policies from a system via JSON  for .NET language families
* [Wikimedia Smite Spam](https://github.com/wikimedia/mediawiki-extensions-SmiteSpam)
  * extension for MediaWiki that helps identify and manage spam content on a wiki


## Review

* [BullMQ](https://github.com/taskforcesh/bullmq)
  * message queue and batch processing for NodeJS and Python based on Redis
* [NCMEC Reporting by ello](https://github.com/ello/ncmec_reporting)
  * Ruby client library for reporting incidents to the National Center for Missing & Exploited Children (NCMEC) CyberTipline
* [Owlculus](https://github.com/be0vlk/owlculus)
  * OSINT (Open-Source Intelligence) toolkit and case management platform
* [RabbitMQ](https://github.com/rabbitmq)
  * message broker that enables applications to communicate with each other by sending messages through queues


## Investigation

* [CIB MangoTree](https://github.com/CIB-Mango-Tree/CIB-Mango-Tree-Website)
  * collection of tools to aid researchers in coordinated inauthentic behavior (CIB) analysis
* [Crossover](https://crossover.social/)
  * open-source project that builds dashboards for monitoring and analyzing the recommendation algorithms of social networks, with a focus on disinformation and election monitoring
* [DAU Dashboard by Tattle](https://github.com/tattle-made/dau-dashboard)
  * Deepfake Analysis Unit(DAU) is a collaborative space for analyzing deepfakes
* [Feluda by Tattle](https://github.com/tattle-made/feluda)
  * configurable engine for analysing multi-lingual and multi-modal content
* [Interference by Digital Forensics Research Lab](https://github.com/DFRLab/interference2024)
  * interactive, open-source database that tracks allegations of foreign interference or foreign malign influence relevant to the 2024 U.S. presidential election
* [OpenMeasures](https://gitlab.com/openmeasures)
  * open source platform for investigating internet trends
* [ThreatExchange by Meta](https://github.com/facebook/ThreatExchange )
  * platform that enables organizations to share information about  threats, such as malware, phishing attacks, and online safety harms in a structured and privacy-compliant manner
* [ThreatExchange Client via PHP](https://github.com/certly/threatexchange)
  * PHP client for ThreatExchange
* [ThreatExchange via Python](https://github.com/facebook/ThreatExchange/tree/main/python-threatexchange)
  * Python library for ThreatExchange
* [TikTok Observatory](https://github.com/aiforensics/tkobservatory)
  * open-source project maintained by [AI Forensics](https://aiforensics.org/) that allows researchers to monitor the promotion and demotion of content by the TikTok reccomendation algorithm


## Datasets

* [Aegis Content Safety by NVIDIA](https://huggingface.co/datasets/nvidia/Aegis-AI-Content-Safety-Dataset-2.0)
  * dataset created by NVIDIA to aid in content moderation and toxicity detection
* [Toxic Chat by LMSYS](https://huggingface.co/datasets/lmsys/toxic-chat)
  * dataset of toxic conversations collected from interactions with Vicuna
* [Toxicity by Jigsaw](https://huggingface.co/datasets/google/jigsaw_toxicity_pred)
  * large number of Wikipedia comments which have been labeled by human raters for toxic behavior
* [Uli Dataset by Tattle](https://github.com/tattle-made/uli_dataset)
  * dataset of gendered abuse, created for Uli ML redaction.
* [VTC by Unitary AI](https://github.com/unitaryai/VTC)
  * implementation of video-text retrieval with comments including a dataset, method of identifying relevant auxiliary information that adds context to videos, and quantification of the value comment-modality bring to video


## Red Teaming Datasets

* [AI Alignment Dataset by Anthropic](https://atlas.nomic.ai/map/anthropic_rlhf)  
  * data used for reinforcement learning with human feedback (RLHF) to align AI models.
* [DEFCOM Red Teaming Dataset](https://github.com/humane-intelligence/ai_village_defcon_grt_data)  
  * dataset from DEF CON’s AI red teaming event.
* [HackAPrompt Jailbreak Dataset](https://huggingface.co/datasets/hackaprompt/hackaprompt-dataset/viewer/default/train?p=1&row=137)  
  * dataset for testing AI vulnerability to prompt-based jailbreaking
* [HiroKachi Jailbreak Dataset](https://sizu.me/love)  
  * dataset focused on adversarial AI prompt attacks
* [Jailbreak Prompt Generator AI Model](https://huggingface.co/tsq2000/Jailbreak-generator)  
  * AI model that generates jailbreak-style prompts
* [JailbreakHub by WalledAI](https://huggingface.co/datasets/walledai/JailbreakHub)
  * collection of jailbreak prompts and corresponding model responses
* [Red Team Resistance Leaderboard](https://huggingface.co/spaces/HaizeLabs/red-teaming-resistance-benchmark)  
  * rankings of AI models based on resistance to adversarial attacks
* [Rentry Jailbreak Datasets](https://rentry.org/gpt0721)  
  * collection of datasets related to jailbreak attempts on AI models
* [SidFeel Jailbreak Dataset](https://github.com/sidfeels/PromptsDB)  
  * collection of prompts used for jailbreaking AI models
 

## Decentralized Platforms

* [Automod by Bluesky](https://github.com/bluesky-social/indigo/tree/main/automod)
  * tool for automating content moderation processes for the Bluesky social network and other apps on the AT Protocol
* [FediCheck](https://connect.iftas.org/library/iftas-documentation/fedicheck/)
  * domain moderation tool to assist ActivityPub service providers, such as Mastodon servers, now open-sourced.
* [Fediverse Spam Filtering](https://github.com/MarcT0K/Fediverse-Spam-Filtering/ )
  * spam filter for Fediverse social media platforms. For now, the current version is only a proof of concept.
* [FIRES](https://github.com/fedimod/fires)
  * reference server + protocol for the exchange of moderation adivsories and recommendations
* [Ozone by Bluesky](https://github.com/bluesky-social/ozone)
  * labeling tool designed for Bluesky. Includes moderation features to action on abuse flags, policy enforcement tools, and investigation features


## User Safety Tools

* [Frankly by Applied Social Media Lab](https://github.com/berkmancenter/frankly/)
  * online deliberations platform that allows anyone to host video-enabled conversations about any topic
* [PolicyKit by UW Social Futures Lab](https://github.com/policykit/policykit)
  * toolkit for building governance in your online community
* [SquadBox by UW Social Futures Lab](https://github.com/amyxzhang/squadbox)
  * tool to help people who are being harassed online by having their friends (or “squad”) moderate their messages
* [Uli by Tattle](https://github.com/tattle-made/Uli)
  * Software and Resources for Mitigating Online Gender Based Violence in India

