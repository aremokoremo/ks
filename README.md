ksコマンド (lsコマンドじゃないよ)
=================================

## 何？:
とってもよく使うlsコマンド、lと間違えてkを打っちゃってksとか入力すると

    $ ks
    -bash: ks: command not found

って怒られるとおもいますが、かわいくないので、

    ＿人人人人人人＿
    ＞　カス乙！　＜
    ￣^Y^Y^Y^Y^Y^Y￣

と罵ってもらえるようにします

ksってカスの略ぽいですし

## セットアップ:
gccでビルドして、生成物を/usr/bin/にコピー

    $ gcc ks.c -o ks
    $ sudo cp ks /usr/bin/


## 使い方:
ls使うシーンで、間違えてksと入力してください

    $ ks
    ＿人人人人人人＿
    ＞　カス乙！　＜
    ￣^Y^Y^Y^Y^Y^Y￣


