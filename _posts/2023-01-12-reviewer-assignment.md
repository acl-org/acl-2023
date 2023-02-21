---
title: "Paper-reviewer matching at ACL 2023: types of contributions and track sub-areas"
author: program-chairs
author_profile: true
tags:
  announcement
  peer-review
categories:
  blog
---

One of the big issues that authors often complain about at NLP conferences is "meh" reviews: the reviewer does not really find any significant problems with methodology or execution of the paper, but the overall recommendation is middling. This can be a symptom of paper-reviewer mismatch: the reviewer just is not sufficiently interested in the overall topic or approach, and hence no matter how good the paper is, it would not elicit much enthusiasm. In a recent [survey](https://aclanthology.org/2022.naacl-main.354) of authors, reviewers and area chairs about their prior experience at NLP venues, many reviewers stated that "_the area match was right, but..._

* _the subject of the paper was not interesting to me (e.g. I would prefer another NLP task, model, or data)"_ (54%)
* _the paper was not asking a research question that would be interesting for me"_ (45%)

At the same time, over 27% of the author respondents reported that they had experience of reviews where the reviewer was not interested in the subject of the paper.

While most recent * ACL conferences and ARR work with some version of an automated paper-reviewer matching system that computes affinity scores between the abstract and title of the submission and the candidate reviewer, based on their publication history. Interestingly, the same survey found that such automated score was overall the lowest ranking factor in paper-reviewer matching, according to the pool of authors, reviewers and area chairs.

A traditional alternative to affinity scores, that also addresses the issue with reviewer interest, is bidding: the reviewers explicitly say which papers they would be interested in. But this process is rather laborious: for a big track, a reviewer would need to indicate their interest for hundreds of papers. It also opens up the possibility of collusion rings.

To address this problem, ACL 2023 will experiment with a keywords-based workflow that explicitly targets two dimensions of submissions: contribution types and track sub-areas.


## Contribution types

This category aims to describe what kind of work is performed in this paper. Our classification is based on [COLING 2018 paper types](http://coling2018.org/paper-types/), with some modifications:

* Computationally-aided linguistic analysis (of either models or data resources)
* NLP engineering experiment (most papers proposing methods to improve state-of-the-art)
* Approaches for data- and compute efficiency
* Reproduction study
* New data resources, particularly for low-resource languages
* Position papers
* Surveys
* Theory
* Publicly available software and pre-trained models

The contribution types cross-cut tracks, and we hope they would help to decrease the amount of cases where the reviewer just [fundamentally does not recognize a certain type of work](https://rbawden.wordpress.com/2019/07/19/one-paper-nine-reviews/) and hence scores it down, or has unreasonable expectations (e.g. experimental results in a position paper). Another goal of the contribution types mechanism is to help to create paper-reviewer assignments that consider different aspects of the paper. This does not always happen in the standard track-based assignment process. 

For example, the category of compute/data-efficiency creates a de-facto equivalent of efficiency track spread across all tracks. Usually tracks are the only way to organize a group of reviewers with interest in a particular topic, but when that topic can be combined with other topics that also require specialized expertise, it becomes impossible to find good reviewer matches only within that track. For example, a paper proposing a QA system where the main contribution is not improvements in accuracy, but in efficiency, could be at a disadvantage in QA track - but a dedicated efficiency track might lack reviewers with expertise in QA. 

If the contribution types mechanism is successful at ACL 2023, we hope that it will become more widely adopted in the future to ensure more fair reviews for different kinds of contributions within all tracks. It could also be further extended, e.g. to encourage the cross-track methods aiming for robustness, cognitive plausibility etc.

## **Track sub-area(s)**

Each track at ACL 2023 has an associated set of keywords describing its potential sub-areas. These lists are not intended to be exclusive; they only describe the biggest expected sub-areas, and hopefully provide a better idea of the kind of work that the track is inviting. In our case they were provided by the SACs of all tracks independently, and future conferences may wish to take a more top-down approach to editing this list.

* **Computational Social Science and Cultural Analytics**: human behavior analysis; stance detection; frame detection and analysis; hate-speech detection; misinformation detection and analysis; psycho-demographic trait prediction; emotion detection and analysis; emoji prediction and analysis; language/cultural bias analysis; human-computer interaction; sociolinguistics; NLP tools for social analysis; quantitative analyses of news and/or social media;
* **Dialogue and Interactive Systems**: spoken dialogue systems; evaluation and metrics; task-oriented; human-in-the-loop; bias/toxicity; factuality; retrieval; knowledge augmented; commonsense reasoning; interactive storytelling; embodied agents; applications; multi-modal dialogue systems; grounded dialog; multilingual / low resource; dialogue state tracking; conversational modeling;
* **Discourse and Pragmatics**: anaphora resolution; coreference resolution; bridging resolution; coherence; cohesion; discourse relations; discourse parsing; dialogue; conversation; discourse and multilinguality; argument mining; communication;
* **Ethics and NLP**: data ethics; model bias/fairness evaluation; model bias/unfairness mitigation; human factors in NLP; participatory/community-based NLP; ethical considerations in NLP applications; transparency; policy and governance; reflections and critiques;
* **Generation**: human evaluation; automatic evaluation; multilingualism; efficient models; few-shot generation; analysis; domain adaptation; data-to-text generation; text-to-text generation; inference methods; model architectures; retrieval-augmented generation; interactive and collaborative generation;
* **Information Extraction**: named entity recognition and relation extraction; event extraction; open information extraction; knowledge base construction; entity linking/disambiguation; document-level extraction; multilingual extraction; zero/few-shot extraction;
* **Information Retrieval and Text Mining**: passage retrieval; dense retrieval; document representation; hashing; re-ranking; pre-training; contrastive learning;
* **Interpretability and Analysis of Models for NLP**: adversarial attacks/examples/training; calibration/uncertainty; counterfactual/contrastive explanations; data influence; data shortcuts/artifacts; explanation faithfulness; feature attribution; free-text/natural language explanations; hardness of samples; hierarchical & concept explanations; human-subject application-grounded evaluations; knowledge tracing/discovering/inducing; probing; robustness; topic modeling;
* **Language Grounding to Vision, Robotics and Beyond**: Vision Language Navigation; Cross-modal Pretraining; Image Text Matching; Cross-modal content generation; Vision Question Answering; cross-modal application; cross-modal information extraction; cross-modal machine translation;
* **Large Language Models**: pre-training; prompting; scaling; sparse models; retrieval-augmented models; ethics; interpretability/analysis; continual learning; security and privacy; applications; robustness; fine-tuning;
* **Linguistic Diversity**: less-resourced languages; endangered languages; indigenous languages; minoritized languages; language documentation; resources for less-resourced languages; software and tools;
* **Linguistic Theories, Cognitive Modeling, and Psycholinguistics**: Linguistic Theories; Cognitive Modeling; Computational Psycholinguistics;
* **Machine Learning for NLP**: Graph-based methods; Knowledge-augmented methods; Multi-task learning; Self-supervised learning; Contrastive learning; Generative models; Data augmentation; Word embeddings; Structured prediction; Transfer learning / domain adaptation; Representation learning; Generalization; Model compression methods; Parameter-efficient finetuning; Few-shot learning; Reinforcement learning; Optimization methods; Continual learning; Adversarial training; Meta learning; Causality; Graphical models; Human-in-the-loop / Active learning;
* **Machine Translation**: Automatic Evaluation; Biases; Domain Adaptation; Efficient Inference for MT; Efficient MT Training; Few-shot/Zero-shot MT; Human Evaluation; Interactive MT; MT deployment and maintainence; MT theory; Modelling; Multilingual MT; Multimodality; Online Adaptation for MT; Parallel Decoding/Non-autoregressive MT; Pre-training for MT; Scaling; Speech Translation; Switch-code Translation; Vocabulary Learning;
* **Multilingualism and Cross-Lingual NLP**: code-switching; mixed language; multilingualism; language contact; language change; linguistic variation; cross-lingual transfer; mutlilingual representations; multilingual pre-training; multilingual benchmarks; multilingual evaluation; dialects and language varieties;
* **NLP Applications**: educational applications, GEC, essay scoring; hate speech detection; multimodal applications; code generation and understanding; fact checking, rumour/misinformation detection; healthcare applications, clincial NLP; financial/business NLP; legal NLP; mathematical NLP; security/privacy; historical NLP; knowledge graphs;
* **Phonology, Morphology, and Word Segmentation**: morphological inflection; paradigm induction; morphological segmentation; subword representations; chinese segmentation; lemmatization; finite-state morphology; morphological analysis; phonology; grapheme-to-phoneme conversion; pronunciation modelling;
* **Question Answering**: commonsense QA; reading comprehension; logical reasoning; multimodal QA; knowledge base QA; semantic parsing; multihop QA; biomedical QA; multilingual QA; interpretability; generalization; reasoning; conversational QA; few-shot QA; math QA; table QA; open-domain QA; question generation;
* **Resources and Evaluation**: corpus creation; benchmarking; language resources; multilingual corpora; lexicon creation; automatic creation and evaluation of language resources; NLP datasets; automatic evaluation of datasets; evaluation methodologies; evaluation; datasets for low resource languages; metrics; reproducibility; statistical testing for evaluation;
* **Semantics: Lexical**: polysemy; lexical relationships; textual entailment; compositionality; multi-word expressions; paraphrasing; metaphor; lexical semantic change; word embeddings; cognition; lexical resources; sentiment analysis; multilinguality; interpretability; probing;
* **Semantics: Sentence-level Semantics, Textual Inference, and Other Areas**: paraphrase recognition; textual entailment; natural language inference; reasoning; semantic textual similarity; phrase/sentence embedding; paraphrase generation; text simplification; word/phrase alignment;
* **Sentiment Analysis, Stylistic Analysis, and Argument Mining**: argument mining; stance detection; argument quality assessment; rhetoric and framing; argument schemes and reasoning; argument generation; style analysis; style generation; applications;
* **Speech and Multimodality**: Automatic Speech Recognition; Spoken Language Understanding; Spoken Language Translation; Spoken Language Grounding; Speech and Vision; QA via Spoken Queries; Spoken Dialog; Video Processing; Speech Technologies; Multimodality;
* **Summarization**: extractive summarisation; abstractive summarisation; multimodal summarization; multilingual summarisation; conversational summarization; query-focused summarization; multi-document summarization; long-form summarization; sentence compression; few-shot summarisation; architectures; evaluation; factuality;
* **Syntax: Tagging, Chunking and Parsing**: Chunking, Shallow-parsing; Part-of-speech tagging; Dependency parsing; Constituency parsing; Deep Syntax Parsing; Semantic Parsing; Syntax-to-semantic interface; Optimized Annotations or data set for Morpho-Syntax related tasks; Parsing Algorithms (symbolic, theoretical results); Grammar and knowledge-based approaches; Multi-task approaches (Large definition); Massively multilingual oriented approaches; Low-resources languages pos tagging, parsing and related tasks; Morphologically-rich languages pos tagging, parsing and related tasks;
* **Theme Track: Reality Check**: right for the wrong reasons; lessons from deployment; (non-)generalizability; (non-)reproducibility; evaluation; methodology; negative results; AI hype & expectations; science-vs-engineering; lessons from other fields; forgotten lessons

## How it will work

Our paper-reviewer matching setup includes the following stages:

1. **sub-area keywords collection:** the senior area chairs of all tracks consider the potential keywords for their tracks. We ask them to come up with no more than 10-15 keywords to describe the sub-areas in which they expect the most submissions in the coming conference, based on their knowledge of the area. While each track can have a lot more potential sub-areas, the goal is only to catch the biggest/most frequent potential sub-areas, which would help to characterize the bulk of the submissions. The more niche submissions would be handled differently.
2. **reviewer recruitment:** at sign-up, reviewers indicate not only which tracks they would like to review for, but also which sub-areas of those tracks they have expertise and interest in. Additionally, they specify the types of contributions they are interested in.
3. **paper submission:** at abstract submission, the authors specify the type of contribution(s) of their paper and the appropriate subarea(s) of their preferred track. If none of the sub-areas is a good fit, the authors can select "other" and specify their own keywords. If several tracks have the same keywords, we leave it up to the authors to determine what is their main contribution, and which track is more likely to have the reviewers who are interested in that. For example, "stance detection" is both in Computational Social Science track and in Sentiment Analysis track. If the authors situate the contribution within a broader argument mining, they may choose "Sentiment Analysis" track. In contrast, if the contribution is better explained as a finding for computational social science that uses stance detection methodology, they may prefer "Computational Social Science" track.
4. **automated paper-reviewer matching:** we create assignments that attempt to maximize matches along the dimensions of contribution types and track sub-areas. The assignments also take into account reviewer quotas, conflicts of interest, and reviewer seniority (to try to ensure at least one senior reviewer per paper).
5. **manual adjustments:** we provide the resulting matches to the senior area chairs, together with the keywords that serve as rationales for the match, and the interests and profiles of the reviewers who still have quotas. The senior area chairs work with area chairs to check and correct assignments as needed.

The keywords will also be visible to area chairs during the rebuttals, post-rebuttal discussion and meta-reviews. We hope that they would help the chairs to appropriately weigh the reviewer criticisms based on the self-declared interests and expertise.

To see whether all this had the desired effect, we will further ask the chairs, authors and reviewers to rate their experience with this matching system, and consent to publication of the analysis of this experiment (statistics only, not individual review data). If the experiment is successful, we will release our forms, guidelines and matching scripts, to help the organizers of future conferences.
