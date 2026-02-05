# my-obsidian-environment

個人用のObsidian環境設定を管理するリポジトリです。

## ディレクトリ構成

```
.
├── 000_dataview/            # Dataviewクエリ集
├── 001_daily/               # デイリーノート
├── 999_assets/              # 画像やファイル
└── 999_templates/           # テンプレートファイル
    ├── 000_default.md
    └── 001_daily.md
```

## Git管理について

### 管理対象

- `.obsidian/` - Obsidianの設定ファイル（一部除外あり）
- `999_templates/` - テンプレートファイル
- `000_dataview.md` - Dataviewクエリ

### 管理対象外

- `*.md` - 個人のノート（デフォルトで除外）
- `.obsidian/workspace.json` - ワークスペース状態
- `.obsidian/cache/` - キャッシュファイル

詳細は [.gitignore](.gitignore) を参照してください。

## プラグイン設定のハイライト

### Templater
- テンプレートフォルダ: `999_templates`
- デイリーノート用テンプレート自動適用: `001_daily/` → `999_templates/001_daily.md`

### Frontmatter Modified Date
- 更新日時フィールド: `updated`
- 除外フォルダ: `999_templates`, `000_dataview`
- フォーマット: `YYYY-MM-DD HH:mm`

### Daily Notes
- 保存先: `001_daily/`
- テンプレート: `999_templates/001_daily.md`

## ライセンス

個人用設定のため、ライセンスは未設定です。
