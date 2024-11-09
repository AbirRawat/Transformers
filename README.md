Python implementations of both Self-Attention and Multi-Head Attention mechanisms, core components of transformer architectures widely used in NLP and time-series models.

Self-Attention: Computes attention scores using query, key, and value (Q, K, V) vectors. The attention score is calculated as:

![Screenshot 2024-11-10 021824](https://github.com/user-attachments/assets/894d3c07-8e96-4027-b9f1-ae7c961dffb6)


![Screenshot 2024-11-10 021810](https://github.com/user-attachments/assets/d4958be0-6257-43fe-a906-40ce65a21db1)


​where dk is the dimension of the key vector, and Softmax is applied to highlight relevant tokens.

Multi-Head Attention: Extends self-attention by applying multiple attention heads to capture diverse patterns. Each head performs attention independently, and outputs are concatenated and transformed to enhance representation power.

Both models are modular and flexible, with clear explanations and examples to facilitate usage and experimentation.
