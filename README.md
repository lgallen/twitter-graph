# twitter-graph
Create a graph from a community on Twitter with Tweepy, NetworkX, and Plotly. This repo contains two iPython Notebooks. 

The first, retrieve_tweets.ipynb, uses the Twitter API to retreive Tweets via Python (Tweepy) from a common community, in this case, users that took place in a specific Twitter chat. Once the Tweets are retrieved, the associated users and their friends, who they are following, is retreived and saved in a CSV in a format that makes it easy to construct a social graph.

The second notebook, social_graph_plotly.ipynb, uses the data retreived in the first notebook to create a visualization of the social graph of those relationships using Plotly.
