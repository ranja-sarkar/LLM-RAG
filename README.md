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
