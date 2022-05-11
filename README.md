# DSML-Projekt

1. Customer Behavior Analytics: As a fleet operator it is crucial to have a deep understanding of
user preferences. A standard approach in customer analytics is clustering to identify user types and/or
recurring behavioral patterns. It is your task to apply these methodologies to the case of bikesharing
and identify archetypical trip types and infer their purpose. Proceed as follows:
– Feature Engineering: A typical trip is described by three main dimensions: (1) day and time of
departure, (2) location of departure/destination1 (3) trip qualities such as duration, net distance2
or net speed3. Create new trip-level features that capture these three dimensions and visualize
their distributions. Which patterns do you observe?
– Model Building/Evaluation: Select and apply a single unsupervised clustering algorithm to identify
clusters of typical trip archetypes. In doing so, try to adhere closely to the CRISP data mining
standard covered extensively in the lectures. At each point in the process clearly defend/argue
your modeling choices with hard data/analyses where possible (e.g., why you have opted for the
specific clustering algorithm, how you prepared the data, the number of clusters your used, etc.)
– Managerial Implications and Interpretation of Results: Provide a comprehensive description of
the trip archetypes you have identified by analyzing how they vary across the above-mentioned
three core trip dimensions. Assign a meaningful label per each trip archetype that can be readily
interpreted by a non-expert in a meaningful way.
2. Predictive Analytics4: Future demand is a key factor that will steer operational decision making of
a shared rental network. As a data scientist it is your responsibility to facilitate this type of decision
support. For the purpose of this assignment we are interested in forecasting the expected number
of trips in the next hour at the most popular rental station in the network. Fleet operators
can use this information to assess whether the current amount of vehicles available at this station
will be sufficient to satisfy demand. To do so, develop a prediction model that predicts bike rental
demand for your target station as a function of suitable features available in or derived from the
datasets (incl. the weather data). Again, follow the core steps of the CRISP data mining process.
– Feature Engineering: Develop a rich set of features that you expect to be correlated with your
target. You can draw on your domain knowledge and/or conduct additional research around the
topic of demand prediction in vehicle rental networks. Justify your selection of features.
– Model Building: Select two regression algorithms that are suitable for the prediction task at
hand. Explain and justify why you selected the three algorithms and describe their respective
advantages and drawbacks.
– Model Evaluation: How well do the models perform? Evaluate and benchmark your models’
performance using suitable evaluation metrics. Which model would you select for deployment?
– Outlook: How could the selected model be improved further? Explain some of the improvement
levers that you might focus on in a follow-up project.
Notes and tips
– Make generous use of visualization techniques to clearly illustrate your findings and present them in
an appealing fashion.
– Evaluate your methodology and clearly state why you have opted for a specific approach in your
analysis.
– Relate your findings to the real world and interpret them for non-technical audiences (e.g. What do
the coefficients in your regression model mean?, What does the achieved error mean for your model?,
etc.)
– Make sure to clearly state the implications (i.e. the ”so what?”) of your findings for managers/decision
makers.
