# textclean

Following is code example :<br>
from textpreprocess import process<br>
sentences=["Hello world example 1 , true that.","Sentence number 2 it is for example" , "This is sentence number 3 and the last one"]<br>
a=process<br>
sent=a.simpleForm(sentences,False)<br>
print(sent)<br>
vocab=a.getVocab(sent)<br>
print(vocab)<br>
vecs=a.getSentenceasVectors(sent,vocab)<br>
print(vecs)<br>
