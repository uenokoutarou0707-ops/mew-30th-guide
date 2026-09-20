# ミュウ30周年サイト

公開URL: https://barrylab.net/mew30/

## 更新方法

1. `dist/` 内のファイルを更新する
2. `main` ブランチへプッシュする
3. GitHub Actions が XServer の `/home/xs985167/barrylab.net/public_html/mew30/` へ自動反映する

## GitHub Actions secrets

- `XSERVER_HOST`: `xs985167.xsrv.jp`
- `XSERVER_USER`: XServerのSSHユーザー名
- `XSERVER_PATH`: `/home/xs985167/barrylab.net/public_html/mew30`
- `XSERVER_SSH_KEY`: このリポジトリ専用のSSH秘密鍵

秘密鍵やパスワードはリポジトリへコミットしない。
