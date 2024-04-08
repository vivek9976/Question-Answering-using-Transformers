# Question Answering with Transformers

## Introduction:

Welcome to the Question Answering with Transformers project! 
In this project i have implement extractive question answering using pre-trained transformer models, specifically using the Hugging Face Transformers library and the SQuAD dataset.

## About Question Answering
Question answering is a fundamental Natural Language Processing (NLP) task that involves providing accurate responses 
to questions posed in natural language. In the context of this project, I have focued on extractive question answering, where 
given a question and a passage of text, the model is tasked with identifying and extracting the span of text from the passage that best answers the question.


## Example 
Imagine you have a large chunk of text about the International Space Station (ISS). You ask a question about it, such as "When was the first part of the ISS launched?"
our model then analyzes the text and provides you with the answer, which in this case is 1998.

context = "The International Space Station (ISS) is a space station, or a habitable artificial satellite, in low Earth orbit.
Its first component launched into orbit in 1998, and the ISS is now the largest human-made body in low Earth orbit and
can often be seen with the naked eye from Earth. The ISS consists of pressurized modules, external trusses, solar arrays, 
and other components. It orbits Earth at an average altitude of approximately 420 kilometers (260 mi)."

question = "When was the first component of the ISS launched?"

answer = "1998"
