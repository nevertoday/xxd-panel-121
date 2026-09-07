<div align="center">

# XXD Panel 121｜暮らしのドゥードル編集帖

日常の小さな感情を、豊かな余白と巧みな図と文字の関係を持つイラストに。

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## サンプル展示

以下のサンプルはそれぞれ異なる原画像を使い、Panel 121 が一枚ずつ独立した一回の生成で作成しました。AIメタデータは削除済みです。横長は左に実写、右にデザインを置く厳密な50:50、縦長は上に実写、下にデザインを置く厳密な50:50です。

**16:9 横長 · 左右 50:50**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 縦長 · 上下 50:50**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

サンプルには各原写真に即した、短く工夫された英語のコピーを使っています。

## 向いている場面と解決する課題

日常の写真には魅力的な姿勢や関係があっても、普通の構図や雑然とした背景に埋もれることがあります。**Panel 121** は写真の同一性を保ち、最も識別しやすい被写体を取り出し、力の抜けたマーカー風ドゥードル、編集された手書き文字、非常に大量の余白で成熟した作品にします。

### 向いている用途

- 人物、日用品、生活の場面を独立系雑誌やライフスタイルの editorial illustration にする。
- 輪郭、姿勢、物語的な関係を保ちながら、背景や副次的な物体の大半を削る。
- 素朴な手描きの気楽さと、図形・文字・空白の成熟した編排を両立する。
- 上下、左右、デザインのみ、複数比率、壁紙、フォルダー一括の統一した納品。

### 解決する課題

- 削減、再配置、トリミング、尺度変更で普通の写真に新しい焦点を作ります。
- 図と文字が見えないグリッド・視覚軸・読む経路を共有し、「上に一文、下に人物」を避けます。
- 小さな図形と大量の余白で距離、間、呼吸を作り、小さなアイコンで空間を埋めません。
- 比較図は厳密に二つの 50:50 領域とし、今回の原写真から直接生成して第三帯や二重変換を防ぎます。

## 原文プロンプト · 5言語

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中国語ファイルはユーザーの原文を逐字保存し、実行時の創作と美的判断における唯一の基準です。他の4言語は完全で忠実な閲覧用翻訳であり、生成指示を書き換えません。

**特徴：** 素朴な生活イラスト · マーカー／クレヨン／オイルパステルの質感 · 見えないグリッド · 図と文字の一体編排 · 軽やかな手書き · 原写真由来の限定色 · 非常に大量の余白

## クイック判定

| 気になること | Panel 121 の対応 |
|---|---|
| 普通の写真構図でも使える？ | 識別しやすい関係を保ち、位置、トリミング、尺度を演出し直します。 |
| 子どもっぽくならない？ | 素朴な絵と成熟した構図を合わせ、子どもの手帳、安い漫画、テンプレートを避けます。 |
| 文字はいつも中央？ | 輪郭、動作、肩の線、負の空間に合わせて非対称の呼応を作ります。 |
| 納品形式は柔軟？ | 4モード、一般的な比率、正確なピクセル、画像ごとの独立一括処理に対応します。 |

## 写真を作品に変える流れ

```text
被写体と物語を理解 → 背景の大半を除去 → マーカー風に簡略化 → 尺度と切り取りを再構成 → 見えないグリッドと読む経路 → 少量の手書き → 大量の余白でリズムを完成
```

## 完成品の識別ポイント

- 写真側は同一性、構造、姿勢、自然光、色の雰囲気を保ち、色調整はごく軽くします。
- 記号化した形に、揺れや途切れ、不完全な線を使い、はみ出し、白抜け、手仕事の誤差を認めます。
- 完全な遠近法や細密写実を求めず、背景と無関係な物体を積極的に削除します。
- 被写体は小さく、中心からずらす、端に寄せる、浮かせる、一部を切る配置で、余白が正負の形と距離を作ります。
- 図と文字は一体です。軽やかな自然な手書きは文字幅と筆圧が変化し、字間と行間は編集で管理します。
- 柔らかく明るい限定色は原写真由来で、温かい白かごく淡い混合色を広い呼吸空間にします。

## 4つの出力モード

- `top-bottom`：全幅の上下2領域のみ。実写を上、デザインを下に置き、各50%。
- `left-right`：全高の左右2領域のみ。実写を左、デザインを右に置き、各50%。上下構成へ回転しません。
- `design-only`：全画面を Panel 121 のデザイン翻訳にし、写真は見えない参照にします。
- `wallpaper-pack`：スマートフォン、iPad、デスクトップ、時計を端末ごとに生成。`linked` または `independent` を選べます。

