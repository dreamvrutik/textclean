# textclean

Following is code example :
from textclean import process
sentences=["Hello world example 1 , true that.","Sentence number 2 it is for example" , "This is sentence number 3 and the last one"]
a=process
sent=a.simpleForm(sentences,False)
print(sent)
vocab=a.getVocab(sent)
print(vocab)
vecs=a.getSentenceasVectors(sent,vocab)
print(vecs)
