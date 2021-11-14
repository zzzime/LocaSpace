 ## VS2019 项目的创建
1，打开Microsoft Visual Studio 2017选择新建Windows Form Application。
 选择.NET FrameWork。名称为HelloWord  

 ![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IelCHf.png)  


2， 把【LSV-DotNet-SDK】文件夹下所有文件拷贝到项目的【Debug】或者【Release】文件夹中。

（Debug/Release路径：HelloWord->bin->Debuy/Release)  

![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IelECQ.png)  


3,  在项目管理器的“ 引用”处右击，选择“添加引用”，然后浏览到Debug文件夹，选择GSGlobeDotNet.dll和GSToolTipDotNet.dll。其中GSGlobeDotNet.dll是核心的assembly，包含了核心的类库和三维控件。GSToolTipDotNet.dll提供了和三维控件一起使用的气泡控件，可以方便的在三维场景中显示文本、图片、表格等信息。

![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IelKbV.png)  
![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/Ielab6.png)  


4, 右击解决方案，点击属性，更改平台目标为x64，输出路径在Debug或Release文件夹当中。

![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/Ielha8.png)  
![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IeloGQ.png) 
![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IelbMn.png) 
## 加载球
现在，开发的基础环境已经搭建好了。现在可以使用LocaSpace SDK进行二次开发了。首先在Form1.cs中导入命名空间，加载三维球。  

`using GeoScene.Globe;`  

 `GSOGlobeControl globeControl1;`  (添加到  public partial class Form1 : Form中)
```C#
 public Form1()
        {
            InitializeComponent();
           //添加球
           globeControl1 = new GSOGlobeControl();
           this.Controls.Add(globeControl1);
           globeControl1.Dock = DockStyle.Fill;
       }
```

注意：`private void Form1_Load(object sender, EventArgs e)` 不要删除

6，点击F5运行可以看到如下的页面。

![RUNOOB 图标](https://z3.ax1x.com/2021/11/04/IelLq0.png)  



       


