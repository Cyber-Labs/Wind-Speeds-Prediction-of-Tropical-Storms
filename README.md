# Wind-Speeds-Prediction-of-Tropical-Storms
In this project, we estimate the wind_speed of a storm in knots at a given point in time using satellite imagery. The training data consist of single-band satellite images from 494 different storms in the Atlantic and East Pacific Oceans, along with their corresponding wind speeds. These images are captured at various times throughout the life cycle of each storm. The goal is to build a model that outputs the wind speed associated with each image in the test set.
For each storm in the training and test sets, we are given a time-series of images with their associated relative time since the beginning of the storm. The models take advantage of the temporal data provided for each storm up to the point of prediction, keeping in mind that the goal of this competition is to produce an operational model that uses recent images to estimate future wind speeds.

# Final Leaderboard Results

![alt text](wind_lb.png "Final LB Standings")
