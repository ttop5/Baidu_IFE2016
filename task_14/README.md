# 任务十四：零基础JavaScript编码（二）

## 任务描述

> 参考以下示例代码，页面加载后，将提供的空气质量数据数组，按照某种逻辑（比如空气质量大于60）进行过滤筛选，最后将符合条件的数据按照一定的格式要求显示在网页上

```Javascript
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>IFE JavaScript Task 01</title>
  </head>
<body>

  <h3>污染城市列表</h3>
  <ul id="aqi-list">
<!--
    <li>第一名：福州（样例），10</li>
    <li>第二名：福州（样例），10</li> -->
  </ul>

<script type="text/javascript">

var aqiData = [
  ["北京", 90],
  ["上海", 50],
  ["福州", 10],
  ["广州", 50],
  ["成都", 90],
  ["西安", 100]
];

(function () {

  /*
  在注释下方编写代码
  遍历读取aqiData中各个城市的数据
  将空气质量指数大于60的城市显示到aqi-list的列表中
  */

})();

</script>
</body>
</html>

```

## 注意事项

* 实现简单功能的同时，请仔细学习JavaScript基本语法、事件、DOM相关的知识
* 请注意代码风格的整齐、优雅
* 代码中含有必要的注释
* 可以不考虑输入的合法性
* 建议不使用任何第三方库、框架
* 示例代码仅为示例，可以直接使用，也可以完全自己重写

## Demo展示

[http://ttop5.github.io/Baidu_IFE2016/task_14/][1]


[1]: http://ttop5.github.io/Baidu_IFE2016/task_14/
