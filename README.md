# 我的项目

这是一个使用Node.js和Express构建的示例项目，展示了如何创建和部署到GitHub。

## 功能特性

- 🚀 基于Express的Web服务器
- 📱 响应式前端界面
- 🔧 RESTful API接口
- 📊 健康检查端点

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动项目

```bash
# 开发模式
npm run dev

# 生产模式
npm start
```

### 访问应用

打开浏览器访问: http://localhost:3000

## API接口

- `GET /` - 获取欢迎信息
- `GET /api/health` - 健康检查

## 项目结构

```
├── index.js          # 主服务器文件
├── package.json      # 项目配置
├── public/           # 静态文件
│   └── index.html   # 主页
└── README.md        # 项目文档
```

## 技术栈

- **后端**: Node.js, Express
- **前端**: HTML5, CSS3, JavaScript
- **部署**: GitHub

## 许可证

MIT License