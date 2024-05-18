# Voice Datasets

## AISHELL-4

{% embed url="https://www.openslr.org/111/" %}

## AISHELL-3

{% embed url="https://www.openslr.org/93/" %}

## AISHELL-1&#x20;

{% embed url="https://www.openslr.org/33/" %}

## Free ST Chinese Mandarin Corpus

{% embed url="https://www.openslr.org/38/" %}

## Primewords Chinese Corpus Set 1

{% embed url="https://www.openslr.org/47/" %}

## aidatatang\_200zh

{% embed url="https://www.openslr.org/62/" %}

## MAGICDATA Mandarin Chinese Read Speech Corpus

{% embed url="https://www.openslr.org/68/" %}

## AliMeeting

{% embed url="https://www.openslr.org/119/" %}

## HI-MIA-CW

{% embed url="https://www.openslr.org/120/" %}

## WenetSpeech

{% embed url="https://www.openslr.org/121/" %}

The WenetSpeech corpus is a 10000+ hours multi-domain transcribed Mandarin Speech Corpus collected from YouTube and Podcast. Optical character recognition (OCR) and automatic speech recognition (ASR) techniques are adopted to label each YouTube and Podcast recording, respectively. To improve the quality of the corpus, we use a novel end-to-end label error detection method to further validate and filter the data.

* 10000+ hours high-label data: with confidence >= 0.95, for supervised training, etc.
* 2400+ hours weak-label data: with 0.6 <= confidence < 0.95, for semi-supervisied or noisy training, etc.
* \~10000 hours unlabeled data: with confidence < 0.6, for unsupervised training, etc.
* 22400+ hours audio in total: consists of both labeled and unlabeled data, for unsupervised training or pretraining, etc.

**Diversity**

The high-label data of Wenetspeech can be mainly classified into 10 categories according to speaking styles and spoken scenarios:

* drama (43.36%)
* reading (11.1%)
* interview (9.38%)
* news (8.68%)
* variety (8.27%)
* documentary (4.77%)
* talk (2.94%)
* audiobook (2.51%)
* commentary (2.48%)

WenetSpeech语料库是一个包含超过10000小时多领域普通话转录语料库，数据来源于YouTube和Podcast。我们采用光学字符识别（OCR）和自动语音识别（ASR）技术，分别为每个YouTube和Podcast录音进行标注。为了提高语料库的质量，我们使用了一种新颖的端到端标签错误检测方法，进一步验证和筛选数据。

* 超过10000小时的高标签数据：置信度 >= 0.95，用于监督学习等。
* 超过2400小时的弱标签数据：0.6 <= 置信度 < 0.95，用于半监督学习或噪声训练等。
* 约10000小时的未标记数据：置信度 < 0.6，用于无监督学习等。
* 总共22400+小时的音频数据：包括标记数据和未标记数据，用于无监督学习或预训练等。

多样性 WenetSpeech的高标签数据主要根据说话风格和语境分为以下10类：

* 剧本 (43.36%)
* 朗读 (11.1%)
* 采访 (9.38%)
* 新闻 (8.68%)
* 综艺 (8.27%)
* 纪录片 (4.77%)
* 演讲 (2.94%)
* 有声书 (2.51%)
* 评论 (2.48%)

```
@inproceedings{zhang2022wenetspeech,
  title={WenetSpeech: A 10000+ Hours Multi-domain Mandarin Corpus for Speech Recognition},
  author={Zhang, Binbin and Lv, Hang and Guo, Pengcheng and Shao, Qijie and Yang, Chao and Xie, Lei and Xu, Xin and Bu, Hui and Chen, Xiaoyu and Zeng, Chenchen and Wu, Di and Peng, Zhendong},
  booktitle={International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year={2022},
  organization={IEEE}
}
```

## MAGICDATA Mandarin Chinese Conversational Speech Corpus

{% embed url="https://www.openslr.org/123/" %}

The contents and the corresponding descriptions of the corpus include:

* The corpus contains **180 hours** of speech data, which is all mobile recorded data.
* **663 speakers** from different accent areas in China are invited to participate in the recording.
* All speech data are manually labeled and the transcriptions are proofed by professional inspectors to ensure the labeling quality.
* Recordings are conducted in a quiet indoor environment.
* The database is divided into training set, validation set, and testing set in a ratio of 15: 1: 2.
* Detail information such as speaker and topic information and is preserved in the metadata file.
* The topic of dialogues is diversified, ranging from science and technology to ordinary life.\
  \
  语料库的内容及相应描述如下：
* 该语料库包含180小时的语音数据，全部为手机录制的数据。
* 邀请了来自中国不同口音地区的663位发言者参与录制。
* 所有语音数据均经过人工标注，并由专业检查员校对，以确保标注质量。
* 录音在安静的室内环境中进行。
* 数据库按照15:1:2的比例划分为训练集、验证集和测试集。
* 详细信息，如发言者和话题信息，保存在元数据文件中。
* 对话的话题多样化，涵盖从科学技术到日常生活的各个方面。

```
@article{yang2022open,
  title={Open Source MagicData-RAMC: A Rich Annotated Mandarin Conversational (RAMC) Speech Dataset},
  author={Yang, Zehui and Chen, Yifan and Luo, Lei and Yang, Runyan and Ye, Lingxuan and Cheng, Gaofeng and Xu, Ji and Jin, Yaohui and Zhang, Qingqing and Zhang, Pengyuan and others},
  journal={arXiv preprint arXiv:2203.16844},
  year={2022}
}
```

## SHALCAS22A

{% embed url="https://www.openslr.org/138/" %}

SHALCAS22A is a 1-channel Chinese Mandarin speech corpus by Shanghai Acoustics Laboratory, CAS and Wuxi Sandu Intelligent Technology Co., Ltd. It was collected over a Hi-Fi microphone in a quiet environment. The corpus contains 14,580 utterances from 60 speakers. Each speaker has 243 utterances.

SHALCAS22A是由中国科学院上海声学研究所和无锡三度智能科技有限公司合作制作的一种单通道的中文普通话语音语料库。它是通过高保真麦克风在安静环境中收集而来的。该语料库包含来自60位发言者的14,580个话语。每位发言者有243个话语。

> SHALCAS22A, a free Chinese Mandarin corpus by Shanghai Acoustics Laboratory, CAS and Wuxi Sandu Intelligent Technology Co., Ltd., 2022

## **LATIC**

{% embed url="https://ieee-dataport.org/open-access/latic-non-native-pre-labelled-mandarin-chinese-validation-corpus-automatic-speech#files" %}

There are 4 participants in the dataset, which includes two males and two females, and their age varies from 19 to 30. The average age is about 24. The dataset contains 4 hours of speech files, 2,579 audio samples, and the average length is about 9-10secs.

\
数据集中有4个参与者，包括两名男性和两名女性，他们的年龄在19到30岁之间变化。平均年龄约为24岁。数据集包含4小时的语音文件，2,579个音频样本，平均长度约为9到10秒。

```
@data{mqtj-qh10-21,
doi = {10.21227/mqtj-qh10},
url = {https://dx.doi.org/10.21227/mqtj-qh10},
author = {ZHANG, XIAO},
publisher = {IEEE Dataport},
title = {LATIC: A Non-native Pre-labelled Mandarin Chinese Validation Corpus for Automatic Speech Scoring and Evaluation Task},
year = {2021} 
}
```
