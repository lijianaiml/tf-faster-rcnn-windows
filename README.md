# tf-faster-rcnn-windows
<<<<<<< HEAD
tf-faster-rcnn的windows实现

endernewton/tf-faster-rcnn的windows版本
原版地址：https://github.com/endernewton/tf-faster-rcnn.git

操作系统win10x64，其他配置使用原版推进配置如下

tensorflow r1.2 cpu
python 3.5
cython
opencv-python
esaydict
cuda 8
cudnn 5.1

此windows实现分为CPU和GPU，模型文件参照原版下载地址
CPU实现：
安装CPU版tensorflow
按照makefile编译/lib中的setup.py
按照makefile编译/data/coco/PythonAPI中的setup.py
运行/tools/demo.py

GPU实现：
安装GPU版tensorflow
按照makefile编译/lib中的setup.py和setup_cuda.py
将/lib/model/nms_wrapper.py中注释去掉，打开USE_GPU_NMS开关
按照makefile编译/data/coco/PythonAPI中的setup.py
运行/tools/demo.py

注意：
显卡型号必须与CUDA和cuDNN版本匹配，确认匹配方法如下
1. 根据计算机GPU型号确定支持的CUDA版本号
https://developer.nvidia.com/cuda-gpus

2. 根据CUDA版本号到tensorflow官网查询对应的cuDNN版本号及tensorflow版本及python版本
https://tensorflow.google.cn/install/install_sources#common_installation_problems

3. NAVIDIA官网查询下载相应版本的CUDA和cuDNN
CUDA下载地址：https://developer.nvidia.com/cuda-toolkit-archive
CuDNN下载地址：https://developer.nvidia.com/rdp/cudnn-download
=======
tf-faster-rcnn的windows实现（cpu）
>>>>>>> 2c4fcd18ca4a2a6e4eaaf28c935c4c4fd07b01af
