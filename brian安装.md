# brian安装

- ### 注意：Brian支持的python >= 3.7，提供的python包也要64位版本的；而且现在brian已经不支持pyhton2

  ## 安装

  - ### conda

    `conda install -c conda-forge brian2`

    将该频道永久添加到频道列表中

    `conda config --add channels conda-forge`

    上面一行代码只需执行一次，之后就可以像安装和更新其他软件包一样安装和更新brian2的软件包

  - ### pip方法
  
    `pip install brian2`
  
  - ### Ubuntu
  
    `sudo apt install python3-brian2`





   ## 更新现有安装

- ### conda

  `conda update brian2`

- ### pip 

  `pip install -U brian2`

- ### Ubuntu

  `suao apt update`

  `suao apt install python3-brian`

  

## 安装其他有用的包

- ### conda 

  `conda install matplotlib pytest ipython notebook`

  `conda  install -c brian-team brian2tools`

- ### pip

  `pip install matplotlib pytest ipython notebook`

  `pip install  brian2tools `

## 测试brian2是否安装成功

`import brian2`

`brian2.test()`

