# Endoscopic-Datasets

# 1.The Kvasir Dataset
#   内容： 
   . 分为Kvasir Dataset v1、Kvasir Dataset v2两个版本，两个版本均包含8个类别。其中，解剖标志三类：Z线，幽门，盲肠；病理结果三类：食管炎，息肉，溃疡性结肠炎；内镜检查程序两类："dyed and lifted polyp"，"dyed resection margins"。版本1共包含4000张图像，每类400张。版本2共包含8000张图像，每类800张。分辨率从720x576到1920x1072不等。
################################################                Kvasir Dataset v1
. Kvasir数据集（v1）的第一版包含8类的4,000张图像，这些图像显示了GI道的解剖标志，病理学发现或内窥镜检查程序，即每类500张图像。解剖学标志是Z线，幽门和盲肠，病理发现是食管炎，息肉和溃疡性结肠炎。此外，我们提供了两组与息肉切除相关的图像，即“染过的息肉和抬高的息肉”和“切除的切除切缘”。
#   Kvasir数据集v1    https://datasets.simula.no/kvasir/data/kvasir-dataset.zip
   . 所述kvasir-dataset.zip（尺寸1.2 GB）归档文件包含4000倍的图像，8类，500个图像为每个类。图像存储在单独的文件夹中，该文件夹根据类图像所属的名称进行命名。图像文件使用JPEG压缩进行编码。编码设置在整个数据集中可能有所不同，并且它们反映了先验未知的内窥镜设备设置。图像文件的扩展名是“ .jpg”。
#   提取的功能（Kvasir数据集v1） https://datasets.simula.no/kvasir/data/kvasir-dataset-features.zip
   . 该kvasir-dataset-features.zip（大小4.7 MB）存档包含从Kvasir数据集中提取的所有图像的视觉特征描述符。提取的视觉特征存储在单独的文件夹和文件中，这些文件夹和文件根据相应图像文件的名称和路径进行相应命名。提取的视觉特征是全局图像特征，即：JCD，Tamura，ColorLayout，EdgeHistogram，AutoColorCorrelogram和PHOG。每个特征向量都包含许多浮点值。向量的大小取决于特征。特征向量的大小为：168（JCD），18（Tamura），33（ColorLayout），80（EdgeHistogram），256（AutoColorCorrelogram）和630（PHOG）。提取的视觉特征存储在文本文件中。每个文件由八行组成，每个功能各占一行。每行由一个特征名称组成，该特征名称与特征向量之间用冒号分隔。每个特征向量都包含由逗号分隔的相应数量的浮点值。提取的视觉特征文件的扩展名是“ .features”。
