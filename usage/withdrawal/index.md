---
layout: default
title: 出金するには
permalink: /usage/withdrawal/
---

## 出金するには

公式サイトに登録します。
<https://tipwaves.pinfort.me>

登録画面はこちらです。
<https://tipwaves.pinfort.me/auth/register>

登録を行うと、メールが送られてきます。ドメイン指定受信等を行っている場合、
mail.tipwaves.pinfort.me からの受信が可能な状態にしてください。

仮登録メールに記載されているリンクにアクセスすると、本登録が行われます。
メールがとどかない場合は、迷惑メールに入っていないかなど確認してみてください。

本登録が正常に完了すると、再びメールが送られてきます。これを確認したら、ログインを行います。

ログイン画面は以下です。
<https://tipwaves.pinfort.me/auth/login>

2facodeはまだ設定していないので無視で結構です。

ユーザーホームに入ったら、「接続」タブのtwitterをクリックします。
認証画面が出てくるので、内容を確認し認証します。

ホームに戻ると、「Linked」タブに twitter: xxxxxx のようなリンクが追加されています。
これをクリックすると、アカウントの画面に遷移します。

whoops, something went wrongのような画面が出た場合は、再読込を試してください。

ここでは様々な情報が確認できます。

今回は出金を行いますので出金したいトークンの残高を確認します。

Tipwavesからの出金には、一律で 0.01WAVES の手数料がかかります。
このため、出金するもの + 0.01WAVESの残高が必要となり、
これが足りない場合は残高不足エラーとなりますので注意してください。

また、出金時、DMを受け取れるようになっている必要があります。
balance all コマンドを使用するなどして、DMが受け取れることを確認してから行ってください。

残高が確認できたら、アカウントの画面に戻って下にスクロールします。すると、出金フォームが現れます。
ここで、出金先のアドレス、出金したいアセット（トークン）のid、出金する量を指定します。
ただし、WAVESを送金する場合は、asset idに WAVES を指定してください。

出金ボタンを押すと、Tipwaves からDMが送られてきます。
DMの内容は以下のようなものです。

出金リクエストが有りました。承認するにはwithdrawal idとピンコードを入力してください。
withdrawal id: xxxxx-xxx-xx-xxxxx-xxxxxxxxxxxx
出金先: 3PHAW99B2HhzBkEKLhgp91XJwG6t6yAwg8N
アセットid: 4iVL5L1xviyDsy79STs6euVAX6sK9j5BNgeyb2aEgQK7
出金量: 100.0
pincode: 1111

このDMを受け取ったら、先程のアカウント画面の下部にある「出金承認画面へ」ボタンを押します。
すると以下のような画面になります。

![出金承認画面](/assets/images/withdrawal-confirm.png)

ここに、先ほど受け取ったDMに記載されているwithdrawal idとpincodeを入力します。2fa codeを設定している場合は2fa codeも入力します。

正常に完了すれば、画面が変わった後上部にtransaction idが表示されます。
更に、DMに「出金を実行しました。」と送信されてきます。これで出金は完了です。
