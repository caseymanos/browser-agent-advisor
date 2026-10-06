# Decision rules

These are routing heuristics, not performance rankings. Evidence refreshed October 5, 2026. Recheck current official sources before recommending.

## Hard constraints

- No data leaves the machine: no verified complete turnkey fit. Local browser execution does not imply local inference, telemetry or tools. Literal no-egress conflicts with online purchasing; clarify scope.
- Native desktop: browser-only infrastructure cannot satisfy this. Use a desktop assistant or a computer-use model plus a desktop runtime.
- Contractual ZDR: verify models, runtime, files, logs and tools. Browserbase managed Agents is still outside browser ZDR/BYOS (Oct 5). OpenAI's Agents API (`/v1/agents`) is not ZDR-eligible. Consumer settings are not contracts.
- Purchases: distinguish native wallets, connection fields, developer examples and checkout UI control. Verify authorization and merchant state; a completed run is not proof of an order.
- Protected sites: persistence, MFA, proxies, CAPTCHA and bot recognition differ. No universal access guarantee; hCaptcha needs separate evidence.
- Budget/scale: compare equivalent billing units and actual workload. Included runs are not concurrency or all-in cost per completed task.

## Starting candidates

| Need | Candidate | Qualification |
|---|---|---|
| Personal desktop/building | ChatGPT Work/Codex | Verify OS, permissions and access; separate from API. |
| Hosted web tasks | Browser Use Cloud or Browserbase Agents | Tie-break on packaged execution versus platform breadth. No measured winner. OpenAI Agents API computer use (beta) is a third option for teams on OpenAI models. |
| Own browser harness | Stagehand v4 | Browser Use OSS may fit existing Python code better. v4 removes agent(). Route on released versions only (Stagehand 4.1.0, browser-use 0.13.10 on Oct 5). |
| Browser infrastructure | Browserbase browsers or Kernel | Select on required controls/integrations and measured workload. OpenAI Agents API computer use is hosted-only and tied to OpenAI models. |
| Custom payments | Kernel + own agent | Adapter coverage and reconciliation apply; some processors use prepared single-use checkout only. |
| Managed payments | Browser Use Cloud conditionally | Wallet fields require account/merchant verification. Browserbase's Stripe example is not a native Agent wallet. |
| Persistent personal assistant | Muse or OpenAI dots, whichever you can access; Instinct comparator | dots: Pro (not EEA/UK/Switzerland), Business Premium, Enterprise; purchases undocumented. Muse: US; Amazon blocks it (reported). Evidence gaps are not measured failures. |

## Dependencies

- Browser Use Cloud V4's September 12 documentation names OpenCode, Browser Use CLI and Cloud Browser.
- Browserbase Agents documents Stagehand tools on Browserbase sessions.
- Browser Use OSS integrates with Kernel and Browserbase; that does not establish Browser Use Cloud depends on either.
- Kernel's Stagehand guide covers v4 (running as an extension in the Kernel browser) and v3.
- Using OpenAI API models is not using the ChatGPT application. Agents API computer use is a developer-run hosted browser with no ChatGPT sessions, saved logins or plan allowances; dots is a separate ChatGPT product.
- Muse discloses its own harness and VM; Instinct's exact browser/model suppliers were not established.

Sources: [Browser Use](https://docs.browser-use.com/cloud/which-product), [Browserbase Agents](https://docs.browserbase.com/platform/agents/overview), [Stagehand](https://docs.stagehand.dev/v4/migrations/v3), [Kernel](https://www.kernel.sh/docs/integrations/overview), [payments](https://kernel.sh/docs/integrations/payments/overview.md), [OpenAI](https://developers.openai.com/api/docs/guides/tools-computer-use), [Muse](https://research.meta.ai/blog/security-and-safety-for-ai-agents-our-approach-with-muse), [dots](https://learn.chatgpt.com/docs/dots), [Agents API computer use](https://developers.openai.com/api/docs/guides/agents-api/tools/computer-use).
