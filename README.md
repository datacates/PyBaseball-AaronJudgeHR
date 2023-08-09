# PyBaseball-AaronJudgeHR
Logistic Regression model for Aaron Judge using PyBaseball to classify balls in play as home runs or not based on exit velocity and launch angle at Yankee Stadium. As a Yankees fan, this was just a proof of concept exercise for fun. 

The model was about as effective as expected based on only two dimensions, between 80-90% accurate over the course of Judge's entire career without factoring in weather/wind speed or launch direction (left field vs right field). The spray chart of balls in play showed some interesting trends too, most of Judge's infield outs are concentrated around third base and almost all of his doubled went to the left field corner.

For the sake of irony, I wrote a function to test the model over the same time period on Jose Altuve. He is the polar opposite of 6"7' Aaron Judge, standing at 5"6' but he has certainly hit his share of home runs at Yankee Stadium. The model was actually much more accurate for Altuve than Judge, which I suspect to be a result of his consisteny in pulling the ball to left field when hitting for power.
