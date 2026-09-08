# Reverse Engineering Valuation Tool

残余利益モデル（Residual Income Valuation）を用いて、**現在の株価に市場が織り込んでいる成長率・要求リターンを逆算するValuation Tool**です。

## Demo

[Web Tool](https://yamaday-2e1.github.io/valuation-tool-rev/)

## 概要

株価そのものを予測するのではなく、
「現在の株価には、どの程度の将来成長が織り込まれているのか？」を可視化します。

### 主な入力値

* 株価（P₀）
* 一株当たり純資産（B₀）
* 予想EPS（E₁）
* 予想DPS（D₁）
* 要求リターン（r）または想定成長率（g）

## 制作目的

大学のゼミでリバース・エンジニアリングを学習した際、Excelによる数値計算だけでなく、実際に操作できるツールにしたいと考え制作しました。

## 使用技術

* HTML
* CSS
* JavaScript
* Claude Code
