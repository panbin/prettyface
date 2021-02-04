# 网红脸生成器-V2.0
安装Miniconda3（无需另外装python）
1.打开https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/
2.找到Miniconda3-4.5.4-Windows-x86_64.exe下载
3.或者直接下载 https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/Miniconda3-4.5.4-Windows-x86_64.exe

下载项目
1.打开https://github.com/a312863063/seeprettyface-generator-wanghong
2.点击img下载项目。
3.将项目解压到桌面。
4.下载模型 https://cloud.189.cn/t/7b2q2eqIzQbm （高速下载）
备用下载：https://pan.baidu.com/s/18WSmt453RWBbYaOVWQn_Hw 
提取码：mp46   百度云限速 
5.将模型文件解压到model文件里。

配置Miniconda运行环境
更换国内源
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --set show_channel_urls yes

安装 tensorflow-gpu
conda install tensorflow-gpu==1.9

!conda install tensorflow-gpu==1.9

安装Pillow
conda  install Pillow

!conda  install Pillow


!pip install numpy==1.16.2

### 生成人脸 
修改generate_wanghong.py
注释掉model_path = 'model/generator_wanghong_256px.pkl'这一行，在开头加#号
启用model_path = 'model/generator_wanghong.pkl'这一行 去掉开头#号

cd  进入目录
执行  python generate_wanghong.py 生成人脸。

python generate_wanghong.py

!python generate_wanghong.py

!pip install numpy==1.16.2