# World Happiness Data

### What you may learn here?
This notebook is a detailed investigation on world happiness. The art behind happiness has been revealed through amazing visualization. The picture of world happiness, impact factor for increased happiness score and region based happiness investigation will show a interesting scenerio of this dataset. Two regression model constructed at the end for happiness prediction and those works well.

### Dataset Context
The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012, the second in 2013, the third in 2015, and the fourth in the 2016 Update. The World Happiness 2017, which ranks 155 countries by their happiness levels, was released at the United Nations at an event celebrating International Day of Happiness on March 20th. The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.

### Dependencies
- [SciPy](http://www.scipy.org/)
- [Scikit Learn](http://scikit-learn.org)
- [Numpy](http://www.numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](http://seaborn.pydata.org/)

### Visualization: Question Answered
- Happiest regions listing based on happiness score
- Top Fifteen happiest countries in world and their Happiness Score
- Top 30 country's region checking
- Relationship among happines score vs Economy (GDP per Capita), Family, Health (Life Expectancy) and Freedom of countries
- Why happiness Score is strongly correlated with Economy, Family & Health?
- Why Happiness score increses with GDP increase?
- Linear relations between Happiness score and GDP
- Generosity dosen't affect happiness score!
- What is the range of most happiness score?
- Investigation on Asia and Europe regions
- Western Europe is happier than Central and Eastern Europe
- Drawing World Happiness Index Map 2015
-

### Predictive Modeling
- Linear Regression
- Random Forest Regression

## Investigation result
- Happiness Ranking basically depends on Economy. Countries having strong GDP rate are happiest countries indeed.
- Happiness score depends on family, health, freedom, trust on govt. etc. All of these terms have a great linear relationship with happiness score.
- World happiness doesn't define generosity or genesrosity has no remarkable impact on Happiness score.
- Regression Model works quite good in our happiness Dataset. Erros is too small to consider. We can easily check differences on above plots.
