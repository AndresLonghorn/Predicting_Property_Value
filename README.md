# This project services to aid a real estate investor. 
Using AI in real estate can provide insights and faster analytics into properties listed under their book value. 

- Predictive Analytics: Machine learning(ML) algorithms can analyze historical data to predict future property values based on previous market trends. This help investors make informed and data driven decisions in regards to buying, leasing, or selling properties that are on the market today. Large data is need to help  models preform accurately. 

- Identify Opportunities: ML can go through large datasets to identify opportunities and assess potential risks associated after acquisition. Features into a property such as location, renovation dates, age of buildings, number of rooms/bathrooms, square feet, lot size, and property condition, service as prossible indicators for future investments. 

- Decision-Making: ML can automate complex tasks that take up a professional valuable time, like assessing spreadsheet data, calculating return on investment prospects, allowing investors to take on more opportunities. Despite the results that ML can provide, it is important to review AI's output. The algorithm is not the all-in-one solutions for real estate investing.  

- Identify Overlooked Features: AI-powered algorithms can identify and target demographics that can be drivers in valuation. Such as a waterfront property by a lake or a downtown condos with a view. 

## Case Study Analysis
### Dataset
The data is provided by Shiva Chandel.
https://www.kaggle.com/datasets/shivachandel/kc-house-data
Online property companies offer valuations of houses using machine learning techniques. The aim of this report is to predict the house sales in King County, Washington State, USA. The dataset consisted of historic data of houses sold between May 2014 to May 2015.

In relationship to price, square feet living space is highly postively correlated with price.  

<img width="128" height="187" alt="image" src="https://github.com/user-attachments/assets/2203190e-15bf-4bb9-8b0b-b047e1f8ef3f" />

Because of a couple of outliers with in the correlation, ML models can experience difficulties in predictions.

<img width="397" height="316" alt="image" src="https://github.com/user-attachments/assets/b6f13d39-3daf-4a28-9854-ffab05de18ac" />

Since correlation does not mean causation, a test of importance in relation to price is needed to ensure better accuracy in prediction target variables (price in this analysis). This data suggestions that in King County, Washington, USA, the most important things to consider when investing in a property are grade, square feet of living space, and latitude(location). A property with a low listing price with high numbers in these areas could pose as a valuable investment.

<img width="637" height="358" alt="image" src="https://github.com/user-attachments/assets/eb5241fc-c36c-49d6-863e-ed45a166eb28" />

In regards a higher preforming model, MSE & R^2 is used. Depending on what is important to an investor, either can serve as benchmarks. yet might be subject to overfitting. The SVR can be used in par with the random forest model to give more confidence in future tests.  
- R^2:

<img width="182" height="38" alt="image" src="https://github.com/user-attachments/assets/f0b9ca69-3abd-47d8-a41f-51361701abcb" />

<img width="599" height="229" alt="image" src="https://github.com/user-attachments/assets/841fe275-f99f-45a5-a73e-5ff865355f8d" />

- MSE:

<img width="133" height="32" alt="image" src="https://github.com/user-attachments/assets/e83befe6-ed02-4f70-a66b-ca43d450f7ff" />
