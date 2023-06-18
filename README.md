- 👋 Hi, I’m @Nikki800
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Nikki800/Nikki800/_c01

ALL TEST accunt.
 
is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
git remote add origin https://github.com/GhGh0621OO/C-
git push -u origin ブランチ名

ブランチ名の作成は？

ChatGPT
ブランチを作成するには、以下のコマンドを使用します。

Copy code
git branch ブランチ名
ブランチ名は新しく作成するブランチの名前です。例えば、feature/my-featureという名前のブランチを作成する場合、以下のようにコマンドを実行します。

bash
Copy code
git branch feature/my-feature
ブランチを作成した後、作成したブランチに切り替えるにはgit checkoutコマンドを使用します。

Copy code
git checkout ブランチ名
例えば、feature/my-featureブランチに切り替える場合は以下のようになります。

bash
Copy code
git checkout feature/my-feature
また、ブランチを作成しながら直接切り替えるにはgit checkoutコマンドの-bオプションを使用します。

css
Copy code
git checkout -b ブランチ名
例えば、feature/my-featureブランチを作成しながら直接切り替える場合は以下のようになります。

bash
Copy code
git checkout -b feature/my-feature
以上のコマンドを使用することで、新しいブランチを作成し、切り替えることができます。

Gitで現在のリポジトリやブランチの構造を表示するためのコマンドは以下の通りです。

リポジトリの表示:

Copy code
git remote -v
上記のコマンドを実行すると、現在のリポジトリに関連付けられたリモートリポジトリの情報（URLなど）が表示されます。

ブランチの表示:

Copy code
git branch
上記のコマンドを実行すると、現在のリポジトリ内のすべてのブランチが表示されます。アスタリスク (*) が付いているブランチが現在の作業中のブランチです。

ブランチとその最新のコミットの表示:
			origin	https://github.com/GhGh0621OO/C- (fetch)
			origin	https://github.com/GhGh0621OO/C- (push)


Copy code
git branch -v
上記のコマンドを実行すると、ブランチ名とそれぞれの最新のコミットのハッシュ値、コミットメッセージが表示されます。

リモートブランチの表示:

Copy code
git branch -r
上記のコマンドを実行すると、リモートリポジトリ内のブランチ一覧が表示されます。

これらのコマンドをターミナルで実行することで、Gitリポジトリやブランチの構造を確認することができます。

------------------------

origin	https://github.com/GhGh0621OO/C- (fetch)
origin	https://github.com/GhGh0621OO/C- (push)
の意味は？

ChatGPT
origin https://github.com/GhGh0621OO/C- (fetch)
origin https://github.com/GhGh0621OO/C- (push)

これらは、git remote -vコマンドを実行した際に表示されるリモートリポジトリの情報です。

origin: リモートリポジトリの名前です。通常、初期設定では"origin"という名前が使用されますが、任意の名前に変更することもできます。
https://github.com/GhGh0621OO/C-: リモートリポジトリのURLです。このURLは、リポジトリがホストされている場所を示しています。
(fetch)と(push)は、リモートリポジトリへの操作のタイプを示しています。具体的には以下のような意味を持ちます:

(fetch): リモートリポジトリからのデータの取得（フェッチ）が可能です。つまり、git fetchコマンドを使用してリモートリポジトリから最新のコミットを取得できます。
(push): ローカルリポジトリからリモートリポジトリにデータを送信（プッシュ）できます。つまり、git pushコマンドを使用してローカルの変更をリモートリポジトリに反映できます。
これらの情報は、リモートリポジトリとのやり取りを行う際に使用される重要な情報です。

-------------------------


プルリクエストの詳細を閲覧するコマンドはありますか

ChatGPT
プルリクエストの詳細を直接閲覧するためのコマンドはありません。プルリクエストの詳細は通常、コードホスティングプラットフォームのウェブインターフェースで表示されます。具体的には、GitHubやGitLabなどのプラットフォームのウェブサイトにログインし、該当するリポジトリやプルリクエストのページを開く必要があります。

例えば、GitHubの場合、プルリクエストの詳細を閲覧するには以下の手順を実行します:

