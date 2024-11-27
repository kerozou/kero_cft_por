# kero_cft_por
- cloudfront + s3 + html/css で簡単な自己紹介ページを用意できるテンプレートです
- AWS CDK v2 を用いて半自動でリソースを構築できます
  - 証明書の管理、S3にアップロードするresourceファイルなどに関しては一部コンソール操作等で手動制御する必要があります

## 詳細なドキュメント
- [frontend/resourcesの詳細](frontend/resources/README.md)
- [リソースデプロイ操作の詳細](infra/CDK/README.md)
- [データupload用Scriptの詳細](infra/Scripts/README.md)