#                                            Kvasir Dataset v2
. Kvasir数据集的第二个版本（v2）扩展了第一个版本，由8类的8,000张图像组成，这些图像显示了GI道的解剖标志，病理学发现或内窥镜检查程序，即每类1,000张图像。这些类别与Kvasir v1中的类别相同：Z线，幽门，盲肠，食道炎，息肉，溃疡性结肠炎，息肉染色和剥离息肉以及切除的切缘。
# Kvasir数据集v2  https://datasets.simula.no/kvasir/data/kvasir-dataset-v2.zip
. 所述kvasir-dataset-v2.zip（尺寸2.3 GB）归档文件包含8000倍的图像，8类，1000个图像为每个类。图像存储在单独的文件夹中，该文件夹根据类图像所属的名称进行命名。图像文件使用JPEG压缩进行编码。编码设置在整个数据集中可能有所不同，并且它们反映了先验未知的内窥镜设备设置。图像文件的扩展名是“ .jpg”。
# 提取的功能（Kvasir数据集v2） https://datasets.simula.no/kvasir/data/kvasir-dataset-v2-features.zip
. 该kvasir-dataset-v2-features.zip（大小9.3 MB）存档包含从Kvasir Dataset v2中提取的所有图像的视觉特征描述符。提取的视觉特征存储在单独的文件夹和文件中，这些文件夹和文件根据相应图像文件的名称和路径进行相应命名。提取的视觉特征是全局图像特征，即：JCD，Tamura，ColorLayout，EdgeHistogram，AutoColorCorrelogram和PHOG。每个特征向量都包含许多浮点值。向量的大小取决于特征。特征向量的大小为：168（JCD），18（Tamura），33（ColorLayout），80（EdgeHistogram），256（AutoColorCorrelogram）和630（PHOG）。提取的视觉特征存储在文本文件中。每个文件由八行组成，每个功能各占一行。每行由一个特征名称组成，该特征名称与特征向量之间用冒号分隔。每个特征向量都包含由逗号分隔的相应数量的浮点值。提取的视觉特征文件的扩展名是“ .features”。
# Kvasir数据集v2折叠  https://datasets.simula.no/kvasir/data/kvasir-dataset-v2-folds.zip
. 该kvasir-dataset-v2-folds.zip（大小25.3 GB）存档包含80000个图像。这是从Kvasir数据集（v2）生成的正式图像集，可用于执行多类分类算法的10倍交叉验证。图像存储在单独的文件夹中，该文件夹根据折叠编号和类别图像的名称进行相应命名。所有图像在每个折叠中都统一命名，并且与Kvasir数据集（v2）中的原始图像名称不匹配。图像文件使用JPEG压缩进行编码。编码设置在整个数据集中可能有所不同，并且它们反映了先验未知的内窥镜设备设置。图像文件的扩展名是“ .jpg”。
# 提取的功能（Kvasir数据集v2折叠） https://datasets.simula.no/kvasir/data/kvasir-dataset-v2-folds-features.zip
. 该kvasir-dataset-v2-fold-features.zip（大小98.6 MB）存档包含从Kvasir Dataset v2 Folds提取的所有图像的视觉特征描述符。提取的视觉特征存储在单独的文件夹和文件中，这些文件夹和文件根据相应图像文件的名称和路径进行相应命名。提取的视觉特征是全局图像特征，即：JCD，Tamura，ColorLayout，EdgeHistogram，AutoColorCorrelogram和PHOG。每个特征向量都包含许多浮点值。向量的大小取决于特征。特征向量的大小为：168（JCD），18（Tamura），33（ColorLayout），80（EdgeHistogram），256（AutoColorCorrelogram）和630（PHOG）。提取的视觉特征存储在文本文件中。每个文件由八行组成，每个功能各占一行。每行由一个特征名称组成，该特征名称与特征向量之间用冒号分隔。每个特征向量都包含由逗号分隔的相应数量的浮点值。提取的视觉特征文件的扩展名是“ .features”。
# Kvasir数据集v2折叠-附加集  https://datasets.simula.no/kvasir/data/kvasir-dataset-v2-folds-additional-classes.zip
. 该kvasir-dataset-v2-folds.zip（尺寸810.9 MB）存档包含20,000多张影像。这是从Kvasir数据集（v2）的扩展生成的官方两类附加图像集，可用于执行多类分类算法的10倍交叉验证。图像存储在单独的文件夹中，该文件夹根据折叠编号和类别图像的名称进行相应命名。所有图像在每个折叠中都统一命名，并且与Kvasir数据集（v2）中的原始图像名称不匹配。图像文件使用JPEG压缩进行编码。编码设置在整个数据集中可能有所不同，并且它们反映了先验未知的内窥镜设备设置。图像文件的扩展名是“ .jpg”。
# 提取的功能（Kvasir数据集v2折叠-附加集）https://datasets.simula.no/kvasir/data/kvasir-dataset-v2-folds-additional-classes-features.zip
. 该kvasir-dataset-v2-fold-features.zip（大小24.3 MB）存档包含从Kvasir Dataset v2 Folds-Additional Set中提取的所有图像的视觉特征描述符。提取的视觉特征存储在单独的文件夹和文件中，这些文件夹和文件根据相应图像文件的名称和路径进行相应命名。提取的视觉特征是全局图像特征，即：JCD，Tamura，ColorLayout，EdgeHistogram，AutoColorCorrelogram和PHOG。每个特征向量都包含许多浮点值。向量的大小取决于特征。特征向量的大小为：168（JCD），18（Tamura），33（ColorLayout），80（EdgeHistogram），256（AutoColorCorrelogram）和630（PHOG）。提取的视觉特征存储在文本文件中。每个文件由八行组成，每个功能各占一行。每行由一个特征名称组成，该特征名称与特征向量之间用冒号分隔。每个特征向量都包含由逗号分隔的相应数量的浮点值。提取的视觉特征文件的扩展名是“ .features”。
