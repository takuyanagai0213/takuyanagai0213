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

## Stack

Go, TypeScript, Next.js, Claude Code, MCP, Skills

## Status

日々更新中。PR / Issue 歓迎します。

---

**AI 時代に残るもの: 業務蓄積 × 個人物語**
