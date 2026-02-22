# Law of Scale Verificator (LSV)

All assets (Architecture, 2D/3D, Products, Intellectual properties) must pass the LSV before global release.

## 概要

Law of Scale Verificator は、[TANAAKK Statement Perfection Verificator](https://www.tanaakk.com/2026/02/21/verification/) の趣旨に基づくデザインレビュー規則です。デザインを「出荷」する前に、人類の基底OS（三大勢力）との整合性を検証し、グローバルリリース可能な品質を保証します。

**PLOG (Product-Led Organic Growth™) との関係**: プロダクト主導の有機的成長を実現するため、デザインモデル・商品モデルがグローバルで「売れる」品質であることを LSV で検証する。Design Auth Key 取得後、製造看板（Execution Trigger Key）に SKU/原価がデプロイされ、OMS/WMS/MES のフローに組み込まれる。

## コンセプト

- **Law of Scale**: デザインが量産可能と判断される条件をデジタル化した検証フレームワーク
- **Statement Perfection**: 人類史が積み上げた普遍的な「型（Archetype）」との整合性が証明された状態
- **Design Auth Key**: デザイン認証キー。このキーが発行されて初めて、製造看板（Execution Trigger Key）に SKU/原価がデプロイされる

## 適用対象

| ツール/ドメイン | 出力形式 | レビュー対象 |
|----------------|----------|--------------|
| Adobe (Photoshop, Illustrator, XD 等) | PSD, AI, XD, PDF | グラフィック、色彩、レイアウト |
| Autodesk (AutoCAD, Revit, Fusion 360 等) | DWG, DXF, RVT, IFC | 2D/3D CAD、建築物、構造 |
| アニメーション | 各種フレーム、動画 | 動き、時間軸、シーケンス |
| 建築 BIM | IFC, RVT | ISO 19650, ISO 16739 準拠 |

## 制約

**law-of-scale-verificator は [universal-guideline](https://github.com/tanaakk/universal-guideline) を制約として機能する。** 重複記述は行わない。

## 使い方

### プロジェクトに追加

各アプリの `.cursor/rules/` に `*.mdc` をコピーするか、Git サブモジュールとして追加：

```bash
git submodule add https://github.com/tanaakk/law-of-scale-verificator.git .cursor/rules/law-of-scale-verificator
# または .mdc を直接コピー
cp law-of-scale-verificator/*.mdc .cursor/rules/
```

### User Rules に貼る

`user-rules-copy-paste.md` を Cursor Settings > Rules for AI にコピー＆ペースト。

## バージョン

- **v1.1.2**: universal-guideline 準拠強化、PLOG 目的明記、商品モデル（product_uuid）接続
- **v1.1.1**: 初回リリース。10カテゴリー整合性マトリクス、認証キー階層、Verification プロセスを定義

## License

AGPL-3.0
