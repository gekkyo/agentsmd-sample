# AGENTS.md サンプルプロジェクト

AGENTS.md の運用例を示すサンプルです。ホームフォルダ用の共用 AGENTS.md と、プロジェクト用の AGENTS.md / README.md の記述例です。

## ディレクトリ構成

```
.
├── AGENTS.md                  # 共用ルール（ホームフォルダ用の AGENTS.md に相当）
├── README.md                  # このファイル
└── event_website_sample/      # プロジェクト用サンプル
    ├── AGENTS.md              # プロジェクト固有のエージェント指示
    └── README.md              # プロジェクトの説明
```

## 各ファイルの役割

- `AGENTS.md`（ルート）: 全プロジェクトで共通のルール。ホームフォルダに置く想定のファイル。
- `event_website_sample/AGENTS.md`: そのプロジェクトだけに適用する指示。共用ルールと矛盾した場合は作業前に確認する。
- `event_website_sample/README.md`: プロジェクトの概要・使い方。人間向けの説明。
