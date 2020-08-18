Next Word Predict Capstone Project
========================================================
author: Geanderson Esteves dos Santos
date: 11 August, 2020
autosize: true
transition: rotate
class: smaller
css: style.css

Data Science Specialization<br />
Capstone Project<br />

========================================================
# **Objective**

<small>
This presentation highlights the Next Word Predict app
concerning an introduction to the application
UI and aspects of the text prediction
algorithm.

The source code files can be found on GitHub:

<ul>
    <li><a target="_blank" href="https://github.com/gesteves91/milestone-capstone">https://github.com/gesteves91/milestone-capstone</a></li>
</ul>

I recommend checking regularly the source code as I will continually update the app.
</small>

========================================================
# **Shiny Application**

<small>
Next Word Predict is an app that uses a text
prediction algorithm to predict the next word based on
text input by the user.

The application suggests the next word in a sentence
using an n-gram algorithm. An n-gram is a contiguous sequence
of *n* words from a given sequence of text.

The text handled to build the predictive text model came from a
large corpus of blogs, news, and Twitter data. N-grams were
extracted from the corpus and then used to formulate the
predictive text model.

Various systems were explored to improve speed and
accuracy using natural language processing and text mining
techniques.
</small>

========================================================
# **The Predictive Text Model**

<small>
The predictive model was built under a sample of
800,000 lines extracted from the large corpus of blogs,
news and twitter data.

The sample data is tokenized and cleaned using the **tm** package and several regular expressions using the **gsub** function. As
part of the cleaning process the data was converted to
lowercase, removed all non-ASCII characters, URLs,
email addresses, Twitter handles, hashtags, ordinal numbers,
profane words, punctuation, and whitespace. The data was
then split into tokens (n-grams).

As the text is entered by the user, the algorithm iterates
from the longest n-gram (4-gram) to the shortest (2-gram) to
detect a match. The predicted next word is considered using
the longest, most frequent matching n-gram. The algorithm
makes use of a simple back-off strategy.
</small>

========================================================
# **Application User Interface**

<small>
The predicted word is shown when the app
detects that you have finished typing one or more words.
When entering text, wait a few seconds for the
output. Use the slider tool to select up to
three next-word predictions. The top prediction is
shown first. And then, the second and third likely
next words. Click the image below for a larger view
of the user interface.
</small>

<a target="_blank" href="http://www.idevelopment.info/data/DataScience/uploads/next-word-predict-ui-large.png"><img src="images/next-word-predict-ui.png"></a>
