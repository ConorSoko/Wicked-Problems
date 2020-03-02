# Stevens et al. Response (Lightning Questions)

Conor Sokolowsky

3/2/2020

1. Stevens et al. introduce a new predictive model to disaggregate large population data sets into gridded, high-resolution density graphs. The model, named the 'Random Forest model', generates a collection of individual regression/classification trees that are then aggregated together to create a predictive layer. The method is similar to machine learning or neural network algorithms in that the aggregated data can be used to estimate variable weights after it is tested.

2. A machine learning method is built upon layers of decision trees, each of which returns a predicted value, but the aggregated predictions from the entire "forest" will typically be more accurate than any of the individual decision trees. Furthermore, when a machine learning algorithm is tested on a data set, it has the ability to 'learn'. It does so by adjusting the importance of various variables and preconditions used in each decision tree's calculation in order to improve the model's accuracy. Such a technique is different from previous statistical approaches in that this model is able to learn which input variables should be most heavily weighted when predicting population distributions, whereas previous models simply tried to incorporate various input variables at equal weighting.

3. Some of the geospatial covariates used by the Random Forest model include geography, land cover, night-time light density, (distance to) tansportation networks, and settlements. They represent vast amounts of data that take an incredible amount of time to process, but are also incredibly useful in developing machine learning models. The sheer size and variability of the data allows for automated processes to refine the importance of each variable and produce highly accurate predictive landscapes without requiring the time, inefficiency, and innacuracy of previous methods.

4. In the context of human development, it is incredibly important to have an accurate description of population density for numerous reasons. It would help organizations target key community nodes that may require improvement, allow for easier population/census counts (which is important in democratic institutions), and allow resources to reach the homes of people far more efficiently. Impact evaluations of projects on communities would be more accurate as well, thereby allowing organizations to refine their own development project methods in order to maximize benefits and minimize costs to the communities around the project sites.

5. My area of investigation revolves around having an accurate population count in my given LMIC (Uzbekistan). This population count is regressed with various covariates accessed from numerous WorldPop data sets. In the future, I hope to isolate my variables into more specialized subject topics to support a tangible thesis, but this topic is yet to be decided.
