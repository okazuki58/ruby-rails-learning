# Ruby/Rails 基礎・発展学習ログ

Ruby/Railsの基礎から発展まで体系的に学ぶための学習ログリポジトリ。
Phase 1からPhase 4まで、段階的に学習を進める。（合計20-25日間）

## Phase 1: Ruby の基礎（5日）

### Day 1: クラスとオブジェクト
- クラスの作り方
- initialize, インスタンス変数
- public/private/protected
- attr_reader/writer/accessor
- クラス変数とクラスメソッド

### Day 2: 配列とハッシュの操作
- each, map, select, reject
- find, find_all, any?, all?
- sum, group_by, partition
- ハッシュの操作（merge, slice, dig, transform_keys/values）

### Day 3: ブロック、Proc、yield
- ブロックとは何か
- yield の使い方
- Proc と lambda の違い
- &:method_name の仕組み
- ブロックを引数として受け取る

### Day 4: モジュールとミックスイン
- module の作り方
- include と extend と prepend の違い
- 名前空間としての利用
- 実践的な使い方

### Day 5: 例外処理とデバッグ
- begin/rescue/ensure/else
- 独自例外の作り方
- raise と throw/catch
- デバッグの基本（binding.pry, puts debugging）

## Phase 2: Ruby の発展（3-4日）

### Day 6: メタプログラミング基礎
- define_method でメソッドを動的に定義
- method_missing の使い方と注意点
- class_eval と instance_eval
- const_missing

### Day 7: リフレクション
- send, public_send
- respond_to?
- methods, instance_methods
- instance_variable_get/set

### Day 8: 特異メソッドと特異クラス
- 特異メソッドとは
- 特異クラス（eigenclass）
- class << self の仕組み
- オブジェクト固有の振る舞い

### Day 9（オプション）: Ruby標準ライブラリ活用
- Date, Time, DateTime
- File, Dir操作
- JSON, CSV処理
- Enumerable, Enumerator

## Phase 3: Rails の基礎（6-7日）

### Day 10: Rails概要とActiveRecord基礎
- Railsの思想（CoC, DRY）
- MVCアーキテクチャ
- ActiveRecordの基本（CRUD操作）
- マイグレーション

### Day 11: Association（関連付け）
- belongs_to, has_many, has_one
- has_many :through
- polymorphic association
- dependent オプション

### Day 12: Validation と Callback
- 標準的なバリデーション
- カスタムバリデーション
- before_save, after_create等のコールバック
- コールバックの実行順序

### Day 13: クエリとパフォーマンス
- where, find, find_by の違い
- N+1問題と includes, preload, eager_load
- joins vs includes
- scope の使い方
- pluck, select の使い分け

### Day 14: ルーティングとコントローラー基礎
- RESTful設計
- resources, resourceルーティング
- ネストしたルーティング
- Strong Parameters
- before_action

### Day 15: コントローラー発展
- レスポンス形式（HTML, JSON）
- リダイレクトとレンダリング
- セッションとCookie
- フラッシュメッセージ

### Day 16: ビューとヘルパー
- ERBテンプレート
- パーシャル
- レイアウト
- ヘルパーメソッド
- form_with の使い方

## Phase 4: Rails の発展（6-8日）

### Day 17: 認証（Authentication）
- Deviseの導入と設定
- ユーザー登録、ログイン、ログアウト
- パスワードリセット
- メール確認

### Day 18: 認可（Authorization）
- Pundit または CanCanCan
- ポリシーベースの権限管理
- ロールベースのアクセス制御

### Day 19: API開発
- RESTful API設計
- JSON serialization（Active Model Serializers / jbuilder）
- APIバージョニング
- CORS設定

### Day 20: テスト基礎（RSpec）
- RSpecのセットアップ
- Model spec
- Request spec
- FactoryBot の使い方

### Day 21: テスト発展
- System spec（統合テスト）
- テストダブル（stub, mock）
- テストカバレッジ
- テストの設計思想

### Day 22: 設計パターン（1）
- Service Object（ビジネスロジックの分離）
- Form Object（複雑なフォームの扱い）
- Query Object（複雑なクエリの整理）

### Day 23: 設計パターン（2）
- Decorator/Presenter（ビューロジックの分離）
- Concern（コードの再利用）
- Value Object
- ファットモデル vs サービス層

### Day 24: バックグラウンドジョブ
- Active Job の基礎
- Sidekiq の導入
- 非同期処理の設計
- ジョブの監視とリトライ

### Day 25（オプション）: Action Cable
- WebSocketの基礎
- Action Cableのセットアップ
- リアルタイム通知の実装
- チャット機能の実装

## 学習の進め方

各Dayの学習Issueはすでに作成済みです。学習を開始する際は：

1. Claude Codeで `day2を進めたい` のようにプロンプトを入力
2. 該当するIssueで学習を進める
3. 学習完了後、Issueにまとめを追加してクローズ

## 学習後の実践

このリポジトリで基礎・発展を学んだ後は、別リポジトリで実践的なプロジェクトを構築し、学んだ知識を統合する。
