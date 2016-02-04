# disease_name_recognition_through_rnn

This directory contain code and data for disease mention recogntion in text through deep neural network and recurrent neural network. Dataset used here is NCBI disease corpus which is publicly available at "http://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/". The code used here is a modified version of the code provided by Matthieu Labeau in his work "Non-lexical neural architecture for fine-grained POS Tagging".

binary_data: All input file for disease mention recognition
class_data: All input file for disease mention recogntion with class
word2vec: All word vectors we learned throug CBOW, Skip-gram and GloVe in pubmed corpus. Here each line contain vectors for correspondin word in vocab file. 
results and multi_results: results obtain by disease mention and disease class recognition respectivly


Software Requirement:
Theano
Numpy
Cuda 6 (Optional)

PS: If you have GPU in machine it will run automatically in GPU without changing anything in code. 

