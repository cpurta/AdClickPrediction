# AdClickPrediciton

This is my implementation of some techniques used to predict the probability
that an ad will be clicked for the [Outbrain Click Prediction Competition](https://www.kaggle.com/c/outbrain-click-prediction/data). Some of the methods includes a statistical method
based on the mean of ads clicked / ads served. One uses the FTRL-Proximal algorithm as
described in [this
paper](https://www.eecs.tufts.edu/~dsculley/papers/ad-click-prediction.pdf).
Also I have been researching methods that have won past ad-click prediciton
competitions such as Field Aware Factorization Machines as described by the team
that one the Criteo Ad Click Prediction competition. Their paper can be found [here](http://www.csie.ntu.edu.tw/~cjlin/papers/ffm.pdf).

## Notebooks

If you have `Jupyter` installed you can open up the notebooks with that and this
will allow you to interact with the notebooks. You will have to download the
data files for the notebooks to work properly. Those can be found
[here](https://www.kaggle.com/c/outbrain-click-prediction/data).

## Best Accuracy

The best accuracy that I have achieved was 0.64175 with the FTRL-Proximal script.

## Future work

I am still tinkering with the data set provided to use the libffm implementation
to try and get better results. 

## LICENSE

MIT
