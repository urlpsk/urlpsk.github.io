# GITALLER Gamepad Viewer CSS

## これはなに？

[Gamepad Viewer](https://gamepadviewer.com/) の [GITALLER](https://www.dj-dao.com/jp/gitaller) 用カスタムスキンCSSです。

[OBS Studio](https://obsproject.com/) による配信・録画映像にGITALLERの入力表示を追加できます。

![見た目](img/sample.png)

## 使い方

OBSの「ソース」追加で「ブラウザ」を選択し、プロパティのURLに以下の文字列を入力してください。

[https://gamepadviewer.com/?p=1&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2212%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2210%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2213%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2211%22%7D%5D%7D&css=https%3A%2F%2Furlpsk.github.io%2Fgamepad_viewer%2Fcss%2Fgitaller.css](https://gamepadviewer.com/?p=1&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2212%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2210%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2213%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2211%22%7D%5D%7D&css=https%3A%2F%2Furlpsk.github.io%2Fgamepad_viewer%2Fcss%2Fgitaller.css)

幅と高さは小さすぎなければ問題ありません。作成者は幅500、高さは150に設定しています。

表示遅延等を設定する場合は [https://gamepadviewer.com/#generate](https://gamepadviewer.com/#generate) の「Custom CSS URL」に [https://urlpsk.github.io/gamepad_viewer/css/gitaller.css](https://urlpsk.github.io/gamepad_viewer/css/gitaller.css)
を指定して生成されるURLを使用してください。 
また、ワイリングはDpadのUp/DownにRemapする必要があります。

## KONAMI PREMIUM コントローラ用URL

キーマップ設定を追加したKONAMI PREMIUMコントローラ用URLを作成してみました。ワイリングには未対応です。制作者はコントローラを所持していないので動作未確認です。  
[https://app.gpv.gg/?p=1&css=https%3A%2F%2Furlpsk.github.io%2Fgamepad_viewer%2Fcss%2Fgitaller.css+&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%220%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%224%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%221%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%223%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%222%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%222%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%223%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%220%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2211%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2212%22%7D%5D%7D](https://app.gpv.gg/?p=1&css=https%3A%2F%2Furlpsk.github.io%2Fgamepad_viewer%2Fcss%2Fgitaller.css+&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%220%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%224%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%221%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%223%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%222%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%222%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%223%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%220%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2211%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%2212%22%7D%5D%7D)

## 開発用リポジトリ

[https://github.com/urlpsk/gamepad_viewer](https://github.com/urlpsk/gamepad_viewer)

## 連絡先

Twitter [@K_YukiDaruma](https://twitter.com/K_YukiDaruma)