---
layout: ka-default
title: カイギアナリティクス 議会議事録AI分析サービス
---

<div class="hero">
<h1>カイギアナリティクス</h1>
<p class="tagline">埋もれた議論を掘り起こし、議員の政策立案を支える。</p>

<div class="hero-stats">
  <div class="hero-stat">
    <span class="number">589,855</span>
    <span class="unit">件</span>
    <span class="label">議事録データ</span>
  </div>
  <div class="hero-stat">
    <span class="number">約45,000</span>
    <span class="unit">件</span>
    <span class="label">議員プロフィール</span>
  </div>
  <div class="hero-stat">
    <span class="number">約1,000</span>
    <span class="unit">自治体</span>
    <span class="label">収集済み</span>
  </div>
</div>
</div>

## なぜ必要か

<div class="issue-card" markdown="1">
<div class="card-label">課題</div>

地方自治体（地方公共団体）1,765で日々交わされる政策議論。その記録は議事録として公開されていますが、**自治体ごとにフォーマットがバラバラ**で、横断的な検索は事実上不可能です。

他の自治体がどのような議論を行っているか——先行事例や政策の効果を調べるには**膨大な時間と労力**が必要です。政策立案に不可欠な「全国の議論の全体像」が見えない状況が続いています。
</div>

<div class="proposal-card" markdown="1">
<div class="card-label">解決</div>

カイギアナリティクスは、WEBスクレイピング・データベース・LLM（大規模言語モデル）各技術を統合し、全国の議会議事録を収集・構造化・可視化します。多忙な議員が政策課題の全体像を一目で把握できる環境を提供します。
</div>

## 何ができるか

### 全国議事録の横断検索

キーワードを指定するだけで、全国約1,000自治体の議事録から関連する議論を抽出。地方別・自治体別に構造化して提供します。（WEBインターフェイスは準備中です。）

### 高精度な分析

AIによる要約・分析では、**ソース分離運用**と**正確性誘導プロンプト**により、ハルシネーション（事実と異なる出力）を徹底的に排除。すべての記述に出典（自治体名・日付・発言者）を明記します。

## 事例 データセンター政策分析

実際にカイギアナリティクスを使用し、「データセンター」をテーマに全国の議会議論を分析した事例です。

| 項目 | 内容 |
|---|---|
| 対象テーマ | データセンター誘致・整備に関する議論 |
| 検索対象 | 全国 381 自治体 |
| 該当議事録 | 3,296 件 |
| 生成物 | 10地方×PDF報告書 + インフォグラフィック + サマリレポート |

### 分析から得られた知見の例

<div class="evidence-card" markdown="1">
<div class="card-label">発見</div>

- **北九州市**: APL社によるデータセンター投資額 *1,250億円超*。低地震リスク・再エネ・工業用水・理工系人材の集積を強みとした誘致戦略
- **薩摩川内市**: 原発再稼働による余剰電力を活かしたデータセンター誘致。*数万世帯分の電力*を供給可能、*年間3,500万円*の税収効果を試算
- **石狩市**: さくらインターネットの石狩データセンターが*約200人*の雇用を創出。冷涼な気候による冷却コスト削減が立地優位性に
</div>

### インフォグラフィック（サンプル）

分析結果を1枚のビジュアルに凝縮したインフォグラフィックです。地方ごとの議論の全体像を一目で把握できます。

<div class="infographic-grid">

![北海道地方](images/infographic-hokkaido.png)

![東北地方](images/infographic-tohoku.png)

![関東地方](images/infographic-kanto.png)

![甲信越地方](images/infographic-koshinetsu.png)

![北陸地方](images/infographic-hokuriku.png)

![東海地方](images/infographic-tokai.png)

![近畿地方](images/infographic-kinki.png)

![中国地方](images/infographic-chugoku.png)

![四国地方](images/infographic-shikoku.png)

![九州沖縄地方](images/infographic-kyushu-okinawa.png)

</div>

## ご利用の流れ

<div class="step-flow">
  <div class="step-item">
    <div class="step-num">1</div>
    <div class="step-content">
      <h4>テーマの設定</h4>
      <p>分析したい政策テーマ（キーワード）をご指定ください。</p>
    </div>
  </div>
  <div class="step-item">
    <div class="step-num">2</div>
    <div class="step-content">
      <h4>全国議事録の横断検索</h4>
      <p>約1,000自治体の議事録データベースからキーワードに関連する議論を抽出します。</p>
    </div>
  </div>
  <div class="step-item">
    <div class="step-num">3</div>
    <div class="step-content">
      <h4>構造化・分析</h4>
      <p>AIが議論を地方別・自治体別に構造化し、要点を分析・要約します。</p>
    </div>
  </div>
  <div class="step-item">
    <div class="step-num">4</div>
    <div class="step-content">
      <h4>成果物の生成</h4>
      <p>PDF報告書、インフォグラフィック、サマリレポート、議事録データを提供します。</p>
    </div>
  </div>
  <div class="step-item">
    <div class="step-num">5</div>
    <div class="step-content">
      <h4>納品・ブリーフィング</h4>
      <p>成果物をお届けし、分析結果についてご説明します。</p>
    </div>
  </div>
</div>

## データ基盤

カイギアナリティクスは、独自に構築した大規模議事録データベースを基盤としています。

<div class="data-grid">
  <div class="data-item">
    <span class="number">589,855</span>
    <span class="unit">件</span>
    <span class="label">議事録</span>
  </div>
  <div class="data-item">
    <span class="number">約45,000</span>
    <span class="unit">件</span>
    <span class="label">議員プロフィール</span>
  </div>
  <div class="data-item">
    <span class="number">約1,000</span>
    <span class="unit">自治体</span>
    <span class="label">収集済み（全体1,765）</span>
  </div>
</div>

| 構成要素 | 技術 |
|---|---|
| データベース | PostgreSQL 15（マスター＋レプリカ構成） |
| 全文検索 | Elasticsearch、Meilisearch |
| AI分析 | 各社大規模言語モデル（LLM）による構造化・要約 |
| 可視化 | NotebookLM + 画像生成モデルによるインフォグラフィック |
| 品質管理 | Anthropic ClaudeCodeによるソース分離運用 + 正確性誘導プロンプト |

---

<div style="text-align: center; padding: 40px 0 20px;">
  <p style="font-family: 'Noto Serif JP', serif; font-size: 1.1rem; color: #1B3A5C;">お問い合わせ</p>
  <p style="color: #666666; font-size: 0.9rem;">サービスの詳細やご利用についてのご質問は、下記までお気軽にお問い合わせください。</p>
  <p style="margin-top: 16px;">
    <strong>カイギアナリティクス</strong><br>
    <span style="color: #666666; font-size: 0.9rem;">junkumagai@gmail.com</span>
  </p>
</div>
