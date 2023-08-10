1.如何在激活的环境中打开jupyter notebook?
> 详细方法: [link](https://blog.csdn.net/w55100/article/details/88925697)  
> shortcuts:
> 激活虚拟环境，以env为例，安装jupyter插件ipykernel
> ```
> conda activate env
> conda install ipykernel
> ```
> 然后运行如下命令
> ```
> python -m ipykernel install --name {你的虚拟环境名字，如env} --display-name {你想显示的名称}
> ```
> 之后就可以直接在虚拟环境中打开jupyter notebook
