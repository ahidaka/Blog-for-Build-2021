# Blog-for-Build-2021

Blog entry for Microsoft Build 2021

今年もMicrosoft Build が開催された。

https://mybuild.microsoft.com/home

Buildは第1回開催以来、毎年5月に開催されるMicrosoftの開発者向けの最大イベントである。
http://www.devdrv.co.jp/hidaka/node/36

新型コロナウイルスの影響で今年3月の Ignite 2021 と同様、全て無料でオンラインで48時間通しでの配信となった。
https://myignite.microsoft.com/home

同一内容を含めて300以上のセッション全てがアーカイブされ、興味あるセッションは後から視聴できるようになっている。

##  Future of Technology with Kevin Scott

ここでは今回のアーカイブの中でお勧めしたいセッション「Future of Technology with Kevin Scott」を取り上げて、ネタバレを交えて少しだけ解説したい。
このセッションはAUDIO TRACKSでJapaneseを選択する事により、優れた専門知識を持つ通訳者による流暢で正確、分かり易い日本語同時通訳を聞くことが出来る。

https://mybuild.microsoft.com/sessions/772a5286-d290-46ca-a27b-b2bd77beedb5?

まず Kevin Scott 氏は、チーフテクノロジオフィサー (CTO) 兼 Technology & Research エグゼクティブバイスプレジデント である。
https://news.microsoft.com/ja-jp/exec/kevin-scott/

かつて Goodleに在籍したこともある彼は副社長としてLinkedInを救い、Microsoft のLinkedIn買収に伴って Satya Nadella によってMicrosoft のCTOに任命された。

https://en.wikipedia.org/wiki/Kevin_Scott_(computer_scientist)

---

今回のBuildで意外なことは、IoTとWindowsに関するセッションが、例年と比べてかなり少ない点である。
特にIoTは、Azure Sphere と Mixed Reality 関連を除けば、このセッションしか無いと言える。

巷ではIoT幻滅期に突入したという意見もあるが、このセッションでKevin Scott は普及期に入ったIoTを語っている。
実際のところIoTとEdge, AI等の取り巻く技術が世の中に浸透し始めて、芸術活動から、バイオテクノロジーや環境保全の様な人類の課題を解決する手段として普及し始めている。
以前の様にどの様なIoTがあるかとか、IoTをどうやって実現するかとかの実験段階ではなく、特にIoTと呼ばずに利用するツールになって来ていると感じた。

## ジェイコブ・コリアー

2017年に第59回グラミー賞を受賞したYouTuber のジェイコブコリアー Jacob Collier のリアルな世界ツアーをMIT Ph.D でクリエイティブ・テクノロジストのベンブルームバーグ Ben Bloomberg がサポートしたストーリーが興味深い。

例えば17種類の楽器を演奏するYouTube動画を観客を待たせること無くライブで実現するために、ハーモナイザーとルーピングシステムを組み合わせた自家製アナログシステムとWindowsを組み合わせ、複雑なハーモニーを素早く重ね、彼の初めてのワールドツアーを成功させた。

新しい技術を組み合わせて、芸術家のアイデアを実現させた例である。
演奏家が楽器だけではなく、メディアを使って自分自身を表現する様になるというのは、Ben の指導教授が提唱していることだ。

この件は、下記 Behind the Tech シリーズ Podcast で、Kevin Scott氏がかなり詳しくまとめている。
技術者にはソフトウェア開発やハードウェア・ガジェットだけでは無く、歌唱やペンタトニック・スケールの様な楽器演奏の知識も求められるのかと、興味深いエピソードである。

エピソード29: ジェイコブコリアー＆ベンブルームバーグ：グラミー賞を受賞したデュオ
https://www.youtube.com/watch?v=WENbI0tKIyc

エピソード30: ジェイコブコリアー＆ベンブルームバーグ：ボーナスエピソード
https://www.youtube.com/watch?v=AZHHFAQgI8w

Jacob Collier
https://www.youtube.com/channel/UCtmY49Zn4l0RMJnTWfV7Wsg

https://www.jacobcollier.com/

## Adafruit

Adafruit は組み込みエンジニアなら誰でも知っているアメリカの著名なコンピューターガジェットメーカーである。
ビデオに登場するMITの女性技術者、Limor Friedが2005年に設立して、世界中で製品が利用されている。
このセッションでは Adafruit Raspberry pi Lobe kit を使用して、AIアプリを作成、画像認識学習、パン屋の商品画像認識レジスターを実演するデモが紹介された。
https://www.adafruit.com/product/4963

Microsoft Lobe はどこでも機械学習モデルを容易に作成して学習させる無料のツールだ。
先日開催のIoT ALGYANの6周年記念イベントでソラコム松下さんのセッションでも紹介され、やはり短時間で学習と認識が出来るデモを行っていた。

https://blogs.microsoft.com/ai/lobe-machine-learning/

https://www.lobe.ai/

https://www.youtube.com/watch?v=NblymNBgUCs&t=3h19m28s

ALGYAN6周年IoT祭2021
https://algyan.connpass.com/event/212471/

余談だが確認のため調べたところ、Adafruit命名の語源となった初めてのプログラマーAda Lovelace がプログラムを書いた150年前、計算機が音楽の様な芸術作品を創造する可能性があることを指摘していたと言われるのが面白い。

世界初のソフトウェア・プログラマー、エイダ・ラブレスの偉業
https://forbesjapan.com/articles/detail/12649

## OpenAI GPT-3

Microsoft が出資しているOpenAI 社は最近、AI利用の言語処理APIのサービス OpenAI GPT-3 をリリースした。
インターネット上にあるあらゆる言語データから学習するとされる自然言語処理モデルは、ベータ版ながら高性能なため登録者だけが限定的に利用できる。

GPT-3 Powers the Next Generation of Apps（登録受付待ち状態）
https://openai.com/blog/gpt-3-apps/

セッションでは次のプロジェクトが紹介された。

CLIP (Contrastive Language–Image Pre-training) 
自然言語に基づいた画像データを学習
https://openai.com/blog/clip/

自然言語を元に画像生成
https://openai.com/blog/dall-e/

例えば、「赤いコートを来た赤ちゃんペンギンがピアノを弾いている」
といった、分かり易い言葉で説明するとその画像が生成される。
クリエイターや開発者が抱えている画像調達の問題解決に役立てることを目指している。

## David Baker 博士

従来の実験という大変な作業をデジタルラボとネットラボで効率的に分散出来、生物学そのものを計算対象とする非常に強力なバイオラボを実現可能にする事例の紹介。
Washinton大学の生化学教授 (Ph.D)で、プロテインデザイン研究所所長のDavid Baker 博士は、分子構造と機能をデザインすることを重点課題としている。

David Baker, PhD

https://www.ipd.uw.edu/people/ipd-faculty-staff/david-baker/

研究チームは、タンパク質のDNA三次元構造、相互作用を知ることでソフトウェアを使用して、コロナウィルスの侵入を阻止するタンパク質を設計し、臨床試験が進行中である。

## Kevin Scott セッションまとめ


## Build 2021のまとめ

Satya Nadella 氏が、次の Windowsは過去10年間で最も重要なアップデートとキーノートで言いながら、Windows周りの情報が少なかったのは、
BUild 2021終了後に明らかにされた「次のWindows」の

は、全般と


Join us to see what's next for Windows
https://www.microsoft.com/en-us/windows/event

