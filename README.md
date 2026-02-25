# 🚬 煙草の行き先

近くの**喫煙可能な飲食店**を探すWebアプリ。ホットペッパーグルメAPIで現在地周辺の喫煙可・分煙のお店を検索できます。

## 🌐 公開URL

**https://fulfill-tokuyama.github.io/tabaco/**

## 使い方

1. 上記URLにアクセス
2. [リクルートWEBサービス](https://webservice.recruit.co.jp/)で無料のAPIキーを取得
3. APIキーを入力（ブラウザに保存されます）
4. 検索範囲（300m〜3km）を選択
5. 必要ならキーワード（例：焼肉、渋谷）を入力
6. 「📍 現在地から探す」をクリック

## 技術スタック

- 純粋なHTML/CSS/JavaScript（フレームワーク不要）
- ホットペッパーグルメAPI
- サーバーレス・単一HTMLファイル構成

## ローカルで動かす

```bash
# リポジトリをクローン
git clone https://github.com/fulfill-tokuyama/tabaco.git
cd tabaco

# index.html をブラウザで開く（または簡易サーバー）
npx serve .
# または
python -m http.server 8000
```

## ライセンス

MIT
