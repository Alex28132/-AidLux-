# -AidLux-

基于边缘计算AidLux的自动驾驶智能预警应用方案

配置环境：

cd YOLOP/YOLOP

pip install -r requirements.txt pip install torch==1.8.1 torchvision==0.9.1 -i https://pypi.mirrors.ustc.edu.cn/simple/

pip install onnxruntime -i https://pypi.mirrors.ustc.edu.cn/simple/

![71f4ed6a0acd86299d391e1fcbfa49fb_image](https://github.com/Alex28132/-AidLux-/assets/53650857/342953e9-7aa6-45a2-80fb-f91f08240183)


进行推理：

python tools/demo.py --source inference/images

报错进行如下操作，不报错不用看 
![81e1bd8f23b028753840d4f039380a02_image2](https://github.com/Alex28132/-AidLux-/assets/53650857/19e3bea1-5a37-418c-9359-7b5a908b3fe0)


pip install opencv_python==4.5.4.60 -i https://pypi.mirrors.ustc.edu.cn/simple/

环境配置完成 
![d1d375adf162fe12dc2b1a86efdf81b3_image3](https://github.com/Alex28132/-AidLux-/assets/53650857/9e7660d2-392b-49c9-b049-93dba915b1f9)



推理结果

![d2aea28c717809993f2fc03b68859285_image4](https://github.com/Alex28132/-AidLux-/assets/53650857/e87c0dab-f303-447f-8e99-df4b0ec60ba8)


运行预警系统： python forewarning.py

![3ea6e0518df17682f5a15269b8556f80_image5](https://github.com/Alex28132/-AidLux-/assets/53650857/be904e86-3675-43d3-8b6a-1fc83cbfdf72)




报错： 

![af7739418d0cf9e36fe63c4e93816e10_image6](https://github.com/Alex28132/-AidLux-/assets/53650857/46590fe7-c5d4-4c0a-aa88-af5b2c8071ac)



解决中文报错后重新运行： 

![ffc1440930eac14f0f1af3985ad4e0ac_image7](https://github.com/Alex28132/-AidLux-/assets/53650857/75648d3f-9546-4283-b536-f5941f000b05)


结果：

https://www.bilibili.com/video/BV1hM4y177r2/?spm_id_from=333.999.0.0&vd_source=ffc65fd2c117392dd6599cf1d3bbaf20
