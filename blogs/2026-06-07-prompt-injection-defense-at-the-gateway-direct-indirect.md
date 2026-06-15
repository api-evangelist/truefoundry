---
title: "Prompt Injection Defense at the Gateway: Direct, Indirect, and Tool-Mediated Attacks"
url: "https://www.truefoundry.com/blog/prompt-injection-defense-llm-gateway"
date: "2026-06-07"
author: "Boyu Wang"
feed_url: "https://www.truefoundry.com/blog"
---
Prompt injection represents a fundamental security challenge in LLM systems because the model reads trusted instructions and untrusted data through the same channel, with no reliable way to tell them apart. The attack landscape includes direct injection within user input, indirect injection through retrieved documents or tool results, tool-mediated injection via poisoned metadata, and jailbreaks. The core vulnerability stems from a structural problem: LLMs concatenate system prompts, user messages, and external content into one token stream without clear boundaries distinguishing directives from data.
