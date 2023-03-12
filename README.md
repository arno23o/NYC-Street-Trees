# NYC-Street-Trees
The Final Project for INFO2950: Introduction to Data Science.

I worked with Tomer Poole-Dayan to explore the following research question: Which socioeconomic factors are accurate predictors for the number of public curbside trees in a NYC neighborhood?

We used python and SQL, as well as the pandas, numpy, seaborn, matplotlib, and sci-kit learn libraries. We also used BeautifulSoup and Selenium to web scrape some of our zipcode demographic data.

Techniques used include: linear regression, quadratic polynomial regression, multivariable linear regression, VIF Scores, KPrototypes clustering, bootstrapping, and hypothesis tests (roughly in order).


Results Overview:
After running various regressions and hypothesis tests, we find that Median Household Income is a statistically significant predictor of the number of public street trees per 100k residents per square mile in a zip code. Specifically, the number of trees increased by 0.1053 for every dollar increase in median household income. With a t-value of 8.055, we have a confidence level of .999 that this result is statistically significant.
Additionally, when we expand our model to include input variables including income, racial makeup, and borough, the fit improves over a single variable regression.
