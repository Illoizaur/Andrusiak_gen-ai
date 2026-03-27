# LLM Agentic Legal Information Retrieval 
## Andrusiak, IPZ-41

### Overview
This competition challenges you to build an LLM-powered agentic legal information retrieval system for Swiss law.

For each English legal question, your model must retrieve and output the most relevant Swiss legal sources (statutes, decisions, etc. mostly cited in German). The goal is to produce a set of citations that best matches the reference solution on a hidden test set.

You’ll get a public training dataset to develop your approach, and you’ll be evaluated on how accurately your predicted citations match the ground truth (citation-level Macro F1).