ブラウザでGitHubのウェブサイトにアクセスします。
リポジトリのページに移動し、プルリクエストのタブを選択します。
閲覧したいプルリクエストをクリックします。
プルリクエストの詳細ページが表示されます。ここで変更内容やコメント、承認の状況などを確認することができます。
上記の手順はGitHubの場合ですが、他のコードホスティングプラットフォームでも同様の手順でプルリクエストの詳細を閲覧することができます。各プラットフォームにはそれぞれ独自のUIがありますので、詳細を閲覧するためには各プラットフォームの提供するウェブインターフェースを使用する必要があります。

///////////////////////////////

GitHubで「具体的なブランチ操作権限（読み取りのみ）」のコマンドは？

ChatGPT
GitHubにおいて、ブランチ操作権限の具体的なコマンドはありません。GitHubでは、ブランチのアクセス権限を管理するために以下の手順を使用します:

リポジトリの設定を開く: GitHub上で対象のリポジトリにアクセスし、リポジトリのメインページに移動します。

Settings（設定）をクリックする: リポジトリのメインページの上部にあるタブの中にSettings（設定）がありますので、それをクリックします。

Manage Access（アクセスの管理）をクリックする: 左側のサイドバーからManage Access（アクセスの管理）を選択します。

ユーザーやチームの権限を編集する: 画面にはリポジトリにアクセスしているユーザーやチームの一覧が表示されます。読み取り専用の権限を与えたいユーザーまたはチームを選択し、適切な権限を設定します。

GitHubの場合、ブランチのアクセス権限はリポジトリ全体の設定として管理されます。個別のブランチに対して読み取り専用のアクセス権限を与えるためには、対象のブランチを保護ルールとして設定する必要があります。保護ルールにより、指定したブランチへの直接の書き込みやマージを制限できます。

具体的な手順や設定方法はGitHubのドキュメンテーションを参照してください。

================================


「
nikkirauda@nikkirauda-iMac:~$ git branch
* _b00
  _b01
  master
」
で、_b00にPCのデスクトップにある「TEST.txt」をリモートリポジトリに
新規追加するコマンドは？
ChatGPT
_b00 ブランチにデスクトップにある TEST.txt ファイルをリモートリポジトリに新規追加するためには、以下のコマンドを実行します。

ファイルをステージングエリアに追加します:

git add /home/nikkirauda/デスクトップ/TEST.txt
コミットを作成します:

git commit -m "Add TEST.txt file"
ローカルの _b00 ブランチをリモートの対応するブランチにプッシュします:

git push origin _b00

上記のコマンドを順番に実行することで、TEST.txt ファイルが _b00 ブランチにコミットされ、リモートリポジトリに新規追加されます。プッシュする際には、対象のリモートリポジトリ名（ここでは origin）とブランチ名（_b00）を指定してください。

+++++++++++++++++++++++++++++++++



Gitで現在のリポジトリやブランチの構造を表示するためのコマンドは以下の通りです。

リポジトリの表示:

Copy code
git remote -v
上記のコマンドを実行すると、現在のリポジトリに関連付けられたリモートリポジトリの情報（URLなど）が表示されます。

ブランチの表示:

Copy code
git branch
上記のコマンドを実行すると、現在のリポジトリ内のすべてのブランチが表示されます。アスタリスク (*) が付いているブランチが現在の作業中のブランチです。

ブランチとその最新のコミットの表示:

Copy code
git branch -v
上記のコマンドを実行すると、ブランチ名とそれぞれの最新のコミットのハッシュ値、コミットメッセージが表示されます。

リモートブランチの表示:

Copy code
git branch -r
上記のコマンドを実行すると、リモートリポジトリ内のブランチ一覧が表示されます。

これらのコマンドをターミナルで実行することで、Gitリポジトリやブランチの構造を確認することができます。


********************************

nikkirauda@nikkirauda-iMac:~$ git push origin _b00
Username for 'https://github.com': GhGh0621OO
Password for 'https://GhGh0621OO@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/GhGh0621OO/C-/'
nikkirauda@nikkirauda-iMac:~$ git push origin _b00
Username for 'https://github.com': GhGh0621OO
Password for 'https://GhGh0621OO@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/GhGh0621OO/C-/'


--------------------------------
このエラーメッセージは、GitHubが2021年8月13日以降、パスワード認証をサポートしていないことを示しています。代わりに、推奨される認証方法を使用する必要があります。

推奨される認証方法の一つは、SSHキーを使用する方法です。SSHキーを設定すると、GitHubとの通信が安全に行われ、パスワードの入力なしでリポジトリにアクセスできます。

