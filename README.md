# YoloVx-on-SageMaker

Yolo-Vx deploy & inference on SageMaker

#### 1 启动SageMaker Notebook Instance

https://catalog.us-east-1.prod.workshops.aws/workshops/3b86fa89-da3a-4e5f-8e77-b45fb11adf4a/zh-CN/0-intro

参考该手册中的

- [0.简介与前提条件](https://catalog.us-east-1.prod.workshops.aws/workshops/3b86fa89-da3a-4e5f-8e77-b45fb11adf4a/zh-CN/0-intro)
- [1.创建Amazon SageMaker Notebook实例](https://catalog.us-east-1.prod.workshops.aws/workshops/3b86fa89-da3a-4e5f-8e77-b45fb11adf4a/zh-CN/1-create-notebook)

**Notebook Instance用于SageMaker API的调用，拉起远端推理机器，只需要ml.c5 / ml.m5系列，可以适当增加Notebook Instance的EBS存储*

**https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html*



#### 2 拉取Sample Code

1/ 在jupyterLab中，左侧的文件列表中，新建一个实验路径，如 ```yolo-test```

2/ 进入该路径，在右侧的Launcher中，打开一个terminal

3/ ```git clone <CURRENT REPO PATH>```

4/ 基于```deploy-yolo-on-sagemaker-endpoint.ipynb```进行部署



#### References

https://aws.amazon.com/cn/blogs/machine-learning/hosting-yolov8-pytorch-model-on-amazon-sagemaker-endpoints/

https://github.com/aws-samples/host-yolov8-on-sagemaker-endpoint
