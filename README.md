# hurricane_path_prediction
# Description

Project for Data Science course. 

Model was built based on the following publication: 
Alemany, S.; Beltran, J.; Perez, A.; Ganzfried, S. Predicting Hurricane Trajectories Using a Recurrent Neural Network. AAAI 2019, 33, 468-475. doi: [https://doi.org/10.1609/aaai.v33i01.3301468](https://doi.org/10.1609/aaai.v33i01.3301468)

Repository: 
[https://github.com/sheilaalemany/hurricane-rnn]([url](https://github.com/sheilaalemany/hurricane-rnn))

## Required Packages
* pandas
* numpy
* keras
* matplotlib


## Known Issues
Due to problems with the latitute/longitude encoding, the model has a high accuracy predicting the latitude, but low accuracy predicting longitude. This can be fixed by includeing a second model that inverts the latitude/longitude selection in model building. May update in the future.
