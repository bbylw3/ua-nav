# WebNav Hub 🇺🇦

<div align="center">
  <h2>🌍 多语言版本 / Multi-language / Багатомовна версія</h2>
  <p>
    <a href="#chinese">🇨🇳 中文</a> |
    <a href="#english">🇺🇸 English</a> |
    <a href="#ukrainian">🇺🇦 Українська</a>
  </p>
</div>

---

## 🇨🇳 中文 <a name="chinese"></a>

### WebNav Hub 🇺🇦

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

## 🇺🇸 English <a name="english"></a>

### WebNav Hub 🇺🇦

An elegant personal navigation website designed with Ukrainian flag color theme, providing convenient website navigation services for users.

## 🌟 Project Features

- **🇺🇦 Ukrainian Theme**: Using the classic blue (#005BBB) and yellow (#FFD700) colors of the Ukrainian flag
- **📱 Responsive Design**: Perfect adaptation for desktop, tablet and mobile devices
- **🎨 Modern UI**: Clean and elegant interface design with excellent user experience
- **⚡ Fast Navigation**: Smooth scrolling and intelligent navigation functions
- **🔗 Rich Resources**: Covering AI search, social media, utility tools, tech news, cloud storage, email and other categories

## 📋 Features

### 🎯 Core Functions
- **Smart Navigation**: Click navigation bar to quickly jump to corresponding categories
- **Smooth Scrolling**: Smooth scrolling within pages to enhance user experience
- **URL Synchronization**: Support browser forward/backward and direct links to specific areas
- **Hover Effects**: Link cards have elegant hover animation effects

### 📂 Content Categories
- **AI Search** (40+ tools): ChatGPT, Claude, Gemini, Tongyi Qianwen and other AI platforms
- **Social Media**: Facebook, Twitter, Instagram, GitHub and other social platforms
- **Utility Tools**: Translation, short links, network speed testing, domain management and other practical tools
- **Tech News**: TechCrunch, The Verge, Ars Technica and other technology media
- **Cloud Storage**: Google Drive, Dropbox, OneDrive and other cloud storage services
- **Email**: Gmail, Outlook, ProtonMail and other email services

## 🛠️ Tech Stack

- **Frontend Framework**: Pure HTML5 + CSS3 + JavaScript
- **Style Processing**: CSS Variables (CSS Custom Properties)
- **Icon Library**: Font Awesome 6.7.2
- **Responsive Layout**: CSS Grid + Flexbox
- **Animation Effects**: CSS Transitions + Transforms

## 🚀 Quick Start

### Environment Requirements
- Modern browsers (Chrome, Firefox, Safari, Edge)
- JavaScript environment supporting ES6+

### Installation and Usage

1. **Clone the project**
   ```bash
   git clone https://github.com/your-username/webnav-hub.git
   cd webnav-hub
   ```

2. **Run locally**
   ```bash
   # Method 1: Use Python simple server
   python -m http.server 8000

   # Method 2: Use Node.js
   npx serve .

   # Method 3: Open directly in browser
   # Double-click index.html file or drag it into browser
   ```

3. **Access the website**
   Open browser and visit `http://localhost:8000` or open `index.html` file directly

## 📁 Project Structure

```
webnav-hub/
├── index.html          # Main page file
├── README.md           # Project documentation
└── assets/             # Static resource directory (if any)
```

## 🎨 Design Philosophy

### Color System
- **Primary Color**: Ukrainian Blue (#005BBB) - Symbolizing sky and ocean
- **Secondary Color**: Ukrainian Yellow (#FFD700) - Symbolizing sunshine and wheat fields
- **Background Color**: Dark colors (#0d0d0d, #1a1a1a) - Providing comfortable reading experience

### Interaction Design
- **Hover Effects**: Cards have slight upward movement and shadow effects when hovered
- **Color Transition**: Smooth color transition for icons and text when hovered
- **Visual Feedback**: Navigation bar active state has obvious visual distinction

## 🌍 Browser Compatibility

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: > 1200px
- **Tablet**: 768px - 1200px
- **Mobile**: < 768px
- **Small Phone**: < 480px
- **Ultra Small**: < 360px

## 🔧 Customization

### Modify Color Theme
Modify CSS variables in the `:root` style of `index.html` file:

```css
:root {
  --primary-color: #005BBB;    /* Primary color */
  --secondary-color: #FFD700;  /* Secondary color */
  --bg-color: #0d0d0d;        /* Background color */
  --card-bg-color: #1a1a1a;    /* Card background color */
  --text-color: #fff;          /* Text color */
}
```

### Add New Link Categories
1. Add new navigation links in HTML
2. Create corresponding `<section>` area
3. Use `category-title` class to add category title
4. Use `link-grid` class to create link grid

## 🤝 Contribution Guidelines

Welcome to submit Issues and Pull Requests to improve this project!

1. Fork this repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project uses MIT License - see [LICENSE](LICENSE) file for details

## 🇺🇦 Support Ukraine - Condemn Russian Aggression

We firmly support the Ukrainian people in resisting Russian aggression. As an open source project, we condemn Russia's illegal invasion of Ukraine and war crimes.

### Our Position
- **Support Ukrainian Sovereignty**: Ukraine is an independent sovereign state with the right to determine its own destiny
- **Condemn Aggressive War**: Russia's invasion of Ukraine violates international law and the UN Charter
- **Support Ukrainian People**: Express deepest sympathy to Ukrainian people suffering from war
- **Call for Peace**: Support achieving fair peace solutions through diplomatic channels

### Call to Action
- Follow Ukrainian situation, support international humanitarian aid
- Condemn war crimes, support international tribunals holding war criminals accountable
- Spread truth, oppose war propaganda and disinformation

## 🙏 Acknowledgments

- **Ukrainian People**: Honor the brave Ukrainian people who show extraordinary courage and resilience in defending their homeland
- **Ukrainian Army**: Honor the heroic Ukrainian armed forces defending national sovereignty
- **International Community**: Thank all countries and people supporting Ukraine
- **Open Source Community**: Thank all contributors to open source projects
- **Design Inspiration**: Inspired by many excellent navigation websites

## 📞 Contact Us

If you have any questions or suggestions, please contact us through:
- Email: your-email@example.com
- GitHub Issues: [Submit Issue](https://github.com/your-username/webnav-hub/issues)

---

## 🇺🇦 Ukrainian <a name="ukrainian"></a>

### WebNav Hub 🇺🇦

Елегантний особистий сайт навігації, розроблений з використанням кольорів прапора України, що надає зручні послуги навігації веб-сайтами для користувачів.

## 🌟 Особливості проекту

- **🇺🇦 Українська тема**: Використання класичного синього (#005BBB) та жовтого (#FFD700) кольорів українського прапора
- **📱 Адаптивний дизайн**: Ідеальна адаптація для настільних ПК, планшетів та мобільних пристроїв
- **🎨 Сучасний інтерфейс**: Чистий та елегантний дизайн інтерфейсу з відмінним користувацьким досвідом
- **⚡ Швидка навігація**: Плавна прокрутка та функції інтелектуальної навігації
- **🔗 Багаті ресурси**: Охоплює AI-пошук, соціальні мережі, утиліти, технологічні новини, хмарне сховище, електронну пошту та інші категорії

## 📋 Характеристики

### 🎯 Основні функції
- **Інтелектуальна навігація**: Клацніть панель навігації для швидкого переходу до відповідних категорій
- **Плавна прокрутка**: Плавна прокрутка всередині сторінок для покращення користувацького досвіду
- **Синхронізація URL**: Підтримка переходу вперед/назад у браузері та прямі посилання на конкретні області
- **Ефекти наведення**: Картки посилань мають елегантні анімаційні ефекти наведення

### 📂 Категорії вмісту
- **AI-пошук** (40+ інструментів): ChatGPT, Claude, Gemini, Tongyi Qianwen та інші AI-платформи
- **Соціальні мережі**: Facebook, Twitter, Instagram, GitHub та інші соціальні платформи
- **Утиліти**: Переклад, короткі посилання, тестування швидкості мережі, управління доменами та інші практичні інструменти
- **Технологічні новини**: TechCrunch, The Verge, Ars Technica та інші технологічні ЗМІ
- **Хмарне сховище**: Google Drive, Dropbox, OneDrive та інші служби хмарного сховища
- **Електронна пошта**: Gmail, Outlook, ProtonMail та інші служби електронної пошти

## 🛠️ Технологічний стек

- **Фронтенд фреймворк**: Чистий HTML5 + CSS3 + JavaScript
- **Обробка стилів**: CSS Змінні (CSS Custom Properties)
- **Бібліотека іконок**: Font Awesome 6.7.2
- **Адаптивна верстка**: CSS Grid + Flexbox
- **Анімаційні ефекти**: CSS Transitions + Transforms

## 🚀 Швидкий старт

### Вимоги до середовища
- Сучасні браузери (Chrome, Firefox, Safari, Edge)
- Середовище JavaScript з підтримкою ES6+

### Встановлення та використання

1. **Клонування проекту**
   ```bash
   git clone https://github.com/your-username/webnav-hub.git
   cd webnav-hub
   ```

2. **Локальний запуск**
   ```bash
   # Спосіб 1: Використання простого сервера Python
   python -m http.server 8000

   # Спосіб 2: Використання Node.js
   npx serve .

   # Спосіб 3: Відкрити безпосередньо в браузері
   # Подвійне клацання файлу index.html або перетягування в браузер
   ```

3. **Доступ до сайту**
   Відкрийте браузер та перейдіть на `http://localhost:8000` або відкрийте файл `index.html` безпосередньо

## 📁 Структура проекту

```
webnav-hub/
├── index.html          # Головний файл сторінки
├── README.md           # Документація проекту
└── assets/             # Каталог статичних ресурсів (якщо є)
```

## 🎨 Філософія дизайну

### Система кольорів
- **Основний колір**: Український синій (#005BBB) - Символізує небо та океан
- **Допоміжний колір**: Український жовтий (#FFD700) - Символізує сонце та поля пшениці
- **Колір фону**: Темні кольори (#0d0d0d, #1a1a1a) - Забезпечують комфортний досвід читання

### Дизайн взаємодії
- **Ефекти наведення**: Картки мають легкий рух вгору та ефекти тіні при наведенні
- **Перехід кольорів**: Плавний перехід кольорів для іконок та тексту при наведенні
- **Візуальний зворотній зв'язок**: Активний стан панелі навігації має очевидну візуальну відмінність

## 🌍 Сумісність браузерів

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Мобільні браузери (iOS Safari, Chrome Mobile)

## 📱 Адаптивні точки перелому

- **Настільний ПК**: > 1200px
- **Планшет**: 768px - 1200px
- **Мобільний**: < 768px
- **Малий телефон**: < 480px
- **Надмалий**: < 360px

## 🔧 Налаштування

### Зміна кольорової теми
Змініть CSS змінні в стилі `:root` файлу `index.html`:

```css
:root {
  --primary-color: #005BBB;    /* Основний колір */
  --secondary-color: #FFD700;  /* Допоміжний колір */
  --bg-color: #0d0d0d;        /* Колір фону */
  --card-bg-color: #1a1a1a;    /* Колір фону картки */
  --text-color: #fff;          /* Колір тексту */
}
```

### Додавання нових категорій посилань
1. Додайте нові навігаційні посилання в HTML
2. Створіть відповідну область `<section>`
3. Використовуйте клас `category-title` для додавання заголовка категорії
4. Використовуйте клас `link-grid` для створення сітки посилань

## 🤝 Настанови щодо внеску

Ласкаво просимо надсилати Issues та Pull Requests для покращення цього проекту!

1. Форкніть це сховище
2. Створіть гілку функції (`git checkout -b feature/AmazingFeature`)
3. Здійсніть коміт змін (`git commit -m 'Add some AmazingFeature'`)
4. Відправте в гілку (`git push origin feature/AmazingFeature`)
5. Відкрийте Pull Request

## 📄 Ліцензія

Цей проект використовує ліцензію MIT - дивіться файл [LICENSE](LICENSE) для деталей

## 🇺🇦 Підтримка України - Засудження російської агресії

Ми твердо підтримуємо український народ у опорі російській агресії. Як проект з відкритим кодом, ми засуджуємо незаконне вторгнення Росії в Україну та воєнні злочини.

### Наша позиція
- **Підтримка українського суверенітету**: Україна є незалежною суверенною державою з правом визначати свою долю
- **Засудження агресивної війни**: Вторгнення Росії в Україну порушує міжнародне право та Статут ООН
- **Підтримка українського народу**: Виражаємо найглибші співчуття українському народу, який страждає від війни
- **Заклик до миру**: Підтримуємо досягнення справедливих мирних рішень через дипломатичні канали

### Заклик до дії
- Слідкуйте за ситуацією в Україні, підтримуйте міжнародну гуманітарну допомогу
- Засуджуйте воєнні злочини, підтримуйте міжнародні трибунали у притягненні військових злочинців до відповідальності
- Поширюйте правду, протидійте воєнній пропаганді та дезінформації

## 🙏 Подяки

- **Український народ**: Вшановуємо хоробрий український народ, який проявляє надзвичайну мужність та витривалість у захисті своєї батьківщини
- **Українська армія**: Вшановуємо героїчні Збройні сили України, які захищають національний суверенітет
- **Міжнародна спільнота**: Дякуємо всім країнам та народам, які підтримують Україну
- **Спільнота відкритого коду**: Дякуємо всім учасникам проектів з відкритим кодом
- **Дизайнерське натхнення**: Натхненні багатьма відмінними сайтами навігації

## 📞 Зв'язатися з нами

Якщо у вас є запитання чи пропозиції, зв'яжіться з нами через:
- Email: your-email@example.com
- GitHub Issues: [Надіслати проблему](https://github.com/your-username/webnav-hub/issues)

---

<div align="center">
  <p><strong>🇺🇦 Слава Україні! 🇺🇦</strong></p>
  <p>Glory to Ukraine! | Слава Україні!</p>
</div>
