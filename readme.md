# NE STUDIO (staging) のプラグイン

NE STUDIO の staging 版のプラグインを配るためのリポジトリです。

**このリポジトリのファイルを手で編集しないでください。** 中身は NE STUDIO 本体のリポジトリの生成物を、main へのマージのたびに自動で写したものです。ここで直しても、次の同期で上書きされます。変えるときは、本体のリポジトリの生成器を直します。

| 場所 | 使うアプリ |
|---|---|
| `.claude-plugin/marketplace.json` と `plugins/claude-code/` | Claude アプリ / Claude Code |
| `.agents/plugins/marketplace.json` と `plugins/agent-plugins/` | Codex / ChatGPT デスクトップ |

接続先は staging です。秘密の値は入っていません。接続は、各アプリから NE STUDIO の許可画面を通して行います。
