# 凡石文化网站 - Vercel部署说明

## 文件结构
```
fanshi-culture/
├── index.html              # 主网站页面（原fanshi_culture_final.html）
├── admin.html              # 管理登录页面
├── README.md               # 本说明文件
└── vercel.json             # Vercel配置文件
```

## 部署步骤

### 方法1：通过Vercel CLI部署
1. 安装Vercel CLI：
   ```bash
   npm install -g vercel
   ```

2. 登录Vercel账号：
   ```bash
   vercel login
   ```

3. 进入项目目录并部署：
   ```bash
   cd fanshi-culture
   vercel
   ```

### 方法2：通过GitHub集成部署
1. 创建GitHub仓库并上传所有文件
2. 登录Vercel，导入GitHub仓库
3. 配置项目设置：
   - Framework Preset: Other
   - Build Command: 留空
   - Output Directory: 留空
4. 点击Deploy完成部署

## 管理功能说明

### 访问管理后台
1. 部署完成后访问：https://your-vercel-app.vercel.app/admin.html
2. 使用默认账号登录：
   - 用户名：admin
   - 密码：admin123

### 管理功能
- **内容管理**：修改网站所有文字和图片内容
- **客户留言**：查看和管理客户咨询信息
- **SEO设置**：配置网站SEO相关参数

## 注意事项

1. **数据存储**：网站使用localStorage存储数据，数据保存在用户浏览器中
2. **安全性**：管理功能仅在客户端运行，建议在生产环境中添加服务器端验证
3. **备份**：定期导出重要数据，避免浏览器数据丢失
4. **自定义**：可以根据需要修改颜色、文字、图片等内容

## 技术栈
- HTML5 + CSS3 + JavaScript
- Tailwind CSS v3
- Font Awesome（部分功能）
- 响应式设计

## 联系信息
- 网站邮箱：qiulibinxm@163.com
- 联系电话：16754983474
- 公司地址：北京市通州区北苑155号417