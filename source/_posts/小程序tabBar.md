# 小程序导航tabBar
  
  在app.json中添加以下代码：
  ```"tabBar": {
    "position":"top",
    "list": [{
      "pagePath": "pages/index/index",
      "text": "index"
    },{
      "pagePath": "pages/logs/logs",
      "text": "logs"
    }]
  }```

  其中position设置成top，将tabBar置于顶部，并不会有icon。
  list是一个数组，可设置最多五个最少两个Tab。