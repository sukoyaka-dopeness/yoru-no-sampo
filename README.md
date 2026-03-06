# よるのさんぽ — yoru-no-sampo

A quiet shared space for people who cannot sleep.  
Walk through the night town. Feel the presence of others. Nothing more.

---

## このサービスとは

深夜に眠れない人が、静かに夜道を歩くサービスです。

チャットなし。いいねなし。ランキングなし。  
ただ歩く。ただ誰かの気配を感じる。

それだけで十分です。

---

## 体験の流れ

1. 深夜（23:00〜05:00）にアクセスする
2. ロード画面を経て、夜の街に入る
3. 左右タップで歩く
4. ときどき誰かとすれ違う
5. 気が向いたらスタンプや定型文を置く
6. 流れ星が1本横切り、夜が終わる

---

## コンセプト

詳細は [PHILOSOPHY.md](./PHILOSOPHY.md) と [WHY_THIS_EXISTS.md](./WHY_THIS_EXISTS.md) を参照。

---

## ファイル構成

```
yoru-no-sampo/
│
├── README.md
├── PHILOSOPHY.md                    ← 哲学・哲学的緊張点
├── WHY_THIS_EXISTS.md               ← 存在理由
│
├── docs/
│   ├── core-concept.md              ← 世界観・基本原則
│   ├── mvp-spec.md                  ← MVP全仕様
│   ├── mvp-map-spec.md              ← マップ構成
│   ├── development-roadmap.md       ← 開発フェーズ
│   ├── tech-stack.md                ← 技術選定
│   │
│   ├── canvas-structure.md          ← Canvas描画レイヤー
│   ├── firebase-structure.md        ← データ構造
│   │
│   ├── ui-flow.md                   ← 画面遷移・操作フロー
│   ├── movement-system.md           ← 移動・カメラ
│   ├── encounter-system.md          ← すれ違いの仕組み
│   ├── atmosphere-system.md         ← 環境演出
│   │
│   ├── message-and-stamp-system.md  ← 表示ルール・仕様
│   ├── message-library.md           ← メッセージ一覧
│   ├── ads-integration.md           ← 広告・スポンサー戦略
│   │
│   ├── future-ideas.md              ← 将来実装アイデア
│   └── undecided-items.md           ← 未決定事項
│
└── meta/
    └── discussion-summary.md        ← コンセプト形成の記録（Phase 1–6）
```

---

## 技術スタック（MVP）

- Vanilla JavaScript
- HTML5 Canvas
- Firebase Realtime Database + Anonymous Auth
- PWA対応

詳細は [docs/tech-stack.md](./docs/tech-stack.md) を参照。

---

## 将来実装

- 季節依存（夏の虫・冬の白い息・春の夜桜）
- 天気依存（雨の反射・霧・星の有無）
- 道の種類の拡張（海沿い・工場地帯・駅前・山道）
- AIキャラクターの追加（夜風さん・街灯くん・ねこ・雨雲さん）
- キャラクター外見の選択（人型・猫・オバケ）
- 朝の演出強化（鳥の影・空の赤み・街灯の順消灯）

詳細は [docs/future-ideas.md](./docs/future-ideas.md) を参照。

---

## ライセンス

未定。[docs/undecided-items.md](./docs/undecided-items.md) に記録。
