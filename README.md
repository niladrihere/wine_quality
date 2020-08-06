# Wine Quality Survey

<hr>

## Overview

Wine is an alcoholic drink, generally contains mild mild alcohol level, around 5% - 15% v/v. It is typicslly maade out of fermented grapes. The difinitive and distinctive taste of wine is what attracts people the most. Different kinds of grapes produce different kinds of wines, depending on terrain, enivronment and production process. We can mojorly categorise wine into two - white and red wine, although there are many.

Wine has been produced from thousands of years, the first evidence dates back to 5000 BC in Georgia, Iran and 4000 BC in Sicily. So we definitely know humans grew attached with it. No wonder the sales are such high, accordint to study 60 Billion dollars are invested in this sector annually.

Since the sectors pulls in a lot of revenue, mojority of the companies are now in a need of data analyst to analyze their data to imporove their sales. Thus opening a tunnel of oppurtunities for data science, machine learning and analytics, in order to stay ahead in this cut-throat competiotion, amking decisions through data driven approach.

Source : <a href="https://en.wikipedia.org/wiki/Wine"> Wikipedia</a>

## How to discern wine quality ?

Wine producers constantly brag about the quality ratings that their wines receive from critics, because a high wine rating — implying high quality — translates into increased sales for a wine. But quality wines come in all colors, degrees of sweetness and dryness, and flavor profiles.

> **Just because a wine is high quality doesn’t mean that you will actually enjoy it. Personal taste is more relevant than quality in choosing a wine. A good wine is, above all, a wine that you like enough to drink — because the whole purpose of a wine is to give pleasure to those who drink it.**

A wine’s quality is not absolute: how great a wine is or isn’t depends on who is doing the judging. The combined opinion of a group of trained, experienced palates (also known as wine experts) is usually considered a definitive judgment of a wine’s quality.

The standards of performance that wine experts use to judge wine quality include the following:

1. Balance: The relationship of four components — sweetness, acidity, tannin, and alcohol — to one another. A wine is balanced when nothing sticks out as you taste it, like harsh tannin or too much sweetness. Most wines are balanced to most people.

2. Length: Used to describe a wine that gives an impression of going all the way on the palate — you can taste it across the full length of your tongue — rather than stopping short halfway. Many wines today are very up front on the palate — they make a big impression as soon as you taste them — but they don’t go the distance in your mouth. They are short. Generally, high alcohol or excess tannin is to blame. Length is a sure sign of high quality.

3. Depth: This is another subjective, unmeasurable attribute of a high-quality wine. We say a wine has depth when it seems to have a dimension of verticality — that is, it does not taste flat and one-dimensional in your mouth. A “flat” wine can never be great.

4. Complexity: There’s nothing wrong with a simple, straightforward wine, especially if you enjoy it. But a wine that keeps revealing different things about itself, always showing you a new flavor or impression — a wine that has complexity — is usually considered better quality. Some experts use the term complexity specifically to indicate that a wine has a multiplicity of aromas and flavors, while others use it in a more holistic (but less precise) sense, to refer to the total impression a wine gives you.

5. Finish: The impression a wine leaves in the back of your mouth and in your throat after you have swallowed it is its finish or aftertaste. In a good wine, you can still perceive the wine’s flavors — such as fruitiness or spiciness — at that point. Some wines may finish hot, because of high alcohol, or bitter, because of tannin — both shortcomings. Or a wine may have nothing much at all to say for itself after you swallow.

6. Typicity: In order to judge whether a wine is true to its type, you have to know how that type is supposed to taste. So you have to know the textbook characteristics of wines made from the major grape varieties and wines of the world’s classic wine regions. For example, the Cabernet Sauvignon grape typically has an aroma and flavor of blackcurrants, and the French white wine called Pouilly-Fumé typically has a slight gunflint aroma.

Source : <a href="https://www.dummies.com/food-drink/drinks/wine/how-to-discern-wine-quality/">Dummies for Wine Quality</a>

### Python libraries used

      1.Numpy
      2.Panadas
      3.Matplotlib.pyplot
      4.Seaborn

### Data Sets

      1.winequality-red.csv
      2.winequality-white.csv
      3.wineqaulity_clean.csv
      4.winequality_modified.csv
      5.winequality_onehot.csv

## About the Dataset

Wine Quality is public dataset available for research in the University of California, Irvine Machine Learning repository created by Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) in 2009. This repository consists of two dataset, red and white wine samples which consists of data points which includes objective tests (e.g. PH values) and the output is presented by the wine experts based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).

Source : <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality"></a>

### Attribute Information

Input variables (based on physicochemical tests):

1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

Output variable (based on sensory data)

12. quality (score between 0 and 10)
