# Financial Advisor using LLMs

#### Capstone Fall 2023 with Accenture

#### Title
Reinforcement Learning using Generative AI LLMs

#### Team Members 
```
Eklavya Jain       (ej2487) (Team Captain)
Priyanka Balakumar (pb2893)
Daniel Young       (day2127)
Dianjing Fan       (df2853)
Ji Qi              (jq2365)
Rohan Poddar       (rp3119)
Hernan Figueroa    (hf2314)
Grant Kim          (gk2636)
```
#### Accenture Mentors
```
Satish Banka
Subha Seshagiri
```
#### Instructor CA
```
Peter Chao
```

#### Abstract

Large Language Models (LLMs) can revolutionize the financial advisory industry by providing automated investing advice in an efficient and accessible way to potential investors. However, utilizing LLMs in the financial industry presents multiple challenges such as obtaining up-to-date data in diverse formats, aligning LLMs responses to human expectations, and cost-effectively updating the LLMs for an evolving financial environment. Our capstone project addresses these issues by integrating open-source LLM models and the latest generative AI technology. This report details our project's progress in creating an advanced portfolio advisor using Large Language Models (LLMs) like Llama2 and Mistral, enhanced with strategies such as Retrieval Augmented Generation (RAG) and Reinforcement Learning from Human Feedback (RLHF). Our approach also involves assembling extensive financial data, employing vector storage and utilizing prompt optimization to improve LLM responses. We reference pioneering works such as FinGPT and BloombergGPT, exploring contributions to training processes and financial applications. Our methodology focuses on LLM selection, fine-tuning, and real-time data integration to implement automated financial advisor capabilities.

#### Results

The evaluation metrics resulted in comparable results across the three models. Mistral DPO exhibited the highest semantic similarity, GPT-3.5 excelled in cosine similarity, and Mistral SFT demonstrated the best perplexity. Overall, we find strong results for a proof of concept model-agnostic, open-source financial advisor LLM application using low compute and limited data.

#### Directory Structure

This is a parent repository consisting of two submodules:
1. `rag`: RAG, prompt optimization, User Interface
2. `fin-rlhf`: Fine-tuning, RLHF

Both the submodules have appropriate READMEs that can help set up the environment and run desired functions.

