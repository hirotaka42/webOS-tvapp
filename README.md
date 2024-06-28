

# 開発の進め方

以下のDeveloperページに従い、進める
https://webostv.developer.lge.com/develop/tools/webos-studio-dev-guide


# LG TV webOSシミュレーターの選択

## 概要
LG製TVをお使いの場合、webOSのバージョンに合わせて適切なシミュレーターを選択する必要がある。

## 前提条件
- お使いのLG TVのwebOSバージョンは8.3.0である。
- SDK 9.0.0を使用してアプリ開発を行う。
- SDK 9.0.0には、webOS 22 (1.4.1)、webOS 23 (1.4.1)、webOS 24 (1.4.1)の3つのシミュレーターが用意されている。

## 適切なシミュレーターの選択
お使いのwebOS 8.3.0のTVに最適なシミュレーターは以下の通りである。

- webOS 22 (1.4.1) - webOS 8.0 ~ 8.2に対応
- webOS 23 (1.4.1) - webOS 8.3に対応
- webOS 24 (1.4.1) - webOS 9.0以降に対応

したがって、webOS 8.3.0のTVでアプリを確認する場合は、**webOS 23 (1.4.1)のシミュレーターを使用することが適切**である。

webOS 22や24のシミュレーターでは、お使いのTVの動作と異なる可能性があるため、避けるべきである。

## 結論
LG TVのwebOS 8.3.0をお使いの場合、SDK 9.0.0のwebOS 23 (1.4.1)シミュレーターを使用して開発・動作確認を行うことが推奨される。
