# Papers
This repository contains the papers and blogs I studied during my research work.

# Gender Bias

# Speech

# Low Resource Languages

# Language Modeling
1. FUDGE: Controlled Text Generation With Future Discriminators

   This paper presents a flexible and modular approach for controlled text generation, Future Discriminators for Generation(FUDGE). Given a preexisting model G for generating text from a distribution of interest, FUDGE enables conditioning on a desired attribute a (for example, formality) while requiring access only to G’s output logits. It can easily compose predictors for multiple desired attributes while preserving the original probability distribution over the natural language text. The key distinguishing feature of FUDGE is that it models whether attribute a will be true in the future, rather than in the present. FUDGE achieves strong performance on a wide range of different tasks: poetry couplet completion, topic control, and informal-to-formal machine translation. Additionally, FUDGE can easily compose different attributes in a modular fashion: the meter, rhyme, and end-of-sentence constraints for couplet completion, and the individual words within each
topic bag for topic control.


# Text Classification
My Btech thesis focuses on the identification of sexual harasment victims on Twitter and their portrayal from a computational linguistic perspective. This project is essentially a text classification problem and some models I explored while working on this are:

1. Convolutional Neural Networks for Sentence Classification

   After considerable success with images, CNNs have become increasingly popular in classic NLP tasks like Text Classification.The paper shows a series of experiments with convolutional neural networks built on top of word2vec. Despite little tuning of hyperparameters, a simple CNN with one layer of convolution performs remarkably well.
   
2. Character-level Convolutional Networks for Text Classification

3. Bag of Tricks for Efficient Text Classification

   This paper shows a simple baseline using fasttext that is at par with deep learning methods.

4. Bag of Tricks for Efficient Text Classification

5. An Embarrassingly Simple Approach for Transfer Learning from Pretrained Language Models

   This presents a conceptually simple and effective transfer learning approach that addresses the problem of catastrophic forgetting. It is based on pretraining a LM and transferring its weights to a classifier with a taskspecific layer. The model is trained using a taskspecific functional with an auxiliary LM loss.Performs very well in small dataset oriented text classification tasks, especially Twitter domain.
   
6. Multi-label Categorization of Accounts of Sexism using a Neural Framework

7. Hierarchical Attention Networks for Document Classification
