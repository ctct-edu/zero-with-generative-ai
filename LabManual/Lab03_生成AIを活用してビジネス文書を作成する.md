# ラボ 03：生成AIを活用してビジネス文書を作成する

#### 推定時間: 20 分



## タスク1 - 演習環境へアクセスする

このタスクでは、生成AIラボへアクセスします。

1. 新しい InPrivate ブラウザー ウィンドウを開きます。

   > 　  どのWebブラウザもウィンドウ右上の設定ボタンから表示することが可能です。
   >
   > 　  Microsoft Edgeでは「InPrivate」ウィンドウ
   >
   > 　  Google Chromeでは「シークレット」ウィンドウ
   >
   > 　  Mozilla Fire Foxでは「プライベート」ウィンドウ

   ![Learn01](./media/Learn01.BMP)

   

2. https://ctctedu-aiplatform.azurewebsites.net/ へアクセスし、以下のアカウントでサインインします。

   > 注：XXXは受講者ごとに異なります。
   >
   > 注：「アカウントの保護にご協力ください」と表示された場合は「今はしない」を選択してください

   | 項目       | 値                                  |
   | ---------- | ----------------------------------- |
   | ユーザーID | `aiuserXXX@ctctedu.onmicrosoft.com` |
   | パスワード | 講師から配布されたパスワード        |

   ![Learn02](./media/Learn02.BMP)

   

3. [要求されているアクセス許可] ページでは、 [承諾] をクリックします 。

   ![Learn03](./media/Learn03.BMP)

   

4. [Start chatting] ページが表示されればサインイン完了となります。

   ![Learn04](./media/Learn04.BMP)

   



## タスク2 - テーマ別にビジネス文書を生成する

このタスクでは、以下のいずれかのテーマに沿って、自分自身でプロンプトを考え、生成してみます。なお、この演習には正解はありません。

ご自身がイメージした内容や、自分が納得できるアイデアにたどり着くまで試してみてください。



- **テーマ１　健康食品のPR文書を生成する**

  あなたの会社では、健康食品「すこやかんせつ」（健やか＋関節の造語）を販売しています。あなたは宣伝用の企画書あるいはPR文書を作成することになりました。以下の製品特徴は以下の通りです。

  ------

  | 項目             | 詳細                                                         |
  | ---------------- | ------------------------------------------------------------ |
  | **製品名**       | すこやかんせつ                                               |
  | **特長**         | 関節の健康をサポートし、日常生活の動きやすさを向上させる健康食品 |
  | **成分**         | - グルコサミン<br>- コンドロイチン<br>- MSM（メチルスルフォニルメタン）<br>- ビタミンD<br>- コラーゲンペプチド |
  | **ターゲット層** | 関節の健康を気にする全ての方<br>特に中高年層やアスリートなど |
  | **価格**         | 200g（カプセル）で2000円                                     |

  ------

  **詳細説明**

  **特長**: 「すこやかんせつ」は、関節の健康を維持し、日々の生活を快適に過ごすために必要な栄養素をバランスよく配合しています。天然成分を使用し、高い吸収率と科学的根拠に基づいた成分配合で信頼性の高い製品です。

  **成分**:

  - **グルコサミン**: 関節の軟骨を保護し、柔軟性を保つのに役立ちます。
  - **コンドロイチン**: 関節の潤滑を助け、摩擦を減少させる効果があります。
  - **MSM（メチルスルフォニルメタン）**: 炎症を軽減し、痛みを和らげる効果が期待されています。
  - **ビタミンD**: 骨の健康を支えるために必要な栄養素で、カルシウムの吸収を助けます。
  - **コラーゲンペプチド**: 関節の弾力性を高め、若々しい動きをサポートします。

  **ターゲット層**: 「すこやかんせつ」は、関節の健康を気にする全ての方に最適です。特に中高年層やアスリートなど、日々の動きやすさを重視する方々におすすめです。

  **価格**: 200g（カプセル）で2000円というお手頃価格で提供しています。公式オンラインショップおよび全国の主要ドラッグストアでお求めいただけます。