以下は、SSHキーを設定する手順の概要です：

SSHキーペアを生成します。ターミナルで以下のコマンドを実行します。

/////////////////////////////////

以下は、SSHキーを設定する手順の概要です：

SSHキーペアを生成します。ターミナルで以下のコマンドを実行します。

bash
Copy code
ssh-keygen -t ed25519 -C "your_email@example.com"
ssh-keygen -t ed25519 -C "saisai0731@gmail.com"

必要に応じて、メールアドレスの部分をご自身のメールアドレスに置き換えてください。

SSHキーペアをGitHubに登録します。
公開鍵をクリップボードにコピーして、GitHubの設定ページにアクセスし、SSHキーを追加します。

詳しい手順は、GitHubの公式ドキュメントを参照してください。

リモートリポジトリのURLをSSH形式に変更します。
リモートリポジトリのURLを次のように変更します。

bash
Copy code
git remote set-url origin git@github.com:GhGh0621OO/C-.git
ご自身のGitHubユーザー名とリポジトリ名に応じて、上記のコマンドを適宜変更してください。

これでSSHキーを使用してGitHubリポジトリにアクセスする準備が整いました。
再度、git pushコマンドを実行してみてください。SSHキーが正しく設定されていれば、認証エラーは発生しないはずです。



+++++++++++++++++++++++++++++++++

ssh-keygen -t ed25519 -C "your_email@example.com"の「-t ed25519 」の指定はどういう意味

ChatGPT
-t ed25519は、SSHキーペアの暗号化アルゴリズムを指定するオプションです。この場合、Ed25519アルゴリズムを使用してSSHキーペアを生成することを意味します。

Ed25519は、高速でセキュアな暗号化アルゴリズムの一つであり、SSHキーペアの生成に広く使用されています。このアルゴリズムは、セキュリティと性能の両方の要件を満たし、一般的に推奨されるSSHキーペアの暗号化アルゴリズムとなっています。

ですので、ssh-keygen -t ed25519 -C "your_email@example.com"コマンドを実行することで、Ed25519アルゴリズムを使用したSSHキーペアが生成されます。


&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

Enter passphrase (empty for no passphrase): 
ですが、ここでは何を入力するのですか

ChatGPT
Enter passphrase (empty for no passphrase)のプロンプトでは、秘密鍵に設定するパスフレーズを入力するためのものです。

パスフレーズは秘密鍵の利用時に要求されるパスワードのようなもので、秘密鍵の保護とセキュリティを向上させるために使用されます。パスフレーズは任意の文字列を入力することができますが、長くて複雑なパスフレーズを使用することをお勧めします。

もしパスフレーズを設定したくない場合は、何も入力せずにそのままEnterキーを押すことで空のパスフレーズを設定することができます。ただし、パスフレーズを設定しない場合、秘密鍵が盗まれた場合により大きなセキュリティリスクが生じる可能性があるため、慎重に判断してください。

==================================


「Your identification has been saved in /home/nikkirauda/.ssh/my_key
Your public key has been saved in /home/nikkirauda/.ssh/my_key.pub
The key fingerprint is:
SHA256:4UWbX6GakSm7yYFzlDs84P7XA8VtLTQv601l2ujHLLk saisai0731@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|          .   .  |
|         o = .o. |
|      . = B..o.+ |
|     . * * =o.= =|
|      + S o... O.|
|     . + *.   + o|
|      . +  o o * |
|       .  . o = =|
|        ..   .E+ |
+----[SHA256]-----+
」とでますが、どういう意味ですか？

ChatGPT
これは、ssh-keygenコマンドによって生成されたSSHキーに関する情報です。

Your identification has been saved in /home/nikkirauda/.ssh/my_key: 生成された秘密鍵の保存先を示しています。
ここで指定したパスに秘密鍵が保存されます。
Your public key has been saved in /home/nikkirauda/.ssh/my_key.pub: 生成された公開鍵の保存先を示しています。

公開鍵は秘密鍵に対応し、他のサーバーに公開して接続する際に使用されます。
The key fingerprint is: SHA256:4UWbX6GakSm7yYFzlDs84P7XA8VtLTQv601l2ujHLLk saisai0731@gmail.com: 
公開鍵の指紋を示しています。指紋は鍵の一意の識別子であり、セキュリティの目的で使用されます。

