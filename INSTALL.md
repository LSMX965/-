# SpeakFlow PWA 安装指南

## iPhone 安装步骤

### 方法一：Safari 浏览器安装（推荐）

1. **打开 Safari 浏览器**
   - 在 iPhone 上打开 Safari 浏览器

2. **访问网页**
   - 访问部署后的 SpeakFlow 应用网址
   - 例如：`https://your-username.github.io/speakflow/`

3. **添加到主屏幕**
   - 点击 Safari 底部的 **分享按钮**（方形框+向上箭头）
   - 向下滑动找到 **"添加到主屏幕"**
   - 点击并确认

4. **完成！**
   - 返回主屏幕，找到 SpeakFlow 图标
   - 点击即可打开使用

---

## 部署到 GitHub Pages（免费）

1. **上传文件**
   - 将以下文件上传到 GitHub 仓库：
     - `speakflow.html`
     - `manifest.json`
     - `sw.js`

2. **启用 GitHub Pages**
   - 进入仓库设置 → Pages
   - Source 选择 `main branch`
   - 保存

3. **获取访问链接**
   - 等待几分钟后访问：`https://你的用户名.github.io/仓库名/speakflow.html`

---

## 文件说明

| 文件 | 说明 |
|------|------|
| speakflow.html | 主应用文件 |
| manifest.json | PWA 配置文件 |
| sw.js | Service Worker（离线功能） |

---

## 使用方法

1. 打开应用
2. 在文本框输入或粘贴英文文章
3. 设置语速和练习模式
4. 点击"开始练习"
5. 跟随 AI 朗读，或点击麦克风跟读对比

---

## 注意事项

- **推荐使用 Safari**（iOS 对 PWA 支持最好）
- 需要麦克风权限才能使用跟读功能
- 首次使用需要联网加载语音资源
- 支持离线缓存，后续可离线使用
