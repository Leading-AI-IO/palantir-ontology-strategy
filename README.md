# パランティアの衝撃：データとAIを繋ぐ「オントロジー」戦略
**The Palantir Impact: Ontology Strategy Connecting Data and AI**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-English%20%7C%20Japanese-blue)](docs/)

<p align="left">
  <img src="./assets/cover_design.png" width="80%">
</p

*Read this in other languages: [English](README_en.md)*

---

> **定義｜What is The Palantir Impact**
>
> **本書とは**、山内怜史（Satoshi Yamauchi）による、Palantir Foundryの中核
> 概念「オントロジー」を、単なるIT技術としてではなく、現実世界を「名詞"
> （オブジェクト・プロパティ・リンク）と「動詞」（アクション・ファンクション・
> 動的セキュリティ）でモデル化し、ブランチとレビューの統治プロセスを通じて
> AIが安全に現実の業務を動かせるようにする運用レイヤーとして解説した構造
> 分析である。本書の言葉：「Palantirがもたらすパラダイムシフト——それは
> "見るだけのデータ"から"ビジネスを直接動かすためのデータ"への転換である」。
>
> **This book** is a structural analysis by Satoshi Yamauchi, explaining
> Palantir Foundry's "Ontology" as an operational layer that models the
> world as nouns and verbs, enabling AI to act safely on real-world
> operations through a branch-and-review governance process. As stated in
> the book: this is a shift "from data you only look at, to data that
> directly drives the business."
>
> *著者・全書籍一覧 / Author & full catalog: [github.com/Leading-AI-IO](https://github.com/Leading-AI-IO)*

---

## 🏛️ Core Tenets（オントロジーを貫く3つの哲学）

従来のデータ基盤（データレイクやDWH）が「見るための死んだデータの沼」に陥る中、Palantirが提示するパラダイムシフトは以下の原則に基づいています。

1. **The Operational Layer（運用レイヤーとしてのデータ）**
   データは分析の果てに人間が手作業で現実を動かすためのものではありません。オントロジーは、システム上に現実のビジネスを再現する「デジタルツイン」であり、データそのものが直接ビジネスを駆動するレイヤーとなります。
2. **Convergence of Noun and Verb（名詞と動詞の統合）**
   システムを「オブジェクト（名詞）」と「アクション（動詞）」の統合として捉えます。顧客や部品といった状態（セマンティクス）だけでなく、発注やステータス変更といった運動的要素（キネティクス）を一つのモデルに内包します。
3. **Governance of Reality（現実世界のバージョン管理）**
   現実の運用を書き換えるという強大な力には、絶対的な統制が必要です。AIが自律的に提案を行う時代においても、オントロジーは「ブランチ（分岐）」と「レビュー」を通じて、圧倒的なスピードとガバナンスを両立させます。

---

## 📖 本文を読む (Read the Book)

本書は、以下のリンクから一気に読み進めることができます。

👉 **[書籍の全文を読む（the-palantir-impact_jp.md）](docs/the-palantir-impact_jp.md)**

### 目次 (Table of Contents)
* **Part I: The Problem and the Paradigm（課題とパラダイムシフト）**
  * 序章：AI時代になぜ「データ統合」は失敗するのか
  * 第1章：謎多きユニコーン「Palantir」と真のデータ統合
  * 第2章：Palantirの心臓部「オントロジー」とは何か？
* **Part II: The Architecture of Action（アクションのアーキテクチャ）**
  * 第3章：【図解】アクションのアーキテクチャ
  * 第4章：現実世界のガバナンス
* **Part III: The Destiny of Intelligence（AIと運用が交差する未来）**
  * 第5章：世界と日本を変えるPalantirのユースケース
  * 第6章：オントロジー×AIがもたらす未来
  * 終章：オントロジー思考で組織のデータを設計せよ

---

## Author & Maintainer
**Satoshi Yamauchi** (山内 怜史)<br>
* **Business Designer & AI Strategist at SunAsterisk.inc**
* **Founder / AI Strategist at Leading.AI**
* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)
* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

