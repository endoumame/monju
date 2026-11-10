# 理論的根拠

このスキルの進め方が、どの知見にもとづいているかをまとめます。認知科学、心理学、そしてAIと人の協働についての研究の順に並べています。

## 読み方

各項目に証拠の強さをつけています。

- **強**: 多くの追試や統合的な分析で支持されている
- **中**: 有力だが、条件によって結果が変わる、または議論が続いている
- **弱**: 研究が少ない、査読前、あるいはこのスキルへの当てはめが推測を含む

出典の確かめ方も2種類あります。末尾の文献一覧で「確認済み」としたものは、作成時に検索して書誌と要旨を確かめました。それ以外は古典的な文献を記憶から引いたもので、原典には当たっていません。発表や資料に使うときは原典を確かめてください。

もう一つ大事な点として、ここにある知見はどれも人間の学習や集団討議についてのもので、**言語モデルをメンバーにした合議で同じ効果が出るかを確かめた研究ではありません。** このスキル自体の効果は未検証です。

## 体験と規則の対応

出発点になった体験と、それを説明する知見、スキルの規則の対応です。

| 体験 | 説明する知見 | スキルの規則 |
|---|---|---|
| 人間の議論は結論を目的にしていなかった | 相互作用そのものが理解を深める（建設的相互作用、ICAP） | 進行役は結論に向かわない。決めずに終えてもよい |
| AIは毎回推奨案を出し、そのレールに乗ってしまう | アンカリング、認知的降伏、自動化バイアス | 案を選ばない。ユーザーが先に書く |
| 出力が多すぎて、理解せずに承認してしまう | 作業記憶の限界、認知負荷、流暢さによる錯覚 | 8行以内、問いは1つ、地図を外に置く |
| 経験の浅い人は grill-me の問いの意味がわからない | 熟達とチャンク、認識主導の意思決定、熟達化の反転効果 | 問いに理由と具体例をつける。「わからない」を受け取る |
| 問いへの問いを重ねると、何の話かわからなくなる | 作業記憶の限界、目標の見失い | 現在地を毎回書く。寄り道は本筋と別の場所で行う |
| それぞれが意見を言うことで深く考えられた | 議論としての推論、自己説明、生成効果 | 意見を並べ、ユーザーに反応してもらう |
| 「そもそも」で前提が見直された | 構えの固着、孵化、心的モデルの組み替え | 「そもそもの人」を必ず入れる。「そもそも」の手 |
| 「つまり◯◯だよね」で合意ができていった | 共通基盤の形成、対話における整合、解釈レベル | 「つまり」「たとえば」の手で具体と抽象を往復する |
| 知識がばらばらなメンバーが補い合った | 分散認知、対人交流記憶、隠れたプロフィール | メンバーを「見ている情報」で分ける。独立に集める |

## 認知科学

### ICAP: かかわり方で理解の深さが変わる（強〜中）

学び手のかかわり方を、受け身（読む、聞く）、能動（印をつける、写す）、構成（自分の言葉で説明や推論を作り出す）、相互作用（相手の発言を受けて構成し合う）の4段階に分けると、あとの段階ほど理解が深くなる、という枠組みです（Chi & Wylie, 2014）。

AIの長い出力を読んで承認するのは「受け身」です。チームでの議論は「相互作用」でした。このスキル全体は、ユーザーのかかわり方を受け身から構成と相互作用へ引き上げるように組んであります。毎回の発言を問いで終えるのも、ユーザーに書いてもらう場面が多いのもそのためです。

### 建設的相互作用: 相手がいると視点が動く（中）

三宅なほみは、二人で仕組みを理解しようとする過程を詳しく調べ、課題に取り組む役と、それを少し外から見る役が入れ替わることで、一人では起きにくい視点の移動が起き、理解が進むことを示しました（Miyake, 1986）。面白いのは、二人が同じ理解に着くとは限らず、それぞれが自分なりに理解を深めるという点です。

