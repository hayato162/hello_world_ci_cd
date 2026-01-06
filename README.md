# hello_world_ci_cd
.github/workflowsを作成し、その配下にymlファイルを作成することで、ワークフローを作成することができる

# Organizationとは
共同作業を行うためのコンテナ
Team, Repository, Projectがある

## Organizationsの作成
Git Hubの画面から新たに作成する
h-yamada-ci-cd-organization
https://github.com/h-yamada-ci-cd-organization

# Teamとは
Organizationに所属するメンバーをまとめる単位

## チームに対する操作権限
- Maintainer：
    チームに対する追加・削除権限がある
- Member：
    一般ユーザー

# Projectとは
- プロジェクトを最新の状態に保つ仕組み
    - Issue, Draft Issue, Pull Requestを一元管理する
- タスクへのメタデータ追加
    - イテレーション（設計→開発→テスト→改善という一連の工程を短期間で繰り返す反復単位のこと）
    - タスクの大きさ、優先度
- さまざまなビューからプロジェクトを確認
    - テーブルビュー、ボードビュー
    - フィルター
    - グルーピング

## Projectに対する操作権限
- Admin
- Write
- Read

# Taskとは
Issue, Draft Issue, Pull RequestのそれぞれがTask
作成、編集、一覧表示、削除ができる

