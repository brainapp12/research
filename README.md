# brainapp事業メモ
- 主に事業のポイントまとめに活用する場所
- 新しく構築したWebアプリや大規模データの処理機構を蓄積して世の中に役立てたい場所
- 研究↔︎開発↔︎実装 の循環を上手に磨き上げるビジネスモデルを
a
## はじめに
- 本ページで紹介すること
- brainappで開発したアプリやサービス
- やってきたことや興味のある技術など

【目的と実施項目】
1. NLPの技術を活かした論文解析、情報検索、企画・開発支援の取り組み（AlphaHedgeの事業内容）をまとめる
2. 誰でもいつでも見ることができ、管理と改良もしやすい状況を作るために、github pagesでWebサイトを作ってみる


## 追加したことなど
2024/07/19
- cssを若干変えてみた。GPTのMac用アプリを入れてみたので、すごく便利になった。
- gpt-4o-miniとの対話形式やりとりページ追加

2024/08/02
- より簡単にLLMを使ってもらえるように修正したい

2024/10/14
- ちょっと間は空いたけど、進捗したこと
  - RAG（brainappRAG）の構築
  -   multilungual-e5-base＋faiss＋gpt-4o-miniの座組
  - ArrowPro-7B-KUJIRA・Japanese Stable LM Base Gamma 7B・Swallow-7b-instruct-hfの検証
  - 10/14の検証だとArrowPro-7B-KUJIRAが特に応答が良さげ

2024/10/15
- RAGの活用で業務改善サービスを構築する
  - brainappRAG：独自データ導入・ベクトル検索・クエリに基づく生成まで実施可能
  - ベクトル検索部分の技術的更新の容易さが課題
 
2024/10/20
- WixのWebサイトに合わせてgithub pagesでも再度構築してみる
-   未着手なので本日10/20より再度作成を再開する

2024/11/11
- 相当進捗している
-   brainappYouTube動画タイトル分析、RAG、GraphRAG、GNN-RAG、Two-tower推薦モデル（SNSデータ×YouTube、SNSデータ×学術論文）、RLHF、brainapp×Createアプリ
