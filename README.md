# ViZDoom on Google Colab 
[ViZDoom Documentation](https://vizdoom.farama.org/)

A traing of model is performed on Google Colab. I used T4 and it performed around 500k step per hours. 
I recomend to get know scenarious on youtube before performing experiments. It makes easier to understand what is point of environment and helps to create reward function. 

Gooogle Colab can only print "state" with matplot lip to watch full replay is code to run localy. I added requirements from Conda Python 3.11 and I ran it on Ubuntu WSL. For use of this code you need to add file with policy to path "./train/basic/<policy_version>" eg. "./train/basic/best_model_500"
<br />

For evaluation of models I used the tensorboard which need to be run before model.learn. Also I added access to
my google drive to save models with callback functions. After learning model is cell with disconnect paid graphics card for avoid unnecessary cost. Model can be learn during night, logs and polices will be saved to drive and paid runtime will be disconnected. 

### fast start
make python venv based on requirements.txt<br />
try to run visualize_basic_scenario.ipynb it should pop small window with ZDoom which can be seleceted with alt + tab<br />
to close run jupyter cell with env.close()<br />

## Health Gathering 
The code for HEALTH GATHERING is the same as HEALTH GATHERING SUPREME only need to be changed 
