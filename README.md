# Openpose Example

1. Caffe model

   a) http://posefs1.perception.cs.cmu.edu/OpenPose/models/pose/coco/pose_iter_440000.caffemodel
   
   b) http://posefs1.perception.cs.cmu.edu/OpenPose/models/pose/mpi/pose_iter_160000.caffemodel

2. Sample video



3. Note on docker 

xhost +
sudo docker run -it --rm --runtime nvidia --network host -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=$DISPLAY -v /home/zamri/dockerfilehost:/location/in/container pytorch-opencv

or 

sudo docker run -it --rm  --network host -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=$DISPLAY -v /Users/zamri/dockerfiles:/location/in/container pytorch-opencv
