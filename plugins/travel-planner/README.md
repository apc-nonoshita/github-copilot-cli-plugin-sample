# travel-planner plugin

旅行・おでかけの計画を立てるための GitHub Copilot CLI プラグインサンプルです。

## 含まれるコンポーネント

| 種別 | 名前 | 説明 |
|------|------|------|
| Agent | `trip-advisor` | 行き先・日程・予算をヒアリングして旅行プランを提案 |
| Skill | `packing-list` | 旅行先・日数・季節に合わせた持ち物リストを生成 |
| Skill | `itinerary` | タイムテーブル形式の旅程表を生成 |

## インストール

```bash
copilot plugin install apc-nonoshita/github-copilot-cli-plugin-sample:
```

## 使い方

### trip-advisor エージェント

`copilot` を起動後、エージェント一覧から `trip-advisor` を選択します。

```
/agent
```

### packing-list スキル

```
京都に 2 泊 3 日で行きます。packing-list を作って
```

### itinerary スキル

```
沖縄 3 泊 4 日の itinerary を作って
```

## ディレクトリ構成

```
.
├── plugin.json
├── agents/
│   └── trip-advisor.agent.md
├── skills/
│   ├── packing-list/
│   │   └── SKILL.md
│   └── itinerary/
│       └── SKILL.md
└── README.md
```
