# Graph Data :metal:

We are provided with some temporal graph data and asked to illustrate some exciting insights hidden within it. There is no pre-defined "correct solution", but we demonstrate mastery of graph data modelling in the context of doing Data Science.



## Data :cloud:
Reddit is an American online community of message forums that is split into "sub-reddits" that each have a self-defined focus. We are provided with a hyperlink graph (https://snap.stanford.edu/data/soc-RedditHyperlinks.html), where each node represents one of the 55,000 sub-reddits and an edge indicates that a post in one sub-reddit linked to a post in another sub-reddit. The edges are directed and multivariate: they are labeled with a creation timestamp and a (crowd-sourced) sentiment polarity that indicates whether the linking content was explicitly negative towards the target sub-reddit.

## Packages and Software used :computer:
Python <br>
matplotlib <br>
D3.js (Chord diagram) <br>
Neo4j <br>
Tableau <br>

## Insights :pencil:

![ScreenShot 1](Visualizations/chord_diagram.png)

![ScreenShot 2](Visualizations/Influential_subreddits.png)

![ScreenShot 3](Visualizations/nodes_that_can_be_visited_by_only_body_or_only_title.png)

![ScreenShot 4](Visualizations/Popular_subreddits.png)

![ScreenShot 5](Visualizations/Subreddits_that_answer_most_other_subreddits.png)

![ScreenShot 6](Visualizations/Subreddits_trend_on_new_year_eve.png)
