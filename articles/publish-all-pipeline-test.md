---
title: 1 本の原稿を Zenn・Qiita・note に一括公開するテスト
emoji: 🚀
type: tech
topics:
  - python
  - githubactions
  - 自動化
published: false
---

## はじめに

この記事は、1 本の原稿から Zenn・Qiita・note に一括で記事を出す仕組みの動作確認用テスト記事です。

## 仕組み

1. `articles/<slug>/` に日本語版と中国語版の原稿を書く
2. スクリプトが各媒体用のファイルを生成する
3. Zenn と Qiita は git に push し、note は MCP のライブラリで投稿する

## 画像

![サンプル画像](/images/publish-all-pipeline-test/sample.png)

## コード

```python
# コードブロック内の画像記法は書き換えない: ![x](images/not-real.png)
print("hello")
```

## 表

| 媒体 | 公開方法 |
|---|---|
| Zenn | GitHub 連携 |
| Qiita | GitHub Actions |
| note | 非公式 MCP |
