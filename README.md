# Welcome to the TechkidsCampTutorial wiki!

## 目次
* 概要
* 作成
* アップロード

### 概要
CAMPでは新知識の導入のために、makecodeの「チュートリアル」というフレームワークを使っています。
Minecraft内の画面で（＝POLTAに遷移することなく）、新たな知識やヒントを表示させることができます（画像参照）。

他にも、
* 管理者がプログラムに使用するブロックを制限する。
* あらかじめ作成したプログラムを表示する。
* gifファイルやpngファイル等を表示する。

などといったことができます。

### アップロード
全てのチュートリアルは、
```
開発者のローカル　→ GitHub Actions → makecode
```
という流れでアップされていきます。

1. 開発者のローカルでチュートリアルファイルを作成し、ルートディレクトリ直下に保存します。

2. pxt.jsonに作成したファイルを追加します。

3. GitHubのリポジトリに作成したファイルをPushします。

4. GitHub Actionsが実行されるので、終わるまで待機します。

5. ビルドが完了したら、<https://minecraft.makecode.com/#tutorial:https://github.com/qureo-inc/QureoTutorial-stg-en/[チュートリアルファイルの名前]>にチュートリアルがデプロイされています！
