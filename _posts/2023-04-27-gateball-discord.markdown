---
title: "ADS 1103 Discord サーバー"
---

- TOC
{:toc}

[ADS 1103 Gateball Server](https://ksmzyp.github.io/2023/04/16/gateball-server.html) の Discord サーバーです。  
ランダムマッチ通知や、プレイヤーランキングに参加できます。

## サーバー招待リンク

<blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">当鯖のDiscordサーバーです<a href="https://t.co/tZZWyV3Op1">https://t.co/tZZWyV3Op1</a></p>&mdash; ADS 1103 Gateball Server (@YGOPro1103) <a href="https://twitter.com/YGOPro1103/status/1651443558828871682?ref_src=twsrc%5Etfw">April 27, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## ランダムマッチ通知

ランダムマッチングに参加すると、`#room-notice` で通知されます。  
プッシュ通知など設定しておけば、対戦相手が現れたのを見逃しません。

## プレイヤーランキング

ランダムマッチの勝敗からレートを算出するプレイヤーランキングです。  
毎朝 5 時に集計され `#rankings` に掲載されます。

### ランキング参加方法

![](/assets/2023-04-27-01.png)

プレイヤー名を `プレイヤー名$ユーザID` の形式にして参加できます。  
`ユーザID` は公開されません。  
なりすまし防止のため `ユーザID` は推測されにくいものにしてください。

### 個人成績

![](/assets/2023-04-27-02.png)

個人成績は `/getscore` コマンドで確認できます。 

### レーティング計算式

勝ちを `W` 負けを `L` として `1000 + (W × 2 - L × 2)` で算出します。