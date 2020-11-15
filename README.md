# TFjs-demoapp-netlify

TensorFlow.jsの[DEMOアプリ](https://github.com/tensorflow/tfjs/tree/master/tfjs-converter/demo/mobilenet)をNetlifyにデプロイしたものです。詳細は以下に記載しました。

[Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる（６）Windows10にTensorFlow.jsの環境構築とDEMOアプリのNetlifyへのデプロイ](https://i-doctor.sakura.ne.jp/font/?p=45117)



## デプロイしたもの

https://infallible-albattani-46b033.netlify.app/

## Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる 目次

[（１）LobeのインストールからTensorFlowモデルのエクスポートまで](https://i-doctor.sakura.ne.jp/font/?p=44635)

[（２）Windows10でPython3.6+TensorFlow1.15をセットアップ](https://i-doctor.sakura.ne.jp/font/?p=44703)

[（３）Windows10ローカル環境でtf_example.pyを実行](https://i-doctor.sakura.ne.jp/font/?p=44808)

[（４）Windows10ローカル環境でFlaskを用いて画像判定](https://i-doctor.sakura.ne.jp/font/?p=44883)

[（５）FlaskアプリをHerokuにデプロイ](https://i-doctor.sakura.ne.jp/font/?p=44947)

[（６）Windows10にTensorFlow.jsの環境構築とDEMOアプリのNetlifyへのデプロイ](https://i-doctor.sakura.ne.jp/font/?p=45117)

## 実行方法

`git clone https://github.com/adash333/TFjs-demoapp-netlify.git`

Run `yarn`

Run `yarn mobilenet` to predict.(Windowsローカル環境)   
(Macでは、package.jsonの、"scripts"の中の"mobilenet":　の部分を[こちら](https://qiita.com/tato_lol/items/b879bea1bf699a5ea5ff)を参考に修正してください。)


## 開発環境

```
Windows10 Pro
VisualStudioCode 1.51.0
Git for Windows v2.29.2
python 3.6
pip 20.2.4
pipenv 2020.11.4

nvm-windows 1.1.7
node v14.15.0
npm 6.14.8
yarn 1.22.10
Visual Studio Community 2019 + "Desktop development with C++" (約8GB)
parcel-bundler 

(仮想環境)
python 3.6
TensorFlow 1.15.3
pillow 7.2.0
autopep8
flake8
mypy
```