# BamTwoogle dataset

This repository contains the BamTwoogle dataset for the paper [ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent](https://arxiv.org/abs/2312.10003).

## Overview

BamTwoogle is a small (100 questions in total), handcrafted collection of information-seeking questions. It was written to be a complementary, slightly more challenging sequel to [Bamboogle](https://github.com/ofirpress/self-ask/blob/main/datasets/bamboogle.md) dataset.

## Dataset Description

The topics and question formats vary, but in general, BamTwoogle adheres to the following guidelines.

### Questions
- The majority of questions require two searches or reasoning steps (like Bamboogle), but some of them need 3 or 4.
- Must have been manually checked to ensure the answer doesn’t appear on the first page of Google search results.

### Expected answers
- Should not be ambiguous.
- Should not be prone to change over time, either due to the phrasing of the question or to the nature of the answer.
- Should account for multiple versions of proper names, etc., where appropriate.
- Should prefer Wikipedia as the source of truth for facts (preference given to topics/articles not flagged for incompleteness, lack of sources, etc.)

# Citation

```
@misc{aksitov2023restmeetsreactselfimprovement,
      title={ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent}, 
      author={Renat Aksitov and Sobhan Miryoosefi and Zonglin Li and Daliang Li and Sheila Babayan and Kavya Kopparapu and Zachary Fisher and Ruiqi Guo and Sushant Prakash and Pranesh Srinivasan and Manzil Zaheer and Felix Yu and Sanjiv Kumar},
      year={2023},
      eprint={2312.10003},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2312.10003}, 
}
```
