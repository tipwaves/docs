---
layout: default
title: 投げ銭するには
permalink: /usage/tip/
---

## 投げ銭するには

アカウント [@tipwaves](https://twitter.com/tipwaves) に対してリプライを行うことで操作します。

### 基本構文
```
@tipwaves tip 相手先 数量 AssetId
```

##### 例(tipwaves 作者に 0.1 WAVES を投げ銭)
```
@tipwaves tip @pinf0rt 0.1 WAVES
```

ただし、ツイートに対して返信するときは相手先を省略することが出来ます。

##### 例(返信例)
```
@tipwaves tip 0.1 WAVES
```

### 注意
- Asset id は`balance all`コマンドで確認できます
- Asset id はトークンごとに一意です。ユーザーごとに変わることはありません
- 所持量は`balance all`コマンドで確認できます
- 巻き込みをしていると投げ銭が出来ません。返信先を投げ銭したい人だけにしてからツイートしてください。

### 主なエラー
- invailed command
  - コマンドの構文が間違っています。
- tip target uncertain
  - 投げ銭先が特定できません。巻き込みしていませんか？また、構文が間違っていても出ることがあります。
- invailed amount
  - 数量が数字でないようです。構文を確認してください。
- not have sufficient amount
  - 指定した数量の残高がありません。

### 主なAsset Id
- DADDY-COIN
  - `42ukm8YHC4dYJSVK8N4LLYwNewtwEZrD7NWFXCYaCAHT`
- INNU
  - `3qnD8PHsjvr2LY8Z4TmksktiDqz7Uie1cC3hBauJPgeP`
- NICHIRIN
  - `5ZUDtgrt2BYzS2VHX6etm4PZ18i5p1sxmezuVJQ6ExtA`
- TurtleCoin
  - `4iVL5L1xviyDsy79STs6euVAX6sK9j5BNgeyb2aEgQK7`
- MKOC
  - `FtpzUCQhLy3CcRtNHRskS3co8DHjASUvKf3vfB5SnF5W`
- otaku token
  - `FHsr53qmxF6SApnyn88ZtajxTyuSRJSvMisMRkCC94mD`
- TawaraCoin
  - `GCKQbzTdy3BuSWe93sjQybLCqFFMYAbc8qGFsJu96UUw`
- BLCoin
  - `CxDQjKkju7iwbkatdiiWmRUHJo8B2RLfR2TGMAuACsX5`
- Hokudai Coin HUC
  - `6ygNs4KxhXgLkR43tbRTPML4mX17Jqk8jvZ2wEv5RMM3`
- kawaz
  - `Cupkg8nPdoh2mkngHMc7eUuisM1SbN8r1EXoih2Qmekn`
- wano
  - `J6qjAqKDasWcLJy83Bpak2eki9ig9SwquKFe8wAKZ7Ec`