合意を目的にしなくても議論が役に立つことの説明になります。このスキルでは、ユーザーは自分の考えを説明する側と、メンバーの意見を外から見る側を行き来します。波多野誼余夫と稲垣佳世子の集団での理解活動の研究も同じ方向を示しています（Hatano & Inagaki, 1991）。

### 熟達とチャンク: なぜ熟練者は即答できるのか（強）

熟練者は、経験から作られた大きな意味のまとまり（チャンク）を大量に持っていて、状況をひと目で型として認識します（Chase & Simon, 1973）。現場の熟練者の意思決定を調べた研究でも、選択肢を比べるのではなく、状況を見て最初に浮かんだ手を頭の中で試す、というやり方が中心でした（Klein, 1998）。

grill-me の質問攻めに熟練者が即答できるのはこのためです。経験の浅い人はその型を持っていないので、抽象的な問いは手がかりのない問いになります。だからこのスキルでは、問いに必ず具体的な場面をつけます。熟練者向けの簡潔な支援が初心者には負担になり、逆に初心者向けの丁寧な支援が熟練者には邪魔になる、という熟達化の反転効果も同じことを示しています（Kalyuga et al., 2003）。

### 認知負荷と作業記憶（強）

頭の中で同時に保って操作できる情報は4つ前後です（Cowan, 2001）。課題そのものの難しさに加えて、提示のしかたが悪いことで生じる余計な負荷があると、理解に使える余力がなくなります（Sweller, 1988）。

長い出力、問いの重なり、寄り道は、どれも余計な負荷です。8行以内、問いは1つ、メンバーは3人まで、割れは3つまで、という上限はここから来ています。

### 分散認知と外に置いた表現（中）

認知は一人の頭の中だけでなく、人と人、人と道具にまたがって成り立つ、という考え方です（Hutchins, 1995）。紙に書いた図や表は、覚えておく負担を減らすだけでなく、見比べる、並べ替えるといった頭の中では難しい操作を可能にします（Kirsh, 2010）。

「地図」はそのための共有の外部表現です。論点を頭で覚えておく代わりに外に置き、ユーザーの余力を考えることに回します。

### 認知的な肩代わりと拡張した心（中）

人は道具に記憶や計算を預けます（Risko & Gilbert, 2016）。道具が思考過程の一部として働くこともあります（Clark & Chalmers, 1998）。これ自体は悪いことではありません。問題は、預けてよい作業（覚えておく、調べる）と、預けると意味がなくなる作業（判断する、理解する）の区別がつかなくなることです。

このスキルでは、調べる作業と覚えておく作業はメンバーと地図に預け、判断と言語化はユーザーに残します。

### メタ認知: 自分の理解を自分で測る（強）

自分が何をどこまでわかっているかを把握する働きをメタ認知と呼びます（Flavell, 1979）。人は仕組みを実際より深く理解していると思い込みやすく、説明を求められて初めてその浅さに気づきます（Rozenblit & Keil, 2002）。

最初と最後に自信を数字で聞くのは、理解の自己評価を目に見える形にするためです。進行役の説明が続いたらユーザーに説明してもらうのも同じ理由です。

### 心的モデルとたとえ話（中）

人は対象の働きを頭の中の模型として持ち、それを動かして推論します（Johnson-Laird, 1983）。たとえ話は、すでに知っている領域の関係の構造を新しい領域に写すことで、模型づくりを助けます（Gentner, 1983）。ただし写してはいけない部分まで写してしまう危険があります。

「たとえば」の手でたとえ話を使うときに、似ている範囲と違う範囲を一言添えるのはこのためです。

### 先に予想する（強）

答えを教わる前に自分で予想すると、外れた場合も含めてあとの学習が進みます（Richland et al., 2009）。自信を持って間違えた内容ほど、訂正がよく残ることも知られています（Butterfield & Metcalfe, 2001）。

