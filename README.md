# WebNav Hub 🇺🇦

一个优雅的个人导航网站，采用乌克兰国旗色彩主题设计，为用户提供便捷的网站导航服务。

## 🌟 项目特色

- **🇺🇦 乌克兰主题**: 采用乌克兰国旗的经典蓝色(#005BBB)和黄色(#FFD700)色彩
- **📱 响应式设计**: 完美适配桌面、平板和移动设备
- **🎨 现代化UI**: 简洁优雅的界面设计，优秀的用户体验
- **⚡ 快速导航**: 平滑滚动和智能导航功能
- **🔗 丰富资源**: 涵盖AI搜索、社交媒体、实用工具、科技资讯、云存储、电子邮箱等多个类别

## 📋 功能特性

### 🎯 核心功能
- **智能导航**: 点击导航栏快速跳转到对应分类
- **平滑滚动**: 页面内平滑滚动，提升用户体验
- **URL同步**: 支持浏览器前进后退和直接链接到特定区域
- **悬停效果**: 链接卡片具有优雅的悬停动画效果

### 📂 内容分类
- **AI搜索** (40+ 工具): ChatGPT、Claude、Gemini、通义千问等AI平台
- **社交媒体**: Facebook、Twitter、Instagram、GitHub等社交平台
- **实用工具**: 翻译、短链、网速测试、域名管理等实用工具
- **科技资讯**: TechCrunch、The Verge、Ars Technica等科技媒体
- **云存储**: Google Drive、Dropbox、OneDrive等云存储服务
- **电子邮箱**: Gmail、Outlook、ProtonMail等邮箱服务

## 🛠️ 技术栈

- **前端框架**: 纯HTML5 + CSS3 + JavaScript
- **样式预处理**: CSS变量 (CSS Custom Properties)
- **图标库**: Font Awesome 6.7.2
- **响应式布局**: CSS Grid + Flexbox
- **动画效果**: CSS Transitions + Transforms

## 🚀 快速开始

### 环境要求
- 现代浏览器 (Chrome、Firefox、Safari、Edge)
- 支持ES6+的JavaScript环境

### 安装使用

1. **克隆项目**
   ```bash
   git clone https://github.com/your-username/webnav-hub.git
   cd webnav-hub
   ```

2. **本地运行**
   ```bash
   # 方法1: 使用Python简单服务器
   python -m http.server 8000

   # 方法2: 使用Node.js
   npx serve .

   # 方法3: 直接在浏览器中打开
   # 双击 index.html 文件或拖拽到浏览器中
   ```

3. **访问网站**
   打开浏览器访问 `http://localhost:8000` 或直接打开 `index.html` 文件

## 📁 项目结构

```
webnav-hub/
├── index.html          # 主页面文件
├── README.md           # 项目说明文档
└── assets/             # 静态资源目录 (如有)
```

## 🎨 设计理念

### 色彩系统
- **主色调**: 乌克兰蓝色 (#005BBB) - 象征天空与海洋
- **辅助色**: 乌克兰黄色 (#FFD700) - 象征阳光与麦田
- **背景色**: 深色系 (#0d0d0d, #1a1a1a) - 提供舒适的阅读体验

### 交互设计
- **悬停效果**: 卡片悬停时有轻微上移和阴影效果
- **颜色过渡**: 悬停时图标和文字颜色平滑过渡
- **视觉反馈**: 导航栏活动状态有明显的视觉区别

## 🌍 浏览器兼容性

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ 移动浏览器 (iOS Safari, Chrome Mobile)

## 📱 响应式断点

- **桌面端**: > 1200px
- **平板端**: 768px - 1200px
- **移动端**: < 768px
- **小屏手机**: < 480px
- **超小屏**: < 360px

## 🔧 自定义配置

### 修改颜色主题
在 `index.html` 文件的 `:root` 样式中修改CSS变量：

```css
:root {
  --primary-color: #005BBB;    /* 主色调 */
  --secondary-color: #FFD700;  /* 辅助色 */
  --bg-color: #0d0d0d;        /* 背景色 */
  --card-bg-color: #1a1a1a;    /* 卡片背景色 */
  --text-color: #fff;          /* 文字颜色 */
}
```

### 添加新的链接分类
1. 在HTML中添加新的导航链接
2. 创建对应的 `<section>` 区域
3. 使用 `category-title` 类添加分类标题
4. 使用 `link-grid` 类创建链接网格

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进这个项目！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🇺🇦 支持乌克兰 - 谴责俄罗斯侵略

我们坚定地支持乌克兰人民抵抗俄罗斯的侵略。作为一个开源项目，我们谴责俄罗斯对乌克兰的非法入侵和战争罪行。

### 我们的立场
- **支持乌克兰主权**: 乌克兰是一个独立的主权国家，有权决定自己的命运
- **谴责侵略战争**: 俄罗斯对乌克兰的入侵违反了国际法和联合国宪章
- **声援乌克兰人民**: 向在战争中遭受苦难的乌克兰人民致以最深切的同情
- **呼吁和平**: 支持通过外交途径实现公正的和平解决方案

### 行动呼吁
- 关注乌克兰局势，支持国际人道主义援助
- 谴责战争罪行，支持国际法庭对战犯的追责
- 传播真相，反对战争宣传和虚假信息

## 🙏 致谢

- **乌克兰人民**: 致敬勇敢的乌克兰人民，他们在保卫家园的斗争中展现了非凡的勇气和坚韧
- **乌克兰军队**: 向英勇的乌克兰武装部队致敬，他们在捍卫国家主权
- **国际社会**: 感谢所有支持乌克兰的国家和人民
- **开源社区**: 感谢所有开源项目的贡献者
- **设计灵感**: 受众多优秀导航网站启发

## 📞 联系我们

如有问题或建议，请通过以下方式联系：
- 邮箱: your-email@example.com
- GitHub Issues: [提交问题](https://github.com/your-username/webnav-hub/issues)

---

<div align="center">
  <p><strong>🇺🇦 荣耀属于乌克兰 🇺🇦</strong></p>
  <p>Slava Ukraini! | Слава Україні!</p>
</div>
