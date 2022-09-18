# Sorting Udemy Courses

![SortingUdemy](/images/udemy.png)

# Business Problem

Within the Data Science category, various Udemy courses are requested to be ranked.

**In this case;**

- A ranking based on `Rating`, `Comment` and `Purchase` numbers as well as a ranking based on the average `weight` of these factors
- Bayesian Average Rating (BAR Score)

Furthermore, at the end of the study, a hybrid solution of all these approaches and a ranking approach is discussed.

**Bayesian Average Rating (BAR Score)**

Bayesian Average Rating calculates a weighted probabilistic average using the distributional information of the scores.

The Bayesian method applies the approach of using past information to make something in the future.

# Dataset Info

### product_sorting.csv

| Feature | Definition |
| --- | --- |
| course_name | Course name |
| purchase_count | Number of purchases |
| rating | Average rating point |
| comment_count | Number of comment |
| 5_point | 5-point rating vote number |
| 4_point | 4-point rating vote number |
| 3_point | 3-point rating vote number |
| 2_point | 2-point rating vote number |
| 1_point | 1-point rating vote number |

# Requirements

```python
pandas==1.4.3
scikit_learn==1.1.2
scipy==1.7.3
```

# **Files (EDIT)**

*[01_arl.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/01_arl.ipynb) -* Association Rule Learning Notebook

*[02_content_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/02_content_based_recommender.ipynb) -* Content Based Filtering Movie Recommender

*[03_item_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/03_item_based_recommender.ipynb) -* Item Based Filtering Movie Recommender

*[04_user_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/04_user_based_recommender.ipynb) -* User Based Filtering Movie Recommender

*[05_matrix_factorization.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/05_matrix_factorization.ipynb) -* Matrix Factorization Movie Recommender

*[Project-I-Hybrid-Recommender-System.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/06_Hybrid-Recommender-System-Project.ipynb) -* Hybrid Movie Recommender PROJECT

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)