先に自分の考えと自信を書いてもらう、メンバーの意見が割れる所を予想してもらう、という手順の根拠です。

### 二重過程（中）

推論には、速くて直感的な過程と、遅くて熟慮的な過程があると考えられています（Evans & Stanovich, 2013）。熟慮は労力がかかるので、もっともらしい答えが手元にあると起動しにくくなります。

AIの推奨案は、まさに「もっともらしい答えが手元にある」状態を作ります。

### 実践への参加（中）

技能は、実践の場に参加することで身につく、という見方です（Lave & Wenger, 1991）。チームの議論は、設計の決め方そのものを学ぶ場でもあります。

このスキルは人間の議論の代わりにはなりません。「しっかり」でチーム向けの論点メモを出すのは、ここで整理したものを人間の議論に持ち込んでもらうためです。

## 心理学

### 生成効果と自己説明（強）

自分で作り出した情報は、読んだだけの情報よりよく残ります（Slamecka & Graf, 1978）。学んでいる内容を自分に説明する人ほど理解が深まります（Chi et al., 1989; 1994）。締めの4行を代筆しないのはこのためです。

### アンカリング（強）

最初に示された値や案が、その後の判断の基準になります（Tversky & Kahneman, 1974）。進行役が案を選ばないこと、議題に候補を含めないこと、「どれがいい」と聞かれても先にユーザーの選択を聞くことの根拠です。

### 議論としての推論（中）

人の推論は、一人で真理に到達するためというより、他人を説得し、他人の主張を吟味するために働く、という説があります（Mercier & Sperber, 2011）。自分の主張の穴には甘く、他人の主張の穴には厳しい、という実験結果とも合います（Trouche et al., 2016）。意見を複数並べ、ユーザーに吟味してもらう形の根拠です。

### 独立に集める（強〜中）

集団で同時に話し合うと、順番待ちで考えが消えたり、先に出た意見に寄ったりして、個別に考えた場合より案が減ります（Diehl & Stroebe, 1987）。また集団は、全員が知っている情報ばかり話題にし、一人しか知らない情報を出しそびれます（Stasser & Titus, 1985）。メンバーに互いの意見を見せないこと、回答に【未確認】の欄を設けることの根拠です。

### 対人交流記憶と集合知（中）

集団は「誰が何を知っているか」を共有することで、個人を超える記憶の仕組みになります（Wegner, 1987）。集団の成績は、発言の機会が均等であるほど高い、という報告もあります（Woolley et al., 2010）。メンバーを見ている情報で分けること、発言を短くしてユーザーの発言の割合を保つことにつながります。後者の研究には追試での議論があります。

### 反対意見（中）

本心からの少数意見は、集団の考えを広げます。しかし役として反対させる「悪魔の代弁者」にはその効果が弱く、かえって元の立場を固めることがあります（Nemeth, Brown & Rogers, 2001; Nemeth, Connell, Rogers & Brown, 2001）。

これはこのスキルにとって不都合な知見です。言語モデルの意見は本心ではありません。そこで、反対を演じさせるのではなく、別の情報を見せて正直な見立てを返してもらう形にし、別のプロバイダーを混ぜて計算そのものを変えています。それで本心の反対意見と同じ効果が出るかはわかっていません。

### 構えの固着と孵化（中）

一度うまくいった解き方に縛られ、もっと簡単な解き方が見えなくなる現象があります（Luchins, 1942）。行き詰まったときに課題から離れると解決が進むことも、多くの研究をまとめた分析で支持されています（Sio & Ormerod, 2009）。「そもそも」の手と、「持ち越す」という終わり方の根拠です。

### 共通基盤と対話での整合（中）

