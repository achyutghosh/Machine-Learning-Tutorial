This repository contains my code following contents
# Contents

- [Getting started](#getting-started)
- [Templates](#templates)
- [Notes](#notes)
- [Python vs R](#python-vs-r)
- [Thoughts on the course](#thoughts-on-the-course)
- [About](#about)

## Getting started

To best make use of this repository, click on the "Clone or download" button towards the top-right of the page. Then, click "Download Zip". Use your preferred software to unzip it, and you're ready to go.

## Templates

In the Udemy course, Hadelin writes templates that make applying certain models very straightforward. I have made multiple improvements, and you should just be able to copy and paste segments into your project (though of course you should make every effort to *understand* before you copy paste).

In the [templates](https://github.com/robertmartin8/udemyML/tree/master/templates) folder, you will find:

- regression templates (python and R)
- classification templates (python and R)
- a cross validation script to compare multiple models (python)
- plot templates, which contain the code to generate a variety of interesting plots.

## Notes

At one stage I was going to write notes for every topic on the Udemy course, but I stopped after a while because I realised that the course was more focused on application than theory. In the [notes](https://github.com/robertmartin8/udemyML/tree/master/notes) folder, there are notes on preprocessing and multiple regression (the latter of which is nicely typed in LaTeX).

## Python vs R

Many people who want to know more about machine learning struggle to choose between python and R. I personally believe that python is a better choice, particularly because it is easy to integrate your machine learning model with a wide range of other systems (e.g a web app), and because of the unified machine learning interface provided by `scikit-learn`. Take a look in the templates to judge for yourself.

I have included a full discussion in this repository, [`python_vs_R.md`](https://github.com/robertmartin8/udemyML/blob/master/python_vs_R.md), which includes comments on the ease/quality of the implementation of various algorithms in each language.

## Thoughts on the course

The Udemy ML course is one of those courses that advertises its lack of mathematics as if it were a good thing. While there is no doubt that the course gives you the very practical ability to formulaically solve a data problem, if your dataset deviates from the standard, you may have trouble.

Basically, I would have liked to see some more theory, because often this gives you a much better idea of what the various parameters do, and how to improve your results. Hadelin is clearly an expert on the subject, and it would be great to tap into some of his real life experience.

Additionally, what I don't understand is where they draw the line between writing code from scratch and using the available libraries. The course makes massive use of the standard libraries most of the time (which I have no objection to), but then sometimes it neglects to use a built-in which would save many lines of code. For example, the backwards-elimination method that we implemented from scratch in R can be replaced by the built in `step()` function. Literally 6 characters.

While I am complaining quite a lot, this course sparked/renewed my interest in machine learning, and has given me the motivation to go and learn the theory, either from a textbook like Elements of Statistical Learning, or from a more rigorous course like Andrew Ng's Machine Learning on Coursera, which I had previously started, but had given up on.

In all fairness, the course never claims to go be a super detailed exploration – it is a great overall introduction (with heavy emphasis on practicality), and it can definitely form a springboard to an education in ML.

## About

This project is available for use, modification etc as discussed under the MIT License.

For more content like this, check out [reasonabledeviations.science](https://reasonabledeviations.science).
"# Machine-Learning-Tutorial" 
