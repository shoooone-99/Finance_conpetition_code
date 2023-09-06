# コンペ概要
住宅ローンの延滞者の予測というタスクになります。 
住宅ローン契約者の金融関連の時系列データが与えられ、そのデータを用いてモデルを作成します。
具体的なデータの内容としては、住宅ローン契約者口座残高、引き落とし回数などが、月ごとの時系列データとして与えられております。

# 評価関数
AUC（Area Under the Curve）を使用

# 実装方法
前処理、学習、予測、の3つにコードを分け実装

①Preprocessing「前処理」

提供データを読み込み、前処理を施し、モデルに入力が可能な状態に変換するモジュール。
　
②Learning「学習」

①の出力を読み込み、モデルを学習し、学習済みモデルを出力するモジュール。

③Predicting「予測」

①で作成した評価要データ及び②で作成した学習済みモデルを読み込み、予測結果を出力するモジュール。

上記3つを、セルに分ける

# モデル作成にあたり工夫したポイント

##

"hoge"のセールスポイントや差別化などを説明する

# Requirement

"hoge"を動かすのに必要なライブラリなどを列挙する

* huga 3.5.2
* hogehuga 1.0.2

# Installation

Requirementで列挙したライブラリなどのインストール方法を説明する

```bash
pip install huga_package
```

# Usage

DEMOの実行方法など、"hoge"の基本的な使い方を説明する

```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```

# Note

注意点などがあれば書く

# Author

作成情報を列挙する

* 作成者
* 所属
* E-mail

# License
ライセンスを明示する

"hoge" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

社内向けなら社外秘であることを明示してる

"hoge" is Confidential.
