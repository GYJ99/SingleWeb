# 纯色页面工具

一个简单而优雅的纯色背景页面工具，可以帮助用户快速预览和选择颜色。

## 功能特点

- 🎨 实时颜色预览：通过颜色选择器或直接输入十六进制颜色值来更改背景色
- 🔄 双向同步：颜色选择器和输入框的值保持同步
- 👀 智能对比度：根据背景色亮度自动调整控制面板的显示样式
- 🎯 简洁界面：可隐藏控制面板，按ESC键显示
- 🌈 完整色彩：支持全部十六进制颜色值

## 使用说明

1. 打开页面后，您可以通过以下方式选择颜色：

   - 使用颜色选择器直接选择颜色
   - 在输入框中输入十六进制颜色值（例如：#FF0000）
2. 界面控制：

   - 点击"隐藏面板"按钮可以隐藏控制面板
   - 按ESC键可以重新显示控制面板
   - 当背景色较深时，控制面板会自动切换为深色模式

## 技术实现

### 核心功能

- 使用HTML5的color input实现颜色选择器
- 使用JavaScript实现颜色值的实时更新和验证
- 使用CSS3实现平滑的过渡动画效果
- 采用亮度计算公式自适应控制面板样式

### 亮度计算

使用以下公式计算颜色的亮度值：

```javascript
brightness = (R * 299 + G * 587 + B * 114) / 1000
```

### 响应式设计

- 采用flex布局确保在各种屏幕尺寸下的良好显示效果
- 使用viewport meta标签确保移动设备上的正确缩放
- 控制面板使用fixed定位，确保始终可见

## 浏览器兼容性

支持所有现代浏览器：

- Chrome
- Firefox
- Safari
- Edge

## 本地运行

1. 克隆或下载项目文件
2. 直接在浏览器中打开index.html文件
3. 开始使用纯色页面工具

## 开发计划

- [ ] 添加颜色预设功能
- [ ] 支持RGB和HSL颜色格式
- [ ] 添加颜色历史记录
- [ ] 支持渐变色背景
- [ ] 添加颜色复制功能

## 贡献

欢迎提交问题和改进建议！如果您有任何想法，请随时提出。

## 许可证

本项目采用MIT许可证。您可以自由使用、修改和分发本项目。
