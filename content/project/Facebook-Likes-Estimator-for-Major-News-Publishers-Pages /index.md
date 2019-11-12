+++
# Project title.
title = "Facebook Likes Estimator"

# Date this page was created.
date = 2016-11-30T00:00:00

# Project summary to display on homepage.
summary = "Facebook Likes Estimator for Major News Publishers’ Pages."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Machine Learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# #url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

The project seeks to find the factors of the numbers of likes for posts from news publisher’s Facebook page.


Data are collected from the Facebook pages of major news publisher such as: The New York Times, BBC News, The Huffington Post, CNN, TIME, The Wall Street Journal, and The Economist. A parser is built to obtain the raw data, which includes total likes for the page, created time of the post, content of the post and total likes for the post. From the raw data, we extract the following features: published day (Sunday-Saturday, marked as 0-6), published time, length of post (as number of words), and the tone of the post (leveled from 0-6). The last feature is supported by the Stanford CoreNLP Natural Language Processing Toolkit. Other features to be tested are event-specific time coefficient, for example, days before Thanksgiving, and preference of terms, which will utilize Stanford CoreNLP’s ability to identify popular terms from text.


These data will be separated into train and test cases. After obtaining the features, we first used visualize method such as histogram and bar plot to gain insight into the data. Finally, applied different mining techniques, for example, decision tree, to clarify the relationship between features and like counts.


In our result, we suggest a better post consist of only a few sharp sentences or a detailed paragraph. The commonly seen emoji icon and hashtag actually have no effect on the post’s popularity. Another trend we found is that post during worktime and workday receives less like.

***Results***: Achieved 95% accuracy in predicting how many likes one post will obtain by machine learning techniques

