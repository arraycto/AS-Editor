# AS-Editor

#### 介绍

基于 vue 可视化拖拽编辑，页面生成工具。提升前端开发效率，可集成至移动端项目作为通过定义 JSON 直接生成 UI 界面。


官网：[https://was666.gitee.io/as-editor-doc](https://was666.gitee.io/as-editor-doc)

在线体验：[http://www.aseditor.fun/](http://www.aseditor.fun/)

#### 安装教程

1.  npm install   （安装 node_modules 模块）
2.  npm run serve （运行）
3.  npm run build （打包）
4.  npm update     (用于更新包到基于规范范围的最新版本)

#### 使用说明

##### 使用教程

![步骤1](https://images.gitee.com/uploads/images/2021/1027/112917_5f4b400d_5546746.png 'image1.png')
![步骤2](https://images.gitee.com/uploads/images/2021/1027/112939_e466bef2_5546746.png 'image2.png')
![步骤3](https://images.gitee.com/uploads/images/2021/1027/112950_60be2a1a_5546746.png 'image3.png')
![步骤4](https://images.gitee.com/uploads/images/2021/1027/113000_117378e7_5546746.png 'image4.png')
![步骤5](https://images.gitee.com/uploads/images/2021/1101/173304_1e88f8bb_5546746.png "image5.png")
![步骤6](https://images.gitee.com/uploads/images/2021/1101/173318_fee90ec7_5546746.png "image6.png")

##### 自定义组件可以看：

```js
src / layout / home / index.vue                 // 编辑页面文件
src / components / sliderassembly / index.vue   // 左侧组件大全文件
src / components / componentscom                // 左侧组件目录
src / components / rightslider                  // 右侧组件目录
src / utils / componentProperties.js            // 组件数据
```

#### componentProperties（组件数据）字段注解

```js
{
  component: 'custommodule',    // 中间部分手机组件的name
  text: '自定义模块',            // 组件文字描述
  type: '1-14',                 // data-tpye
  active: true,                 // 是否选中
  style: 'custommodulestyle',   // 右边组件设置的name
  setStyle: {}                  // 组件动态数据
}
```

#### 扩展项目

AS-Editor-H5：[https://gitee.com/was666/as-editor-h5.git](https://gitee.com/was666/as-editor-h5.git)

AS-Editor-H5 是移动端 vue 模版，可以通过定义的 JSON 生成 vue 页面

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

#### 结尾

##### 如果喜欢的话给个 star 一下哈！

##### 如果有意见和问题 可以在 lssues 提出，我会在线解答。
