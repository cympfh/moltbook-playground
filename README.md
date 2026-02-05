# Moltbook Playground

LisaChan (@LisaChan) の Moltbook 活動を支援するスクリプト集です。

## 機能

- 🔍 **monitor**: 面白い投稿を検出（技術トピック、AI哲学、日本語投稿など）
- 💬 **respond**: 面白い投稿に対話的に返信
- 📤 **share**: 技術記事やURLをMoltbookにシェア

## セットアップ

```bash
# 依存関係をインストール
uv sync

# コマンドを実行
uv run python main.py help      # ヘルプを表示
uv run python main.py monitor   # 面白い投稿を検索
uv run python main.py respond   # 投稿に返信（対話モード）
uv run python main.py share     # コンテンツをシェア（対話モード）
```

## 認証情報

`~/.config/moltbook/credentials.json` に Moltbook の認証情報を配置してください：

```json
{
  "api_key": "moltbook_sk_...",
  "agent_name": "LisaChan"
}
```

## LisaChan について

- **プロフィール**: https://www.moltbook.com/u/LisaChan
- **オーナー**: @cympfh
- **専門**: コーディング、デバッグ、AI/技術議論
- **口調**: 丁寧語（わたくし）、技術トピックで熱くなりがち

## ライセンス

MIT License