会話では、互いに理解したことを確かめ合いながら共有の土台を積み上げます（Clark & Brennan, 1991）。対話する二人の言葉づかいや捉え方は、やりとりの中で自然に揃っていきます（Pickering & Garrod, 2004）。「つまり」を確認の問いとして出すこと、ユーザーの言葉をそのまま使うことの根拠です。

### 解釈レベル（中）

同じ対象を、抽象的に（なぜ）も、具体的に（どうやって）も捉えられ、どちらで捉えるかで判断が変わります（Trope & Liberman, 2010）。具体と抽象の往復を「つまり」と「たとえば」で意図的に起こしています。

### 事前検死（中）

「うまくいかなかった」と仮定して原因を考えると、「うまくいかないかもしれない」と考えるより多くの原因が挙がります（Mitchell, Russo & Pennington, 1989; Klein, 2007）。「逆から」の手の根拠です。

### 望ましい困難（中）

学習中に適度な困難があるほうが、その場の出来は下がっても、あとに残ります（Bjork, 1994）。このスキルはAIに答えを出させるより面倒に感じるはずで、それは設計どおりです。

### 足場かけ（中）

学び手が一人ではできないが、支えがあればできる範囲があり、支えはできるようになるにつれて外していきます（Vygotsky, 1978; Wood, Bruner & Ross, 1976）。「わからない」に具体例で応じること、慣れた分野では「軽め」で済ませられることにつながります。

## AIと人の協働についての研究

### 認知的降伏（中、査読前）

Shaw と Nave は、AIの出力をほとんど吟味せずに採用し、自分の直感も熟慮も上書きしてしまう現象を「認知的降伏」と名づけました（Shaw & Nave, 2026）。事前登録した3つの実験（参加者1,372人）で、AIが正しいと正答率が上がり、誤っていると下がりました（基準に対して＋25、−15ポイント）。AIを使うと、誤ったあとでも自信は上がりました。AIへの信頼が高い人、考えることへの欲求が低い人ほど降伏しやすい傾向も報告されています。確かめた時点では査読前でした。

### 自動化バイアス（強）

自動化された支援があると、人はその出力を点検しなくなり、誤りを見逃します（Parasuraman & Manzey, 2010）。航空や医療で長く研究されてきた現象です。

### 生成AIと批判的思考（中）

知識労働者319人への調査で、AIへの信頼が高いほど批判的思考が減り、自分の力への自信が高いほど増える、という関係が報告されています（Lee et al., 2025）。自己申告にもとづく調査です。先に自分の考えを書いてもらうことは、自分の考えを持った状態でAIの出力に向き合うための手順でもあります。

### 認知的強制（中）

AIの提案を見る前に自分で判断させる、といった仕掛け（認知的強制機能）は、AIへの過信を減らします。ただし、過信を最も減らした設計ほど、使い手からの評価は低くなりました。また、考えることへの欲求が高い人ほど恩恵を受けました（Buçinca, Malaya & Gajos, 2021）。

このスキルの「先に書く」はこの仕掛けそのものです。面倒に感じること、疲れているときには効きにくいことも、この研究から予想されます。「軽め」の規模と「持ち越す」という終わり方を用意しているのはそのためです。

### 流暢さ（中）

読みやすく滑らかな情報は、内容にかかわらず正しく感じられます（Alter & Oppenheimer, 2009）。言語モデルの文章は常に流暢なので、この錯覚が起きやすくなります。事実に `ファイル:行` を求め、確かめていないことを「未確認」と書かせるのは、流暢さではなく根拠で判断できるようにするためです。

### 迎合（中）

言語モデルは、相手が示した意見に合わせて回答を変える傾向があります（Sharma et al., 2023）。メンバーにユーザーの考えを渡さないこと、進行役が褒めないことの根拠です。

## あえて根拠にしなかったもの

