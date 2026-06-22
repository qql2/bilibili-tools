# bilibili-tools

> B 站视频评论总结工具 — 基于 [MediaCrawler](https://github.com/qql2/MediaCrawler) 的薄桥接层。

## 快速开始

```bash
# 使用 MediaCrawler 抓取 B 站视频评论
python3 bilibili-comment-bridge.py BV199jJ6REJR

# 指定拉取条数
python3 bilibili-comment-bridge.py BV199jJ6REJR --count 120

# 从 URL 解析
python3 bilibili-comment-bridge.py "https://www.bilibili.com/video/BV199jJ6REJR"
```

## 前置条件

- [MediaCrawler](https://github.com/qql2/MediaCrawler) 在 `~/MediaCrawler`
- 已通过 MediaCrawler 完成 B 站登录
- Python 3.9+，`pip install -r requirements.txt`

## 文件结构

```
bilibili-tools/
├── bilibili-comment-bridge.py   # OpenClaw 桥接脚本
└── README.md
```
