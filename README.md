# Network Anomalies Detection for Live Video Streaming events

This project analyzes, cleans and transforms data, given data from different events and customers, it later creates a machine learning model that detects events with anomalous behavior.

#The data

viewer id : A unique identifier of the viewer. If the viewer participates
in multiple events, the identifier remains the same

event id : A unique identifier of the event

customer id : A unique identifier of the customer. Events and viewers
cannot appear in multiple customers

timestamp : The exact millisecond when the viewer reported data in our
backend servers

country id : A unique identifier of the country where the viewer joins
the event

city id : A unique identifier of the city where the viewer joins the event

viewer type : A boolean flag that defines if the viewer joins the event
from the corporate’s office or from home

qoe : The quality of experience of the viewer in the specific timestamp

Engagement : The engagement of the viewer in the specific timestamp


# analysis.ipynb
The first part of the project entails, the data analysis, cleaning and transformation. 

# model.ipynb
This file includes 3 possible models all of which are implemented using the same architecture: LSTM autoencoders.
