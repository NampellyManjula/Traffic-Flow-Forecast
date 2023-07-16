# Traffic-Flow-Forecast
ML Project

You’ll forecast twelve-hours of traffic flow in a major U.S. metropolitan area. Time, space, and directional features give you the chance to model interactions across a network of roadways.

Submissions are evaluated on the mean absolute error between predicted and actual congestion values for each time period in the test set.

Submission File For each row_id in the test set, you should predict a congestion measurement. The file should contain a header and have the following format:

row_id, congestion 140140, 0.0 140141, 0.0 140142, 0.0 ... The congestion target has integer values from 0 to 100, but your predictions may be any floating-point number. Files and Field Descriptions ->train.csv - the training set, comprising measurements of traffic congestion across 65 roadways from April through September of 1991.

1.row_id - a unique identifier for this instance

2. time - the 20-minute period in which each measurement was taken

3. x - the east-west midpoint coordinate of the roadway

4. y - the north-south midpoint coordinate of the roadway

5. direction - the direction of travel of the roadway. EB indicates "eastbound" travel, for example, while SW indicates a "southwest" direction of travel.

6. congestion - congestion levels for the roadway during each hour; the target. The congestion measurements have been normalized to the range 0 to 100. -> test.csv - the test set; you will make hourly predictions for roadways identified by a coordinate location and a direction of travel on the day of 1991-09-30. -> sample_submission.csv - a sample submission file in the correct format
