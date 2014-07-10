yokeuni2013
============

デジタルアーツ東京で2013年に作成したUnityの習作ゲームの資料とリソース。

Unity3.5用のため、Unity4.3以降に実装された2Dの機能は使われていない。新しいUnityで実装する場合は、以下の配慮が必要。

- 2DはSpriteに書き換える。
- シーンの切り替えに利用しているSetActiveRecursively(bool)は、SetActive(bool)に書き換える。

