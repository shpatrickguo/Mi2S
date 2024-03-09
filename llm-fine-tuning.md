---
description: Purpose, Data Preparation, Code, and Comparative Results
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

# LLM Fine-Tuning

曾經拿哪個 LLM Base Model 作 Fine tuning&#x20;

當初是出於什麼目的要 Fine-tuning? 比如說希望他在哪方面或哪個 Domain 表現更好&#x20;

需要準備哪些資料？&#x20;

相關的程式碼

最後有任何的實驗結果比較有無 Fine-tuning 之類的



### DeBERTa

{% embed url="https://arxiv.org/abs/2006.03654" %}
He, Pengcheng, et al. "Deberta: Decoding-enhanced bert with disentangled attention." _arXiv preprint arXiv:2006.03654_ (2020).
{% endembed %}

{% embed url="https://arxiv.org/abs/2111.09543" %}
He, Pengcheng, Jianfeng Gao, and Weizhu Chen. "Debertav3: Improving deberta using electra-style pre-training with gradient-disentangled embedding sharing." _arXiv preprint arXiv:2111.09543_ (2021).
{% endembed %}

{% @github-files/github-code-block %}

<figure><img src=".gitbook/assets/1_6PgadenApxx4vQ-YEu2Wcg (4).png" alt=""><figcaption><p>Enhanced mask decoder in DeBERTa. <a href="https://towardsdatascience.com/large-language-models-deberta-decoding-enhanced-bert-with-disentangled-attention-90016668db4b">https://towardsdatascience.com/large-language-models-deberta-decoding-enhanced-bert-with-disentangled-attention-90016668db4b</a></p></figcaption></figure>

### Mistral 7B

{% embed url="https://arxiv.org/abs/2310.06825" %}
Jiang, Albert Q., et al. "Mistral 7B." _arXiv preprint arXiv:2310.06825_ (2023).
{% endembed %}

{% embed url="https://huggingface.co/mistralai/Mistral-7B-v0.1" %}

{% embed url="https://mistral.ai/news/announcing-mistral-7b/" %}

{% @github-files/github-code-block %}
