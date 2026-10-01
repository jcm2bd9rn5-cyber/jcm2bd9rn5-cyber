<p align="center">
  <img src="https://raw.githubusercontent.com/jcm2bd9rn5-cyber/jcm2bd9rn5-cyber/main/assets/profile-hero.svg" width="100%" alt="Shogo Taguchi — Build. Ship. Improve." />
</p>

# Shogo Taguchi · 田口 将伍

**身近な課題を、使い続けたくなるプロダクトに。**

東京電機大学 システムデザイン工学部 情報システム工学科 / 2028年3月卒業予定。  
Flutter・SwiftUIでモバイルアプリを開発しています。筋トレ記録アプリ **Strive** を個人で企画・設計・実装し、App Storeで公開・改善を続けています。

<p>
  <a href="https://apps.apple.com/jp/app/strive/id6770878590"><img src="https://img.shields.io/badge/Strive-App_Store-0D96F6?style=flat-square&amp;logo=appstore&amp;logoColor=white" alt="Strive on the App Store" /></a>
  <a href="https://strive-lp-xi.vercel.app/"><img src="https://img.shields.io/badge/Strive-Website-18181B?style=flat-square&amp;logo=safari&amp;logoColor=white" alt="Strive公式サイト" /></a>
  <a href="mailto:jcm2bd9rn5@privaterelay.appleid.com"><img src="https://img.shields.io/badge/Contact-Email-52525B?style=flat-square&amp;logo=maildotru&amp;logoColor=white" alt="メールで連絡" /></a>
</p>

- **個人開発：** 課題発見からUI設計、認証・データ保存・課金の実装、ストア公開、運用まで担当。
- **チーム開発：** ハッカソンでFlutter Webのフロントエンドと発表を担当し、サポーターズ賞を受賞。
- **関心：** 自社プロダクト開発。使う人の反応を見ながら、体験と実装の両方を改善すること。

---

## Featured project — Strive

### 前回重量を、忘れない。

筋トレ中に「前回は何kgで、何回できたか」をすぐ確認できる記録・分析アプリ。  
自分自身のトレーニングで感じた不便を出発点に、**記録 → 成長の可視化 → 次の挑戦**がつながる体験を作っています。

友人とのランキングでは、**「負けたくない」という気持ちも継続の力に変える**ことを目指しています。

<p>
  <strong>App Store公開済み</strong> · 個人開発 · 企画 / 設計 / 実装 / リリース / 継続改善
</p>

<table>
  <tr>
    <th width="33%">HOME</th>
    <th width="33%">WORKOUT</th>
    <th width="33%">ANALYTICS</th>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/jcm2bd9rn5-cyber/strive-lp/1d5c884539d8f66b384c269ef1250a508b5ffc17/assets/screens/home.webp" width="175" alt="Striveのホーム画面" /></td>
    <td align="center"><img src="https://raw.githubusercontent.com/jcm2bd9rn5-cyber/strive-lp/1d5c884539d8f66b384c269ef1250a508b5ffc17/assets/screens/workout.webp" width="175" alt="Striveのセット記録画面" /></td>
    <td align="center"><img src="https://raw.githubusercontent.com/jcm2bd9rn5-cyber/strive-lp/1d5c884539d8f66b384c269ef1250a508b5ffc17/assets/screens/analytics.webp" width="175" alt="Striveのトレーニング分析画面" /></td>
  </tr>
</table>

**主な機能**

- セットごとの重量・回数記録、前回記録との比較、PRの自動判定
- インターバルタイマー、トレーニング履歴、Growth Score・月間比較・BIG3分析
- フレンド機能・ランキング、RevenueCatによるサブスクリプション

**開発で考えたこと**

| 課題 | 設計・実装 |
| --- | --- |
| トレーニング中に記録や確認の手間がかかる | 前回記録を入力の近くに表示し、片手操作やタップ数を意識してUIを改善 |
| 登録前に使い心地を試したい | 匿名利用から始められ、必要に応じてApple / Googleアカウントを連携 |
| 記録を残すだけでは継続につながりにくい | 成長の分析と友人との競争を組み合わせ、次のトレーニングの動機を作る |

**Stack：** `Flutter` `Dart` `Firebase Authentication` `Cloud Firestore` `RevenueCat`

[App Storeで見る](https://apps.apple.com/jp/app/strive/id6770878590) · [公式サイト](https://strive-lp-xi.vercel.app/)

<sub>アプリ本体のソースコードは非公開です。公開サイトと実際のアプリから、機能・UIをご覧いただけます。</sub>

---

## Other projects

### Nolune — 撮る瞬間も楽しめるカメラ

Dynamic Island付近からカメラが展開し、撮った写真をチェキ風の演出でアルバムに残すiOSアプリの試作。

- **担当：** 個人開発 / UI設計・実装
- **実装：** カメラプレビュー・撮影、スワイプ操作、SwiftUIアニメーション、写真のローカル保存
- **Stack：** `Swift` `SwiftUI` `AVFoundation`
- **状況：** 試作済み・開発休止中

### GuruMeet — ハッカソンでのチーム開発

Flutter Webを使ったチーム開発。フロントエンドの実装と成果発表を担当しました。

- **チーム：** shogari
- **実績：** サポーターズ賞を受賞
- **Stack：** `Flutter Web` `Dart`

### Strive LP — 公開アプリを伝えるWebサイト

Striveの機能や開発背景を紹介し、App Storeへつなぐ公式ランディングページ。

**Stack：** `HTML` `CSS` `JavaScript` `Vercel`

[サイトを見る](https://strive-lp-xi.vercel.app/) · [ソースコード](https://github.com/jcm2bd9rn5-cyber/strive-lp)

<details>
  <summary>その他の開発 — Focas</summary>

### Focas — 集中時間の記録

ポモドーロタイマーと集中時間の記録を組み合わせた集中支援アプリ。カテゴリ管理、統計、ストリーク表示などを実装しています。

**Stack：** `React Native` `Expo` `TypeScript`

</details>

---

## Technologies

技術は、実際に使ったプロジェクトと合わせて紹介しています。

| 領域 | 技術 | 使用プロジェクト |
| --- | --- | --- |
| モバイル | Flutter / Dart | Strive |
| iOSネイティブ | Swift / SwiftUI / AVFoundation | Nolune |
| 認証・データ保存 | Firebase Authentication / Cloud Firestore | Strive |
| 課金・運用 | RevenueCat / App Store Connect | Strive |
| Web | Flutter Web / Dart | GuruMeet |
| Web | HTML / CSS / JavaScript / Vercel | Strive LP |
| モバイル | React Native / Expo / TypeScript | Focas |

## Now & next

- StriveのAndroid版公開に向けた準備と、使いやすさの改善
- バックエンド、API・DB設計、テストを学び、設計と実装の幅を広げること
- コードレビューや設計レビューのあるチームで、プロダクト開発を経験すること

## Contact

モバイル・Webサービスの開発や、エンジニアインターンの機会に関心があります。

[メールで連絡](mailto:jcm2bd9rn5@privaterelay.appleid.com) · [Strive公式サイト](https://strive-lp-xi.vercel.app/)
