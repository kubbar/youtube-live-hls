# youtube-live-hls　(m3u8 Get for IPTV)

### 障害情報：現在メンテナンス実施中です
### Last Check Date -> (2025-04-09 JST 10:00)
ここに障害内容を表示します、このgitをブックマークして下さい。<br/>
@でのchannel指定について表記を修正(予告通り、廃止になりました。@での指定は出来ません)<br/>
nicknameへ変更してください。<br/>
一部ユーザーの迷惑行為が確認された為、バージョンを変更しました。<br/>
v2 → v3　アドレスが変更になっています。ご注意下さい。<br/>

[Hey, "78.177.165.242"!! You Access is It's annoying!](https://yt-hls-get-v3.x0.to/youtube/err-logs/78-177-165-242.txt)<br/>
channel ID = 24 characters, you input 23 characters,,error!!!!<br/>
why? ".m3u8"??<br/>
It will be automatically disconnected, but please don't put in anything unnecessary.<br/>
・videoID  check grep -> ([a-z_A-Z0-9\-]{11}) 11文字以外は内部的に捨ててるので、動いてる様に見せてるだけ。<br/>
・過去に類似機能を持ったサイトの名残の様だが当方とは無関係です。リスト修正はしっかり行うようにして下さい。<br/>

改善されない様ならアナタをブロック致します。<br/>


#### This PHP program is being test-operated by "[@K_A_R_E_N](https://www.youtube.com/@K_A_R_E_N)" for the purpose of sale. Please try it out to see how it works.
<br/>

## 必ず最後までお読み下さい。
> [!WARNING]
> Please be sure to read to the end.<br/>
> If you are not fluent in Japanese,<br/>
>  please use the translation function of your browser.<br/>

<br/>

## ライブ放送 配信者が観れる地域を設定しています。
> [!TIP]
> Server設置場所 (JP IP)　日本<br/>
<br/>

### ライブ配信者のページにあるVideoページのソース内を必ず調べて下さい。
あなたに見えている放送が、JPを許可していなければ表示されません。<br/>
<br/>

###  ("regionsAllowed" JP) が無ければ、放送を探す権利すらありません。
> [!TIP]
>　"watch?v=" が含まれているvideoページの事です。<br/>
>　[チェックツール](https://www.lenostube.com/en/youtube-country-restriction-checker/)を使うと簡単かも知れません。 "Video is unrestricted" OK?<br/>
> ("JP" & Your Code) 無ければ 404 Error.<br/>

### 存在しないIDやチャンネルを指定しないで下さい。
> [!WARNING]
> 
> 永久にエラーでプログラムの負荷を高める迷惑行為です。
> 早急にリスト内から削除して下さい。<br/>
> リストに存在するだけで勝手に情報を集めるアプリがありますので<br/>
> 本当に削除して下さい。
> あなたではなく、私が不正リクエストを繰り返してしまうのです。
> IP規制が再び発生する可能性があります。<br/>
<br/>

## お使いのアプリの設定を必ず確認して下さい。
> [!CAUTION]
> 統計情報/サムネイル/存在確認　等のオプションは全て解除して下さい。<br/>
> 初期設定でサーバーに迷惑なオプションがデフォルトでONされている事があります。
> 秒間数十件のリクエスト・・迷惑です。
<br/>

### ユーチューブのライブ配信からm3u8をあなたに代わって探してきます。
発見出来た場合は302ステータスコードでリダイレクトを掛けます。<br/>
発見出来ない場合は404応答します。<br/>


### DoS Attack Protected.
送信されてきたデータを厳しくチェックしています。<br/>
余計な追加オプション等はエラーになります。<br/>
<br/>

## 最終チェックパス→TEST デプロイ　※既にアクセスが可能です<br/>
> [!WARNING]
> 勘違いしないで下さい。<br/>
> 個人による"自作PHPプログラムの公開テスト"です。<br/>
> これは"公共の無料サービス"ではありません。<br/>

<br/>

## ユーザーデータの収集/公開への同意
IP,country,User-Agent,AccessTime,videoID<br/>


## 利用条件・注意事項
> [!CAUTION]
> 私の[Youtube Channel](https://youtube.com/@K_A_R_E_N??sub_confirmation=1) 任意登録する事。<br/>
> 記載されたリストを公開する場合は、このgitへのリンクをどこかに入れる事<br/>
> 個人の研究的 実験プログラムにつき、商用アプリ等への組み込み禁止<br/>
> Youtube仕様変更への対応が困難な場合は提供終了する場合があります。<br/>
> 個人プログラムの為、メンテナンス時等 アナウンス用の宣伝動画に差し替える事があります。<br/>

<br/>

# --------------------------------------------------------

## 指定できる Command について。
#### ?video=xxxxxxxxxxx　(11 characters long) over cut 11.
> [!NOTE]
> 　Youtube video ID offer.<br/>
> 　11文字のvideoID のみを指定<br/>
> 　videoIDは配信側の RE:Try により変わる事があります。
> 　既に使われていないIDを指定し続ける事は禁止です。
<br/>

#### ?channel=UCxxxxxxxxxxx　start (UC)　(24 characters long) over cut 24.
> [!NOTE]
> 　Youtube Channel ID offer.<br/>
> 　24文字の"UC"から始まる24文字のみを指定<br/>
<br/>

#### ?nickname=@xxxxxxxxxxx　start (@)　(MAX 24 characters long) over cut 24.
> [!NOTE]
> 　Youtube Nick name offer.<br/>
> 　最大24文字以下の"@"から始まる文字を指定<br/>
> 　配信側で自由に設定変更が可能な為、非推奨での指定方法です。<br/>
> 　エラー頻発の頻度が高いため、この指定は使わないで下さい。<br/>
<br/>

# --------------------------------------------------------

以上の事を踏まえて　新サイトはコレだ！！！！　　↓<br/>
# ///////////////////////////////////////////////
~~~
Channel ID offer.
Weathernews Japan.
https://yt-hls-get-v3.x0.to/youtube/?channel=UCNsidkYpIAQ4QaufptQBPHQ
https://www.youtube.com/channel/UCNsidkYpIAQ4QaufptQBPHQ


Video ID offer.
J-POP avex 24/7 Music Live
https://yt-hls-get-v3.x0.to/youtube/?video=tr77RbnfYIU
https://www.youtube.com/watch?v=tr77RbnfYIU


~~~
# ●●●● WARNING ●●●●
~~~
 実際にyoutubeでライブを行っているのに認識されない場合は
　・ video と channel コマンド指定が間違っていませんか？ 
　・ プログラムがyoutubeにIP規制されている
　・ WebブラウザでURLを開いてみて下さい。m3u8ダウンロードされますか？
　　 ダウンロードされたm3u8をVLCで再生できますか？　出来ない場合もリージョンカントリーエラーです。
　・ 404エラーの場合 JP x　リージョンカントリーエラー
　・ 403エラーの場合 ごめんなさい、あなたのアクセスを禁止させて頂きました。
　　 リストを削除した上で、二度と私に関わりを持とうとしないで下さい。 good bye, for ever.
　・ youtubeの仕様変更  3～4日頻度で　新プレイヤーで規制掛けてきてます。正直、しんどい、、、
　   この場合も、404エラーになります。復旧までアクセスしないで下さい。
　   このgit上で恐らく　障害発生をアナウンスしています。
　・ キャッシュを搭載しています。再度取得するのは1～2時間後です。
　・ WAF system on.　(一部アプリや、国際アクセス等を自動的に遮断する可能性があります)
~~~
# ●●●● WARNING ●●●●

# ENJOY!!
このPHPプログラムの販売が可能です。<br/>
１ライセンス 日本円で「20,000円」<br/>
アパッチ等サーバーとPHP8.3プログラムのインストール、cURL&SSL証明書の設定、cookieのブラウザからの抜き出し、編集等<br/>
取り扱いが可能で、日本語でコミュニケーション出来る方に限ります。<br/>
