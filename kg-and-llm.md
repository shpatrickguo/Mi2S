---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# KG + LLM

{% embed url="https://medium.com/@bijit211987/enhancing-llms-inference-with-knowledge-graphs-7140b3c3d683" %}

## Knowledge Graph Integration Strategies

### Knowledge Graph Embeddings

Represent entities and relations in the knowledge graph as dense vector embeddings, which can be incorporated into the language model’s input or output representations. This allows the model to capture and utilize relational knowledge during training or inference.\


{% embed url="https://towardsdatascience.com/knowledge-graph-embeddings-101-2cc1ca5db44f" %}

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://arxiv.org/abs/2309.12501" %}

### Knowledge Graph Augmentation

Augment the language model’s training data with knowledge graph triples, effectively teaching the model to better represent and reason over structured knowledge.\


{% embed url="https://arxiv.org/abs/2203.13965" %}

{% embed url="https://aclanthology.org/2022.coling-1.220/" %}

### Knowledge Graph Retrieval

During inference, retrieve relevant knowledge graph subgraphs or facts based on the input text, and provide this structured knowledge as additional context to the language model.

### Knowledge-Grounded Generation

Develop language generation models that can directly generate text conditioned on knowledge graph facts, ensuring the generated output respects and accurately reflects the provided knowledge.

### Multi-Task Learning:

&#x20;Train language models on a combination of traditional language tasks (e.g., text generation, question answering) and knowledge graph tasks (e.g., link prediction, path ranking), enabling them to develop both language understanding and structured knowledge capabilities.

{% embed url="https://medium.com/@researchgraph/enhancing-language-models-the-role-of-knowledge-graph-augmentation-in-overcoming-llm-challenges-c232b5e9328f" %}
Unveiling Strategies to Enhance LLMs through Knowledge Graphs
{% endembed %}

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>
