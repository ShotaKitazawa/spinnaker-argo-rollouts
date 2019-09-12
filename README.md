# これはなに？

Spinnaker から Argo-Rollouts の Rollout リソースを CD することで、 Blue-Green Deployment + 切り替え前の正常性テスト を行うための検証用リポジトリ

# ディレクトリ構成

## argo-rollouts/

Argo Rollouts 自体を管理するディレクトリ。Argo Rolloutsのバージョンアップは当ディレクトリの argo-rollouts.yaml を更新

## app/

Application を管理するディレクトリ

## shared/

共有リソースのディレクトリ
