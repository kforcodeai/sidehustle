# Granular Services & Prices Reference — HighLevel, India (2026)

**Verified on 31 October 2026 · Currency: INR for agency estimates; USD for vendor rate cards.**

This is an internal reference to what an agency can deliver with HighLevel, what must be built or integrated, the charges that accumulate, and possible resale prices. It covers native modules, paid add-ons, implementation and managed services, industry systems, custom software, and restricted or emerging products. It contains **300 core service entries, 41 supplementary app-specific scopes, and 32 solution assemblies**. Section 14 maps the complete inspected spm-ts app inventory. The granular layer in sections 9–13 adds **160 implementation units, 40 recurring work units, metering formulas and 7 itemised build examples**.

**Evidence labels are part of the reference:**

- **Verified vendor fact:** supported by the linked official product or billing documentation, as checked on the date above. Product access, destination, provider and contract can alter the actual account bill.
- **Estimate:** effort, internal labour cost, Indian agency selling prices and markup bands calculated for this reference. These are editable assumptions, not HighLevel tariffs or a survey of Indian agencies.
- **Observed offer:** an identifiable provider's public asking price. It does not reveal their cost, realised markup, take-home earnings or Indian market average.
- **Conditional / unresolved:** beta access, incomplete public pricing, contradictory documentation or an unverified capability. Such entries are explicitly conditional; unknown costs are not treated as zero.

HighLevel can be a component of an effectively unlimited number of custom solutions. “Complete” here means coverage of its documented functional families and material billable dependencies, with representative implementations and expansion rules—not a claim that every conceivable custom application is enumerated.

## Contents

