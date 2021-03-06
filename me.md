---
layout: default
title: Me | Ogihara Ryo
permalink: /me
description: 自分語り
---

# Me

<!--
## イントロダクション

### 概要

この記事は壮大な自分語りだ。私のキャリア、思想、こだわり、ノウハウといった全てをこの記事に詰め込んだ。

### 執筆動機

自分の思想を体系的にまとめた1つのテキストを書き上げたかった。元々は有料 [note](https://note.com/) に書いて、自分に興味を持ってくれた方に読んでもらえれば良いかな、と思っていたのだが、note は体系的な長文を書き上げるにあたって Markdown に対応しておらず、見出しのレベルも1階層しかなかったため諦めた。

### 想定読者

私の働き方や思想に興味のある人向けに書いた。これからソフトウェアエンジニアを目指す方や、働き方を変えたい現役ソフトウェアエンジニアの方の1つのモデルケースとして参考になれば幸いだ。ただし、私は後述するように大成功を収めた人間ではないし、他人のモデルケースに再現性はないので、あくまで参考程度に捉えてほしい。

## 目次

-->

## 1. 行動指針

「こんな人間でありたい」「こういう人生でありたい」といった理想を達成するために、常日頃から意識している行動指針について記す。この記事で記す思想はこれらの行動指針を元に作られている。

### 1-1. 何を大切にするか

以下の優先順位で行動を決定する。

1. 最低限の健康と家庭
2. 業界の健全性
3. 自らの市場価値
4. 所属する組織

まず、自らの人生は命と家庭あってこそなので、最低限の健康と家庭を最も大切にする。何故「最低限」と付くのかは [健康](#健康) の章にて詳しく述べるが、健康を追求するには時間や知識を要するし、食や運動量等においてはこだわりすぎると日々の幸福度を下げる要因になり得るので「最低限」というわけだ。

次に業界の健全性を大切にする。労働力の安売りは、それが自らの評価や所属する組織や顧客の利益に貢献するとしても絶対にしない。労働力の安売りは、自分で自分の仕事の価値と自らの市場価値を下げ、同じ仕事をしている人々の市場価値まで下げてしまう。仕事の価値を下げて放流すると業界の健全性は損なわれることにより、将来的には自分が安い値段で働かされる羽目になるかもしれない。

そして、自らの市場価値を大切にする。その気になればいつでも会社を辞めることができ、個人で仕事を請けることができ、食べていけるような技術力と人脈を常に保ち続ける。上記では、所属する組織を最も下位に置いているが、勿論所属する組織を蔑ろにするというわけではなく、健康や家庭、業界の健全性、自らの市場価値等を差し置いてでも所属する組織に奉仕してはならない、ということだ。

### 1-2. プログラマーの三大美徳

Perl の生みの親である Larry Wall が著書 [Programming Perl](https://www.oreilly.co.jp/books/4873110963/) で提唱したプログラマーの三大美徳、怠惰(Laziness)・短気(Impatience)・傲慢(Hubris) というものがある。私もこれらをプログラマーの美徳だと捉え、ソフトウェアに対して同様の思想を持って業務を遂行している。本記事では心構えの話のみに留めるので、プログラミングにおいての思想の適用方法については、[小飼弾氏の記事](https://tech.nikkeibp.co.jp/it/article/Watcher/20061005/250057/?rt=nocnt)を読んでみてほしい。

この思想は、Larry Wall 本人も正反対と[述べている](https://www.oreilly.co.jp/BOOK/osp/OpenSource_Web_Version/chapter10/chapter10.html) 努力(Diligence)・忍耐(Patience)・謙虚(Humility) や、書籍 [Team Geek ―Googleのギークたちはいかにしてチームを作るのか](https://www.amazon.co.jp/Team-Geek-%E2%80%95Google%E3%81%AE%E3%82%AE%E3%83%BC%E3%82%AF%E3%81%9F%E3%81%A1%E3%81%AF%E3%81%84%E3%81%8B%E3%81%AB%E3%81%97%E3%81%A6%E3%83%81%E3%83%BC%E3%83%A0%E3%82%92%E4%BD%9C%E3%82%8B%E3%81%AE%E3%81%8B-Brian-Fitzpatrick/dp/4873116309) で述べられている HRT と呼ばれる 謙虚(Humility)・尊敬(Respect)・信頼(Trust) を否定するものではない。あくまで対人コミュニケーションにおいてはこれらを重視しながらも、プログラミングや対ソフトウェアへの心構えとしてプログラマーの三大美徳を強く意識するということだ。

#### 1-2-1. 怠惰(Laziness)

1つ目の美徳は「怠惰」だ。長い目で見た時の労力を減らすための努力は厭わない。人々の労力を減らすようなプログラムを書き、何度も質問に答える必要がないようにドキュメントを書く。

> The quality that makes you go to great effort to reduce overall energy expenditure. It makes you write labor-saving programs that other people will find useful, and document what you wrote so you don't have to answer so many questions about it. Hence, the first great virtue of a programmer.

もう少し独自に解釈を広げると、自分が怠惰な生活を送れるように業務を効率化するためには時間を投資する。代表的な例はテストの自動化だ。テストコードを書くのもテスティングフレームワークの DSL を習得するのにもコストがかかるので投資が必要だが、その後の手動テストやデグレチェック等といったコストを削減できるため多くの場合は長い目で見ると労力は減る。

#### 1-2-2. 短気(Impatience)

2つ目の美徳は「短気」だ。自らは怠惰であろうとするがコンピューターが怠惰であることは許さない。現在のニーズに対応するだけではなく、今後のニーズを想定したプログラムを書く。~~若干のこじつけを感じなくもない。~~

> The anger you feel when the computer is being lazy. This makes you write programs that don't just react to your needs, but actually anticipate them. Or at least that pretend to. Hence, the second great virtue of a programmer.

実践するには後述の [YAGNI(You ain't gonna need it)]() とのバランスが難しい。こちらももう少し独自に解釈を広げるとすれば、短気なプログラマーが書くプログラムはコンピューターの性能を無駄なく引き出し、短気なプログラマーによって行われるプログラミングはバックグラウンドで自動コーディング規約チェックや自動テストを走らせており、コンピューターの怠惰を許さない。

#### 1-2-3. 傲慢(Hubris)

3つ目の美徳は「傲慢」だ。神罰が下るほどのプライドを持ち、他の人々に悪く言われない高品質なコードを書き、保守する。

> Excessive pride, the sort of thing Zeus zaps you for. Also the quality that makes you write (and maintain) programs that other people won't want to say bad things about. Hence, the third great virtue of a programmer.

自尊心を高く保つためには、自信に裏付けされる確かな技術力を保ち続け、自分のせいでビジネスが停滞したり、関係者が困ったりすることがないように自己研鑽を続ける必要がある。謙虚であることも必要だが、傲慢に見えるほどの自信は時には顧客やチームのメンバーに安心感を与える。

### 1-3. スターを目指さない

私は富も地位も名誉も多くは求めない。「そこそこ」であることを自分に許している。GAFA は目指さないし、年収も1,000万そこそこをキープできれば充分だ。スターを目指すには莫大なコストがかかるし、運要素も強くなってくる。エンジニアになるにあたってメジャーリーガーや NBA 選手の練習量を引き合いにだして勉強を勧めている方もいるが、年俸十億以上のスポーツ選手を目指すためのマインドセットや練習量と、「そこそこ」で甘んじるソフトウェアエンジニアに求められるマインドセットや練習量は違う。全てを自己研鑽に捧げなくても良い。人生は遊んでこそである。家族とたくさんの時間を過ごして、次々に発売するゲームを余すことなく楽しみ、時にはプログラミングや仕事を楽しむような人生を理想としている。そもそも私は、目の弱さや集中力の無さから労働時間は1日4時間程度が限界で、プログラミングや仕事よりも遊ぶことを好み、できる限りリスクを取らないタイプなのでスターを目指す器ではないのだ。ただ、意識低い系エンジニアとして在宅でソフトウェアエンジニアリングを楽しみながら1日4時間労働で年収1,000万程度の生活をするのは、それほど難しくはない。

この記事では、そんな私がどのようにして労働時間を減らしているか、どのようにして仕事を獲得しているか、リモートワークを始めるに至ったか、リモートワークを継続して成功させるために何をしてきたか、意識が低いなりにどんな思想やこだわりを持って仕事に取り組んでいるか、といったことを書き記していく。ソフトウェアエンジニア志望の人と話をしていると、一攫千金を求めたり GAFA を目指したりする人よりも、在宅で仕事ができるようになりたい人や、フルフレックス勤務で働きたい人の方が多いような印象を受けている。そういった人たちの参考になれば幸いである。

<!--

## 2. キャリアパス

### 2-1. 新卒でソフトウェアエンジニアへ

#### 2-1-1. 適性と配属

#### 2-1-2. 取り組んだ技術

#### 2-1-3. ハードワーク

#### 2-1-4. MLM勧誘

### 2-2. 1年間の無職期間と起業失敗

#### 2-2-1. 自己啓発

#### 2-2-2. 不労所得を目指して


### 2-3. web系エンジニアへのキャリアチェンジ

#### 2-3-1. アルバイト期間

#### 2-3-2. 入社即炎上

#### 2-3-3. 急成長

#### 2-3-4. 社内政治

### 2-4. フリーランス

### 2-5. 会社員と個人事業主の両立

#### 2-5-1. 本業


#### 2-5-2. 副業


## 3. 労働環境

### 3-1. フルリモート

### 3-2. フルフレックス

### 3-3. 副業


## 4. 時間

### 4-1. 緊急度と重要度

### 4-2. 他人の時間を尊重する

### 4-3. 労働時間と生産性


## 5. リモートワーク

### 5-1. リモートワークとは

### 5-2. リモートワークに必要な個人適性

### 5-3. リモートワークに必要な環境


## 6. 生産性

### 6-1. 内的モチベーションに期待しない

### 6-2. 集中力

#### 6-2-1. ポモドーロ・テクニック

### 6-3. 自動化


## 7. 技術研鑽

### 7-1. 最新技術を追わない

### 7-2. 食える技術

### 7-3. 勉強のモチベーション


## 8. 対人コミュニケーション

## 9. 営業

### 9-1. SNS

#### 9-1-1. Facebook

#### 9-2-2. Twitter

### 9-2. 技術情報のアウトプット

### 9-3. イベント参加

## 10. 教育

### 10-1. プログラミング教育と能力の再現性

### 10-2. 個別教育と一斉教育

## 11. コミュニティ

### 11-1. コミュニティへの参加

### 11-2. コミュニティ運営


## 12. プログラミング

### 12-1. 可読性

### 12-2. YAGNI

### 12-3. プロトタイピング

### 12-4. 保守性

### 12-5. 例外

### 12-6. TDD

### 12-7. エディター

## 13. メンタル

### 13-1. どういう時にメンタルが崩壊するか

### 13-2. 自己防衛


## 14. 家庭

### 14-1. 結婚

### 14-2. 家


## 15. 健康

### 15-1. 幸福

### 15-2. 運動

### 15-3. 目


## 16. コンプレックス

### 16-1. 学歴

### 16-2. 英語

### 16-3. 目

### 16-4. 対人コミュニケーション


## 終わりに

-->

<style scoped>
  article {
    font-family: "游明朝", YuMincho, "Hiragino Mincho ProN W3", "ヒラギノ明朝 ProN W3", "Hiragino Mincho ProN", "HG明朝E", "ＭＳ Ｐ明朝", "ＭＳ 明朝", serif;
  }
</style>