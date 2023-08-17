# Car Price Prediction
After a thorough model comparison, a _`random forest with 30 selected features`_ is the best model for car price prediction due to its superior performance and robustness. 
Its _`RMSE`_ highlights that the squared differences between the predicted and actual car prices from this model have an average error of _`235.75 dollars`_, 
while the _`MAE`_ showcases that the predicted car prices from this model are off by _`57.99 dollars`_ compared to the actual car prices on average. 
Furthermore, an _`adjusted R-squared`_ value of _`0.9992`_ indicates that the variables used in this final random forest model can explain approximately _`99.92%`_ of the variability in car prices. 
It proves its capability to pinpoint vital car features, capture fluctuated data patterns, and utilize them for precise price predictions with minimal error deviations. 

# Data Dictinoary
## Independent Variable (Predictor Variable)
| `Variable`| `Description`| `Data Type` |
| ------------- |:-------------:| -----:|
| Car_ID      | Unique id of each observation |*Interger*|
|Symboling| Its assigned insurance risk rating, A value of +3 indicates that the auto is risky, -3 that it is probably pretty safe |*Categorical*|
|carCompany | Name of car company |*Categorical*  |
| fueltype | Car fuel type i.e gas or diesel| *Categorical*|
|aspiration | Aspiration used in a car |*Categorical*|
| doornumber | Number of doors in a car |*Categorical*|
|carbody | Body of car| *Categorical*|
| drivewheel | Type of drive wheel |*Categorical*|
| enginelocation | Location of car engine |*Categorical*|
| wheelbase | Wheelbase of car |*Numeric*|
| carlength | Length of car |*Numeric*|
| carwidth | Width of car| *Numeric*|
| carheight | height of car| *Numeric*|
| curbweight | The weight of a car without occupants or baggage |*Numeric*|
| enginetype | Type of engine |*Categorical*|
| cylindernumber | Cylinder placed in the car |*Categorical*|
| enginesize | Size of car| *Numeric*|
| fuelsystem | Fuel system of car |*Categorical*  |
| boreratio | Boreratio of car |*Numeric*|
| stroke | Stroke or volume inside the engine |*Numeric*|
| compressionratio | Compression ratio of car |*Numeric*|
| horsepower | Horsepower |*Numeric*|
| peakrpm | car peak rpm| *Numeric*|
| citympg | Mileage in city |*Numeric*|
| highwaympg | Mileage on highway |*Numeric*|

## Dependent Variable (Target)
| `Variable`| `Description`| `Data Type` |
| ------------- |:-------------:| -----:|
| price      | Price of car |*Numeric* |


