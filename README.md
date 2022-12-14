# How to use
1. Copy **"Correlation.ipynb"** to google drive
2. Open the file with google colab
3. Chage x and y value by your data
4. Run the code

# Correlation
In this repository, four famous correlation algorithms have been implemented. Pearson, spearman, Chatterjee, and MIC correlation algorithm implemented.

In statistics, correlation or dependence is any statistical relationship, whether causal or not, between two random variables or bivariate data. Although in the broadest sense, "correlation" may indicate any type of association, in statistics it normally refers to the degree to which a pair of variables are linearly related. Familiar examples of dependent phenomena include the correlation between the height of parents and their offspring, and the correlation between the price of a good and the quantity the consumers are willing to purchase, as it is depicted in the so-called demand curve.

Correlations are useful because they can indicate a predictive relationship that can be exploited in practice. For example, an electrical utility may produce less power on a mild day based on the correlation between electricity demand and weather. In this example, there is a causal relationship, because extreme weather causes people to use more electricity for heating or cooling. However, in general, the presence of a correlation is not sufficient to infer the presence of a causal relationship (i.e., correlation does not imply causation).

Four Collation algorithm Pearson, spearman, Chatterjee, and MIC implemented in **"Corelation.ipynb"**.

# Pearson correlation

In statistics, the Pearson correlation coefficient, the Pearson product-moment correlation coefficient (PPMCC), the bivariate correlation, or colloquially simply as the correlation coefficient ― is a measure of linear correlation between two sets of data. It is the ratio between the covariance of two variables and the product of their standard deviations; thus, it is essentially a normalized measurement of the covariance, such that the result always has a value between −1 and 1. As with covariance itself, the measure can only reflect a linear correlation of variables, and ignores many other types of relationships or correlations

### Formula: 
![correlation_coefficient_formula](https://user-images.githubusercontent.com/94763669/183486330-7bddb1fb-44be-4aef-9273-0dfb4f2d715f.svg)

### Value of Peason correlation for different set of (x,y):
![Correlation_examples2](https://user-images.githubusercontent.com/94763669/183485763-f91d9565-2609-4fe6-a94f-93601775526b.svg)

# Spearman’s correlation

In statistics, Spearman's rank correlation coefficient or Spearman's ρ, named after Charles Spearman, is a nonparametric measure of rank correlation (statistical dependence between the rankings of two variables). It assesses how well the relationship between two variables can be described using a monotonic function.

The Spearman correlation between two variables is equal to the Pearson correlation between the rank values of those two variables; while Pearson's correlation assesses linear relationships, Spearman's correlation assesses monotonic relationships (whether linear or not). If there are no repeated data values, a perfect Spearman correlation of +1 or −1 occurs when each of the variables is a perfect monotone function of the other.

Intuitively, the Spearman correlation between two variables will be high when observations have a similar (or identical for a correlation of 1) rank (i.e. relative position label of the observations within the variable: 1st, 2nd, 3rd, etc.) between the two variables, and low when observations have a dissimilar (or fully opposed for a correlation of −1) rank between the two variables.

### Formula:
![spearman_s_rank_correlation_coefficient](https://user-images.githubusercontent.com/94763669/183487903-75eaa8fa-6e7a-46de-a878-348a4159504b.svg)

### Pearson vs Speqrman's:
![300px-Spearman_fig1 svg](https://user-images.githubusercontent.com/94763669/183487771-fde2508c-1725-4d58-837c-fca1879a39bc.png)


# Chatterjee Correlation
Chatterjee CC (CCC: Chatterjee, 2021), as a function of ranks correlation, is a new correlation method with a very simple and understandable formula, and quick computing, but significantly robust to deal with the aforementioned data types without having any assumptions for the variables’ distributions.

**Article:** : https://arxiv.org/abs/1909.10140?source=techstories.org

### Formula:
![Chatterjee Correlation Formula](https://user-images.githubusercontent.com/94763669/183488356-1cc7d03f-b337-400c-a8df-ec58f060aa0e.png)

### Value of Chatterjee correlation for different set of (x,y):

![Chatterjee Correlation plots](https://user-images.githubusercontent.com/94763669/183488524-1cbd9a76-e105-4fa0-a8db-098059078cc4.png)

# Maximal Information Coefficient(MIC) correlation

In statistics, the maximal information coefficient (MIC) is a measure of the strength of the linear or non-linear association between two variables X and Y.

The MIC belongs to the maximal information-based nonparametric exploration (MINE) class of statistics. In a simulation study, MIC outperformed some selected low power tests, however concerns have been raised regarding reduced statistical power in detecting some associations in settings with low sample size when compared to powerful methods such as distance correlation and Heller–Heller–Gorfine (HHG). Comparisons with these methods, in which MIC was outperformed, were made in Simon and Tibshirani and in Gorfine, Heller, and Heller. It is claimed that MIC approximately satisfies a property called equitability which is illustrated by selected simulation studies It was later proved that no non-trivial coefficient can exactly satisfy the equitability property as defined by Reshef et al., although this result has been challenged. Some criticisms of MIC are addressed by Reshef et al. in further studies published on arXiv.

### how to use in python: https://minepy.readthedocs.io/en/latest/python.html

### Formula:
![MIC](https://user-images.githubusercontent.com/94763669/183489891-59a5acb8-4528-467b-9d63-b267f17a4313.jpeg)

### Value of some of correlation algorithms for different shapes:
![1_AAGEtBhIR4kGit_fuzWyAg](https://user-images.githubusercontent.com/94763669/183490127-da915dbe-e8a2-4720-9975-37016a42eb90.jpeg)


# Useful links:
- Chatterjee Correlation:
https://www.sciencedirect.com/science/article/pii/S0169136822002621#:~:text=Chatterjee%20CC%20(CCC%3A%20Chatterjee%2C,assumptions%20for%20the%20variables'%20distributions.
- Chatterjee Correlation article:https://arxiv.org/abs/1909.10140?source=techstories.org
- install minepy on python: https://minepy.readthedocs.io/en/latest/python.html
- Implementing Pearson correlation with scipy: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html
- Implementing Spearman's correlation with scipy: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.spearmanr.html
- Implementing Pearson and Spearman Coefficients in python: https://realpython.com/numpy-scipy-pandas-correlation-python/
- Efficient test for nonlinear dependence of two continuous variables : 
https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0697-7#:~:text=The%20two%20most%20common%20non,statistical%20dependence%20between%20two%20variables 

