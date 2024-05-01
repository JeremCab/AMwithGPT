# Argument Mining with GPT: A Comparison between In-Context Learning and Fine-Tuning

Paper submitted to ESANN 2024

## Abstract
Argument Mining (AM) is a challenging task in NLP which focuses on extracting the complex argumentative structure of a text. Argument Type Classification (ATC) is an essential sub- task of AM. Besides, recent developments have emphasized the ability of LLMs to exhibit impressive emergent capabilities via in-context learning (ICL), which obviates the need for fine-tuning. Our work addresses the ATC task with GPT from both ICL and fine-tuning perspectives. We present a two-step ICL approach, combining few-shot learning via kNN-based examples selection and majority vote-based ensembling. For this ICL approach, we introduce two prompting strategies: the single prediction and the all-in-one predictions, where argument components are classified either one by one or all at once, respectively. We also introduce a fine-tuning technique where additional contextual and structural features are injected into the prompts in various configurations. The fine-tuning free ICL approach for GPT outperforms fine-tuned approaches for BERT-like models. The fine-tuning technique for GPT competes with the state-of-the-art results for the ATC task.


## In-context learning

The notebooks for the experiments related to the **in-context learning (ICL) approach** are in the folder `InContextLearning/`.


## Fine-tuning 

The notebooks for the experiments related to the **fine-tuning (FT) approach** are in the folder `FineTuning/`.
