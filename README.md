# Traffic-Flow-Forecast
ML Project

You’ll forecast twelve-hours of traffic flow in a major U.S. metropolitan area. Time, space, and directional features give you the chance to model interactions across a network of roadways.

Submissions are evaluated on the mean absolute error between predicted and actual congestion values for each time period in the test set.

Submission File For each row_id in the test set, you should predict a congestion measurement. The file should contain a header and have the following format:

row_id, congestion 140140, 0.0 140141, 0.0 140142, 0.0 ... The congestion target has integer values from 0 to 100, but your predictions may be any floating-point number. Files and Field Descriptions ->train.csv - the training set, comprising measurements of traffic congestion across 65 roadways from April through September of 1991.
