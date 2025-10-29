# Unambiguous Definition Generation in Semantically Scarce Terminological Resources

High-quality terminological resources are essential for ensuring semantic precision and interoperability in specialised NLP applications. However, many existing terminological databases, such as the InterActive Terminology for Europe (IATE), lack important semantic information for the reutilization of terms.  

This study explores whether Large Language Models (LLMs) can generate accurate, domain-appropriate definitions for specialised terms by using contextual information extracted from existing terminological resources. Two open-source models, **Llama-3.1-8B-Instruct** and **Mistral-7B-v0.1**, were evaluated across four experimental setups with progressively richer semantic context:  
1. **Zero-shot prompting** with term and domain labels.  
2. **Prompting with semantic information**, based on the addition of structured metadata.
3. **Retrieval-Augmented Generation (RAG) with semantic information** for relational contextualization. 
4. **Scrapping** from external documents for context retrieval.

Results show that structured semantic metadata improves generation quality, while excessive or noisy contextual input can produce worse performance. For this task, **Llama-3.1** consistently outperformed **Mistral-7B**.  


![Pipeline Diagram](https://github.com/luxxiferr/definitions_terminology_llm/blob/main/img/pipeline.drawio.svg?raw=true)
