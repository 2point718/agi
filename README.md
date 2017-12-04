# nn-flaskapp
Flask Webapp of ANN Projects (this is not a reference implementation)

To run the example in a conda environment

[code language="bash"]
conda create --name nn-flaskapp -y python=3.6
source activate nn-flaskapp
conda env update -n nn-flaskapp  --file requirements.txt
python nn_flaskapp.py
[/code]

To remove the environment

[code language="bash"]
conda remove -n nn-flaskapp --all -y
[/code]