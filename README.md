一、简述
Pangolin 是一个轻量级的便携式快速开发库，用于管理 OpenGL 显示/交互和抽象视频输入。它的核心是一个简单的 OpenGL 视口管理器，它可以帮助模块化 3D 可视化而不增加其复杂性，并提供先进但直观的 3D 导航处理程序。Pangolin 还提供了一种通过配置文件和 ui 集成来操纵程序变量的机制，并具有用于可视化图形数据的灵活的实时绘图仪。
Pangolin 的精神是减少通常为可视化和与（通常是基于图像和 3D 的）系统交互而编写的样板代码，而不会影响性能。它还支持许多平台的一次性编写代码，目前包括 Windows、Linux、OSX、Android 和 IOS。

二、最新代码
在Github上查找并可下载最新版本：
git clone https://github.com/stevenlovegrove/Pangolin.git

三、Pangolin文件配置
将Pangolin代码下载到home中之后，按照以下步骤进行安装。
cd Pangolin
mkdir build
cd build
cmake ..
make
sudo make install
