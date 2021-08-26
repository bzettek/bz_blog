---
layout: post
title:  "Spring 2021 Overview"
date:   2021-08-25 2:50
categories: jekyll update
---
I am a little late on this update, but hey better late than never! I Finally finished up the semester. I definitely made progress in becoming a better engineer this semester!
I will start by talking about one of my favorite projects I've created and then end with my NSA research.

<h3>College Football Attendance Predictor</h3>
Here are the technologies I used:
* Python
* Docker
* Ubuntu
* Flask
<p> </p>
<img src="/assets/footballH.jpg" width="520" height="350" />

For this project, the goal was to create a predictor that could estimate the attendance
of college football games. College football generates millions of dollars for universities, so
it seemed like a good place to use a machine learning algorithm.

I used a scikit-learn library and Python to do the actual machine learning.
Google Colab was the code editor of choice this time instead of Jupyter Notebooks.
It was a lot more convenient and I definitely will be using it again if I ever do data science analysis.

I used a random forest regressor and the results were great!
The features I used were various statistics from a Kaggle dataset.
[Dataset Used in Model](https://www.kaggle.com/jeffgallini/college-football-attendance-2000-to-2018)
Some drawbacks of using this was outliers in the data would not do too well due to the nature of the
algorithm.
<img src="/assets/resultsCF.png" width="275" height="600" />
<p> </p>
The left is the output directly from the algorithm.
<p>
The last thing we did for this class was host it on a VM.
A lot of the code was provided for us by instructors, but we essentially used Flask and Docker to package the
application. The docker file used an Ubuntu image which was nice to have a little Linux mixed in.
I learned how to pickle a model and also host it on a university run Virtual Machine.
Overall, this was a ton of fun and coding is way better when you're making something you are passionate about.
The full code is available on my Github linked at the bottom of the page.
</p>

<h3> Entropy Sources of the Linux Pseudorandom Number Generator </h3>
For this research, we met weekly with a member of the National Security Agency (NSA) and were able to ask any questions and collaborate
to create this report.
[Report](https://drive.google.com/file/d/1BYedk4uvmAFC6Bqu3c99sdhtd5jnAshq/view?usp=sharing)
<p></p>
<img src="/assets/raspPi.jpeg" width="200" height="175" />

My area of focus was on the Raspberry Pi and how the SOC creates entropy to be used by the system.
It was fascinating that a device that can fit in your hand can easily calculate pretty much indistinguishable random numbers.
It's worth noting the above sentence is only true if you don't know the seed.
<p> </p>
This is my first post in a while and I just wanted to say thank you for reading!
If you need help with anything engineering or career related feel free to contact me.