The key's randomart image is: ...: 公開鍵のランダムアートイメージです。視覚的な表現であり、
公開鍵の一意性を確認するために使用されます。

これらの情報は、SSHキーの生成と保存が正常に行われたことを示しています。秘密鍵は安全に保管し、
公開鍵を必要なサーバーやサービスに提供して利用することができます。




###################################


ED25519 256の意味は？

ChatGPT
ED25519 256は、ED25519鍵アルゴリズムの鍵の長さを表しています。

ED25519は、楕円曲線暗号に基づく公開鍵暗号方式であり、鍵の長さは256ビットです。これは、鍵の強度やセキュリティレベルを示しています。より長い鍵は一般的により強力であり、より高いセキュリティを提供します。

ED25519は、高速でセキュアな鍵の生成と認証を可能にするために設計されており、一般的にSSH鍵として使用されます。その短い鍵の長さにもかかわらず、非常に強力なセキュリティを提供するため、広く採用されています。


--------------------------------------


SHA256とはどういう意味ですか

ChatGPT
SHA-256（Secure Hash Algorithm 256-bit）は、256ビットの長さを持つハッシュ関数です。

SHA-256は、データの一意のハッシュ値を計算するために使用されます。ハッシュ関数は、任意のサイズのデータを固定サイズのハッシュ値に変換する数学的なアルゴリズムです。SHA-256は、データの内容がわずかにでも変更されると異なるハッシュ値が生成される性質を持っています。

SHA-256は、セキュリティやデータ整合性の検証、デジタル署名、データベースの索引作成など、さまざまな用途で使用されます。特に、SSL/TLSプロトコルや電子メールの署名など、セキュリティ関連の領域で広く採用されています。SHA-256は、SHA-2ファミリーの一部であり、より強力なセキュリティを提供するために設計されたハッシュ関数です。



======================================



これらのキーを使って
git push origin _b00
コマンド実行する手順は？

ChatGPT
以下は、SSHキーを使用してGitリポジトリにプッシュする手順です。

SSHキーの公開鍵をGitHubに追加します。

公開鍵の内容は、~/.ssh/my_key.pub ファイルに保存されています。
GitHubのウェブサイトにログインし、アカウントの設定に移動します。

SSHとGPGキーのセクションに進み、新しいSSHキーを追加します。公開鍵の内容を入力します。

GitリポジトリのリモートURLをSSH形式に変更します。

ターミナルで、以下のコマンドを実行します。

kotlin

Copy code

git remote set-url origin git@github.com:GhGh0621OO/C-.git

SSHキーを使用してプッシュします。

ターミナルで、以下のコマンドを実行します。
perl
Copy code
git push origin _b00
SSHキーに関連付けられたパスフレーズが求められる場合は入力します。
これにより、SSHキーを使用してGitリポジトリにプッシュすることができます。


*****************************************



プルリクエスト
課題
コードスペース
マーケットプレイス
エクスプロア
 
@GhGh0621OO 
二要素認証（2FA）の有効化
2
3
リカバリーコードをダウンロードする
リカバリーコードは、デバイスにアクセスできなくなった場合の第二認証要素として使用できます。
1Password、Authy、Keeperなどの安全なパスワードマネージャで保存することをお勧めします。

リカバリーコードは安全な場所に保管してください
端末を紛失し、リカバリーコードをお持ちでない場合は、アカウントにアクセスできなくなります。
a7a9e-b2513
6a1fb-de080
a0bef-a45cb
fb3bf-5478f
766e8-4685c
a6cfe-24b18
19348-66e8a
33b3e-7a79f
b7384-f5c71
61c0c-235be
128f1-21efd
5678d-28386
cb2aa-3f4a0
bcf55-739e3
7d805-a5e32
ab3e2-82023

***************************************************************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************

nikkirauda@nikkirauda-iMac:~$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/home/nikkirauda/.ssh/id_rsa): 

上記のメッセージは、SSHキーペアの生成が正常に完了したことを示しています。

