# (MBTI) Myers-Briggs Personality Type Dataset

# 数据来源

https://www.kaggle.com/datasets/datasnaek/mbti-type

## 相关code工作
1. 内附数据清洗，分类的代码：
https://www.kaggle.com/code/kimp1995/mbti-classification  
2. capstone-master
该工作中有对mbti_1.csv 进行清洗，并有清洗完的数据，可参考利用。

## Context

The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

- Introversion (I) – Extroversion (E)
- Intuition (N) – Sensing (S)
- Thinking (T) – Feeling (F)
- Judging (J) – Perceiving (P)

[(More can be learned about what these mean here)](http://www.myersbriggs.org/my-mbti-personality-type/mbti-basics/home.htm)

So for example, someone who prefers introversion, intuition, thinking and perceiving would be labelled an INTP in the MBTI system, and there are lots of personality based components that would model or describe this person’s preferences or behaviour based on the label.

It is one of, if not the, the most popular personality test in the world. It is used in businesses, online, for fun, for research and lots more. A simple google search reveals all of the different ways the test has been used over time. It’s safe to say that this test is still very relevant in the world in terms of its use.

From scientific or psychological perspective it is based on the work done on [cognitive functions](http://www.cognitiveprocesses.com/Cognitive-Functions/) by Carl Jung i.e. Jungian Typology. This was a model of 8 distinct functions, thought processes or ways of thinking that were suggested to be present in the mind. Later this work was transformed into several different personality systems to make it more accessible, the most popular of which is of course the MBTI.

Recently, its use/validity has come into question because of unreliability in experiments surrounding it, among other reasons. But it is still clung to as being a very useful tool in a lot of areas, and the purpose of this dataset is to help see if any patterns can be detected in specific types and their style of writing, which overall explores the validity of the test in analysing, predicting or categorising behaviour.

## Content

This dataset contains over 8600 rows of data, on each row is a person’s:

- Type (This persons 4 letter MBTI code/type)
- A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))

## Acknowledgements

This data was collected through the [PersonalityCafe forum](http://personalitycafe.com/forum/), as it provides a large selection of people and their MBTI personality type, as well as what they have written.

## Inspiration

Some basic uses could include:

- Use machine learning to evaluate the MBTIs validity and ability to predict language styles and behaviour online.
- Production of a machine learning algorithm that can attempt to determine a person’s personality type based on some text they have written.
