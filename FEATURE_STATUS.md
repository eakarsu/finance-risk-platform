# Feature status — Financial risk & fraud controls

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 266 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 3 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 1 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 6 | 0 | Native records/view |
| Activity & audit trail | audit | 9 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Provider agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order installment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capture completion matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full return reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partial return allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchant discount calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Promotional subsidy calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consumer dispute allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve hold validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing deposit detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Provider channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network fee library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchant hierarchy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction volume ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Domestic cross-border classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment basis calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Switch fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Token service fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account updater fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorization fee control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit request workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network merchant analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Issuer agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account card hierarchy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible spend calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth bonus validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Large-ticket adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Virtual card analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ghost card analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foreign exchange fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Late fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intercompany exclusion control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Issuer claim workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor agreement library | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Merchant account registry | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Card transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interchange qualification reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Card-brand assessment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor markup reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Downgrade detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate fee detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund and reversal fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-border and currency fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tokenization qualification analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback fee reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Monthly statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovered fee ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor channel and location analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio | records | 1 | 0 | Native records/view |
| Disputes | records | 1 | 0 | Native records/view |
| Prevention | records | 1 | 0 | Native records/view |
| Recovery & Reporting | records | 1 | 0 | Native records/view |
| Merchant | records | 1 | 0 | Native records/view |
| Transaction | records | 1 | 0 | Native records/view |
| Dispute | records | 1 | 0 | Native records/view |
| Representment | records | 1 | 0 | Native records/view |
| Evidence Item | records | 1 | 0 | Native records/view |
| Fraud Signal | records | 1 | 0 | Native records/view |
| VAMP Snapshot | records | 1 | 0 | Native records/view |
| Prevention Rule | records | 1 | 0 | Native records/view |
| Recovery Payout | records | 1 | 0 | Native records/view |
| Alert | records | 1 | 0 | Native records/view |
| Acquirer Report | records | 1 | 0 | Native records/view |
| Case Note | records | 1 | 0 | Native records/view |
| Draft: Representment Evidence Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: VAMP Ratio Forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Dispute Pattern Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorization capture ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund chargeback ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing model reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Markup fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gateway fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum fee control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve holdback reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement timing audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deposit-to-batch matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing settlement detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account processor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accounts | records | 2 | 0 | Native records/view |
| Transactions | records | 4 | 0 | Native records/view |
| Alerts | records | 3 | 0 | Native records/view |
| SAR Cases | records | 1 | 0 | Native records/view |
| EDD Cases | records | 1 | 0 | Native records/view |
| Investigations | records | 1 | 0 | Native records/view |
| Watchlists | records | 1 | 0 | Native records/view |
| Sanctions Hits | records | 1 | 0 | Native records/view |
| PEPs | records | 1 | 0 | Native records/view |
| CTRs | records | 1 | 0 | Native records/view |
| Regulatory Filings | records | 1 | 0 | Native records/view |
| KYC Profiles | records | 1 | 0 | Native records/view |
| Source of Funds | records | 1 | 0 | Native records/view |
| Beneficial Owners | records | 1 | 0 | Native records/view |
| Typologies | records | 1 | 0 | Native records/view |
| Jurisdictions | records | 1 | 0 | Native records/view |
| AI · Typology Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Transaction Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Sanctions Name Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · False Positive Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · SAR Narrative Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Investigation Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Network Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Beneficial Owner Trace | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Source of Funds Explain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · EDD Questionnaire | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Regulatory Filing Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Customer Risk Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Peer Group Compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Jurisdictional Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · KYC Refresh Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adverse media screen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Kyc onboarding prescreen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Peer benchmarks | records | 1 | 0 | Native records/view |
| Ingestion | records | 1 | 0 | Native records/view |
| Case workflow | records | 1 | 0 | Native records/view |
| Escalation | records | 1 | 0 | Native records/view |
| Fincen exports | records | 1 | 0 | Native records/view |
| Advisory actions | records | 1 | 0 | Native records/view |
| Structuring risk | records | 1 | 0 | Native records/view |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Production controls | records | 2 | 0 | Native records/view |
| Fraud Rules | records | 1 | 0 | Native records/view |
| Fraud Alerts | records | 1 | 0 | Native records/view |
| Credit Scores | records | 1 | 0 | Native records/view |
| Risk Models | records | 1 | 0 | Native records/view |
| Watchlist | records | 1 | 0 | Native records/view |
| Behavioral Patterns | records | 1 | 0 | Native records/view |
| Merchant Profiles | records | 1 | 0 | Native records/view |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Rule Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargebacks | records | 1 | 0 | Native records/view |
| Refund Abuse Risk | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Transfers | records | 1 | 0 | Native records/view |
| Beneficiaries | records | 1 | 0 | Native records/view |
| Currencies | records | 1 | 0 | Native records/view |
| AI Chat | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Fee Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AML Risk Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| KYC Screening | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Rate Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary Risk Score | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Smart Routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Split Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Receipts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Route optimize | records | 1 | 0 | Native records/view |
| Split plan | records | 1 | 0 | Native records/view |
| Corridor liquidity risk | records | 1 | 0 | Native records/view |
| Cash buffer stress | records | 1 | 0 | Native records/view |
| Robo advisor | records | 1 | 0 | Native records/view |
| Credit scoring | records | 1 | 0 | Native records/view |
| Portfolio dashboard | records | 1 | 0 | Native records/view |
| Import | records | 1 | 0 | Native records/view |
| Stock screener | records | 1 | 0 | Native records/view |
| Crypto analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan advisor | records | 1 | 0 | Native records/view |
| Insurance optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement planner | records | 1 | 0 | Native records/view |
| Budget coach | records | 1 | 0 | Native records/view |
| Goal tracker | records | 1 | 0 | Native records/view |
| Bill negotiator | records | 1 | 0 | Native records/view |
| Asset allocation | records | 1 | 0 | Native records/view |
| Rebalancing suggest | records | 1 | 0 | Native records/view |
| Budget optimize | records | 1 | 0 | Native records/view |
| Stock recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement project | records | 1 | 0 | Native records/view |
| Advanced tools | records | 1 | 0 | Native records/view |
| Financial Statements | records | 1 | 0 | Native records/view |
| Profit & Loss | records | 1 | 0 | Native records/view |
| Balance Sheets | records | 1 | 0 | Native records/view |
| Cash Flow | records | 1 | 0 | Native records/view |
| Revenue Drift | records | 1 | 0 | Native records/view |
| Revenue Forecasts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| KPI Metrics | records | 1 | 0 | Native records/view |
| Expense Records | records | 1 | 0 | Native records/view |
| Budget vs Actuals | records | 1 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detection | records | 1 | 0 | Native records/view |
| Compliance | records | 1 | 0 | Native records/view |
| Tax Reports | records | 1 | 0 | Native records/view |
| Generate Report | records | 1 | 0 | Native records/view |
| Custom Reports | records | 1 | 0 | Native records/view |
| Financial Ratios | records | 1 | 0 | Native records/view |
| NL Query | records | 1 | 0 | Native records/view |
| Peer Comparison | records | 1 | 0 | Native records/view |
| Export Data | records | 1 | 0 | Native records/view |
| Scheduled Reports | records | 1 | 0 | Native records/view |
| Scenario Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DCF Valuation | records | 1 | 0 | Native records/view |
| Monte Carlo | records | 1 | 0 | Native records/view |
| Capital Budgeting | records | 1 | 0 | Native records/view |
| Break-Even | records | 1 | 0 | Native records/view |
| Working Capital | records | 1 | 0 | Native records/view |
| AI Presentations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Variance Explainer | records | 1 | 0 | Native records/view |
| Forecast Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Board Reports | records | 1 | 0 | Native records/view |
| Expense Categorizer | records | 1 | 0 | Native records/view |
| Audit Readiness | records | 1 | 0 | Native records/view |
| Covenant Tracking | records | 1 | 0 | Native records/view |
| Segment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Backlog tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscriptions | records | 1 | 0 | Native records/view |
| Budgets | records | 1 | 0 | Native records/view |
| Agents | records | 1 | 0 | Native records/view |
| autonomous budget agent | records | 1 | 0 | Native records/view |
| subscription analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| financial goal orchestration | records | 1 | 0 | Native records/view |
| expense anomaly detection | records | 1 | 0 | Native records/view |
| cashflow forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debt snowball planner | records | 1 | 0 | Native records/view |
| the agents js route is unfulfilled | records | 1 | 0 | Native records/view |
| transactions without categorize | records | 1 | 0 | Native records/view |
| budgets without budget | records | 1 | 0 | Native records/view |
| subscriptions without subscription | records | 1 | 0 | Native records/view |
| accounts without net | records | 1 | 0 | Native records/view |
| bank credit card sync plaid mx | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| investment portfolio tracking | records | 1 | 0 | Native records/view |
| tax planning module | records | 1 | 0 | Native records/view |
| limited spending analytics no aggregations beyond | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| bill pay integration | integration | 1 | 0 | Provider request records only |
| notifications layer grep 0 | records | 1 | 0 | Native records/view |
| webhooks for transaction events | integration | 1 | 0 | Provider request records only |
| mobile app | records | 1 | 0 | Native records/view |
| only 7 frontend pages | records | 1 | 0 | Native records/view |
| Bookkeeping | records | 1 | 0 | Native records/view |
| Tax Preparation | records | 1 | 0 | Native records/view |
| Payroll | records | 1 | 0 | Native records/view |
| Financial Reports | records | 1 | 0 | Native records/view |
| Client Profitability | records | 1 | 0 | Native records/view |
| Practice Management | records | 1 | 0 | Native records/view |
| Settings | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 266 feature pages were visited in the browser; 264 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 127 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

127 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
