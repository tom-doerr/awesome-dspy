# Awesome DSPy

A curated list of awesome examples and resources for DSPy.

## Table of Contents

- [Agents](#agents)
- [Dataloaders](#dataloaders)
- [Functional](#functional)
- [Integrations](#integrations)
- [Longform QA](#longform-qa)
- [Math](#math)
- [NLI](#nli)
- [QA](#qa)
- [Quiz](#quiz)
- [Text to SQL](#text-to-sql)
- [Tweets](#tweets)
- [Videos](#videos)
- [Papers](#papers)
- [Other Resources](#other-resources)

## Agents

- [multi_agent.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/agents/multi_agent.ipynb): Multi-agent system examples.
- [multi_agent_llama3.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/agents/multi_agent_llama3.ipynb): Multi-agent system using Llama3.

## Dataloaders

- [dataloaders_dolly.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/dataloaders/dataloaders_dolly.ipynb): Dataloaders for the Dolly dataset.
- [dolly_subset_100_rows.csv](https://github.com/stanfordnlp/dspy/blob/main/examples/dataloaders/dolly_subset_100_rows.csv): Subset of the Dolly dataset with 100 rows.

## Functional

- [functional.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/functional/functional.ipynb): Functional programming in Python.
- [repl.py](https://github.com/stanfordnlp/dspy/blob/main/examples/functional/repl.py): REPL for testing functional programming concepts.
- [signature_opt_typed.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/functional/signature_opt_typed.ipynb): Optimized function signatures with type hints.
- [Using DSPy to train Gpt 3.5 on HumanEval by Thomas Ahle](https://github.com/stanfordnlp/dspy/blob/main/examples/functional/functional.ipynb): Training Gpt 3.5 on HumanEval.
- [Building a chess playing agent using DSPy by Franck SN](https://medium.com/thoughts-on-machine-learning/building-a-chess-playing-agent-using-dspy-9b87c868f71e): Creating a chess-playing agent with DSPy.

## Integrations

- [clarifai_llm_retriever_example.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/integrations/clarifai/clarifai_llm_retriever_example.ipynb): Example integration with Clarifai LLM retriever.
- [readme.md](https://github.com/stanfordnlp/dspy/blob/main/examples/integrations/readme.md): Documentation for integrations.

## Longform QA

- [longformqa_assertions.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/longformqa/longformqa_assertions.ipynb): Assertions in long-form question answering.
- [utils.py](https://github.com/stanfordnlp/dspy/blob/main/examples/longformqa/utils.py): Utility functions for long-form QA.
- [Long-form Answer Generation with Citations, by Arnav Singhvi](https://colab.research.google.com/github/stanfordnlp/dspy/blob/main/examples/longformqa/longformqa_assertions.ipynb): Applying DSPy Assertions in long-form answer generation.

## Math

- [CoT.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/math/gsm8k/CoT.ipynb): Chain of Thought (CoT) in math problems.
- [turbo_8_8_10_gsm8k_200_300.json](https://github.com/stanfordnlp/dspy/blob/main/examples/math/gsm8k/turbo_8_8_10_gsm8k_200_300.json): GSM8K dataset for Turbo model.

## NLI

- [scone-cot_fewshot-turbo-gpt4-demos.json](https://github.com/stanfordnlp/dspy/blob/main/examples/nli/scone/scone-cot_fewshot-turbo-gpt4-demos.json): SCONE dataset demos with CoT and few-shot learning.
- [scone.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/nli/scone/scone.ipynb): SCONE dataset examples.
- [Indian Languages NLI with gains due to compiling by Saiful Haq](https://github.com/saifulhaq95/DSPy-Indic/blob/main/indicxlni.ipynb): Indian Languages NLI examples.

## QA

- [hotpotqa_with_assertions.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/qa/hotpot/hotpotqa_with_assertions.ipynb): HotpotQA with assertions.
- [hotpotqa_with_MIPRO.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/qa/hotpot/hotpotqa_with_MIPRO.ipynb): HotpotQA with MIPRO.
- [multihop_finetune.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/qa/hotpot/multihop_finetune.ipynb): Multi-hop finetuning for QA.
- [DSPy on BIG-Bench Hard Example, by Chris Levy](https://drchrislevy.github.io/posts/dspy/dspy.html): BIG-Bench Hard Example with DSPy.

## Quiz

- [quiz_assertions.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/quiz/quiz_assertions.ipynb): Quiz assertions.
- [Generating Answer Choices for Quiz Questions, by Arnav Singhvi](https://colab.research.google.com/github/stanfordnlp/dspy/blob/main/examples/quiz/quiz_assertions.ipynb): Applying DSPy Assertions in quiz question generation.

## Text to SQL

- [financial_data_text_to_sql.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/text_to_sql/financial_data_text_to_sql.ipynb): Converting financial data to SQL queries.
- [Optimizing Performance of Open Source LM for Text-to-SQL using DSPy and vLLM, by Juan Ovalle](https://github.com/jjovalle99/DSPy-Text2SQL): Text-to-SQL optimization with DSPy.

## Tweets

- [compiling_langchain.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/tweets/compiling_langchain.ipynb): Compiling LangChain examples.
- [tweet_metric.py](https://github.com/stanfordnlp/dspy/blob/main/examples/tweets/tweet_metric.py): Metrics for analyzing tweets.
- [tweets_assertions.ipynb](https://github.com/stanfordnlp/dspy/blob/main/examples/tweets/tweets_assertions.ipynb): Assertions in tweet analysis.
- [Generating Tweets for QA, by Arnav Singhvi](https://colab.research.google.com/github/stanfordnlp/dspy/blob/main/examples/tweets/tweets_assertions.ipynb): Applying DSPy Assertions in tweet generation.
- [AI feedback, or writing LM-based metrics in DSPy](https://github.com/stanfordnlp/dspy/blob/main/examples/tweets/tweet_metric.py): Writing LM-based metrics in DSPy.

## Videos

- [Getting Started with RAG in DSPy!](https://www.youtube.com/watch?v=CEuUG4Umfxs&list=PLnn6VZp3hqNs_4E6toR990Pg1-2aDuzDq)
- [DSPy Explained!](https://www.youtube.com/watch?v=41EfOY0Ldkc&list=PLnn6VZp3hqNs_4E6toR990Pg1-2aDuzDq&index=2)
- [Adding Depth to DSPy Programs](https://www.youtube.com/watch?v=0c7Ksd6BG88&list=PLnn6VZp3hqNs_4E6toR990Pg1-2aDuzDq&index=3)
- [Structured Outputs with DSPy](https://www.youtube.com/watch?v=tVw3CwrN5-8&list=PLnn6VZp3hqNs_4E6toR990Pg1-2aDuzDq&index=4)

## Papers

- **[Oct'23] [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714)**     
- **[Jan'24] [In-Context Learning for Extreme Multi-Label Classification](https://arxiv.org/abs/2401.12178)**       
- **[Dec'23] [DSPy Assertions: Computational Constraints for Self-Refining Language Model Pipelines](https://arxiv.org/abs/2312.13382)**   
- **[Dec'22] [Demonstrate-Search-Predict: Composing Retrieval & Language Models for Knowledge-Intensive NLP](https://arxiv.org/abs/2212.14024.pdf)

