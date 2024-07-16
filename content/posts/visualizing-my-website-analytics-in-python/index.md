+++
title = "Visualizing my Website Analytics with Python"
date = 2024-07-16T15:30:00+05:30
draft = false
description = "A visual overview of my website traffic"
+++
I recently completed a mini course on data science and machine learning using Python. I learnt how to manipulate, clean, and analyze data using Python libraries such as [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/) and [NumPy](https://numpy.org/) and various machine learning algorithms.

A while back, I wrote about [GoatCounter](https://vachan.me/posts/goat-counter/), a free and open source web analytics service that I use to track traffic on my website. GoatCounter lets you export the data as .csv file and I decided to explore the data.

I had to clean the dataset and remove null values and disregard visits by bots. The csv format used by GoatCounter is explained [here](https://www.goatcounter.com/help/export#csv-format-72).

Here are the results:

{{<figure src = "posts2.png" caption = "Top 10 posts with the most visits.">}}
{{<figure src = "os.png" caption = "Operating System Popularity">}}
In the above pie chart, Android is the clear winner because the majority of people who visit my website are from India. Windows is the runner up.
{{<figure src = "browser.png" caption = "Browser Popularity">}}
{{<figure src = "browservsos.png" caption = "Popularity of browsers used on various operating systems.">}}

GoatCounter does already give good visualizations of the data but I decided to do it on my own just for applying what I have learned from the course. The graphs below are really basic but the whole process of using pandas and matplotlib to generate these graphs was interesting.

This is day 34 of [#100DaystoOffload](https://100daystooffload.com)
