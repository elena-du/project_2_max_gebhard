# Evolution of Competitiveness in Olympic Weightlifting

The idea behind this project was to see if there was some general upward trend in competitiveness within major world competitions for olympic weightlifting. It was assumed that, given the steady increase in global prosperity, and the popularity of the sport on the world stage, in particular at the olympics, that there would be a general increase in athlete ability. 

To test this, I scraped the competition data from the IWF site for all world championships and olympic games of the past 20 years. I filtered out any non-medalists from the competitions, and organized the medalists in terms of Body weight, weight lifted, age, and year of competition.

To test the trend for increases in competitiveness, i isolated each weightclass, of which there were 8, and plotted weight lifted by athlete against year of lift. I did not find a consistent trend for either deterioration in performance, or improvement. Across the 8 classes, the linear regression analysis i did showed an even split in positive and negative developments in athlete performances across the weightclasses, suggesting no real change in average competitiveness at these events.  

Tools used included:

Numpy,
Pandas,
BeautifulSoup,
seaborn,
statsmodels,
matplotlib,
mpl_toolkits,
sklearn,
scipy,
plotly
