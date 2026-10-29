# AI Threat Hunting Agent

An AI agent that turns a threat hypothesis into an investigation plan, queries laboratory logs, gathers evidence, and explains its findings.

**Status:** project planning. The architecture, tools, and milestones below are proposals; they do not describe a working implementation yet.

## Official project

**Subject 9: Agent IA de Threat Hunting**

> Construire un agent qui transforme une hypothèse de menace en plan d'investigation, génère des requêtes sur des logs de laboratoire, interprète les résultats et rassemble les preuves. Le système doit justifier ses conclusions, indiquer l'incertitude et associer les observations aux tactiques et techniques MITRE ATT&CK.

Required concepts: **AI Agent, LLM, SIEM/logs, RAG, MITRE ATT&CK**.

The assignment is available in [subject.pdf](subject.pdf).

## What is threat hunting?

Threat hunting means actively looking for evidence of an attack, including situations where no automatic alert has fired.

A hunt starts with a hypothesis, such as:

> Someone may have guessed an SSH password and accessed the Raspberry Pi.

The investigator decides which records could support or contradict that idea, searches them, and assesses the results. A hypothesis is a question to investigate, rather than a conclusion to prove.

Repeated failed logins can have innocent explanations. A successful login after failures does not, by itself, prove that an account was compromised.