Your identification has been saved in /home/nikkirauda/.ssh/id_rsa: 秘密鍵（identity）が /home/nikkirauda/.ssh/id_rsa に保存されました。
Your public key has been saved in /home/nikkirauda/.ssh/id_rsa.pub: 公開鍵が /home/nikkirauda/.ssh/id_rsa.pub に保存されました。
The key fingerprint is:: キーの指紋情報が表示されます。これはキーの一意性を確認するために使用されます。
The key's randomart image is:: キーのランダムアートイメージが表示されます。視覚的な識別情報として使用されます。
ssh-keygen -t ed25519 -C "ms0726967323@outlook.jp"

Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/nikkirauda/.ssh/id_ed25519
Your public key has been saved in /home/nikkirauda/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:YWLOBnpo9papFa8fKBOi7wWis7d9YSdO53/gu+gZ27Y ms0726967323@outlook.jp
The key's randomart image is:
+--[ED25519 256]--+
|                 |
|                 |
|    . o o        |
|   o = o .       |
|o B o + S        |
|o= = B= o .      |
|+ o O+o*.. .     |
| +.O .o..*o .    |
|.o=.oo..=oE=     |
+----[SHA256]-----+
nikkirauda@nikkirauda-iMac:~$ cd ~/.ssh
nikkirauda@nikkirauda-iMac:~/.ssh$ ls
id_ed25519  id_ed25519.pub  id_rsa  id_rsa.pub  my_key  my_key.pub
nikkirauda@nikkirauda-iMac:~/.ssh$ ls -l
合計 24
-rw------- 1 nikkirauda nikkirauda  419  6月 18 14:16 id_ed25519
-rw-r--r-- 1 nikkirauda nikkirauda  105  6月 18 14:16 id_ed25519.pub
-rw------- 1 nikkirauda nikkirauda 2610  6月 18 14:11 id_rsa
-rw-r--r-- 1 nikkirauda nikkirauda  580  6月 18 14:11 id_rsa.pub
-rw------- 1 nikkirauda nikkirauda  464  6月 18 10:07 my_key
-rw-r--r-- 1 nikkirauda nikkirauda  102  6月 18 10:07 my_key.pub
nikkirauda@nikkirauda-iMac:~/.ssh$ 

ちゃんと、id_rsa（秘密鍵）と、id_rsa.pub（公開鍵）が保存されていました！

秘密鍵は誰かに教えちゃいけないらしいです（自明）

*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
*****************************************	**********************************************************************************
# Gitをインストールされているか確認
sudo apt install -y git
git --version


#　ユーザー名/メールアドレスの設定
			ユーザー名、メールアドレスの設定は、commitした際に使用されるため設定が必須です。

#ユーザー名の設定
			git config --global user.name "あなたの名前"

#メールアドレス
			git config --global user.email YourMailAddress@gmail.com

# Proxyの設定(必要な環境のみ)
			会社等でProxyサーバー経由で外部ネットワークにアクセスする場合は、
			GitにProxy設定をする必要があります。

# Proxy設定
			git config --global http.proxy http://[username]:[password]@[proxy_server名]:[ポート番号]
			git config --global https.proxy http://[username]:[password]@[proxy_server名]:[ポート番号]

# 設定結果の確認
			設定の一覧を確認するコマンドは以下です。
			git config --list

ANS===
nikkirauda@nikkirauda-iMac:~/.ssh$ 

git config --list

user.email=saisai0731@gmail.com
			user.name=キンちゃん
			credential.helper=cache --timeout=3600
			core.repositoryformatversion=0
			core.filemode=true
			core.bare=false
			core.logallrefupdates=true
			remote.origin.url=https://GhGh0621OO:gHgH0621@https://github.com/GhGh0621OO/C-
			remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
ANS===

cloneしてみる
			早速、公開リポジトリをcloneしてみましょう。
			何でもよいのですが、今回は
			[
				googleが提供しているログモジュールglog]
				をクローンしてみます。

# 適当なディレクトリに移動
			mkdir work/git
			cd work/git

#clone を実行
			git clone https://github.com/google/glog.git
			
# *************************************************************************************************************************************************************************
*************************************************************************************************************************************************************************

cat /home/nikkirauda/.ssh/id_rsa.pub

