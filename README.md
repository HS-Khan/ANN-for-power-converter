# ANN-for-power-converter
Artificial Neural Network-based voltage control for the power converter. 
This repository is based on an [already-published paper](https://arxiv.org/pdf/2111.03207.pdf). 
**An invitation for research collaboration on this topic to enhance the performance of ANN-based
<img width="639" alt="paper" src="https://github.com/HS-Khan/ANN-for-power-converter/assets/67041551/680e4229-3a59-432d-a073-9293be28663d">
 controller** 

Introduction:
The rapid growth of renewable energy technology enables the concept of microgrids (MG) to be widely accepted in power systems. Due to the advantages of the DC distribution systems such as easy integration of energy storage and less system loss, DC MG attracts significant attention nowadays. Linear controllers such as PI or PID are matured and extensively used by the power electronics industry, but their performance is not optimal as system parameters are changed. In this study, an artificial neural network (ANN) based voltage control strategy is proposed for the DC–DC boost converter. In this paper, the model predictive control (MPC) is used as an expert, which provides the data to train the proposed ANN. As ANN is tuned finely, then it is utilized directly to control the step-up DC converter. The main advantage of the ANN is that the neural network system identification decreases the inaccuracy of the system model even with inaccurate parameters and has less computational burden compared to MPC due to its parallel structure. To validate the performance of the proposed ANN, extensive MATLAB/Simulink simulations are carried out. The simulation results show that the ANN-based control strategy has better performance under different loading conditions compared to the PI controller. The accuracy of the trained ANN model is about 97%, which makes it suitable to be used for DC microgrid applications.

Questions: 
Is black box-based control for power converters widely accepted by researchers and the industry?
What do you suggest as an expert to implement the ANN in the Power converter domain?


The repository is currently under construction as I familiarize myself with the usage of GitHub. I anticipate updating the codes and providing additional necessary information within the next few weeks.
                   Let us collectively endeavor to foster a more sustainable world.