- **意思決定疲労（自我消耗）**: 判断を重ねると意志力が減る、という説は広く知られていますが、大規模な追試で再現されませんでした（Hagger et al., 2016）。短時間に大量の判断をすると疲れる、という実感は本物でしょうが、このスキルでは作業記憶と認知負荷の側から説明しています。
- **学習スタイル**: 人によって合う学び方の型がある、という説は根拠が乏しいので使っていません。

## このスキルの限界

1. **効果は未検証。** 上の知見を組み合わせた設計であり、このスキル自体を試した結果ではありません。
2. **言語モデルは本心の反対者ではない。** 別のプロバイダーを混ぜても、学習した資料は重なっており、同じ所で同じ誤りをすることがあります。
3. **メンバーは暗黙の事情を知らない。** 過去の経緯、顧客との約束、チームの力量といった、コードに書かれていない知識は持っていません。人間のメンバーが持っていた知識のばらつきは再現しきれません。
4. **進行役もレールを敷く。** どの論点を地図に載せるか、どの手を使うかは進行役が選んでいます。案は選ばなくても、話の枠は作っています。地図を全部見せる、論点はユーザーに選んでもらう、という手当てをしていますが、なくなりはしません。
5. **面倒である。** 効く仕組みと面倒さは裏表です。急ぎの小さな判断に使うものではありません。

重い判断ほど、ここで論点を整理したうえで人間の議論に持ち込んでください。

## 文献

### 確認済み（作成時に検索して書誌と要旨を確認）

- Buçinca, Z., Malaya, M. B., & Gajos, K. Z. (2021). To trust or to think: Cognitive forcing functions can reduce overreliance on AI in AI-assisted decision-making. *Proceedings of the ACM on Human-Computer Interaction, 5*(CSCW1), Article 188.
- Lee, H.-P., Sarkar, A., Tankelevitch, L., Drosos, I., Rintel, S., Banks, R., & Wilson, N. (2025). The impact of generative AI on critical thinking. *CHI '25*.
- Nemeth, C., Brown, K., & Rogers, J. (2001). Devil's advocate versus authentic dissent: Stimulating quantity and quality. *European Journal of Social Psychology, 31*.
- Nemeth, C., Connell, J. B., Rogers, J. D., & Brown, K. S. (2001). Improving decision making by means of dissent. *Journal of Applied Social Psychology, 31*(1), 48–58.
- Shaw, S. D., & Nave, G. (2026). Thinking—fast, slow, and artificial: How AI is reshaping human reasoning and the rise of cognitive surrender. Wharton School Research Paper（査読前）.

### 記憶からの引用（原典未確認）

