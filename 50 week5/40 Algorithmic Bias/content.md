# Algorithmic Bias

Machine learning algorithms are, by definition, only as good as the data used
to train them. This means that constructing a good data set is as critical
for any machine learning solution as writing a good algorithm. Problems that
arise from using data that does not properly represent the relationship your
model is intended to capture, are called *algorithmic biases*. There are two
common sources of algorithmics bias:

### 1. Selection Bias

This simply means the data that was collected and selected to be used is not a
fair representation of the actual problem you are trying to solve. It seems
easy to spot this, but it can pop up in unexpected places, like with a
survivorship bias:

![embed](https://www.youtube.com/embed/P9WFpVsRtQg)

Facial recognition systems are unfortunately still often trained more on white
faces than on black faces, and as a result, perform better when recognizing a
white face. This can quickly have real world impacts, like black people getting
questioned more at the airport, because the passport facial scan is more likely
to fail for them.

### 2. Historic Bias

These are biases which are historically present within our society, and thus
will inherently also be reflected in the data we collect. However, societal
biases against minorities or other such biases are things we might not want our
algorithms to actually learn and imitate. This is the much more insidious
version of algorithmic bias, as it is harder to detect and much harder to
remove from the data. It is a very real problem though, as this investigation
by *ProPublica* in 2016 showed quite clearly:

[Machine Bias: Risk assessments in criminal sentencing](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)

The reason this type of bias is so hard to correct for is because completely
anonymizing data can be very hard. If you don't want the algorithm to include
race as a factor, it is not enough to just remove the `race` feature from the
data set. In quite a few cities, postal code can be a perfectly good proxy
for race, and the algorithm can just learn to discriminate against certain
postal codes instead. Many aspects of our personal data can be indicative of
race or gender, some of which are not always immediately obvious. Removing all
potentially discriminatory features from the data also means throwing away a
large part of the data that helps the algorithm to learn better, so there is an
inherent trade-off.

**Optionally**, you can also read the full write-up of how the analysis was
performed. It contains a lot of the technical details, but also gives an
interesting view of what is required for a rigorous data science project.
ProPublica used regression to model the risk score over time, and even included
confidence bounds on their plots, so the techniques are directly related to the
material from this week.

[How we analyzed the COMPAS recidivism algorithm](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm)

## Uncovering Bias

For the written assignment this week, you should search online for articles
describing other instances of algorithmic bias resulting in discrimination of
race, gender, or any other type of discrimination. The text you write should:

* Cite the original article you found
* Give a short description of the problem
* Classify this as selection bias or historic bias
* Outline what type of discrimination or other negative effects resulted from
this
* Suggest a possible strategy the developers of the algorithm could have taken
to try and reduce this bias

### Peer review

For this week, you should again swap writing assignments with other students,
read them and share feedback with each other, both on the contents of the
arguments and the structure of the writing.

In addition to your analysis of a case of algorithmic bias, you
should read the written assignments from at least 3 other students from last
week (Alpha Go). You can form your own groups for this, sharing the
assignments you submitted among yourselves. Read the other assignments and
discuss anything that might be unclear, that you disagree on or maybe just
arguments you found interesting. Then, answer the following questions.

**Q1. Which students' assignments did you read?**

**Q2. Were there any new definitions of creativity given in the other
assignments that you did not include yourself? If so, what were they?**

**Q3. Does the argument you made for or against the creativity of move 37 still
hold, if you include all these new definitions of creativity? Motivate your
answer.**

**Q4. Which assignments answered the question of whether or not move 37 was
creative differently than you did?**

**Q5. Summerize what you think was the strongest argument given among those
students who answered the question differently.**

**Q6. Did reading these other arguments change your own opinion on the
creativity of move 37? Why, or not?**

