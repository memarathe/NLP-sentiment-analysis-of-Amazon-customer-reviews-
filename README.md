# NLP-sentiment-analysis-of-Amazon-customer-reviews-
Sentiment analysis of Amazon product reviews involves analyzing customer feedback to determine the underlying sentiment—whether the review is positive, negative, or neutral. This process helps businesses and consumers understand the general opinion about a product based on user-generated content.

The input text files contain sentences labelled with positive or negative sentiment, extracted from reviews of products, movies, and restaurants

=======
Format:
=======
sentence \t score \n


=======
Details:
=======
Score is either 1 (for positive) or 0 (for negative)	
The sentences come from three different websites/fields:

imdb.com
amazon.com
yelp.com

For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a clearly positive or negative connotaton, the goal was for no neutral sentences to be selected.
