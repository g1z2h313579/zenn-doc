---
title: "Zenn GitHub 联动部署文章的测试"
emoji: "🧪"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["zenn", "github"]
published: false
---

## 前言

本文是一篇测试文章，用于确认通过 Zenn 的 GitHub 联动部署文章的流程是否正常运行。

## 机制

1. 在本地使用 `zenn-cli` 以 Markdown 文件形式编写文章
2. push 到 `main` 分支
3. Zenn 的 GitHub 联动检测到变更，自动部署文章

## 需要确认的内容

- push 后 Zenn 端会执行部署
- 文章会反映到 Zenn 上
