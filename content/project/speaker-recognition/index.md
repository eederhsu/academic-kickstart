+++
# Project title.
title = "Speaker Identification"

# Date this page was created.
date = 2015-11-30T00:00:00

# Project summary to display on homepage.
summary = "Using FFT and signal processing techniques to identify speakers."

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
This research focuses on speaker recognition, which has a variety of applications – automatic identification of the electronic device’s owner or different speakers in a conference. Collecting 20 training samples, the authors have used FFT to analyze the spectra of two different speakers and found several features in it, such as the number of the peaks that are larger than the mean amplitude. After establishing five criteria, the researchers successfully identified speakers from 10 input test data. What remains to be deeper understood includes the implementation of machine learning algorithms and the analysis of the signals in time domain.

***Results***: Achieved 100% accuracy on identifying two speakers by performing FFT to the speech signals and utilized 5 differences between the speakers such as the number of peaks in the spectrum