# Text Summarization for Medical Journals

### Overview

This project focuses on developing a text summarization model specifically for medical journals. It leverages advanced Natural Language Processing (NLP) techniques to create concise and informative summaries that medical professionals can use to stay updated on extensive research literature. The primary evaluation metrics include BERTScore and keyword extraction, which assess the effectiveness of the summarization process.

### BERTScore Calculation

To evaluate the quality of generated summaries, we compute BERTScore, which measures the semantic similarity and content overlap between generated summaries and reference summaries (the abstracts of the medical journals). BERTScore is advantageous because it accounts for not just exact word matches but also the contextual embeddings of words, providing a more nuanced understanding of semantic significance.

Results
* Precision: 0.8295
Indicates a high proportion of accurately identified relevant words from the generated summary.

* Recall: 0.7937
Reflects how well the generated summary captures relevant information from the reference text.

* F1 Score: 0.8110
Represents the harmonic mean of precision and recall, showcasing the overall performance of the summarization model in aligning with the reference text. A higher F1 Score indicates good performance in capturing the pertinent information from the source.

### Keyword Extraction
In addition to BERTScore, keyword extraction provides further insights into the relevance and coverage of the generated summaries. This process identifies key ideas or subjects in the document, allowing for an evaluation of how well the generated summary represents the important concepts from the original article.

Results
* Keyword Similarity:
There is a 40% similarity in the top 10 keywords between the generated summary and the reference abstract, suggesting that critical concepts have been effectively captured.

* Keyword Overlap with Original Article:
The model achieved a keyword overlap score of 0.8554, indicating that 85.54% of the keywords from the original article appear in the generated summary. In comparison, the overlap between the original article and the abstract text (reference summary) was 76.99%. This suggests that our model is successful in preserving essential information while generating the summary.
