# pAIrs - 画像選別アプリ

マッチングアプリのような直感的なUIで画像を簡単に振り分けることができるアプリケーションです。

## 機能

- 画像フォルダをドラッグ＆ドロップまたは選択して読み込み
- 左右キーまたはボタンで画像を「Like」「Dislike」に振り分け
- 進捗バーで処理状況を確認
- ピンク基調のかわいらしいUI

## 必要要件

- Python 3.8以上
- pip（Pythonパッケージマネージャー）

## 使用方法

### 実行可能ファイル（推奨）
1. [Releases](https://github.com/yourusername/pAIrs/releases)から最新のpAIrs.exeをダウンロード
2. ダウンロードしたpAIrs.exeをダブルクリックして実行

### ソースコードから実行
1. リポジトリをクローン
```bash
git clone https://github.com/yourusername/pAIrs.git
cd pAIrs
```

2. 仮想環境を作成して有効化
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # macOS/Linux
```

3. 必要なパッケージをインストール
```bash
pip install -r requirements.txt
```

4. アプリケーションを起動
```bash
python main.py
```

2. 画像の振り分け
- 画像フォルダを直接ウィンドウにドラッグ＆ドロップするか、「フォルダを選択」ボタンから選択
- 左右キーまたはボタンで画像を振り分け
  - →キー または ハートボタン：画像を「Like」に振り分け
  - ←キー または ゴミ箱ボタン：画像を「Dislike」に振り分け

3. 設定のカスタマイズ
設定タブで以下の項目をカスタマイズ可能：
- ファイル操作モード（移動/コピー）
- 出力フォルダの指定
- キーボードショートカット

## 対応画像フォーマット

- JPEG (.jpg, .jpeg)
- PNG (.png)
- GIF (.gif)
- BMP (.bmp)
- WebP (.webp)

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。
