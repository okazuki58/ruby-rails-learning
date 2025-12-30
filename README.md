# Ruby/Rails 基礎学習ログ

Ruby/Railsの基礎を学ぶための学習ログリポジトリ。
Phase 1からPhase 3まで、段階的に学習を進める。

## Phase 1: Ruby の基礎（3-5日）

### Day 1: クラスとオブジェクト ✅
- クラスの作り方
- initialize, インスタンス変数
- public/private
- attr_reader/writer/accessor

### Day 2: 配列とハッシュの操作
問題形式で学ぶ
- each, map, select, reject
- find, find_all
- sum, group_by
- ハッシュの操作（merge, slice, dig）

### Day 3: ブロック、Proc、yield
問題形式で学ぶ
- ブロックとは何か
- yield の使い方
- Proc と lambda の違い
- &:method_name の仕組み

### Day 4: モジュールとミックスイン
問題形式で学ぶ
- module の作り方
- include と extend の違い
- 実践的な使い方

### Day 5: 例外処理とデバッグ
問題形式で学ぶ
- begin/rescue/ensure
- 独自例外の作り方
- デバッグの基本（binding.pry）

## Phase 2: Rails の基礎（5-7日）

### Day 6-7: ActiveRecord の深い理解
- CRUD操作
- Association（has_many, belongs_to, has_one）
- Validation
- Callback

### Day 8-9: クエリとパフォーマンス
- where, find, find_by の違い
- N+1問題と includes
- joins vs includes
- scope の使い方

### Day 10-11: コントローラーとルーティング
- Strong Parameters
- before_action
- RESTful設計
- ネストしたルーティング

### Day 12: ビューとヘルパー
- パーシャル
- ヘルパーメソッド
- form_with の使い方

## Phase 3: Rails の設計パターン（3-5日）

### Day 13: サービスオブジェクト ✅ 今日触れた
- いつ使うか
- 実践パターン

### Day 14: Form Object
- 複雑なフォームの扱い

### Day 15: Query Object
- 複雑なクエリの整理

### Day 16: Decorator/Presenter
- ビューロジックの分離

### Day 17: Concern
- コードの再利用

## 学習の進め方
1. 各Dayのフォルダ内にREADME.mdで学習内容を記録
2. 実装したコードをコミット
3. 学んだことをまとめる
4. 必要に応じてIssueで課題管理
