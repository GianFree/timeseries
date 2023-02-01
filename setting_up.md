```
conda create --name ts_w_simone python=3.10

conda activate ts_w_simone

pip install sktime
pip install seaborn
pip install astropy
pip install yfinance

# to add the kernel to jupyter notebook,
# so it is available in the list of possible kernel in VSCode
pip install ipykernel
python -m ipykernel install --user --name ts_w_simone --display-name "BUBU"
```