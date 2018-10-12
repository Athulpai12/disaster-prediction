# disaster-prediction
Recently we witnessed a lot of disasters in India and we were not ready for it.So further avoid such situations we need to predict to be prepared for such situations.So my idea deals with the prediction of natural disasters to be better prepared for it.
So how would I doing it you ask below are the details :

1)Bhuvan - It is a tailor made software by ISRO  detailing different events that have taken place in India and gives a satellite image of all the events that have taken place.Now these images contain a lot of data and can be used to predict a pattern with the direction wind and hurricanes effected place or fire and the amount of crop destruction or locations effected by Tsunami.
Deep learning technique techniques(CNN and LSTM) can employed to dissect these time series data and get meaningful information out of it.

2) Along with these images data like temperature location latitude and humidity during the disaster time can be taken from an API to get further insight into knowing how these places are effected and on how the disaster spreads can be noted.Like once Tsunami hits one place the other locations that might get effected can be predicted for people to be prepared.It can also be used to find during which months and place do fire spread and how fast it spreads.

So how  would I be using azure:
Azure be used for deploying the deep neural network to dissect the time series data.
Azure would be used for predicting based on the neural networks data and the other details(like latitude and temperate variance  for helping people the be prepared for a disaster.
Also the web app would  be deployed using azure  and notifications would be sent to people based on their location if they are going to face any disaster in the near future.
