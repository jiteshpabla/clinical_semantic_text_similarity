# clinical_semantic_text_similarity

### Task
The task is about finding an automated method to measure the degree of semantic equivalence between two samples of biomedical texts. In our case, the biomedical texts contain just one sentence from clinical notes. The similarity is measured by real numbers from 0 (completely dissimilar) to 5 (complete semantic equivalence). Performance of the method is measured by the Pearson correlation coefficient between the predicted similarity scores and reference human judgments (two clinical experts were asked to manually annotate every text pair).

### File description
- features_processing: Implementation of Token-based and Embedding-based (Word2Vec) features; Combination of all features and final results.
- bert_features_process: Implementation of BERT based features.
- bert_analysis: The results from the features of each BERT model (separately).
- X_fintune_X_sentence_transformers: Finetuning BERT models.

### More details
Please read the [project report](https://github.com/jiteshpabla/clinical_semantic_text_similarity/blob/master/project_report.pdf) for results and more detailed description.

**Note**: The dataset for this project is not open source. The code will still work for any text similarity dataset.
