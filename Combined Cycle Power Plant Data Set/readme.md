# Multivariate Linear Regression on Combined Cycle Power Plant Data Set

Data set can be accessed from [here](https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant).

The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the plant was set to work with full load.

## Attribute Information

Features consist of hourly average ambient variables
- Temperature (T) in the range 1.81°C and 37.11°C
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW

The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization.

The problem that is solved here is predicting the net hourly electrical energy output when the temperature, ambient pressure, relative humidity, exhaust vacuum of a Combined Cycle Power Plant is known.
