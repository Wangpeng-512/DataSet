# Endoscopic-Datasets

# 1.The Kvasir Dataset
#   内容： 分为Kvasir Dataset v1、Kvasir Dataset v2两个版本，两个版本均包含8个类别。其中，解剖标志三类：Z线，幽门，盲肠；病理结果三类：食管炎，息肉，溃疡性结肠炎；内镜检查程序两类："dyed and lifted polyp"，"dyed resection margins"。版本1共包含4000张图像，每类400张。版本2共包含8000张图像，每类800张。分辨率从720x576到1920x1072不等。
#   Kvasir数据集v1    https://datasets.simula.no/kvasir/data/kvasir-dataset.zip
    所述kvasir-dataset.zip（尺寸1.2 GB）归档文件包含4000倍的图像，8类，500个图像为每个类。图像存储在单独的文件夹中，该文件夹根据类图像所属的名称进行命名。图像文件使用JPEG压缩进行编码。编码设置在整个数据集中可能有所不同，并且它们反映了先验未知的内窥镜设备设置。图像文件的扩展名是“ .jpg”。
#   提取的功能（Kvasir数据集v1） https://datasets.simula.no/kvasir/data/kvasir-dataset-features.zip
    该kvasir-dataset-features.zip（大小4.7 MB）存档包含从Kvasir数据集中提取的所有图像的视觉特征描述符。提取的视觉特征存储在单独的文件夹和文件中，这些文件夹和文件根据相应图像文件的名称和路径进行相应命名。提取的视觉特征是全局图像特征，即：JCD，Tamura，ColorLayout，EdgeHistogram，AutoColorCorrelogram和PHOG。每个特征向量都包含许多浮点值。向量的大小取决于特征。特征向量的大小为：168（JCD），18（Tamura），33（ColorLayout），80（EdgeHistogram），256（AutoColorCorrelogram）和630（PHOG）。提取的视觉特征存储在文本文件中。每个文件由八行组成，每个功能各占一行。每行由一个特征名称组成，该特征名称与特征向量之间用冒号分隔。每个特征向量都包含由逗号分隔的相应数量的浮点值。提取的视觉特征文件的扩展名是“ .features”。
   
