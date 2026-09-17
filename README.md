# 🦍 猩球力量日志 · Week 16 手机打卡应用

专为健身房极简触控与力量增肌追踪打造的 Web / PWA 单页应用。

## ✨ 特性
* **适配纯黑 OLED 界面**：弱光健身房低眩光、大触控面积，出汗手滑也不易误触。
* **完整挂载 Week 16 计划**：Day 1 至 Day 7 包含预填目标重量、组数、次数与力学提示。
* **微调步进器**：支持快速点击 `+ / -` 微调重量与次数。
* **组歇震动倒计时**：点击“完成”自动触发 90s 组间休息，倒计时结束触发震动与蜂鸣提醒。
* **一键复制汇报文本**：训练结束点击“复制今日训练手记”，生成与系统便签格式一致的纯文本，直接发回给 AI 复盘。
* **本地防丢保存**：自动实时保存在手机浏览器 LocalStorage 中，刷新或切换 App 不丢数据。

---

## 🚀 如何通过 GitHub Pages 免费上线（只需 2 分钟）

### 步骤 1：在 GitHub 上新建仓库
打开 [GitHub New Repository](https://github.com/new)，新建一个公开仓库（Repository Name 例如填 `workout` 或 `fitness`），选择 **Public**。

### 步骤 2：在本地初始化并推送到 GitHub
在本项目终端中依次执行以下命令（将其中的 `<你的GitHub用户名>` 和 `<仓库名>` 替换为实际值）：
```bash
git init
git add .
git commit -m "feat: initialize week 16 workout tracker"
git branch -M main
git remote add origin https://github.com/<你的GitHub用户名>/<仓库名>.git
git push -u origin main
```

### 步骤 3：开启 GitHub Pages 静态网站服务
1. 进入 GitHub 仓库页面，点击顶部的 **Settings**；
2. 在左侧边栏找到 **Pages**；
3. 在 **Build and deployment** 下方的 **Branch** 选择 `main`，文件夹保持 `/ (root)`，点击 **Save**；
4. 等待 1 分钟左右刷新页面，页面顶部即会显示你的专属网址：
   `https://<你的GitHub用户名>.github.io/<仓库名>/`

---

## 📱 手机端使用技巧（秒变独立 App）
1. 用手机自带浏览器（如 Chrome、Safari、夸克等）打开上述 GitHub Pages 网址；
2. 点击浏览器菜单按钮，选择 **“添加到主屏幕”**（或“添加到桌面”）；
3. 手机桌面即可生成专属图标，点开后为**全屏无地址栏**的独立 App 体验，离线也能秒开。
