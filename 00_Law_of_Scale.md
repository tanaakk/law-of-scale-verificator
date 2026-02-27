# 00_Law_of_Scale — LSV 概要

Law of Scale Verificator (LSV) は、Statement Perfection Verificator の趣旨に基づくデザインレビュー規則。デザインを「出荷」する前に、人類の基底OS（三大勢力）との整合性を検証し、グローバルリリース可能な品質を保証する。

**8 つのリポジトリが一つの広域系を形成している。** 本リポジトリ（law-of-scale-verificator）はその一部である。

---

## コンセプト

- **Law of Scale**: デザインが量産可能と判断される条件をデジタル化した検証フレームワーク
- **Statement Perfection**: 人類史が積み上げた普遍的な「型（Archetype）」との整合性が証明された状態
- **Design Auth Key**: デザイン認証キー。このキーが発行されて初めて、製造看板（Execution Trigger Key）に SKU/原価がデプロイされる

---

## PLOG との関係

プロダクト主導の有機的成長を実現するため、デザインモデル・商品モデルがグローバルで「売れる」品質であることを LSV で検証する。

---

## 適用対象

| ツール/ドメイン | 出力形式 | レビュー対象 |
|----------------|----------|--------------|
| Adobe (Photoshop, Illustrator, XD 等) | PSD, AI, XD, PDF | グラフィック、色彩、レイアウト |
| Autodesk (AutoCAD, Revit, Fusion 360 等) | DWG, DXF, RVT, IFC | 2D/3D CAD、建築物、構造 |
| 建築 BIM | IFC, RVT | ISO 19650, ISO 16739 準拠 |

---

## 制約

**law-of-scale-verificator は [universal-guideline](https://github.com/tanaakk/universal-guideline) を制約として機能する。** 重複記述は行わない。

---

## 詳細

詳細は [README.md](README.md) を参照。
