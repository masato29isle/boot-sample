# Spring-Boot サンプルアプリケーション

## 概要
* Spring-Bootをベースにて作成したサンプルアプリケーションです
* swagger-uiにて作成したAPIの実行が可能です

## アプリケーション起動方法
プロジェクト直下にて以下コマンドを入力してください  
(もちろんIDEを通しての実行でもOK)

* gradleコマンドがインストール済みである場合
```
gradle boot-sample:bootrun 
```

* gradleコマンドがインストール済みでない場合
```
[mac/Linux]
./gradlew boot-sample:bootrun 

[windows]
./gradlew.bat boot-sample:bootrun  
```

## 使用言語およびフレームワーク
* Java : 11
* Spring Boot : 2.7.7
* MyBatis : 3.5.11

## その他
* 学習用サンプルとしてactuatorのbeansを有効にしています
* swagger-uiのアクセスURLは以下になります  
http://{HOST名}:8080/swagger-ui/


