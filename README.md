# KnowledgeGraph-LLM
KnowledgeGraph created using OpenAI ChatGPT to understand LLM reasoning and troubleshooting.

**Project Files**
- [📄 Dummy Dataset (dummy_data.txt)](./dummy_data.txt)
- [🌐 Knowledge Graph Visualization (knowledgegraph.html)](./knowledge_graph.html)

---

The dataset of this project was generated synthetically using the OpenAI LLM and inserted in `dummy_data.txt`.

### Workflow
The project was created in a Python notebook (Google Colab) and ingests a text file to read and create a knowledge graph by running a chain of prompts.

The workflow consists of seven stages:

Input Text  
   ↓  
[1] Preprocessing  
   ↓  
[2] Entity Extraction  
   ↓  
[3] Relationship Extraction  
   ↓  
[4] Personality & Attribute Extraction  
   ↓  
[5] Graph Schema Generation  
   ↓  
[6] Graph Construction (e.g., Neo4j / NetworkX / RDF)  
   ↓  
[7] (Optional) Reasoning & Visualization  

---

### Execution
The workflow was executed using **LangChain** and **OpenAI API**, with iterative prompting and debugging both manually and through the LLM.

### Results
The results of the generated knowledge graph can be viewed here:
👉 [View Knowledge Graph Visualization](./knowledge_graph.html)
