# Geo-Explore
This repository contains the final project for DSE 511. The main objective of this project is to develop a proof of concept framework for the best ways to generate embedding spaces in relation to the built environment. The overall goal is to generate a platform for information retrieval (IR) of the built environment. For example, if an extreme event happens at a specified location within a major city, what will the impact be on the surrounding infrastructure? One of the main issues within the current literature is that building attribution models are all bespoke, done in different areas of interest (AOI's), and also using different methods. With the advances of generative artifical intelligence (AI), is it possible to leverage existing Large Language Models (LLMs) to enhance how the built environment is currently modeled? While LLMs have shown progress, there are issues associated with how they reason with spatial cognition, a known and common issue. However, leveraging vector spaces has shown the potential for LLMs to then integrate the ancillary vectors into an intrinsic meaning, allowing for a fusion of corpus. This yields the following questions: Is it possible to generate new vector spaces to enhance the abilities of current LLMs to enhance built environment cognition at the building level? How many vector spaces (buildings, roads, transmission lines, etc.) are possible? How are buildings represented in the vector space (is one building a vector? Or are all buildings a vector?)? 

The best possible outcome for this project would be to develop a baseline workflow which shows that including a ancillary data layer to be embedded: buildings with points of interest information (GeoJSON), improves upon the current LLMs comprehension of the built environment. Furthermore, additional insight into how the embedding space currently handles the GeoJSON (i.e. is one building parsed into an individual vector? Or are all buildings in the GeoJSON processed in one singular vector space?) will prove seminal for further work. 

All tasks and issues will be tracked on this repository.

# Objectives
Shirley
- develop a high quality and encompasing figure for our workflow
- learn more about rag approaches and generative AI (LangChain book chapters 2-4, more if comfortable)
- assistance with writing the results/discussion
- assist in prompt generation

Eva
- Will discuss on Tuesday, 11/11
- Have a few ideas, one of which is to better understand the embedding space, would love your thoughts on this
- assistance with writing the methods
- assist in prompt generation

Anibely
- Repository management
- model selection for embedding space
- assistance with writing the methods / results

Clinton
- Manuscript completion (introduction, literature review, methods, results, discussion)
- direction for prompt generation
- modeling


# Prompt Guidance
I think that 3 high-level groups of prompts will be developed

1) Location based prompts
- "what direction is the building located at x, y from the nearest sea or ocean"

2) Distance based prompts
- "how far is building located at x, y from the nearest sea or ocean"

3) Contextual based prompts
- "How many buildings are within 1,000 meters from the building located at x, y?"

# POC
- Clinton Stipek - cstipek@vols.utk.edu
- Feel free to add your names here

# Manuscript
https://www.overleaf.com/4319268146rbknjkqpssjz#632785

# Relevant Research to Read
- Demystifying embedding spaces using Large Language Models (Tennenholtz); https://arxiv.org/abs/2310.04475
- A semantic embedding space based on large language models for modelling human beliefs (Lee); https://www.nature.com/articles/s41562-025-02228-z
- A systematic review of geospatial location embedding approaches in large language models: A path to spatial AI systems (Tucker); https://arxiv.org/abs/2401.10279
- Embedding-Aligned Language Models (Tennenholtz); https://arxiv.org/abs/2406.00024
