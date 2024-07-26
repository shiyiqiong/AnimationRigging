版本：Unity 2022.3.14f1c1。
***
Animation Rigging（动画绑定约束）用途：Unity提供的一套官方插件，用于提供一套便利的通过程序代码控制蒙皮动画的方案。
***
Animation Rigging（动画绑定约束）使用：
- 下载Animation Rigging包；

  ![image](https://github.com/user-attachments/assets/d5d16930-4fd4-4fe9-818d-ce0277b11cc3)

- 在动画根节点添加骨骼渲染器组件，方便可视化编辑骨骼；
  
  ![image](https://github.com/user-attachments/assets/c1e3b0e6-d319-4698-b989-687e4334eb0a)

- 在动画根节点添加绑定构建器组件；

  ![image](https://github.com/user-attachments/assets/d6b58216-a321-4a7a-a3b5-a2eac276d261)

- 创建绑定层级，将层级添加到绑定构建器中（可设置权重，以及是否启用）；

  ![image](https://github.com/user-attachments/assets/d2bc7f86-c7af-4fce-83a6-58e853a93581)

- 在绑定层级中，添加绑定对象；
- 在绑定对象上添加对应绑定组件；
- 在绑定组件上设置对应控制器和动画骨骼对象；

  ![image](https://github.com/user-attachments/assets/75d1c980-e59e-4ea6-adb9-c66d601297e3)

- 在程序中通过程序代码操作控制器，从而控制蒙皮动画的骨骼；
- 最终通过权重，是程序操作的动画和蒙皮动画混合播放。
