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

**product_sorting.csv**

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

# **Files**

*[01-user-time-weighted-product-score.ipynb](https://github.com/oguzerdo/rating-sorting-approaches/blob/main/01-rating-products/01-user-time-weighted-product-score.ipynb) -* User & Time Weighted Product Score Calculation Notebook

*[02.1-sorting-udemy-courses.ipynb](https://github.com/oguzerdo/rating-sorting-approaches/blob/main/02-product-sorting/02.1-sorting-udemy-courses/2.1-sorting-udemy-courses.ipynb) -* Sorting Udemy Courses Notebook

*[02.2-sorting-imdb-movies.ipynb](https://github.com/oguzerdo/rating-sorting-approaches/blob/main/02-product-sorting/02.2-sorting-imdb-movies/2.2-sorting-imdb-movies.ipynb) -* Sorting IMDB Movies Notebook

*[03-sorting-reviews.ipynb](https://github.com/oguzerdo/rating-sorting-approaches/blob/main/03-sorting-reviews/03-sorting-reviews.ipynb) -* Sorting Reviews Notebook

*[04-amazon-rating-product-sorting-reviews.ipynb](https://github.com/oguzerdo/rating-sorting-approaches/blob/main/04-amazon-rating-product-sorting-reviews/04-amazon-rating-product-sorting-reviews.ipynb) -* Rating Product & Sorting Reviews in Amazon

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)