- Alter, A. L., & Oppenheimer, D. M. (2009). Uniting the tribes of fluency to form a metacognitive nation. *Personality and Social Psychology Review*.
- Bjork, R. A. (1994). Memory and metamemory considerations in the training of human beings. In *Metacognition: Knowing about knowing*.
- Butterfield, B., & Metcalfe, J. (2001). Errors committed with high confidence are hypercorrected. *Journal of Experimental Psychology: Learning, Memory, and Cognition*.
- Chase, W. G., & Simon, H. A. (1973). Perception in chess. *Cognitive Psychology*.
- Chi, M. T. H., Bassok, M., Lewis, M. W., Reimann, P., & Glaser, R. (1989). Self-explanations. *Cognitive Science*.
- Chi, M. T. H., de Leeuw, N., Chiu, M.-H., & LaVancher, C. (1994). Eliciting self-explanations improves understanding. *Cognitive Science*.
- Chi, M. T. H., & Wylie, R. (2014). The ICAP framework: Linking cognitive engagement to active learning outcomes. *Educational Psychologist*.
- Clark, A., & Chalmers, D. (1998). The extended mind. *Analysis*.
- Clark, H. H., & Brennan, S. E. (1991). Grounding in communication. In *Perspectives on socially shared cognition*.
- Cowan, N. (2001). The magical number 4 in short-term memory. *Behavioral and Brain Sciences*.
- Diehl, M., & Stroebe, W. (1987). Productivity loss in brainstorming groups. *Journal of Personality and Social Psychology*.
- Evans, J. St. B. T., & Stanovich, K. E. (2013). Dual-process theories of higher cognition. *Perspectives on Psychological Science*.
- Flavell, J. H. (1979). Metacognition and cognitive monitoring. *American Psychologist*.
- Gentner, D. (1983). Structure-mapping: A theoretical framework for analogy. *Cognitive Science*.
- Hagger, M. S., et al. (2016). A multilab preregistered replication of the ego-depletion effect. *Perspectives on Psychological Science*.
- Hatano, G., & Inagaki, K. (1991). Sharing cognition through collective comprehension activity. In *Perspectives on socially shared cognition*.
- Hutchins, E. (1995). *Cognition in the wild*. MIT Press.
- Johnson-Laird, P. N. (1983). *Mental models*. Harvard University Press.
- Kalyuga, S., Ayres, P., Chandler, P., & Sweller, J. (2003). The expertise reversal effect. *Educational Psychologist*.
- Kirsh, D. (2010). Thinking with external representations. *AI & Society*.
- Klein, G. (1998). *Sources of power: How people make decisions*. MIT Press.
- Klein, G. (2007). Performing a project premortem. *Harvard Business Review*.
- Lave, J., & Wenger, E. (1991). *Situated learning: Legitimate peripheral participation*. Cambridge University Press.
- Luchins, A. S. (1942). Mechanization in problem solving. *Psychological Monographs*.
- Mercier, H., & Sperber, D. (2011). Why do humans reason? Arguments for an argumentative theory. *Behavioral and Brain Sciences*.
- Mitchell, D. J., Russo, J. E., & Pennington, N. (1989). Back to the future: Temporal perspective in the explanation of events. *Journal of Behavioral Decision Making*.
- Miyake, N. (1986). Constructive interaction and the iterative process of understanding. *Cognitive Science*.
- Parasuraman, R., & Manzey, D. H. (2010). Complacency and bias in human use of automation. *Human Factors*.
- Pickering, M. J., & Garrod, S. (2004). Toward a mechanistic psychology of dialogue. *Behavioral and Brain Sciences*.
- Richland, L. E., Kornell, N., & Kao, L. S. (2009). The pretesting effect. *Journal of Experimental Psychology: Applied*.
- Risko, E. F., & Gilbert, S. J. (2016). Cognitive offloading. *Trends in Cognitive Sciences*.
- Rozenblit, L., & Keil, F. (2002). The misunderstood limits of folk science: An illusion of explanatory depth. *Cognitive Science*.
- Sharma, M., et al. (2023). Towards understanding sycophancy in language models. arXiv.
- Sio, U. N., & Ormerod, T. C. (2009). Does incubation enhance problem solving? A meta-analytic review. *Psychological Bulletin*.
- Slamecka, N. J., & Graf, P. (1978). The generation effect. *Journal of Experimental Psychology: Human Learning and Memory*.
- Stasser, G., & Titus, W. (1985). Pooling of unshared information in group decision making. *Journal of Personality and Social Psychology*.
- Sweller, J. (1988). Cognitive load during problem solving. *Cognitive Science*.
- Trope, Y., & Liberman, N. (2010). Construal-level theory of psychological distance. *Psychological Review*.
- Trouche, E., Johansson, P., Hall, L., & Mercier, H. (2016). The selective laziness of reasoning. *Cognitive Science*.
- Tversky, A., & Kahneman, D. (1974). Judgment under uncertainty: Heuristics and biases. *Science*.
- Vygotsky, L. S. (1978). *Mind in society*. Harvard University Press.
- Wegner, D. M. (1987). Transactive memory: A contemporary analysis of the group mind. In *Theories of group behavior*.
- Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry*.
- Woolley, A. W., Chabris, C. F., Pentland, A., Hashmi, N., & Malone, T. W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*.
