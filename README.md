# FRESH! 品質宣言

FRESH! のサービス、プロダクトにおいて目指す品質をここに宣言します。

**守りは徹底するが果敢に攻める**

新しい技術的挑戦を続けることでサービス、プロダクトの品質が向上すると考えます。

## 放送品質

### 画質

- 最大2160p(4K)を可能とし、1080p(Full HD)での快適な視聴を保証します
- 常に業界最高水準の画質の追求し、動画技術への技術投資を積極的に行います

### 視聴

- クライアントでの視聴品質（ビットレート・停止時間・クラッシュ）をトラッキングし、視聴品質を継続して定量的に評価します
- 視聴におけるユーザーの生の声を重視し、番組内コメント・Twitterから視聴への不満コメント収集し、どのような事象が発生していたかを分析します

### 配信

- モバイル回線下における安定配信のために、低ビットレートでの高画質配信を実現します
- 配信トラブル起因での動画の破損を可能な限り自動修復し、視聴できない配信を出しません

### 遅延

- 低遅延モードにおいて3〜4秒
- 通常モードにおいて10秒

## プロダクトの品質

- [https://frehslive.tv](https://frehslive.tv)
- [https://broadcast.freshlive.tv](https://broadcast.freshlive.tv)
- [Android アプリ](https://play.google.com/store/apps/details?id=jp.co.cyberagent.valencia&hl=ja)
- [iOS アプリ](https://itunes.apple.com/jp/app/fresh/id1026540588)
- [FRESH! Cast](https://itunes.apple.com/jp/app/fresh-cast/id1312723241)

### SLA（Service Level Agreement）

- Web・API・CDNにおいて、ユーザーからのエンドツーエンドでのサービス稼働率を99.999%を保証します
- 視聴・配信という重要なドメインは、部分的な障害が発生したとしても守り抜かれる設計にします（Fault tolerant design）

### デザイン / パフォーマンス

動画視聴及び配信をコアにした体験を提供します（すべてのプロダクト）

- 動画を邪魔しないカラーリング
- 動画視聴、及び配信に関わるUIの使いやすさ
- 動画、配信開始にたどり着くまでの情報の得やすさ

動画・配信を視聴したい、というニーズにすぐ応えられるパフォーマンス、また安定して動画視聴や配信ができる環境の提供を目指します。

#### Web

様々な環境や閲覧デバイスでも快適に利用できるような品質を提供します。

- [https://frehslive.tv](https://frehslive.tv) : SpeedCurve にて SpeedIndex, Startrender などの指標を計測し改善に努めます
- アクセシビリティを高める取り組みを継続します（詳細は別に記載）

#### Android アプリ

- 連続性とマテリアルデザインの階層構造を保った統一された操作性を提供します
- Crash free 99.9% を目指します

参考 : [FRESH! AndroidアプリのUI/UX](https://developers.cyberagent.co.jp/blog/archives/7177/)

#### iOS アプリ

堅牢で拡張性の高いコード品質を保ち、効率的に改善施策を行います。

- Crash freeを最大にする努力を継続し、Crash free 99.9% を目指します

デバイスやユーザーの状況に最適化されたUI/UXを提供し、ストレス無い視聴体験を提供します。

- 映像品質や通信頻度の調整により通信量やバッテリー使用量を適正に保ちます

### アクセシビリティ

FRESH! では誰もが生放送サービスを楽しめる、配信できることを目指し、アクセシビリティの確保と向上に取り組んでいます。

#### 独自ガイドラインの制定

[FRESH! Accessibility Guidelines](https://openfresh.github.io/a11y-guidelines/) を制定し、アクセシビリティにおいてサービスに携わるメンバーが目指すべき品質を定義しています。

#### JIS X 8341-3:2016 への対応（Web）

アクセシビリティ確保・向上の一環として、FRESH! では JIS X 8341-3:2016、及び [Web Content Accessibility Guidelines2.0](https://www.w3.org/TR/WCAG20/)（[日本語](https://waic.jp/docs/WCAG20/Overview.html)） への対応に取り組んでいます。

##### 対象範囲

FRESH! [https://freshlive.tv/](https://freshlive.tv/) 以下全体。

※ただしユーザーから提供される放送、動画、画像、テキストなどは対象外とします。

##### 目標とする適合レベル及び対応度

**2018年9月までに JIS 8341-3:2016 の 適合レベルAに準拠**

本仕様書における「準拠」という対応度の表記は、[情報通信アクセス協議会ウェブアクセシビリティ基盤委員会「ウェブコンテンツのJIS X 8341-3:2016 対応度表記ガイドライン – 2016年3月版」](https://waic.jp/docs/jis2016/compliance-guidelines/201603/)で定められた表記によります。

----
2018年2月28日制定