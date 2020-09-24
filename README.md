# dir2tree
可以将文件目录转化为一个动态可以展开的目录树文件，文件为html格式


#### install

    pip install dir2tree

#### demo
    from dir2tree import GetTreeFile
    
    rootPath=r"C:\py_project\TeaCases\python法律应用实务\大型非诉项目处理\尽职调查文件夹"
    if __name__=='__main__':
        GetTreeFile(rootPath)


#### result

![](https://www.lawtip.cn/images/md/20200924-1.png)
