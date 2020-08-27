# vscode_as3_air_desktop_project_template

Action Script 3.0 (Adobe Air Desktop) のプロジェクトテンプレ。
バイナリファイルを除くための.gitignore, 自前の簡易テスト用クラス付き。

.vscode/launch.json に設定が２種類あり、プログラムのエントリーポイントを Main.as か Tester.as か選べる。
Tester.as の方はテスト用のクラスを記述して使用。asconfig が2つあるのもこのため。

もし使用する AIRSDK のバージョンが変化したらapplication.xml のバージョンナンバーの部分も変更して使う。
現時点ではとりあえず 32.0 で指定してある。適宜変更する。

2020/08/28 .vscode/settings.json ファイルを git 管理から除外。
このファイルには現状SDKのパスが書いてあるが、PC毎にこのパスが変わったりするため除外。
VSCode でフォルダーを開いたら、画面右下の "No SDK" をクリックすれば、settings.json をソフトが生成してくれるのでこれを使用する。