- **テーマ２　工事現場での事故報告書を作成**

  あなたの会社は大手建設会社です。ある日の午後、工事現場で大規模な鉄骨の設置作業が行われていました。現場は忙しく、作業員たちは次々と指示を受けて働いていました。その中で、クレーンが鉄骨を吊り上げている最中に突然バランスを崩し、大きな音と共に鉄骨が崩れ落ちる事故が発生しました。事故に巻き込まれた作業員は4人。幸いにも全員軽傷で済みましたが、事故原因の調査が始まりました。証言は以下の通りです。これらを元に報告と再発防止策を提出してください。

  | 名前  | 役割           | 証言                                                         | 状況                                                         | 時刻  |
  | ----- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----- |
  | Aさん | 現場監督       | 「事故の直前に、クレーンの動きが不安定だと感じて作業を一時停止するよう指示を出していた。しかし、一部の作業員がその指示を無視して作業を続けた。」 | 事故発生時、現場の中央付近で監督していた。                   | 14:45 |
  | Bさん | クレーン操作員 | 「クレーンで鉄骨を吊り上げている最中に、急にバランスが崩れた。どこかで固定が外れたように感じた。」 | クレーン操作室にいた。事故後にすぐにクレーンを停止。         | 14:50 |
  | Cさん | 作業員         | 「指示通りに作業を停止したが、一部の同僚が続けて作業をしていた。突然、鉄骨が崩れ落ちた。」 | 事故発生時、作業エリアの端で待機していた。                   | 14:55 |
  | Dさん | 作業員         | 「作業を続けていたが、クレーンの固定が甘かったようだ。急にバランスを失って倒れた。」 | 事故発生時、鉄骨近くで作業していた。倒れた鉄骨の下敷きにはならなかったが、軽傷を負った。 | 15:00 |

  

- **テーマ３　商社におけるコスト改善の提案資料作成**

  あなたの会社では、長年にわたり海外からの鉄鋼輸入および材料研究を行ってきました。しかし、ここ数年、慢性的な円安が続いており、輸入コストの上昇により鉄鋼の価格を上げざるを得ない状況に直面しています。このままでは、顧客への価格転嫁が避けられず、競争力の低下も懸念されます。そこで、我々はこの課題を乗り越えるためにいくつかの打開策を検討しております。そこであなたは各部署から出された案をまとめ、経営企画会議で報告することになりました。各部署の意見は以下の通りです。

  | 部署  | 案の概要                   | 具体策                                                       | 数値目標                                                     |
  | ----- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 部署A | 調達先の多様化             | - 円安影響を受けにくい国（例：インド、ベトナム、ブラジル）からの輸入ルートを新たに3つ開拓<br>- 為替リスク評価と長期契約を最低5件締結<br>- サプライヤーとの関係強化のため、年2回の現地訪問と交渉力向上のための研修実施 | - 調達先の多様化率を現行の20%から50%に拡大<br>- 為替リスクを最大10%低減 |
  | 部署B | 鉄鋼リサイクル推進         | - 国内リサイクル施設を2箇所新設し、既存施設の設備更新を3箇所実施<br>- リサイクル技術向上のため、年間予算の15%を研究開発に投資<br>- 廃棄物回収システムの整備と効率化のため、GPSトラッキングとデータ解析技術を導入<br>- リサイクル素材の利用拡大に向けた顧客向けセミナーを年4回開催 | - リサイクル率を現行の30%から60%に向上<br>- 年間リサイクル量を20,000トンから40,000トンに倍増 |
  | 部署C | 新素材および加工技術の開発 | - 新合金や軽量・高強度素材の開発プロジェクトを5件立ち上げ<br>- 大学や研究機関との共同研究契約を3件締結し、共同研究予算を年間20%増加<br>- 新素材の商業化に向けたプロトタイプを年間10種類製造<br>- カスタマイズ製品の提供とマーケット開拓のため、マーケティングチームを増員し、年間販売イベントを6回開催 | - 新素材の市場シェアを5%確保<br>- 研究開発費の年次増加率を10%設定 |
  | 部署D | デジタル化と自動化の推進   | - IoTとAI技術を活用したスマートファクトリーを2箇所導入<br>- 生産ラインの自動化とロボット導入により、10ラインを自動化<br>- データ解析による生産プロセス最適化のため、ビッグデータ解析システムを導入<br>- デジタルツイン技術によるシミュレーションと予防保全のため、年間予算の15%をITインフラに投資 | - 生産効率を20%向上<br>- 人件費を15%削減<br>- 設備稼働率を90%に向上 |

  

  その他にも、様々なことを聞いて試してみて下さい。



**Lab03 は以上となります。お疲れ様でした。**
