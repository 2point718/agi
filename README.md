# ANN Projects (this is not a reference implementation)


To run the flask app in a conda environment

```bash
conda create --name nn-flaskapp -y python=3.6
source activate nn-flaskapp
conda env update -n nn-flaskapp  --file requirements.txt
python nn_flaskapp.py
```

To remove the environment

```bash
conda remove -n nn-flaskapp --all -y
```
