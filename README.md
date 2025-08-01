<p align="center">
<img width="997" height="670" alt="段落テキスト (1)" src="https://github.com/user-attachments/assets/838abee6-dab2-4826-94ae-dfaf111d4dde" />
</p>


# 株価シミュレーション & 自動投資戦略アプリ

## 📌 概要
このアプリは、S&P500および日経平均の構成銘柄を対象に、AIが週ごとに最適な投資戦略を自動で決定し、株価をシミュレーションします。
売買タイミングでのメール通知や、週次の投資結果レポート送信を行います。
銘柄リストは月1回、Wikipediaから自動で取得・更新します。

⚠️ 投資助言を目的としたものではありません。個人学習・技術デモ用途です。

---

## ⚙️ 主な機能
- 📈 **株価シミュレーション**：週次で売買条件をAIが決定し、シミュレーション実行
- 📧 **通知機能**：売買の局面でメール通知
- 📝 **レポート作成**：週次で投資結果のレポートをメール送信
- 🔄 **銘柄リスト自動更新**：S&P500・日経平均銘柄を月1でWebスクレイピングにより更新
- 💡 **戦略再構築**：AIが週次で投資戦略（売買条件）を最適化

---

## 🛠 技術スタック
- Python 3.x
- pandas / scikit-learn（データ分析・AI）
- yfinance（株価データ取得）
- BeautifulSoup4（Webスクレイピング）
- smtplib / email（通知・レポート送信）
- matplotlib（グラフ描画）

---
## 📥 メール通知画像
![IMG_7602](https://github.com/user-attachments/assets/51277f69-2d4d-426f-a78e-ab2bcad8acfe)


## 🚀 実行方法
```bash

git clone https://github.com/your-username/stock-simulation-app.git
cd stock-simulation-app
pip install -r requirements.txt
python main.py

⚠️ 注意事項
実データは含めておらず、APIキーや個人メールアドレス情報は除外しています。

投資判断や売買を推奨するものではありません。

✅ このアプリで身につくスキル
AIによる金融モデリング

Webスクレイピングとデータ自動取得

メール通知システム構築

データ可視化とレポーティング

Python開発
