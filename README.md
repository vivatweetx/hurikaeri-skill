# hurikaeri-skill

ふりかえり(レトロスペクティブ)の設計・進行を支援する Agent Skill です。[ふりかえり実践会 hurikaeri.jp](https://hurikaeri.jp/) の手法カタログ(151種)を土台に、状況の問診から進行台本の作成まで伴走します。

## できること

- 「明日のふりかえり考えて」から、人数・時間・チーム状態の問診 → 手法選び → そのまま読める進行台本の作成まで
- 「毎回KPTでマンネリ」「意見が出ない」「反省会になってしまう」などの悩み相談
- ふりかえり結果のメモを貼ると、次回の手法と問いを提案

## インストール

### Claude Code

```
mkdir -p ~/.claude/skills
cd ~/.claude/skills
# このリポジトリをcloneするか、zipを展開してください
```

zip配布版: https://hurikaeri.jp/skill/

### おすすめ: MCPと併用する

このSkill単体でも動きますが、[hurikaeri MCP](https://hurikaeri.jp/mcp/) を接続すると、手法151種・コツ124本・悩みQ&A68件を常に最新の状態で参照できます。SkillはMCPの「使いこなし方」を知っているので、併用がいちばん効果的です。

```
claude mcp add --transport http hurikaeri https://hurikaeri-site.viva-tweet-x.workers.dev/mcp
```

## ライセンス・出典

手法データの出典: [ふりかえり実践会 hurikaeri.jp](https://hurikaeri.jp/)(森一樹 @viva_tweet_x)
このSkillが提案する手法には出典URLが明記されます。そのままチームに共有してください。
