# Create-3Dmax-Model 构建3D max 模型
This repo is about ways to create 3D Model
## todo
该3D建模的对象为武汉大学信息学部星湖旁经纬石。首先本人拍摄了56张经纬石照片，所有照片见文件夹的`数据集`。

接着，我在PhotoScan的软件中进行三维模型的建立，对原始照片数据进行照片对齐、建立密集点云的处理。  
将PhotoScan软件的模型保存为后缀为ply格式的文件，并导入到Geomagic软件中。Geomagic软件中,我们需要对模型进行简化处理，这样在缩小数据量，提升处理速率之外还能去除模型上的一些毛刺，
便于后续贴纹理等处理。  

最后，将Geomagic软件的模型保存为后缀为obj格式的文件，并导入到3dmax软件中，进行后续的纹理贴图制作。选择模型发送至mudbox进行纹理贴图映射就可以完成整个过程啦。

## vedio format
当然，可以将模型加载导入到3D可视化工具Lumion中做成视频。我做的视频见的`3d vedio.mp4`
