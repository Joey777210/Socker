# Socker
Socker是基于linux的容器引擎，基于xianlubird的书《自己动手写Docker》和runc
环境：Ubuntu 18.04，go 13.4
目前思路：结合mqtt实现容器内的数据下发<br/>
目前遇到的问题和bug：<br/>
  1,在busybox中mount /proc时会报错。mount2 point
  2，后台运行top时， 通过ps -ef并不能看到init接管top进程
