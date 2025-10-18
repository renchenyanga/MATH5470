# MATH5470

The file **`model.zip`** contains the trained model weights and some additional useful files.  
If you want to **load the pre-trained model** without running the full training process, please:

1. Set `load = True` in the `kfold_lightgbm` function.  
2. Unzip the `model.zip` file into the **same directory** where the `code.ipynb` file is located.  

Otherwise, if you prefer to **train the model from scratch**, simply set `load = False`.  
In this case, the script will execute the complete model training process.
