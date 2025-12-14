# Frame Compositor (Magic Wand Edition)

ユーザーがアップロードした「白枠付きイラスト（フレーム）」の白部分を自動選択・透明化し、その背面に「写真」を合成できるWebアプリです。

![Screenshot](https://dummyimage.com/600x400/203a43/fff&text=App+Screenshot)

## 特徴
- **単一ファイル**: HTMLファイル1つだけで動作します。
- **Magic Wand (自動選択ツール)**: クリックした箇所の似た色を自動で計算して透過します。
- **許容値調整**: 色の近似判定をスライダーで調整可能。
- **Glassmorphism Design**: モダンですりガラスのような美しいUI。
- **プライバシー**: すべての画像処理はブラウザ内で行われ、サーバーにアップロードされることはありません。

## 使い方
1. [Demo / App Link](https://cervelo874-dev.github.io/frame-compositor/) (※GitHub Pages設定後に有効になります)
2. `index.html` をブラウザで開きます。
3. **フレーム画像**をアップロードします。
4. 画像の透過したい部分（白い背景など）を**クリック**します。
5. **写真**をアップロードし、配置やサイズを調整します。
6. 「画像を保存」ボタンでPNGとしてダウンロードします。

## 開発
- Canvas操作に [Fabric.js](http://fabricjs.com/) を使用しています。
- 外部ライブラリはCDN経由で読み込んでいます。

## ライセンス
MIT
