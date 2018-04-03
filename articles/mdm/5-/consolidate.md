# 主数据排重

主数据排重包括查重规则、排重合并和合并任务。在“查重规则”节点进行自动排重任务生成，在“排重合并”节点进行手动排重和合并，在“合并任务”节点显示手动排重合并和自动排重的任务列表。排重仅适用于主数据，不涉及物料主数据。

## 查重规则

查重规则是对数据自动查重时所遵循的规则。点击【主数据排重】→【查重规则】，进入查重规则页面，此页面可进行查重规则的新增、修改、删除，排重数据准备和启动排重等操作。设置查重规则后，启动排重，系统自动生成排重任务，在“合并任务”节点显示，由管理员进行排重。

![](/articles/mdm/5-/images/image53.png)
 
<p align="center">图：查重规则</p>

 

➢ 新增

选择左侧主数据，单击〖新增〗，弹出窗口，填写内容后，点击〖确定〗。

![](/articles/mdm/5-/images/image54.png)
 
<p align="center">图：新增</p>
 

➢ 修改

选择主数据记录，单击〖修改〗按钮，弹出窗口，填写内容后点击〖确定〗。

![](/articles/mdm/5-/images/image55.png)
 
<p align="center">图：修改</p>
 

➢ 删除

选择一行主数据，单击〖删除〗按钮，弹出确认提示。

➢ 排重数据准备

单击〖排重数据准备〗按钮，完成排重数据准备。

![](/articles/mdm/5-/images/image56.png)
 
<p align="center">图：排重数据准备</p>
 

查重算法包括精确和模糊。精确算法包括：完全匹配、简繁匹配、全半角匹配和同音匹配。

主数据中设置的查重规则包括简繁、全半角或同音匹配时，需要首先对查重规则执行“排重数据准备”，然后执行查重。
完全匹配和模糊匹配不需要执行“排重数据准备”，直接启动排重。

➢ 启动排重

单击〖启动排重〗按钮，弹出如下窗口：

![](/articles/mdm/5-/images/image57.png)
 
<p align="center">图：启动排重</p>
 

## 排重合并

点击【主数据排重】→【排重合并】，进入排重合并页面，如下图所示：

![](/articles/mdm/5-/images/image58.png)
 
<p align="center">图：排重合并</p>
 

单击主数据右侧![](/articles/mdm/5-/images/image59.png)按钮，选择主数据，然后按〖确定〗。

单击〖高级查询〗，选择待选条件，单击〖选择〗，然后按〖确定〗。

![](/articles/mdm/5-/images/image60.png)
 
<p align="center">图：高级查询</p>
 

页面右侧显示查询结果。

双击选择某条主数据，至少选择两条主数据进行合并，单击〖合并〗按钮。单击〖移除〗，移除的数据不参与排重和合并。

![](/articles/mdm/5-/images/image61.png)
 
<p align="center">图：合并和排重</p>
 

手动排重时，根据属性，选择“主数据合并”进行合并，或者选择“主数据排重”排除重复数据。

## 合并任务

显示手动排重合并和自动排重的任务列表。点击【主数据排重】→【合并任务】，进入合并任务页面，左边是查询选择框，右边是查询结果。

![](/articles/mdm/5-/images/image62.png)
 
<p align="center">图：合并任务</p>
 

主数据：点击主数据右侧分类按钮，选择主数据。

处理状态：点击处理状态右侧下拉按钮，选择处理状态。

点击〖查询〗按钮进行查询，查询结果在页面右侧显示。