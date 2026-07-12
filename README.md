# 浄化槽探索ゲーム REAL v4

フジクリーン CB-5 を題材にした教育用3D探索ゲームです。

## 最も簡単な公開方法（Netlify Drop）

1. このZIPを展開します。
2. Netlifyの「Deploy manually / Netlify Drop」を開きます。
3. 展開してできた `jokaso-real-v4-public` フォルダを、アップロード欄へドラッグ＆ドロップします。
4. 公開が完了すると、`https://xxxx.netlify.app` 形式のURLが発行されます。

※ スマートフォンでは、ZIPを「ファイル」アプリ等で展開してから、フォルダ内の全ファイルをアップロードしてください。PCの方が簡単です。

## GitHub Pagesで公開する方法

1. GitHubで新しいリポジトリを作成します。例: `jokaso-game`
2. このフォルダ内の全ファイルをリポジトリのルートへアップロードします。
3. リポジトリの `Settings` → `Pages` を開きます。
4. `Deploy from a branch` を選択します。
5. Branchを `main`、Folderを `/(root)` にして保存します。
6. 数分後、Pages画面に公開URLが表示されます。

URL例: `https://ユーザー名.github.io/jokaso-game/`

## 操作

- 移動: W/A/S/D または矢印キー
- 上下: R / F
- 視点: 画面をドラッグ
- 部品説明: 部品をクリックまたはタップ
- スマートフォン: 画面下の操作ボタン

## 注意

- Three.jsをCDNから読み込むため、プレイ時にはインターネット接続が必要です。
- メーカーCADの再配布ではなく、寸法・構造資料を参照した教育用の独自生成モデルです。
