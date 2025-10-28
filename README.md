# Unambiguous Definition Generation in Semantically Scarce Terminological Resources

 High-quality terminological resources are essential for ensuring semantic precision and interoperability in specialised
 NLP applications. However, many existing terminological databases, such as the InterActive Terminology for
 Europe (IATE), lack complete definitional information, limiting their usability. This paper investigates whether Large
 Language Models (LLMs) can generate accurate and domain-appropriate definitions for specialised terms using
 contextual cues extracted from existing terminological resources. Two open-source models (Llama-3.1-8B-Instruct
 and Mistral-7B-v0.1) were evaluated across four experiments with increasing levels of semantic enrichment: (1)
 zero-shot prompting with term and domain labels, (2) addition of structured metadata, (3) relational enrichment via
 Retrieval Augmented Generation (RAG), and (4) context retrieval from external documents. The evaluation shows
 that structured semantic metadata significantly improves generation quality, while excessive or noisy contextual
 information can hinder performance. For this specific task, Llama-3.1 consistently outperformed Mistral-7B.
 The findings highlight the potential of LLMs to support the automatic drafting of terminological definitions while
 emphasising the importance of curated, structured semantic input.

 
![Diagrama del pipeline](https://github.com/luxxiferr/definitions_terminology_llm/blob/main/img/pipeline.drawio.svg?raw=true)
