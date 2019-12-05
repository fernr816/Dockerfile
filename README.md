# Dockerfile
## keras_mnist
Cuda9.0 + Anaconda3 + keras + tensorflow-gpu + mnist_cnn

## keras_yolo3
CUDA9.0 + Anaconda3 + keras-yolo3<br>

### usage
docker run -it --rm \
-v ~/path/to/input_img/:/keras-yolo3/input_img \
-v $HOME/.Xauthority:/root/.Xauthority \
-e DISPLAY=$DISPLAY \
--net host \
keras_yolo3

## sample_openpose
CUDA9.0 + Anaconda3 + openpose(with python API)

### usage
docker run -it --rm \
-v ~/path/to/input/:/openpose/input \
-v $HOME/.Xauthority:/root/.Xauthority \
-e DISPLAY=$DISPLAY \
--net host \
sample_openpose
