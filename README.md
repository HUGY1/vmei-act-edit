# vmei-act-edit
### 活动页可视化拖拽编辑生成

### 需求及步骤

1. 确定拖拽效果好的组件。编辑使用拖拽调整顺序（拖拽功能可以先放弃，通过组件上移下移替代）
2. 拖拽的单位是组件，对活动页每一个部分组件化。暂定使用vue及其组件
3. 组件及其配置 通过json格式进行上传
4. 后台通过json数据解析，拼凑成前端页面
5. 页面打包成可访问的html页面


### 目前暂定基础组件：  
1. 纯图片。高度自适应    
配置：上传图片
2. 图片一行2个链接。   
配置：链接类型，id，使用图片
3. 图片一行3个链接。   
配置：链接类型，id，使用图片
4. 倒计时组件。   
配置：文字，背景颜色，字体颜色，字体框框颜色
5. 商品列表。   
配置：美妆团id，商品排列列数，背景色。标题背景色，标题字体颜色
6. 规则按钮，及其滑动内页。   
配置：规则按钮图片，内页图片上传