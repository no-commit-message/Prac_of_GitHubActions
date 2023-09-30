# GitHubActionsの勉強
GitHubActionsでCI/CDパイプラインを構築する練習としてプロジェクトを作成しました

# 使用技術
- 開発環境: DevContainer with Docker
- バックエンド: Django
- フロントエンド: Django Template Language(DTL), Tailwind CSS
- デプロイ先: AWS EC2 t2.micro　**(本当はVPCの中にサブネット立てて、SSL証明書をアタッチしたELBからEC2に繋ぐように構築したいのですが、お金がかかるので今回はやりません涙)**
- CI/CD: GitHubActions (今回の本命)
![画像](https://www.kagoya.jp/howto/wp-content/uploads/githubactions.png)