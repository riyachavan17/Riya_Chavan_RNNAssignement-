# Riya_Chavan_RNNAssignement-
1 . Dataset Creation
Creates a synthetic dataset of 10 labeled educational sentences.
Labels include: Math, Science, History.
2. Text Preprocessing
Uses Tokenizer to tokenize the text.
Applies pad_sequences for uniform input length.
Encodes class labels for classification.
For text generation:
Tokenizes a long paragraph about the French Revolution.
Creates n-gram sequences to train a next-word prediction model.
3. Model Building
Two separate models are built using Sequential():
Classification Model:
Embedding → SimpleRNN → Dense(softmax)
Generation Model:
Embedding → SimpleRNN → Dense(softmax)
4. Training and Evaluation
Trains classification model and reports accuracy.
Trains generation model using one-hot encoded targets.
