
  
# Most Viewed: Popular by Views


Amazon Personalize Recipe:
[Popular-by-Views](https://docs.aws.amazon.com/personalize/latest/dg/ECOMMERCE-use-cases.html#most-viewed-use-case)



Recommends popular products based on how many times customers have viewed an item. The most popular items have the most
"View" interactions with unique users. The recipe returns the same popular items for all users. Therefore, recommendations are
not personalized to the individual user and are useful when you want a system-wide representation of what's popular.



Popular by Views is implemented used on the homepage to display popular items when there is not browsing
history for the current user (i.e. cold user). Once the known or anonymous user has more than three interactions (this
is an arbitrary number chosen in the Retail Demo Store's implementation), the storefront will switch to a personalized
recommendation using the Recommended For You retail recommender. You can tell when this transition is made when the homepage
grid header changes from "Popular products" to "Inspired by your shopping trends".



You may notice some items are annotated with a "Promoted" banner across the top of the product image. This banner indicates
products that match a promotional filter that is optionally applied when retrieving recommendations. Promotional filters are
a great way to ensure that a user-defined percentage of recommended items match a specific filter expression but are also
relevant to the user. This can be used to highlight products on sale or new products recently added to the catalog.



  