Related Projects

本書は、以下のオープンソースプロジェクトと連携しています。

| プロジェクト | 概要 | リンク |
|---|---|---|
| **The AI Strategist** | AIストラテジストという職業を定義し、BTC交差点で戦うための実践的フレームワーク | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist) |
| **Depth & Velocity** | 生成AI時代の新規事業開発方法論 | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity) |
| **The Silence of Intelligence** | Anthropic CEO ダリオ・アモディの思想を体系化。産業構造の解剖シリーズ第2弾 | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence) |
| **The Anatomy of Anthropic** | Anthropicの戦略・製品・研究・安全性を包括的に解剖 | [GitHub](https://github.com/Leading-AI-IO/the-anatomy-of-anthropic) |
| **What They Won't Teach You** | AIに有利な世代が教えない、AIの使い方と"思考のOS" | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you) |
| **The Edge of Intelligence** | AIがあなたのデバイスで動く時代：クラウドの終わりと、エッジの始まり | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence) |
| **The Redesign of Design Strategy** | デザイン戦略の再定義。IDEO崩壊の構造分析を含む | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era) |
| **The Orchestrator** | AI時代に最も希少な人材像「オーケストレーター」を世界で初めて定義 | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned** | AIが広告を「割り込み」から「優しい提案」に変える。検索の終焉、広告が初めて「歓迎される存在」になる未来。 | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned) |
| **The AI Organization** | AI導入が失敗する本質は技術ではなく組織にある。AI時代の組織論 | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization) |
| **The Structural Shift from SaaS** | SaaSからService-as-a-Softwareへの構造的転換。Next SaaS ビジネスモデル。| [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model) |
| **The 10:80:10 Principle** | 人とAIの共創黄金比「10:80:10」の法則——AI時代の思考のOS。| [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)  |
| **A Trillion Dollars and a Firebomb** | 1兆ドルと火炎瓶。AI時代の同時加速する現実。 | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb)  |
| **The End of the Attention Economy** | アテンション・エコノミーの終わり。次世代SNSの在り方とは？ | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Growth Engine of Anthropic** | Anthropicの1兆ドル到達の構造解剖。 | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic)  |
| **The Agentic Commerce Economy** | AIエージェントが購買を代行する時代、広告モデルの構造的変化。 | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)  |
| **Will ai break the planet** | 数十兆円のインフラ投資と、地球温暖化の「不可逆ライン」。 | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)  |
| **The-forward-deployed-shift** | 成果実装 ── FDEが示す、AIで「作る」が終わった世界の価値のありか。 | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)  |
| **Frontier-Grade Open Weights** | フロンティア級のオープンウェイトモデルは、開かれたのか。 | [GitHub](https://github.com/Leading-AI-IO/frontier-grade-open-weights)  |
| **Earned-ai-model-optionality** | AIモデルは選べる。選べるのは、選べるようにした企業だけだ。 | [GitHub](https://github.com/Leading-AI-IO/earned-ai-model-optionality)  |
| **Us-china-ai-competition** | 米中AI競争の多層構造 ── 決めているのは、強さではなく条件である。 | [GitHub](https://github.com/Leading-AI-IO/us-china-ai-competition)  |
| **The China AI Registry** | あなたが名前を言える5つの中国AIモデルは、中国が数えているものの1%に満たない。 | [GitHub](https://github.com/Leading-AI-IO/the-china-ai-registry)  |

---

## Contribution
Issues and Pull Requests are welcome.<br>
If you find any typos or have updated information about Palantir's architecture or Ontology, please feel free to contribute.

誤字脱字の修正や、Palantirのアーキテクチャやオントロジーに関する最新情報の提供など、エンジニアの皆様からのPull Requestを歓迎します。

## License
This project is licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/) - see the [LICENSE](LICENSE) file for details.

---

© 2026 Satoshi Yamauchi / Leading AI — Licensed under CC BY 4.0