1. [Cost model, notation and markup](#1-cost-model-notation-and-markup)
2. [Verified platform and vendor charges](#2-verified-platform-and-vendor-charges)
3. [Service catalogue](#3-service-catalogue)
4. [Complete solution assemblies](#4-complete-solution-assemblies)
5. [Special billing and delivery cases](#5-special-billing-and-delivery-cases)
6. [Worked cost calculations](#6-worked-cost-calculations)
7. [Observed market offers and limits of markup evidence](#7-observed-market-offers-and-limits-of-markup-evidence)
8. [Coverage and source register](#8-coverage-and-source-register)
9. [Atomic deliverables and unit pricing](#9-atomic-deliverables-and-unit-pricing)
10. [Recurring operations priced by actual work](#10-recurring-operations-priced-by-actual-work)
11. [Consumption units and exact costing rules](#11-consumption-units-and-exact-costing-rules)
12. [Change charges, scope boundaries and delivery checks](#12-change-charges-scope-boundaries-and-delivery-checks)
13. [Itemised build examples](#13-itemised-build-examples)
14. [Frontend app coverage audit — spm-ts](#14-frontend-app-coverage-audit--spm-ts)

## 1. Cost model, notation and markup

### 1.1 What a service actually costs

For a client using an agency-owned account:

`Monthly direct cost = allocated platform cost + enabled add-ons + metered consumption + external providers/hosting + recurring delivery labour + collection/FX fees + non-recoverable taxes.`

`One-time direct cost = implementation labour + migration/cleanup + external licences/assets + testing/handover + non-recoverable fees/taxes.`

`Quoted service total = setup fee + monthly platform/access fee + monthly managed-work fee + software/add-on resale + metered usage + separately scoped external work + applicable tax.`

Each table below shows **labour-only implementation cost**, plus explicit vendor-cost codes. It is not the total direct cost. Where the client already owns and pays for HighLevel, the agency's platform allocation is zero for that project, but client software and usage charges continue. Do not count the same subscription in both the access fee and an add-on line.

### 1.2 Editable estimating assumptions

| Input | Reference assumption | Meaning |
|---|---:|---|
| Configuration, content, training and routine operations | ₹500/hour | Loaded delivery cost assumption; replace with your actual employee/contractor cost |
| Custom integration/software engineering | ₹1,200/hour | Includes routine development and testing effort; not an external vendor's rate |
| USD conversion | ₹95/USD | Deliberate budgeting assumption, **not** a verified spot rate |
| Scope | One sub-account, one brand, one language | Extra languages, branches, data sources and revisions add effort |
| Client content | Supplied unless a row includes creation | Copy, photos, filming, translation and domain acquisition are separate when required |
| Setup range | Bounded small/medium implementation | Complex data, unusual permissions and enterprise requirements need a fresh estimate |
| Tax | Excluded from all quote ranges | Apply actual invoice treatment; a sample tax percentage is not tax advice |
| Ongoing service | Defined monthly work allowance | No implied unlimited changes, moderation or human availability |

Effort ranges include ordinary configuration, a test of the stated flow and a short handover. They exclude prolonged approval waiting, extensive rewriting and reconstruction of undocumented systems. For every estimate, choose one actual effort and one actual multiplier; the low and high endpoints represent different scope assumptions.

### 1.3 Markup classes used throughout the catalogue

| Code | What is marked up | Illustrative markup on that cost | Equivalent selling multiplier / gross margin on that line |
|---|---|---:|---|
| **C** | Configuration/content labour | 100–200% | 2–3× cost / 50–66.7% before other costs |
| **T** | Engineering labour | 50–150% | 1.5–2.5× cost / 33.3–60% before other costs |
| **V** | Paid software/add-on cost | 15–50% | 1.15–1.5×; management charged separately |
| **U** | Metered communication/AI/automation cost | 20–50% | 1.2–1.5×; collection/FX fees can consume part of this |
| **P** | Client-paid spend, payouts or goods | 0% pass-through by default | Ads, postage, affiliate commissions, reward face value, shipping, merchant fees; any procurement/service fee must be explicit |

These are **suggested quoting bands**, not evidence of what people actually earn. A 1.5× multiplier is 50% markup, not 150% markup. A “free/included” incremental feature has no meaningful percentage markup until platform allocation and servicing cost are assigned.

`Markup % = (selling price − chosen cost base) ÷ chosen cost base × 100`\
`Gross margin % = (selling price − total direct cost) ÷ selling price × 100`

A 200% labour markup can coexist with a loss after platform allocation, support and usage. Net profit additionally deducts sales, general overhead, refunds and tax effects.

### 1.4 Monthly managed-work bands

These are **optional additional services**, not HighLevel subscription prices. A catalogue row's M-code gives both your recurring labour cost and an indicative monthly fee. A dash means no recurring work is included. Large content-production rows specify their monthly deliverable separately.

| Code | Monthly labour included | Your labour cost/month | Indicative managed-work fee/month | Markup |
|---|---:|---:|---:|---|
| M0 | No ongoing work | ₹0 | ₹0 | Not applicable; hosting/platform/usage may continue |
| M1 | 0.5–1 configuration hour | ₹250–500 | ₹500–1,500 | C |
| M2 | 1–2 configuration hours | ₹500–1,000 | ₹1,000–3,000 | C |
| M3 | 2–4 configuration hours | ₹1,000–2,000 | ₹2,000–6,000 | C |
| M4 | 4–8 configuration hours | ₹2,000–4,000 | ₹4,000–12,000 | C |
| M5 | 8–16 configuration hours | ₹4,000–8,000 | ₹8,000–24,000 | C |
| M6 | 2–4 engineering hours | ₹2,400–4,800 | ₹3,600–12,000 | T |
| M7 | 4–8 engineering hours | ₹4,800–9,600 | ₹7,200–24,000 | T |

M-bands buy monitoring, defined edits, content work or administration as specified in the row. They do not buy staffed customer support, a full-time operator, guaranteed response times or unlimited AI. Combine overlapping maintenance under one scoped allowance rather than adding every row's M-band mechanically.

### 1.5 Delivery and vendor-cost codes

| Code | Meaning |
|---|---|
| N | Native configuration; platform allocation still applies; no separate module charge identified in the sources used |
| I | External integration/provider; its subscription, tasks, usage and hosting are extra |
| X | Custom software or external implementation on top of HighLevel |
| B | Beta/Labs/access-restricted; verify access and price before promising delivery |
| E | LC Email sending/receiving/forwarding and optional validation/IP |
| W | WhatsApp $10/location/month plus messaging/calling and applicable rebilling charges |
| P | LC Phone rental/usage, carrier/registration and optional recording/transcription |
| A | AI usage or eligible AI Employee allowance; channel charges remain separate |
| F | Premium workflow executions / eligible Workflow Pro allowance |
| G | Payment gateway fees, refunds/disputes, mandate and settlement charges where applicable |
| D | Domain, external assets, premium plugins or stock/media licences |
| S | Search Atlas SEO / Listings / Prospecting subscription as selected |
| H | Hosting/backend/app infrastructure; distinguish native site hosting, WordPress and AI Studio Cloud |
| R | Resold paid add-on from section 2 |

Codes can stack: `N+W+A+F` means native delivery plus four distinct possible cost layers. `B` does not mean free. Vendor-code markups use V or U in addition to the row's labour markup; P-class spend uses pass-through unless separately agreed.

## 2. Verified platform and vendor charges

### 2.1 Agency subscription and entitlement boundaries

| Plan | Monthly USD / reference INR | Annual USD / reference INR | Published capacity and relevant gate |
|---|---:|---:|---|
| Starter | $97 / ₹9,215 | $970 / ₹92,150 | 3 sub-accounts; core CRM features |
| Unlimited | $297 / ₹28,215 | $2,970 / ₹2,82,150 | Unlimited sub-accounts; basic API; supported phone/email rebilling at cost |
| Founder (also called Agency Pro / Pro / SaaS Pro in older guides) | $497 / ₹47,215 | $4,970 / ₹4,72,150 | Markup rebilling, SaaS capabilities and Founder-gated features |
| Enterprise | Quote required | Quote required | Contract-specific capacity, support and included add-ons |

Unlimited contacts/users/sub-accounts are not unlimited communication, AI, premium actions or external storage. Annual equivalents are paid commitments, not monthly cash payments. Confirm whether an agency's own operating account consumes a Starter slot. Source: [official subscription pricing][S01].

**Automatic rebilling is product-specific.** The general guide permits supported at-cost rebilling on $297/$497 and markup on $497. Individual resale products can have different gates; some require an agency Stripe connection. Manually invoicing a managed service is different from enabling HighLevel's automatic wallet rebilling. An agency wallet funds provider charges before collection from a client; a failed client payment does not erase the agency cost. [Billing and wallets][S02], [rebilling mechanics][S03].

Illustrative monthly platform allocation, before usage, FX or tax:

| Active paying locations | Starter allocation | Unlimited allocation | Founder allocation |
|---:|---:|---:|---:|
| 1 | ₹9,215 | ₹28,215 | ₹47,215 |
| 3 | ₹3,071.67 | ₹9,405 | ₹15,738.33 |
| 10 | Not within plan capacity | ₹2,821.50 | ₹4,721.50 |
| 25 | Not within plan capacity | ₹1,128.60 | ₹1,888.60 |
| 50 | Not within plan capacity | ₹564.30 | ₹944.30 |

This is cost allocation, not a recommended customer subscription price. A client consumes allocated capacity even when they send no messages.

### 2.2 Fixed add-ons and agency overhead

USD amounts are verified list prices; INR and resale ranges are calculations. **Indicative software resale below = vendor cost × 1.15–1.5, rounded to rupees**, before collection/FX/tax. Setup and managed work are additional.

| Item / billing scope | Vendor price | Reference cost | Indicative software-only resale | Exception |
|---|---:|---:|---:|---|
| WhatsApp / enabled sub-account / month | $10 | ₹950 | ₹1,093–1,425 | Messaging/calls extra |
| Branded Client Portal App / sub-account / month | $49 | ₹4,655 | ₹5,353–6,983 | Customer/member app; distinct from agency white-label mobile app |
| Dedicated email IP / IP / month | $59 | ₹5,605 | ₹6,446–8,408 | Eligibility, sending-domain and warm-up requirements |
| Online Listings / enabled location | $30/month; $150/6 months; $300/year | ₹2,850/month; ₹14,250/6 months; ₹28,500/year | ₹3,278–4,275/month on monthly purchase | Directory/country coverage must be checked for Indian address |
| SEO powered by Search Atlas / sub-account / month | $79 | ₹7,505 | ₹8,631–11,258 | Quotas/projects/keywords apply; content and link acquisition extra |
| Premium Prospecting / enabled subscription / month | $29 | ₹2,755 | ₹3,168–4,133 | Agency subscription can link one sub-account under documented terms; not automatically $29 for every client |
| WordPress hosting / single-site entry offer / month | Starts at $10 | Starts at ₹950 | Starts at ₹1,093–1,425 | Higher hosting plans published up to $497; checkout determines capacity and actual tier |
| Ad Manager / agency base fee | $0/month | ₹0 incremental | No percentage markup on zero cost | Can charge for access/services; ad spend extra |
| Domain registration / domain / term | Varies by TLD | Quote required | Actual renewal cost + 15–50% or handling fee | Intro price differs from renewal, transfer and redemption |
| Marketplace apps, snapshots, templates | Seller-specific | Quote required | Licence cost + permitted handling/service fee | One-time, subscription, usage and commercial reuse terms vary |

Sources: [add-on price list][S01], [Listings][S04], [Prospecting terms][S05], [WordPress reselling][S06], [Ad Manager][S07], [SEO][S08].

| Agency-level item | Published vendor charge | Reference cost | Cost treatment |
|---|---:|---:|---|
| White-label CRM mobile app | $497/month or $1,491/quarter | ₹47,215/month or ₹1,41,645/quarter | Agency-wide overhead; customer access/support is separately priced |
| Premium support | $500/month or $5,000/year | ₹47,500/month or ₹4,75,000/year | Agency overhead; not client-facing 24/7 staffed support |
| White-label Zap | $50/month | ₹4,750/month | Agency branding/integration offering, not arbitrary free Zapier task volume |
| HighLevel certification | $97/month or $970/year | ₹9,215/month or ₹92,150/year | Agency education cost; not a customer feature |
| Advanced account setup (HighLevel's own service) | $1,000 one-time | ₹95,000 | Optional vendor implementation purchase; distinct from your labour |
| HIPAA upgrade | $297/month, account-wide | ₹28,215/month | Agency scope; guide says cannot be deactivated after enablement |

Sources: [official billing guide][S02], [HIPAA activation terms][S64]. These are overhead inputs; allocation or a scoped service fee is more meaningful than automatically charging each client the entire agency bill. HIPAA purchase alone is not proof that a particular deployment, integration or operator is compliant.

### 2.3 Email consumption

| Charge | Vendor rate | INR at ₹95/USD | Example resale using U (20–50%) |
|---|---:|---:|---:|
| LC Email | $0.675/1,000 billable email events | ₹64.125/1,000 | ₹76.95–96.19/1,000 |
| Email validation | $2.50/1,000 checks | ₹237.50/1,000 | ₹285–356.25/1,000 |

LC documents charges for incoming/outgoing recipients, CC/BCC and forwarding, not simply one charge per newsletter job. Validation is separate; repeat checking can create additional usage. Domain authentication does not supply a Google Workspace/Zoho mailbox, and a dedicated sending domain is not a dedicated IP. Limits depend on ramp-up and configuration, so verify the account's displayed send allowance. External SMTP can shift billing to another provider. [LC Email charges][S09], [SMTP/mailbox distinction][S10].

### 2.4 WhatsApp: current rule changes and conflicting rate presentations

**HighLevel's billing guide says that from 1 October 2026 service messages beyond 1,000 per phone number/month and utility messages inside the customer-service window are billable. Its older in-page table is labelled through 30 September.** Eligible Click-to-WhatsApp Free Entry Point windows remain a separate 72-hour exception; check the qualifying entry/reply conditions. This is a HighLevel billing statement; do not automatically apply it to a different direct-Meta/BSP contract. [HighLevel WhatsApp guide][S11].

| India charge | October CSV attached to HighLevel guide | Reference INR | Older article-body figure | Reference treatment |
|---|---:|---:|---:|---|
| Marketing / delivered message | $0.0118 | ₹1.121 | $0.0124 | October attachment basis pending wallet confirmation |
| Utility / delivered message | $0.0014 | ₹0.133 | $0.0015 | Same; in-window billing changed per guide |
| Service / delivered message beyond free allowance | $0.0014 | ₹0.133 | “FREE” through 30 September | First 1,000/number/calendar month free per guide |
| Authentication template | No India authentication column in attachment | Unresolved | Not safely derivable | Obtain actual supported template/category rate |
| WhatsApp business-initiated calling to India | Article calling table: $0.0056/min | ₹0.532/min | Separate product | Not the template-message price; validate account eligibility |
| User-initiated WhatsApp calling | Guide lists no usage fee | ₹0 base call usage | Separate from PSTN | Do not infer free Voice AI or free workflow activity |

The [October 2026 CSV][S12] was downloaded and read directly. Its attachment URL may redirect to an expiring signed link; access it through the guide if needed. The body figures are approximately October values × 1.05 after rounding; the guide separately describes a default 1.05× rebilling multiplier. **This relationship is an inference, not proof that every account bill includes or excludes a 5% layer.** Preserve both figures, inspect actual transactions and avoid adding 5% twice. For a conservative pre-reconciliation estimate, use the higher displayed body figure and state the basis. The exact billed unit rate remains unresolved until account-level confirmation.

For U-class resale on the CSV basis, marketing is approximately ₹1.35–1.68/message and utility/service ₹0.16–0.20/message. These examples do not include the $10 subscription, management, FX, taxes or rounding. Charges follow delivered billable messages and destination/category rules, not a flat price per customer. Do not add the older conversation model on top of per-message billing.

### 2.5 Phone, SMS, call intelligence and India restrictions

| Item | Verified rate / charging unit | Reference INR | Boundary |
|---|---:|---:|---|
| India local number, beta | $4/month | ₹380/month | Approved access and per-location regulatory verification required |
| India local inbound call | $0.0075/min | ₹0.7125/min | Forwarding/delivery legs can add cost |
| India outbound child leg | $0.0075/min | ₹0.7125/min | **Not total outbound call cost**; parent leg separately billed |
| US/Canada local number | $1.15/month | ₹109.25/month | Does not grant Indian local capabilities |
| US/Canada toll-free number | $2.15/month | ₹204.25/month | Messaging verification/usage separate |
| US/Canada SMS | $0.00747/segment each direction | ₹0.70965/segment | Plus carrier fees and applicable registration |
| US/Canada browser/mobile outbound voice | $0.0166/min published combined example | ₹1.577/min | Destination/route and legs must match |
| US local inbound to browser/mobile | $0.01165/min published combined example | ₹1.10675/min | Other answering methods differ |
| Call recording | $0.0025/min | ₹0.2375/min | Supported countries/numbers only |
| Recording storage | $0.0005/min/month | ₹0.0475/min/month retained | Recurs while retained |
| Call transcription | $0.024/min | ₹2.28/min | Distinct from Voice AI inference |
| Answering-machine detection | $0.0075/call | ₹0.7125/call | Optional extra |
| A2P registration and recurring campaign fees | Brand/type-dependent; live rate required | Variable | Some fees start on submission even if rejected |
| Number intelligence, validation, RCS/MMS, SIP/conferences | Product/route-dependent | Variable | Quote from the enabled provider; not universal SMS cost |

Sources: [India phone beta][S13], [phone rate guide][S14]. These two sources support different country-specific systems; do not copy a US capability into India. The [13 October international update][S15] supersedes older figures for its affected destinations and number types.

**India beta limits:** domestic outbound calls; inbound answered by forwarding number; no native SMS/MMS, Voice AI, IVR workflow calls, recording/transcription, warm/blind transfers or answering in the web/mobile app under the cited guide. India endpoints and regulatory documents are required; number movement is restricted. Published purchase-cap wording is “one additional” number per eligible account, so confirm actual inventory/capacity rather than promising a number pool. WhatsApp onboarding is separate. [India feature restrictions][S13].

A location-level 5% pass-through uplift applies to specified carrier/registration/Verified Caller ID/RCS categories, separate from agency markup; it is not automatically 5% on every phone event. Check whether a quoted A2P amount already includes it. [Phone pass-through rules][S16].

Voice Intelligence is a Labs feature for eligible recorded LC calls, with no separate charge beyond normal transcription according to its guide. Recording/storage still have their own costs. India beta recording limitations prevent promising this on those numbers. [Voice Intelligence][S17].

### 2.6 Premium workflows

| Tier / per enabled sub-account | Subscription USD / INR per month | Included premium executions | Overage USD / INR each |
|---|---:|---:|---:|
| No paid tier | $0 / ₹0 | 100 **lifetime**, not monthly | $0.01 / ₹0.95 |
| Starter | $10 / ₹950 | 10,000/month | $0.008 / ₹0.76 |
| Growth | $25 / ₹2,375 | 30,000/month | $0.006 / ₹0.57 |
| Scale | $50 / ₹4,750 | 65,000/month | $0.004 / ₹0.38 |

The product-specific guide explicitly says allowances are **per sub-account**, despite ambiguous agency wording in the overview. Multiple premium steps, marketplace/LC actions, retries and re-entry can each consume executions. Standard workflow steps do not. AI actions/model use may have separate charges and are not blanket-covered by Workflow Pro. Paid monthly balances do not normally roll over; workflows continue into paid overages. [Workflow Pro tiers][S18], [premium-action billing][S19].

### 2.7 AI plans, usage and app hosting

| AI Employee / enabled sub-account | USD/month | INR/month | Main included agent allowances |
|---|---:|---:|---|
| Starter | $20 | ₹1,900 | Assistant-focused; no included Conversation/Voice/Reviews/Managed Agent allowance; agency must be on Founder |
| Growth | $50 | ₹4,750 | 1,000 Conversation responses; 100 Voice minutes; 100 Managed Agent runs/month; Reviews under fair use |
| Unlimited | $97 | ₹9,215 | Conversation/Voice/Reviews under fair use; 1,000 Managed Agent runs/month |

Assistant access differs between agency and sub-account users. “Unlimited” is subject to fair use, and Extra Usage can enable paid overages. Flow Agents/Agent Studio and Workflow AI usage are separate from blanket plan coverage. Channels and phone charges are additional. AI subscription software resale can use V; variable AI usage can use U. Automatic AI Employee rebilling requires the $497 agency plan. [AI product pricing][S20].

| Usage type | Cost basis | Quoting treatment |
|---|---|---|
| Conversation AI / prompt optimizers | Selected model input/output tokens when not covered | Not a fixed universal per-response rate |
| Traditional Voice AI | Minutes × ($0.045 engine + selected TTS) + LLM tokens | OpenAI TTS example adds $0.015/min; phone extra |
| Speech-to-speech voice | Selected model per-minute rate | Do not also assume the traditional TTS formula |
| Reviews AI PAYG | $0.01 / AI-assisted reply sent | Suggestion generation differs from sending; see product details |
| Managed Agents | Runs/plan allowance, then model/resource usage | Chat sessions, event triggers and schedules count differently |
| Flow Agents | PAYG model/tools/search/media | No included AI Employee allowance |
| Ask AI / AI Studio / Creator Studio | User tier, rolling allowance, model/resources | Creation activity and app hosting are distinct |
| Free builder helpers / knowledge base | Published included features, fair use | Does not make the running customer-facing agent free |

Use [the live AI product tables][S20] for model rates and plan-specific coverage. This reference deliberately does not freeze every model tariff. A longer prompt, retrieved context, generated media or tool loop changes cost even when the count of visible customer replies is unchanged.

HighLevel also supports **fixed-unit client rebilling** for Conversation and Voice AI, independently of token-cost markup. The agency still pays underlying actual usage: a low fixed client rate can create a negative spread. A documented example rate is illustrative, not a vendor cost. [Fixed-rate AI rebilling][S60].

**AI Studio Cloud has a separate, more specific rate card.** It calls its free instance **Tiny**, while the general AI guide uses older Nano/Micro wording. Use the Cloud guide's tier names and checkout when estimating hosting. [AI Studio Cloud][S21].

| Cloud resource / project | Published charge | INR reference |
|---|---:|---:|
| Tiny | Free instance | ₹0 incremental compute |
| Mini | $0.015456/hour; ~$11.28/730h | ~₹1,071.60/month |
| Small | $0.02369/hour; ~$17.29/730h | ~₹1,642.55/month |
| Medium | $0.09453/hour; ~$69.01/730h | ~₹6,555.95/month |
| Large | $0.174455/hour; ~$127.35/730h | ~₹12,098.25/month |
| X-Large | $0.330855/hour; ~$241.52/730h | ~₹22,944.40/month |
| Database | First 2 GB free; extra reserved GB at $0.000197/hour | ~₹13.66/GB/730h |
| File storage | First 1 GB free; extra actual GB at $0.000047/hour | ~₹3.26/GB/730h |

Database capacity cannot be reduced in that Cloud environment; first expansion is to 8 GB. Pausing compute leaves excess storage charges active. Resizing can bill both sizes for the transition hour. These are infrastructure charges, not the cost to design or operate the application. [Cloud billing details][S21].

### 2.8 Payments and external providers

HighLevel connects payment providers; provider support varies by product surface and method. Do not assume that an Indian gateway available on a payment link also works in SaaS wallets, POS, a Service Menu or a particular recurring mandate. [Payment support matrix][S22].

Razorpay's integration requires merchant keys/webhooks and a verified branded domain. Its guide says **Razorpay cannot fund SaaS Mode or wallet auto-recharges through this integration because supported off-session charging is missing**. Fixed-schedule subscriptions are a different capability. Some older matrix entries differ from the integration narrative; test the exact surface and method. [Razorpay integration][S23], [SaaS custom-provider requirements][S24], [calendar restrictions][S25].

Razorpay publishes standard 2% gateway pricing, promotional offers and method-specific exceptions; the retrieved page also lists credit-card-on-UPI at 2.15% + GST. Use the merchant contract, not a universal 2% assumption. Gateway fees, international/FX fees, subscription-product fees, chargebacks, refunds and instant settlements can differ. HighLevel integration does not guarantee every Razorpay method is exposed. [Razorpay pricing][S26].

**India agency billing dependency:** Stripe currently lists new Indian accounts as invite-only. Features requiring an agency Stripe connection therefore need a working eligible account; paying for HighLevel alone does not establish that access. Do not assume Razorpay can replace it for SaaS wallet charging. [Stripe India availability][S62].

**External Indian SMS cost stack:** provider account/usage, DLT entity onboarding where applicable, registered headers/content templates, consent setup, scrubbing/route charges, and integration monitoring. Obtain the provider’s actual fee schedule and approval scope; no universal India per-SMS or DLT registration price is asserted here. [Airtel registration/header/template resources][S63].

External SMS/voice, Make/Zapier/n8n, cloud hosting, ERP/POS/accounting, logistics, webinar platforms, mailbox providers, domain registrars and licensed media have their own contracts. Where no verified price is recorded here, use **actual provider quote + relevant usage**, not an invented vendor tariff.

## 3. Service catalogue

All setup amounts below are **estimates in INR**. The “Effort → cost” column is labour only, computed from section 1. Setup selling ranges apply the row's C/T multiplier. Monthly M-codes expand to the exact labour-cost and resale ranges in section 1.4. Vendor codes link to the charges in section 2 and remain additional.

**Common scope:** one location/brand/language, ordinary client-supplied content, up to two revision rounds. A “workflow” means one bounded business process, not unlimited branching or ongoing campaigns. A native item marked N still requires paid platform access. Basic ongoing monitoring is only included if a monthly M-band is purchased.

### 3.1 Contacts, companies, CRM data and permissions

Native foundations are documented under [Contacts/CRM][S27], [Companies][S28], [Custom Objects][S29] and [associations][S30]. These are sellable configuration and data services, not separate per-contact licences.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| CRM01 | Account foundation: business profile, time zone, currency, 5 users and permissions | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CRM02 | Contact CSV import: up to 5,000 clean records and field mapping | N | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M0 | C |
| CRM03 | Data cleanup: one duplicate/formatting rule set, up to 5,000 records | N | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |
| CRM04 | Contact segmentation: 5 Smart Lists, tags and lifecycle definitions | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| CRM05 | Custom fields and values: up to 20 fields plus reusable business values | N | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M1 | C |
| CRM06 | Company/B2B CRM: company schema and contact associations | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CRM07 | Automatic company matching/enrichment: domain rules and exclusions | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| CRM08 | Custom object: one entity, up to 15 fields, import template and record views | N | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| CRM09 | Record relationships: up to 3 association types, tested with sample records | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| CRM10 | Role/access design: 3 role profiles and assignment/visibility tests | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CRM11 | Consent/DND records: capture fields, suppression segments and opt-out routing | N+E+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CRM12 | Document/file organisation: field uploads, shared-file structure and permissions | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CRM13 | Data enrichment integration: one external data source and matching rules | I+F | 6–14h → ₹7,200–16,800 | ₹10,800–42,000 | M6 | T |
| CRM14 | CRM migration: contacts, deals and 5 reconstructed workflows from one system | N+I | 20–50h → ₹10,000–25,000 | ₹20,000–75,000 | M3 | C |
| CRM15 | Data export/offboarding: agreed record types and attachment manifest | N+I | 4–12h → ₹2,000–6,000 | ₹4,000–18,000 | M0 | C |

**Boundaries:** Company enrichment here means documented name/domain/logo matching, not a guaranteed phone/email lead database. Existing company associations are not automatically corrected. Custom objects do not inherit every Contact marketing feature; marketing still targets eligible contacts. [Matching rules][S31]. Custom Objects are documented across all plans, capped at 10 per location; object/field/record support and export formats still need account verification. [Object access and limits][S61]. Exporting contacts does not reproduce a whole account, historical inbox or every asset in another CRM.

### 3.2 Sales pipelines, lead handling and conversion

Buildable processes combine [Opportunities APIs][S32] with native CRM and workflow configuration. The deliverables below are agency-designed implementations.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| SAL01 | One sales pipeline: up to 8 stages, values, owners and board views | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| SAL02 | Three-pipeline sales process: entry/exit rules and cross-pipeline handoffs | N | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| SAL03 | Lead source capture: UTMs, 5 source rules and basic source reporting | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| SAL04 | Speed-to-lead: notifications, assignment and one acknowledgement path | N+E+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| SAL05 | Round-robin/territory lead routing: 5 reps and exception queue | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL06 | Rule-based lead scoring: 10 positive/negative signals and priority views | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL07 | Nurture sequence: 5 messages, stop conditions and one handoff path | N+E+W | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| SAL08 | Sales task/callback SLA: due dates, overdue alerts and escalation | N+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| SAL09 | Quote follow-up: estimate sent/accepted/lost states and 3 reminders | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL10 | Stale/lost deal recovery: eligibility segment and 3-touch campaign | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL11 | Appointment-to-deal automation: booking/show/no-show stage updates | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL12 | Sales team performance dashboard: 8 agreed metrics | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SAL13 | Referral/dealer lead distribution: partner fields, routing and audit trail | N+I+F | 8–20h → ₹4,000–10,000 | ₹8,000–30,000 | M3 | C |
| SAL14 | Sales commission calculation: custom rules and external payout report | X+I+H | 16–40h → ₹19,200–48,000 | ₹28,800–1,20,000 | M6 | T |

**Boundaries:** Rule-based scoring differs from metered AI evaluation. Delivery receipts and lead events must be available for SLA calculations. Commission reports do not move money or replace payroll/accounting. Partner-level row security may require separate accounts or a custom portal.

### 3.3 Websites, funnels, forms, surveys, quizzes and design assets

Native builders are listed in [core features][S01]; [Forms/Funnels/Surveys APIs][S32] cover specific operations. Custom code, graphic production and advanced optimisation are agency work.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| WEB01 | Lead form: up to 10 fields, consent field and CRM notification | N | 1–3h → ₹500–1,500 | ₹1,000–4,500 | M1 | C |
| WEB02 | Customer survey: up to 15 questions and response tagging | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| WEB03 | Qualification quiz: 10 questions, 3 result paths and lead capture | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WEB04 | Landing page: 6 sections, responsive layout, form and thank-you state | N+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| WEB05 | Business website: 5 pages, navigation, forms and mobile checks | N+D | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C |
| WEB06 | Lead funnel: 3 pages and CRM follow-up entry | N+E+W+D | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M2 | C |
| WEB07 | Sales funnel: checkout, one upsell/downsell and confirmation | N+G+D | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| WEB08 | Click-to-WhatsApp page: branded CTA, click tracking and source capture | N+W | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M1 | C |
| WEB09 | Lead magnet delivery: opt-in, file delivery and 3-email sequence | N+E | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| WEB10 | Website live-chat widget: branding, routing and office-hour message | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| WEB11 | All-in-one chat widget: eligible channels, labels and handoff links | N+W+P | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| WEB12 | Popup/banner/countdown/trigger-link campaign: 3 page placements | N | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M1 | C |
| WEB13 | A/B funnel test: one controlled variant and conversion report | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M3 | C |
| WEB14 | Blog foundation: categories, authors, template and first 2 supplied posts | N+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WEB15 | Brand Board/media library: colours, fonts, logo variants and asset folders | N+D | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| WEB16 | QR pack: 3 editable destinations for reviews, booking or lead capture | N | 1–3h → ₹500–1,500 | ₹1,000–4,500 | M1 | C |
| WEB17 | Domain connection: one domain/subdomain, DNS and SSL verification | N+D | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| WEB18 | Website migration: up to 5 pages reconstructed, redirects and forms | N+D | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M3 | C |
| WEB19 | Multilingual website: additional 5-page language version and forms | N+I+D | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M2 | C |
| WEB20 | Custom calculator/configurator embedded in a HighLevel page | X+H | 16–40h → ₹19,200–48,000 | ₹28,800–1,20,000 | M6 | T |
| WEB21 | WordPress launch/migration: 5 pages, theme and essential plugins | N+H+D | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C |
| WEB22 | WordPress care: updates, backups and monthly restore verification setup | N+H+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M3 | C |

**Boundaries:** HighLevel funnel/site hosting and WordPress hosting are different products. Translation, cookie/consent tooling, legal text, accessibility remediation and custom scripts are scoped work; none is automatically solved by publishing a page. QR artwork does not include printing, NFC hardware or a universal payment integration. Native QR booking destinations are documented for [calendars/services/rentals][S33].

### 3.4 Meetings, services, rentals and field operations

[Calendar types and Rentals][S34], [Services][S35] and [Field Services beta][S36] are different scheduling systems. The following are distinct implementations.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| CAL01 | Personal booking calendar: hours, buffers, form and calendar connection | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| CAL02 | Team round-robin calendar: 5 staff, allocation and conflict calendars | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CAL03 | Collective booking: availability intersection for 3 required team members | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CAL04 | Class/group booking: capacity, attendee form and confirmation | N+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CAL05 | Appointment reminders: confirm, 24-hour and same-day plus cancellation link | N+E+W+P | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CAL06 | No-show recovery: status checks, 2 follow-ups and rebooking | N+E+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| CAL07 | Paid booking/deposit: one gateway, fee and refund/cancellation handling | N+G | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CAL08 | Services menu: 10 services, staff, durations, variants and booking page | N+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M2 | C |
| CAL09 | Resources/rooms/equipment: 5 resources and conflict tests on eligible calendar | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CAL10 | Appointment packages/recurring visit administration: one defined booking model | N+G | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| CAL11 | Rental listings: 10 assets, stock/variants and booking page | N+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| CAL12 | Rental pricing: seasonal/duration rules, deposit, fees and tax settings | N+G | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| CAL13 | Rental external calendar connection: 3 listings, block import/export and tests | N+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CAL14 | Rental notifications: booking changes and one self-service cancellation path | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| CAL15 | Field Services foundation: service areas, 5 technicians and 10 services | B+G | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M4 | C |
| CAL16 | Field Services dispatch: requests, estimates, jobs and 2-visit scheduling | B+E+W+G | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M4 | C |
| CAL17 | Field Services field-worker setup: mobile job status, checklists and notes | B | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| CAL18 | External dispatch/job system sync: one Jobber/POS/ERP interface | I+F+H | 20–50h → ₹24,000–60,000 | ₹36,000–1,50,000 | M7 | T |

**Boundaries:** Rentals' calendar sync can be delayed; it is not a guaranteed real-time hotel channel manager. Verify fees/cancellation support in the newer specific articles rather than assuming old “upcoming” lists remain current. Field Services is **private beta**, not generally available; its forthcoming reporting, portal and Voice AI features must not be sold as delivered. Services calendars and Field Services catalogues are separate. Gateway availability differs by widget/menu. [Rentals][S34], [Field Services status][S36], [calendar payments][S25].

### 3.5 Email marketing and deliverability services

Email services combine native campaign tools with [LC Email charges][S09]. A campaign build and actual delivery are separate costs.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| EML01 | Sending-domain authentication: SPF/DKIM, DMARC review and test delivery | N+E+D | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| EML02 | Branded email template: header/footer and 3 reusable sections | N+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| EML03 | Newsletter build/send: one supplied-content campaign, one audience | N+E | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M0 | C |
| EML04 | Four newsletters/month: initial template and calendar configuration | N+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M4 | C |
| EML05 | Email welcome/nurture: 5 emails, branching and unsubscribe checks | N+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| EML06 | Transactional email: 3 event templates and tested event mapping | N+E+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| EML07 | Email list hygiene: mapping, validation and suppression, 10,000 contacts | N+E | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| EML08 | Deliverability audit: DNS, bounce/spam patterns and remediation report | N+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| EML09 | Dedicated IP enablement/warm-up plan: eligible domain and monitored ramp | N+E+R | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| EML10 | Personal inbox two-way sync: 3 eligible Google/Microsoft accounts | N+I | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M1 | C |
| EML11 | External SMTP connection: one provider and sending/reply tests | I+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M2 | C |
| EML12 | Behavioural segmentation/re-engagement: 3 segments and 3-email sequence | N+E | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| EML13 | Email design/content creation: initial style system; ongoing 4 full emails | N+E+A | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |

**Boundaries:** List size is not the billable event count. Opens are an imperfect signal; deliverability, clicks and actual conversions need separate interpretation. A new sender cannot assume full throughput on day one. Personal inbox sync, bulk sending and hosted employee mailboxes are distinct products. Bought/scraped addresses do not establish permission or inbox placement.

### 3.6 WhatsApp onboarding, campaigns, chat and calling

Use [WhatsApp billing][S11] for costs and [Flows restrictions][S37] for booking limitations. All below assume the account can be approved for the official connection.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| WAP01 | Official WhatsApp onboarding: business assets, number and connection tests | N+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| WAP02 | Business App coexistence onboarding: supported number and history checks | N+W | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |
| WAP03 | Template pack: 5 messages, variables, category/language and submission | N+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M0 | C |
| WAP04 | Broadcast campaign: clean opted-in segment, one template, schedule and report | N+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M0 | C |
| WAP05 | WhatsApp nurture: 5-message sequence with eligibility and opt-out checks | N+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| WAP06 | WhatsApp appointment/renewal reminders: 3 templates and stop conditions | N+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WAP07 | Interactive menu/buttons: one supported FAQ/routing journey | N+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WAP08 | WhatsApp Flow form: one supported in-app lead intake and field mapping | N+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| WAP09 | WhatsApp Flow booking: one eligible calendar and confirmation | N+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| WAP10 | Missed-call WhatsApp back: eligible call event to approved follow-up | N+W+P | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WAP11 | Click-to-WhatsApp ad intake: source trigger, routing and first response | N+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| WAP12 | WhatsApp AI qualification: knowledge, consent, handoff and booking link | N+W+A | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| WAP13 | WhatsApp team support desk: 5 users, ownership, labels and escalation | N+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| WAP14 | WhatsApp calling setup: eligible user/business-initiated calling and permissions | N+W | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |
| WAP15 | Multi-number/migration project: eligibility, cutover and continuity tests | N+W+I | 8–20h → ₹4,000–10,000 | ₹8,000–30,000 | M3 | C |

**Boundaries:** Number ownership/OTP, business verification, template approval, consent and quality restrictions can delay launch without reducing build effort. Unofficial QR-session blasting tools are not equivalent to the native Business Platform. Flows booking currently excludes Coexistence connections, payment-enabled calendars, recurring appointments and guest booking; custom fields are restricted. Sending the Flow can incur messaging charges. Calling country/number eligibility and permission requirements differ from messaging. [Flows][S37].

### 3.7 Unified inbox, social messaging, SMS and telephony

Capabilities are country/channel-specific. [Instagram messaging rules][S38], [phone pricing][S14] and [India restrictions][S13] control what can actually run.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| MSG01 | Unified inbox: email/social/live chat ownership and routing for 5 staff | N+E | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| MSG02 | Facebook Messenger response flow: one page, FAQs and human handoff | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| MSG03 | Instagram comment-to-DM: one trigger, private response and opt-in step | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M2 | C |
| MSG04 | Instagram inbound DM automation: 5 responses within eligible windows | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| MSG05 | TikTok lead/inbox connection: eligible business and tested message path | N+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| MSG06 | Manual actions queue: call/message tasks with ownership and completion checks | N+P+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| MSG07 | US/eligible-country SMS nurture: 5 messages and reply handling | N+P | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| MSG08 | US A2P/toll-free onboarding help: one brand/campaign and evidence pack | N+P | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |
| MSG09 | LC Phone number provisioning: eligible country, routing and test calls | N+P | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| MSG10 | India local phone beta: regulatory bundle, forwarder and domestic call tests | B+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| MSG11 | Missed-call SMS back: supported SMS-capable route and event rules | N+P | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| MSG12 | IVR/call routing: 3 branches, voicemail and business-hours handling | N+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| MSG13 | Call tracking number pool: one campaign and attribution report | N+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| MSG14 | Recording/transcription/Voice Intelligence: eligible calls, retention and QA settings | B+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| MSG15 | Dialer/SIP setup: eligible phone configuration and 5 users | N+P+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| MSG16 | External India SMS gateway: approved sender/template, delivery callback and opt-outs | I+F+H | 12–28h → ₹14,400–33,600 | ₹21,600–84,000 | M6 | T |
| MSG17 | External India telephony connector: inbound/outbound events and CRM logging | I+F+H | 20–50h → ₹24,000–60,000 | ₹36,000–1,50,000 | M7 | T |
| MSG18 | Customer-support queue: cases via pipeline/custom object, SLA and escalation | N+E+W | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C |

**Boundaries:** IVR, SMS, recording, app answering and Voice AI rows are **not available on India LC beta numbers** under the cited guide. External Indian providers must support the actual number, event and compliant route; HighLevel cannot observe an arbitrary personal-number missed call. SMS cost depends on segments/encoding, replies and carrier fees; emoji/Indian-language text can alter segmentation. TikTok is a global capability entry, not a claim of normal Indian-market availability. A CRM queue is not automatically a full helpdesk with every ticketing feature.

### 3.8 Social publishing, media and content operations

[Social Planner documentation][S39] describes the platform tools; editorial/creative production below is an agency service. Verify supported format/API restrictions per social network.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| SOC01 | Social account connections: 5 eligible profiles and permission tests | N | 2–5h → ₹1,000–2,500 | ₹2,000–7,500 | M1 | C |
| SOC02 | Publishing calendar: approval process, brand settings and 4-week structure | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M2 | C |
| SOC03 | Schedule 12 supplied posts/month: initial templates and approval flow | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M3 | C |
| SOC04 | Create 12 captions/month: brand voice setup and channel adaptation | N+A | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M4 | C |
| SOC05 | Create 12 static visuals/month: design system plus original assets | N+A+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| SOC06 | Four short-video edits/month: supplied footage, captions and exports | N+I+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| SOC07 | Content repurposing: one supplied article/video into 8 posts/month | N+A | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M4 | C |
| SOC08 | Social recurring/RSS posting: one content source and review controls | N+I | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M2 | C |
| SOC09 | Social approval/reporting: 3 reviewers and one monthly performance report | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| SOC10 | AI creative pack: 5 image/copy variants with human brand review | N+A+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M0 | C |
| SOC11 | Social comment/inbox triage workflow: routing and saved replies | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M3 | C |
| SOC12 | Blog content production: 4 researched articles/month, initial template | N+A+D | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |

**Boundaries:** Filming, professional photography, actors/voiceovers, music/stock rights and advanced video production are external costs. “Manage social media” must state post counts, channels, revision limits and human moderation hours. Scheduling software does not provide organic reach or guarantee every personal-account format can auto-publish.

### 3.9 Advertising, tracking and conversion reporting

HighLevel [Ad Manager][S07] has a $0 agency base fee and supports Meta, Google and LinkedIn with differing capabilities. Media buying, creative and analytics work remain agency deliverables.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| ADS01 | Meta lead campaign: one offer, 2 audiences, 3 supplied creatives and CRM mapping | N+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M4 | C |
| ADS02 | Click-to-WhatsApp ads: one campaign, source capture and response workflow | N+W+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M4 | C |
| ADS03 | Google Search campaign: 2 ad groups, conversion event and exclusions | N+I | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M4 | C |
| ADS04 | LinkedIn campaign: one eligible campaign type, audience and CRM mapping | N+I | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M4 | C |
| ADS05 | Retargeting implementation: 2 eligible audiences and one campaign | N+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| ADS06 | Ad creative pack: 3 concepts, copy and 6 static adaptations | N+A+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M0 | C |
| ADS07 | Pixel/GA4/GTM installation: one website, 5 events and validation | N+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| ADS08 | Server-side conversion/event sync: one ad platform and deduplication | I+F+H | 12–28h → ₹14,400–33,600 | ₹21,600–84,000 | M6 | T |
| ADS09 | Lead form connectors: Meta/LinkedIn/TikTok field mapping and duplicate rules | N+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| ADS10 | Offline sales conversion feedback: won-deal mapping and one platform | I+F | 10–24h → ₹12,000–28,800 | ₹18,000–72,000 | M6 | T |
| ADS11 | Ad dashboard: spend, leads, appointments and won revenue by source | N+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| ADS12 | Landing page conversion review: one page, 5 fixes and one test | N | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |

**Boundaries:** Ad spend is P-class client spend, not part of the management fee. Pixel consent, browser blocking, attribution windows, refunds and duplicate events affect reporting. Not every ad network's native campaign type is exposed in HighLevel; external Ads Manager work may be necessary. Percentage-of-spend management can be quoted separately, but it is a fee on client spend, not evidence of gross margin on labour.

### 3.10 Reputation, local SEO, organic SEO and prospecting

Capabilities draw on [Reputation][S40], [Listings][S04], [Search Atlas][S08] and [Prospecting][S05]. External search/content work is indicated separately.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| REP01 | Review request system: 2 templates, customer trigger and reminders | N+E+W+P | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| REP02 | Review QR + private feedback: two independent public/feedback destinations | N | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | M1 | C |
| REP03 | Review response operations: templates and routing; up to 30 replies/month | N+A | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M3 | C |
| REP04 | AI review replies: eligible Auto-Pilot/drip settings and brand escalation rules | N+A | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M2 | C |
| REP05 | Reputation reporting: competitor view and monthly review trends | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| REP06 | Video testimonial collection: request journey, consent and display setup | N+E+D | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| REP07 | Google Business Profile setup/correction: one location and eligible fields | I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| REP08 | GBP content management: 4 supplied-content posts/month and details upkeep | N+I | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M3 | C |
| REP09 | Listings activation/correction: one eligible business, NAP audit and sync | N+S | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| REP10 | Search Atlas SEO setup: site connection, crawl and keyword baseline | N+S | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| REP11 | Local SEO heatmap/audit: 3 terms, geography and report explanation | N+S | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| REP12 | On-page SEO: titles, headings, internal links and metadata on 5 pages | N+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| REP13 | Technical SEO remediation: one site's crawl/indexing/redirect issues | X+I | 12–30h → ₹14,400–36,000 | ₹21,600–90,000 | M6 | T |
| REP14 | SEO content refresh: 4 existing pages/month, initial content baseline | N+S+A | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| REP15 | Prospecting audit widget: one site embed, report and CRM handoff | N+S | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| REP16 | B2B prospect research: eligible tool configuration, 100 qualified records/month | N+S+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| REP17 | Search/AI visibility reporting using available tools or external provider | I+S | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |

**Boundaries:** GBP itself is free; the charge is for agency work. Some old help pages mention discontinued Google chat; do not include that as a live channel. Listings directories differ by country and eligibility. SEO content, outreach and paid tools are different cost centres. Section 14 now confirms a native Visibility AI remote/route from frontend source. Its live entitlement and tariff remain unresolved: AUD09 covers conditional native onboarding, while the last row here remains external/available-tool reporting. Do not gate public review requests by satisfaction or guarantee rankings.

### 3.11 Retention, repeat business, loyalty and customer journeys

These are buildable CRM/automation solutions. HighLevel’s full [Loyalty & Referral product is private beta][S41]; ordinary tagged workflows are a different implementation.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| RET01 | Birthday/anniversary journey: consent, date logic and one offer | N+E+W | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| RET02 | Repeat-purchase/refill reminder: one product interval and stop conditions | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| RET03 | Renewal journey: 3 reminder intervals, status update and payment link | N+E+W+G | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| RET04 | Customer win-back campaign: segment, 3 messages and outcome tracking | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| RET05 | Post-purchase cross-sell: one eligibility rule and 3 messages | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| RET06 | NPS/CSAT programme: one survey, follow-up tasks and trend dashboard | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| RET07 | Customer onboarding: intake, checklist, welcome messages and handoff | N+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| RET08 | Complaint/service recovery: case stages, escalation and closure survey | N+E+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C |
| RET09 | Basic referral tracking: referrer field, lead attribution and manual reward report | N | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| RET10 | Simple visit-count loyalty: tagged counters, eligibility and staff approval | N+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| RET11 | Native Loyalty & Referral: one rewards programme, earning and redemption rules | B+G | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| RET12 | Native wallet membership/scanner setup: eligible Apple/Google Wallet and staff roles | B+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| RET13 | External loyalty/POS sync: transactions, balances and reconciliation | I+H+F | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M7 | T |

**Boundaries:** Reward face value, discounts, free goods, fraud/reversals and fulfilment are merchant costs. A workflow counter is not a transaction-safe loyalty ledger. Native beta access and scanner rollout vary; no verified standalone public subscription rate was found, so beta licence/usage cost is unresolved. Affiliate sales commissions and customer loyalty rewards are distinct products.

### 3.12 Estimates, documents, invoices and payment administration

[Payment support][S22], [Razorpay][S23], [invoice APIs][S32] and [Documents & Contracts][S42] define the supported surfaces. These are operations/automation services, not accounting or legal certification.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| PAY01 | Gateway onboarding: one eligible provider, webhooks, domain and live test | N+G | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| PAY02 | Product/price catalogue: 20 items, recurring/one-time prices and tax fields | N+G | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| PAY03 | Payment link/checkout: 3 offers, confirmation and CRM record | N+G | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| PAY04 | Invoice template/workflow: brand, line items, reminders and paid-state actions | N+G+E | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| PAY05 | Recurring invoicing: one schedule, eligible payment method and failure path | N+G+E | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| PAY06 | Estimate/quote system: 3 templates, approval and conversion to invoice | N+G+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| PAY07 | Proposal/contract template: supplied terms, signatures and completion workflow | N+E+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| PAY08 | Multi-recipient document process: signing order and internal notification | N+E | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| PAY09 | Payment-plan/deposit workflow: staged amount, reminders and status tracking | N+G | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| PAY10 | Failed-payment/dunning sequence: 3 retries/reminders within gateway support | N+G+E+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| PAY11 | Refund/dispute administration: approval routing, records and reconciliation report | N+G | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M3 | C |
| PAY12 | Subscription change/cancellation journey: supported provider events and access changes | N+G | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| PAY13 | Payment reconciliation dashboard: invoices versus transactions and exceptions | N+G+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| PAY14 | India accounting/GST export bridge: one Zoho Books/Tally/ERP destination | I+F+H | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M7 | T |
| PAY15 | Supported POS/Tap-to-Pay enablement: eligible country/device/provider | N+G+I | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |

**Boundaries:** Gateway acceptance, fixed-schedule subscription, off-session charge and recurring invoice are different capabilities. A HighLevel invoice is not proof of GST e-invoicing/IRN, statutory return filing or compliant accounting treatment. E-sign workflows do not certify every document's enforceability. Card-reader hardware, supported country/device, merchant onboarding and return/refund fees are external dependencies.

### 3.13 Ecommerce, orders, fulfilment and gift cards

Native commerce combines [Products/Store APIs][S32], connected stores and [Gift Cards][S43]. Warehousing and logistics require external systems.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| COM01 | Native store: up to 20 products, collections, variants and checkout | N+G+D | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M3 | C |
| COM02 | Product catalogue import: 100 clean SKUs, variants and images | N+I | 8–20h → ₹4,000–10,000 | ₹8,000–30,000 | M2 | C |
| COM03 | Store promotions: 3 coupons/discount rules and seasonal collection | N+G | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| COM04 | Order lifecycle automation: confirmation, fulfilment status and customer alerts | N+E+W+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| COM05 | Abandoned checkout recovery: identified contacts, 3 reminders and stop rules | N+E+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| COM06 | Post-purchase journey: review, upsell and reorder rules for one product family | N+E+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| COM07 | Shipping/tax setup: one country and supported rate/tax approach | N+G+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| COM08 | Shopify connection: field/event mapping and 5 tested order scenarios | N+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| COM09 | WooCommerce/custom store sync: order/contact mapping and retry handling | I+F+H | 20–50h → ₹24,000–60,000 | ₹36,000–1,50,000 | M7 | T |
| COM10 | Inventory/POS connector: stock source, order sync and reconciliation | I+F+H | 32–80h → ₹38,400–96,000 | ₹57,600–2,40,000 | M7 | T |
| COM11 | Gift card programme: denominations, artwork, terms and sale/redemption tests | N+G | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| COM12 | Gift card campaigns: issue/delivery rules and balance/reconciliation report | N+G+E | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| COM13 | Returns/RMA process: intake, approval stages and external fulfilment handoff | N+I+E | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| COM14 | Digital product delivery: one paid offer, access entitlement and download journey | N+G+E | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| COM15 | Ecommerce analytics: order/repeat/recovery dashboard, 8 metrics | N+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |

**Boundaries:** HighLevel store inventory is not automatically an ERP, marketplace multivendor ledger or warehouse system. Anonymous browsing cannot become a recoverable contact without an identifier/eligible event. Gift-card face value is a merchant liability, not agency revenue; confirm eligible checkout/provider and partial-balance/refund behaviour. Shipping, returns, COD collections and products are P-class spend. Shopify's subscription/apps and any middleware remain additional.

### 3.14 Courses, communities, webinars, events and client portals

[Membership/course documentation][S44], [Communities][S45] and [Client Portal][S46] supply native building blocks. Content development and moderation are separate services.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| EDU01 | Course portal: 1 course, 20 supplied lessons, branding and access tests | N+G | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M2 | C |
| EDU02 | Course drip/progression: 4 modules, release rules and completion journey | N+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| EDU03 | Quiz/certificate setup: eligible assessment, pass rules and certificate template | N | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M1 | C |
| EDU04 | Paid course offer: checkout, enrolment, expiry and refund/access rules | N+G+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| EDU05 | Community launch: 1 group, 5 channels, permissions and onboarding | N | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| EDU06 | Paid community: eligible payment, access tiers and renewal communications | N+G+E | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| EDU07 | Community moderation system: guidelines, routing and 8–16 hours/month | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| EDU08 | Community event: registration, reminders and follow-up content | N+E+W | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M2 | C |
| EDU09 | Recorded/evergreen webinar funnel: registration, video and follow-up | N+E+D | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C |
| EDU10 | Live webinar integration: external meeting platform, attendance and follow-up | I+E+F | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| EDU11 | Client Portal branding: domain, navigation, files and member login | N+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| EDU12 | Client file/document access: folders, sharing and permission checks | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| EDU13 | Branded Client Portal mobile app: eligible add-on and submission assets | N+R+D | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| EDU14 | Course/community migration: 50 supplied lessons and member access mapping | N+I | 24–60h → ₹12,000–30,000 | ₹24,000–90,000 | M3 | C |
| EDU15 | Learning content creation: 5 original lessons, scripts and simple assets | N+A+D | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M0 | C |
| EDU16 | Event registration/ticket journey: form/checkout, attendee data and reminders | N+G+E | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |

**Boundaries:** A registration funnel/video player is separate from live conferencing. Native Meeting Room/Community Live Room scopes are now covered under AUD10–AUD12; external Zoom/Meet licences apply only when selected. Native course/video functions do not guarantee SCORM/xAPI, proctored examinations, university SIS or accredited certification. Reselling the member app is not the same as the white-label CRM mobile app or the new Client App Builder. External store/Apple/Google accounts, approvals and charges apply only to the app product that actually requires them.

### 3.15 Affiliate programmes and partner administration

The client-facing Affiliate Manager is distinct from HighLevel’s own agency referral programme. See [Affiliate Manager API][S32].

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| AFF01 | Affiliate programme: one campaign, attribution window, products and rates | N+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M2 | C |
| AFF02 | Affiliate onboarding portal: signup, approval, materials and notifications | N+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| AFF03 | Affiliate commission rules: 3 tiers/products and reversal handling | N+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| AFF04 | Affiliate reporting/payout preparation: one monthly statement process | N+I | 5–10h → ₹2,500–5,000 | ₹5,000–15,000 | M3 | C |
| AFF05 | External affiliate-event/postback integration: one external source | I+F+H | 12–28h → ₹14,400–33,600 | ₹21,600–84,000 | M6 | T |
| AFF06 | Dealer/ambassador programme: partner data, lead ownership and reward report | N+I | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C |

**Boundaries:** Client affiliate commissions and payout processing are P-class merchant costs. Advertised affiliate commission rates are not agency service margins. Attribution can differ across domains, devices, refunds and privacy settings; specify the system of record and approval process.

### 3.16 AI conversations, voice, knowledge, agents and creative assistants

Customer-facing bots, builder assistants and autonomous agents have different billing. [AI pricing][S20], [knowledge-base tools][S47], [Flow Agent documentation][S48] and [Managed Agent connectors][S49] define the underlying products.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| AI01 | Knowledge base: crawl/import up to 30 supplied pages/docs and organise topics | N+A | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| AI02 | Knowledge-base maintenance: refresh rules, gap review and test-question set | N+A | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M3 | C |
| AI03 | Website Conversation AI: FAQ, 20 test questions, handoff and lead capture | N+A | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| AI04 | Multichannel AI qualification: 3 channels, shared fields and handoff logic | N+A+W+E | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M4 | C |
| AI05 | AI appointment assistant: eligible calendar search, booking and exceptions | N+A | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| AI06 | AI support triage: classify issue, consult knowledge and create human case | N+A | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M4 | C |
| AI07 | AI product recommendation: 20 supplied products and qualification rules | N+A+G | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M4 | C |
| AI08 | AI receptionist: eligible non-India-LC-beta number, greeting and escalation | N+A+P | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M4 | C |
| AI09 | AI outbound follow-up: eligible route, consent and callback outcomes | N+A+P | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M4 | C |
| AI10 | Voice AI web widget: microphone journey, knowledge and handoff tests | N+A | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| AI11 | Voice prompt/language QA: one language/accent and 30 test conversations | N+A+P | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C |
| AI12 | AI review reply implementation: tone, approval and escalation settings | N+A | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| AI13 | AI workflow classification/summarisation: one structured output and validation | N+A+F | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| AI14 | Flow Agent: one multistep business task with 3 tools and failure handling | N+A+I | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M6 | T |
| AI15 | Managed Agent: one bounded task, trigger/schedule and permitted tools | N+A+I | 16–40h → ₹19,200–48,000 | ₹28,800–1,20,000 | M6 | T |
| AI16 | Ask AI projects/skills setup: business context and 3 repeatable instructions | N+A | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| AI17 | Creator/Content AI production setup: brand references and 5 reusable prompts | N+A+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| AI18 | External AI agent integration: custom model/runtime and CRM event bridge | X+I+A+F+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| AI19 | AI evaluation/handoff audit: 50 scenarios, error review and remediation list | N+A | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C |

**Boundaries:** AI minutes, tokens, agent runs, WhatsApp delivery, phone legs and premium actions can coexist. Evaluate booking/cancellation/refund actions, escalation and language accuracy rather than promising reliable autonomous operation in every case. No Indian LC beta Voice AI entitlement is implied. Human call-centre staffing is separate. Managed Agents and Flow Agents are not the same product; plan allowance for one cannot be assumed for the other.

### 3.17 Custom apps, AI Studio, Client App Builder and MCP experiences

[AI Studio][S50] supports custom app work with separate [Cloud billing][S21]. [Client App Builder][S51] is a newer Labs product with a narrower portal/Android scope. External MCP UI work is a custom implementation, not a generally included HighLevel view.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| APP01 | AI Studio brochure/microsite: 5 pages, lead form and CRM connection | N+A+D | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C |
| APP02 | AI Studio interactive tool: calculator/quiz, 3 screens and lead storage | X+A+H | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M6 | T |
| APP03 | AI Studio portal: login, 3 record views and file upload | X+A+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| APP04 | AI Studio business app: custom database, roles and one business workflow | X+A+H+I | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| APP05 | AI Studio Cloud provisioning: tier, storage, access and spend visibility | N+A+H | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| APP06 | Client App Builder web portal: 5 screens using supported HighLevel modules | B+A+D | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M3 | C |
| APP07 | Client App Builder Android APK: branding, navigation and device tests | B+A+D | 24–48h → ₹12,000–24,000 | ₹24,000–72,000 | M4 | C |
| APP08 | Client App Builder custom-object views: one data entity and permitted actions | B+A | 12–28h → ₹6,000–14,000 | ₹12,000–42,000 | M3 | C |
| APP09 | External customer/partner portal: custom UI, HighLevel auth/data and roles | X+I+H | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| APP10 | MCP connector installation: authorised user, location, scopes and smoke tests | N+I+A | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| APP11 | Custom CRM MCP server: bounded tools, auth, tenancy and audit logs | X+I+H+A | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| APP12 | MCP contact workspace/pipeline/calendar view: one supported-host UI | X+I+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| APP13 | Agent execution/status interface: backend state and supported host rendering | X+I+H+A | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| APP14 | Custom payment provider/app: provider adapter, webhooks and reconciliation | X+I+G+H | 100–240h → ₹1,20,000–2,88,000 | ₹1,80,000–7,20,000 | M7 | T |

**Boundaries:** Client App Builder currently supports browser apps/Android APK, not iOS or app-store publishing. Its guide limits apps/domains and excludes arbitrary server code, databases, npm packages and custom checkout; use supported HighLevel invoice flows. AI Studio Cloud is a different backend product. Public API existence does not imply full builder automation. MCP host rendering and action permissions must be proven. The supplied selective-UI documents describe proposed work, not shipped connector features. [Client App Builder limits][S51], [public MCP][S52].

### 3.18 Workflows, integrations, migration and reliability

Use [public API authentication][S53], [rate limits][S54] and the exact [endpoint contracts][S32]. No blanket “all UI actions via API” entitlement is assumed.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| INT01 | Standard workflow: one trigger, up to 10 ordinary steps and one branch | N+E+W | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M1 | C |
| INT02 | Advanced workflow: up to 30 steps, 5 branches and re-entry/stop rules | N+F+E+W | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C |
| INT03 | Premium workflow setup: cost mapping, test executions and rebilling config | N+F | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C |
| INT04 | Inbound/outbound webhook: one event/payload and basic failure handling | I+F+H | 8–20h → ₹9,600–24,000 | ₹14,400–60,000 | M6 | T |
| INT05 | Google Sheets sync: 1 sheet, 10 fields and duplicate prevention | N+I+F | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| INT06 | Make/Zapier/n8n automation: one 5-step external flow and alerts | I+F+H | 12–28h → ₹14,400–33,600 | ₹21,600–84,000 | M6 | T |
| INT07 | Two-way CRM sync: one object, identity rules, conflicts and retries | I+F+H | 32–80h → ₹38,400–96,000 | ₹57,600–2,40,000 | M7 | T |
| INT08 | ERP/POS/accounting integration: 3 entity types and reconciliation | I+F+H | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| INT09 | OAuth private/Marketplace app: installation, refresh and location permissions | X+I+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| INT10 | Workflow audit: 10 existing workflows, loops, cost and failure review | N+F | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M0 | C |
| INT11 | Integration reliability: retry/dead-letter queue, alerts and replay tooling | X+I+H | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M7 | T |
| INT12 | API data export/backup job: 3 entity types, storage and restore sample | X+I+H | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M6 | T |
| INT13 | Cross-location reporting/warehouse feed: 5 locations and incremental sync | X+I+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| INT14 | Legacy migration: 50k records, 3 entities and 10 rebuilt automations | X+I+H | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| INT15 | Connector version upgrade: auth/API changes and regression scenarios | X+I+H | 16–40h → ₹19,200–48,000 | ₹28,800–1,20,000 | M6 | T |
| INT16 | Customer data deletion/retention workflow: supported stores and evidence report | N+I+H | 12–30h → ₹14,400–36,000 | ₹21,600–90,000 | M6 | T |

**Boundaries:** The documented OAuth API limits are 100 requests/10 seconds and 200,000/day per app per location/agency resource; endpoint/contract exceptions and current headers matter. API traffic itself is not universally a premium workflow action, but a workflow calling an external service may be billable. Retries, polling and large backfills add provider/runtime usage. Scheduled exports require separate restore testing and do not guarantee complete disaster recovery. [Rate limits][S54].

### 3.19 Reporting, project management and operating services

[Reporting][S55] provides native dashboards. [Project Management][S56] is Founder/$497 and Labs-gated; basic CRM tasks are a separate capability.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| OPS01 | Native dashboard: 10 widgets, agreed definitions and access views | N | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| OPS02 | Scheduled report: one template, 3 recipients and delivery cadence | N+E | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| OPS03 | Call/appointment funnel reporting: 8 metrics and reconciliation checks | N+P | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| OPS04 | Revenue/attribution report: lead sources, won deals and paid revenue | N+G+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| OPS05 | External BI dashboard: one data source and 3 pages in external BI tool | I+H | 24–60h → ₹28,800–72,000 | ₹43,200–1,80,000 | M6 | T |
| OPS06 | Multi-location executive reporting: 5 location feeds and common metrics | X+I+H | 40–100h → ₹48,000–1,20,000 | ₹72,000–3,00,000 | M7 | T |
| OPS07 | Basic CRM tasks: due dates, reminders, repeat tasks and assignees | N | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | M1 | C |
| OPS08 | Project Management foundation: 2 Spaces, 5 Lists and status schema | B | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M2 | C |
| OPS09 | Client onboarding project template: 20 tasks, subtasks and record links | B | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| OPS10 | Project custom fields/permissions: 10 fields, private Space and member tests | B | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| OPS11 | Project automation/API integration: one external task source and mappings | B+I+H | 20–50h → ₹24,000–60,000 | ₹36,000–1,50,000 | M6 | T |
| OPS12 | Staff training: one 2-hour session, preparation and recording | N | 4–6h → ₹2,000–3,000 | ₹4,000–9,000 | M0 | C |
| OPS13 | System documentation: 10 workflows, credentials-owner map and runbook | N | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M0 | C |
| OPS14 | Monthly account administration: baseline audit and 8–16 delivery hours | N | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M5 | C |
| OPS15 | Support desk setup: ticket intake, triage, knowledge and client communications | N+I+E | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M4 | C |
| OPS16 | Account offboarding: export, cancellation inventory and access removal | N+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M0 | C |

**Boundaries:** A support M-band buys the stated hours, not round-the-clock staffing. Project Management does not automatically provide payroll, timesheet billing or every external project tool feature. API automation requires the right project scopes and access. A report's historical data depends on what was captured; attribution cannot reconstruct identifiers that were never stored.

### 3.20 White-label SaaS, snapshots, agency administration and resale

Agency-level implementations use [SaaS and Snapshots APIs][S32], [SaaS billing rules][S03] and each product’s resale terms. Platform and add-on subscriptions are recurring dependencies.

| ID | Service / bounded deliverable | Delivery + vendor costs | Setup effort → your labour cost | Indicative setup fee | Monthly work | Labour markup |
|---|---|---|---:|---:|---|---|
| SAS01 | Agency foundation/white-label desktop: domain, brand, menus and support links | N+D | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M2 | C |
| SAS02 | SaaS configurator: 3 plans, entitlements, checkout and provisioning tests | N+G | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C |
| SAS03 | Usage rebilling: 5 cost categories, wallet setup and billing reconciliation | N+G+E+P+A | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| SAS04 | Client sub-account provisioning: snapshot, users, domain checklist and handover | N+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| SAS05 | Snapshot creation: 10 workflows, fields, funnel and reusable settings | N+D | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M2 | C |
| SAS06 | Snapshot deployment/update: dependency checks and one client acceptance pass | N+D | 4–10h → ₹2,000–5,000 | ₹4,000–15,000 | M2 | C |
| SAS07 | Snapshot/template commercial packaging: documentation, licensing and install guide | N+I | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M2 | C |
| SAS08 | Marketplace app resale/onboarding: one licensed app, entitlements and support map | N+I+R | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C |
| SAS09 | White-label CRM mobile app rollout: agency add-on, brand assets and release checks | N+R+D | 24–48h → ₹12,000–24,000 | ₹24,000–72,000 | M4 | C |
| SAS10 | Multi-branch provisioning: 5 locations, shared conventions and permissions | N+R | 30–60h → ₹15,000–30,000 | ₹30,000–90,000 | M4 | C |
| SAS11 | Client billing operations: dunning, add-on inventory and monthly reconciliation | N+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C |
| SAS12 | Account ownership/agency transfer: eligible assets, access and cutover checks | N+I | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M0 | C |
| SAS13 | Reseller partner/dealer portal: custom access, provision requests and reporting | X+I+H | 60–160h → ₹72,000–1,92,000 | ₹1,08,000–4,80,000 | M7 | T |
| SAS14 | HIPAA-enabled deployment configuration: eligible account, access and workflow audit | N+R+I | 24–60h → ₹12,000–30,000 | ₹24,000–90,000 | M4 | C |

**Boundaries:** Founder/SaaS features and payment-provider eligibility must exist before selling automatic provisioning/rebilling. A snapshot is reusable configuration, not live customer data or an account clone; credentials, subscriptions, domains and certain assets require separate setup. “Your own SaaS” remains dependent on HighLevel's platform and terms. Regulatory review, legal documents, specialised security testing and full compliance certification are separate professional services. The HIPAA add-on is account-wide and documented as non-deactivatable. [Billing guide][S02].

## 4. Complete solution assemblies

The following are **reference implementations**, not recommended agency packages. They show how components become sellable business systems. Costs and quotes are estimates; no outcome/ROI is guaranteed.

Each solution assumes one location, ordinary client data/content, one primary channel and the bounded scope below. **Its integrated build replaces overlapping standalone setup lines**; do not add every component's setup fee again. Monthly M-bands cover combined management only. Add platform allocation, the indicated vendor subscriptions and actual consumption to obtain full cost. Expand M-bands from section 1.4. C/T markup applies to build labour, V/U to vendor lines.

| ID / solution scope | Component references | Vendor/deployment costs | Build hours → labour cost | Indicative setup fee | Monthly managed work | Build markup |
|---|---|---|---:|---:|---|---|
| SOL01 — Local lead-to-appointment system: 1 pipeline, 1 page, 1 calendar, 3 follow-ups | CRM01, SAL01, WEB04, CAL01, SAL07 | N+E+W | 24–40h → ₹12,000–20,000 | ₹24,000–60,000 | M3 | C |
| SOL02 — Salon/spa operating system: 10-service menu, 5 staff, reminders, reviews and return visits | CAL08, WAP06, REP01, RET02 | N+W+G | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL03 — Gym/studio member journey: trial intake, classes, conversion and renewal reminders | CAL04, SAL01, RET03, PAY05 | N+E+W+G | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL04 — Coaching/admissions CRM: application, 2 pipelines, counsellor assignment and fee follow-up | WEB01, SAL02, SAL05, PAY04 | N+E+W+G | 32–56h → ₹16,000–28,000 | ₹32,000–84,000 | M4 | C |
| SOL05 — Clinic front desk: intake, appointments, reminders, follow-up tasks and reviews | CRM01, CAL01, CAL05, REP01 | N+E+W | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL06 — Real-estate sales CRM: property object, buyer links, allocation, site visits and broker report | CRM08, CRM09, SAL05, CAL01 | N+E+W | 40–72h → ₹20,000–36,000 | ₹40,000–1,08,000 | M4 | C |
| SOL07 — Restaurant customer engagement: booking enquiry, menu page, reviews and opted-in repeat offers | WEB04, CAL01, REP02, RET01 | N+E+W | 24–40h → ₹12,000–20,000 | ₹24,000–60,000 | M3 | C |
| SOL08 — Home-services enquiry-to-job: intake, quote, calendar, invoice and review; ordinary CRM version | SAL01, PAY06, CAL01, PAY04, REP01 | N+E+W+G | 36–60h → ₹18,000–30,000 | ₹36,000–90,000 | M4 | C |
| SOL09 — Field-service dispatch: beta job lifecycle, 5 technicians and 10 services | CAL15, CAL16, CAL17 | B+E+W+G | 48–80h → ₹24,000–40,000 | ₹48,000–1,20,000 | M4 | C |
| SOL10 — Rental business: 10 assets, price rules, deposit, external blocks and notifications | CAL11, CAL12, CAL13, CAL14 | N+E+W+G | 32–56h → ₹16,000–28,000 | ₹32,000–84,000 | M3 | C |
| SOL11 — Ecommerce recovery/retention: one store, identified checkout recovery and repeat campaigns | COM05, COM06, COM08 | N+I+E+W | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL12 — D2C store operations: 20-product storefront, order alerts, gift cards and reporting | COM01, COM04, COM11, COM15 | N+E+G+I | 48–80h → ₹24,000–40,000 | ₹48,000–1,20,000 | M4 | C |
| SOL13 — Consultant/coach client system: booking, paid offer, onboarding and file portal | CAL07, PAY03, RET07, EDU11 | N+E+G | 32–56h → ₹16,000–28,000 | ₹32,000–84,000 | M3 | C |
| SOL14 — Course business: 20 lessons, drip, paid enrolment, community and certificates | EDU01, EDU02, EDU03, EDU04, EDU05 | N+E+G | 48–80h → ₹24,000–40,000 | ₹48,000–1,20,000 | M4 | C |
| SOL15 — Paid membership community: access tier, onboarding, events, renewal and moderation setup | EDU05, EDU06, EDU08, RET03 | N+E+G | 36–60h → ₹18,000–30,000 | ₹36,000–90,000 | M4 | C |
| SOL16 — Event/webinar system: registration, payment, external live session and follow-up | EDU09, EDU10, EDU16 | N+I+E+W+G | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL17 — Automotive dealer/service CRM: vehicle object, enquiry routing, test drive and service reminders | CRM08, SAL05, CAL01, RET02 | N+E+W | 36–60h → ₹18,000–30,000 | ₹36,000–90,000 | M4 | C |
| SOL18 — Insurance/financial-adviser CRM: policy object, renewal tasks, documents and appointment flow | CRM08, RET03, PAY07, CAL01 | N+E+W | 36–60h → ₹18,000–30,000 | ₹36,000–90,000 | M4 | C |
| SOL19 — Recruitment pipeline: candidate intake, jobs object, interviews and status communications | CRM08, SAL02, CAL03, EML05 | N+E | 40–72h → ₹20,000–36,000 | ₹40,000–1,08,000 | M4 | C |
| SOL20 — B2B distributor CRM: company contacts, quote approvals, follow-up and dealer reporting | CRM06, PAY06, SAL13, OPS04 | N+E+I | 40–72h → ₹20,000–36,000 | ₹40,000–1,08,000 | M4 | C |
| SOL21 — Customer support desk: email/WhatsApp routing, case queue, knowledge and CSAT | MSG01, MSG18, AI01, RET06 | N+E+W+A | 40–72h → ₹20,000–36,000 | ₹40,000–1,08,000 | M4 | C |
| SOL22 — AI lead desk: website/WhatsApp qualification, eligible calendar, human handoff and QA | AI04, AI05, WAP12, AI19 | N+W+A | 48–80h → ₹24,000–40,000 | ₹48,000–1,20,000 | M4 | C |
| SOL23 — Voice receptionist for eligible overseas market: knowledge, phone route, booking and escalation | AI08, AI05, MSG09 | N+A+P | 40–72h → ₹20,000–36,000 | ₹40,000–1,08,000 | M4 | C |
| SOL24 — India receptionist via external voice provider: provider bridge, CRM events and booking | MSG17, AI18, CAL01 | I+A+H+F | 80–160h → ₹96,000–1,92,000 | ₹1,44,000–4,80,000 | M7 | T |
| SOL25 — Loyalty/referral system: eligible native beta, rewards, member wallet and staff setup | RET11, RET12 | B+G+I | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL26 — Franchise network: 5 isolated locations, templates, permissions and consolidated reporting | SAS10, SAS05, OPS06 | X+I+H+R | 100–200h → ₹1,20,000–2,40,000 | ₹1,80,000–6,00,000 | M7 | T |
| SOL27 — White-label CRM SaaS: 3 plans, snapshot, provisioning, rebilling and support operations | SAS01, SAS02, SAS03, SAS05, SAS11 | N+G+R | 72–120h → ₹36,000–60,000 | ₹72,000–1,80,000 | M5 | C |
| SOL28 — Agency delivery workspace: project Spaces, onboarding templates, CRM links and reporting | OPS08, OPS09, OPS10, OPS01 | B | 28–48h → ₹14,000–24,000 | ₹28,000–72,000 | M3 | C |
| SOL29 — Custom customer/partner portal: role-based records, files, appointment and payment links | APP09, CRM08, PAY03 | X+I+H+G | 100–240h → ₹1,20,000–2,88,000 | ₹1,80,000–7,20,000 | M7 | T |
| SOL30 — AI Studio internal business app: auth, 3 record types, 5 screens and one workflow | APP04, APP05, INT04 | X+A+H+I | 100–240h → ₹1,20,000–2,88,000 | ₹1,80,000–7,20,000 | M7 | T |
| SOL31 — Client App Builder member app: 5-screen web portal and Android APK using existing content | APP06, APP07, EDU11 | B+A+D | 48–80h → ₹24,000–40,000 | ₹48,000–1,20,000 | M4 | C |
| SOL32 — CRM-to-ERP integration: 3 object types, retries, exception dashboard and handover | INT08, INT11, PAY14 | X+I+H+F | 100–240h → ₹1,20,000–2,88,000 | ₹1,80,000–7,20,000 | M7 | T |

**Industry exceptions:** Clinic workflows above cover front-desk CRM, not electronic medical records or a proven healthcare-compliance deployment. Admissions workflows are not an accredited LMS/SIS. Recruitment is an agency-built CRM process, not a claimed native full ATS. Financial-service workflows do not provide advice, underwriting or regulatory approval. Restaurant engagement is deliverable through ordinary modules. Section 14 additionally captures the source-confirmed restricted Restaurants product under AUD03–AUD08; its public availability and commercial tariff still require confirmation.

For any further industry, map its customer/asset records, intake, state transitions, communications, appointments, documents, payments, fulfilment and reporting to the components above. Estimate only the additional complexity. Bespoke inventory, ledger, medical, payroll or operational systems require explicit external components where native functionality is insufficient.

## 5. Special billing and delivery cases

### 5.1 Cases that change the actual bill

| Case | What changes | Cost/reference treatment |
|---|---|---|
| Several branches in one account | Shared objects/users/billing and imperfect isolation | Additional configuration, permissions and reporting labour; not automatically another vendor subscription |
| Separate branch sub-accounts | Independent users/configuration and add-on instances | Allocate platform across locations; multiply per-location add-ons, not agency-wide overhead |
| One business with several WhatsApp numbers | Number eligibility, traffic and free allowances can differ | Confirm number capacity and subscription scope; service-message allowance in guide is per number |
| Marketing inside WhatsApp's 24-hour window | Messaging permission window is not an automatic marketing discount | Category/destination tariff still matters; Free Entry Point exception evaluated separately |
| Booking Flows over WhatsApp | Sending and supporting automation can both be metered | Booking UI does not make template/channel charges disappear; payment-enabled calendar restrictions apply |
| Number/WhatsApp migration | OTP, previous BSP obligations, downtime and history limits | Separate cutover labour, existing-provider cancellation and overlap charges |
| Long or multilingual SMS | Unicode and concatenation alter segment count | Price message segments, not visible chats or recipient count; US rates do not price Indian DLT routes |
| Calls forwarded or transferred | Multiple legs, destinations and rounding | Sum actual leg charges; do not multiply a single advertised child-leg rate by minutes and call it total |
| Call recording retained for months | Storage is recurring, not a one-time processing fee | Recording minutes × retention months × storage rate; add transcription only if used |
| AI voice plus WhatsApp follow-up | Multiple charge types in one customer interaction | AI + phone + message + premium execution; included AI does not absorb the rest |
| Agent event loop, retry or repeated trigger | More runs/actions/tokens than business outcomes | Bill underlying usage with deduplication/re-entry rules; one sale can produce many billable events |
| Premium workflow with four charged steps | Four actions per contact rather than one “workflow” | Contacts × premium steps × eligible runs, plus extra API/model/marketplace charges |
| Email forwarding/CC/BCC | Extra recipients/events | Do not estimate from outbound campaign-recipient count alone |
| Cold/new sending domain | Ramp-up and provider risk controls | Extra monitoring/warm-up labour and staged delivery; no guaranteed instant high-volume send |
| Fixed-unit AI client billing | Client pays a fixed per-message/minute rate while agency cost varies | Compute actual spread per period; the configured rate replaces percentage markup for that client event [fixed-rate rules][S60] |
| Model or voice-provider change | Token and per-minute rates change | Price selected model/provider and context; do not preserve old cents-per-message promise |
| Plan allowance exhausted | May pause or create overages depending on product/settings | AI Extra Usage and Workflow Pro overages behave differently; record the selected behaviour |
| App hosting paused | Storage can continue despite no compute | AI Studio database/file charges persist; removing Cloud deletes data |
| Client stops using the service | Paid number, IP, add-on or location subscription may continue | Cancel each actual vendor item; stopping workflows is not cancellation |
| Account/agency transfer | Some assets, subscriptions and compliance records may not transfer | New provider approvals, reconfiguration and overlap bills may be needed |
| Prepaid client wallet | Cash received is not earned gross profit immediately | Reconcile provider consumption, credit liability, collection fees and refunds |
| Failed client card/recharge | Agency may already have funded usage | Bad debt/collection exposure is an agency cost; auto-recharge is not a spend cap |
| Annual vendor subscription, monthly customer billing | Different cash and cancellation timing | Allocate amortised cost, but retain actual annual cash commitment and refund terms |
| Introductory vendor discount | Renewal may be higher | Document introductory and renewal cost separately; margin on a temporary discount is temporary |
| India and overseas clients mixed | Different number, gateway, channel and tax rules | Use destination and merchant account facts, not the agency's headquarters alone |
| Affiliate/gift/loyalty cash flows | Customer value or merchant liability passes through | Keep gross funds/face value outside agency service revenue; reward fulfilment is additional |
| Full-time human operations requested | Software access does not deliver staffing | Cost actual operator hours/shifts, supervision and external contact-centre charges |

### 5.2 Access, evidence and unresolved-price register

| Product/capability | Verified or unresolved state on 31 October 2026 | Quoting consequence |
|---|---|---|
| India LC numbers | Beta; documented restrictions | Gate provisioning on approved access and country-specific checks; unsupported voice/SMS features require another solution |
| Native Loyalty & Referral | Private beta; scanner availability varies | Confirm access and commercial price; do not describe beta licensing as ₹0 |
| Field Services | Private beta, with planned functionality still unavailable | Confirm feature-by-feature fit; recurring vendor rate not established in reviewed public sources |
| Rentals | Documented enablement; some older articles retain beta/upcoming wording | Test the account and newer specific features; no separate tariff found does not certify permanent free access |
| Project Management | $497 agency tier and Labs toggle | Include Founder platform cost; ordinary CRM tasks do not establish access to the full workspace |
| Voice Intelligence | Labs; eligible recorded LC calls | Standard recording/transcription costs; not a workaround for unsupported India recording |
| Client App Builder | Sub-account Labs; web and Android scope | No separately verified complete tariff; account checkout/AI use applies; no iOS/store-publishing promise |
| AI Studio Cloud | Specific Tiny/Mini rate card differs from generic Nano/Micro wording | Use product-specific rates and actual selected tier |
| WhatsApp India rate | October CSV differs from body; 5% layer unclear | Preserve rate basis; confirm wallet before fixed-price usage commitments |
| WhatsApp authentication | Not present in reviewed India CSV columns | Obtain exact supported category price; utility is not a substitute tariff |
| Restaurants native vertical product | Frontend remote/routes and industry/SaaS access guard confirmed in section 14; public entitlement/API/rate remain unresolved | Ordinary CRM/website scopes remain offerable; AUD03–AUD08 price conditional native/custom implementation, with Q for native charges |
| Native Visibility AI / Vibe / Creator variants | Frontend apps/routes confirmed in section 14; branding, live access, quotas and price can differ | AUD09/AUD24 and APP scopes retain account verification; source presence is not an included licence |
| Internal hosted-operation registry | 741 operations across 43 domains before session scope filtering | Coverage evidence only; neither a commercial licence nor proof every customer can invoke every operation |
| Proposed MCP Apps/selective UI | Internal design documents are proposals | Engineering quote required; do not market proposed UI as a shipped HighLevel feature |
| Stripe onboarding for an Indian agency | New accounts invite-only per Stripe | Confirm eligible account before promising features requiring agency Stripe [Stripe][S62] |
| Razorpay SaaS/wallet automation | Unsupported by the cited integration due to off-session requirements | Use eligible provider or external/manual billing design; ordinary payment acceptance is insufficient |
| Marketplace applications | Seller-specific scope/prices/permissions | Obtain current listing/licence and identify who supports each failure mode |
| Custom objects/portals | Native objects exist; each surface has limits | Test associations, permissions, marketing reach and portal support; custom object is not arbitrary database parity |
| Broader enterprise/regulated use | Configuration and add-ons do not prove end-to-end compliance | Price actual professional review and missing controls; do not attach an unverified certification claim |

### 5.3 Price boundaries for expanded scope

| Extra scope | Cost mechanism | Markup basis |
|---|---|---|
| Additional location/account | Repeated configuration + per-location vendor charges + consolidated reporting | C/T on new labour, V/U on actual subscriptions/usage |
| Additional language | Translation, templates per language, content/voice QA | C/T; external translator/voice cost separately |
| Additional workflow branch or integration entity | Build, tests, reconciliation and run-time actions | C/T + metered F/A/I |
| Additional campaign/post/email | Actual production and approval effort + delivery | C + E/W/P/A as used |
| Additional data volume | Cleanup, batch runtime, storage and restore verification | C/T + provider charges; records alone do not price complexity |
| More revisions/support hours | Agreed hours at internal ₹500/₹1,200 base | C/T; choose actual multiplier and service response terms |
| Faster service or guaranteed response | Reserved staff capacity and service obligation | Separate capacity costing; no evidence-based universal rush markup found |
| Unsupported native requirement | External component or custom implementation | T + actual I/H costs; a working proof of capability precedes a fixed quote |

## 6. Worked cost calculations

All examples use ₹95/USD, exclude tax unless explicitly shown, and are **calculations, not vendor offers or market observations**. Margins are gross contribution before general overhead and sales costs.

### 6.1 WhatsApp marketing campaign to 1,800 Indian recipients

Assume one delivered marketing message each, no Free Entry Point exemption, 3 configuration hours, and CSV-basis usage plus 30% U markup:

| Line | Agency cost | Client charge |
|---|---:|---:|
| Build/send/report labour | 3 × ₹500 = ₹1,500 | ₹3,000 at 100% C markup |
| Messages, October CSV basis | 1,800 × $0.0118 × ₹95 = ₹2,017.80 | ₹2,623.14 at 30% U markup |
| WhatsApp subscription, if first/only campaign that month | $10 × ₹95 = ₹950 | ₹1,187.50 at 25% V markup |
| Total before platform, fees and taxes | **₹4,467.80** | **₹6,810.64** |

Gross contribution before those omitted items is ₹2,342.84. If the month's WhatsApp subscription is already included in platform billing, remove it from **both** sides here. At the older $0.0124 body figure, message cost would be ₹2,120.40; reconcile the ₹102.60 difference before locking the tariff. The calculation uses billable deliveries, not a guarantee all 1,800 contacts will receive the message.

### 6.2 Support messages plus utility reminders

One number delivers 2,400 service messages and 600 utility messages in the month. On the October CSV basis, with no Free Entry Point exemption:

`Service cost = (2,400 − 1,000) × $0.0014 = $1.96`\
`Utility cost = 600 × $0.0014 = $0.84`\
`Message cost = $2.80 = ₹266; plus $10 subscription = ₹950.`

This assumes the guide's free allowance and the CSV's unit rates apply to the actual account. AI-generated replies add A; utility messages do not consume the service free allowance. At 30% U markup the ₹266 usage line becomes ₹345.80, before management, platform and fees.

### 6.3 Email campaign with validation and forwarding

10,000 outbound billable events + 2,000 incoming/forwarded events + 10,000 validation checks:

`Email = 12 × $0.675 = $8.10 = ₹769.50`\
`Validation = 10 × $2.50 = $25 = ₹2,375`\
`Combined vendor usage = ₹3,144.50; at 30% U markup = ₹4,087.85.`

At 4 labour hours, build cost is ₹2,000; a ₹4,000–6,000 service fee corresponds to C. The vendor charge is not simply ₹64 per 1,000 customer records.

### 6.4 Premium workflow: 5,000 leads, four billable steps

20,000 premium executions in one location, ignoring already-consumed lifetime credits:

| Option | Vendor calculation | INR cost |
|---|---:|---:|
| PAYG | 20,000 × $0.01 = $200 | ₹19,000 |
| Starter | $10 + 10,000 × $0.008 = $90 | ₹8,550 |
| Growth | $25, within 30,000 allowance | ₹2,375 |
| Scale | $50, within 65,000 allowance | ₹4,750 |

This arithmetic compares one specific workload. It is not a rule that the highest tier is cheapest. External AI/tool charges are separate, and allowances cannot be pooled across unrelated sub-accounts unless the actual contract permits it. At 30% U markup, the ₹2,375 vendor line becomes ₹3,087.50; automation management is extra.

### 6.5 Voice AI: eligible overseas calls

For 500 traditional PAYG minutes using $0.045 engine + $0.015 TTS:

`Engine/TTS subtotal = 500 × $0.06 = $30 = ₹2,850.`

**Then add actual LLM tokens, the actual phone legs/rental, recording/transcription if used, and managed-work cost.** This ₹2,850 is not the all-in call cost. In a supported AI plan, remove only components covered by its actual allowance. At 30% markup the uncovered engine/TTS subtotal would sell for ₹3,705. This example is not deliverable as native Voice AI on India LC beta numbers.

### 6.6 One managed location: full monthly direct cost

Assume Founder shared among 25 paying locations, WhatsApp, AI Growth, 10,000 billable email events, 1,800 marketing messages at CSV basis, and 4 support hours. No separate validation, premium workflow or phone usage:

| Monthly agency cost | INR |
|---|---:|
| Allocated Founder | ₹1,888.60 |
| WhatsApp fixed | ₹950.00 |
| AI Growth | ₹4,750.00 |
| Email | ₹641.25 |
| WhatsApp marketing | ₹2,017.80 |
| Support labour | ₹2,000.00 |
| **Direct cost before collection/FX/tax** | **₹12,247.65** |

At ₹18,000 revenue, contribution is ₹5,752.35, approximately **32.0%**. This is an illustration of total costing, not a recommended package or a claim of 32% net earnings. Reselling AI Growth at a 25% markup gives ₹5,937.50, but that line alone does not cover the rest of the system.

### 6.7 Payment fees on a ₹1,000 customer sale

At an **assumed** 2% gateway rate plus an **assumed** 18% tax on that fee:

`Fee ₹20 + tax ₹3.60 = ₹23.60; merchant receipt ₹976.40.`

This illustrates fee arithmetic only. It is not a claim that every UPI/payment/gateway transaction has this rate. If your agency separately collects ₹10,000 from the client, your own collection processing is another agency cost. At an assumed 2.36% fee on gross collection, recovering ₹10,000 net requires `₹10,000 ÷ (1 − 0.0236) = ₹10,241.70`; simply adding 2.36% under-recovers slightly.

### 6.8 Markup versus profit

A configuration takes 10 hours: ₹5,000 labour. A ₹15,000 setup fee represents 200% markup on **labour**. If direct assets/integration/testing outside that labour budget add ₹3,000, total direct cost is ₹8,000 and contribution is ₹7,000 (46.7% of revenue), before overhead/taxes. Calling it a 200% profit margin would be incorrect.

## 7. Observed market offers and limits of markup evidence

**Public evidence supports asking-price examples, not a universal “markup people make”.** These providers do not publish complete delivery costs or realised profitability. They serve differing markets/scopes; USD-to-INR conversion does not turn an overseas offer into an Indian benchmark. The C/T/V/U bands in this file remain estimating assumptions.

| Provider's own published offer, checked 31 October 2026 | Asking price | Reference INR at ₹95/USD | Interpretation |
|---|---:|---:|---|
| AutoGen CRM snapshot installation | $299 one-time | ₹28,405 | Specific implementation offer, not standalone software cost |
| AutoGen CRM starter setup | $499 one-time | ₹47,405 | Published starter scope includes account/pipeline/calendar/forms/workflows |
| AutoGen CRM Growth Build | $1,250 one-time | ₹1,18,750 | More extensive funnel/automation build; subscription separate |
| aibrevo single-business setup | $1,499–4,999 | ₹1,42,405–4,74,905 | Scope/timeline and ownership terms differ |
| High Level Admins setup | Starts $5,000 | Starts ₹4,75,000 | Larger scoped implementation, not comparable to a small one-workflow task |
| High Level Admins Admin service | $2,500/month | ₹2,37,500/month | Published dedicated staffing scope; tools/usage are additional |

Primary seller pages: [AutoGen CRM][S57], [aibrevo][S58], [High Level Admins][S59]. These are observed advertised prices, not endorsements, representative samples or proof the offers achieve sales.

To calculate an observed markup, the same provider's actual loaded delivery cost and included scope would be needed. **Do not divide these service prices by HighLevel's $97/$297/$497 agency fee and label the result their markup.** A multi-client agency subscription is not the sole direct cost of one implementation.

A fee expressed as 10–20% of ad spend, a revenue share, per-appointment charge or fixed retainer can be offered commercially, but none yields a known margin without delivery/usage cost, attribution, refunds and contract scope. No evidence-based India-wide margin range is established by this audit.

## 8. Coverage and source register

### 8.1 Coverage of the supplied local material

The following files were read as **capability-discovery inputs**. Internal designs and generated contracts do not establish public pricing, release status or unrestricted client access.

- [Product classification](/Users/kforcode/Developer/Highlevel/backend/ai-backend/apps/ghl-mcp/tmp/mcp-apps-product-classification.md): proposed MCP UI coverage and product inventory.
- [Selective UI design](/Users/kforcode/Developer/Highlevel/backend/ai-backend/apps/ghl-mcp/tmp/mcp-apps-selective-ui-design.md): presentation/execution separation and proposed custom experiences.
- [Generated hosted-operation registry](/Users/kforcode/Developer/Highlevel/backend/ai-backend/apps/ghl-mcp/generated/hosted-operation-agent-registry.generated.json): **741 operations, 43 domains** in the file inspected. Its own note says runtime operations can be narrowed by session scopes.

The registry was used to check for missing commercial service families; it was not treated as a list of 741 individually priced products.

| Registry domain(s) | Commercial coverage in this file |
|---|---|
| contacts, businesses, locations, users, custom-fields | CRM, data, access, account administration |
| objects, associations | Custom industry records and linked-data implementations |
| opportunities | Sales routing, pipelines, forecasting/reporting |
| conversations, chat-widget, phone-system, voice-ai | Inbox, messaging, phone and AI services |
| calendars | Meetings, services, bookings; additional UI-only verticals researched separately |
| campaigns, emails, email-isv | Campaigns, sending setup and email-provider integrations |
| forms, surveys, funnels, countdown-timer, links | Lead capture, surveys, quizzes, sites/funnels, timers and tracking links |
| blogs, brand-boards, files, medias | Content, brand systems and asset/document operations |
| ad-publishing, social-planner | Paid campaigns and organic publishing |
| products, store, payments, invoices, proposals | Commerce, quotes, subscriptions, documents and payment administration |
| affiliate-manager | Affiliate and partner programmes |
| courses, clientportal-ai | Learning, portals and related app experiences |
| agent-studio, knowledge-base | Flow agents, knowledge and AI implementation |
| projects | Project/task workspaces and integration |
| workflows | Standard/premium automation, audits and custom orchestration |
| marketplace, oauth | Licensed apps, private/public integrations and custom development |
| saas-api, snapshots | SaaS provisioning, resale and reusable implementations |

Public/UI areas beyond that registry also covered: reputation, Listings/SEO/Prospecting, WhatsApp/Flows/calling, Rentals, Services, Field Services, Loyalty, Communities, webinars, gift cards, client/mobile apps, AI Studio/Cloud, Client App Builder, training, migrations and managed operations. The full frontend inventory in section 14 captures restricted Restaurants, native Visibility AI, ticketing, conferences/events and other app surfaces. Proposed specialised MCP views remain conditional custom builds.

### 8.2 Evidence hierarchy and reconciliation

Use the **actual contract/checkout and billing transaction** to settle an account-specific rate. For published facts, prefer a current product-specific billing guide and dated rate attachment over a generic page; use a newer dated changelog for affected rates. A support article can contain stale examples even after a recent modification. Where the public evidence conflicts, this reference records the conflict rather than claiming an unsupported ground truth.

The following uncertainties remain material: WhatsApp CSV/body and 5% treatment; exact authentication price; restricted-beta commercial fees; actual marketplace/third-party subscriptions; provider-surface payment support; and account-specific model, number or storage availability. Vendor prices are time-bound evidence. Labour/retail estimates and margin assumptions are not verified vendor facts.

### 8.3 Primary source register

All links below were accessed directly, retrieved through web search, or discovered within the official support/API indexes during the 31 October 2026 audit. Specific rates and restrictions were read from the linked pricing/product articles; broad folder links identify additional reference material rather than certifying every possible configuration. Dates below are displayed modification/effective dates where recorded, not future guarantees.

| Source | Scope / date note |
|---|---|
| [S01 — HighLevel pricing][S01] | Current agency plans, broad features and add-on list |
| [S02 — Official pricing and billing guide][S02] | Wallets, resale, agency add-ons; supporting generic overview |
| [S03 — Rebilling, reselling and wallets][S03] | Product-specific billing mechanics |
| [S04 — Online Listings][S04] | Directory deployment/resale; eligibility varies |
| [S05 — Prospecting free vs premium][S05] | Agency versus linked sub-account terms; 21 April 2026 |
| [S06 — WordPress reselling][S06] | Separate hosting plans/resale; 10 September 2026 |
| [S07 — Ad Manager reselling][S07] | $0 agency base fee; 25 September 2026 |
| [S08 — Search Atlas SEO][S08] | SEO features/quotas and billing |
| [S09 — LC Email][S09] | Billable events, verification and ramp-up |
| [S10 — SMTP credentials][S10] | Sending service versus hosted mailbox |
| [S11 — WhatsApp billing guide][S11] | October rule changes; contains older body rate table |
| [S12 — WhatsApp October 2026 CSV attachment][S12] | India marketing 0.0118, utility/service 0.0014 USD; read directly |
| [S13 — India numbers/voice beta][S13] | 8 September 2026; regional restrictions and rates |
| [S14 — Phone pricing][S14] | 12 October 2026; destination/leg/registration details |
| [S15 — International phone/SMS update][S15] | Effective 13 October 2026, affected countries only |
| [S16 — Phone pass-through markup][S16] | Specific 5% categories; body used over ambiguous page title |
| [S17 — Voice Intelligence][S17] | Labs and transcription dependency; 27 October 2026 |
| [S18 — Workflow Pro tiers][S18] | Per-sub-account allowance and overages |
| [S19 — Premium workflow billing][S19] | Lifetime free credits and action/execution definitions |
| [S20 — AI product pricing][S20] | 29 October 2026; role/plan/model-specific costs |
| [S21 — AI Studio Cloud][S21] | 17 October 2026; Tiny/Mini tiers and storage billing |
| [S22 — Payment-provider support matrix][S22] | Provider and product-surface support |
| [S23 — Razorpay integration][S23] | Domain/webhooks; SaaS/wallet limitation |
| [S24 — SaaS custom payment providers][S24] | Recurring plus off-session requirement |
| [S25 — Calendar payments][S25] | Gateway/widget/menu differences |
| [S26 — Razorpay pricing][S26] | Provider fees, method exceptions/promotions |
| [S27 — Contact setup][S27] | Native contact configuration reference |
| [S28 — Companies][S28] | Native company record model |
| [S29 — Custom Objects][S29] | Entity modelling; 23 December 2025 |
| [S30 — Associations][S30] | Linked object/company/opportunity records |
| [S31 — Company creation/enrichment][S31] | 27 October 2026; matching boundaries |
| [S32 — Public API documentation][S32] | Operation-specific availability; not full UI parity |
| [S33 — QR codes for bookings][S33] | Calendar, Services and Rentals destinations |
| [S34 — Rentals overview][S34] | Asset scheduling; verify newer specific changes |
| [S35 — Services enablement][S35] | Service-based booking product |
| [S36 — Field Services overview][S36] | Private beta; 29 October 2026 |
| [S37 — WhatsApp booking Flows][S37] | Coexistence/payment/custom-field/recurrence restrictions |
| [S38 — Instagram DM action][S38] | Standard DM window versus comment private reply |
| [S39 — Social Planner index][S39] | Channel-specific publishing documentation |
| [S40 — Reputation index][S40] | Review, competitor and testimonial capabilities |
| [S41 — Loyalty & Referral][S41] | Private beta, wallet and scanner rollout |
| [S42 — Documents & Contracts index][S42] | Document/signature workflows |
| [S43 — Gift Cards][S43] | Sale, issue, balance and redemption |
| [S44 — Membership/course index][S44] | Course platform features |
| [S45 — Communities][S45] | Group/content/member operations |
| [S46 — Client Portal][S46] | Customer-facing portal setup |
| [S47 — Knowledge-base index][S47] | Import, crawl and refresh capabilities |
| [S48 — Flow Agents overview][S48] | Agent Studio's separate product |
| [S49 — Managed Agent MCP connectors][S49] | External tool connections and agent setup |
| [S50 — AI Studio][S50] | App/site building product |
| [S51 — Client App Builder][S51] | Labs; 30 October 2026; web/Android and current limits |
| [S52 — Public MCP server][S52] | Supported public integration surface |
| [S53 — OAuth documentation][S53] | Scope, installation and token boundaries |
| [S54 — Public API rate limits][S54] | Per-app/resource limits |
| [S55 — Reporting/dashboards][S55] | Dashboard configuration reference |
| [S56 — Project Management][S56] | Founder/$497 and Labs; 30 October 2026 |
| [S57 — AutoGen CRM prices][S57] | Primary seller's advertised service offers |
| [S58 — aibrevo service price][S58] | Primary seller's advertised setup range |
| [S59 — High Level Admins prices][S59] | Primary seller's setup/staffing scope and prices |
| [S60 — Fixed-rate AI rebilling][S60] | Client unit rate can differ from actual underlying agency token cost |
| [S61 — Custom Object access/limits][S61] | All-plan availability and location cap |
| [S62 — Stripe India availability][S62] | Invite-only onboarding dependency |
| [S63 — Airtel commercial communication resources][S63] | DLT registration, headers, templates and consent references |
| [S64 — HIPAA activation terms][S64] | Account-wide fee and permanent enablement |

### 8.4 Reference maintenance boundary

The “verified on” date applies to this research pass only. Changes in vendor rates, feature access, contracts, FX and delivery scope require a new dated revision. A new custom solution should cite its native or external dependency, record its unknown charges, and show labour plus ongoing consumption. This prevents an estimate or proposed integration from becoming a false permanent vendor fact.

## 9. Atomic deliverables and unit pricing

**Granular expansion dated 31 October 2026.** Sections 1–8 remain the service and vendor-rate reference. This section adds **160 smaller implementation units**, followed by recurring operations, consumption formulas, change charges and itemised examples. These are components of the existing 300 services, not 160 additional independent HighLevel products.

### 9.1 How these units relate to the service catalogue

| Layer | What is priced | Example | Counting rule |
|---|---|---|---|
| Vendor resource | Actual subscription/consumption | WhatsApp number connection and delivered message | Record by actual billing scope; charge once |
| Atomic deliverable | One small, accepted piece of implementation | One approved-template submission or one routing condition | Price the defined unit and its effort |
| Service | Several related deliverables | WAP05: WhatsApp nurturing journey | Use its scoped total **or** its itemised components |
| Solution | Several services plus integration/testing | SOL02: salon operating system | Replace overlapping service totals with one integrated estimate |
| Managed operation | Work performed after launch | Investigate one failed run; revise one template | Charge agreed hours/event quantities; vendor usage continues |

A component already included in the accepted parent scope attracts **no extra setup charge**. Granular units are useful for genuinely smaller jobs, itemised custom estimates, scope changes and additional work. They are not a justification to charge both a parent setup price and all its children.

### 9.2 Unit-level assumptions

- **Agency labour costs and client quote amounts in sections 9–13 are estimates, not verified market rates. Vendor cost formulas use the separately sourced section 2 tariffs.** C means ₹500/hour internal cost and 100–200% labour markup; T means ₹1,200/hour and 50–150% markup, as in section 1.
- Units assume an active, correctly permissioned account and required connections/content already supplied. The parent service's delivery mode, vendor-cost codes, country/access gates and source references apply. A smaller unit does not remove an upstream subscription or an unsupported-feature restriction.
- Effort includes configuration/build and the **local acceptance check stated in the row**. Cross-system testing, client training, discovery, copywriting and vendor approval waiting are extra only when outside the agreed parent scope. Quantities refer to one location, one language and one revision unless stated otherwise.
- The price range spans different effort and markup choices; choose a single effort and multiplier when quoting. No setup unit includes ongoing hosting, traffic or monitoring automatically.
- Optional standalone-job minimum: price at least **2 configuration hours (₹1,000 cost; ₹2,000–3,000 quote)** or **2 engineering hours (₹2,400 cost; ₹3,600–6,000 quote)** if the task needs its own handover/context. This is an editable commercial assumption. Apply a minimum to the combined job, not to every small unit; do not add it again as a fee.
- Fractional hours describe marginal work on a known system. Rebuilding unknown workflows, restoring deleted records or debugging unavailable third-party APIs needs a diagnostic estimate first.

The acceptance checks below are **proposed delivery specifications**, not claims that every capability is a native toggle. When a parent includes I/X/B, test the actual integration/custom build/access before accepting the unit.

### 9.3 CRM data units

Inherited charges/access: CRM services, section 3.1. Data execution quantities are distinct from design quantities.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| CRM-U01 / CRM05 | Create one ordinary custom field with validation/default specification | 0.25–0.5h → ₹125–250 | ₹250–750 | C | Sample record saves and reads correctly; complex calculations excluded |
| CRM-U02 / CRM04 | Define one Smart List with up to 3 filter conditions | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Included/excluded sample records match the definition |
| CRM-U03 / CRM02 | Map one clean source column to an existing field | 0.25–0.5h → ₹125–250 | ₹250–750 | C | Five representative rows retain expected values and formats |
| CRM-U04 / CRM03 | Clean one formatting rule across up to 1,000 rows | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Before/after exception count supplied; manual research excluded |
| CRM-U05 / CRM03 | Design and run one deduplication rule on up to 1,000 candidate records | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Merge precedence, survivor and exception report checked; take an export first |
| CRM-U06 / CRM08 | Define one custom-object schema, up to 10 fields | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Three sample records and field types work; import/portal excluded |
| CRM-U07 / CRM09 | Configure one association label/type between two supported entities | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Relationship and unlink example pass without changing unrelated links |
| CRM-U08 / CRM10 | Configure one role profile and test one allowed/denied record path | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Both permitted and forbidden paths checked; full security audit excluded |

### 9.4 Sales process units

Inherited charges/access: SAL services. Test deals are separated from live customer opportunities.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| SAL-U01 / SAL01 | Configure one pipeline with up to 5 stages and value conventions | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Sample deal traverses the defined stages; communication excluded |
| SAL-U02 / SAL05 | Add one lead-assignment condition and fallback owner | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Matching and non-matching test leads get expected owners |
| SAL-U03 / SAL06 | Add one rule-based score signal and threshold response | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Positive, negative and boundary-value tests pass |
| SAL-U04 / SAL07 | Add one follow-up touch with eligibility and stop check | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Eligible lead enters; reply/opt-out or agreed stop prevents next touch |
| SAL-U05 / SAL08 | Add one overdue-task escalation branch | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Due/overdue/closed-task cases route as specified |
| SAL-U06 / SAL03 | Map one inbound lead source/UTM into a CRM source field | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | A tagged test visit produces the expected source value |
| SAL-U07 / SAL11 | Map one appointment outcome to a deal-stage update | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | One outcome updates only the intended opportunity |
| SAL-U08 / SAL14 | Implement one additional commission rule in an existing external calculator | 2–4h → ₹2,400–4,800 | ₹3,600–12,000 | T | Sale, cancellation and rounding examples match agreed arithmetic; payouts excluded |

### 9.5 Website, form and funnel units

Inherited charges/access: WEB services. Supplied text/assets are assumed unless the unit explicitly produces them.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| WEB-U01 / WEB04 | Build one reusable responsive section with supplied copy/image | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Agreed desktop/mobile widths render without overlap |
| WEB-U02 / WEB01 | Add one conditional form path with up to 3 fields | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Matching/non-matching submissions collect and map expected fields |
| WEB-U03 / WEB06 | Add one thank-you/next-step page to an existing funnel | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Correct redirect and lead event occur after test submission |
| WEB-U04 / WEB07 | Configure one supported checkout offer or upsell step | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Test purchase creates the expected order/amount; gateway setup excluded |
| WEB-U05 / WEB17 | Connect one domain/subdomain to an existing site | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | DNS/SSL and canonical destination verified; domain purchase excluded |
| WEB-U06 / WEB18 | Map and verify 10 old URLs to approved destinations | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | HTTP response and destination checked; SEO outcome not guaranteed |
| WEB-U07 / WEB16 | Create one branded editable QR destination | 0.25–0.75h → ₹125–375 | ₹250–1,125 | C | Two devices scan to the intended current URL; printing excluded |
| WEB-U08 / WEB20 | Add one field/calculation to an existing custom calculator | 2–5h → ₹2,400–6,000 | ₹3,600–15,000 | T | Boundary/invalid-input tests pass; new calculation engine excluded |

### 9.6 Calendar, service, rental and field units

Inherited charges/access: CAL services. Field units remain private-beta dependent; calendar/provider constraints remain in force.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| CAL-U01 / CAL01 | Configure one weekly availability pattern, buffers and booking notice | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Open/blocked/boundary slots match the agreed time zone |
| CAL-U02 / CAL02 | Add one staff member and conflict-calendar mapping | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Busy slot is not offered; eligible free slot is offered |
| CAL-U03 / CAL05 | Add one reminder with a reschedule/cancel route | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | A scheduled and cancelled appointment take correct paths |
| CAL-U04 / CAL08 | Configure one service with up to 2 variants and one assigned staff member | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Duration, availability and selected price match the service option |
| CAL-U05 / CAL11 | Configure one rental listing with stock quantity and base duration | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Requested quantity blocks availability correctly in a sample booking |
| CAL-U06 / CAL12 | Add one supported seasonal/duration pricing rule | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Before/during/after or duration-boundary amounts match the specification |
| CAL-U07 / CAL16 | Configure one field-service job/visit scenario in an enabled beta account | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Request, job, visit and assigned technician states reconcile |
| CAL-U08 / CAL17 | Configure one field checklist and completion condition | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Worker can complete required items and office sees the saved result |

### 9.7 Email units

Inherited charges/access: EML services; E/validation/IP/provider charges remain additional.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| EML-U01 / EML01 | Authenticate one sending subdomain using required DNS records | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Provider verifies records; test headers inspected; DNS waiting not productive labour |
| EML-U02 / EML02 | Build one reusable email content block | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Test renders and links work in agreed clients; original artwork excluded |
| EML-U03 / EML03 | Build one campaign from supplied copy in an existing template | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Audience count, preview, unsubscribe and approved test send checked |
| EML-U04 / EML05 | Add one email touch to an existing sequence | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Trigger, wait and reply/opt-out stop path pass |
| EML-U05 / EML07 | Submit one batch of up to 1,000 contacts for validation and import results | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Status counts reconcile; vendor check charge separate |
| EML-U06 / EML08 | Diagnose one deliverability symptom and supply findings | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | DNS/log/sample-header evidence supplied; broad inbox-placement guarantee excluded |
| EML-U07 / EML09 | Run one documented warm-up/ramp review cycle | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Current allowance, volume and adverse events recorded; dedicated IP not included |
| EML-U08 / EML11 | Configure one external SMTP sending identity and test reply path | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Successful send/reply and error case verified; provider/mailbox subscription excluded |

### 9.8 WhatsApp units

Inherited charges/access: WAP services. Delivery/template category/number approval is vendor-controlled; unit completion cannot guarantee approval.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| WAP-U01 / WAP01 | Prepare one number's connection/verification prerequisite pack | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Ownership, business assets and missing approvals documented; approval wait excluded |
| WAP-U02 / WAP03 | Prepare and submit one template in one language | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Variables/sample data/category submitted; one content revision included |
| WAP-U03 / WAP05 | Add one template touch, eligibility condition and opt-out branch | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Valid/invalid-recipient and stop-state tests recorded; delivery costs extra |
| WAP-U04 / WAP04 | Prepare one audience batch, up to 1,000 existing opted-in records | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Suppression, duplicate and eligible-send counts reconcile |
| WAP-U05 / WAP08 | Configure one supported Flow screen and CRM field mapping | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Complete/incomplete inputs save expected values; inherited Flow restrictions apply |
| WAP-U06 / WAP09 | Connect one eligible appointment-booking Flow path | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Available-slot and unavailable-slot cases pass; paid-calendar workaround excluded |
| WAP-U07 / WAP13 | Add one team-routing queue and escalation condition | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Owned/unowned conversations follow agreed routing; staffed replies excluded |
| WAP-U08 / WAP15 | Reconcile one number/provider migration dependency set | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Cutover, rollback limits and residual subscriptions documented; historic recovery not promised |

### 9.9 Inbox, SMS and phone units

Inherited charges/access: MSG services and country restrictions. Rows do not enable unsupported India LC beta features.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| MSG-U01 / MSG01 | Connect one eligible inbox/channel and test conversation ownership | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Inbound message reaches correct queue and reply uses correct channel |
| MSG-U02 / MSG03 | Configure one Instagram comment-triggered private response | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Eligible comment path tested; unrestricted DM window not assumed |
| MSG-U03 / MSG07 | Add one supported SMS touch and reply/STOP handling | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Encoding/segments and incoming opt-out path checked |
| MSG-U04 / MSG08 | Prepare one brand/campaign evidence correction and resubmission | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Specific rejection addressed; registration fees and carrier approval separate |
| MSG-U05 / MSG09 | Configure one eligible phone number's forwarding/office-hours route | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Open/closed/unanswered test calls follow expected path |
| MSG-U06 / MSG12 | Add one supported IVR branch and fallback | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Valid/invalid/no-input paths checked on eligible phone system |
| MSG-U07 / MSG14 | Set one recording-retention/transcription policy on supported numbers | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Sample call and retained artefact inspected; usage/storage charges extra |
| MSG-U08 / MSG16 | Map one external Indian SMS delivery-status callback | 3–6h → ₹3,600–7,200 | ₹5,400–18,000 | T | Delivered/failed/duplicate callback cases map correctly; provider DLT setup separate |

### 9.10 Publishing and creative units

Inherited charges/access: SOC services; content rights, generation credits and network API limitations remain separate.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| SOC-U01 / SOC01 | Connect one eligible social profile and test its permissions | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Correct profile available for an approved supported-format test |
| SOC-U02 / SOC03 | Schedule one supplied post on one channel | 0.25–0.5h → ₹125–250 | ₹250–750 | C | Text, media, link and time zone verified; no original creation included |
| SOC-U03 / SOC04 | Write one short caption and adapt it to one additional channel | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Brand facts and channel limit checked; research/interview excluded |
| SOC-U04 / SOC05 | Create one static creative from an agreed design system | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Final dimensions and licensed assets recorded; original identity design excluded |
| SOC-U05 / SOC06 | Edit one supplied short clip, up to 60 seconds, with captions | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Audio/captions/export checked; filming and advanced animation excluded |
| SOC-U06 / SOC08 | Map one content feed and review/scheduling condition | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Valid and malformed/duplicate items take expected paths |
| SOC-U07 / SOC09 | Configure one reviewer approval handoff | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Rejected draft does not publish under the specified process |
| SOC-U08 / SOC10 | Generate and human-review one set of 3 AI creative variants | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Factual/brand/format checks completed; model usage and rights review separate |

### 9.11 Advertising and conversion-event units

Inherited charges/access: ADS services. Labour quote excludes every rupee of media spend.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| ADS-U01 / ADS01 | Build one additional Meta ad set with supplied audience and creatives | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Objective, geography, spend cap and destination reviewed before approval |
| ADS-U02 / ADS03 | Build one Google Search ad group with supplied keyword intent | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Match types, negatives, ad text and conversion target checked |
| ADS-U03 / ADS04 | Build one supported LinkedIn audience/ad combination | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Eligibility, objective and field mapping checked; platform-specific limitations apply |
| ADS-U04 / ADS06 | Produce one ad-copy concept with 3 short variations | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Claims, CTA and platform length checked; legal approval excluded |
| ADS-U05 / ADS07 | Implement and verify one browser conversion event | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | One intended action fires once in agreed test conditions |
| ADS-U06 / ADS08 | Implement one server event and browser/server deduplication key | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Paired events deduplicate in provider diagnostics; infrastructure extra |
| ADS-U07 / ADS09 | Map one lead-ad form and up to 10 fields to CRM | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Test lead fields, source and duplicate behaviour verified |
| ADS-U08 / ADS10 | Map one won-sale/refund event to an external conversion feed | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Sale, reversal and replay cases reconcile; ad-platform attribution not guaranteed |

### 9.12 Review, SEO and prospecting units

Inherited charges/access: REP services. These are bounded tasks rather than promises of ranking or review outcomes.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| REP-U01 / REP01 | Configure one public review request and reminder/stop rule | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Eligible customer receives approved path; no satisfaction gating |
| REP-U02 / REP02 | Build one separate private-feedback capture path | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Feedback reaches a case/owner; public review access remains independent |
| REP-U03 / REP04 | Define one review-reply tone and human-escalation condition | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Positive/negative/unsafe-content examples follow the agreed process |
| REP-U04 / REP07 | Correct one GBP business-data group for one eligible location | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Submitted change and evidence recorded; Google approval wait excluded |
| REP-U05 / REP09 | Reconcile one address/phone consistency issue across enabled listings | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Affected directory/provider status recorded; manual unconnected sites excluded |
| REP-U06 / REP12 | Optimise one page's title, description, headings and internal links | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Published values and target links verified; new copy outside scope extra |
| REP-U07 / REP13 | Remediate one diagnosed technical SEO defect across one template | 3–8h → ₹3,600–9,600 | ₹5,400–24,000 | T | Affected URLs retested; unrelated template rewrites excluded |
| REP-U08 / REP15 | Embed one prospecting audit widget and route qualified submissions | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Widget/lead/source flow checked; underlying subscription and report limits apply |

### 9.13 Retention and loyalty units

Inherited charges/access: RET services. Beta/ledger restrictions and merchant reward liabilities remain unchanged.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| RET-U01 / RET01 | Add one anniversary/date-based trigger and eligibility rule | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Date, missing-date and opt-out examples pass |
| RET-U02 / RET02 | Add one product/service repeat interval and stop condition | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Purchase updates next expected contact; cancelled/refunded cases defined |
| RET-U03 / RET03 | Add one renewal interval/status branch | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Due, renewed and lapsed records route correctly |
| RET-U04 / RET06 | Build one satisfaction question and follow-up owner assignment | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Responses save and route; no selective public review suppression |
| RET-U05 / RET08 | Configure one complaint severity/SLA escalation rule | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Open, overdue and resolved cases take correct path |
| RET-U06 / RET09 | Add one referrer attribution field/link and manual reward report rule | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Referrer/referred contact attribution survives test conversion |
| RET-U07 / RET11 | Configure one earning/reversal rule in an accessible native beta | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Earn, cancel and duplicate-event cases checked; beta fee unresolved |
| RET-U08 / RET12 | Configure one supported reward/wallet/scanner path for existing programme | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Authorised redemption and invalid scan tested where rollout permits |

### 9.14 Billing and document units

Inherited charges/access: PAY services. Provider-surface compatibility, merchant charges and supplied legal/accounting content remain dependencies.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| PAY-U01 / PAY02 | Create one product price, frequency and tax-label configuration | 0.5–1h → ₹250–500 | ₹500–1,500 | C | One-time/recurring selection and test amount agree with specification |
| PAY-U02 / PAY03 | Create one supported payment link for an existing product | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Amount, confirmation and paid event checked; merchant onboarding excluded |
| PAY-U03 / PAY04 | Create one reusable invoice template and line-item layout | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Draft/tax/amount preview reconciles to supplied invoice rules |
| PAY-U04 / PAY06 | Create one estimate acceptance-to-invoice state transition | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Accepted, declined and replay cases avoid duplicate invoices |
| PAY-U05 / PAY07 | Create one supplied contract template with signature fields | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Recipient, field placement and completed-copy access tested |
| PAY-U06 / PAY08 | Add one additional recipient/signing-order condition | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Expected recipient receives the correct step; identity assurance is separately scoped |
| PAY-U07 / PAY10 | Add one failed-payment reminder/retry condition supported by provider | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Failure, recovery and cancelled-subscription tests pass |
| PAY-U08 / PAY14 | Map one invoice/tax/payment entity to an external accounting system | 6–12h → ₹7,200–14,400 | ₹10,800–36,000 | T | Create/update/refund reconciliation passes; statutory filing not included |

### 9.15 Commerce and fulfilment units

Inherited charges/access: COM services, including gateway/store/provider subscriptions and external logistics.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| COM-U01 / COM02 | Import one clean batch of 25 simple product SKUs | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Count, price, image and availability sample reconcile; data research excluded |
| COM-U02 / COM01 | Configure one product family with up to 5 supplied variants | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Option, SKU and checkout price match chosen variant |
| COM-U03 / COM03 | Add one supported promotion/coupon and eligibility boundary | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Eligible/ineligible/expired/limit cases checked |
| COM-U04 / COM04 | Map one external fulfilment status to customer notification | 2–4h → ₹2,400–4,800 | ₹3,600–12,000 | T | Valid, duplicate and unknown status events tested; carrier subscription extra |
| COM-U05 / COM05 | Add one identified-checkout recovery touch | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Known contact, completed order and opt-out conditions tested |
| COM-U06 / COM11 | Configure one gift-card denomination/design and redemption test | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Issue, balance and supported checkout sample reconcile |
| COM-U07 / COM13 | Configure one return-authorisation case path and fulfilment handoff | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Requested/approved/refunded/rejected records carry correct state |
| COM-U08 / COM10 | Map one stock update and duplicate/out-of-order handling rule | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Replayed/late stock events do not create unapproved duplicate changes |

### 9.16 Learning, community, webinar and portal units

Inherited charges/access: EDU services. Content production, broadcasts, moderation staffing and app products remain distinct.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| EDU-U01 / EDU01 | Upload and format one supplied lesson with existing video/file | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Member sees playable/readable content and expected navigation |
| EDU-U02 / EDU02 | Configure one module's drip/release/access condition | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Before/after-release and cancelled-member tests pass |
| EDU-U03 / EDU03 | Create one completion/certificate template using supported rules | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Qualified member can access the expected certificate; accreditation excluded |
| EDU-U04 / EDU05 | Configure one community channel and membership/visibility rule | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Eligible and ineligible test members see correct access |
| EDU-U05 / EDU09 | Configure one recorded-webinar registration/reminder step | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Registered, attended/identified and suppressed-contact paths checked |
| EDU-U06 / EDU10 | Map one external live-session attendance event to CRM | 3–6h → ₹3,600–7,200 | ₹5,400–18,000 | T | Join/absent/replayed event rules tested; broadcast platform fee extra |
| EDU-U07 / EDU11 | Configure one portal navigation/file-access section | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Authorised/unauthorised member path checked; custom backend excluded |
| EDU-U08 / EDU13 | Prepare one branded-member-app asset/submission update | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Required assets/build submission documented; store approval/provider fee separate |

### 9.17 Affiliate and partner units

Inherited charges/access: AFF services; merchant commissions and actual payout transfers are separate.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| AFF-U01 / AFF01 | Configure one affiliate campaign/product attribution rule | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Test referral and unattributed purchase reconcile |
| AFF-U02 / AFF02 | Configure one affiliate approval/activation state | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Pending, approved and rejected partner access differ as specified |
| AFF-U03 / AFF02 | Create one supplied partner-resource page/material pack | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Eligible affiliate can find working links; original media production excluded |
| AFF-U04 / AFF03 | Add one commission tier/rate for a supported campaign | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Tier boundary and product examples match the agreed calculation |
| AFF-U05 / AFF03 | Specify and test one refund/commission-reversal path | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Reversed order does not retain an incorrectly approved payable |
| AFF-U06 / AFF04 | Produce one partner statement/payout-approval export format | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Totals reconcile to selected transactions; payout execution excluded |
| AFF-U07 / AFF05 | Implement one external postback and idempotent attribution mapping | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Sale/refund/replay payloads give the expected attribution |
| AFF-U08 / AFF06 | Add one dealer lead-ownership/territory rule | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Assigned/unassigned/conflicting partner examples resolve as specified |

### 9.18 AI implementation and evaluation units

Inherited charges/access: AI services. All model/tool/channel charges remain additional unless actually covered by the chosen allowance.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| AI-U01 / AI01 | Clean/import one knowledge source, up to 10 supplied pages or one 20-page file | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Representative facts retrieved; inaccessible/scanned-content cleanup excluded |
| AI-U02 / AI03 | Configure one bot persona, objective and prohibited-action boundary | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Normal and boundary prompts follow agreed behaviour in the test set |
| AI-U03 / AI04 | Map one qualification answer to a field and human-handoff condition | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Complete, missing and ambiguous responses handled under the specification |
| AI-U04 / AI05 | Configure one supported booking tool/action and failure response | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Available/unavailable/permission-error cases checked |
| AI-U05 / AI09 | Configure one eligible outbound voice outcome and follow-up path | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Consent, no-answer and human-transfer/callback conditions tested where supported |
| AI-U06 / AI14 | Connect one external tool to an existing Flow Agent | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Success, timeout, invalid payload and permission denial tested |
| AI-U07 / AI15 | Configure one Managed Agent schedule/event with duplicate prevention | 3–6h → ₹3,600–7,200 | ₹5,400–18,000 | T | Expected invocation count observed; duplicate/re-entrant case handled |
| AI-U08 / AI19 | Run and annotate 10 defined AI test conversations/scenarios | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Inputs, outputs, pass/fail and defects delivered; inference usage separate |

### 9.19 App and MCP implementation units

Inherited charges/access: APP services. Client App Builder, AI Studio, external portals and custom MCP views are different delivery routes.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| APP-U01 / APP02 | Build one small UI screen on an existing app/navigation/design system | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Layout, loading, empty and error states demonstrated; new backend excluded |
| APP-U02 / APP03 | Implement one role-scoped app record view/action on an existing backend | 6–12h → ₹7,200–14,400 | ₹10,800–36,000 | T | Authorised and cross-user-denied paths tested; identity redesign excluded |
| APP-U03 / APP05 | Configure one existing AI Studio project's compute/storage settings | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Actual selected resource/tier and expected bill documented; usage extra |
| APP-U04 / APP06 | Configure one supported Client App Builder portal screen | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Current member and unauthorised access tested; Labs limitations apply |
| APP-U05 / APP07 | Create/test one Android APK build from an already-working supported app | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | C | Install, login and core navigation pass on agreed device; app-store/iOS work excluded |
| APP-U06 / APP10 | Connect one authorised user/location to an existing supported MCP surface | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Allowed read and denied action/location tested; external assistant subscription extra |
| APP-U07 / APP11 | Implement one custom MCP tool with schema and permission enforcement | 6–12h → ₹7,200–14,400 | ₹10,800–36,000 | T | Valid, invalid and cross-tenant requests tested; server foundation extra |
| APP-U08 / APP12 | Implement one custom host-compatible preview/picker view | 8–16h → ₹9,600–19,200 | ₹14,400–48,000 | T | Selection/context handoff and unsupported-host fallback demonstrated |

### 9.20 Workflow and integration units

Inherited charges/access: INT services. Check the actual executed action type when costing premium steps; an API request and a premium action are different units.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| INT-U01 / INT01 | Add one standard workflow trigger and entry guard | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Eligible/ineligible/duplicate entry cases tested |
| INT-U02 / INT02 | Add one branch with up to 3 conditions and fallback | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Boundary and default branch tested; copy/messages excluded |
| INT-U03 / INT04 | Map one webhook payload, up to 10 fields, to an existing endpoint | 3–6h → ₹3,600–7,200 | ₹5,400–18,000 | T | Required/optional/invalid fields behave as agreed |
| INT-U04 / INT07 | Add one two-way identity/conflict rule for an existing object sync | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Concurrent updates resolve without an uncontrolled sync loop |
| INT-U05 / INT09 | Implement one token-refresh/permission-error path in an existing OAuth app | 6–12h → ₹7,200–14,400 | ₹10,800–36,000 | T | Expiry, revoked token and insufficient-scope cases checked |
| INT-U06 / INT11 | Implement one retry/backoff/dead-letter/replay path | 6–12h → ₹7,200–14,400 | ₹10,800–36,000 | T | Transient failure recovers; permanent failure is visible and replayable |
| INT-U07 / INT12 | Add one entity export/restore sample to an existing backup job | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Record counts and one restoration sample verified; full-account restoration excluded |
| INT-U08 / INT16 | Add one external data store to an agreed deletion/retention process | 4–8h → ₹4,800–9,600 | ₹7,200–24,000 | T | Known record deleted/retained under the agreed rule; unsupported copies listed |

### 9.21 Reporting and delivery operations units

Inherited charges/access: OPS services. Full Project Management retains its Founder/Labs gate.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| OPS-U01 / OPS01 | Define/build one dashboard metric with one filter/dimension | 0.75–1.5h → ₹375–750 | ₹750–2,250 | C | Result reconciles to five underlying sample records |
| OPS-U02 / OPS02 | Configure one scheduled-report audience/cadence | 0.5–1h → ₹250–500 | ₹500–1,500 | C | Approved recipient receives the correct period/version |
| OPS-U03 / OPS04 | Reconcile one sales/paid-revenue metric for one period | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Deal, invoice, payment and refund differences explained |
| OPS-U04 / OPS08 | Configure one project List, statuses and existing-field views | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Task can move through specified states; feature access verified |
| OPS-U05 / OPS09 | Build one reusable 10-task onboarding checklist | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Assignees, relative dates and CRM associations checked |
| OPS-U06 / OPS10 | Set one project-space membership/privacy boundary | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Member and non-member access tests recorded |
| OPS-U07 / OPS12 | Deliver one 60-minute training session plus preparation | 2–3h → ₹1,000–1,500 | ₹2,000–4,500 | C | Recording/notes and agreed practical exercise supplied |
| OPS-U08 / OPS13 | Document one business flow, ownership and failure-recovery path | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Another authorised operator can follow the documented example |

### 9.22 Agency, SaaS and snapshot units

Inherited charges/access: SAS services. Provider approval, automatic rebilling eligibility and snapshot omissions remain material.

| Unit ID / parent service | Atomic deliverable and quantity | Effort → agency labour cost | Indicative labour quote | Markup | Local acceptance check / scope boundary |
|---|---|---:|---:|---|---|
| SAS-U01 / SAS02 | Configure one SaaS plan's price/entitlement matrix | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Test provisioned account has the expected paid/included feature set |
| SAS-U02 / SAS03 | Configure one eligible usage-rebilling category | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | One test event reconciles agency cost, client debit and chosen markup |
| SAS-U03 / SAS04 | Provision one additional location from an approved existing template | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Brand, users, assets and required missing connections recorded |
| SAS-U04 / SAS05 | Package one existing asset group into a snapshot and test load | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Target account receives supported configuration; credentials/live data not assumed |
| SAS-U05 / SAS06 | Deploy one approved snapshot revision to one test/client location | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Changes and preserved client-specific values verified |
| SAS-U06 / SAS08 | Onboard one licensed Marketplace app for one location | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Licence, scopes, event and uninstall/dependency impact documented |
| SAS-U07 / SAS11 | Reconcile one location's add-on/usage bill for one month | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Vendor lines, client debits, credits and unpaid exposure explained |
| SAS-U08 / SAS12 | Prepare one transfer/offboarding dependency inventory | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Owners, exportable assets, subscriptions and non-transferable items listed |

## 10. Recurring operations priced by actual work

These are **optional operations after launch**, not mandatory maintenance attached to every native feature. The table prices one execution of the stated work unit. Multiply by the agreed weekly/monthly/event frequency; vendor subscriptions and consumption remain additional. The original M-bands are an alternative monthly allowance, so do not stack the same labour under both schemes.

A change fee applies only outside included revision/support scope. A defect in your own agreed delivery is not automatically a new paid change. Vendor incidents, data repair, new requirements and routine operations should have separate agreed treatment.

| Operation / parent | Work unit | Suggested frequency | Effort → labour cost per unit | Indicative service fee per unit | Markup | Boundary |
|---|---|---|---:|---:|---|---|
| RUN01 / CRM03 | Review one data-quality exception batch, up to 100 flagged records | Weekly or event-based | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Manual identity research and bulk repair excluded |
| RUN02 / CRM10 | Review access for up to 10 users and execute approved removals | Monthly/quarterly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Record owner and evidence; additional locations separate |
| RUN03 / SAL05 | Review one routing queue and correct up to 5 rule/data exceptions | Weekly | 0.5–1.5h → ₹250–750 | ₹500–2,250 | C | Redesign of territories/compensation excluded |
| RUN04 / SAL12 | Review one pipeline conversion report and reconcile 5 exceptions | Monthly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Ad optimisation and staff coaching separate |
| RUN05 / WEB05 | Update up to 3 supplied text/image sections on an existing site | Monthly/on request | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | New layout, language or copywriting separate |
| RUN06 / WEB22 | Execute one supported WordPress update/backup/restore-sample cycle | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Malware recovery, premium plugin and hosting extra |
| RUN07 / CAL02 | Review 5 staff schedules and recurring booking conflicts | Monthly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Changes must be approved by business owner |
| RUN08 / CAL16 | Review field/rental booking exceptions, up to 10 cases | Weekly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Dispatching staff throughout the week is separate labour |
| RUN09 / EML03 | Prepare one supplied-content email send and review its outcome | Per campaign | 1.5–3h → ₹750–1,500 | ₹1,500–4,500 | C | Recipient events/validation charges separate |
| RUN10 / EML08 | Review sender health, bounces and suppression with one findings note | Weekly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | New-domain rebuild and incident remediation separate |
| RUN11 / WAP04 | Operate one approved campaign batch and delivery exception report | Per campaign | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Consent cleanup/template production not included |
| RUN12 / WAP13 | Review WhatsApp templates/quality/failed events and 5 exceptions | Weekly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Live customer conversations are separate staffing |
| RUN13 / MSG01 | Handle a defined inbox shift for one trained operator | Per 4-hour shift | 4–4h → ₹2,000–2,000 | ₹4,000–6,000 | C | Only four productive hours assumed; team lead/leave cover extra |
| RUN14 / MSG14 | Review 10 recorded calls for quality/retention exceptions | Weekly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Supported numbers only; transcription and storage extra |
| RUN15 / SOC03 | Schedule and verify 12 supplied posts in existing templates | Per batch | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Original content/creative and moderation extra |
| RUN16 / SOC05 | Produce 4 original static creatives using an agreed design system | Per batch | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | C | Stock, AI credits and major revisions extra |
| RUN17 / ADS01 | Review one active campaign, make 3 approved adjustments and log them | Weekly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Spend, new creatives and new campaign builds extra |
| RUN18 / ADS11 | Reconcile one ad/CRM conversion report for one platform/period | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Uncaptured historical identifiers cannot be reconstructed |
| RUN19 / REP03 | Review/draft/post up to 10 authorised review replies | Per batch | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | AI charges separate; legal/escalated responses excluded |
| RUN20 / REP12 | Refresh 2 agreed pages' on-page SEO using supplied content | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | New long-form writing and search subscription extra |
| RUN21 / RET04 | Prepare one opted-in reactivation segment and campaign report | Per campaign | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Delivery charges and original offer creative extra |
| RUN22 / RET11 | Reconcile up to 100 reward/redemption entries and 10 exceptions | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Merchant reward value, refunds and POS integration extra |
| RUN23 / PAY13 | Reconcile up to 100 payment transactions and 10 exceptions | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Accounting certification, chargebacks and manual collections extra |
| RUN24 / PAY11 | Handle one refund/dispute case pack under approved merchant instructions | Per case | 1–3h → ₹500–1,500 | ₹1,000–4,500 | C | Actual refund value/processor dispute fees are merchant spend |
| RUN25 / COM02 | Update 25 clean supplied SKUs/prices in an existing catalogue | Per batch | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Variant redesign and source-data cleanup extra |
| RUN26 / COM13 | Review 10 fulfilment/return exceptions and route actions | Weekly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Warehouse picking, shipping and refund funds excluded |
| RUN27 / EDU01 | Upload 4 supplied lessons into an existing course structure | Per batch | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Scripting/filming/editing/translation separate |
| RUN28 / EDU07 | Moderate one community for a defined operator work block | Per 4-hour block | 4–4h → ₹2,000–2,000 | ₹4,000–6,000 | C | No implied 24/7 presence; escalations beyond block separate |
| RUN29 / AFF04 | Reconcile 100 affiliate transactions and draft payout statement | Monthly | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | Commission funding and payment execution excluded |
| RUN30 / AFF02 | Onboard 5 approved partners using existing materials | Per batch | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Recruiting partners or producing new collateral excluded |
| RUN31 / AI02 | Refresh 10 changed knowledge pages and rerun 10 existing questions | Per cycle | 2–4h → ₹1,000–2,000 | ₹2,000–6,000 | C | New source research/model inference extra |
| RUN32 / AI19 | Review 20 AI conversation samples and revise one bounded prompt issue | Weekly/monthly | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | C | New channel/tool/function is separate implementation |
| RUN33 / APP05 | Review one app's infrastructure use, logs and spend exceptions | Monthly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | Hosting usage and incident repair separate |
| RUN34 / APP04 | Diagnose and fix one reproducible small app defect outside warranty scope | Per approved issue | 3–8h → ₹3,600–9,600 | ₹5,400–24,000 | T | Larger redesign gets its own estimate; do not rebill covered defects |
| RUN35 / INT11 | Monitor one integration and resolve 5 known/replayable exceptions | Weekly | 2–4h → ₹2,400–4,800 | ₹3,600–12,000 | T | Provider outage investigation or new schema separate |
| RUN36 / INT15 | Adapt one connector to a small documented API/schema change | Per change | 4–10h → ₹4,800–12,000 | ₹7,200–30,000 | T | Re-authentication, migration and breaking redesign may add scope |
| RUN37 / OPS02 | Prepare one recurring report with narrative on 5 agreed metrics | Monthly | 1–2h → ₹500–1,000 | ₹1,000–3,000 | C | New data sources and metrics extra |
| RUN38 / OPS12 | Run one 60-minute office-hours session plus preparation | Monthly | 1.5–2.5h → ₹750–1,250 | ₹1,500–3,750 | C | Hands-on implementation outside session separate |
| RUN39 / SAS11 | Reconcile one month's wallet/add-on/client-billing exceptions for 5 locations | Monthly | 3–6h → ₹1,500–3,000 | ₹3,000–9,000 | C | Unpaid charges remain an agency exposure, not a reconciler guarantee |
| RUN40 / SAS06 | Test one snapshot revision and deploy to 3 approved locations | Per release | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | C | Each client's unique integrations/content require separate tests |

**Frequency arithmetic:** Four weekly reviews are a four-review monthly bundle only if that is the contractual quantity. A five-occurrence month, holiday coverage, additional channels and unused-hour rollover need an explicit rule. An average calendar month contains more than four weeks; do not silently assume 48 weeks of delivery is a full year.

**Human staffing:** RUN13 and RUN28 use the reference ₹500/hour loaded-labour assumption, not a researched wage. Supervisor time, peak concurrency, recruitment, leave, training, phone time and night/weekend obligations must be costed if promised. Automated replies and human handling are separately measurable work.

## 11. Consumption units and exact costing rules

### 11.1 A job is not a usage unit

Use the current vendor rates in section 2. This ledger adds **measurement and calculation rules**, not a second conflicting vendor rate card. Symbols `r` and `fx` mean the actual applicable unit rate and billed INR/USD conversion. Credits are deducted once, only within the product/location/period that grants them.

| Cost line | Record these quantities | Cost calculation | Common wrong denominator |
|---|---|---|---|
| Core agency plan | Plan, billing term, funded locations and allocation rule | Actual subscription cost × agreed client allocation | One entire agency subscription charged to each client without disclosure |
| Fixed location add-on | Enabled product/location and active billable period | Sum actual billable add-on instances and periods | Branches, users and contacts treated as the same billing scope |
| Domain | TLD, term, intro/renewal/transfer/redemption | Actual registrar charge + approved handling | Quoting the intro price as permanent annual cost |
| LC Email | Actual billable recipient/events by sending, inbound and forwarding category | Sum vendor-billable events × applicable email rate | Campaign jobs or CRM contact count |
| Validation | Actual validation events, including rechecks | Checks × validation rate | Unique addresses ever stored |
| Dedicated IP | Number of paid IPs and periods | IPs × IP subscription cost | Confusing a sending domain with an IP |
| WhatsApp templates | Delivered messages by destination, category and exemption | Sum billed deliveries × matching destination/category rate | Contacts, templates created or 24-hour chat sessions |
| WhatsApp service allowance | Number, calendar month, event order and actual allowance consumed | Charge post-allowance events at their actual destination rates | Subtracting 1,000 separately for every country, contact or sub-account |
| WhatsApp free entry | Qualifying entry/reply and eligible window | Exclude only actual exempt deliveries under the account's terms | Treating any ad click or open chat as permanently free |
| SMS/MMS | Direction, destination, encoding, segments and carrier | Sum segments × route rate + actual carrier/registration charges | Visible message bubbles or only outbound text count |
| Phone rental | Country/type/number and billable period | Sum actual active rental charges | Assuming all countries use US local prices |
| Voice calls | Each leg's destination, connected/billable duration and rounding | Sum billable leg units × each leg rate + applicable optional charges | Child-leg minutes presented as total call cost |
| Recording/storage | Recorded minutes; retained quantity by month | Recording usage + retained minutes × storage rate for each month | Transcribing once and ignoring ongoing retention |
| Premium automation | Charged triggers/actions/apps, re-entry and actual attempts | Subscription + max(0, eligible executions − included executions) × overage | Workflow names or successful customer outcomes |
| Conversation/model AI | Product/model, actual input/output tokens and covered allowance | Input tokens × input rate + output tokens × output rate; apply only eligible coverage | Visible messages × an assumed constant cost |
| Traditional voice AI | Engine/TTS minutes, model tokens and plan coverage | Eligible uncovered engine/TTS + tokens + actual channel charges | One all-inclusive “AI minute” copied across voices/routes |
| Speech-to-speech AI | Selected model's billed minutes/units and coverage | Matching model rate × actual units + applicable channel costs | Adding a second traditional TTS stack without evidence |
| Managed Agent | Actual counted sessions/events/schedules, covered runs and underlying usage | Apply that product's allowance; bill actual uncovered model/resource use | Assuming every visible user message is one run |
| Flow Agent/tool call | Actual models, tool invocations, searches and generated media | Sum individual billed resources at their current rates | Applying Managed Agent plan allowance to a different product |
| Client fixed-unit AI resale | Billable client messages/minutes and configured unit price | Client revenue = units × configured price; contribution = revenue − actual uncovered cost | Calling fixed-unit price a fixed agency cost |
| App compute | Project, tier and actual billed hours | Sum tier-hours × hourly rates, including transition-hour rules | Multiplying an approximate monthly figure by an arbitrary calendar month |
| Database/file storage | Reserved DB GB and actual file GB by hour | Excess reserved DB GB-hours × DB rate + excess actual file GB-hours × file rate | Treating empty reserved DB as unbilled actual usage |
| Payment processing | Method, gross collected amount, fees/taxes/refunds/disputes | Actual merchant contract and invoice; agency's collection cost separately | Applying 2% to every method or treating all funds as agency income |
| External integration runtime | Provider tasks, executions, API events, hosting and retries | Sum provider bill + charged HighLevel steps + engineering operations | Assuming one business event equals one provider task |
| Rewards/affiliate/gift value | Approved earned value, reversals, outstanding liability and actual payouts | Merchant ledger and payment costs, separate from agency fee | Counting issued face value or payout funds as service margin |

Billable trigger/action rules were rechecked against [HighLevel's premium-feature guide][S19]; client fixed-unit AI pricing was rechecked against [the AI rebilling guide][S60]. The rate snapshot and unresolved vendor conflicts in section 2 remain authoritative within this file.

### 11.2 Mixed workflow: count every charged component

**Specified example:** 2,000 eligible contacts enter once; each reaches one premium trigger and three premium actions. One action sends one marketing template; one invokes a model; one writes to an external provider. Assume all four steps are actually marked billable in this account and no retries/credits.

`Premium executions = 2,000 × 4 = 8,000.`

Add, separately: 2,000 billable delivered templates **if all are delivered and chargeable**, actual AI tokens, external-provider task/runtime charges, and fixed subscriptions. If 100 runs repeat two premium actions, add 200 executions, plus only the downstream channel/provider events that actually occurred. A failed delivery can still leave a charged action/model/API attempt.

The four-step count is a workload specification, not a claim that every trigger/model action has standard $0.01 pricing. The platform labels and product billing details determine which actions enter which meter. [Execution definitions][S19].

### 11.3 Workflow tier cost equality points

Using section 2.6's recorded prices, **after lifetime free credits have been consumed**, for one location/month and supported premium executions only:

| Comparison | Equal-cost execution count | Calculation |
|---|---:|---|
| PAYG versus Starter | 1,000 | `0.01 × n = 10`, while Starter is within allowance |
| Starter versus Growth | 11,875 | `10 + 0.008 × (n − 10,000) = 25` |
| Growth versus Scale | 34,166.67; integer crossover at 34,167 | `25 + 0.006 × (n − 30,000) = 50` |

These are cost equalities for the stated tariff, not a recommended agency strategy. Account credits, plan-change rules and separately metered AI/apps can change the full bill.

### 11.4 Quote one unit cost before promising fixed client pricing

| Situation | What must be known | Safe costing basis |
|---|---|---|
| Fixed AI response tariff | Actual distribution of token/tool/context cost per response | Tested cost spread plus allowance, not an average from a different model |
| Fixed voice-minute tariff | Number route, answering legs, selected voice/model and covered usage | Worst scoped supported route/voice mix with recorded exclusions |
| Included messaging allowance | Delivered events, destinations and categories | Define unit/count, category mix and actual overage tariff |
| Unlimited workflow edits | Labour demand and complexity | No calculable finite cost until the allowance/boundary is defined |
| Per-appointment fee | Definition of qualified/booked/showed, cancellations and duplication | Agency delivery/usage cost plus agreed attribution and credit rules |
| Revenue share | Paid versus invoiced amount, refunds, tax and attribution window | Contract-defined earned fee; it does not replace provider-cost reconciliation |
| Low-traffic app hosting | Selected resources and minimum/inactive behaviour | Exact hours/storage/provider terms; low visits do not prove zero hosting |
| Multi-location subscription | Location separation, add-on instances and billing ownership | Sum actual resources with one explicit shared-platform allocation |

## 12. Change charges, scope boundaries and delivery checks

### 12.1 Scope changes priced as measured increments

The following are **estimated additional work**, not automatic surcharges. Apply only outside the approved scope and use the existing atomic unit if it already describes the change. Parent inclusions and covered-defect fixes take precedence.

| Change | Measured unit | Incremental labour estimate | Labour cost | Indicative extra fee | Treatment of other charges |
|---|---|---:|---:|---:|---|
| Another ordinary field | One field | 0.25–0.5h C | ₹125–250 | ₹250–750 | New mapping/validation/portal view extra only if needed |
| Another routing condition | One condition + fallback test | 0.5–1.5h C | ₹250–750 | ₹500–2,250 | New premium steps/events add F usage |
| Another template language | One template/language, supplied translation | 0.5–1.5h C | ₹250–750 | ₹500–2,250 | Translation and message delivery separate |
| Another supported channel | One connection + 3 mapped paths | 3–6h C | ₹1,500–3,000 | ₹3,000–9,000 | New W/P/E/A subscription/usage as applicable |
| Another staff member | One eligible staff/calendar/permission mapping | 0.5–1.5h C | ₹250–750 | ₹500–2,250 | No automatic native per-user fee invented; external licences may differ |
| Another location from known template | One additional provisioned location | 2–4h C | ₹1,000–2,000 | ₹2,000–6,000 | Repeat actual per-location add-ons; domains/approvals extra |
| Another responsive page section | One supplied-content section | 1–2h C | ₹500–1,000 | ₹1,000–3,000 | Creative/licensed assets extra |
| Another translated website page | One supplied-translated page in known layout | 1–2h C | ₹500–1,000 | ₹1,000–3,000 | Translation, routing and locale QA beyond page extra |
| Another clean import batch | 1,000 records in established mapping | 0.5–1.5h C | ₹250–750 | ₹500–2,250 | Validation/provider runtime separate; dirty data re-estimated |
| Another external payload/entity | One entity, up to 10 fields | 3–6h T | ₹3,600–7,200 | ₹5,400–18,000 | Provider API/tasks/storage separate |
| Another AI knowledge source | 10 supplied pages / one bounded file | 1–2h C | ₹500–1,000 | ₹1,000–3,000 | Model/indexing/storage only if actually billed |
| Another AI language evaluation | 10 scenarios, supplied correct-answer reference | 2–4h C | ₹1,000–2,000 | ₹2,000–6,000 | Translation/native-language expert, calls and inference extra |
| Another role-scoped app screen | One screen on existing backend | 6–12h T | ₹7,200–14,400 | ₹10,800–36,000 | New identity/backend redesign excluded |
| Another custom MCP tool | One bounded contract on existing server | 6–12h T | ₹7,200–14,400 | ₹10,800–36,000 | Hosting, auth/runtime, marketplace release separate |
| Another test cycle after scope change | One bounded scenario set, up to 10 cases | 2–4h C | ₹1,000–2,000 | ₹2,000–6,000 | Do not charge again for already included acceptance tests |
| Another engineering diagnostic block | One approved investigation block | 2–4h T | ₹2,400–4,800 | ₹3,600–12,000 | Deliver evidence/next estimate, not a promise every issue is fixed |

A changed field can affect forms, imports, workflows, reporting and portals. Count the actual affected components instead of adding an arbitrary “complexity percentage”. Where requirements are not bounded, specify diagnostic time and an unresolved implementation estimate.

### 12.2 Acceptance evidence by deliverable type

| Deliverable | Evidence sufficient for the scoped local acceptance | Evidence that is separate work |
|---|---|---|
| Data import | Mapping, count reconciliation, sample values and exception file | Researching missing records or reconstructing an old inbox |
| Routing/workflow | Eligible/ineligible/duplicate/stop examples and expected state | Full regression of every unrelated account workflow |
| Message/email | Approved text, recipient identity, channel/status and suppression path | Guarantee of inbox placement, vendor approval or future deliverability |
| Booking | Busy/free/cancelled/time-zone cases and expected customer/staff record | Every external calendar provider's long-term service availability |
| Payment | Amount/method, paid/failed/refund event and duplicate handling | Statutory accounting certification or money settlement guarantee |
| AI conversation | Recorded scenario results, human handoff and action limits | Guarantee that all future open-ended prompts produce the correct answer |
| Integration | Auth, schema, idempotency, errors and replay of scoped cases | New undocumented third-party API or a second system architecture |
| App/portal | Loading/empty/error/role-boundary checks and agreed device/browser | Unscoped penetration audit, every-device support or store approval |
| Dashboard | Defined metric and reconciliation to underlying sample records | Recovering historical data not captured by any connected source |
| Snapshot/provisioning | Actual target-account load with omissions and dependencies recorded | Assumption that credentials, live data and every asset transfer automatically |

### 12.3 Handling vendor rejection, incidents and defective work

| Event | Distinction needed for costing | Proposed contract treatment; estimate only |
|---|---|---|
| Template/A2P/merchant rejection | Your incomplete submission versus vendor/business eligibility | Correct your included submission; price approved new research/rework separately when outside scope |
| Workflow fails acceptance | Scoped defect versus changed requirement | Fix the scoped defect within delivery; a new branch/channel gets an additional-unit quote |
| Provider outage | Waiting time versus active diagnosis/recovery | Charge only agreed active incident labour, not every elapsed outage hour |
| Repeated failed delivery | Channel rejection versus workflow duplication | Inspect actual billed attempts; reverse only credits/refunds actually granted |
| Client supplies dirty data | Existing data-quality scope versus newly discovered corruption | Evidence and a bounded cleanup estimate precede mass changes |
| External API changes | Original promised support term versus new compatibility work | Use included maintenance if covered; otherwise quote affected mappings/auth/tests |
| Accidental deletion | Restore capability versus investigation only | Quote known restore work; do not sell guaranteed full recovery without a tested source |
| Licence/subscription cancellation | Workflow stop versus actual paid resource cancellation | Record each cancelled resource and effective date; outstanding commitments remain explicit |

### 12.4 Minimum line-item record

Every standalone job or addition can be recorded with these fields:

`Parent service ID → atomic unit(s) → quantity → delivery mode/access gate → prerequisites → chosen labour hours/rate → labour markup → one-time provider costs → recurring provider resources → metered units/rates/credits → recurring work quantity → local acceptance → excluded scope → warranty/change rule → tax/FX/collection treatment.`

This is a reference schema, not a mandatory approval workflow. It makes the quote auditable while keeping vendor cost, build effort, managed work and markup distinct.

## 13. Itemised build examples

These examples demonstrate **bottom-up agency costing**, not vendor tariffs, fixed offers or market observations. Chosen effort lies within the atomic-unit ranges. To make the arithmetic inspectable, C labour sells at **2.5× cost (150% markup)** and T labour at **2× cost (100% markup)** here. Other multipliers within the stated bands can be selected.

Local checks are included in each unit. The separate end-to-end line covers the interactions between units and handover, not a second charge for repeating the same local check. Choose these itemised estimates **instead of** the overlapping parent-service setup totals. None includes paid platform access, software, messages, AI tokens, ads, hosting, taxes or collection costs unless explicitly listed.

### 13.1 Three-touch WhatsApp nurture on an already-connected account

Parents: WAP03, WAP05 and WAP04. Scope: three new templates in one language, three follow-up touches and one audience batch of up to 1,000 existing opted-in records. Existing approved number/business connection is a prerequisite.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| WAP-U02 — Prepare and submit one template in one language | 3 × 1h C | ₹1,500 | ₹3,750 |
| WAP-U03 — Add one template touch, eligibility condition and opt-out branch | 3 × 1.5h C | ₹2,250 | ₹5,625 |
| WAP-U04 — Prepare one audience batch, up to 1,000 existing opted-in records | 1 × 0.75h C | ₹375 | ₹937.5 |
| End-to-end stop/reply/re-entry tests and handover | 1 × 1.75h C | ₹875 | ₹2,187.5 |
| **Labour total only** | **10h** | **₹5,000** | **₹12,500** |

Optional operations: RUN12 twice/month at 1 hour per review = ₹1,000 labour cost and ₹2,500 labour fee at the chosen multiplier. Add W fixed subscription once if not already included; bill actual template deliveries/category/destination, any AI use and premium actions separately. New number verification, translation and new offer copy are additional units.

### 13.2 Sales pipeline with three lead-routing rules

Parents: SAL01, SAL05, SAL08, SAL03 and CRM04. Scope: one five-stage pipeline, three ownership rules, one escalation, two Smart Lists and one source mapping. Existing users/data fields are available.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| SAL-U01 — Configure one pipeline with up to 5 stages and value conventions | 1 × 1.5h C | ₹750 | ₹1,875 |
| SAL-U02 — Add one lead-assignment condition and fallback owner | 3 × 1h C | ₹1,500 | ₹3,750 |
| SAL-U05 — Add one overdue-task escalation branch | 1 × 1h C | ₹500 | ₹1,250 |
| CRM-U02 — Define one Smart List with up to 3 filter conditions | 2 × 0.75h C | ₹750 | ₹1,875 |
| SAL-U06 — Map one inbound lead source/UTM into a CRM source field | 1 × 1h C | ₹500 | ₹1,250 |
| OPS-U08 — Document one business flow, ownership and failure-recovery path | 1 × 1.5h C | ₹750 | ₹1,875 |
| Integrated routing, duplicate, escalation and permissions checks | 1 × 2h C | ₹1,000 | ₹2,500 |
| **Labour total only** | **11.5h** | **₹5,750** | **₹14,375** |

Optional operations: RUN03 four times/month at 1 hour = ₹2,000 labour cost and ₹5,000 labour fee. Add only actual channel/notification and premium-action usage. Sales-rep labour and deal commission are outside the implementation fee.

### 13.3 Three-staff booking with two reminders

Parents: CAL01, CAL02 and CAL05. Scope: one availability pattern, three staff/conflict mappings and two reminders. Payments, service menus and migration are excluded.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| CAL-U01 — Configure one weekly availability pattern, buffers and booking notice | 1 × 1h C | ₹500 | ₹1,250 |
| CAL-U02 — Add one staff member and conflict-calendar mapping | 3 × 0.75h C | ₹1,125 | ₹2,812.5 |
| CAL-U03 — Add one reminder with a reschedule/cancel route | 2 × 1h C | ₹1,000 | ₹2,500 |
| Cross-calendar time-zone/cancellation tests and handover | 1 × 1.5h C | ₹750 | ₹1,875 |
| **Labour total only** | **6.75h** | **₹3,375** | **₹8,437.5** |

Optional operations: RUN07 once/month at 1 hour = ₹500 cost and ₹1,250 labour fee. Add channel usage for actual reminders. A staff calendar is not an additional HighLevel sub-account; a separately managed branch may be.

### 13.4 Six-section landing page, conditional intake and thank-you page

Parents: WEB04, WEB01, WEB06 and WEB17. Scope: supplied text/artwork, six sections in a known design system, one conditional form path, a separate thank-you page and one domain connection.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| WEB-U01 — Build one reusable responsive section with supplied copy/image | 6 × 1.5h C | ₹4,500 | ₹11,250 |
| WEB-U02 — Add one conditional form path with up to 3 fields | 1 × 1h C | ₹500 | ₹1,250 |
| WEB-U03 — Add one thank-you/next-step page to an existing funnel | 1 × 1.5h C | ₹750 | ₹1,875 |
| WEB-U05 — Connect one domain/subdomain to an existing site | 1 × 1.5h C | ₹750 | ₹1,875 |
| Mobile/form/source/redirect end-to-end checks and handover | 1 × 2h C | ₹1,000 | ₹2,500 |
| **Labour total only** | **15h** | **₹7,500** | **₹18,750** |

Optional operations: RUN05 once/month at 1 hour = ₹500 labour cost and ₹1,250 labour fee. Domain registration/licences, actual sending, original copy and tracking-provider work are additional. The scope is larger than WEB04 alone because it includes conditional intake, thank-you page and domain work.

### 13.5 Website AI FAQ and qualification with 30 evaluation cases

Parents: AI01, AI03, AI04 and AI19. Scope: two bounded supplied knowledge sources, persona/boundary configuration, two qualification mappings and three batches of 10 defined test cases. Existing website and chat connection are prerequisites.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| AI-U01 — Clean/import one knowledge source, up to 10 supplied pages or one 20-page file | 2 × 1.5h C | ₹1,500 | ₹3,750 |
| AI-U02 — Configure one bot persona, objective and prohibited-action boundary | 1 × 3h C | ₹1,500 | ₹3,750 |
| AI-U03 — Map one qualification answer to a field and human-handoff condition | 2 × 2h C | ₹2,000 | ₹5,000 |
| AI-U08 — Run and annotate 10 defined AI test conversations/scenarios | 3 × 2.5h C | ₹3,750 | ₹9,375 |
| Cross-flow human handoff and owner training | 1 × 1.5h C | ₹750 | ₹1,875 |
| **Labour total only** | **19h** | **₹9,500** | **₹23,750** |

Optional operations: RUN31 once/month at 3 hours = ₹1,500 labour cost and ₹3,750 labour fee. AI test/live inference, optional AI plan and channel costs are separate. Adding booking tools, another language or a phone agent changes both build effort and run-time costs.

### 13.6 One-object CRM integration on an existing app/server foundation

Parents: INT04, INT07, INT09 and INT11. Scope: one payload mapping, one conflict rule, one token-refresh path, retries/replay, two flow/runbook documents and an integrated failure test. Existing server/auth registration/hosting are prerequisites.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| INT-U03 — Map one webhook payload, up to 10 fields, to an existing endpoint | 1 × 4h T | ₹4,800 | ₹9,600 |
| INT-U04 — Add one two-way identity/conflict rule for an existing object sync | 1 × 6h T | ₹7,200 | ₹14,400 |
| INT-U05 — Implement one token-refresh/permission-error path in an existing OAuth app | 1 × 8h T | ₹9,600 | ₹19,200 |
| INT-U06 — Implement one retry/backoff/dead-letter/replay path | 1 × 8h T | ₹9,600 | ₹19,200 |
| OPS-U08 — Document one business flow, ownership and failure-recovery path | 2 × 1.5h C | ₹1,500 | ₹3,750 |
| End-to-end integration/revocation/replay checks | 1 × 6h T | ₹7,200 | ₹14,400 |
| **Labour total only** | **35h** | **₹39,900** | **₹80,550** |

Optional operations: RUN35 four times/month at 2 engineering hours = ₹9,600 labour cost and ₹19,200 labour fee. Add external provider tasks, paid HighLevel actions, hosting and storage. This does not include initial app/server infrastructure or a second synced entity.

### 13.7 Three-plan SaaS provisioning on an eligible agency account

Parents: SAS02, SAS03, SAS04, SAS05 and SAS11. Scope: three SaaS plans, three eligible rebilling categories, one test location, one existing asset-group snapshot and one billing reconciliation. Working eligible provider and agency entitlements are prerequisites.

| Component | Quantity × chosen hours | Agency labour cost | Chosen labour fee |
|---|---:|---:|---:|
| SAS-U01 — Configure one SaaS plan's price/entitlement matrix | 3 × 3h C | ₹4,500 | ₹11,250 |
| SAS-U02 — Configure one eligible usage-rebilling category | 3 × 1.5h C | ₹2,250 | ₹5,625 |
| SAS-U03 — Provision one additional location from an approved existing template | 1 × 3h C | ₹1,500 | ₹3,750 |
| SAS-U04 — Package one existing asset group into a snapshot and test load | 1 × 3h C | ₹1,500 | ₹3,750 |
| SAS-U07 — Reconcile one location's add-on/usage bill for one month | 1 × 2h C | ₹1,000 | ₹2,500 |
| Provisioning/payment-failure/entitlement end-to-end checks | 1 × 3.5h C | ₹1,750 | ₹4,375 |
| **Labour total only** | **25h** | **₹12,500** | **₹31,250** |

Optional operations: RUN39 once/month at 3 hours = ₹1,500 labour cost and ₹3,750 labour fee for its defined five-location reconciliation scope. Add actual agency platform, payment collection, enabled add-ons and client consumption. Founding plan purchase does not guarantee Stripe onboarding or enable Razorpay off-session wallet charges.

### 13.8 Add the vendor bill without counting it twice

For any itemised build above, complete the following lines using the recorded vendor rates/actual account quote:

| Bill layer | One-time cost | Monthly/usage cost | Client pricing basis |
|---|---|---|---|
| Build | Selected atomic labour + integrated QA/handover | None unless recurring operations selected | C/T on chosen labour, as itemised |
| Platform | Setup/transfer fees only if actually purchased | One agreed allocation of the agency/client plan | Explicit access subscription or client-paid platform |
| Enabled products | Actual one-time licence/activation fee | Actual W/R/S/P/IP/hosting instances | V, or client pays provider directly |
| Consumption | Testing charges that are not covered | Actual E/W/P/A/F/I units, adjusted once for eligible credits | U or an explicit fixed-unit client tariff |
| Operations | None if already included in setup | Defined RUN unit quantities or one combined M allowance | C/T; no duplicate staffing/support labour |
| Client pass-through funds | Actual purchased goods/setup hardware | Ads, rewards, payouts, gateway/fulfilment as contracted | P or explicit separately identified fee |
| Collection/FX/tax | Actual payment and non-recoverable costs | Actual recurring collection, conversion and tax treatment | Included/disclosed under the contract; no universal invented percentage |

`Full job contribution = all earned client fees − all direct costs for the same scope/period.`

Prepaid wallets, affiliate funds, deposits and gift-card face value require their own balances; they are not automatically earned service fees. Where the vendor rate is unresolved, keep it as **quote required**, state the billing meter and complete that line before presenting an all-inclusive total.

## 14. Frontend app coverage audit — spm-ts

**Audit date: 31 October 2026.** This section closes the gap between a service catalogue organised by customer outcome and the actual app surfaces in the supplied frontend. Every inventoried app handle is mapped below; route modules and local app/page directories receive separate coverage maps. Implementations discovered here extend the earlier catalogue rather than replacing its pricing model.

### 14.1 Audited boundary and evidence

The audited checkout is `/Users/kforcode/Developer/Highlevel/frontend/spm-ts`, commit `baff64a4e999d35b00964ab90c72b7c939816e7b`. This is a **source inspection**, not a live feature-entitlement or production-availability test. A configured remote, route, or production URL does not establish a purchased licence, a working remote, a public release, API parity or a ₹0 vendor price.

| Inventory surface | Items inspected | Interpretation |
|---|---:|---|
| Runtime remote-app Config | 113 handles | Locally declared federation configuration |
| Async remote-app Config | 14 handles | Includes overlaps with runtime configuration |
| iframe-app Config | 33 top-level handles | Includes preview/legacy helpers and nested prospecting configuration |
| Deduplicated handle union | 154 handles | Every handle has an explicit mapping in section 14.3 |
| Literal defineAsyncMicroApp calls | Checked against the union | No extra literal app handle outside those declarations was found |
| Agency/location route modules | 90 files | Includes index/guarded/fallback modules; section 14.4 |
| Native app/page directories | 101 directories | `src/apps` and `src/pmd/pages`, excluding `__tests__`; section 14.5 |

The counts measure source entries, **not 154 commercial products**. Preview URLs, alternate transports, multiple builders and legacy/new versions can implement the same customer capability. An inventory item is captured when it has a priced-service mapping, an explicit conditional implementation, or an explicit internal/technical classification.

Primary local evidence:

- [Runtime app declarations](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/config/runtimeRemoteApps.ts), [async declarations](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/config/async-remoteApps.ts), [iframe declarations](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/config/iframeApps.ts).
- [Location route composition](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/routes/location/index.ts), [agency route composition](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/routes/agency/index.ts), and their referenced route files.
- [Detailed app coverage audit](/Users/kforcode/Developer/K/agencybuisness/highlevel-app-coverage-audit.json): exact handle declarations, loader/code references, route paths, directory mappings and input hashes. This is the machine-readable companion to this document; it does not contain customer records, credentials or copied environment files.

**Status vocabulary:** Covered = named services already cover the commercial work. Conditional = the app is wired but delivery depends on access, working remote capabilities or a still-unverified commercial tariff. Technical = shell, infrastructure, internal diagnostic, preview or vendor-support surface; no independent customer product is inferred. Alias/helper = a different transport/view for an already-covered capability.

### 14.2 Additional app-specific service scopes and prices

These **41 supplementary service scopes** make frontend-discovered apps explicit. All setup costs and resale ranges remain **estimates** using section 1's ₹500/hour C and ₹1,200/hour T assumptions. Monthly M-bands are optional managed-work allowances, not vendor licence prices. Do not add one of these scopes again when the same work is included in an existing service or solution.

**Q = vendor tariff/allowance unresolved:** obtain the account's current commercial terms. Q is not zero, included or a retail price. N/I/X/B and other cost codes retain their original meanings. Any beta/access gate applies before implementation; external/custom work is explicit. An implementation quote does not guarantee unobserved remote features.

| Service ID / defined scope | Delivery / additional vendor costs | Effort → agency labour cost | Indicative setup fee | Monthly work | Markup | Access / price exception |
|---|---|---:|---:|---|---|---|
| AUD01 — Native ticketing setup: ticket list/detail/settings, 5 users and agreed workflow links | B+Q+E+W | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C | crm.tickets gate and ticket/settings scopes; source-backed app distinct from a CRM-pipeline workaround |
| AUD02 — Native ticket workflow/SLA implementation: 3 supported status/owner/escalation rules | B+Q+F+E | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Implement only actions/statuses supported in the enabled remote; email-to-ticket/omnichannel parity requires a test |
| AUD03 — Restaurants menu setup: 30 supplied items, categories and supported option rules | B+Q+G | 10–20h → ₹5,000–10,000 | ₹10,000–30,000 | M3 | C | Restaurant industry plus eligible agency industry/SaaS gate; unsupported modifier/POS behaviour separately scoped |
| AUD04 — Restaurants floor/table setup: up to 12 tables and one supported layout | B+Q | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Floor route is confirmed; capacity/turn-time rules must be tested in the remote |
| AUD05 — Restaurants reservations: one venue, booking settings and 3 customer notifications | B+Q+E+W | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Reservation/settings routes exist; payment/no-show/availability features are conditional on account implementation |
| AUD06 — Restaurants guest website/online ordering: branding and up to 30 supplied menu items | B+Q+G+D | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C | Separate restaurant guest-site route; not proof of every native store/checkout capability |
| AUD07 — Restaurants pickup/delivery configuration: service region, hours and supported fulfilment rules | B+Q+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Delivery carrier, courier staffing, maps/route costs and merchant charges extra |
| AUD08 — Restaurant POS/delivery connector: one provider, order/status mapping and retries | X+I+H+F | 32–80h → ₹38,400–96,000 | ₹57,600–2,40,000 | M7 | T | External integration unless actual native connector is verified; no Swiggy/Zomato/POS compatibility inferred |
| AUD09 — Native Visibility AI onboarding/report: one brand and up to 10 agreed monitored queries | Q+S | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C | App route/loader confirmed; supported engines/queries, allowances and price must be checked in the remote |
| AUD10 — Native Meeting Room setup: 3 hosts, guest/waiting-room settings and calendar link tests | B+Q | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Labs plus location-feature gate in checkout; native conference app distinct from physical scheduling resources |
| AUD11 — Meeting recording/transcript/summary workflow: 3 meeting scenarios and access/retention handoff | B+Q+A+H | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Recording does not automatically enable transcription; conference storage/AI tariff not borrowed from PSTN phone rates |
| AUD12 — Native Community Live Room event: one event, eligible audience and host rehearsal | N+Q+E | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Native alternative to Zoom/Meet where enabled; live moderation/production and commercial usage terms separate |
| AUD13 — Native Events build: ticketed or RSVP event, 3 ticket types and 3 sessions/speakers | Q+G+E | 12–24h → ₹6,000–12,000 | ₹12,000–36,000 | M3 | C | Public event app differs from calendar and community events; confirm access, ticket/payment/refund rules |
| AUD14 — Event check-in operation setup: attendee import, 3 authorised devices and duplicate check-in tests | Q+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Check-in route verified; devices, venue Wi-Fi, badges and on-site staffing extra |
| AUD15 — GoKollab activation/navigation: account linkage, existing community/course discovery and handoff | Q+I | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C | Distinct source app; verify account/channel visibility and current activation terms rather than assume a second branded app licence |
| AUD16 — Membership analytics: progress/assessment/revenue views and 8 metric definitions | N+Q | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Analytics revamp is feature-gated; available historical assessment/progress data limits reconstruction |
| AUD17 — AI agent logs/health operations setup: 30 run samples, failure taxonomy and escalation | Q+A | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Agent logs/health remotes are distinct; log visibility and native monitors need account proof |
| AUD18 — AI Insights/Performance configuration: one supported insight/metric workflow and validation | Q+A | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Source confirms named apps, not every promised insight/output; scope only demonstrated remote functions |
| AUD19 — AI memory/context governance: one agent context, retention rules and 10 retrieval/isolation tests | Q+A+I | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Memory app differs from a knowledge library; actual deletion, persistence and user/account isolation must be verified |
| AUD20 — Reusable agent action/tool pack: 3 supported actions, inputs/outputs and failure handling | Q+A+I+F | 16–40h → ₹19,200–48,000 | ₹28,800–1,20,000 | M6 | T | Actions Platform/agent-builder capabilities and running/tool charges checked separately |
| AUD21 — Industry-agent configuration: one supported industry task, 3 tools and 20 acceptance cases | B+Q+A+I | 20–40h → ₹10,000–20,000 | ₹20,000–60,000 | M4 | C | Industry-agent remote is not proof of autonomous regulated advice or restaurant voice support |
| AUD22 — Branded desktop app configuration/rollout: agency brand profile and 5 supported-device tests | Q+D+I | 16–32h → ₹8,000–16,000 | ₹16,000–48,000 | M3 | C | Desktop customizer is distinct from the $497 CRM mobile app and $49 member app; vendor/distribution tariff unresolved |
| AUD23 — Native Media Studio/Clips setup: supplied long video into 3 reviewed short clips | Q+A+D | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Clip generation/editor wiring confirmed; processing/media credits, limits and rights separate |
| AUD24 — Creator Studio production workspace: brand references, 5 prompts and approval/export process | N+Q+A+D | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Generation allowance differs by actor/AI plan; filming, licensed assets and human review remain delivery work |
| AUD25 — Commerce DocumentX layout system: 3 supported invoice/estimate document layouts and preview tests | N+Q+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M2 | C | payments/v2/layouts hosts layoutListMfaApp and layoutBuilderMfaApp; these are commerce document layouts, not email layouts |
| AUD26 — Contact restoration diagnostic: deleted-contact eligibility check and one supported restore batch | N+Q | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M0 | C | Restore app exists; retention window, recoverable entities and successful recovery must be confirmed |
| AUD27 — Native preference centre: 3 channel choices, DND/suppression mapping and tests | N+E+W | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Preference state, legal consent evidence and message-provider opt-out need reconciliation |
| AUD28 — Audit/access hardening: 3 roles, supported MFA/session settings and one audit-report scope | N+Q | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Only authorised controls; not an independent security certification or full penetration test |
| AUD29 — Custom menu/custom page links: 4 branded destinations and visibility/embedded-access tests | N+I+H | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Navigation links do not grant backend access or provide arbitrary external SSO |
| AUD30 — Domain resale/renewal administration: 3 domains, ownership/renewal inventory and client pricing | N+D+R | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Registration/renewal/transfer/redemption separate; do not treat every available TLD as same price |
| AUD31 — Mailbox/domain warm-up and blacklist/postmaster monitoring setup: 2 eligible mailboxes/domains | Q+E+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C | Specific routes exist; mailbox/warm-up/monitor tariffs and client-owned mail provider remain separate |
| AUD32 — Social listening/comment operations: 3 supported profiles, keywords and response triage | Q+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M3 | C | Route-backed listening/comment app paths; supported networks/quotas and data access must be checked |
| AUD33 — Facebook/Meta marketing-message setup: eligible page, opt-in and one campaign path | Q+I | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Meta marketing-message UI is distinct from WhatsApp and unrestricted Messenger replies; eligibility and charges unresolved |
| AUD34 — In-app notification/preferences setup: 5 supported alerts, owners and delivery choices | N+Q+E+P | 4–8h → ₹2,000–4,000 | ₹4,000–12,000 | M2 | C | In-app alerts versus SMS/email/mobile push have different delivery requirements and costs |
| AUD35 — Course badge/certificate and assessment configuration: 2 templates and eligibility checks | N+Q | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Native course certificate/badge routes; accredited awards, proctoring and university systems excluded |
| AUD36 — Power Dialer setup: 5 users, dispositions, queues and eligible route tests | Q+P | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Native dialer remote is explicit; calling capabilities, pacing/queue options and India restrictions still apply |
| AUD37 — Native product inventory administration: 25 SKUs, variants and one stock-update scenario | N+Q+G | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Products/inventory is not an implied full warehouse/ERP/POS ledger |
| AUD38 — Invoice integration setup: one supported provider and invoice/payment reconciliation | I+Q+G+F | 12–30h → ₹14,400–36,000 | ₹21,600–90,000 | M6 | T | Separate invoices-integrations surface; actual provider/API support, subscription and tax/accounting scope defined |
| AUD39 — CRM shared-document portal: 3 document groups, member permissions and one access-revocation test | N+Q | 6–12h → ₹3,000–6,000 | ₹6,000–18,000 | M2 | C | Shared CRM files, contracts/e-signatures and external file backups are distinct scopes |
| AUD40 — Features/limits and billing entitlement audit: 5 enabled products across 3 test locations | N+Q+G | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | Compare actual access, paid instances and rebilling; support tooling/internal debugger is not client software |
| AUD41 — Native Ask AI evaluation child: 20 supported cases, one evaluation configuration and output review | Q+A | 8–16h → ₹4,000–8,000 | ₹8,000–24,000 | M3 | C | AskAIEvaluation.vue loads copilotApp EvaluationPage; separate landing page is placeholder; actual client access, scoring features and inference tariff must be confirmed |

**Public corroboration:** [Meeting Room overview][S65] confirms native rooms, calendar links and meeting artefacts; [Community Live Rooms][S67] confirms the native community-event option. [Events documentation][S66] confirms RSVP/ticketed registration, schedules and attendee check-in. These pages do **not** supply a complete all-in conference/event tariff; their unknown usage/limit terms stay Q.

**Local restrictions that materially change this reference:**

- Restaurants now has source-confirmed overview, orders, menu, floor, integrations, reservations, website and pickup/delivery settings routes. The current guard actually checks restaurant industry plus eligible company industry/SaaS conditions; older comments mention an extra beta flag, so do not quote comment text as the executable rule. Public release, connected POS/delivery providers and vendor prices remain unresolved.
- Native ticketing uses a hidden per-location `crm.tickets` flag plus ticket/settings permissions. It is not the same as opening a support ticket with HighLevel's own helpdesk, nor the pipeline-based service MSG18.
- Meeting Rooms uses `meet.meetingRoom` plus the location `meeting-room` permission in the inspected frontend. Physical calendar rooms/resources are a different feature. Native video meeting costs cannot be inferred from LC Phone recording rates.
- The `ai-evaluations` landing view currently inserts placeholder content, but its `ask-ai` child separately loads `copilotApp` → `EvaluationPage`. AUD41 captures this conditional native child; existing AI19 and AI-U08 price agency-run testing. Neither host proves a generally available, fully functioning evaluation suite or its price; a custom evaluation tool remains an explicit X/T project.
- Visibility AI is now source-confirmed as a named native remote/route. Its supported engines, quotas, price and runtime availability are still unverified; AUD09 captures conditional native onboarding while REP17 remains an external/available-tool reporting option.

Local evidence: [Restaurants routes](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/routes/location/restaurants.ts), [Restaurants guard](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/routes/guards/restaurantsAccessGuard.ts), [ticketing flag](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/store/ticketing.ts), [ticketing host](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/apps/ticketing/TicketingPage.vue), [meeting gate](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/pmd/navigation/meetingsRoomAccess.ts), [evaluation placeholder](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/apps/aiEvaluations/AIEvaluations.vue), [Visibility AI host](/Users/kforcode/Developer/Highlevel/frontend/spm-ts/src/pmd/pages/visibility-ai/VisibilityAiBuilder.vue).

### 14.3 Complete app-handle mapping

Every one of the 154 deduplicated configuration handles appears exactly once in this mapping. A row may group aliases/builders for the same commercial capability. Original service IDs and AUD service IDs identify priced scope; Q flags remain unresolved. Cost units for covered apps come from section 2 and their referenced service rows.

| Capability / inventory status | Exact app handles | Priced scope / reference | Cost/availability boundary |
|---|---|---|---|
| Shell/navigation — Technical | `switchyardApp` | AUD29; SAS01 | Navigation shell; configure permitted menus, do not sell an independent Switchyard licence |
| Voice and dialer — Covered/conditional | `voiceAiApp`, `powerDialerApp` | AI08–AI11; MSG15; AUD36 | A/P; eligible countries/routes and dialer tariff checked |
| Payments/widgets — Covered | `leadgenPaymentsApp`, `paymentsApp`, `paymentsAppUrl` | PAY01–PAY13; AUD40 | G; same payment capability through several host components |
| Products/store catalogue — Covered | `productsApp`, `storeCatalogApp`, `storeWidgetApp`, `ecommerceApp` | COM01–COM04; AUD37 | G/I; native products/store widgets and legacy ecommerce alias |
| Reviews/reputation — Covered | `reputationApp` | REP01–REP06 | E/W/P/A where actually used |
| Course awards — Covered | `certificatesApp` | EDU03; AUD35 | Course certificates/badges; not agency certification subscription |
| Listings — Covered | `yextApp` | REP09; S04 | S; country/directory eligibility |
| Native Visibility AI — Conditional | `visibilityAiApp` | AUD09; REP17 | Source-confirmed native app; Q/actual engines and limits |
| AI Studio/Vibe — Covered/conditional | `vibeEditorApp`, `vibeBuilderAppUrl` | APP01–APP05 | A/H; source labels are related builders, not proof of identical releases |
| Email builder/preview — Covered/helper | `emailBuilderMfaApp`, `emailBuilderApp`, `emailPreviewApp`, `emailPreviewAppUrl`, `newEmailPreviewBetaUrl` | EML02–EML05 | E/A; builder/preview/legacy transports not separate customer licences |
| Template Library — Covered | `templateLibraryApp`, `templateLibraryAppUrl` | SAS07; WEB15; EML02 | Asset licences/reuse terms, not one fee for every preview |
| Advertising — Covered | `adPublishingApp` | ADS01–ADS12 | Ad spend separate; supported campaign type tested |
| Loyalty — Conditional | `loyaltyApp` | RET11–RET13 | B/Q; merchant reward liability separate |
| Reporting — Covered | `reportingApp`, `funnelWebsiteAnalytics` | OPS01–OPS06; ADS11; WEB13 | Data source completeness and attribution limits |
| Notifications — Covered | `notificationApp` | AUD34; SAL04; OPS02 | Native alerts versus metered external delivery |
| WordPress — Covered | `wordpressApp` | WEB21–WEB22 | H/D and actual hosting tier |
| Resale/wallet — Covered | `resellingApp`, `walletKitApp`, `locationBillingApp`, `platformBillingApp` | SAS03; SAS11; AUD40 | Agency/client wallet and actual add-on instances; no extra app licence inferred |
| Agency affiliate portal — Technical/account programme | `affiliateDashboardApp` | Section 7; SAS11 | HighLevel affiliate earnings/programme, distinct from client AFF services |
| Agency reporting — Covered | `agencyDashboardApp` | OPS06; SAS11 | Agency MRR/usage/report administration; no standalone inferred fee |
| SaaS — Covered | `saasApp` | SAS02–SAS04; AUD40 | Founder and compatible collection/provider gate |
| Company/location administration — Covered | `companyApp`, `locationsApp`, `crmLocationAppURL` | CRM01; SAS04; SAS10 | Agency/company/location setup; not automatically the B2B Companies object |
| Phone integration — Covered/conditional | `phoneIntegrationApp` | MSG08–MSG17 | P/I plus regional and registration constraints |
| Content AI — Covered | `contentAIApp` | SOC04–SOC10; AI17 | A/D and actor-specific AI allowance |
| Internal billing tools — Technical | `internalToolsApp`, `fpDebuggerApp` | Section 14.6 | Authorised internal/debug/support surfaces; no independently sellable client app |
| Preference management — Covered | `preferenceManagementApp` | AUD27; CRM11 | Reconcile UI preference with actual channel DND/consent |
| Gift cards — Covered | `giftCardsApp` | COM11–COM12 | G; face value is merchant liability |
| Conversation utilities — Covered/helper | `conversationsUtilitiesApp` | MSG01; MSG06; SAL04 | Inbox utilities/snippets/manual actions covered by workflow or operations scope |
| Translation feedback — Technical | `i18nFeedbackApp` | Section 14.6; WEB19 | Platform feedback UI; separate client translation work only if requested |
| Contact views — Covered | `contactsHighriseApp`, `contactsApp` | CRM01–CRM04 | Alternative contact UIs share customer-data scope |
| Object settings — Covered | `crmObjectsSettingsApp`, `customFieldsApp` | CRM05; CRM08–CRM09 | Fields/schema/settings, not separate per-view licences |
| Contact restore — Conditional | `ghlContactRestoreApp` | AUD26; CRM15 | Recovery window/records depend on actual product; no restore guarantee |
| Brand assets — Covered | `brandBoardsApp` | WEB15; SOC10; AI17 | Brand board/voice assets and actual generation/licences |
| External tracking — Covered | `externalTrackingApp` | ADS07–ADS10; SAL03 | Tracking source and privacy/attribution constraints |
| SEO — Covered | `seoApp` | REP10–REP14 | S; quotas/projects/paid content separate |
| Countdowns — Covered | `countdownTimerApp` | WEB12 | One page asset; no freestanding product price inferred |
| Payment links — Covered | `leadgenPaymentLinksApp` | PAY03 | G; hosted checkout dependency |
| QR tools — Covered | `qrCodeListApp`, `qrCodeBuilderApp` | WEB16; REP02 | One QR capability with list/builder views |
| Social Planner — Covered/conditional | `socialPlannerApp` | SOC01–SOC12; AUD32 | Supported channels/formats; listening quota/price checked |
| Proposal templates/builders — Covered/helper | `proposalsEstimateTemplateApp`, `proposalsEstimatesApp`, `proposalBuilderAppUrl`, `proposalTemplateBuilderAppUrl`, `proposalBuilderPreviewUrl` | PAY06–PAY08 | Same document lifecycle; builder/preview not separate fees |
| Custom objects — Covered | `customObjectsApp` | CRM08–CRM09 | Schema, limits, associations and per-surface support |
| Conversations — Covered | `conversationsV2App`, `conversationsAppUrl` | MSG01–MSG07; WAP13 | Connected channels cost separately; new UI not new channel |
| Authentication — Technical/covered administration | `authApp` | CRM10; AUD28 | Native security/user configuration; no unauthorised identity-service resale |
| Media library/editor — Covered | `mediaCenterApp`, `mediaEditorApp` | WEB15; SOC05–SOC06; AUD39 | Storage/licensed assets and actual media processing extra |
| Funnels/websites — Covered | `funnelWebsiteApp`, `funnelBuilderAppURL` | WEB01–WEB20 | Actual hosting/domain/integration dependencies |
| Redirect/domain connection — Covered | `redirectApp`, `domainConnectApp` | WEB17–WEB18 | Domain ownership, DNS and renewal distinct |
| Chat widget — Covered | `chatWidgetApp` | WEB10–WEB11; AI03 | Channel/AI usage if enabled |
| Onboarding/launchpad — Covered/helper | `onboardingApp`, `launchpadApp`, `newOnboardingFrontend` | CRM01; SAS04; OPS12 | Onboarding/configuration work; internal wizard not independent app subscription |
| Domain resale — Covered | `domainResellingApp` | AUD30; WEB17 | D/R; TLD/renewal/transfer price |
| Forms/surveys — Covered | `formSurveyApp`, `formBuilderAppURL` | WEB01–WEB03 | Form/payment/AI extras only if used |
| Users — Covered | `usersApp` | CRM01; CRM10 | Native users versus external operator staffing |
| CRM shared documents — Covered | `documentsApp` | CRM12; AUD39 | File permissions/portal sharing distinct from signed legal contract template |
| Knowledge — Covered | `knowledgeBaseApp` | AI01–AI02 | Source quality, refresh and running-agent inference distinct |
| Ask AI/Copilot — Covered | `copilotApp` | AI16; AI17; OPS12; AUD41 | Actor/plan usage; not unrestricted autonomous native actions |
| Agent Studio/Builder — Covered/conditional | `agentStudioApp`, `agentBuilderApp` | AI14–AI15; AUD20 | Agent product, allowed tools and billing meter checked |
| Agent logs/health — Conditional | `agentLogsApp`, `agentHealthApp` | AUD17; AI19 | Q/A; run visibility, monitors and troubleshooting scope |
| Agent performance/insights — Conditional | `performanceAiApp`, `insightsAiApp` | AUD18; OPS01 | Named remotes do not prove every advertised insight |
| Location settings — Covered | `locationSettingApp`, `settingsAppUrl` | CRM01; CAL01–CAL12; SAS11; AUD40 | Settings container, each actual configured feature separately scoped |
| Agent actions — Conditional | `actionsPlatformApp` | AUD20; INT03–INT06 | Tool/action entitlement plus A/F/I, no invented flat platform fee |
| Integration hub — Covered | `integrationsApp` | INT04–INT09; SAS08 | Provider support, Marketplace licence/tasks and APIs |
| AI memory — Conditional | `aiMemoryApp` | AUD19; AI16 | Q/A; distinguish persistent memory from uploaded knowledge |
| Estimates — Covered | `estimatesApp` | PAY06 | Provider/payment conversion and document lifecycle |
| Blogs — Covered | `blogsApp`, `blogsAppUrl` | WEB14; SOC12 | Editor/iframe variants share content scope |
| Labs — Technical/covered administration | `labsApp` | AUD40; Section 14.6 | Feature toggle is not commercial availability or an independent client licence |
| Native ticketing — Conditional | `ticketingApp` | AUD01–AUD02 | Hidden crm.tickets location flag and ticket/settings scopes; Q |
| AI Growth/promotion — Conditional/promotion | `aiGrowthApp`, `aiEmployeesApp` | AI03–AI17; Section 14.6 | App/offer pages do not establish free usage; actual AI plan applies |
| Implementation-expert marketplace — Technical/service procurement | `implementationExpertsMfaApp` | Section 14.6; OPS12 | Marketplace/expert selection and separate supplier contract, not a bundled technical entitlement |
| Desktop branding — Conditional | `desktopCustomizerApp` | AUD22 | Q; distinct desktop product, no mobile-app tariff assumed |
| Client portals/builders — Conditional | `clientPortalBuilder`, `aiAppBuilderApp` | APP06–APP08; EDU11–EDU13 | Client App Builder/portal version and Labs/access constraints |
| Industry agents — Conditional | `industryAgentsApp` | AUD21 | Demonstrated industry workflows only; Q/A/I |
| Events — Covered/conditional | `eventsManagementApp` | AUD13–AUD14; EDU16 | Native event registration/check-in; access and commercial rates checked |
| Restaurants — Conditional | `restaurantsApp` | AUD03–AUD08 | Industry/SaaS guard, real source routes and unresolved vendor tariff |
| Email sequences/home — Covered/helper | `emailSequenceApp`, `emailHomeV2App`, `emailMarketingApp`, `emailHomeAppUrl`, `newEmailHomeBetaUrl` | EML03–EML05; EML12–EML13 | E; versions/transport do not multiply email event charges |
| Membership analytics — Conditional | `membershipAnalyticsApp` | AUD16; EDU03 | Revamp feature flag; progress/assessment data support |
| Meeting Rooms — Conditional | `meetingsApp` | AUD10–AUD12 | Labs/permission plus conference-specific usage/recording terms |
| Communities/GoKollab — Covered/conditional | `communitiesApp`, `goKollabApp` | EDU05–EDU08; AUD15 | Account/member-app visibility and activation terms |
| Rental/service/field apps — Covered/conditional | `calendarRentalsApp`, `calendarServicesApp`, `fieldServicesApp` | CAL08–CAL18 | Three distinct products; Field Services private beta |
| Feature discovery — Technical | `featureDiscoveryApp` | Section 14.6; AUD40 | Discovery/onboarding UI; not a separately priced business capability |
| Snapshots — Covered | `snapshotsApp` | SAS05–SAS07 | Configuration licences/import/update; not live account data |
| Commerce document layouts — Covered/helper | `layoutListMfaApp`, `layoutBuilderMfaApp` | AUD25; PAY04–PAY08 | DocumentX commerce layout list/builder; not email layout components |
| Default email templates — Covered/helper | `defaultEmailTemplatesApp` | EML02; EML05 | Reusable email templates; E/A only where actually used |
| Media Studio/Clips — Conditional | `mediaStudioApp` | AUD23; SOC06–SOC07 | Editing/generation workflow and actual processing credits |
| Opportunities — Covered/helper | `opportunitiesApp`, `crmOpportunitiesAppURL` | SAL01–SAL14 | Legacy iframe and native deals UI map to same sales process |
| Calendar host/settings — Covered/helper | `calendarComponentsApp`, `appointmentModalApp`, `calendarSettingsApp`, `calendarAppURL` | CAL01–CAL14 | Booking modal/settings/host are not separate subscriptions |
| Bulk actions — Covered/helper | `bulkActionsApp` | CRM02–CRM04; CRM15 | Count actual mutations and charged downstream events; not automatic backup |
| Courses/membership settings — Covered | `membershipApp`, `membershipSettingsApp` | EDU01–EDU04; EDU14; AUD16 | Course content/offers/assessment/settings components |
| Marketplace — Covered | `marketplaceApp` | SAS08; INT09 | Seller licence/commercial terms and scope verified per installed app |
| Invoices/invoice integrations — Covered | `invoicesApp`, `invoicesIntegrationsApp` | PAY04–PAY05; AUD38 | Invoice UI plus provider adapter; G/I/F where used |
| Client affiliate manager — Covered | `affiliateManagerAppUrl` | AFF01–AFF06 | Client programme distinct from agency HighLevel affiliate portal |
| Creator Studio — Covered/conditional | `creatorStudioAppUrl` | AUD24; AI17; SOC10 | A/actor allowance, production labour and licences |
| Preview/widget helpers — Alias/helper | `builderPreviewUrl`, `calendarBetaPreviewUrl`, `formBetaPreviewUrl`, `funnelBetaPreviewUrl`, `surveyBetaPreviewUrl`, `widgetUrl` | WEB01–WEB07; CAL01; Section 14.6 | Rendering/preview endpoints, not additional client products |
| ISV/email/phone services — Covered/conditional | `isvAppUrl` | EML01; EML08–EML11; MSG08–MSG10; AUD31 | Actual sending/validation/domain/IP/phone/warm-up resource costs |
| Mobile customizer — Covered/conditional | `mobileAppCustomiserAppUrl` | SAS09; EDU13 | Identify CRM versus member app before applying R charge |
| Prospecting — Covered | `prospect` | REP15–REP16 | Nested frontendUrl is part of the same handle; S/sub-account sharing terms |
| Workflow builder — Covered | `workflowAppURL` | INT01–INT03; SAL07 | Standard actions, F and A/I billed by actual executed feature |
| Vendor support portal — Technical/support | `supportPortalUrl` | Section 14.6; OPS15 | HighLevel vendor helpdesk, distinct from native client ticketing |

### 14.4 Complete route-module coverage

The 90 agency/location route modules below are classified by commercial purpose. Paths are source-relative to `src/routes/`; index files compose routes, and restricted/suspended/auth-failure pages are technical states. Child paths within a module can be multiple views of one service, not additional products. Exact literal paths are retained in the companion audit.

| Source route module(s), relative to src/routes | Scope coverage | Exception / classification |
|---|---|---|
| `agency/affiliatePortal.ts`, `agency/partners.ts` | Section 14.6; AFF06 where separately implemented | Agency HighLevel affiliate/partner programme UI; partner-admin restrictions are not client programme access |
| `agency/aiAgentsContest.ts`, `agency/aiEmployeePromo.ts` | AI03–AI17; Section 14.6 | Contest/promotional surfaces; do not price them as another autonomous AI engine |
| `agency/aiUsage.ts`, `agency/askAi.ts` | AI16; SAS11; AUD17–AUD20 | Actor-specific AI/usage administration |
| `agency/dashboard.ts` | OPS06; SAS11 | Agency reporting |
| `agency/desktopWhitelabelApp.ts`, `agency/mobileAppCustomiser.ts` | AUD22; SAS09; EDU13 | Desktop/CRM-mobile/member-mobile products distinguished |
| `agency/ghlSwag.ts`, `agency/ideas.ts`, `agency/university.ts` | Section 14.6; OPS12 | Merchandise, feedback and education/professional development |
| `agency/implementationExperts.ts` | Section 14.6 | Expert procurement; vendor contract and fees separate |
| `agency/index.ts` | Section 14.1 | Route composition; not a separate product |
| `agency/integration.ts`, `agency/marketplace.ts` | INT09; SAS08 | App integrations and licences |
| `agency/launchpad.ts`, `agency/subAccounts.ts` | CRM01; SAS04; SAS10 | Provisioning/onboarding; shared and per-location resources distinguished |
| `agency/prospecting.ts` | REP15–REP16 | S, eligible agency/linked account rules |
| `agency/reselling.ts`, `agency/saas.ts` | SAS02–SAS03; SAS11; AUD40 | Subscription/usage/wallet and entitlements |
| `agency/settings.ts` | CRM01; CRM10; EML01–EML11; AUD28–AUD31; SAS14 | Agency settings, default emails, ISV, compliance, billing and permissions |
| `agency/snapshots.ts`, `agency/templateLibraryAdmin.ts` | SAS05–SAS07; WEB15 | Reusable assets, licences and deployment |
| `location/aiEmployeePromo.ts` | AI03–AI17; Section 14.6 | Offer/promotion, not an extra running AI tariff |
| `location/aiEvaluations.ts` | AUD41; AI19 | Landing page placeholder; Ask AI child loads a separate native evaluation component |
| `location/analytics.ts`, `location/custom-metric.ts`, `location/dashboard.ts`, `location/reporting.ts` | OPS01–OPS06 | Actual metric definitions, sources and reconciliation |
| `location/ask-ai.ts`, `location/copilot.ts` | AI16; AUD17–AUD20; AUD41 | Ask AI/Copilot routes/variants and evaluation support |
| `location/automation.ts` | INT01–INT03; INT10; AUD20 | Workflow builders, analytics/settings, legacy campaigns/triggers and source-wired Flowguard path |
| `location/blogs.ts`, `location/creator-studio.ts` | WEB14; SOC12; AUD24 | Blog/editor/content generation and media licences |
| `location/business.ts`, `location/contacts.ts`, `location/customObjects.ts` | CRM01–CRM09; AUD26–AUD27 | Native people/company/object records, views and restore limits |
| `location/calendars.ts`, `location/fieldServices.ts` | CAL01–CAL18 | Meetings/services/rentals and restricted Field Services |
| `location/conversations.ts` | MSG01–MSG18; WAP01–WAP15 | Inbox, manual actions, snippets, channels and telephony gates |
| `location/customMenuLink.ts`, `location/customPageLink.ts` | AUD29; APP09 | Navigation/embed customisation; not an external backend licence |
| `location/documentx.ts` | AUD25; PAY04–PAY08 | Commerce document-layout list/builder, distinct from email layouts |
| `location/documents-contracts/document-contracts-builder-preview.ts`, `location/documents-contracts/document-contracts-template-list.ts`, `location/documents-contracts/documents-contracts-builder.ts`, `location/documents-contracts/documents-contracts-list.ts`, `location/documents-contracts/documents-contracts-template-builder.ts` | PAY07–PAY08 | Document/contract list, templates, builder and preview share a document lifecycle |
| `location/events.ts` | AUD13–AUD14 | RSVP/ticketed event, orders, tickets, attendees, schedule and check-in |
| `location/form-builder.ts`, `location/quiz.ts`, `location/survey-builder.ts` | WEB01–WEB03 | Distinct capture/qualification experiences |
| `location/funnel-websites.ts` | WEB04–WEB22; COM01; EDU09–EDU11 | Funnels/sites/stores/webinars/client portal and associated builder/QR/domain paths |
| `location/index.ts` | Section 14.1 | Composition; repeated imports are not duplicate customer products |
| `location/integrations.ts` | INT04–INT09; SAS08 | Supported providers/scopes/runtime costs |
| `location/launchpad.ts` | CRM01; SAS04 | Setup/onboarding helper |
| `location/marketing.ts` | EML01–EML13; SOC01–SOC12; AFF01–AFF06; RET11–RET13; AUD23–AUD24; AUD32–AUD33 | Includes social listening, clips, native loyalty, brand voice, ads, email and affiliates |
| `location/membership.ts` | EDU01–EDU16; APP06–APP08; AUD10–AUD16; AUD35 | Course/settings/analytics/certificates/badges, communities, GoKollab, native Meetings and Client App Builder |
| `location/mobileApp.ts` | SAS09; EDU13 | Mobile app product and rollout, not desktop customization |
| `location/no-permissions.ts`, `location/restricted.ts`, `location/suspended.ts`, `location/verification.ts` | Section 14.6; CRM10; AUD40 | Access/billing/verification states; no independent product licence |
| `location/notifications.ts`, `location/reminders.ts` | AUD34; CAL05; SAL08 | Notification/reminder delivery and metered channels |
| `location/opportunities.ts` | SAL01–SAL14 | Sales opportunities/pipeline/forecast-related implementation |
| `location/payment-products/estimates.ts`, `location/payment-products/invoices-integrations.ts`, `location/payment-products/invoices.ts`, `location/payment-products/payment-links.ts` | PAY03–PAY06; AUD38 | Estimate/invoice/link/integration surfaces |
| `location/paymentSetup.ts`, `location/payments.ts`, `location/payments/integrations.ts`, `location/payments/subscriptions.ts`, `location/payments/transactions.ts` | PAY01–PAY05; PAY09–PAY15; AUD40 | Provider/mandate/transaction setup and actual compatibility |
| `location/payments/coupons.ts`, `location/payments/gift-cards.ts`, `location/payments/orders.ts`, `location/products/inventory.ts`, `location/products/products.ts`, `location/stores/abandoned-checkout.ts` | COM01–COM15; AUD37 | Product/stock/order/coupon/gift/recovery work; provider/merchant costs separate |
| `location/reputation.ts`, `location/seo.ts`, `location/visibilityAi.ts` | REP01–REP17; AUD09 | Reputation/Search Atlas versus source-confirmed native Visibility AI |
| `location/restaurants.ts` | AUD03–AUD08 | Source-confirmed restricted restaurant-specific product and all documented host child paths |
| `location/settings.ts` | CRM01–CRM13; CAL01–CAL14; AI01–AI17; AUD17–AUD20; AUD26–AUD31; AUD40 | Phone/WhatsApp, AI, users, objects, integrations, preferences, audit and domain/mail settings |
| `location/tasks.ts` | OPS07–OPS11 | Basic tasks versus full gated Project Management |
| `location/ticketing.ts` | AUD01–AUD02 | Native gated client ticket system, not vendor helpdesk |
| `location/vibe.ts` | APP01–APP05 | AI Studio/Vibe builder source naming; hosting and usage separate |

### 14.5 Complete local app/page-directory coverage

This second pass captures local pages whose commercial function may be absent from the remote-app names, including scoring, manual actions, native Meta marketing messages, audit logs, CRM view builders and legacy surfaces. Paths below are relative to `src/`. A directory can contain legacy code or host wrappers; source presence alone is not a release guarantee.

| Local directory path(s), relative to src | Priced scope / reference | Boundary |
|---|---|---|
| `apps/actionsPlatform` | AUD20; INT03–INT06 | Agent tool/actions; actual remote support and usage |
| `apps/agentHealth`, `apps/agentLogs` | AUD17 | Run/log health operations and actual permissions |
| `apps/agentStudio` | AI14; AUD20 | Flow/agent builder and runtime charges |
| `apps/ai-memory` | AUD19 | Persistent context/memory boundaries |
| `apps/aiEmployeePromo`, `pmd/pages/aiEmployees` | AI03–AI17; Section 14.6 | AI offering/promotion and actual entitlements |
| `apps/aiEvaluations` | AUD41; AI19 | Landing placeholder plus source-wired Ask AI evaluation child |
| `apps/aiUsage`, `apps/askAi`, `pmd/pages/copilot` | AI16; AUD17–AUD20 | User-scoped assistant/usage administration |
| `apps/conversations`, `pmd/pages/conversations` | MSG01–MSG18; WAP13 | Both local directory trees covered; channels and utilities |
| `apps/custom-fields` | CRM05 | Fields/validation/reuse |
| `apps/i18n-feedback` | Section 14.6 | Platform translation feedback; client translation work is WEB19 |
| `apps/implementationExperts` | Section 14.6 | Implementation specialist procurement |
| `apps/insights-ai` | AUD18 | Conditional insight/metric capability |
| `apps/knowledgeBase` | AI01–AI02 | Source ingestion, refresh and testing |
| `apps/manage-scoring` | SAL06 | Rule-based scoring, not automatically AI inference |
| `apps/manual-actions` | MSG06 | Manual queue/task operation; human staffing separate |
| `apps/phone-integration`, `apps/voice`, `pmd/pages/power-dialer` | MSG08–MSG17; AI08–AI11; AUD36 | Eligible calling/dialer/AI features and country restrictions |
| `apps/saas`, `pmd/pages/saas` | SAS02–SAS04; SAS11 | Both native directory trees covered; subscription/provision/billing |
| `apps/superAgents` | AI15; AUD19–AUD21 | Managed/specialised agent shell; exact supported features validated |
| `apps/ticketing` | AUD01–AUD02 | Location Labs plus scopes |
| `apps/trigger-links`, `pmd/pages/links`, `pmd/pages/countdown_timer` | WEB12; SAL03 | Tracking/short links/timers; downstream use metered separately |
| `pmd/pages/CustomObjects`, `pmd/pages/business` | CRM06; CRM08–CRM09 | Companies/custom entities and links; UI limitations apply |
| `pmd/pages/ad_manager` | ADS01–ADS12 | Campaign tools, separate media and creative work |
| `pmd/pages/affiliates` | AFF01–AFF06; Section 14.6 | Distinguish client programme from agency-vendor affiliate administration |
| `pmd/pages/agency`, `pmd/pages/agencyDashboard` | SAS01–SAS14; OPS06; AUD40 | Company/team/client administration, reporting and billing |
| `pmd/pages/ai-app-builder`, `pmd/pages/client-portal` | APP06–APP08; EDU11–EDU13 | Client portal/app builder; current web/Android scope |
| `pmd/pages/analytics`, `pmd/pages/reporting` | OPS01–OPS06 | Defined metrics, sources and dashboard/report work |
| `pmd/pages/announcements`, `pmd/pages/nudges` | Section 14.6; AUD34 | Vendor/shell notices and onboarding, not unsolicited client-message spend |
| `pmd/pages/audit` | AUD28 | Authorised account audit/review; internal tools are separate |
| `pmd/pages/blogs` | WEB14; SOC12 | Supplied versus produced content and publishing |
| `pmd/pages/brand_boards` | WEB15; AI17 | Brand palette/voice references and assets |
| `pmd/pages/bulk-actions` | CRM02–CRM04; CRM15 | Bulk mutation/import/export; downstream effects checked |
| `pmd/pages/calendars`, `pmd/pages/field-services` | CAL01–CAL18 | Meeting/service/rental/field modules and access gates |
| `pmd/pages/certificates` | EDU03; AUD35 | Course certificate/badge not agency certification membership |
| `pmd/pages/chat_widget` | WEB10–WEB11; AI03 | Widget surface versus actual channels and running AI |
| `pmd/pages/communities`, `pmd/pages/gokollab`, `pmd/pages/meeting`, `pmd/pages/membership` | EDU01–EDU16; AUD10–AUD16; AUD35 | Includes room/live/analytics/GoKollab/course/community differences |
| `pmd/pages/contact`, `pmd/pages/contact-views`, `pmd/pages/customers`, `pmd/pages/record-drawer`, `pmd/pages/smartlist`, `pmd/pages/view-builder` | CRM01–CRM10; OPS01 | People/record views and configurable lists; not arbitrary custom software entitlement |
| `pmd/pages/content_ai`, `pmd/pages/creator-studio` | SOC04–SOC10; AI17; AUD24 | Actor/plan generation and editorial work |
| `pmd/pages/conversation_ai_settings` | AI03–AI07; WAP12 | Conversation agents, channels and bounded actions |
| `pmd/pages/default_emails`, `pmd/pages/emailBuilder`, `pmd/pages/emailMarketing` | EML02–EML05 | Email/defaults versus commerce document layouts distinguished in app matrix |
| `pmd/pages/desktopWhitelabelApp`, `pmd/pages/mobileAppCustomiser` | AUD22; SAS09; EDU13 | Desktop/CRM-mobile/member-mobile have separate scope and tariffs |
| `pmd/pages/developer_marketplace`, `pmd/pages/integrations` | INT04–INT09; SAS08; AUD38 | Licence, scopes, API/provider support and actual tasks |
| `pmd/pages/domain_connect` | WEB17–WEB18; AUD30 | Domain ownership/connection/resale/redirect |
| `pmd/pages/eject` | Section 14.6; SAS12 | Account ejection/transfer state; authorised administration only |
| `pmd/pages/events` | AUD13–AUD14 | Native ticketed/RSVP event lifecycle |
| `pmd/pages/funnels`, `pmd/pages/vibe` | WEB04–WEB22; APP01–APP05 | Traditional website/funnel builder and AI Studio routes distinguished |
| `pmd/pages/industry_agents` | AUD21 | Conditional industry-specific agent deployment |
| `pmd/pages/isv` | EML01; EML08–EML11; MSG08–MSG10; AUD31 | Communication sending/phone/mail administration, not universal flat licence |
| `pmd/pages/launchpad`, `pmd/pages/onboarding` | CRM01; SAS04; OPS12 | Setup wizard/education and actual configuration labour |
| `pmd/pages/location_setting`, `pmd/pages/settings` | CRM01–CRM13; SAS11; AUD28–AUD31; AUD40 | Container surfaces; quote actual configured functions, not a mystery settings app fee |
| `pmd/pages/loyalty` | RET11–RET13 | Native beta points/wallet/scanner and merchant liabilities |
| `pmd/pages/marketing` | EML01–EML13; SOC01–SOC12; AFF01–AFF06 | Container includes multiple already-classified tools |
| `pmd/pages/medias` | WEB15; SOC05–SOC06; AUD23; AUD39 | Media store/editing/usage and clip processing |
| `pmd/pages/metaMarketingMessage` | AUD33 | Eligible Meta campaign path, distinct from WhatsApp billing |
| `pmd/pages/notifications` | AUD34 | Native notifications versus paid delivery channels |
| `pmd/pages/opportunity` | SAL01–SAL14 | Sales deals/pipelines and access |
| `pmd/pages/payments` | PAY01–PAY15; COM01–COM15; AUD25; AUD37–AUD38 | Includes commerce document layouts, inventory and provider integration |
| `pmd/pages/prospecting` | REP15–REP16 | Actual S plans and report/link-account quotas |
| `pmd/pages/reputation`, `pmd/pages/seo`, `pmd/pages/visibility-ai` | REP01–REP17; AUD09 | Separate review, Search Atlas and native Visibility AI products |
| `pmd/pages/restaurants` | AUD03–AUD08 | Restricted restaurant product and fulfilment/integrations |
| `pmd/pages/snippets` | MSG06; WAP03; SAL07 | Reusable text/response assets, not a new paid channel |
| `pmd/pages/socialPlanner`, `pmd/pages/socialPlannerAgency` | SOC01–SOC12; AUD23; AUD32 | Agency/location views, listening, clips and platform support |
| `pmd/pages/tasks` | OPS07–OPS11 | Basic CRM tasks and gated full projects |
| `pmd/pages/template_library` | SAS07; WEB15 | Content/snapshot reuse licence and install scope |
| `pmd/pages/triggers`, `pmd/pages/workflow` | INT01–INT03; INT10; SAL07 | Legacy/current automation, Flowguard path, charged executions |
| `pmd/pages/wordpress` | WEB21–WEB22 | Managed hosting/care and plugin licences |

### 14.6 Internal, programme, preview and support surfaces

Capturing every app does not mean pretending every app is an independently resellable product. The following source surfaces have an explicit commercial classification.

| Surface | What can legitimately be priced | What is not established by source presence |
|---|---|---|
| Switchyard/navigation shell | AUD29/menu configuration, onboarding and actual custom integrations | A distinct client Switchyard subscription or unlimited backend capability |
| Auth/verification/restricted/suspended/eject pages | Authorised user/access configuration, remediation diagnostics and offboarding | A resale licence for authentication internals, account bypass or recovery guarantee |
| Vendor support portal/internalTools/fpDebugger | Agreed authorised troubleshooting or vendor escalation labour | Client access to employee-only tools or a second native client ticketing licence |
| Feature Discovery/Labs/onboarding/nudges | Account configuration/education and entitlement verification | Guaranteed beta admission, permanent free feature access or priority vendor support |
| Agency affiliate/partner/AI-contest/promotional pages | Actual onboarding/content/administration work if commissioned | Extra running-agent capacity, guaranteed commission earnings or client affiliate-program parity |
| University/implementation-expert pages | Training delivery or an independently contracted specialist | Included outside specialist labour or a resale right to every vendor course/certification |
| Swag/Ideas/i18n-feedback/announcements | Actual requested procurement, translation or feedback administration | A new business automation product merely because a page exists |
| Previews/widgets/legacy transports/new versions | Testing/design and the underlying configured feature | Multiplying one site's, invoice's or campaign's licence by every UI component/URL |
| Generic routing/layout/empty/error components | Included implementation/testing work | Independently valuable software subscription without another delivered capability |

Client-facing work on an account must be authorised and possible with that account's own roles/scopes. A surface marked internal is captured by classification, not offered as an unauthorised client service.

### 14.7 Changes this audit makes to earlier statements

| Previously incomplete distinction | Source-backed correction | Pricing effect |
|---|---|---|
| Restaurants only represented by CRM/menu-page work | Dedicated restricted restaurant remote and overview/order/menu/floor/reservation/website/fulfilment routes captured | AUD03–AUD08; Q for native tariff, I/X for unverified external POS/delivery |
| Native Visibility AI only mentioned as unresolved internal naming | Actual named remote and host route confirmed | AUD09 is conditional native scope; REP17 remains external/available-tool reporting |
| Live webinar/event work largely external | Native Meeting Room and Community Live Room documented, separate from external webinar providers | AUD10–AUD12; conference-specific fees/limits require confirmation |
| Registration funnel versus full events management | Dedicated ticketed/RSVP event module with sessions, attendees, tickets and check-in documented | AUD13–AUD14; merchant/ticket/venue/device/staffing costs distinguished |
| Client support represented mainly as pipeline/custom-object cases | Dedicated native Ticketing remote with hidden per-location gate and permission checks | AUD01–AUD02 differ from MSG18 and HighLevel's vendor helpdesk |
| AI Evaluations might be treated uniformly as either shipped or absent | Placeholder landing, separate source-wired Ask AI EvaluationPage child | AUD41 conditional; agency-run evaluation priced separately under AI19 |
| Generic layout app naming could be confused with email | DocumentX route proves commerce layouts | AUD25 for commerce; email default/template rows remain EML scopes |
| Mobile and desktop branding could share a presumed licence | Desktop customizer has a separate source app/route | AUD22; do not reuse $49 member-app or $497 CRM-mobile tariff |
| AI health, memory, actions, industry agents and insight components hidden in broad AI lines | Each named remote gets an explicit capability/cost-boundary mapping | AUD17–AUD21; no claim all tools are included in AI Employee |
| Shared files/restoration/permissions treated as generic admin | Native document/restore/preferences/audit/billing surfaces identified | AUD26–AUD31 and AUD39–AUD40, with restoration/data/security boundaries |

### 14.8 Completion criteria and remaining uncertainty

**No inventoried app handle, route module or app/page directory remains unclassified in this checked-out source inventory.** Each maps to existing services, the 41 new supplementary scopes or a stated technical/internal purpose. The audit companion records mappings and exact source references so this claim is checkable rather than based on keyword mentions.

What remains unverified is **not omitted coverage**: live client entitlements, access to restricted releases, remotely loaded implementations, model/provider tariffs, per-product storage/conference/event charges and the real account bill. The shell references separate remote apps whose full source is not in this checkout; no claim is made to have audited every internal screen/action of those external applications. The source-controlled registries are also not proof that a runtime manifest cannot add or change apps later.

For additional source revisions, compare app declarations, literal loader calls, route modules and local directories against this inventory; an unclassified new entry needs a priced scope or explicit technical/conditional classification. Keep Q where the commercial tariff is unknown. Add-on costs must be verified in checkout/contract before any all-inclusive price is represented as final.

Additional official sources inspected for this expansion:

| Source | Supported claim |
|---|---|
| [S65 — Meeting Room overview][S65] | Native room/video/calendar/recording/transcript capability; recording alone does not generate a transcript |
| [S66 — Native Events][S66] | RSVP/ticketed event creation, schedules, tickets, attendees and check-in |
| [S67 — Community Live Rooms][S67] | Native Community event location, host/attendee and join flow |


[S01]: https://www.gohighlevel.com/pricing
[S02]: https://help.gohighlevel.com/support/solutions/articles/155000001156-highlevel-pricing-guide
[S03]: https://help.gohighlevel.com/support/solutions/articles/155000002095-rebilling-reselling-and-wallets-explained
[S04]: https://help.gohighlevel.com/support/solutions/articles/48001196389
[S05]: https://help.gohighlevel.com/support/solutions/articles/155000005458
[S06]: https://help.gohighlevel.com/support/solutions/articles/48001199647
[S07]: https://help.gohighlevel.com/support/solutions/articles/155000004261
[S08]: https://help.gohighlevel.com/support/solutions/articles/155000004723
[S09]: https://help.gohighlevel.com/support/solutions/articles/48001220605
[S10]: https://help.gohighlevel.com/support/solutions/articles/155000002132
[S11]: https://help.gohighlevel.com/support/solutions/articles/155000001428
[S12]: https://help.gohighlevel.com/helpdesk/attachments/155081573332
[S13]: https://help.gohighlevel.com/support/solutions/articles/155000008083-india-phone-numbers-voice-calling
[S14]: https://help.gohighlevel.com/support/solutions/articles/48001223556
[S15]: https://ideas.gohighlevel.com/changelog/messaging-and-phone-numbers-pricing-updates-effective-october-13-2026
[S16]: https://help.gohighlevel.com/support/solutions/articles/155000007147-understanding-the-5-markup-on-phone-system-pass-through-charges
[S17]: https://help.gohighlevel.com/support/solutions/articles/155000009487-voice-intelligence
[S18]: https://help.gohighlevel.com/support/solutions/articles/155000003971-workflows-pro-plan-pricing
[S19]: https://help.gohighlevel.com/support/solutions/articles/155000005678
[S20]: https://help.gohighlevel.com/support/solutions/articles/155000006652-ai-product-pricing
[S21]: https://help.gohighlevel.com/support/solutions/articles/155000009207
[S22]: https://help.gohighlevel.com/support/solutions/articles/155000006075
[S23]: https://help.gohighlevel.com/support/solutions/articles/155000002559
[S24]: https://help.gohighlevel.com/support/solutions/articles/155000006276-how-to-use-custom-payment-providers-for-saas-mode
[S25]: https://help.gohighlevel.com/support/solutions/articles/155000000875-collecting-payments-in-calendars
[S26]: https://razorpay.com/pricing/
[S27]: https://help.gohighlevel.com/support/solutions/articles/155000005055-getting-started-create-and-manage-contacts
[S28]: https://help.gohighlevel.com/support/solutions/articles/155000004430-getting-started-with-companies
[S29]: https://help.gohighlevel.com/support/solutions/articles/155000003896-getting-started-with-custom-objects
[S30]: https://help.gohighlevel.com/support/solutions/articles/155000004033-associations-between-opportunities-companies-custom-objects
[S31]: https://help.gohighlevel.com/support/solutions/articles/155000008769-automatic-company-creation-and-enrichment
[S32]: https://marketplace.gohighlevel.com/docs/
[S33]: https://help.gohighlevel.com/support/solutions/articles/155000009359-create-and-manage-qr-codes-for-calendars-services-rentals
[S34]: https://help.gohighlevel.com/support/solutions/articles/155000006649-rentals-calendars-overview-how-to-get-started
[S35]: https://help.gohighlevel.com/support/solutions/articles/155000006240-how-to-enable-services-for-your-sub-account
[S36]: https://help.gohighlevel.com/support/solutions/articles/155000009368-field-services-overview-how-to-get-started
[S37]: https://help.gohighlevel.com/support/solutions/articles/155000003720
[S38]: https://help.gohighlevel.com/support/solutions/articles/155000003298-instagram-dm-workflow-action
[S39]: https://help.gohighlevel.com/support/solutions/folders/48000684282
[S40]: https://help.gohighlevel.com/support/solutions/48000449583
[S41]: https://help.gohighlevel.com/support/solutions/articles/155000009221-how-to-create-loyalty-referral-programs-in-highlevel
[S42]: https://help.gohighlevel.com/support/solutions/folders/155000000203
[S43]: https://help.gohighlevel.com/support/solutions/articles/155000006980-getting-started-with-gift-cards
[S44]: https://help.gohighlevel.com/support/solutions/folders/48000671055
[S45]: https://help.gohighlevel.com/support/solutions/articles/155000000280-how-to-setup-customize-and-manage-your-communities
[S46]: https://help.gohighlevel.com/support/solutions/articles/155000000193-how-to-set-up-the-client-portal-
[S47]: https://help.gohighlevel.com/support/solutions/folders/155000001371
[S48]: https://help.gohighlevel.com/support/solutions/articles/155000006058-overview-of-flow-agents-in-agent-studio
[S49]: https://help.gohighlevel.com/support/solutions/articles/155000008304-mcp-connectors-for-managed-agents
[S50]: https://help.gohighlevel.com/support/solutions/articles/155000007587-ai-studio-in-highlevel
[S51]: https://help.gohighlevel.com/support/solutions/articles/155000009531-getting-started-with-client-app-builder-build-custom-web-and-mobile-apps-with-ai
[S52]: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
[S53]: https://marketplace.gohighlevel.com/docs/Authorization/OAuth2.0/index.html
[S54]: https://marketplace.gohighlevel.com/docs/other/rate-limits/index.html
[S55]: https://help.gohighlevel.com/support/solutions/articles/155000001531-how-to-create-a-custom-dashboard
[S56]: https://help.gohighlevel.com/support/solutions/articles/155000008442-introduction-to-project-management
[S57]: https://autogencrm.com/pricing/
[S58]: https://aibrevo.com/solutions/gohighlevel-setup-agency/
[S59]: https://highleveladmins.com/gohighlevel-setup
[S60]: https://help.gohighlevel.com/support/solutions/articles/155000008422-fixed-rate-rebilling-for-ai-products
[S61]: https://help.gohighlevel.com/support/solutions/articles/155000006631
[S62]: https://support.stripe.com/questions/stripe-accounts-are-invite-only-in-india
[S63]: https://www.airtel.in/business/commercial-communication/help
[S64]: https://help.gohighlevel.com/support/solutions/articles/48000983084

[S65]: https://help.gohighlevel.com/support/solutions/articles/155000009149-meeting-room-in-highlevel-overview
[S66]: https://help.gohighlevel.com/support/solutions/articles/155000008071-how-to-create-and-manage-events-in-highlevel-private-beta-
[S67]: https://help.gohighlevel.com/support/solutions/articles/155000007834-live-rooms-in-communities-events
