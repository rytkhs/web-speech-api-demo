# Web Speech API デモ

このプロジェクトは、Web Speech API を使用した音声認識のデモンストレーションアプリケーションです。ブラウザの音声認識機能を使用して、話した言葉をリアルタイムでテキストに変換することができます。

![image](https://github.com/user-attachments/assets/bd846bbb-4194-4efa-953f-fd30c684fd02)


## 機能

- リアルタイムの音声認識
- 認識した文字列のテキストエリアへの表示
- 暫定的な認識結果の表示
- 認識テキストのクリア機能

## 必要要件

- 最新の Web ブラウザ（Google Chrome 推奨）
- マイク付きのデバイス
- インターネット接続

## 使用方法

1. リポジトリをクローンするか、ダウンロードします：

```bash
git clone [リポジトリのURL]
```

2. `index.html`を Web ブラウザで開きます。

3. マイクボタンをクリックして、音声認識を開始します。

4. お使いのブラウザから、マイクの使用許可を求められた場合は「許可」をクリックしてください。

5. 話した内容がテキストエリアに表示されます。

## 技術仕様

- HTML5
- CSS3
- JavaScript
- [Web Speech API](https://developer.mozilla.org/ja/docs/Web/API/Web_Speech_API)

## ブラウザ対応状況

- Google Chrome: ✅ 完全対応
- Microsoft Edge: ✅ 対応
- Firefox: ⚠️ 一部機能に制限あり
- Safari: ⚠️ 一部機能に制限あり

## 注意事項

- ブラウザによって音声認識の精度や対応状況が異なる場合があります。
- 最良の結果を得るために、Google Chrome の使用を推奨します。
- 音声認識には、デバイスのマイク使用権限が必要です。
