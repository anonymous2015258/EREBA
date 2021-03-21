# EREBA

We have used Python 3.6 to run the files. Pytorch has been used to create and exectute the models. Other libraries Needed: tqdm, numpy, pandas.


We have already put the trained estimator model weights in the directory. To create test inputs, following commands are needed to be executed for three different AdNNs. mode1 is used for input-based test generation and mode2 for universal test generation (DDNN represents BranchyNet).


```
python blockdrop_attack.py mode1

```

```
python ddnn_attack.py mode1

```


In the folder quality, all the generated test inputs are stored. ip and op is used to express input (original) and output (test) inputs.
