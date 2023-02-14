# What is Rank Aggregation?
As pointed out in [1, page 417], this is a relatively unexplored approach in the context of recommendation systems, where instead of a single algorithm, a certain set of algorithms is used that generate recommendations for a given user, and then the results of these algorithms are aggregated to create a new recommendation. Aggregation is not a trivial problem, as there is no single universal method for combining such rankings.

# Where to start?
From [this](https://vene.ro/blog/kemeny-young-optimal-rank-aggregation-in-python.html) great blog post.

Next, I think it is worth reading these two publications:
* Rank aggregation
* Is rank aggregation effective?

# Software:
* [Ranx](https://github.com/AmenRa/ranx) - A Blazing-Fast Python Library for Ranking Evaluation, Comparison, and Fusion.
* [Ranky](https://github.com/Didayolo/ranky) - Another good library written in Python.
* [RecRankAgg](https://github.com/mbalchanowski/RecRankAgg) - Easy to use rank aggregation software for recommendation systems.
* [RankAggreg](https://cran.r-project.org/web/packages/RankAggreg/vignettes/RankAggreg.pdf) - R package for rank aggregation problem.
* [MC4](https://github.com/kalyaniuniversity/MC4) - An implementation of Markov Chain Type 4 Rank Aggregation algorithm in Python.

# More:
* Great repository about group recommender systems [source](https://github.com/lucasvinhtran/group-recommender-systems).
