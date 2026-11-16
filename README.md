# お年玉ゲッター

Unityで制作した「お年玉ゲッター」のポートフォリオ用プロジェクトです。シーン、ゲームのスクリプト、入力・描画設定を収録しています。

[Judge.cs](Assets/Scripts/Judge.cs) では、Yahoo! JAPANのルビ振りAPIによる読み仮名の取得、先頭文字の判定、日本語版Wikipediaでの記事の存在確認を確認できます。

## Unityで開く

1. Unity Hubでこのフォルダを追加し、Unity 6000.3.2f1で開きます。
2. DOTweenを公式配布元からインポートしてセットアップし、TextMesh ProのEssential Resourcesをインポートします。Unity Package ManagerはPackagesの設定から依存パッケージを取得します。
3. `Assets/Scenes/Title.unity` を開きます。ルビ振りAPIを使う場合は、JudgeコンポーネントのInspectorから自身のYahoo! JAPANアプリIDを設定します。

元の画像・音声素材は収録していません。元の見た目や音を再現するには素材の再設定が必要です。
