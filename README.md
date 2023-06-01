# How to Control Sentiment in Text Generation: A Survey of the State-of-the-Art in Sentiment-Control Techniques

A list of papers on Sentiment-Controlled Text Generation including links to papers, categorisation scheme and annotations of each paper.
[Here](https://docs.google.com/spreadsheets/d/18mYRGZf8NaLuckEER4fQ7RGWyEy-hI6P9lFjcYocSg8/edit?usp=sharing) you can find all the annotations we did on the analysed papers.

![sentiment-ctg categorisation scheme image](https://github.com/michelalorandi/sentimentCTG-survey/blob/main/sentiment_ctg_categorisation.png?raw=true)

# Contents
- [Surveys](#surveys)
- [Sentiment-Controlled Text Generation](#sentiment-controlled-text-generation)
  - [**By control implementation**](#by-control-implementation)
    - [Complete Training](#complete-training)
    - [Model Fine-Tuning](#model-fine-tuning)
    - [Disentanglement](#disentanglement)
    - [Modification of Token Distribution](#modification-of-token-distribution)
    - [Hybrid](#hybrid)
  - [**By task**](#by-task)
    - [Free text](#free-text)
    - [Story Generation](#story-generation)
    - [Topic to Essay Generation](#topic-to-essay-generation)
    - [Conversational Agent](#conversational-agent)
  - [**By control**](#by-control)
    - [Single](#single)
    - [Multiple](#multiple)
  - [**By Control Attributes**](#by-control-attributes)
    - [Polarity Control](#polarity-control)
      - [Sentiment](#sentiment)
      - [Toxicity](#toxicity)
    - [Content Control](#content-control)
      - [Topic](#topic)
      - [Action](#action)
      - [Character](#character)
      - [Need](#need)
    - [Syntactic Control](#syntactic-control)
      - [Tense](#tense)

# Surveys

Overview of surveys on Controllable Text Generation.

- Exploring Controllable Text Generation Techniques [(Prabhumoye et al., COLING 2020)](https://aclanthology.org/2020.coling-main.1/)
- A Survey of Controllable Text Generation using Transformer-based Pre-trained Language Models [(Zhang et al., 2022)](https://arxiv.org/abs/2201.05337)


# Sentiment-Controlled Text Generation

A list of papers focused on Sentiment-Controlled Text Generation.

## By control implementation

A list of papers categorised by control implementation methods.

### Complete Training
- A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph [(Qiao et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.299/)
- Controlled Text Generation with Adversarial Learning [(Betti et al., INLG 2020)](https://aclanthology.org/2020.inlg-1.5/)
- Psychology-guided Controllable Story Generation [(Xie et al., COLING 2022)](https://aclanthology.org/2022.coling-1.564/)

### Model Fine-Tuning
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)

### Disentanglement
- Attribute Alignment: Controlling Text Generation from Pre-trained Language Models [(Yu et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.194/)

### Modification of Token Distribution
- Plug and play language models: A simple approach to controlled text generation [(Dathathri et al., ICLR 2019)](https://arxiv.org/pdf/1912.02164.pdf)
- Plug-and-Play Conversational Models [(Madotto et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.219/)
- Adapting a Language Model for Controlled Affective Text Generation [(Goswamy et al., COLING 2020)](https://aclanthology.org/2020.coling-main.251/)
- Gradient-based Constrained Sampling from Language Models [(Kumar et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.144/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- BeamR: Beam Reweighing with Attribute Discriminators for Controllable Text Generation [(Landsman et al., Findings 2022)](https://aclanthology.org/2022.findings-aacl.40/)

### Hybrid
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)
- Empathetic and Emotionally Positive Conversation Systems with an Emotion-specific Query-Response Memory [(Tian et al., Findings 2022)](https://aclanthology.org/2022.findings-emnlp.475/)
- DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts [(Liu et al., ACL-IJCNLP 2021)](https://aclanthology.org/2021.acl-long.522/)
- DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation [(Zhang & Song, EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.223/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)
- Multi-Attribute Controlled Text Generation with Contrastive-Generator and External-Discriminator [(Liu et al., COLING 2022)](https://aclanthology.org/2022.coling-1.516/)


## By task
A list of papers categorised by considered task.

### Free text
- Controlled Text Generation with Adversarial Learning [(Betti et al., INLG 2020)](https://aclanthology.org/2020.inlg-1.5/)
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
- Attribute Alignment: Controlling Text Generation from Pre-trained Language Models [(Yu et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.194/)
- Plug and play language models: A simple approach to controlled text generation [(Dathathri et al., ICLR 2019)](https://arxiv.org/pdf/1912.02164.pdf)
- Adapting a Language Model for Controlled Affective Text Generation [(Goswamy et al., COLING 2020)](https://aclanthology.org/2020.coling-main.251/)
- Gradient-based Constrained Sampling from Language Models [(Kumar et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.144/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- BeamR: Beam Reweighing with Attribute Discriminators for Controllable Text Generation [(Landsman et al., Findings 2022)](https://aclanthology.org/2022.findings-aacl.40/)
- DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts [(Liu et al., ACL-IJCNLP 2021)](https://aclanthology.org/2021.acl-long.522/)
- DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation [(Zhang & Song, EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.223/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)
- Multi-Attribute Controlled Text Generation with Contrastive-Generator and External-Discriminator [(Liu et al., COLING 2022)](https://aclanthology.org/2022.coling-1.516/)

### Story Generation
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)

### Topic to Essay Generation
- A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph [(Qiao et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.299/)

### Conversational Agent
- Plug-and-Play Conversational Models [(Madotto et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.219/)
- Empathetic and Emotionally Positive Conversation Systems with an Emotion-specific Query-Response Memory [(Tian et al., Findings 2022)](https://aclanthology.org/2022.findings-emnlp.475/)


## By control
A list of papers categorised by whether a single or multiple attributes are controlled at a time.

### Single
- Controlled Text Generation with Adversarial Learning [(Betti et al., INLG 2020)](https://aclanthology.org/2020.inlg-1.5/)
- Plug-and-Play Conversational Models [(Madotto et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.219/)
- Gradient-based Constrained Sampling from Language Models [(Kumar et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.144/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- BeamR: Beam Reweighing with Attribute Discriminators for Controllable Text Generation [(Landsman et al., Findings 2022)](https://aclanthology.org/2022.findings-aacl.40/)
- Empathetic and Emotionally Positive Conversation Systems with an Emotion-specific Query-Response Memory [(Tian et al., Findings 2022)](https://aclanthology.org/2022.findings-emnlp.475/)
- DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts [(Liu et al., ACL-IJCNLP 2021)](https://aclanthology.org/2021.acl-long.522/)
- DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation [(Zhang & Song, EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.223/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)

### Multiple
- A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph [(Qiao et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.299/)
- Psychology-guided Controllable Story Generation [(Xie et al., COLING 2022)](https://aclanthology.org/2022.coling-1.564/)
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
- Attribute Alignment: Controlling Text Generation from Pre-trained Language Models [(Yu et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.194/)
- Plug and play language models: A simple approach to controlled text generation [(Dathathri et al., ICLR 2019)](https://arxiv.org/pdf/1912.02164.pdf)
- Adapting a Language Model for Controlled Affective Text Generation [(Goswamy et al., COLING 2020)](https://aclanthology.org/2020.coling-main.251/)
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)
- Multi-Attribute Controlled Text Generation with Contrastive-Generator and External-Discriminator [(Liu et al., COLING 2022)](https://aclanthology.org/2022.coling-1.516/)


## By Control Attributes
A list of papers categorised by considered control attributes.

### Polarity Control

#### Sentiment
- A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph [(Qiao et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.299/)
- Controlled Text Generation with Adversarial Learning [(Betti et al., INLG 2020)](https://aclanthology.org/2020.inlg-1.5/)
- Psychology-guided Controllable Story Generation [(Xie et al., COLING 2022)](https://aclanthology.org/2022.coling-1.564/)
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
- Attribute Alignment: Controlling Text Generation from Pre-trained Language Models [(Yu et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.194/)
- Plug and play language models: A simple approach to controlled text generation [(Dathathri et al., ICLR 2019)](https://arxiv.org/pdf/1912.02164.pdf)
- Plug-and-Play Conversational Models [(Madotto et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.219/)
- Adapting a Language Model for Controlled Affective Text Generation [(Goswamy et al., COLING 2020)](https://aclanthology.org/2020.coling-main.251/)
- Gradient-based Constrained Sampling from Language Models [(Kumar et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.144/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- BeamR: Beam Reweighing with Attribute Discriminators for Controllable Text Generation [(Landsman et al., Findings 2022)](https://aclanthology.org/2022.findings-aacl.40/)
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)
- Empathetic and Emotionally Positive Conversation Systems with an Emotion-specific Query-Response Memory [(Tian et al., Findings 2022)](https://aclanthology.org/2022.findings-emnlp.475/)
- DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts [(Liu et al., ACL-IJCNLP 2021)](https://aclanthology.org/2021.acl-long.522/)
- DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation [(Zhang & Song, EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.223/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)
- Multi-Attribute Controlled Text Generation with Contrastive-Generator and External-Discriminator [(Liu et al., COLING 2022)](https://aclanthology.org/2022.coling-1.516/)

#### Toxicity
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Gradient-based Constrained Sampling from Language Models [(Kumar et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.144/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts [(Liu et al., ACL-IJCNLP 2021)](https://aclanthology.org/2021.acl-long.522/)
- DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation [(Zhang & Song, EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.223/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)

### Content Control 

#### Topic
- A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph [(Qiao et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.299/)
- Controlled Text Generation with Adversarial Learning [(Betti et al., INLG 2020)](https://aclanthology.org/2020.inlg-1.5/)
- Controllable Natural Language Generation with Contrastive Prefixes [(Qian et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.229/)
- A Distributional Lens for Multi-Aspect Controllable Text Generation [(Gu et al., EMNLP 2022)](https://aclanthology.org/2022.emnlp-main.67/)
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
- Attribute Alignment: Controlling Text Generation from Pre-trained Language Models [(Yu et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.194/)
- Plug and play language models: A simple approach to controlled text generation [(Dathathri et al., ICLR 2019)](https://arxiv.org/pdf/1912.02164.pdf)
- Plug-and-Play Conversational Models [(Madotto et al., Findings 2020)](https://aclanthology.org/2020.findings-emnlp.219/)
- Adapting a Language Model for Controlled Affective Text Generation [(Goswamy et al., COLING 2020)](https://aclanthology.org/2020.coling-main.251/)
- Improving Controllable Text Generation with Position-Aware Weighted Decoding [(Gu et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.272/)
- GeDi: Generative Discriminator Guided Sequence Generation [(Krause et al., Findings 2021)](https://aclanthology.org/2021.findings-emnlp.424/)
- Multi-Attribute Controlled Text Generation with Contrastive-Generator and External-Discriminator [(Liu et al., COLING 2022)](https://aclanthology.org/2022.coling-1.516/)

#### Action
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)

#### Character
- Psychology-guided Controllable Story Generation [(Xie et al., COLING 2022)](https://aclanthology.org/2022.coling-1.564/)
- CHAE: Fine-Grained Controllable Story Generation with Characters, Actions and Emotions [(Wang et al., COLING 2022)](https://aclanthology.org/2022.coling-1.559/)

#### Need
- Psychology-guided Controllable Story Generation [(Xie et al., COLING 2022)](https://aclanthology.org/2022.coling-1.564/)

### Syntactic Control

#### Tense
- Controlled Text Generation Using Dictionary Prior in Variational Autoencoders [(Fang et al., Findings 2022)](https://aclanthology.org/2022.findings-acl.10/)
