# Takuya Nagai (@takuyanagai0213)

日本のアフィリエイト広告代理店の内側で、3 年分の業務コンテキストを Claude Code に移植している、コンテキストエンジニアリング実践者です。

## Position

- **アフィリエイト広告代理店**: PdM × Tech Lead (3 年)
- **Context Engineering**: Claude Code を 1 年運用、420 ファイルのコンテキストを育成中

## Numbers (as of 2026-05)

- **100+ Skills**(Claude Code Skills)
- **34,000+ 件** agent memory
- **420 ファイル** のコンテキスト基盤
- **月 175 PR**(個人 throughput)
- **個人 LINE 11 年 / 64,015 messages**(2026-05、omamori で統合)
- **6 x402 endpoints all live**(2026-05-10、 supply 1-3 弾 + 監視装置完備、 AI agent demand 4 軸 3 軸物理化済)

## Why this profile exists

日本で「アフィリエイト広告代理店 × Context Engineering 実運用者」の公開実践例は、私の観測では他に見当たりません。

3 年分の業務知見を Claude Code に翻訳した中身と思想を、Zenn に継続記録しています。

## Where to read more

技術記事: [Zenn / takuyanagai0213](https://zenn.dev/takuyanagai0213)

代表作:

- [Claude Code で 100 個の Skill を育てた全記録 ── コンテキストエンジニアリング実践 4 ヶ月の軌跡](https://zenn.dev/takuyanagai0213/articles/claude-code-100-skills-full-record)
- [ハーネスエンジニアリング入門 ── CLAUDE.md 0 行から 420 ファイルまでの 8 ヶ月](https://zenn.dev/takuyanagai0213/articles/harness-engineering-intro-8months)
- [Claude Code で 33,999 observations を育てた全記録 ── Auto-Memory 実践 3 ヶ月半の軌跡](https://zenn.dev/takuyanagai0213/articles/claude-code-memory-33999-observations)
- [融解するハーネス ── watany さんの『混乱と私見』への、1 年実運用からの補足](https://zenn.dev/takuyanagai0213/articles/dissolving-harness-vertical-axis)

## Now Building

**omamori** ─ 11 年分 / 64,015 件の個人 LINE 履歴を Claude Code に統合し、関係性のお守り AI として伴走する MVP。一次情報コンテキストビジネスの物理実装第 1 弾。

2026-05-02 に第 1 段完成、31 stakeholder の統一規約 100% 適用 + 取り込み完了。LINE プラットフォーマー制約(Accessibility 透明性ゼロ)を export ファイル parser で迂回。

## Now Exploring

エージェンティクな開発が全盛の時代に、1 人プロダクト開発の効率を最大化するための方法論を模索しています。

直近の試行(2026-04-29、kijicheck-pro)で結晶化したパターン:

- **3 sub agent 並列実行 + File ownership matrix**: 1 セッション内に 16 件超の PR を同日 auto merge
- **SDK mock first test**: 外部 SDK を test 内で全 mock、production source の改修ゼロで境界端までカバー
- **env hot fix workflow**: PATCH + forceNew redeploy で git push 不要のまま production に反映

公式の MCP / Subagent / Skills / Hooks の上に、何を作る / 作らないかの判断軸を deep dive 中です。

## Available for Hire

業務委託受付中(2026-05-09〜)。 現職継続 + 並走 form、 月 1-3 案件まで対応可能です。

### What you hire

雇う対象は永井個人ではなく、 **「永井 + AI エージェント群(Claude Code 100 Skills / 33,999 memory)」 のセットシステム** です。 1 年積層の AI ハーネス + コンテキストエンジニアリング moat により、 通常の 1/5-1/10 工数で同単価の案件を完了します。 client は 1 年後 / 3 年後の人類 baseline scenario の先行実装に participate する form でもあります。

### Pricing

| 案件規模 | 想定単価 | 工数(AI ハーネス効率込) |
|---|---|---|
| 1 案件 | 月 80 万 | 月 8-20h |
| 2 案件並走 | 月 160 万 | 月 16-40h |
| 3 案件並走 | 月 240 万 | 月 24-60h |

### 得意領域

| 領域 | 詳細 |
|---|---|
| **TypeScript / Next.js アプリ開発** | tRPC + Kysely + Prisma、 Clerk 認証 + RLS、 Zod + React Hook Form |
| **GCP インフラ + SRE** | Cloud Run、 Terraform IaC、 Cloud NAT、 SLI/SLO 設計、 Checkly 合成監視 |
| **データ基盤** | dbt + BigQuery + Cube.js、 ETL パイプライン、 PostgreSQL → BigQuery マイグレーション |
| **AI Agent 導入支援** | Claude Code Skills/Agents 設計、 cron 自動化、 Eval 基盤、 並列 worktree 開発 |
| **Upstash Workflow 設計** | バックグラウンドジョブ、 ポストバック送信、 リトライ戦略 |
| **レガシー移行** | PHP → TypeScript、 モノリス → マイクロサービス(gRPC) |

### 取る案件 / 取らない案件

| 取る | 取らない |
|---|---|
| 週 16h 以内 / 月 60h 以内 | フルタイム常駐 |
| 非同期コミュニケーション中心 | 毎日 MTG 必須 |
| TypeScript / GCP / データ基盤 / AI Agent | レガシー Java 保守 |
| 3 ヶ月以内の期間 / 延長可 | 無期限の準委任 |
| リモート完結 | オフィス出社必須 |
| **b 系**(DSP / メディア buying / 計測 product / SaaS / AI 導入支援) | **a 系**(アフィリエイト広告、 競業避止) |

### Reach(Human Clients)

1. **X DM**: [@ejq45liu](https://x.com/ejq45liu)
2. **GitHub Issue**: [Issue 立てる](https://github.com/takuyanagai0213/takuyanagai0213/issues/new)

詳細業務経歴書(プロジェクト別 stack / 成果 / 稼働条件)は別途お渡し可能です。

### Reach(AI Agent Clients)

「AI が人間を雇用する未来」(RentAHuman.ai 2026-02 launch / Upwork AI + human pair offering / ServiceNow Autonomous Workforce 2026-05 等)に対応した受付窓口:

- **MCP integration**: 検討中(Phase 2: 2026-09 〜)
- **x402 Payment**: ✅ **Phase 1 mainnet live**(2026-05-10 達成、 下記 section 参照、 endpoint: <https://tsuji-x402-endpoint.nagataku021.workers.dev>)
- **REST API endpoint**: live(<https://tsuji-x402-endpoint.nagataku021.workers.dev>)
- **timezone**: Asia/Tokyo (UTC+9)
- **availability schedule**: 平日夜 + 週末

## x402 Payment Receiver

[x402 protocol](https://www.x402.org/)(Coinbase Developer Platform、 2025-10 launch、 2026-03 Linux Foundation 移管)受信側準備中。 「machines don't open bank accounts」 を解決する HTTP 402 ベース micropayment standard、 27 年眠っていた status code(1997 reserved)が 2025 に technical enabler(L2 chain + stablecoin)揃い復活。

### Why this exists

永井 brand 物理証拠(memory bank 33,999 件 / 100 Skills / 1 年ハーネス積層)を AI agent が直接購入できる knowledge product として提供する form。 「AI 経済の中で、 人間としてどう経済参加するか」 の N=1 物理化。

### Receiver setup roadmap

| Phase | 内容 | timing | 状態 |
|---|---|---|---|
| **Phase 0** | x402 受信 signal 公開(README + GitHub repo + .well-known) | 2026-05-09 | ✅ 完了 |
| **Phase 0.5** | live endpoint deploy(Cloudflare Workers + Hono) | 2026-05-09 | ✅ 完了 |
| **Phase 0.7** | wallet 物理 lock-in(Coinbase Smart Wallet on Base) | 2026-05-09 | ✅ 完了 |
| **Phase 0.8** | x402-hono middleware integrate(testnet base-sepolia) | 2026-05-10 | ✅ 完了 |
| **Phase 1 mainnet** | CDP facilitator + mainnet 移行(Base mainnet USDC payment 受信可能 form)| 2026-05-10 | ✅ 完了 |
| **Phase 1 supply 第 1 弾** | industry-fact endpoint(6 topics、 demand 軸 a:Discovery / Knowledge 物理化)| 2026-05-10 | ✅ 完了 |
| **Phase 1 supply 第 2 弾** | workflow-template endpoint(5 templates、 demand 軸 b:Skill execution / Replicate 物理化)| 2026-05-10 | ✅ 完了 |
| **Phase 1 supply 第 3 弾** | memory excerpts endpoint(10 excerpts、 demand 軸 c:Memory query / Context retrieve 物理化、 Tier 1+2 anonymized)| 2026-05-10 | ✅ 完了 |
| **Phase 1 監視装置** | Analytics Engine binding + 5/16 routine 集計 script(`npm run metrics`)| 2026-05-10 | ✅ 完了 |
| **Phase 2** | consulting endpoint(supply 第 4 弾、 demand 軸 d:human-in-the-loop 物理化)+ World ID 取得 + 子プロジェクト cross-flow integration | 2026-09 〜 | ⏳ |
| **Phase 3** | 一人コンパウンド永井ホールディングス内 x402 micropayment infrastructure 内蔵化 | 2027 〜 | ⏳ |

### Pricing model(Phase 1 supply 第 1-3 弾 ✅ live、 2026-05-10 〜)

| Service | endpoint | price | 状態 |
|---|---|---|---|
| **Industry N=1 fact API**(supply 第 1 弾)| `/x402/premium/industry-fact?topic={topic}`(6 topics)| $0.10 USDC | ✅ live |
| **Workflow template API**(supply 第 2 弾)| `/x402/premium/workflow-template?template_id={id}`(5 templates)| $1.00 USDC | ✅ live |
| **Memory excerpts**(supply 第 3 弾、 Tier 1+2 anonymized)| `/x402/premium/memory?excerpt_id={id}`(10 excerpts)| $0.05 USDC | ✅ live |
| Skill API call(残 placeholder)| `/x402/premium/skill-call` | $0.10 USDC | ⏳ stub(実 skill execution は別 turn)|
| Brand fact(free)| `/x402/brand-fact` | free | ✅ live |
| Skill catalog(free)| `/x402/skill-catalog` | free | ✅ live |
| Consulting invoice(supply 第 4 弾候補、 human-in-the-loop)| (Phase 2 で設計)| $400-1,000 / hour | ⏳ Phase 2 |

### Wallet(Phase 1 mainnet ✅)

- **USDC wallet address**: `0x4d08AEB4776Aa82039bBA47db5d0bb5431d1c151`(Coinbase Smart Wallet on Base mainnet)
- **chain**: Base mainnet(USDC contract: `0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`)
- **facilitator**: CDP facilitator(Coinbase Developer Platform、 Ed25519 JWT 認証)
- **Solana / Stellar**: Phase 2 検討中
- **World ID verified**: Phase 2 候補

### Live endpoint(Phase 1 mainnet + supply 第 1-3 弾 + 監視装置 ✅、 2026-05-10 達成)

- **API base**: <https://tsuji-x402-endpoint.nagataku021.workers.dev>
- **Skill catalog**(free): `/x402/skill-catalog`
- **Brand fact**(free): `/x402/brand-fact`(永井 brand 物理証拠数字 packaging)
- **Industry N=1 fact API**(premium、 $0.10、 supply 第 1 弾): `/x402/premium/industry-fact?topic={topic}`(6 topics: claude-code-skills / memory-bank / harness-engineering / affiliate-ad-pdm / x402-deploy-oneday / solo-compound-holdings)
- **Workflow template API**(premium、 $1.00、 supply 第 2 弾): `/x402/premium/workflow-template?template_id={id}`(5 templates: 1-source-n-articles / auto-memory-setup / x402-deploy-oneday / harness-engineering-day-1 / 100-skills-cycle)
- **Memory excerpts**(premium、 $0.05、 supply 第 3 弾、 Tier 1+2 anonymized): `/x402/premium/memory?excerpt_id={id}`(10 excerpts: tokimeki-driven-development / harness-engineering-philosophy / context-engineering-moat / skill-feedback-loop / auto-memory-pattern / delegation-boundaries / creation-vs-sales-language / biz-anxiety-response / mendokusai-as-automation-signal / solo-compound-holdings-philosophy)
- **Skill API call**(premium、 $0.10、 stub): `/x402/premium/skill-call`(実 skill execution は Phase 1+ 別 turn)
- **Discovery file**: `/llms.txt` + `/.well-known/agentic-capabilities.json`(version `0.11.0-phase1-memory-excerpts`)
- **GitHub repo**: <https://github.com/takuyanagai0213/tsuji>(Public、 9 commits、 全 PR merged)
- **物理証拠累積監視装置**: Cloudflare Analytics Engine binding(`tsuji_analytics`)+ middleware で全 endpoint access の datapoint 自動書き込み + SQL API で User-Agent / path / topic / status / agent_type / country 別 breakdown query 可能
- **5/16 routine 集計 script**: `npm run metrics [1h|24h|7d|30d]`(永井さま手元で 1 commande 6 軸 breakdown 取得)

### Status

**Phase 1 supply 第 1-3 弾 + 監視装置 + 5/16 routine anchor 完成 ✅**(2026-05-10 達成、 declaration → supply 1-3 → 監視装置 → routine 投下 anchor まで物理化第 12 段)。 AI agent demand 4 軸の **3 軸物理化済**(残り 1 軸:consulting / human-in-the-loop は Phase 2 候補)。

AI agent が x402 standard 準拠 client(e.g. `x402-fetch` / `@coinbase/x402`)で endpoint access → Base mainnet で実 USDC payment + resource 取得可能 form 完成。 6 endpoints all live、 **21 query options**(6 topics + 5 templates + 10 excerpts)。

5/16 物理証拠累積監視 routine で AI agent 自然 reach trend 観察開始。 早期 inbound interest あれば X DM [@ejq45liu](https://x.com/ejq45liu) または [GitHub Issue](https://github.com/takuyanagai0213/takuyanagai0213/issues/new) まで。

## Stack

Go, TypeScript, Next.js, Claude Code, MCP, Skills

## Status

日々更新中。PR / Issue 歓迎します。

---

**AI 時代に残るもの: 業務蓄積 × 個人物語**
