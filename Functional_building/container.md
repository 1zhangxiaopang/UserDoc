### 标签页配置  

#### 功能说明  

>通过使用标签页，您同时浏览多个页面，并轻松在这些标签页之间切换，无需打开多个窗口。

#### 功能搭建

* 第一步,进入系统管理中的系统功能，

![第一步](../image/sys/sys%20(1).png ':size=70%')

* 第二步，点新建功能或右键点击新增功能，开始配置标签页组件。

![第二步](../image/sys/sys%20(11).png ':size=70%')


* 第三步，先选择左侧样式，将样式拖至中间，后选中标签页拖至模板设计中间，再点中间小圆点回弹窗口。

![第三步](../image/sys/sys24.png ':size=70%')
>1. 拉取左侧模板，如果模板列表没有想要的模板可以新建一个自定义模板，参考<a href="#/Functional_building/Template">模板配置</a>   
>2. 点击下拉栏，查看各类型功能组件  
>3. 选择容器类，拖拽标签页组件到中间区域  

  

* 第四步，更改标签名，如果有标签选择再点+新增，所需配置组件，同样左侧拉取模板，顶部拉取组件，进行配置。

![第四步](../image/平台介绍/tab1.png ':size=70%')
>1. 点击标签名进行修改 
>2. 点击新增标签页  
>3. 对该标签页选择组件
>4. 勾选主功能后，方可选择菜单栏,注意标签页内的组件才可以勾选为主功能，空白标签页不能作为主功能

* 第五步，根据实际需求对标签页内组件进行组件明细，字段，菜单配置。
可参考其他组件配置，操作步骤相同。


### 引用组件配置  

#### 功能说明  

>如果您需要一条数据关联一张表格，而这个表格已经搭建完毕，有完整的工具栏和标题字段，您可以使用引用组件将该表格引用并关联，无需重新配置关联表格。

#### 功能搭建

* 第一步，根据实际需求点击鼠标拖出左侧模板，点中间的下拉栏，选中容器中引用组件下拉。

![第一步](../image/sys/ref1.png ':size=70%')

>1. 拉取左侧模板，如果模板列表没有想要的模板可以新建一个自定义模板，参考<a href="#/Functional_building/Template">模板配置</a>   
>2. 点击下拉栏，查看各类型功能组件  
>3. 选择容器类，拖拽引用组件到中间区域  
>注：引入组件不可作为主功能存在，本例中使用①表格作为主功能  

* 第二步，表格的详细配置可参考<a href="#/Functional_building/BasicData">基础数据栏</a>表格配置，本例主要说明表格与引用组件关联需要注意的细节，在①表格中配置组件关联时关联引用组件，并手动输入关联表的关联id。
  
![第二步](../image/sys/ref2.png ':size=70%')  

>1. 组件关联需在父组件中进行关联，此处①表格关联②引用组件  

>2. id为①表格的自身id  

>3. 无法选择目标字段，需手动输入目标字段  

* 第三步，①表字段配置时，需要选取标题字段作为描述字段 

![第三步](../image/sys/ref4.jpg ':size=70%')  


* 第四步，①表配置完毕，点击②引用组件进行配置，在引用功能中添加需要引用的功能组件，可添加多个  

     
![第四步](../image/sys/ref3.png ':size=70%') 
 
>1. 进入②引用组件功能配置 

>2. 功能名自动添加，无需手动添加   

>3. 引用功能配置需要关联的功能组件  

>4. 点击添加功能组件，可添加多个  

>5. 点击搜索需要关联功能组件，双击选入  

>6. 点击删除功能组件  

* 第五步，点击保存后Ctrl+F5刷新，进入系统功能界面找到关联功能组件，然后右键选择修改功能  

![第五步](../image/sys/ref6.png ':size=70%')  

>1. 在系统管理导航页面找到系统功能点击进入  

>2. 搜索关联功能组件   

>3. 引用功能配置需要关联的功能组件    

>4. 点击选中关联组件  

>5. 右键单击修改功能  

* 第六步，在多对一中选取我们保存的引用组件

![第六步](../image/sys/ref5.png ':size=70%')  

>1. 检查关联功能组件是否有关联id，若没有，选取master_bill_id主单id  

>2. 选取保存的引用组件  

* 第七步，点击保存后Ctrl+F5刷新，进入我们的引入功能组件，上表的标题对应下表的主单id，实现一条数据对应多个现有功能组件  

![第六步](../image/sys/ref7.png ':size=70%') 

>1. 此时表中无数据，点击新增添加数据  

>2. 上表的第一条数据对应下表