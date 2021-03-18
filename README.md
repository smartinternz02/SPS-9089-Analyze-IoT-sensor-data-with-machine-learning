# SPS-9089-Analyze-IoT-sensor-data-with-machine-learning
Analyze IoT sensor data with machine learning

link for demonstration video :- 
https://drive.google.com/file/d/1_Y1CoVTpzO7FqsqYz-yD71Jj1LCwOy9h/view?usp=sharing


link for the node red application :-
https://node-red-zyfky-2021-02-19.eu-gb.mybluemix.net/ui

link for watson iot simulator:- 
http://watson-iot-sensor-simulator.mybluemix.net/

Use the below credentials for iot simulator:- 
note:- Use the resources judicialy as the machine learning model provides only 20 capacity units per month.

Organization ID:- actc1w
Device Type :- nodemcu
Device ID :- apnode
Authentication Token :- !zZmCjXQzIoSHFG3gd


note:- The machine learning model generally consider values between 16 to 50 as normal temperature values.
values above or below this range are considered as abnormal temperature values.

"temp dataset for project" is a csv dataset file
 containing temperature values and the status column 
specifies weather the corresponding temperature value is beyond limit or not
0 is for ok and 1 is for not ok.
temperature values between 0 to 16 and beyond 50 are not ok.
temperature values between 15 and 50 are ok.
