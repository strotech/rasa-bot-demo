=============================================
Conda setup
=============================================
conda create --name rasa-env python==3.8 
conda activate rasa-env

python -m pip uninstall pip
python -m ensurepip
python -m pip install -U pip

python -m pip install --upgrade setuptools
python -m pip install rasa

conda deactivate
=============================================
Rasa setup
=============================================
rasa init