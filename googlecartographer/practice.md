## Practice

- 开终端代理，使用官网默认下载，编译，安装方法，不要自己折腾。


- 多用source将自己的或者引用的包加入终端的环境中。
`source /opt/ros/kinetic/setup.bash`
`source /home/ben/projects/slam/devel_isolated/setup.bash `

- 使用pycharm调试省事省力，记得将ros环境加入到pycharm中

`sudo bash -i -c /XX/bin/pycharm.sh `


- 在结束后，使用服务可以生成点云或者地图

`rosservice call /finish_trajectory "stem: 'demo3d'"`

![](http://i1.piimg.com/567571/c37d1365afb8189a.png)

- 使用[pointcloudviewer](https://github.com/googlecartographer/point_cloud_viewer)先生成树，再启动本机服务就可以看点云

- 其中驱动包，可以自己写，也可以从网上来找例子