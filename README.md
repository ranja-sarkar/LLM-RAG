
A list of **LLMs** available for commercial use: https://github.com/eugeneyan/open-llms


**What is TRANSFER LEARNING?**

In the classic supervised learning scenario of ML, if we intend to train a model for some task and domain 
A, we assume that we are provided with labeled data (train & test) for the same task and domain. 

We can train a model A on this dataset and expect it to perform well on unseen data of the same task and domain. On another occasion, when given data for some other task or domain 
B, we require labeled data of the same task or domain that we can use to train a new model B  so that we can expect it to perform well on this data.

<img width="365" alt="22" src="https://github.com/user-attachments/assets/c4f41fec-2dc8-4bca-a7ed-85dc83024523" />

The traditional supervised learning paradigm breaks down when we do not have sufficient labeled data for the task or domain we care about to train a reliable model and a model that has inherited bias of its training data does not know how to generalize to the new domain. 

**Transfer learning** allows us to deal with these scenarios by leveraging the already existing labeled data of some related task or domain. We try to store this knowledge gained in solving the source task in the source domain and apply it to our problem of interest. 

<img width="370" alt="11" src="https://github.com/user-attachments/assets/43e3e9f7-0e6f-4685-b467-f1be32006608" />

In practice, we seek to transfer as much knowledge as we can from the source setting to our target task or domain. 

https://neptune.ai/blog/transfer-learning-guide-examples-for-images-and-text-in-keras


**What is ZERO-SHOT LEARNING?**

If we take transfer learning to the extreme and aim to learn from only a few, one or zero instances of a class, we arrive at few-shot, one-shot, and zero-shot learning respectively. 

Enabling models to perform one-shot and zero-shot learning is admittedly among the hardest problems in ML. At the same time, it is something that comes naturally to us humans: Toddlers only need to be told once what a dog is in order to be able to identify any other dog, while adults can understand the essence of an object just by reading about it in context, without ever having encountered it before.

In the more realistic generalized **zero-shot learning**, training classes are present only at test time and has garnered attention post this publication of late 2020:
https://arxiv.org/pdf/1703.04394

A **zero-shot** topic classification demo is here: https://huggingface.co/spaces/joeddav/zero-shot-demo


In July 2020, transfer learning in LLMs garnered attention post publication of the paper entitled **'Language Models are few-shot learners'**:
https://arxiv.org/pdf/2005.14165

