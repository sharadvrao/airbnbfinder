# AirbnbFinder: A Powerful Airbnb Recommendation Engine

**Overview** A platform that greatly simplifies the process of locating an Airbnb property in Seattle. Airbnb’s current design requires the user to enter very granular information and potentially search through hundreds of listings. AirbnbFinder presents a streamlined approach which allows the user to enter flexible search criteria, indicate relative preferences, and incorporate relevance feedback information. 

**Data** The design utilizes data from Inside Airbnb, a publicly available raw dataset of Airbnb properties from multiple markets. The data was prepared using techniques including NLP, categorical encoding, and standardization.

**Modeling** At the heart of AirbnbFinder is a content based recommendation engine. Preferences are quantified then used to construct a cosine similarity-based measure of the 20 most alike properties. The user is given the opportunity to select preferred properties and this information is used to further refine the search results.   

<p align="center">
  <img src="https://github.com/sharadvrao/apartment_recommender/blob/master/model.png">
</p>

**What’s Next?**  Recommendation engine performance is inherently challenging to evaluate. Further refinement of the utilized distance metrics through an ad-hoc process of evaluation by a multitude of users is a proposed method. The ultimate goal of the platform is to scale the technology to the property rental market at large.
