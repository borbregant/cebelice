# Cebelice

## TODO (short goal):

- [X] Izbira ustreznih že pridobljenih datasetov (recimo še enega, ki ima teden meritev notri)
- [X] Glede na zgornjo točko ustrezen izbor vremenskega dataseta
- [ ] Združevanje zgornjega
- [ ] Vizualizacija kar imamo

## TODO (long goal):

- [X] Data collection
- [X] Data preprocessing
  - [ ] Merge tables by time series (weight, humidity, temperature, ...)
  - [ ] Remove data with high deviation and replace it with predicted regression
  - [ ] Label time series with events (rain, beekeeper adds something to the hive etc.)
- [ ] Predicition model
  - [ ] Fit data to predicted theoretical weigth (exclude weight of bees in the hive, take labels into account)
- [ ] Testing
