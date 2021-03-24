gazebo 仿真
```
   roslaunch ur5e_grasp ur5e_grasp_gazebo.launch 
```


查看节点情况

```
   // 查看所有节点与话题的通讯关系
  $ rqt_graph
  // 查看某个特定节点的信息
  $ rosnode info [node_name]
  // 列出正在运行的节点
  $ rosnode list
  // 显示出特定话题的消息
  $ rostopic list -v
```

