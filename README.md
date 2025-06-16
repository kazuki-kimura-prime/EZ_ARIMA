# EZ_ARIMA：ARIMAモデルによる年間予測支援ツール

## 📌 概要

**EZ_ARIMA** は、Google Colabでの使用を前提としたPythonベースで構築されたARIMAモデルによる時系列データの年間予測支援ツールです。  
環境観測や利用者数など、幅広い月次の時系列データに基づく将来予測に適しています。

---

## 🔍 主な機能

- SARIMAモデルによる**12か月先までの自動予測**
- AICベースのパラメータ選定（`statsmodels`ライブラリ）
- 残差分析（ヒストグラム, Q-Qプロット, ACF）
- 評価指標：MAE, RMSE, MAPE, R²
- 検証用と将来予測用の2段階モデル構築

---

## 🚀 使い方

以下のボタンをクリックすると、Google Colab 上でノートブックを直接開いて実行できます（Googleアカウントが必要です）：

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kazuki-kimura-prime/EZ_ARIMA/blob/main/EZ_ARIMA.ipynb)

Google Colab 上でノートブックを上から順に実行してください。

---

## 📁 ファイル構成

```
EZ_ARIMA/
├── EZ_ARIMA.ipynb  　　　　　　　　　　　　　　# Jupyterノートブック
├── README.md                            # 本ファイル
├── LICENSE                              # ライセンス情報（MIT）
```

---

## 🔧 依存ライブラリ

- pandas
- numpy
- matplotlib
- statsmodels
- seaborn


---

## ⚠️ ライセンスに関する注意

上記の外部ライブラリ・コードに依存しております。著作権侵害の意図は一切なく、ライセンス遵守を前提として構成しています。  
万が一問題となるコード等が発見された場合は、 [Issues](https://github.com/kazuki-kimura-prime/EZ_ARIMA/issues) にてご連絡ください。

本ソフトウェアは個人で制作したものであり郡山市及び郡山市上下水道局は制作に関係しておりません。

---

## 📜 ライセンス

MITライセンスの下で提供されています。詳細は `LICENSE` ファイルをご覧ください。
