# Dashtoon GenAI Assignment
Assignment for Dashtoon Generative AI engineer
## Dependencies
I have used tensorflow library for creating and running the model architecture. The dependencies of the notebook can be installed using the following command:<br>
```
pip install tensorflow ipython matplotlib numpy Pillow scikit-image tqdm numpy
```
## Downloading dataset from kaggle
Install the Kaggle CLI Tool using the below command(refer to [installation link](https://www.kaggle.com/docs/api#getting-started-installation-&-authentication)):


```
pip install --user kaggle
```


Please use a kaggle.json(Kaggle API) and put it in the appropriate location. The CLI tool will look for this token at `~/.kaggle/kaggle.json` on Linux, OSX, and other UNIX-based operating systems, and at `C:\Users\<Windows-username>\.kaggle\kaggle.json` on Windows.
In the same directory as the notebook, run the following commands for downloading the kaggle dataset and unxipping it:


```
kaggle datasets download -d ikarus777/best-artworks-of-all-time
unzip best-artworks-of-all-time
```
The dataset can be found [here](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time). It can also be manually downloaded and unxipped if any issues are there.

## Running the notebook
The notebook is `Dashtoon_GenAI.ipynb`. Once the above set up is done, the notebook is ready to be run. Just open the notebook and run all the cells! Read along to understand.
A copy of the Colab notebook is [here](https://colab.research.google.com/drive/16zbHad2_9mhcGTyPIZX9N9mapTEd4iH0).