AAAAB3NzaC1yc2EAAAADAQABAAABgQCdJJYS8kV/+UO1YuF9vAMYsYaLU89gJRWpOmPd2GFls5fpcK5suStCugkBXJlLlDCRiMEisI5wZaeexH1/ZoT5ReNxtGqXwrVsiZHP/7dRQhTQWIwPhilMlN0MCQFuVxvmp1LvvFMc7JRixCD4+f1SK/J2l88KJdvYSn5aTtcczf9JgJC0awLfJrqUalDq6Z9OmPniD6+BazH8u/osXdLvewIQNV1hnbSDOQv/sgERQUX4WL2uTG84SIlq/vHu5TV8vvxsVaUH4JLPdeA96WeuNV6WwivS66V3EPUD2Uo5RlFNtFFrq0Mr3w2QSRB3cz4Gwav5fFM6o4tYEifrPexRfWjONbAvmozJqMNYIQA6TyzDVIFoVBRzpnFET9mp9WMzJi0VCV/JYKsj9mD+5IoVKy6nEM/qSOcFeVTGzXqO8iXSDpEf7I51y4oEW568BL4z3tSQFLXj5b5OGAEUwI6twdrZtyiDXhmkUz9dhJFfR17h+7hag3TEu7/Nt3wVTSc= nikkirauda@nikkirauda-iMac
*************************************************************************************************************************************************************************
#　SSHキー追加
			SSHキー/新規追加で
				Authentication Key
				Signing Key
				のどっちをえらんだらいいか
			ChatGPT
			SSHキーの新規追加時には、「Authentication Key」を選択する必要があります。

			「Authentication Key」は、SSH接続時のユーザー認証に使用されるキーです。公開鍵と秘密鍵のペアで構成されており、
			公開鍵はサーバーに登録しておくことで、サーバー側でのユーザーの認証に使用されます。

			一方、「Signing Key」は、デジタル署名などの用途に使用されるキーです。
			データの完全性や認証を保証するために使用されますが、SSH接続においてはユーザー認証には関与しません。

			したがって、SSH接続に使用するための新しいキーペアを作成する場合は、「Authentication Key」を選択してください。

#　SSHキー追加の確認
			
SSHキー追加の確認は？

			ChatGPT
			SSHキーの追加が正しく行われたかどうかを確認するには、以下の手順を参考にしてください：

			ターミナルを開きます。
			
			ssh-add -l 
		
			コマンドを実行します。
			
			キーペアに関連付けられたSSHキーが表示されれば、追加が正常に行われています。
			SSHキーは、キーペアの秘密鍵が適切に設定されている場合にのみ表示されます。
			また、SSHキーの追加が成功した場合でも、接続するリモートサーバーでそのキーが受け入れられている必要があります。
			リモートサーバーに接続する際に問題が発生する場合は、サーバーのSSH設定や公開鍵の確認も行ってください。

なお、SSHキーの追加がうまくいかない場合は、設定やパーミッションの問題が考えられますので、詳細なエラーメッセージやログを確認することをおすすめします。

結果

			ssh-add -l コマンドの実行結果を見ると、3つのSSHキーが追加されていることが分かります。

			saisai0731@gmail.com に関連付けられたED25519形式のSSHキー
			ms0726967323@outlook.jp に関連付けられたED25519形式のSSHキー
			9 に関連付けられたRSA形式のSSHキー
			これらのキーは正常に追加されており、SSH接続に使用することができます。キーの表示には、キーペアの公開鍵のハッシュと関連する識別情報が含まれています。

			もし接続するリモートサーバーで問題が発生する場合は、SSHキーがサーバーに登録されているか、またはサーバーのSSH設定が正しく行われているかを確認してください。


*************************************************************************************************************************************************************************
*************************************************************************************************************************************************************************

# Gitをインストール
			cmd sudo apt update
			cmd sudo apt install git

# Gitリポジトリの作成: Gitを使用してプロジェクトのバージョン管理を行うには、
# Gitリポジトリを作成する必要があります。リポジトリを作成するディレクトリに移動し、以下のコマンドを使用します。
cmd git init

# ファイルの追加とコミット: ファイルをGitのバージョン管理下に置くには、
# ファイルをリポジトリに追加し、コミットする必要があります。以下のコマンドを使用します。
cmd git add ファイル名
cmd git commit -m "コミットメッセージ"

# リモートリポジトリとの連携: リモートリポジトリ（GitHubやGitLabなど）との連携を行う場合は、
# リモートリポジトリを追加し、プッシュする必要があります。以下のコマンドを使用します。
cmd git remote add origin リモートリポジトリのURL
cmd git push -u origin ブランチ名

# リモートリポジトリのURLを取得

