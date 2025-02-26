# awesome-safety-tools
A curated collection of open source tools for online safety


Inspired by prior work like [Awesome Redteaming](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming/) and [Awesome Phishing](https://github.com/PhishyAlice/awesome-phishing). 

Help and contribute by adding a pull request to add more resources and tools!


## Hash Matching 
* [Hasher Matcher Action (HMA) by Meta](https://github.com/facebook/ThreatExchange/tree/main/hasher-matcher-actioner)
  * hashing algorithm, matching function, and ability to hook into actions
* [PDQ by Meta](https://github.com/facebook/ThreatExchange/tree/main/pdq)
  * perceptual hash algorithm for images
* [TMK by Meta](https://github.com/facebook/ThreatExchange/tree/main/tmk)
  * visual similarity match for videos
* [VPDQ](https://github.com/facebook/ThreatExchange/tree/main/vpdq)
  * visual similarity match for videos using PDQ algorithm 
* [Hasher-Matcher-Actioner (CLIP demo)](https://github.com/juanmrad/HMA-CLIP-demo)
  * HMA extension for CLIP as reference for adding other format extensins
* [Perception ](https://github.com/thorn-oss/perception)
  * provides a common wrapper around existing, popular perceptual hashes (such as those implemented by ImageHash)
* [Altitude by Jigsaw](https://github.com/jigsaw-code/altitude)
  * web UI and hash matching for violent extremism and terrorism content
* [Lattice Extract by Adobe](https://github.com/adobe/lattice_extract)
  * grid and lattice detection to guard against FP in hash matching
* [RocketChat CSAM](https://github.com/prostasia/rocketchatcsam)
  * CSAM hash matching for RocketChat
* [MediaModeration (Wiki Extension)](https://github.com/wikimedia/mediawiki-extensions-MediaModeration?tab=readme-ov-file)
  * CSAM hash matching for Wikimedia

## Classification
* [OSmod by Jigsaw](https://github.com/conversationai/conversationai-moderator)
  * toolkit of machine learning (ML) tools, models, and APIs that platforms can use to moderate content
* [Perspective API by Jigsaw](https://github.com/conversationai/perspectiveapi)
  * machine learning-powered tool that helps platforms detect and assess the toxicity of online conversations
* [Presidio by Microsoft](https://github.com/microsoft/presidio)
  * toolset for detecting Personal Identifiable Information (PII) and other sensitive data in images and text
* [Llama Guard by Meta](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard3)
  * AI-powered content moderation model to detect harm in text-based interactions
* [Purple Llama by Meta](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard3)
  * set of tools to assess and improve LLM security. Includes Llama Guard, CyberSec Eval, and Code Shield
* [ShieldGemma by Google DeepMind](https://www.kaggle.com/code/fernandosr85/shieldgemma-web-content-safety-analyzer?scriptVersionId=198456916)
  * AI safety toolkit by Google DeepMind designed to help detect and mitigate harmful or unsafe outputs in LLM applications
* [Roblox Voice Safety Classifier](https://github.com/Roblox/voice-safety-classifier)
  * machine learning model that detects and moderates harmful content in real-time voice chat on Roblox. Focuses on spoken language detection.
* [Detoxify by Unitary AI](https://github.com/unitaryai/detoxify)
  * detects and mitigates generalized toxic language (including hate speech, harassment, bullying) in text
* [NSFW Filtering](https://github.com/nsfw-filter/nsfw-filter)
  * browser extension to block explicit images from online platforms. User facing.
* [NSFW Keras Model](https://github.com/GantMan/nsfw_model)
  * convoluted neural network (CNN) based explicit image ML model 
* [Guardrails AI](https://github.com/guardrails-ai/guardrails)
  * a Python framework that helps build safe AI applications checking input/output for predefined risks

## Core Infrastructure
* [Mjolnir by Matrix](https://github.com/matrix-org/mjolnir)
  * moderation bot for the Matrix protocol that automatically enforces content policies
* [AbuseIO](https://github.com/AbuseIO/AbuseIO)
  * abuse management platform designed to help organizations handle and track abuse complaints related to online content, infrastructure, or services
* [Ozone by Bluesky](https://github.com/bluesky-social/ozone)
  * labeling tool designed for Bluesky. Includes moderation features to action on abuse flags, policy enforcement tools, and investigation features
* [Open Truss by Github](https://github.com/open-truss/open-truss)
  * framework designed to help users create internal tools without needing to write code
* [Access by Discord](https://github.com/discord/access)
  * a centralized portal for managing access to internal systems within any organization

## Clustering
* [SpamAssassin by Apache](https://spamassassin.apache.org)
  * anti-spam platform that uses a variety of techniques, including text analysis, Bayesian filtering, and DNS blocklists, to classify and block unsolicited email
* [scikit-learn](https://github.com/scikit-learn/scikit-learn)
  * python library including clustering through various algorithms, such as K-Means, DBSCAN, and hierarchical clustering


## Rules Engines
* [RulesEngine by Microsoft](https://microsoft.github.io/RulesEngine/)
  * a library for abstracting business logic, rules, and policies from a system via JSON  for .NET language families
* [Marble](https://github.com/checkmarble/marble)
  * a real-time fraud detection and compliance engine tailored for fintech companies and financial institutions
* [Automod](https://github.com/bluesky-social/indigo/tree/main/automod)
  * a tool for automating content moderation processes for the Bluesky social network and other apps on the AT Protocol
* [Wikimedia Smite Spam](https://github.com/wikimedia/mediawiki-extensions-SmiteSpam)
  * an extension for MediaWiki that helps identify and manage spam content on a wiki


## Review
* [RabbitMQ](https://github.com/rabbitmq)
  * a message broker that enables applications to communicate with each other by sending messages through queues
* [BullMQ](https://github.com/taskforcesh/bullmq)
  * message queue and batch processing for NodeJS and Python based on Redis
* [Owlculus](https://github.com/be0vlk/owlculus)
  * an OSINT (Open-Source Intelligence) toolkit and case management platform
* [NCMEC Reporting by ello](https://github.com/ello/ncmec_reporting)
  * a Ruby client library for reporting incidents to the National Center for Missing & Exploited Children (NCMEC) CyberTipline

## Threat Intelligence
* [ThreatExchange by Meta](https://github.com/facebook/ThreatExchange )
  * a platform that enables organizations to share information about  threats, such as malware, phishing attacks, and online safety harms in a structured and privacy-compliant manner
* [ThreatExchange Client via PHP](https://github.com/certly/threatexchange)
  * a PHP client for ThreatExchange
* [ThreatExchange via Python](https://github.com/facebook/ThreatExchange/tree/main/python-threatexchange)
  * a Python library for ThreatExchange
* [FediCheck](  https://about.iftas.org/activities/moderation-as-a-service/fedicheck/)
  * a web service designed to assist ActivityPub service providers, such as Mastodon servers

## Datasets
* [Aegis Content Safety by NVIDIA](https://huggingface.co/datasets/nvidia/Aegis-AI-Content-Safety-Dataset-2.0)
  * a dataset created by NVIDIA to aid in content moderation and toxicity detection
* [Toxicity by Jigsaw](https://huggingface.co/datasets/google/jigsaw_toxicity_pred)
  * a large number of Wikipedia comments which have been labeled by human raters for toxic behavior
