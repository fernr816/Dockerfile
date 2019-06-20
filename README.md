# Dockerfile
## keras_mnist
Cuda9.0 + Anaconda3 + keras + tensorflow-gpu + mnist_cnn

## sample_keras_yolo3
CUDA9.0 + Anaconda3 + keras-yolo3<br>

### usage
docker run -it --rm \
-v ~/path/to/input_img/:/keras-yolo3/input_img \
-v $HOME/.Xauthority:/root/.Xauthority \
-e DISPLAY=$DISPLAY \
--net host \
sample_keras_yolo3
