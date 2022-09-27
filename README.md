# A Quick Introduction to Bag of Words and TF-IDF

Have you ever wondered how Machine Learning (ML) deals with text when ML is based on math and statistics? I mean, the text isn't numbers after all... Right? 

Let me introduce you to the** Bag-of-Words (BoW)** model. Aside from its funny-sounding name, a BoW is a critical part of **Natural Language Processing (NLP)** and one of the building blocks of performing Machine Learning on text.

A BoW is simply an *unordered* collection of words and their frequencies (counts).  For example, let's look at the following text:

```text
"I sat on a plane and sat on a chair."

and  chair  on  plane  sat
  1      1   2      1    2
```

**Note**: The tokens (words) have to be `2` or more characters in length.

It's as simple as that. Let's look at how this was computed and what it might look like with a few more sentences, or what we commonly refer to as a **document**. 

Read more here: https://www.dataknowsall.com/bowtfidf.html
