# 从 excel 批量导入
当您有成百上千个点位信息需要标注到地图中时，如果还用手工进行逐一标注，那工作量太大了。这时您就需要用到“批量添加数据”工具来进行批量标注, 

一、使用 Excel 格式的地址或名称数据生成地图

1.地址模板如下，地址为必填项

![](http://pic.dituwuyou.com/map%2Fpicture%2F10.31%2Faddress.jpg)

2.新建图层->批量添加数据->选择相应的excel文件->设置地址字段

![](http://pic.dituwuyou.com/map%2Fpicture%2F10.31%2Fimport-data2.jpg)

3.地址要求是正确详细的，如果解析时地址找不到或是不唯一，定位出来的点会显示为黑色。字段推荐使用详细地址，如果使用名称的时候，在“手动”列选择详细的省份和城市会大幅提升定位准确率。

![](http://pic.dituwuyou.com/map%2Fpicture%2F10.31%2Faddress2.jpg)

二、 使用 Excel 格式的经纬度数据生成地图

1.地址模板如下，经度和纬度为必填数据项

![](http://pic.dituwuyou.com/map%2Fpicture%2F10.31%2Flatlag.jpg)

2.新建图层->批量添加数据->选择相应的excel文件->设置经纬度及坐标系，完成即可，对话框中，红色*标识字段为必填字段

![](http://pic.dituwuyou.com/map%2Fpicture%2F10.31%2Flatlag2.jpg)
