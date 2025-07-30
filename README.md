# 🔮 预测训练器 (Forecast Prediction Trainer)

一个帮助你记录预测、验证判断能力的思维实验工具。通过系统化地记录和跟踪预测结果，提升你的决策和判断能力。

## 🌟 功能特色

- **📝 预测记录** - 记录你对未来事件的预测
- **⏰ 截止日期管理** - 设置预测验证的时间点
- **🎯 信心值评估** - 量化你对预测的确信程度 (1-100%)
- **✅ 结果验证** - 在截止日期后验证预测是否准确
- **📊 能力统计** - 全面的预测能力分析面板
- **📱 响应式设计** - 完美适配桌面和移动设备

## 🚀 在线体验

访问 [https://dwaguan.github.io/forecast/](https://dwaguan.github.io/forecast/) 立即开始使用

## 📊 统计指标

应用提供四个核心指标来评估你的预测能力：

1. **总预测数** - 记录的预测总量
2. **成功率** - 已验证预测中成功的比例
3. **平均信心** - 所有预测的平均信心值
4. **校准指数** - 成功率与平均信心值的比值，衡量预测校准程度

### 校准指数解读
- **= 1.0** - 完美校准，信心值与实际准确率匹配
- **> 1.0** - 保守预测，实际表现超出预期
- **< 1.0** - 过度自信，需要调整信心评估

## 🛠️ 技术实现

- **纯前端应用** - HTML5 + CSS3 + Vanilla JavaScript
- **本地存储** - 使用 localStorage 保存数据
- **响应式设计** - CSS Grid + Flexbox
- **无依赖** - 不需要任何外部库或框架

## 📱 使用方法

### 1. 添加预测
1. 在"预测内容"框中描述你要预测的事件
2. 设置截止日期（验证预测的时间点）
3. 调整信心值滑块（1-100%）
4. 点击"保存预测"

### 2. 管理预测
- **未到期** - 等待截止日期到来
- **今日到期** - 需要今天验证的预测
- **已过期** - 可以验证结果的预测

### 3. 验证结果
在预测截止日期后，点击"预测成功"或"预测失败"来记录实际结果

### 4. 查看统计
在统计面板中查看你的预测能力分析

## 🎯 使用场景

- **个人成长** - 提升判断和决策能力
- **投资决策** - 记录市场预测和投资判断
- **项目管理** - 预测项目里程碑和风险
- **学习研究** - 验证假设和理论预测
- **日常生活** - 训练对各种事件的判断力

## 🔧 本地开发

### 直接运行
由于是纯静态页面，可以直接在浏览器中打开 `index.html` 文件

### 使用本地服务器
```bash
# 使用 Python 3
python -m http.server 8000

# 使用 Node.js
npx http-server

# 使用 PHP
php -S localhost:8000
```

然后访问 `http://localhost:8000`

## 📂 项目结构

```
forecast/
├── index.html          # 主页面文件
├── .github/
│   └── workflows/
│       └── jekyll-gh-pages.yml    # GitHub Pages 部署配置
└── README.md           # 项目说明文档
```

## 🚀 部署

项目使用 GitHub Actions 自动部署到 GitHub Pages：

1. 推送代码到 `main` 分支
2. GitHub Actions 自动触发构建
3. 部署到 `https://dwaguan.github.io/forecast/`

## 💾 数据说明

- **数据存储** - 使用浏览器 localStorage，数据保存在本地
- **数据安全** - 数据不会上传到服务器，完全本地化
- **数据备份** - 建议定期导出重要预测记录（未来版本将支持）

## 🔮 未来计划

- [ ] 数据导出/导入功能
- [ ] 预测分类和标签
- [ ] 图表可视化统计
- [ ] 更详细的校准分析
- [ ] 多语言支持
- [ ] 预测提醒功能
- [ ] 团队协作功能

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

### 贡献指南
1. Fork 项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

如有问题或建议，请通过以下方式联系：

- 创建 [GitHub Issue](https://github.com/dwaguan/forecast/issues)
- 项目主页：[https://github.com/dwaguan/forecast](https://github.com/dwaguan/forecast)

---

⭐ 如果这个项目对你有帮助，请给它一个星标！
