# Code Review
 
* **[X] README.md included**
* **[X] Slides included**
* **[X] Code included**
 
## Clean Code:
 
* Code is clean, generally follows PEP-8
* Good job organizing the web-scraping script into a series of functions.
* To further improve the code, you can include docstrings to explain the purpose, input, and output of the function, package helper functions into a separate .py file. 
* Another tiny detail I don't think there is a PEP-8 rule for it, but by convention, libraries import is a separate cell in the Jupyter notebook.
* Consider using comprehension lists, like transforming 
 
```
  for key, value in dict_here.items():
      items.append(value)
```
 
 into 
 
```
[items.append(value) for _, value in dict_here.items()]

```
 
## Project Documentation
 
* Good general walk through the project in the README.md file. Consider including the results of your modeling in a table or descriptive format. 
Based on the visualization, you are on to some interesting patterns in the data. It is great to have those described and summarised in the README.md. 
* You mention that the analysis didn't back up your initial hypothesis - it might be interesting to expand on this and outline the future work or the next hypothesis to test.
* Consider using Markdown cells and - maybe - a few inline comments to explain your code's logic, especially in the modeling part - to explain the choice of predictors and methods.
 
## Proper Data Science
 
* Great idea to juxtapose NumPy implementation of regression and sklearn's one.
* Nice EDA! 
* Even though the dataset is not a large one, it makes sense to evaluate performance on the train-test split, try different predictors and their combinations, feature engineering. Polynomial regression seem to go nicely with the data. A lot of cool things yet to try from the pre-built notebooks!
