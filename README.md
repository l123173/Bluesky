# Jupyter
**问题：import 明明安装了，但是还找不到**  
Jupyter 的环境和conda中的不一样，很容易导致上述问题  
解决方法：  
conda install nb_conda_kernels  
conda install ipykernel  
缺一不可，注意看执行结果，第二句容易fail，如果执行不了，试试翻墙  

# Conda
conda info -e （查看所有的虚拟环境）
conda activate env (进虚拟环境，如果不起作用，就加source）

# Ophyd
https://blueskyproject.io/ophyd/tutorials/install.html
他是其是把conda，pip，source的安装方法都列出来了，注意区分。

https://blueskyproject.io/ophyd/tutorials/install.html
如果**报错**说没有caproto这个模块，用上面这个网址的pip命令，安装一下（完全按照这个PIP里的命令，完全！！！）
