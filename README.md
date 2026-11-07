# 立冬京华

立冬页面：照片 + 文案 + 柴可夫斯基《第一钢琴协奏曲》第一乐章（CC0 录音）。

## 文件

- `index.html` — 页面
- `bg.jpg` — 照片（1200×1600）
- `music.m4a` — 音乐（103 秒，AAC）

## 发布到 GitHub Pages

1. 在 GitHub 新建空仓库（不勾 README）
2. 在能连上 GitHub 的网络下运行：
   ```
   ./deploy.command https://github.com/<用户名>/<仓库名>.git
   ```
3. 仓库 Settings → Pages → Source: *Deploy from a branch*，Branch `main`，目录 `/ (root)`，Save
4. 约 1 分钟后访问 `https://<用户名>.github.io/<仓库名>/`

## 直接手动上传（手机/网页版也行）

GitHub 仓库页 → Add file → Upload files → 把 `index.html`、`bg.jpg`、`music.m4a` 三个一起拖进去 → Commit changes。
然后同上开 Pages。

## 音乐授权

Tchaikovsky — Piano Concerto No.1, Op.23, I. Allegro
录音来自 Wikimedia Commons，CC0（公有领域）。
https://commons.wikimedia.org/wiki/File:Tchaikovsky,_Concerto_No.1_in_B-flat_minor_Op.23,_I._Allegro.ogg
