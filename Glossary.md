# 訳語集 (Glossary)

ENISA プレイブック日本語翻訳版（非公認翻訳：原文 CC BY）で使用する訳語の統一表です。
この訳語表はあくまで参考であり、厳密に合致させているものではありません。

## 見出し・定型語

| 原文 | 訳語 | 備考 |
|---|---|---|
| Principle | 原則 | |
| Objective | 目的 | |
| Checklist | チェックリスト | |
| Minimum evidence | 最低限の証跡 | |
| Release gate | リリースゲート | |
| secure by design | セキュア・バイ・デザイン | 初出時は「セキュア・バイ・デザイン / secure by design」と併記 |

## 用語

| 原文 | 訳語 | 備考 |
|---|---|---|
| trust boundary | 信頼境界 | |
| threat modelling | 脅威モデリング | 英綴り modelling に対応 |
| threat model | 脅威モデル | |
| privileged path | 特権パス | |
| critical asset | 重要資産 | |
| entry point | 入口 | |
| data flow | データフロー | |
| mitigation | 緩和策 | |
| secure defaults | セキュアなデフォルト | |
| deny by default / default-deny | デフォルト拒否 | |
| allow list | 許可リスト | |
| negative test | ネガティブテスト | 認可されていない操作が失敗することを確認するテスト |
| verification | 検証 | |
| refresh trigger | 見直しのトリガー | |
| exception | 例外 | |
| least privilege | 最小権限 | |
| blast radius | 被害範囲 | 初出時は原文併記 |
| lateral movement | ラテラルムーブメント（横展開） | 初出時は原文併記 |
| permission creep | 権限の肥大化 | 初出時は原文併記 |
| privilege hygiene | 権限の衛生管理 | |
| JIT (just-in-time) | JIT（ジャストインタイム） | 時間を限定した権限昇格 |
| break-glass | ブレークグラス（緊急用アクセス） | |
| attribution | 帰属の明確化 | 操作者を特定できること |
| elevation | 権限昇格 | |
| named account | 記名アカウント | |
| shared admin | 共有の管理者アカウント | |
| service account | サービスアカウント | |
| workload identity | ワークロードアイデンティティ | |
| IAM inventory | IAM のインベントリ | |
| identity | アイデンティティ | |
| authoritative identity source | 信頼できるアイデンティティソース | 初出時は原文併記 |
| single source of truth | 唯一の正 | |
| actor | 主体 | |
| authentication (authn) | 認証 | |
| authorisation (authz) | 認可 | 英綴り authorisation に対応 |
| MFA | MFA | 多要素認証 (multi-factor authentication) |
| device binding | デバイスバインディング | |
| cryptographic credentials | 暗号的な認証情報 | |
| session | セッション | |
| credential | 認証情報 | |
| rotate / revoke / expire | ローテーション／失効／期限切れ | |
| compensating controls | 補完的対策 | |
| man-in-the-middle attack | 中間者攻撃 | |
| replay | リプレイ | |
| injection | 注入 | |
| tampering | 改ざん | |
| account takeover | アカウント乗っ取り | |
| impersonation | なりすまし | |
| OTA (over-the-air) | OTA | アップデートチャネルの文脈で使用 |
| PII | PII（個人を特定できる情報） | |
| tenant | テナント | |
| segmentation | セグメンテーション | |
| rate limit | レート制限 | |
| signed updates | 署名付きアップデート | |
| attack surface | 攻撃対象領域（アタックサーフェス） | 初出時は原文併記 |
| minimisation | 最小化 | 英綴り minimisation に対応 |
| exposure inventory | 露出のインベントリ | |
| HMI (human-machine interface) | HMI（ヒューマンマシンインターフェース） | |
| debugger | デバッガ | |
| diagnostic | 診断用 | |
| dependency | 依存関係 | |
| legacy | レガシー | |
| deprecated | 非推奨 | |
| artefact | 成果物（アーティファクト） | 本番ビルドの成果物を指す。英綴り artefact に対応 |
| authenticity and integrity | 真正性と完全性 | |
| data retention | データ保持 | |
| defence in depth | 多層防御 | 英綴り defence に対応 |
| containment | 封じ込め | |
| detection | 検知 | |
| alert | アラート | |
| independent controls | 独立した対策 | |
| enforcement point | 強制ポイント | |
| single point of failure | 単一障害点 | |
| step-up authentication | ステップアップ認証 | |
| staged access | 段階的なアクセス | |
| freshness | 鮮度 | 完全性 (integrity) と併記される文脈 |
| integrity | 完全性 | |
| transport security | トランスポートセキュリティ | |
| playbook | プレイブック | |
| open design | オープン設計 | |
| security through obscurity | 隠蔽によるセキュリティ | 初出時は原文併記 |
| security design note | セキュリティ設計ノート | |
| open standards | オープンスタンダード | |
| proprietary crypto | 独自仕様の暗号 | |
| secure configuration guide | セキュアな構成ガイド | |
| hardening | ハードニング | |
| vulnerability disclosure | 脆弱性の開示 | |
| triage | トリアージ | |
| peer review | ピアレビュー | |
| SBOM | SBOM | ソフトウェア部品表 (Software Bill of Materials) |
| CODEOWNERS | CODEOWNERS | ファイル名のため訳さない |
| changelog | 変更履歴 | |
| life cycle | ライフサイクル | |
| end of sale / end of support / end of life | 販売終了／サポート終了／ライフ終了 | end of life は初出時に原文併記 |
| support window | サポート期間 | |
| patch SLA | パッチ SLA | |
| transactional update | トランザクション的なアップデート | |
| rollback | ロールバック | |
| recovery | 復旧 | |
| brick (devices) | 文鎮化（brick） | 初出時は原文併記 |
| fallback | フォールバック | |
| residual risk | 残存リスク | |
| root-cause analysis | 根本原因分析 | |
| telemetry | テレメトリ | |
| pseudonymised | 仮名化した | 英綴り pseudonymised に対応 |
| decommissioning | 廃止 | |
| factory reset | 工場出荷時リセット | |
| deprovisioning | デプロビジョニング | |
| SPDX / CycloneDX | SPDX／CycloneDX | 標準形式名のため訳さない |
| user-centric design | ユーザー中心設計 | |
| usability | ユーザビリティ | |
| onboarding | オンボーディング | |
| remediation | 是正 | |
| role-based access | ロールベースのアクセス | |
| workaround | 回避策 | |
| secure coding | セキュアコーディング | |
| coding baseline | コーディングのベースライン | |
| weakness class / vulnerability class | 脆弱性クラス | |
| by construction | 構造的に | |
| memory-safe language | メモリ安全な言語 | |
| parameterised | パラメータ化された | 英綴り parameterised に対応 |
| SQL injection | SQL インジェクション | |
| cross-site scripting | クロスサイトスクリプティング | |
| output encoding | 出力エンコーディング | |
| input validation | 入力の検証 | |
| deserialisation | デシリアライズ | 英綴り deserialisation に対応 |
| banned pattern | 禁止パターン | |
| secret | シークレット | API キー、トークン等 |
| pin (dependencies) | ピン留めする | |
| protected branch | 保護されたブランチ | |
| force push | 強制プッシュ | 初出時は原文併記 |
| CI/CD | CI/CD | |
| SAST | SAST | 静的アプリケーションセキュリティテスト |
| fuzzing | ファジング | |
| property-based testing | プロパティベーステスト | |
| AI-generated code | AI が生成したコード | |
| logging | ログ記録 | |
| monitoring | 監視 | |
| must-log | 必ず記録する (must-log) | 初出時は原文併記 |
| audit log | 監査ログ | |
| SIEM | SIEM | |
| NTP / time sync | 時刻同期 (NTP) | |
| retention | 保持 | |
| brute force | ブルートフォース | |
| suppression window | 抑制ウィンドウ | |
| alert catalogue | アラートのカタログ | |
| on-call | オンコール | |
| runbook | ランブック | |
| tabletop exercise | 机上演習 | 初出時は原文併記 |
| dry run | ドライラン | |
| configuration management | 構成管理 | |
| change management | 変更管理 | |
| configuration drift / silent drift | ドリフト／サイレントドリフト | |
| baseline | ベースライン | |
| infrastructure as code (IaC) | コードとしてのインフラ (IaC) | |
| change gating | 変更のゲート制御 | |
| linting | リンティング | |
| change log | 変更履歴 | |
| secure by default | セキュア・バイ・デフォルト | 初出時は「セキュア・バイ・デフォルト / secure by default」と併記 |
| incident response (IR) | インシデント対応 (IR) | |
| incident lead | インシデントリーダー | |
| escalation | エスカレーション | |
| decision authority | 意思決定権限 | |
| eradicate | 根絶 | インシデント対応の手順名 |
| lessons learned | 教訓の抽出 | 初出時は原文併記 |
| near miss | ニアミス | |
| immutability | 不変性 | 初出時は原文併記 |
| backup / restore | バックアップ／復元 | |
| RTO / RPO | RTO／RPO | |
| ransomware | ランサムウェア | |
| quarantine | 隔離 | |
| device fleet | デバイス群 | |
| DAST | DAST | 動的アプリケーションセキュリティテスト |
| advisory | アドバイザリ | |
| CSAF | CSAF | 標準名のため訳さない |
| VEX | VEX | 標準名のため訳さない |
| transitive dependency | 推移的依存関係 | 初出時は原文併記 |
| risk register | リスク登録簿 | 初出時は原文併記 |
| regulatory reporting obligation | 規制上の報告義務 | |
| intake | 受付 | |
| known exploited | 悪用が確認されている | 初出時は原文併記 |
| regression | リグレッション | |
| supply chain | サプライチェーン | |
| supplier | サプライヤー | |
| due diligence | デューデリジェンス | |
| VDP (vulnerability disclosure policy) | VDP | 脆弱性開示ポリシー |
| OWASP SCVS | OWASP SCVS | 名称のため訳さない |
| SLSA | SLSA | 名称のため訳さない |
| provenance | 来歴 | 初出時は原文併記 |
| lock file | ロックファイル | |
| registry | レジストリ | |
| ephemeral build environment | 一時的なビルド環境 | 初出時は原文併記 |
| hermetic build | ハーメティックビルド | 初出時は原文併記 |
| AI/ML model | AI/ML モデル | |
| core functionality | 中核機能 | |
| opt-in | オプトイン | |
| default credentials | デフォルトの認証情報 | |
| hard-coded | ハードコードされた | |
| first boot | 初回起動 | |
| provisioning | プロビジョニング | |
| restrictive initial access | 制限的な初期アクセス | |
| plain-text protocol | 平文のプロトコル | |
| encryption | 暗号化 | |
| cipher | 暗号スイート | |
| downgrade | ダウングレード | |
| fail securely | 安全に失敗する | |
| mutual authentication | 相互認証 | |
| end-to-end | エンドツーエンド | |
| trust anchor | トラストアンカー | 初出時は原文併記 |
| post-quantum cryptography | ポスト量子暗号 | |
| key pair | 鍵ペア | |
| certificate | 証明書 | |
| secure storage | セキュアストレージ | |
| hardware-backed | ハードウェアに裏付けられた | |
| extraction (of secrets) | 抽出 | |
| revocation | 失効 | |
| staged rollout | 段階的な展開 | |
| maintenance window | メンテナンスウィンドウ | |
| unattended installation | 無人でのインストール | |
| security posture | セキュリティ態勢 | 初出時は原文併記 |
| degraded state | 劣化した状態 | |
| secure baseline | セキュアなベースライン | |
| account recovery | アカウントの復旧 | |
| ownership transfer | オーナーシップ移転 | |
| social engineering | ソーシャルエンジニアリング | |
| Architectural Foundations | アーキテクチャの基盤 | index.md の見出し |
| Operational Integrity | 運用の完全性 | index.md の見出し |
| Default Hardening | デフォルトのハードニング | index.md の見出し |
| Guided Protection | ガイド付きの保護 | index.md の見出し |
| SME (small and medium-sized enterprise) | 中小企業 (SME) | |
| CRA (Cyber Resilience Act) | サイバーレジリエンス法 (CRA) | |
| product with digital elements | デジタル要素を含む製品 | |
| progressive adoption | 段階的な導入 | |
| residual risk (acceptable level of) | 許容可能な残存リスク | |
| integrator | インテグレーター | |
| manufacturer | 製造者 | |

## 翻訳方針

- markdown の構成（見出し、リスト、チェックボックス）は原文のまま維持する。
- 翻訳が難しい語はカタカナまたは英単語のままとし、必要に応じて日本語の後に括弧書きで原文を併記する。
- ENISA の名称は「欧州連合サイバーセキュリティ局」とする。
- 各ファイルの冒頭に、翻訳版である旨、CC BY であること、ENISA 非公認であることを明記する。
