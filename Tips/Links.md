# 生成AI入門研修 外部参照リンク集

このリンク集は、「ゼロから始める生成AI」の各章に対応する公式資料をまとめたものです。研修内容を復習するときや、サービスの機能、利用条件、法制度の最新情報を確認するときに使用してください。

> **情報確認日: 2026年8月4日**
>
> 生成AIサービスの名称、機能、利用条件、料金、データの取り扱い、法制度は更新される可能性があります。実際に利用するときは、リンク先の最新版と所属組織の規程を確認してください。
>
> 本リンク集では日本語資料を優先しています。日本語の公式資料がない、または英語版の方が情報が新しい場合は、`英語` と明記して掲載しています。

## 迷ったらここから

最初からすべてを読む必要はありません。まずは、学習したい章に対応する資料を1つ選んでください。

| 章 | まず読む資料 | 選定理由 |
|---|---|---|
| 第1章 | [ChatGPTの機能概要](https://help.openai.com/en/articles/9260256-chatgpt-capabilities-overview) | 生成AIサービスでできる代表的な作業を一覧できます。 |
| 第1章 | [AWSの生成AIサービスを選ぶ](https://docs.aws.amazon.com/generative-ai-on-aws-how-to-choose/) | 生成AIを利用するサービス、アプリケーションを構築するサービス、基盤の違いを俯瞰できます。 |
| 第2章 | [Microsoft 365 Copilotでのプロンプトの書き方](https://support.microsoft.com/ja-jp/microsoft-365-copilot/get-started-writing-prompts-in-microsoft-365-copilot) | 「目標・コンテキスト・期待値・ソース」の4要素を具体例とともに確認できます。 |
| 第2章 | [プロンプト設計戦略](https://ai.google.dev/gemini-api/docs/prompting-strategies) | 明確な指示、例示、背景情報、入力の構造化など、主要な改善方法を体系的に確認できます。 |
| 第3章 | [AI事業者ガイドライン](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/) | 日本でAIを開発・提供・利用する際の基本的な考え方を確認できます。 |
| 第3章 | [AIと著作権について](https://www.bunka.go.jp/seisaku/chosakuken/aiandcopyright.html) | 生成AIと著作権について、文化庁の整理とチェックリストを確認できます。 |
| 第4章 | [Claudeでファイルを作成・編集する](https://support.claude.com/en/articles/12111783-create-and-edit-files-with-claude) | 文書、表計算、プレゼンテーション、PDF、データ分析への活用例を確認できます。 |
| 第4章 | [Geminiアプリでファイルをアップロードして分析する](https://support.google.com/gemini/answer/14903178?hl=ja) | 文書、表計算、画像などを要約・分析する方法を確認できます。 |

---

## 第1章 AIって色々あります

各社の公式資料を見比べると、生成AIサービスに共通する機能と、モデルや提供形態による違いを整理できます。その後、基盤モデル、マルチモーダル、AIエージェントなど、生成AIを支える考え方へ進んでください。

### まず読む

- [Microsoft 365 Copilot Chatの概要](https://learn.microsoft.com/ja-jp/copilot/overview) — **Microsoft／日本語**：Web情報に基づくチャット、ファイルの追加、画像生成、エージェントなど、Copilot Chatの主要機能を確認できます。
- [ChatGPTの機能概要](https://help.openai.com/en/articles/9260256-chatgpt-capabilities-overview) — **OpenAI／英語**：質問回答、文章作成、要約、Web検索、画像やファイルの利用など、ChatGPTでできる代表的な作業を確認できます。
- [Claudeの概要](https://platform.claude.com/docs/en/intro) — **Anthropic／英語**：Claudeが文章、推論、分析、コーディング、画像理解などに対応する生成AIであることを確認できます。
- [Geminiアプリ ヘルプ](https://support.google.com/gemini/?hl=ja) — **Google／日本語**：Geminiアプリの基本操作、利用できる機能、設定、トラブルへの対処を探せる公式ヘルプです。

### さらに知る

- [Microsoft 365 Copilotの概要](https://learn.microsoft.com/ja-jp/microsoft-365/copilot/microsoft-365-copilot-overview) — **Microsoft／日本語**：Microsoft GraphやMicrosoft 365アプリと連携する有償版Copilotの仕組みを確認し、Copilot Chatとの違いを整理できます。
- [OpenAIのモデル一覧](https://developers.openai.com/api/docs/models) — **OpenAI／英語・技術者向け**：モデルごとに対応する入力・出力、推論、画像、音声などの違いを確認できます。
- [Geminiアプリを使用する](https://support.google.com/gemini/answer/13275745?hl=ja) — **Google／日本語**：Geminiへの質問、回答の確認、会話の継続など、基本的な使い方を確認できます。
- [AWSの生成AIサービスを選ぶ](https://docs.aws.amazon.com/generative-ai-on-aws-how-to-choose/) — **AWS／英語**：すぐに使えるAI支援サービス、基盤モデルを利用するサービス、AIを開発する基盤の違いを俯瞰できます。
- [Amazon Bedrockの概要](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html) — **AWS／英語・技術者向け**：複数企業の基盤モデルを選び、生成AIアプリケーションを構築するマネージドサービスの概要を確認できます。
- [Claudeモデルの概要](https://platform.claude.com/docs/en/about-claude/models/overview) — **Anthropic／英語・技術者向け**：Claudeのモデル群について、能力、速度、コンテキスト長、利用できるプラットフォームなどの違いを確認できます。

---

## 第2章 生成AIにうまくお願いする方法

プロンプトには唯一の正解があるわけではありません。各社の整理方法を見比べながら、「目的」「背景情報」「参照資料」「例」「制約」「出力形式」「反復改善」のうち、必要な要素を選んでください。

### まず読む

- [Microsoft 365 Copilotでのプロンプトの書き方](https://support.microsoft.com/ja-jp/microsoft-365-copilot/get-started-writing-prompts-in-microsoft-365-copilot) — **Microsoft／日本語**：プロンプトを「目標・コンテキスト・期待値・ソース」の4要素で組み立てる方法と具体例を確認できます。
- [Copilotプロンプトギャラリーについて](https://learn.microsoft.com/ja-jp/microsoft-365/copilot/copilot-prompt-gallery) — **Microsoft／日本語**：Microsoftが用意したプロンプト例を探し、保存、調整、共有するための考え方を確認できます。
- [Prompt engineering](https://developers.openai.com/api/docs/guides/prompt-engineering) — **OpenAI／英語・技術者向け**：指示の優先順位、関連する背景情報、例示、再利用可能なプロンプトなど、回答を制御する基本技法を確認できます。
- [プロンプト設計戦略](https://ai.google.dev/gemini-api/docs/prompting-strategies) — **Google／英語**：明確な指示、少数例、背景情報、入力の構造化、複雑な作業の分割などを具体例付きで学べます。

### さらに知る

- [OpenAIのモデル向けガイダンス](https://developers.openai.com/api/docs/guides/latest-model) — **OpenAI／英語・発展**：新しいモデルに対して、目的、制約、証拠、成功条件、出力形式を伝える際の実践的な考え方を確認できます。
- [Claudeのプロンプトエンジニアリング概要](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) — **Anthropic／英語**：プロンプトを改善する前に成功条件を定義し、結果を評価しながら改善する流れを確認できます。
- [Claudeのプロンプト作成ベストプラクティス](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — **Anthropic／英語・発展**：明確な指示、背景説明、例示、構造化、出力形式の指定などを詳しく確認できます。
- [Gemini API Prompt Gallery](https://ai.google.dev/gemini-api/prompts) — **Google／英語**：分類、要約、抽出、文章作成など、目的別の公式プロンプト例を参照できます。
- [Amazon Bedrockのプロンプトエンジニアリング概念](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-engineering-guidelines.html) — **AWS／英語・技術者向け**：指示、コンテキスト、入力データ、出力指示を組み合わせる基本構造を確認できます。
- [プロンプトエンジニアリングとは](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-prompt-engineering.html) — **AWS／英語**：プロンプトエンジニアリングの目的と、ゼロショット、少数例、思考を促す手法などの用語を整理できます。

---

## 第3章 生成AIを賢く、安全に使おう

安全な利用では、サービス提供者の説明だけでなく、行政機関や標準化関連団体の資料も確認することが重要です。最初に日本のガイドライン、個人情報、著作権を読み、必要に応じて海外制度や技術的な対策へ進んでください。

### まず読む

- [AI事業者ガイドライン](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/) — **経済産業省・IPA・AISI／日本語**：AIの開発者、提供者、利用者が考慮すべき事項をまとめた最新版を確認できます。2026年3月31日に第1.2版が公開されています。
- [生成AIサービスの利用に関する注意喚起](https://www.ppc.go.jp/news/careful_information/230602_AI_utilize_alert/) — **個人情報保護委員会／日本語**：個人情報や要配慮個人情報を生成AIへ入力するときの注意点を確認できます。
- [AIと著作権について](https://www.bunka.go.jp/seisaku/chosakuken/aiandcopyright.html) — **文化庁／日本語**：AI学習時と生成・利用時の著作権上の考え方、チェックリスト、解説資料を確認できます。
- [人工知能関連技術の研究開発及び活用の推進に関する法律（AI法）](https://www8.cao.go.jp/cstp/ai/ai_act/ai_act.html) — **内閣府／日本語**：2025年に公布・施行された日本のAI法について、目的、概要、法文へのリンクを確認できます。
- [AIセキュリティ](https://www.ipa.go.jp/digital/ai/security/index.html) — **IPA／日本語**：生成AI利用者向けの基本的なセキュリティ対策、代表的な攻撃、最新の調査資料を確認できます。

### さらに知る

- [AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) — **欧州委員会／英語**：EU AI Actのリスクベースの考え方、適用時期、生成AIや汎用AIモデルに関するルールを確認できます。
- [C2PA Specifications](https://spec.c2pa.org/specifications/specifications/2.2/index.html) — **C2PA／英語・技術者向け**：画像などの作成元や編集履歴を検証可能にするContent Credentialsの仕様と解説を確認できます。
- [Microsoft 365 CopilotとCopilot Chatのエンタープライズデータ保護](https://learn.microsoft.com/en-us/microsoft-365/copilot/enterprise-data-protection) — **Microsoft／英語**：プロンプト、応答、アクセス権、暗号化、基盤モデルの学習への利用有無など、法人向けの保護内容を確認できます。
- [Business data privacy, security, and compliance](https://openai.com/business-data/) — **OpenAI／英語**：法人向けChatGPTとAPIにおけるデータの学習利用、暗号化、保持、管理機能を確認できます。
- [Geminiアプリのプライバシーハブ](https://support.google.com/gemini/answer/13594961?hl=ja) — **Google／日本語**：Geminiへ提供する情報、収集される情報、モデル改善への利用、履歴やプライバシー設定を確認できます。
- [商用製品の個人データをモデル学習にどう利用するか](https://privacy.claude.com/en/articles/7996885-how-do-you-use-personal-data-in-model-training) — **Anthropic／英語**：Claude for WorkやAnthropic APIなど、商用製品におけるデータとモデル学習の考え方を確認できます。
- [AWS SRA for AI](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture-generative-ai/gen-ai-sra.html) — **AWS／英語・発展**：生成AIにおける権限管理、データ保護、入出力検証、ネットワーク分離、ログ、監視などのセキュリティ対策を確認できます。

---

## 第4章 生成AIの面白い使い方

各社の公式資料を見比べながら、調査、要約、文章作成、ファイル分析、画像や資料の作成など、サービスを問わず応用できる活用方法を確認してください。実際に使う際は、利用できる機能とデータの取り扱いをサービスごとに確認します。

### まず読む

- [Microsoft 365 Copilot Chatの使用を開始する](https://support.microsoft.com/ja-jp/microsoft-365-copilot/get-started-with-microsoft-365-copilot-chat) — **Microsoft／日本語**：サインイン、プロンプトの入力、ファイルや画像の追加、回答の生成という基本操作を確認できます。
- [ChatGPT for any role](https://academy.openai.com/public/clubs/work-users-ynjqu/resources/chatgpt-for-any-role) — **OpenAI／英語**：メール作成、文章改善、分析、計画など、職種を問わず使える業務例とプロンプト例を確認できます。
- [Claudeでファイルを作成・編集する](https://support.claude.com/en/articles/12111783-create-and-edit-files-with-claude) — **Anthropic／英語**：文書、表計算、プレゼンテーション、PDF、グラフ、データ分析などの作成例を確認できます。
- [Geminiアプリを使用する](https://support.google.com/gemini/answer/13275745?hl=ja) — **Google／日本語**：質問、文章作成、アイデア出し、画像やファイルを使った代表的な操作を確認できます。
- [AWSの生成AIサービスを選ぶ](https://docs.aws.amazon.com/generative-ai-on-aws-how-to-choose/) — **AWS／英語**：文章生成、分析、業務支援、生成AIアプリケーション構築など、目的に応じたサービスの選び方を確認できます。

### さらに知る

- [Microsoft 365 Copilot Chatのよくある質問](https://support.microsoft.com/ja-jp/microsoft-365-copilot/frequently-asked-questions-about-microsoft-365-copilot-chat) — **Microsoft／日本語**：調査、要約、文章作成、比較、画像生成、スキル学習など、Copilot Chatで試せる代表的な用途とプロンプト例を確認できます。
- [OpenAI Academy](https://openai.com/academy/) — **OpenAI／英語**：AIの基礎、日常業務、教育、エージェント、ワークフローなど、目的別の公式学習コンテンツを参照できます。
- [Claudeへファイルをアップロードする](https://support.claude.com/en/articles/8241126-upload-files-to-claude) — **Anthropic／英語**：文書や画像の対応形式、アップロード方法、PDFや大きなファイルを扱うときの注意点を確認できます。
- [Geminiアプリでファイルをアップロードして分析する](https://support.google.com/gemini/answer/14903178?hl=ja) — **Google／日本語**：文書、表計算、画像などを追加し、要約、分析、グラフ作成を依頼する方法を確認できます。
- [Amazon Q Businessとは](https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/what-is.html) — **AWS／英語**：組織内情報に基づく質問回答、要約、コンテンツ生成、タスク支援と、アクセス権に応じた回答の仕組みを確認できます。

---

## 利用時の確認ポイント

- 生成結果に日付、数値、制度、製品仕様が含まれる場合は、リンク先の一次情報と照合してください。
- サービスへ入力してよい情報かを、所属組織の情報管理規程で確認してください。
- 無償版と有償版、個人向けと法人向けでは、機能やデータの取り扱いが異なる場合があります。
- 法律やガイドラインについて判断に迷う場合は、所属組織の法務、情報セキュリティ、個人情報保護の担当者へ相談してください。
