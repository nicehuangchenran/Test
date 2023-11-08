```text
pip install 包名称 -i https://pypi.tuna.tsinghua.edu.cn/simple（清华镜像）
pip install 包名称 -i  https://pypi.doubanio.com/simple/ （豆瓣镜像）
```

 `deactivate 环境名` 退出环境

`conda info --envs` 查看现有环境

`conda list pip list` 查看安装的包

`conda remove -n 环境名 --all` 删除环境

# pip3 list查看现在安装的包，在多个文件路径下都可以用

# canvas代码

解析命令行参数；
构建环境ALEModern或ALEClassic；
初始化AtariNet模型；
载入训练好的模型参数；
采用epsilon-greedy策略，输出每个状态下最优动作的索引以及对应的Q值。