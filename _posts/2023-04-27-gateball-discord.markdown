---
title: "ADS 1103 Discord サーバー"
---

- TOC
{:toc}

[ADS 1103 Gateball Server](https://ksmzyp.github.io/2023/04/16/gateball-server.html) の Discord サーバーです。  
ランダムマッチ通知や、プレイヤーランキングに参加できます。

## サーバー招待リンク

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">荒らし対策のため、今後はサーバ利用にユーザ登録が必要になります。<br><br>【ユーザ登録申請手順】<br>招待リンクからDiscordサーバに参加した後、当アカウントに以下の項目を記載してDMを送ってください。<br><br>・Discordサーバのユーザ名<a href="https://t.co/tZZWyV3Op1">https://t.co/tZZWyV3Op1</a></p>&mdash; ADS 1103 Gateball Server (@YGOPro1103) <a href="https://twitter.com/YGOPro1103/status/1704000375488147660?ref_src=twsrc%5Etfw">September 19, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## ランダムマッチ通知

ランダムマッチングに参加すると、`#room-notice` で通知されます。  
プッシュ通知など設定しておけば、対戦相手が現れたのを見逃しません。

## プレイヤーランキング

ランダムマッチの勝敗からレートを算出するプレイヤーランキングです。  
毎朝 5 時に集計され `#leaderboard` に掲載されます。

### 個人成績

![](/assets/2023-04-27-02.png)

個人成績は `/getscore` コマンドで確認できます。 

### レーティング計算式

勝ちを `W` 負けを `L` として `1000 + (W × 2 - L × 2)` で算出します。