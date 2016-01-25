# newline-echarts

###Introduce

许多人使用百度的echarts.js时候会出现数据名太长覆盖的情况，newline-echarts.js能够很好解决这种换行问题


###Usage

newline(option, 6, 'yAxis')
* 参数一：是你的option
* 参数二：是多少个字就换行
* 参数三：是x轴还是y轴 可选项 'yAxis' OR 'xAxis'

##Example
```
var chart = echarts.init(document.getElementById("main"));
<script src="js/echarts.js"></script>
var option = 
{
    # your options
}

option = newline(option, 6, 'yAxis')
chart.setOption(option)

```
