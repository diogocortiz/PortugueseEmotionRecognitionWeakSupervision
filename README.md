# PortugueseEmotionRecognitionWeakSupervision
A Weakly Supervised Dataset of Fine-Grained Emotions in Portuguese including 28 categories

Affective Computing is the study of how computers can recognize, interpret and simulate human affects. Sentiment Analysis is a common task in NLP related to this topic, but it focuses only on emotion valence (positive, negative, neutral). An emerging approach in NLP is Emotion Recognition, which relies on fined-grained classification. This research describes an approach to create a lexical-based weak supervised corpus for fine-grained emotion in Portuguese. We evaluate our dataset by fine-tuning a transformer-based language model (BERT) and validating it on a Golden Standard annotated validation set. Our results (F1-score= .64) suggest lexical-based weak supervision as an appropriate strategy for initial work in low resources environment.

This dataset is described in the paper "A Weakly Supervised Dataset of Fine-Grained Emotions in Portuguese", published at the Symposium in Information and Human Language Technology (STIL 2021).

Please note that in respect of twitter's terms of use, we only make available the Tweet_ID associated with each annotated category.
To collect the sentence text, the researcher must collect it directly from the Twitter API using the Tweet ID list.
