# question_answering_model
This is a python file in which you can get the code of  question-answering model of machine learning.This code will help you to easily accomplish your model. 
In first part, we imported library named tranformers by giving commamnd- "pip install transformers".
Then from transformers we imported function named as pipeline by giving the command;  " from transformers import pipeline".
then we used model variable to use pipeline function and assigning the task of the "question-answering" then it will take some time to download some files.
then we can give any paragraph or content using the variable "context" and run it. 
then use a variable to put your question in variable question and also give context=context as an argument and command to give the answer; ans=model(question="your_question",context=context)
print(ans)
this code will easily help you to create a model of Ml. you can change the context and the questions anytime.

