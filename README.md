Mental Health Sentiment Analysis
This project focuses on classifying text into multiple mental health categories, including depression, anxiety, and related conditions. Using transformer-based models and pre-trained embeddings like GloVe, the goal is to predict one of several mental health conditions based on the sentiment expressed in the text.

Dataset
The dataset contains text labeled with the following mental health categories:

Normal: 16,351 examples
Depression: 15,404 examples
Suicidal: 10,653 examples
Anxiety: 3,888 examples
Bipolar: 2,877 examples
Stress: 2,669 examples
Personality Disorder: 1,201 examples
The dataset is imbalanced, with "Normal" and "Depression" being the majority classes.

Approach
Data Preprocessing: Includes text vectorization, tokenization, and cleaning. Data augmentation techniques like translation-based augmentation are used to help balance the classes.
Modeling: Transformer architectures are used with positional embeddings and transformer
Evaluation: Model performance is evaluated using accuracy, confusion matrices, and attention-based visualizations to identify which parts of the text most strongly influence predictions.
