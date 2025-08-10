# 仏教哲学経営設計（Buddhist Philosophical Business）

このリポジトリは、仏教哲学を基盤とした中長期的な経営設計の骨格を示したドキュメント群です。  
各ファイルはセクションごとに分割され、個別に閲覧・更新可能です。

## プロジェクト概要

仏教哲学の「中道」「縁起」「正命」の思想を現代の経営システムに応用し、**貨幣利得を唯一の目的から降ろす**が**利得そのものは否定しない**という価値観を実現するための包括的なフレームワークです。

### 核となる目的関数

$$
\max \; \mathcal{W} 
= \underbrace{\alpha \cdot \big(-D\big)}_{\text{苦の総量最小化}}
+ \underbrace{\beta \cdot R}_{\text{関係的充足の最大化}}
+ \underbrace{\gamma \cdot E}_{\text{生態健全性の維持・再生}}
+ \underbrace{\delta \cdot u(\Pi)}_{\text{適正利益の満たし方}}
$$

- **D**: 苦（dukkha）の指標（孤立・不安・搾取・有害外部性）
- **R**: 関係的充足（信頼・参加・能力形成・時間余裕）
- **E**: 生態系健全性（排出・多様性・水・土壌）
- **u(Π)**: 適正利益の満たし方（飽和効用関数による「足るを知る」）

## ファイル構成

### 📚 哲学・理念（Philosophy）
1. [目的関数アーキテクチャ（Objective Architecture）](./docs/philosophy/01_objective_architecture.md)  
2. [哲学から制度へ（Doctrine → Design）](./docs/philosophy/02_doctrine_to_design.md)  
3. [二重統治（Dual Governance）](./docs/philosophy/03_dual_governance.md)  
4. [測定と会計（Metrics & Accounting）](./docs/philosophy/04_metrics_accounting.md)  
5. [二重市場（Dual Listings）](./docs/philosophy/05_dual_listings.md)  
6. [マーケティング（Karunā Marketing）](./docs/philosophy/06_karuna_marketing.md)  
7. [ファイナンス（Steward Finance）](./docs/philosophy/07_steward_finance.md)  
8. [学習（Epistemic Loop）](./docs/philosophy/08_epistemic_loop.md)  
9. [侵蝕に対する防御（Anti-Erosion Invariants）](./docs/philosophy/09_anti_erosion_invariants.md)  
10. [総合結論（Conclusion）](./docs/philosophy/10_conclusion.md)  

### ⚙️ 運用・実装（Operation）
- [運用ガイド（Operation Guide）](./docs/operation/README.md)
- [ガバナンス（Governance）](./docs/operation/01-governance.md)
- [合意形成（Deliberation）](./docs/operation/02-deliberation.md)
- [アイデンティティ・レピュテーション（Identity & Reputation）](./docs/operation/03-identity-and-reputation.md)
- [資金調達・管理（Funding & Stewardship）](./docs/operation/04-funding-and-stewardship.md)
- [ライセンス・データ（Licensing & Data）](./docs/operation/05-licensing-and-data.md)
- [ビルドワークフロー（Build Workflow）](./docs/operation/06-build-workflow.md)
- [コミュニティヘルス（Community Health）](./docs/operation/07-community-health.md)
- [測定・評価（Metrics & Evaluation）](./docs/operation/08-metrics-and-evaluation.md)

#### 🔧 実用ツール
- **プレイブック（Playbooks）**
  - [参加型予算・QF（Participatory Budgeting QF）](./docs/operation/playbooks/participatory-budgeting-qf.md)
  - [合意形成・QV（Consensus & QV）](./docs/operation/playbooks/consensus-and-qv.md)
  - [Polis プロセス（Polis Process）](./docs/operation/playbooks/polis-process.md)

- **テンプレート（Templates）**
  - [実験キャンバス（Experiment Canvas）](./docs/operation/templates/experiment-canvas.md)
  - [決定記録（Decision Record）](./docs/operation/templates/decision-record-template.md)
  - [RFC テンプレート（RFC Template）](./docs/operation/templates/rfc-template.md)

### 📖 参考文献・資料（References）
- [空海：両界曼荼羅の現代的な解釈](./docs/references/空海_両界曼荼羅の現代的な解釈.md) - 胎蔵界（慈悲・関係性）と金剛界（智慧・識別）の二層アーキテクチャ
- [飽和効用関数](./docs/references/飽和効用関数.md) - 目的関数の数学的基盤と実用方法

## 特徴

### 🎯 仏教哲学の現代応用
- **中道**: 利潤至上でも利潤否定でもない適正利益の追求
- **縁起**: 相互依存の関係性から生じる価値の重視
- **正命**: 他害のない生業の実現

### 🔄 Plurality実装
- **デジタル合意形成**: Pol.is による開放的意見収集
- **参加型資源配分**: Quadratic Funding（QF）と参加型予算
- **CC0志向**: 知識コモンズのオープン運営
- **透明ガバナンス**: ラフコンセンサスとADR（決定記録）

### 📊 四項混成の最適化
各項目（D, R, E, u(Π)）に重み（α, β, γ, δ）を設定し、ガバナンスで合意形成を行い、年次で見直し可能な設計

## 使用方法

1. **理念理解**: `docs/philosophy/` から目的関数アーキテクチャを理解
2. **実装設計**: `docs/operation/` から具体的な運用方法を参照
3. **実践**: プレイブックとテンプレートを使用して実装
4. **評価**: 四半期ごとの目的関数レビューで改善

## ライセンス

このプロジェクトは知識コモンズとして公開されており、CC0ライセンスの下で自由に利用・改変・配布できます。

---

*「貨幣利得を唯一の目的から降ろす」が「利得そのものは否定しない」を実現する仏教哲学経営システム*
