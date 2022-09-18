# Sorting Reviews

![SortingReviews](/images/sorting-reviews.png)

# Business Problem

There may be reviews as well as ratings about products.  These reviews are one of the biggest factors influencing a person's purchasing decision.

**Which review will we put at the top?**

Our aim is to show the most helpful reviews, not the highest ones. The ranking here will be based on whether other users find the reviews helpful or not.

The following various sequencing approaches were considered within the project.

- Up-Down Diff Score = (up ratings) − (down ratings)
- Average Rating Score= (up ratings) / (all ratings)
- Wilson Lower Bound Score

# Requirements

```python
pandas==1.4.3
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