# スキルとスキルを交換するサービス

## フロントエンド 環境構築

### AngularJs(macOS編)

**Node.jsのインストール**

macOSでNode.jsをインストールをするには、**[Homebrew]** および **[nodebrew]** を利用する。

1. Xcodeのインストール
 brewのインストールには「Xcode」が必要。
 以下、コマンドを実行し、インストールされているか確認。

 `$ xcode-select --install`

 下記メッセージが表示されれば、OK。
 インストールされていない場合は、プロンプトが表示されて、インストールを促されるので、それに従いインストールする。

 `xcode-select: error: command line tools are already installed, use "Software Update" to install updates`


2. Homebrewのインストール

 以下、コマンドを実行。
 リポジトリの場所が変更される可能性がある為、公式サイトに掲載されているコマンドの実行を推奨。

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

[Homebrew(公式)](https://brew.sh/index_ja.html)

3. nodebrewのインストール

 以下、コマンドを実行。

`brew install nodebrew`

4. nodebrewを利用して、node.jsの最新版をインストール

 以下、コマンドを実行。

 `nodebrew install-binary latest`

 以下、コマンドを実行し、`current` を確認

 `nodebrew list`

 `current: none` だった場合

 以下、コマンドを実行。
 
 `node use v0.0.0`
 *v0.0.0には、使用するバージョンを指定する。
