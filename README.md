# Chest-Cancer-Classification-using-MLFlow-DVC

created folder structure using template.py

conda create -n cancer python=3.8 -y for creating the virtual envirornment

#
# To activate this environment, use
#                                                                                                                                                              
#     $ conda activate cancer
#
# To deactivate an active environment, use                                                                                                                     
#
#     $ conda deactivate


after this do
conda activate cancer
pip install -r requirements.txt

export/set MLFLOW_TRACKING_URI=https://dagshub.com/BhavyaLikhitha/Chest-Cancer-Classification-using-MLFlow-DVC.mlflow
export set MLFLOW_TRACKING_USERNAME=BhavyaLikhitha \
export set MLFLOW_TRACKING_PASSWORD =67e311e47e6329264788b16fb4d2dc2a3c432f6b \
python script.py


dvc init
dvc repro


amazon uri = 509399636936.dkr.ecr.us-east-2.amazonaws.com/chestcancer