モードと比率は複数指定できます。`1:1`、`3:4`、`4:3`、`4:5`、`5:4`、`2:3`、`3:2`、`9:16`、`16:9`、`21:9`、`5:7`、`7:5`、正確なピクセルに対応します。文字はプロンプト生成、指定文の逐字使用、なしから選べます。フォルダ入力では各画像を分離して処理し、PNGを一つの新しいタスクフォルダへ置きます。

## はじめに

```bash
git clone https://github.com/nevertoday/xxd-panel-121.git
npx skills add https://github.com/nevertoday/xxd-panel-121 --skill xxd-panel-121
```

インストール後に Agent セッションを再起動し、`$xxd-panel-121` を呼び出します。ユーザー単位の Codex には `--global --agent codex --yes` を追加できます。

```text
/xxd-panel-121 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ja-JP
/xxd-panel-121 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-121 photo.jpg --mode design-only --size 9:16 --text none
```

完全な実行契約は [SKILL.md](SKILL.md)、実行アダプターは[英語](references/xxd-panel-121-prompt.en.md)／[中国語](references/xxd-panel-121-prompt.zh-CN.md)を参照してください。

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

> **広告表示：** このセクションのQRコードおよび有料会員・サービスのリンクはXXDのプロモーション情報です。スキャンや購入は任意であり、オープンソースの利用には影響しません。

### Xiaoxiaodong 総控 · 将軍総指揮 Skill · CNY 100

CNY 100 の一回払いで、このシリーズの将軍総指揮 Skill（`xxd-panel-all`）を利用できます。全兵士 Skills の統括、推薦、指名派遣、一括調整に対応します。WeChat では「将軍総指揮 Skill」と記載してください。

<!-- xxd-panel-command-system:start -->
**購入後に利用可能：全隊を指揮する「将軍 Skill」**

| 階級 | Skill | 担当 |
|---|---|---|
| **将軍級** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付き Skills の検出、画像・テーマ・用途からの推薦、番号指定の派遣、同一素材の複数スタイル試作、フォルダー画像の一括割り当てと個別派遣。 |
| **兵士級** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学だけを実行し、将軍から渡された一つの仕事を完成させます。 |

将軍 Skill は、番号付き Skills 全隊の司令塔です。購入後すぐに利用でき、インストール、更新、編成、派遣方法についてサポートを受けられます。将軍は整理と派遣だけを担当し、兵士の原文美学を改変・混合・上書きしません。各完成作品は、選ばれた兵士 Skill が独立して制作します。
<!-- xxd-panel-command-system:end -->

### 知識星球＋会員プロンプトライブラリ＋全将軍 Skills 会員 · 年額 CNY 699

[知識星球](https://wx.zsxq.com/group/15554814142882)、[XXD 会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)、全将軍 Skills 会員は同じ会員権です。**一度の年額決済で3つの特典をすべて利用でき、二重の購入は不要です。**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

---

<div align="center">

## ☕ オープンソースを支援

このプロジェクトが役に立ったら、Buy Me a Coffee から任意で応援していただけます。

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
<!-- xxd-readme-ads:end -->

## ライセンス

本プロジェクト（Skill、プロンプト、スクリプト、文書、付属サンプル画像を含む）は **PolyForm Noncommercial License 1.0.0** の下で提供されます。完全な法的条文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

分かりやすく言うと：

- 個人は学習、研究、実験、テスト、趣味のプロジェクト、私的娯楽に使用できます。慈善団体、教育機関、公的研究・安全・保健機関、環境保護団体、政府機関も使用できます。
- **非商業目的**であれば、使用、複製、変更、派生物の作成、共有が可能です。共有時には本ライセンス（または上記リンク）と、作者が示したすべての `Required Notice:` 文を添付する必要があります。
- 商用製品・サービス、有料納品、アクセス権やライセンスの販売、商業利用につながることが予想される用途には使用できません。商用利用には著作権者から別途書面による許可を得てください。
- 本契約が付与するのは明記された著作権ライセンスと限定的な特許ライセンスだけです。商標、ブランド名、その他明記されていない権利は付与されず、ライセンスを第三者へ再許諾することもできません。
- 書面で違反通知を受けた場合、32 日以内に遵守状態へ戻り、実際の是正措置を取らなければライセンスは直ちに終了します。特許侵害を書面で主張した場合も特許ライセンスが終了します。
- 内容は法律が認める範囲で「現状のまま」提供され、保証はありません。利用に伴うリスクと損失は利用者が負います。
