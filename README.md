# Telugu-Paraphrase-detection Using Siamese Network

Paraphrasing methods will generate, identify or extract the phrases or sentences that convey the same meaning. In our work, we try to identify a pair of sentences as Paraphrased or Non-paraphrased. The ability to detect similar sentences is an important function for several applications like text summarization, question answering, and plagiarism detection. We have created a dataset using simple Telugu sentences and after paraphrasing them it is manually labelled as Paraphrased pair or non-paraphrased pair respectively. We made use of INLTK for finding the word embedding and a Siamese network for calculating the similarity score between pairs of sentences and different models like LSTM and Bi-LSTM are implemented for obtaining the sentence embedding and made a comparative study between them and came to one best model i.e., Bi-LSTM.



Requirements

generated_embedding_2.txt

Telugu_nlp_dataset_final.xlsx


packages need to be installed

torch

tensorflow

numpy

pandas

keras
