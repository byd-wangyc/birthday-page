# 图片放置说明

把你的图片放进 `assets/photos/` 目录：

- 顶部横幅（Hero）：将合照命名为 `hero.jpg` 放在 `assets/photos/hero.jpg`。
- 照片墙（Gallery）：把其它图片放到 `assets/photos/`，然后在 `index.html` 底部找到 `window.PHOTO_LIST`，把文件路径按示例填入：

```js
window.PHOTO_LIST = [
  'assets/photos/1.jpg',
  'assets/photos/trip.png',
  // ...
];
```

建议：
- 图片尽量压到 200KB-800KB 之间，JPG/WEBP 效果更好。
- 文件名尽量英文数字，避免空格和中文，以免路径大小写/编码问题。

上传到 GitHub 并启用 Pages 后，1 分钟左右就能在公开链接看到更新。

