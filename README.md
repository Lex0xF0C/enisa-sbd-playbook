> **【非公式の日本語翻訳版です】**
> このリポジトリは、ENISA（欧州連合サイバーセキュリティ局）が公開した下記の文書に基づくプレイブック集（原文: 英語）の、**非公式の日本語翻訳版**を掲載しています。
> - 原典: [*ENISA Secure by Design and Default Playbook: A Practical Guide to Secure by Design and Default Principles for SMEs*](https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA_Secure_By_Design_and_Default_Playbook_v1.pdf)（ENISA セキュア・バイ・デザイン／デフォルト プレイブック: 中小企業向けセキュア・バイ・デザイン／デフォルトの原則に関する実践ガイド）
> - 原文は CC BY ライセンスで提供されており、本翻訳版も同ライセンスの下で提供します。原文からの変更点は、日本語への翻訳（および本注記の追加）です。
> - 本翻訳版は ENISA が作成・承認・推奨したものではなく、**ENISA 非公認**の翻訳です。翻訳の正確性について、ENISA は一切関与していません。
> - 解釈に疑義がある場合は、必ず英語の原文を参照してください。
> - [目次（Index）](/index/index.md)
> - 翻訳：[Lex0xF0C](https://lex0xf0c.github.io/)
> - [『ENISA Secure by Design and Default Playbook: A Practical Guide to Secure by Design and Default Principles for SMEs』（日本語訳版）](ENISA-Secure-by-Design-and-Default-Playbook-ja.md)

# ENISA セキュア・バイ・デザイン／デフォルト プレイブック (ENISA Secure by Design and Default Playbooks)

中小企業 (SME) 向けの、セキュア・バイ・デザインおよびセキュア・バイ・デフォルトの22のプレイブックからなる実践的なコレクションです。*[ENISA セキュア・バイ・デザイン／デフォルト プレイブック: 中小企業向けセキュア・バイ・デザイン／デフォルトの原則に関する実践ガイド](https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA_Secure_By_Design_and_Default_Playbook_v1.pdf)* に基づいています。


## 概要 (About)

セキュア・バイ・デザインは、製品セキュリティにおける根本的な転換を意味します。開発後に保護措置を後付けするのではなく、構想の段階から組み込みます。セキュア・バイ・デフォルトは、製品が合理的に可能な限り最も安全な構成で出荷されることを確保し、ユーザーの専門知識への依存を減らし、設定ミスの可能性を抑えます。

このリポジトリは、セキュリティ原則という理想と、中小企業の制約の中での実践との間のギャップを埋めることを目指す、プレイブックの一覧を提供します。開発チームが、設計、構築、デプロイ、保守、廃止の各段階で適用できる、構造化され、わかりやすいチェックリストを提供します。

本ガイダンスは、網羅的または規範的な実装フレームワークではなく、実践的な出発点として意図されています。その適用は、製品の意図された用途、文脈、関連するリスク、および適用される要件に合わせて調整すべきです。本ガイダンスは、法的な助言を提供するものではありません。

## プレイブックの構成 (Playbook structure)

各プレイブックは、次の項目で構成されます。

- 原則 (Principle)
- 目的 (Objective)
- チェックリスト (Checklist)
- 最低限の証跡 (Minimum evidence)
- リリースゲート (Release gate)

## プレイブック一覧 (Playbooks)


### セキュア・バイ・デザイン (Secure by Design)
セキュア・バイ・デザインは、開発の段階で製品に保護措置を組み込み、後から追加することはしません。
- **アーキテクチャの基盤 (Architectural Foundations)** — 製品を本質的に侵害や悪用が困難なものにする、構造上の設計上の選択。
- **運用の完全性 (Operational Integrity)** — 開発、デプロイ、運用、廃止を通じて製品のセキュリティを維持する、人と手続きの実践。

| アーキテクチャの基盤 | 運用の完全性 |
|---|---|
| • [信頼境界と脅威モデリング](playbooks/01-trust-boundaries-and-threat-modelling.md)<br>• [最小権限](playbooks/02-least-privilege.md)<br>• [強固なアイデンティティと認証のアーキテクチャ](playbooks/03-strong-identity-and-authentication-architecture.md)<br>• [攻撃対象領域の最小化](playbooks/04-attack-surface-minimisation.md)<br>• [多層防御](playbooks/05-defence-in-depth.md)<br>• [オープン設計](playbooks/06-open-design.md) | • [ライフサイクル管理](playbooks/07-life-cycle-management.md)<br>• [ユーザー中心設計](playbooks/08-user-centric-design.md)<br>• [セキュアコーディングと検証の実践](playbooks/09-secure-coding-and-verification-practices.md)<br>• [ログ記録、監視、アラート](playbooks/10-logging-monitoring-and-alerting.md)<br>• [構成管理と変更管理](playbooks/11-configuration-and-change-management.md)<br>• [インシデント対応と復旧](playbooks/12-incident-response-and-recovery.md)<br>• [脆弱性管理とパッチ管理](playbooks/13-vulnerability-and-patch-management.md)<br>• [サプライチェーンの管理策](playbooks/14-supply-chain-controls.md) |

### セキュア・バイ・デフォルト (Secure by Default)

セキュア・バイ・デフォルトは、製品が合理的に可能な限り最も安全な構成で出荷されることを確保します。

- **デフォルトのハードニング (Default Hardening)** — ソフトウェアの工場出荷時の状態であり、初期構成が可能な限り制限的であることを確保するもの。
- **ガイド付きの保護 (Guided Protection)** — ユーザーが安全な状態を維持できるようにする、必須のセットアップ手順、自動化、明確なフィードバック。

| デフォルトのハードニング | ガイド付きの保護 |
|---|---|
| • [デフォルトサービスの最小化](playbooks/15-minimisation-of-default-services.md)<br>• [制限的な初期アクセス](playbooks/16-restrictive-initial-access.md)<br>• [デフォルトでのセキュアな通信](playbooks/17-secure-communication-by-default.md)<br>• [デフォルトでの一意のデバイスアイデンティティとシークレット](playbooks/18-unique-device-identity-and-secrets-by-default.md) | • [必須のセキュリティオンボーディング](playbooks/19-mandatory-security-onboarding.md)<br>• [自動化された保守とアップデート](playbooks/20-automated-maintenance-and-updates.md)<br>• [透明性のあるセキュリティ態勢](playbooks/21-transparent-security-posture.md)<br>• [セキュアな復旧とオーナーシップのライフサイクル](playbooks/22-secure-recovery-and-ownership-life-cycle.md) |


### プレイブックの相互関係 (How the playbooks fit together)

図1は、製品のライフサイクル、セキュア・バイ・デザインおよびセキュア・バイ・デフォルトの原則、リスク管理活動の間の関係を示しています。

リスク管理活動は、重要な考慮事項（何を保護する必要があるか、懸念される脅威、製品の意図された目的とセキュリティへの影響を踏まえた許容可能な残存リスクの水準など）を明確にすることで、セキュリティの文脈を確立します。セキュア・バイ・デザインとセキュア・バイ・デフォルトの原則は、この文脈を実践的なセキュリティ上の判断に落とし込み、要件定義からライフ終了 (end of life) に至るまで、製品のライフサイクルの各プロセスを通じて適用されます。

![製品のライフサイクル全体にわたるセキュア・バイ・デザインとセキュア・バイ・デフォルト](assets/images/figure-1.png)

*図1: 製品のライフサイクル全体にわたるセキュア・バイ・デザインとセキュア・バイ・デフォルト（図中の文言は原文のとおり英語です）。*

## 段階的な導入 (Progressive adoption)

プレイブックは、文脈と優先順位付けから始め、続いて適切なエンジニアリングのベースラインを確立し、その後により広範な実装へと進む形で、段階的に導入できます。ここでいう段階的な導入とは、組織が時間をかけてセキュリティのプラクティスを構築し、強化していく方法を指します。これは、特にサイバーレジリエンス法 (CRA) に基づくものを含む法的義務から生じる、適用される要件や管理策の実施を遅らせることを意味するものではありません。本ガイダンスは、そうした義務を妨げるものではなく、それらの義務が優先されます。

| 段階 | プレイブックの例 | 重点 |
|---|---|---|
| **1. 文脈と優先事項を確立する** | • [信頼境界と脅威モデリング](playbooks/01-trust-boundaries-and-threat-modelling.md) | 製品の文脈、リスク管理、脅威モデリングを用いて、最も関連性の高い脅威、信頼境界、セキュリティ目標を特定します。これが、残りのプレイブックの優先順位付けと範囲を導きます。 |
| **2. 基礎的なエンジニアリングのベースラインを確立する** | • [セキュアコーディングと検証の実践](playbooks/09-secure-coding-and-verification-practices.md)<br>• [ログ記録、監視、アラート](playbooks/10-logging-monitoring-and-alerting.md)<br>• [脆弱性管理とパッチ管理](playbooks/13-vulnerability-and-patch-management.md)<br>• [サプライチェーンの管理策](playbooks/14-supply-chain-controls.md)<br>• [制限的な初期アクセス](playbooks/16-restrictive-initial-access.md)<br>• [デフォルトでのセキュアな通信](playbooks/17-secure-communication-by-default.md)<br>• [デフォルトでの一意のデバイスアイデンティティとシークレット](playbooks/18-unique-device-identity-and-secrets-by-default.md)<br>• [自動化された保守とアップデート](playbooks/20-automated-maintenance-and-updates.md) | 製品の文脈、セキュリティ目標、特定されたリスクと脅威に基づいて、ベースラインを確立します。中核となるエンジニアリング上の管理策を、製品に関連するセキュア・バイ・デフォルトのプレイブックで補完します。製品の文脈や特定されたリスクと脅威に対処するために必要な場合は、その他のプレイブックも優先すべきです。 |
| **3. 実装を拡大し、強化する** | • 残りの該当するプレイブック | 製品の文脈、意図された用途、デプロイの文脈、特定されたリスクと脅威に応じて、残りの該当するプレイブックを実装し、優先順位を付けます。時間をかけて、カバレッジ、一貫性、自動化を高め、関連する指標を用いて進捗を評価します。 |

製品によっては、基礎的な段階で他のプレイブックを実装する必要がある場合があります。例えば、可用性が重視される製品では、[インシデント対応と復旧](playbooks/12-incident-response-and-recovery.md)を早期に実装する必要があるかもしれません。また、リセット、オーナーシップの移転、または廃止をサポートする製品では、[セキュアな復旧とオーナーシップのライフサイクル](playbooks/22-secure-recovery-and-ownership-life-cycle.md)が必要になるかもしれません。

段階的な導入は、個々のプレイブックの内部にも適用できます。組織は、優先度の高いリスクと適用される要件に対処するチェックリスト項目から始め、時間をかけてカバレッジ、証跡、自動化を強化していくことができます。

この順序は例示です。後の段階で取り組むプレイブックが本質的に重要性が低いわけではなく、適用されるセキュリティ上または規制上の要件を先送りしてはなりません。

## 想定する読者 (Intended audience)

本ガイダンスは、次の方々を対象としています。

- ソフトウェア開発者およびエンジニア
- 技術系のプロダクトマネージャー
- 中小企業のセキュリティ責任者
- システムアーキテクト

特に、デジタル要素を含む製品を開発する中小企業の製造者に関連性があります。

## 期待される成果 (Intended outcomes)

これらのプレイブックの適用は、次の事項に寄与することを意図しています。

- 繰り返し発生する、防止可能な脆弱性の減少
- より安全なデフォルト構成と、不必要な露出の低減を備えた製品の提供
- セキュリティリスクのより早期の特定と対処
- 依存関係、ビルドプロセス、リリース、アップデートの可視性と保護の強化
- 脆弱性のより迅速な検知、是正、伝達
- 製品のライフサイクル全体を通じた、サイバーセキュリティインシデントの発生可能性と影響の低減

これらの成果は、より安全でレジリエントな製品を通じて、ユーザーと運用者に利益をもたらします。製造者は、より一貫したセキュリティ上の判断を通じて、顧客とインテグレーターは、より明確で追跡可能なセキュリティ証跡を通じて、それぞれ利益を得られます。
