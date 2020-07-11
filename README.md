# Looking Glass projects/obj_show

## 用途/Feature

在looking glass中显示带有texture的.obj的3d模型。

Show a `.obj` file with texture in the looking glass.

## 用法/Usage

1. 将使用的texture`.png`文件和`.obj`放在`./program/test`文件夹中，并重命名为`0.png`和`0.obj`
2. 运行`./program/run.bat`启动程序
3. 用鼠标左键拖曳旋转，用鼠标右键拖曳上下移动，用鼠标滚轮调节远近

1. Place the used texture `.png' and `.obj' files in the `.../program/test' folder and rename them `0.png' and `0.obj'. /program/test` folder and rename them `0.png` and `0.obj`
2. Run the `. /program/run.bat `Start-up program
3. drag and rotate with left mouse button, drag and move up and down with right mouse button, adjust the distance with the mouse wheel

## 更多设置/advanced

参照`./program/config.xml`

| 属性名称/setting name | 设置解释/explanation                                       | 默认值/default |
| --------------------- | ---------------------------------------------------------- | -------------- |
| DepthNear             | 设定深度最小值/depth min                                   | 1              |
| DepthFar              | 设定深度最大值/depth max                                   | 100            |
| CircleNormal          | 设定模型旋转及朝向/model rotation and orientation          | 0 1 0          |
| CircleRadius          | 设定视角与模型中心的初始距离/distance between model centre | 1.2            |
| InitialAngle          | 设定模型初始角度/model initial angle                       | 240            |
| SamplingAngle         | 设定模型旋转单位角度/model rotation unit angle             | 1.2            |

 