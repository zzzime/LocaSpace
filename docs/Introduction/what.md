# LocaSpace SDK 介绍

## 1，概述
 LocaSpace 是一个专业的三维地理信息平台。它为公共事业单位、企业和科研机构提供功能强大、性能稳定和性价比高的三维地理信息解决方案。使用LocaSpace 三维GIS平台，用户能够轻松地创建、浏览、分析和发布三维地理信息数据。LocaSpace 还提供方便的二次开发接口。  

## 2，工作内容
用户可运用LocaSpace 完成以下工作：
* 加载高分辨率影像数据（DOM）
* 支持高精度地形数据（DEM）
* 支持真实地下三维场景
* 支持KML，Shapefile，3ds，vrml等数据格式
* 采用中间层接口设计，支持OpenGL和D3D
* 场景中支持各类几何体，例如：点，线，面，三维实体等 
* 三维场景中对象的空间位置的灵活控制 
* 海量的文字标注支持，小比例尺场景下文字标注有智能避让功能，可以定制标注的字体，大小等属性
* 方便的测量功能，在三维场景中精确测量平面距离，表面距离，高度，投影面积，表面积等
* 纵剖面分析功能，根据数字高程数据分析纵剖面
* 三维模型的编辑功能，可以直接在三维场景中编辑模型，例如移动模型的空间位置，缩放模型的大小，旋转模型等
* 模型的渐进加载，Geometry  framework和纹理的分离加载效果，模型的半透明的渐进加载效果
* 灵活控制视点，设定飞行轨迹，支持fly to, jump to, circle等预定义飞行模式	三维控件支持多种事件，可方便添加对应的事件处理
* 三维场景参数控制，可以根据具体客户机器的性能，控制系统运行速度和效果，调整三维渲染的参数设置，例如：反锯齿，分形，重采样等

## 3，技术参数
1. 支持海量地形、影像、模型、矢量、KML的渲染，支持多图层叠加显示，支持矢量图层设置颜色、形状等风格设置，支持统计图、专题图等；
2. 矢量支持Shapefile，GML，Autocad 的dwg、dxf; MapInfo的mif；KML等。
3. 栅格支持ArcGIS Grid数据，Erdas的img数据，USGS的DEM格式，支持Jpeg、png、Tiff、GIF、bmp、raw、jp2k等图片导入； 模型数据支持3ds、obj、.x、dae格式。
4. 支持Oracle、SQL Server、MySQL等数据库存储；
5. 支持天空、大气、雾、星空、火焰、雨、雪、风等离子效果、支持水、树木、路灯等虚拟小品构建；
6. 支持飞行、第一视角浏览、支持高精度出图、支持动画效果、支持AVI视频录制；
7. 支持空间查询和空间分析（量算、DEM分析，如：坡度、坡向、填挖方、计算土方量等）、洪水淹没演示、通视分析、可视域分析、雷达分析、剖面分析、扩散分析、噪声分析、光照分析等。
8. 支持矢量批量拉伸建模（面拉伸成体、线拉伸成管道或者公路或者墙面，点拉伸成柱子或者杆）；
9. 支持规则几何体编辑（在场景中可以直接放置球、立方体、柱体等规则几何体）、支持模型库（利用模型库可以指定某个模型为某个点图层的符号样式，达到快速构建场景的目的）、填充库（在编辑的时候可以用填充库指点某个模型某个面的填充风格）；
10. 系统运行速度，在GeForce6600上渲染10万面帧速可达60fps；





 [版权所有© 中科图新(苏州）科技有限公司。保留所有权利。](http://www.engine3d.com/about.html)