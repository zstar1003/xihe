# 贡献指南 Contributing Guide

感谢您对羲和项目的关注！我们欢迎任何形式的贡献。

## 🤝 如何贡献

### 报告 Bug

如果您发现了 bug，请[创建一个 Issue](https://github.com/zstar1003/Flutter_build_ios_test/issues/new) 并包含以下信息：

- 📱 设备信息（型号、操作系统版本）
- 🐛 Bug 描述（详细说明问题）
- 🔄 复现步骤（如何触发这个 bug）
- 📸 截图或录屏（如果可能）
- 💡 期望的行为

### 提出功能建议

我们欢迎新功能的想法！请[创建 Issue](https://github.com/zstar1003/Flutter_build_ios_test/issues/new) 并说明：

- 🎯 功能描述
- 💭 使用场景
- 🎨 UI/UX 设计建议（如果有）

### 提交代码

1. **Fork 仓库**
   ```bash
   # 在 GitHub 上点击 Fork 按钮
   ```

2. **克隆到本地**
   ```bash
   git clone https://github.com/你的用户名/Flutter_build_ios_test.git
   cd Flutter_build_ios_test
   ```

3. **创建分支**
   ```bash
   git checkout -b feature/amazing-feature
   # 或
   git checkout -b fix/bug-fix
   ```

4. **进行开发**
   ```bash
   # 安装依赖
   flutter pub get

   # 运行应用
   flutter run

   # 运行测试
   flutter test
   ```

5. **提交更改**
   ```bash
   git add .
   git commit -m "feat: add amazing feature"
   ```

6. **推送分支**
   ```bash
   git push origin feature/amazing-feature
   ```

7. **创建 Pull Request**
   - 在 GitHub 上打开你的 fork
   - 点击 "New Pull Request"
   - 填写 PR 描述

## 📝 代码规范

### Commit 信息格式

我们使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <subject>

<body>

<footer>
```

**类型 (type)**:
- `feat`: 新功能
- `fix`: Bug 修复
- `docs`: 文档更新
- `style`: 代码格式（不影响功能）
- `refactor`: 代码重构
- `perf`: 性能优化
- `test`: 测试相关
- `chore`: 构建/工具链相关

**示例**:
```bash
feat(ui): 添加深色模式支持
fix(api): 修复诗词加载失败的问题
docs(readme): 更新安装说明
```

### Dart 代码规范

遵循 [Effective Dart](https://dart.dev/guides/language/effective-dart) 规范：

- 使用 `flutter analyze` 检查代码
- 使用 `flutter format` 格式化代码
- 添加必要的注释和文档
- 保持代码简洁易读

### 项目结构

```
lib/
├── main.dart           # 应用入口
├── models/             # 数据模型
├── providers/          # 状态管理
├── screens/            # 页面
├── services/           # 服务层
├── theme/              # 主题配置
└── widgets/            # 自定义组件
```

## 🧪 测试

在提交 PR 之前，请确保：

- [ ] 代码通过 `flutter analyze`
- [ ] 代码已使用 `flutter format` 格式化
- [ ] 在 iOS 和 Android 上测试通过
- [ ] 添加了必要的单元测试
- [ ] 更新了相关文档

## 📖 文档

如果您的更改涉及到：

- 新功能 → 更新 README.md
- API 变更 → 更新文档注释
- 配置变更 → 更新安装说明

## 🎨 设计资源

如果您想贡献设计：

- 应用图标应为 1024x1024 px
- 背景图片建议 1920x1080 px
- 保持简约优雅的设计风格
- 符合诗词文化氛围

## 💡 开发建议

### 推荐的开发工具

- **IDE**: VS Code / Android Studio
- **插件**: Flutter、Dart、GitLens
- **调试**: Flutter DevTools

### 性能优化

- 避免不必要的 Widget 重建
- 使用 `const` 构造函数
- 合理使用缓存
- 优化图片资源

### 国际化

如果添加新文本：
- 考虑多语言支持
- 使用语义化的键名

## ❓ 问题解答

### 如何运行项目？

```bash
flutter pub get
flutter run
```

### 如何构建发布版本？

```bash
# Android
flutter build apk --release

# iOS
flutter build ios --release
```

### 遇到依赖问题怎么办？

```bash
flutter clean
flutter pub get
```

## 📞 联系方式

如有任何疑问，欢迎通过以下方式联系：

- 📧 Email: zstar1003@163.com
- 💬 GitHub Issues: [创建 Issue](https://github.com/zstar1003/Flutter_build_ios_test/issues)
- 🌟 GitHub: [@zstar1003](https://github.com/zstar1003)

## 🙏 感谢

感谢所有为羲和项目做出贡献的开发者！

您的每一个 PR、Issue、Star 都是对我们最大的支持！

---

**让我们一起让羲和变得更好！** 🎉
