# AdmitHub AI Coding Exercise

## 1. Text classifier

Use Keras (or Tensorflow) to construct and train an RNN model that takes an input text string and maps it to a given question space.

More specifically, construct your model from the CSV file containing Question and Answer (Q&A) data from Harvard's admissions website as the training data for your model.

This will be the basis for a simple chatbot that maps or classifies an incoming text string to a given Question and consequently allows it to output a given Answer.

*Notes: This Question/Answer dataset only has 215 records, but imagine that this is merely 10% of the total QA data. Refrain from making any specific assumptions about this data*

## 2. Chatbot API

Use a web framework to create a RESTful API for the model from #1 (feel free to use something like Flask or Bottle). It should consume and return JSON.

Instead of returning the question that the given input string was mapped to, return the corresponding answer associated with the question space.
