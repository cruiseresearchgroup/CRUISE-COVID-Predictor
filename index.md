This project is about exploring the Symptom Survey data. For more details, please check [The COVID-19 Symptom Data Challenge
](https://www.symptomchallenge.org/challenge). This work is presented by RMITCruisers!



### Research Questions

1. How much the Symptom Surveys Dataset is effective and useful for the task of predicting the COVID-19 outbreaks?
2. What are the most important attributes included in the COVID-19 Symptom Surveys dataset? And does it correlate with the COVID-19 cases numbers?
3. What is the best period length that needed to be analyzed in order to be able to predict the next COVID-19 hot spots?
4. Is our proposed model able to predict the status of COVID-19 in the next period for a specific region?




### Data

1. [CMU US Symptom Survey](https://cmu.app.box.com/s/ymnmu3i125go4aue0qxosi3rbcae20bj)
2. [Wikipedia Case Number](https://en.wikipedia.org/wiki/Template:COVID-19_pandemic_data/United_States_medical_cases)


### Methods

#### Feature Selection


#### Framework

![](figs/framework.png)

#### Sliding Window

![](figs/sliding_7.png)

![](figs/sliding_14.png)

### Results

#### Results of Four States

#### Without Less Important Signals


#### Prediction VS Real


### Conclusion
- Symptom Surveys dataset would be very useful for future prediction of COVID-19 cases.
- Not all signals are useful for predictions. Important signals are more helpful for the prediction.
- Our model is able to predict the trend (decreasing/increasing) of the case number of a state with selected important signals.


### Future Work
- Combining other open datasets to further improve the prediction performance.
- Integrate our prediction model into COVID Forecast Hub for better visualization.
- How to make recommendations for the government regarding policy decisions based on the prediction results.




#### Contacts

Hao Xue (hao.xue@rmit.edu.au)