cmd git remote -v
ans origin	https://github.com/GhGh0621OO/C- (fetch)　　取りだし許可・可能の意味
ans origin	https://github.com/GhGh0621OO/C- (push)　　書き込み可能意味

# 追加
cmd git remote add origin https://github.com/GhGh0621OO/C-

# 現在のリモートを表示
cmd git config --get remote.origin.url
ans https://github.com/GhGh0621OO/C-　　（　user='GhGh0621OO’　/　リポジトリ=’C-’　）

# 現在のブランチ取得
git branch
ans{
* _b00
  _b01
  master
}

# ブランチ名は新しく作成 多くのユーザに権限を与えて（読み・修正・削除）
			# git branch ブランチ名
			# ブランチ名は新しく作成するブランチの名前です。
			# 例えば、feature/my-featureという名前のブランチを作成する場合、以下のようにコマンドを実行します。

git branch C-/my-feature
git branch
ans{
  C-/my-feature     # 追加
* _b00
  _b01
  master
}

git branch C-/my-feature

# _b00 ブランチにデスクトップにある TEST.txt ファイルをリモートリポジトリに新規追加するためには、
			以下のコマンドを実行します。
			ファイルをステージングエリアに追加します:

			git add ~/Desktop/TEST.txt（文法）
			
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
		（実際発行）
git add /home/nikkirauda/デスクトップ/TEST.txt

実行結果｛

｝					nikkirauda@nikkirauda-iMac:~$ git commit -m "Add TEST.txt file"
					ブランチ _b00
					追跡されていないファイル:
						(use "git add <file>..." to include in what will be committed)
						#tree.txt#
						.bash_history
						.bash_logout
						.bashrc
						.cache/
						.config/
						.dotnet/
						.emacs.d/
						.gitconfig
						.gitkraken/
						.gnupg/
						.guix-profile
						.lesshst
						.local/
						.pki/
						.profile
						.ssh/
						.sudo_as_admin_successful
						.swp
						.tree.txt.swp
						.ttt.cpp.swp
						.vscode/
						.xinputrc
						FirstStepUbuntu.odt
						snap/
						tree.txt
						work/
						"\343\203\200\343\202\246\343\203\263\343\203\255\343\203\274\343\203\211/"
						"\343\203\207\343\202\271\343\202\257\343\203\210\343\203\203\343\203\227/#ForKubotaScriptListScript-FstCmd.sh#"
						"\343\203\207\343\202\271\343\202\257\343\203\210\343\203\203\343\203\227/ForKubotaScriptListScript.sh"
						"\343\203\207\343\202\271\343\202\257\343\203\210\343\203\203\343\203\227/GitHub-gitcomands-operations.txt"
						"\343\203\211\343\202\255\343\203\245\343\203\241\343\203\263\343\203\210/"
						"\343\203\224\343\202\257\343\203\201\343\203\243/"
						"\346\227\245\346\234\254\350\252\236\345\205\245\345\212\233UBNTU.odt"
						"\347\204\241\351\241\214 1.odt"

					nothing added to commit but untracked files present (use "git add" to track)

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

結果｛

このメッセージは、コミットする前に追跡されていない（git add されていない）ファイルが存在することを示しています。
コミットに含めたいファイルをトラッキングするには、git add コマンドを使用してファイルをステージングエリアに追加する必要があります。

例えば、tree.txt ファイルをコミットに含める場合は、以下のコマンドを使用します。

git add tree.txt

これにより、tree.txt ファイルがステージングエリアに追加され、

次に git commit を実行するとコミットが作成されます。

同様に、他のファイルも必要に応じて git add コマンドを使用してステージングエリアに追加してください。

}

# コミットを作成します:
git commit -m "Add TEST.txt file"

結果｛

			git commit コマンドの実行結果を見ると、以下のようなメッセージが表示されています。

			[_b00 23aaf86] Add TEST.txt file
			 1 file changed, 24243 insertions(+)
			 create mode 100644 tree.txt
			このメッセージは、_b00 ブランチに対して Add TEST.txt file というコミットが作成されたことを示しています。
			また、変更されたファイルは tree.txt であり、行数は 24243 行追加されたことが表示されています。ファイルのモードも 100644 となっています。

			これにより、TEST.txt ファイルがコミットされ、変更内容が記録されました。
｝

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★





