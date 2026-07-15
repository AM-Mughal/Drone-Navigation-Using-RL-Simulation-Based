# Drone-Navigation-Using-RL-Simulation-Based

Simulation Environment: Airsim
RL Algorithm: PPO

Drone 1 (tracker drone) takes input image, of Drone 2 (target drone), from its camera. Image is then passed to yolo detection model. Yolo model then outputs bounding boxes. Those bounding boxes along with some other inputs are passed to PPO algorithm and PPO algorithm then outputs the velocites. Those velocites are then passes to flight controller and fc controls the tracker drone accordingly. 
