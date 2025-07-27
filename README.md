# 🤖 LLM Portfolio Battle

AI言語モデルのポートフォリオサイト生成能力を比較するプロジェクト

## 概要

このプロジェクトは、[LMArena](https://lmarena.ai/) のBattleモードで各AI言語モデルに同じプロンプトを与えて作成されたポートフォリオサイトを比較・検証するためのものです。

## 使用プロンプト

```
めちゃくちゃかっこいいエンジニアのポートフォリをサイトをhtml+tailwindcssでつくって
```

## 参加モデル

- Claude 3.5 Sonnet
- DeepSeek R1
- Folsom
- Gemini 2.5 Pro
- Kraken
- Qwen3 Coder
- Summit
- Zenith

## サイト構成

```
llm/
├── index.html                           # メインページ（モデル比較）
├── claude-3-5-sonnet-20241022/
│   └── index.html
├── deepseek-r1-0528/
│   └── index.html
├── folsom-072125-1/
│   └── index.html
├── gemini-2.5-pro/
│   └── index.html
├── kraken-072125-2/
│   └── index.html
├── qwen3-coder-480b-a35b-instruct/
│   └── index.html
├── summit/
│   └── index.html
├── zenith/
│   └── index.html
└── prompt.md                           # 使用プロンプト
```

## 使用方法

1. `index.html` をブラウザで開く
2. 各モデルのリンクをクリックして生成されたポートフォリオサイトを比較
3. プロンプトをコピーして他のモデルでも試すことが可能

## 技術仕様

- **技術スタック**: HTML + TailwindCSS
- **要件**: レスポンシブデザイン対応
- **目的**: エンジニアのポートフォリオサイト生成

## ライセンス

MIT License