# virtualMotorNerve-spec

## 概要

このページでは、Virtual Motor Nerve の概要と、大まかな指針を説明します。

Virtual Motor Nerve は、以下の二つを目的としたツールです。

* 現実世界の様々なデバイス (e.g. Keyboard, Camera, Smartphone, Tablet, et al.) からの情報群をバーチャル世界に入力し、影響を与えること
* バーチャル世界の情報群を現実世界で観測可能にすること

## 背景

2017 年から、多くのバーチャル実体 (i.e. VTuber, Vの者, バーチャルライバー) が現実世界から観測できるようになりました。しかし、バーチャル実体を現実世界で観測出来るようにするためには多くのコストと技術力が必要になります。また、これらを実現するソフトウェアには自由な実装が未だ多くありません。

## 本プロジェクト群の目的

Virtual Motor Nerve は、簡単にバーチャル実体を観測出来るようにするソフトウェアを、より多くの人が利用できることを目的とします。

## 本ドキュメントの構成

* Virtual Motor Nerve の構成
* 中央サーバーが提供するインターフェース
* 入力端末が送信する情報
* 表示クライアントが受け入れる情報

|Version|Note|
|:---|:---|
|v0.0.1-pre|initial|