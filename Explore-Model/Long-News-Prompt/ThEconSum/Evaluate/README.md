## CSV Files
ALL csv files involves evaluating summaries from the ThEconSum dataset using two popular evaluation metrics: BERT Score and ROUGE Score. 
The dataset consists of economic-related summaries, and 50 rows were randomly sampled.

## Evaluation Metrics
The evaluation is performed using two well-known metrics in Natural Language Processing (NLP):

#### 1. BERT Score:
  This metric leverages pre-trained BERT embeddings to compute similarity between the reference and generated summaries at a token level.
BERT Score is effective in capturing semantic meaning and context, making it useful for evaluating the quality of summaries beyond mere word overlap.

#### 2. ROUGE Score:
  The ROUGE metric is used for measuring the overlap between n-grams in the generated and reference summaries.
In this project, we use ROUGE-N and ROUGE-L:<br>
ROUGE-N: Measures n-gram overlap (e.g., unigram, bigram).<br>
ROUGE-L: Measures the longest common subsequence (LCS) between the generated and reference summaries.
