# 原生 JavaScript 待办清单

一个只使用 HTML、CSS 和 JavaScript 制作的小型待办清单，无需框架、后端或安装依赖。

## 功能

- 添加待办事项，并阻止添加空白内容
- 勾选完成或取消完成
- 删除事项
- 筛选全部、未完成、已完成事项
- 使用浏览器 `localStorage` 保存数据，刷新后仍可查看

## 运行方式

下载仓库后，直接用浏览器打开 `index.html` 即可。数据保存在当前浏览器中，不会上传到服务器。

## 用到的基础知识

- **HTML**：语义化结构、表单、按钮和列表
- **CSS**：Flexbox 布局、响应式样式与交互状态
- **JavaScript**：DOM 创建与更新、事件监听、数组操作、条件判断、`localStorage` 与 JSON

## 项目文件

- `index.html`：页面结构
- `style.css`：视觉样式
- `script.js`：待办清单逻辑
