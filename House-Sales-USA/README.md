<h1 align="center">🚀House Sales in King County, USA🚀</h1>

<h1 align="left">📋About the dataset</h1>

- This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. Access here: [dataset](https://www.kaggle.com/harlfoxem/housesalesprediction?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDA0101ENSkillsNetwork20235326-2022-01-01)

  | Variable      | Description                                                                                                 |
  | ------------- | ----------------------------------------------------------------------------------------------------------- |
  | id            | A notation for a house                                                                                      |
  | date          | Date house was sold                                                                                         |
  | price         | Price is prediction target                                                                                  |
  | bedrooms      | Number of bedrooms                                                                                          |
  | bathrooms     | Number of bathrooms                                                                                         |
  | sqft_living   | Square footage of the home                                                                                  |
  | sqft_lot      | Square footage of the lot                                                                                   |
  | floors        | Total floors (levels) in house                                                                              |
  | waterfront    | House which has a view to a waterfront                                                                      |
  | view          | Has been viewed                                                                                             |
  | condition     | How good the condition is overall                                                                           |
  | grade         | overall grade given to the housing unit, based on King County grading system                                |
  | sqft_above    | Square footage of house apart from basement                                                                 |
  | sqft_basement | Square footage of the basement                                                                              |
  | yr_built      | Built Year                                                                                                  |
  | yr_renovated  | Year when house was renovated                                                                               |
  | zipcode       | Zip code                                                                                                    |
  | lat           | Latitude coordinate                                                                                         |
  | long          | Longitude coordinate                                                                                        |
  | sqft_living15 | Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area |
  | sqft_lot15    | LotSize area in 2015(implies-- some renovations)                                                            |
  
<h1 align="left">📚Libraries</h1>

- For this project I used the following libraries

| ID            | Description   |
| ------------- | ------------- |
| 1 | `Pandas`                  |
| 2 | `Matplotlib`              |
| 3 | `Numpy`                   |
| 4 | `Seaborn`                 |
| 5 | `Sklearn.pipeline`        |
| 6 | `Sklearn.preprocessing`   |
| 7 | `Sklearn.linear_model`    |

<h1 align="left">📈Charts</h1>

<h3 align="left">📉Boxplot</h1>

- The box plot was used to determine whether houses with a waterfront view or without a waterfront view have more price outliers.



<h3 align="left">📉Regplot</h1>

- The regression plot was used to determine if the feature sqft_above is negatively or positively correlated with price.

<img scr="C:\Users\augusto.oliveira\OneDrive - Ministério das Relações Exteriores\Área de Trabalho\regplot.png">
