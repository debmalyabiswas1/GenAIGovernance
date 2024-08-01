Collection of Resources to implement an effective 
Generative AI Governance Program at Enterprises

A comprehensive checklist is the first step in implementing an effective Generative AI (Gen AI) Governance program.

We are seeing a lot of cases where Data Science or Data Protection Impact Assessment (DPIA) checklists are getting repurposed for Gen AI Governance. While relevant, most of them only address a part of the puzzle - deep diving into that specific aspect.

Gen AI solutions are complex. Given this, a holistic understanding of all aspects involved in a Gen AI solution: use-case - to - architecture - to - evaluation - to -privacy - to - risk is needed to properly govern Gen AI solutions in an Enterprise. For example, effective risk management cannot be implemented without an understanding of the underlying solution architecture: Retrieval Augmented Generation (RAG) or Fine-tuning. 

In case of RAG, privacy risks are limited to the enterprise data retrieved as 'context' to the prompt. Fine-tuning leads to the creation of a new Small Language Model (SLM) with embedded enterprise data, that can be further used as an Large Language Model (LLM) by downstream applications. Hence, this new SLM needs to be provided the same privacy and risk attention as a pre-trained LLM.

This is a first attempt towards creating a comprehensive Gen AI Governance Checklist. 

The document is structured in the form of a Gen AI Solution Card. It aims to provide the necessary details of the underlying Gen AI solution, such that it can be deployed in a scalable and responsible fashion, complying with applicable regulations. Given this, it serves as an initial governance checklist for the Legal, Privacy, Auditing, Responsible AI, Ethical AI, etc. teams of the enterprise to understand the design, capabilities, and constraints of the Gen AI solution. 

The only constraint that we had in mind was to keep it to 25 questions - so as not to overwhelm the development teams -:) We do believe that something like this should not be done in isolation (redundant work) and will benefit from community participation - so uploading it on Github under MIT license (which is one of the most permissive licenses).
So please feel free to use it as desired (including for commercial usage) and submit your suggestions / updates - looking forward to a healthy dialogue on the same.
