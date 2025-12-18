# Applied Statistics Assessment
## Higher Diploma in Computer Science and Data Analytics, Winter 2025/26
**By A. O'Connor**
*********
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1200/1*OTQHk3rsuzwdidO9zgSOfA.png" alt="Python Logo" />
</p>

*********
## Introduction 
This repository contains my work on the assessment problems for *Applied Statistics*, a module I am taking as part of the Higher Diploma in Computer Science and Data Analytics at [Atlantic Technological University](https://www.atu.ie/).

The solutions to the problem set are contained in a single [Jupyter Notebook](https://github.com/a-o-connor/applied_statistics_assessment/blob/main/problems.ipynb). Some roughwork and notes made throughout the semester while studying applied statistics are contained in the `roughwork`folder.

The problem set is available [on Git Hub](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/problems.md).

## Getting Started
### Dependencies
A number of statistics modules are used throughout the notebook for data manipulation, visualisation and analysis. Links to the documentation for these modules are listed below: 
- [NumPy](https://numpy.org/doc/stable/index.html) 
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/) 
- [Scikit Learn](https://scikit-learn.org/stable/)

The required Python dependencies are listed in `requirements.txt`.

- Install dependencies using:
    ````bash
    pip install -r requirements.txt
    ````
- The Jupyter notebook can be opened and executed directly, or opened in Google Colab by clicking on the link below:
<div align="center">
    <a target="_blank" href="https://colab.research.google.com/github/a-o-connor/applied_statistics_assessment/blob/main/problems.ipynb">
        <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
    </a>
</div>

### Overview of notebook contents:
1. Problem 1: Extending the Lady Tasting Tea Experiment
- In this problem, the classic [Lady Tasting Tea](https://en.wikipedia.org/wiki/Lady_tasting_tea) experiment is simulated for 12 cups (instead of the original 8 cup experiment) and the probability of the participant correctly identifying all cups with milk first by random chance is calculated. 
2. Problem 2: Normal Distribution
- In this problem, 100,000 samples of size 10 are drawn from a standard normal distribution. The sample standard deviation and the population standard deviation are calculated for each sample, and the histogram for both sets of values are plotted.
3. Problem 3: *t*-Tests
In this problem, a simulation is carried out that draws two samples of size 100 with different means, runs a *t*-test on the two samples, and calculates the proportion of times the null hypothesis is not rejected.
4. Problem 4: ANOVA
In this problem, three samples of size 30 are generated, and both a oneway ANOVA and three *t*-tests (one for each pariwise combination) are run to test whether all 3 sample means are equal. 
