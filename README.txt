// Cordova プロジェクトの作成

「ターミナル」起動
↓
$ cd Developer
↓
~Developer$ cordova create app01 com.example.myApp01 HelloWorld -d
/*
	cordova create：プロジェクトを作成するためのコマンド
	app01：プロジェクト用に作成するフォルダ名（任意の命名）
	com.example.myApp01：Javaパッケージ命名規約に沿った パッケージ名 (Android アプリで必要)（任意の命名）
	HelloWorld：プロジェクト名（任意の命名）
	-d：途中経過を表示するスイッチ
 */
↓
プラットフォーム用ファイルの追加
~Developer$ cd app01
↓
/*
	Android：$ cordova platform add android
	iOS：$ cordova platform add ios
	Windows：$ cordova platform add windows
*/

// vscode で開く

~app1$ code .

※コマンドでvscodeが立ち上がらなければvscodeから手動でOK

// vscode でのビルド／デバッグ

表示 > コマンドパレット > Cordova: Build
表示 > コマンドパレット > Cordova: Run
