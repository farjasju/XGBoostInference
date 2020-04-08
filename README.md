# XGBoostInference

## FastForest

Implementing XGBoost inference using [guitargeek](https://github.com/guitargeek)'s [XGBoost-FastForest](https://github.com/guitargeek/XGBoost-FastForest) library. 

Reads a text model file (exported using XGBoost's `dump_model` function) and makes predictions on the samples stored in `1000_samples.csv`.

The prediction results are stored in `fastforest_probs.csv`.

### How to use

First, make sure to install [XGBoost-FastForest](https://github.com/guitargeek/XGBoost-FastForest).

Then, you just have to compile the project:

```bash
g++ fastforest.cpp fast_forest_experiment.cpp 
```

And run the executable to generate the predictions:

```bash
./a.out
```

