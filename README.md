# KotlinRoomMigrationSample
Sample for migrating SQLiteDatabase to Room with Kotlin.

## About this project.
このサンプルは、Google公式のSQLiteDatabaseからRoomへの移行サンプルをKotlinに移植したものです。

This project was forked from Google's migration sample.

[Room Migration Sample](https://github.com/android/architecture-components-samples/tree/master/PersistenceMigrationsSample)

## Branches

ブランチの説明

### master
オリジナルのJavaのサンプルコードそのままです。
Same as original Java sample.

### Robolectric
androidTestにあるソースをtestに移動し、Robolectricで動くようにしました。
Migrate androidTests to unit test by using Robolectric.

### kotlin
Kotlinに変換したサンプルです。
A sample of migrating to Kotlin.

*WIP*

### kotlin_with_lib
Kotlinに変換し、さらにdatabaseのあるモジュールをライブラリに分けたサンプルです。
A sample of separating database classed into library modules.

*WIP*