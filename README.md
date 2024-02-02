# Recommender Systems

# VIT Chennai Teacher Recommendation System

## Overview

VIT Chennai employs a Fully Flexible Credit System (FFCS), allowing students to choose their teachers each semester based on the subjects they desire and the offerings of the teachers. This system provides students with the flexibility to select electives, teachers, and time slots according to their preferences. However, a common challenge is that students often lack information about the teaching styles and effectiveness of the available faculty.

To address this gap, we propose the implementation of a Teacher Recommendation System, leveraging data from previous years. This system aims to assist students in making informed decisions about their course selections by recommending teachers based on the feedback and ratings provided by previous students.

## Objectives

- **Enhancing Student Decision-Making:**
  - Provide students with insights into the teaching styles and effectiveness of various faculty members.
  - Enable students to make informed decisions when selecting teachers for their courses.

- **Utilizing External Data Source:**
  - The initial phase of the project will utilize a sample dataset from ratemyprofessor.com.
  - Future extensions involve collecting a custom dataset from VIT students, making the system more relevant and real-time.

## Dataset

- **Sample Dataset:**
  - The initial model will use a sample dataset sourced from ratemyprofessor.com to demonstrate the feasibility of the recommendation system.

- **Real-time Extension Scope:**
  - Future iterations of the project will involve collecting a custom dataset from VIT students, enhancing the system's relevance and accuracy.

## Methodology

Recommender systems are essential components of online platforms, utilizing user purchase history to predict products of potential interest. Two primary approaches are:

### 1. Content-Based Recommendation:

**Definition:**
Content-based recommendation systems suggest items to users based on the features of the items themselves. It analyzes the characteristics of items that a user has interacted with or liked in the past and recommends similar items.

**Example:**
Consider a movie recommendation system. In a content-based approach, the system might recommend movies based on the genre, actors, director, or keywords associated with movies that the user has previously enjoyed. For instance, if a user likes action movies starring a particular actor, the system will recommend other action movies featuring the same actor.

**Pros:**
- Personalized recommendations based on user preferences.
- Less reliance on user behavior data, making it suitable for new users.

**Cons:**
- Limited diversity in recommendations, as it relies heavily on the features of the items.
- May struggle to discover new interests if the user's preferences evolve.

### 2. Collaborative Filtering:

**Definition:**
Collaborative filtering recommends items to users by leveraging the preferences and behaviors of other users. It identifies users with similar tastes and suggests items liked by those with comparable preferences.

**Example:**
Continuing with the movie recommendation system, collaborative filtering would examine the preferences of other users who have liked or disliked the same movies as the target user. If two users share a liking for similar movies, the system might recommend movies liked by one user to the other.

**Another Example**
### Users' Preferences:

- **Person A:**
  - Likes: Pizza, Chicken, Coke

- **Person B:**
  - Likes: Chicken, Pizza

### Collaborative Filtering Recommendation:

In a collaborative filtering approach, the system identifies common preferences between Person A and Person B, focusing on shared items like Chicken and Pizza. The algorithm then leverages this similarity to suggest items liked by one person to the other.

#### Recommendation:

Given the shared preferences of Chicken and Pizza between Person A and Person B, the collaborative filtering algorithm makes the following recommendation:

- **Recommended Item for Person B:**
  - **Coke**

## Why Collaborative Filtering is Often Preferred:

1. **Serendipity in Recommendations:**
   - Collaborative filtering has the potential to surprise users with unexpected but appreciated recommendations by identifying patterns that may not be apparent from item features alone.

2. **Adaptability to Evolving User Preferences:**
   - Collaborative systems adapt well to changes in user preferences over time, as they rely on the collective behavior of users.

3. **Handling New Items:**
   - Collaborative filtering can recommend new items based on the preferences of users with similar tastes, overcoming the limitation of content-based systems that struggle with novel items.

While both content-based and collaborative filtering have their merits, collaborative filtering often stands out for its ability to provide more diverse and serendipitous recommendations, particularly in scenarios with a large user base and dynamic preferences.



## Similarity Measures Used

### Cosine Similarity
Measures similarity between vectors using the cosine of the angle between them. Commonly employed in text analysis to determine document similarity.

### Pearson Correlation Coefficient
Quantifies the linear relationship between two variables (X and Y). Mathematically expressed using covariance (σXY) and standard deviations (σX), resulting in a correlation coefficient (ρ) between -1 and +1.


## Algorithms Used

### Teacher Recommender System
- Collaborative Filtering Approach
- Data Mining Techniques

### Machine Learning Algorithms Used

1. **Non-Negative Matrix Factorization Method Implementation (NMF or NNMF):**
   - Factors a matrix V into non-negative matrices W and H, offering insights into multivariate analysis and linear algebra.

2. **KNN Algorithm Implementation:**
   - Solves classification model problems by creating an imaginary boundary to classify data based on proximity.

3. **Singular Value Decomposition Implementation (SVD):**
   - Decomposes a matrix into three matrices, providing algebraic and geometrical insights into linear transformations.

These algorithms collectively enhance the Teacher Recommender System's ability to predict user preferences and provide valuable recommendations.
