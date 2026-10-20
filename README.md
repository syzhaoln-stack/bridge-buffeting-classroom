# 抖振 · 课后概念实验室

在线体验：https://syzhaoln-stack.github.io/bridge-buffeting-classroom/

宽频风荷载链：https://syzhaoln-stack.github.io/bridge-buffeting-classroom/#chain

五个实验：结构怎样筛选频率、拖动风谱看三维响应、动压线性化、宽频风→荷载→位移、跨向相干与阻尼。

宽频工况可以左右拖风谱改变频带、上下拖动改变强弱；拖结构频响或位移谱的橙线改变固有频率。前后方案使用同一随机相位及物理时刻，灰色保留改前对照。三维、荷载谱、位移谱和时程由同一计算链连接。

## 本地运行与修改

下载仓库，双击index.html即可运行。所有JavaScript、样式、Three.js及计算模型都内嵌在这个文件中，可用文本编辑器修改；无需安装Node.js、MATLAB或CFD软件。风场重算使用本地Blob Worker。

- guide.html：操作、公式、单位与模型范围。
- source-review.html：原课程代码的复核与改进依据。
- course-alignment.html：课件概念与实验对应。
- THREE-LICENSE.txt：随页面内嵌的Three.js许可。

本网页展示线性教学模型，参数未经实桥试验标定；具体假设在页面和说明文档中注明。
