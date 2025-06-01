installation:

1. Download the files.
2. Open the IPYNB in a jupyter-notebook (visual studio code is recommended), python version used for testing is 3.12.3
3. ensure all modules are installed (can be done by removing the # before !pip install {module}
4. Change YOUR_PATH to the path you're using (linux example: "/home/{username}/projects/EuroSAT_RGB/EuroSAT/"
5. From here you can either run everything, the 15th cell will take a long time due to training a new model. Another option is not running the 15th cell, removing the comment in the 16th cell before model_seq.load_weights(f'{YOUR_PATH}/model.weights.h5') and running that. 
6. If retraining the model: uncomment the following line in cell 19 "model_seq.save_weights(f"{YOUR_PATH}/model.weights.h5")"