*******************case1********************** *******************case1**********************
*******************case1********************** *******************case1**********************
*******************case1********************** *******************case1**********************
# いよいよ　「ローカルの _b00 ブランチをリモートの対応するブランチにプッシュ」
git push -u origin _b01

ans{
			SSHキー認証でやってほしいとERROR
}

				git push -u origin _b01
				ChatGPT
				git push -u origin _b01
				
				コマンドは、_b01 ブランチをリモートリポジトリの origin という
				名前のリモートにプッシュするためのコマンドです。

				このコマンドを実行すると、現在のローカルブランチ _b01 のコミットがリモートリポジトリの
				_b01 ブランチに送信されます。また、-u オプションを使用することで、リモートリポジトリの
				_b01 ブランチをトラッキングブランチとして設定します。これにより、
				今後の git push コマンドを単純に git push と実行するだけで、対応するリモートブランチにプッシュすることができます。

				なお、事前にリモートリポジトリ origin を設定しておく必要があります。
				リモートリポジトリの追加は git remote add コマンドを使用して行います。例えば、以下のように実行します。

				csharp
				Copy code
				git remote add origin <リモートリポジトリURL>
				上記のコマンドでリモートリポジトリを追加した後、
				git push -u origin _b01 コマンドを実行することで、
				_b01 ブランチをリモートリポジトリにプッシュできます。
				
				cmd git remote -v
						ans origin	https://github.com/GhGh0621OO/C- (fetch)　　取りだし許可・可能の意味
						ans origin	https://github.com/GhGh0621OO/C- (push)　　書き込み可能意味
						
						psw : 'gHgH0621'

				
				
				git remote remove origin
				git remote add origin https://github.com/GhGh0621OO/C-

*******************case1********************** *******************case1**********************
*******************case1********************** *******************case1**********************
*******************case1********************** *******************case1**********************

*******************case2*********************** ******************case2**********************
# いよいよ　「ローカルの _b00 ブランチをリモートの対応するブランチにプッシュ」
		gGitコマンドでユーザ名とパスワードを設定するには、以下の方法を試してみてください。
		ユーザ名とパスワードを含むリモートリポジトリのURLを使用する方法:git push -u origin _b01
		コマンドでユーザ名とパスワードをいれて、「ローカルの _b00 ブランチをリモートの
		対応するブランチにプッシュ」できるように設定したい

git remote set-url origin https://ユーザ名:パスワード@リモートリポジトリのURL
git remote set-url origin https://GhGh0621OO:gHgH0621@https://github.com/GhGh0621OO/C-


		この方法では、https://ユーザ名:パスワード@リモートリポジトリのURL の
		形式でリモートリポジトリのURLを指定し、認証情報を含めることでユーザ名とパスワードを設定します。

Gitの認証情報キャッシュを使用する方法:

git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'

			この方法では、Gitの認証情報キャッシュを有効にし、一定時間（ここでは3600秒）キャッシュされた
			認証情報を使って自動的に認証するように設定します。

			どちらの方法でも、一度設定すれば以降のプッシュ操作でユーザ名とパスワードを入力する必要はありません。
			ただし、セキュリティ上の理由からパスワードをコマンドラインに直接記述することは推奨されません。
			代わりに、SSHキーを使用して認証するなど、よりセキュアな方法を検討することをおすすめします。
			
＃			現在の「リモートリポジトリのホスト名」を表示したい

			ChatGPT
			現在のリモートリポジトリのホスト名を表示するには、git remote -v コマンドを使用します。以下のコマンドをターミナルで実行してください：

			git remote -v
			このコマンドは、現在のリモートリポジトリの名前とURLを表示します。URLの中にホスト名が含まれています。

*******************case2********************** *******************case2**********************


git ls-remote --refs --quiet --exit-code https://github.com/GhGh0621OO/C-/
ASK　Username for 'https://github.com': GhGh0621OO
			Password for 'https://GhGh0621OO@github.com': 
			remote: Support for password authentication was removed on August 13, 2021.
			remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories
			#cloning-with-https-urls for information on currently recommended modes of authentication.
			fatal: Authentication failed for 'https://github.com/GhGh0621OO/C-/'


git ls-remote --refs --quiet --exit-code origin


git ls-remote --refs --quiet --exit-code origin/master
git ls-remote --refs --quiet --exit-code C-/_b01


mkdir ~/Desktop/test



