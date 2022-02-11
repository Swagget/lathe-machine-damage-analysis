# lathe-machine-damage-analysis
Connected a vibration sensor to a lathe machine to predict the level of wear using the amplitude of vibrations.

## Data
The data was obtained by connecting a vibration sensor to lathe machines at Manipal University Jaipur. We connected sensors to machines where the drill bits have been replaced recently and ones that are need to be switched.
We used the points where the drill bits were changed to test when a machine would require changing the drill bit.

## Techiniques
Used ExponentialSmoothing, SimpleExpSmoothing, HoltWinters timeseries forecasting algorithms to predict the vibrations and the increasing wear and tear of the machines.

# Conclusions
We discovered that counterintuitively the vibrations were decreasing over time, this is likely because the timeframe of the data isn't sufficient to calculate an increasing trajectory of vibrations.
