# caffe-iuf
Dockerfile for old version of caffe. Old but: deconv layers, max unpool, locally connected layers.

Run me with proper parameters:
nvidia-docker run -i -t --device=/dev/nvidia0:/dev/nvidia0 --device=/dev/nvidiactl:/dev/nvidiactl matthieudelaro/caffe-iuf

Your devices may change depending on your hardware. Use those returned by:
ls /dev | grep nvidia
