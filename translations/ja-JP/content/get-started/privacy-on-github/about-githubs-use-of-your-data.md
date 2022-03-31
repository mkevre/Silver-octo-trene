---
title: GitHubによるユーザのデータの利用について
redirect_from:
  - /articles/about-github-s-use-of-your-data
  - /articles/about-githubs-use-of-your-data
  - /github/understanding-how-github-uses-and-protects-your-data/about-githubs-use-of-your-data
intro: '{% data variables.product.product_name %}はユーザのリポジトリのデータを使い、ユーザを関連するツール、人々、プロジェクト、情報につなげます。'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Policy
  - Legal
shortTitle: GitHub's use of your data
---

## {% data variables.product.product_name %} によるユーザのデータの利用について

{% data variables.product.product_name %}は、プロダクト内の一般化された知見を配信するために、メタデータを集約し、コンテンツのパターンをパースします。 It uses data from public repositories, and also uses metadata and aggregate data from private repositories when a repository's owner has chosen to share the data with {% data variables.product.product_name %} by enabling the dependency graph. If you enable the dependency graph for a private repository, then {% data variables.product.product_name %} will perform read-only analysis of that specific private repository.

If you enable data use for a private repository, we will continue to treat your private data, source code, or trade secrets as confidential and private consistent with our [Terms of Service](/free-pro-team@latest/github/site-policy/github-terms-of-service). 弊社が知る情報は、集約されたデータからのみです。 詳しい情報については、「[プライベートリポジトリのデータ使用を管理する](/get-started/privacy-on-github/managing-data-use-settings-for-your-private-repository)」を参照してください。

{% data reusables.repositories.about-github-archive-program %} 詳細は「[{% data variables.product.prodname_dotcom %} 上のコンテンツとデータのアーカイブ処理について](/github/creating-cloning-and-archiving-repositories/about-archiving-content-and-data-on-github#about-the-github-archive-program)」を参照してください。

{% data reusables.user-settings.export-data %}詳細は「[個人アカウントのデータのアーカイブをリクエストする](/articles/requesting-an-archive-of-your-personal-account-s-data)」を参照してください。

メタデータあるいは集約されたデータを使う大きな新機能は、[{% data variables.product.prodname_dotcom %}blog](https://github.com/blog)でアナウンスします。

## データによるセキュリティの推奨事項の改善

データの利用方法の例として、パブリックリポジトリの依存対象のセキュリティの脆弱性を検出し、アラートを出すことができます。 詳しい情報については、「[{% data variables.product.prodname_dependabot_alerts %} について](/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)」を参照してください。

潜在的なセキュリティの脆弱性を検出するために、{% data variables.product.product_name %}は依存対象のマニフェストファイルの内容をスキャンし、プロジェクトの依存対象のリストを作成します。

{% data variables.product.product_name %}はまた、依存対象のマニフェストに加えられた変更についても知ります。 たとえばあなたが脆弱性のある依存対象をセキュリティアラートを受けた後で安全なバージョンにアップグレードして、他者も同じようにした場合、{% data variables.product.product_name %}はその脆弱性へのパッチの方法を学習し、影響を受けるリポジトリに同じパッチを推奨できます。

## プライバシーとデータ共有

プライベートリポジトリのデータはマシンによってスキャンされ、{% data variables.product.product_name %}のスタッフが読むことは決してありません。 弊社の[利用規約](/free-pro-team@latest/github/site-policy/github-terms-of-service#3-access)に記載されている場合を除き、人の眼はプライベートリポジトリの内容を見ることはありません。

あなたの個人データあるいはリポジトリデータがサードパーティと共有されることはありません。 弊社は、分析から得られた集約データをパートナーと共有することがあります。