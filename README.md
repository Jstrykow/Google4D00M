There is problem with open AI gym and Gymnasium, there are diffrent paramenters inside step function, Gymnasium has place for random seed. For visualizing the version you train of Stablebaseline need to be the same for traing and rendering. StableBaselines3 from version 2.0 using Gymnasium. If you want to use gym, during installation of ViZDOOM use pip install vizdoom[gym]. For use of this code you need to add file with policy to path "./train/basic/<policy_version>" eg. "./train/basic/best_model_500"
<br />
fast start<br />
make python venv based on requirements.txt<br />
try to run visualize_basic_scenario.ipynb it should pop small window with ZDoom which can be seleceted with alt + tab<br />
to close run jupyter cell with env.close()<br />
