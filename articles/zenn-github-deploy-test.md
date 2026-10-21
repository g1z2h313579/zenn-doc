---
title: "Zenn の GitHub 連携による記事デプロイのテスト"
emoji: "🧪"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["zenn", "github"]
published: false
---

## はじめに

この記事は、Zenn の GitHub 連携による記事デプロイの動作確認用テスト記事です。

## 仕組み

1. ローカルで `zenn-cli` を使って Markdown ファイルとして記事を書く
2. `main` ブランチに push する
3. Zenn の GitHub 連携が変更を検知し、記事を自動でデプロイする

## 確認したいこと

- push によって Zenn 側でデプロイが実行されること
- 記事が Zenn 上に反映されること
