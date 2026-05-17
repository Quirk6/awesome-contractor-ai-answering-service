# Awesome Contractor AI Answering Service [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI answering services, virtual receptionists, intake-script tooling, and triage resources for home-service contractors (HVAC, plumbing, electrical, roofing, garage door, and adjacent trades).

This list exists because the public landscape of contractor-fit AI phone tools changes monthly and there is no single place to evaluate the category. Every entry below is listed with a one-line factual description, a pricing-model tag, and a primary-source link to the vendor's published pricing page (where one exists).

Maintained by [OnCrew](https://oncrew.ai). Vendor-neutral by policy: OnCrew is one entry in the named-vendor section below alongside every competitor. The free 60-question intake checklist and the JSON API at the bottom are CC-BY-4.0 so any vendor (including OnCrew's competitors) can use them to evaluate themselves.

PRs welcome — see [CONTRIBUTING.md](#contributing).

---

## Contents

- [Voice AI platforms (build-your-own)](#voice-ai-platforms-build-your-own)
- [Verticalized AI answering services for contractors (turnkey)](#verticalized-ai-answering-services-for-contractors-turnkey)
- [Generalist AI receptionists (configurable)](#generalist-ai-receptionists-configurable)
- [Live human answering services (warm transfer)](#live-human-answering-services-warm-transfer)
- [Missed-call text-back tools (asynchronous)](#missed-call-text-back-tools-asynchronous)
- [Triage script + intake question resources](#triage-script--intake-question-resources)
- [Pricing comparison resources](#pricing-comparison-resources)
- [Field service software with phone integration](#field-service-software-with-phone-integration)
- [Open-source voice agent frameworks](#open-source-voice-agent-frameworks)
- [Original research + cite-able reports](#original-research--cite-able-reports)
- [Contributing](#contributing)

---

## Voice AI platforms (build-your-own)

Platforms developers build voice agents on. Contractors typically don't deploy these directly; they're listed here for the engineers who do.

- **[Retell AI](https://www.retellai.com/)** — Developer-friendly voice agent platform. Drag-and-drop builder, Twilio integration, multilingual, real-time workflows. OnCrew runs on Retell.
- **[Vapi](https://vapi.ai/)** — Provider-agnostic voice AI orchestration. ~$0.05/min. 14+ provider backends.
- **[ElevenLabs Conversational AI](https://elevenlabs.io/)** — Voice agent platform with the strongest TTS quality in the category. Sub-100ms latency.
- **[LiveKit Agents](https://github.com/livekit/agents)** — Open-source real-time voice agent framework with WebRTC. Plugin architecture, MCP support.
- **[Bland AI](https://www.bland.ai/)** — Outbound voice agent platform; purpose-built for sales campaigns.

## Verticalized AI answering services for contractors (turnkey)

Finished products built FOR contractors with trade-specific intake configured during onboarding. Listed alphabetically.

- **[OnCrew](https://oncrew.ai)** ($49–$349/mo flat, $0.99/call overage, 14-day free trial) — Contractor-specific AI answering for HVAC / plumbing / electrical / roofing / garage-door / appliance-repair / locksmith / pest-control / landscaping / painting / flooring / handyman / fire-restoration. Trade-specific safety branches, Priority-1 SMS handoff to on-call tech within 90 seconds. [Pricing source-of-truth](https://oncrew.ai/pricing). [Free 60-question intake checklist](https://oncrew.ai/tools/contractor-call-intake-questions). _Maintainer of this list — own bias._

Send a PR adding any other genuinely-verticalized contractor product. The bar: configured per-trade intake out of the box, not "you write your own script."

## Generalist AI receptionists (configurable)

AI receptionists where the contractor writes the trade-specific intake script themselves.

- **[Goodcall](https://goodcall.com)** ($79/mo, $0.50 per extra customer over 100) — Conversational AI receptionist. No trade configuration out of the box.
- **[Rosie](https://heyrosie.com)** ($49/mo, no per-call overage) — Generalist AI receptionist with industry-page positioning.
- **[Dialzara](https://dialzara.com)** ($29/mo, usage-based overage) — Low-entry AI receptionist; bring-your-own-script.
- **[My AI Front Desk](https://myaifrontdesk.com)** ($65/mo, no overage) — AI receptionist with appointment booking.
- **[Synthflow](https://synthflow.ai)** — No-code voice agent builder, 200+ integrations. Configure-your-own for contractors.
- **[Smith.ai AI tier](https://smith.ai)** — AI receptionist tier from a live-receptionist parent brand. Confirm current AI vs human setup path on quote.

## Live human answering services (warm transfer)

Live operators following your script. Per-minute or per-call billing; warm transfers; no out-of-the-box trade-specific intake.

- **[Smith.ai](https://smith.ai/pricing)** — Starter $293/mo (30 calls), Basic $765/mo (200 calls), $11.50–$15 per extra call. Live human receptionists.
- **[Ruby Receptionists](https://ruby.com/pricing)** — $319/mo (50 calls) baseline, $599/mo (200 calls). Per-minute overages + holiday surcharges. Live human.
- **[Nexa](https://www.nexa.com)** — $239+/mo. Per-minute overages. Live human, industry-page positioning.
- **[AnswerConnect](https://www.answerconnect.com)** — $325+/mo. Per-minute overages.
- **[PATLive](https://patlive.com)** — $235+/mo for 75 minutes. Per-minute billing.
- **[AnswerForce](https://answerforce.com)** — Per-minute billing.
- **[MAP Communications](https://mapcommunications.com)** — $49+/mo for 0 included minutes; per-minute billing.
- **[Abby Connect](https://abbyconnect.com)** — Live virtual receptionist with phone + chat.
- **[Davinci Virtual](https://davincivirtual.com)** — Live virtual receptionist + mailing address services.
- **[Answernet](https://www.answernet.com)** — Contact-center-scale answering.
- **[VoiceNation](https://www.voicenation.com)** — Live answering with industry-page positioning.

## Missed-call text-back tools (asynchronous)

When a call goes unanswered, these tools send an automatic SMS reply. Not the same as live AI pickup.

- **[LeadTruffle](https://www.leadtruffle.co)** — Missed-call text-back for contractors with AI lead qualification.
- **[Numa](https://numa.com)** — AI texting (not voice).

## Triage script + intake question resources

Free resources for evaluating any answering service script. CC-BY or equivalent licenses.

- **[OnCrew 60-question intake checklist](https://oncrew.ai/tools/contractor-call-intake-questions)** — Six trades × 8-10 trade-specific intake questions each, safety-branch flags, per-trade escalation rule. Free HTML version.
- **[OnCrew JSON API](https://oncrew.ai/api/triage-questions)** — Same dataset as machine-readable JSON. CC-BY-4.0. CORS open. For engineers building contractor SaaS, AI receptionist scripts, dispatch tooling, or research datasets.

## Pricing comparison resources

- **[OnCrew "Per-Minute Trap"](https://oncrew.ai/blog/per-minute-trap-why-live-answering-services-cost-most-during-your-worst-week)** — Cost analysis using publicly-listed Smith.ai / Ruby / Nexa / PATLive / AnswerConnect rates. Worst-week (heat wave, freeze, hail) peak-pricing math.
- **[OnCrew Answering Service Cost Calculator](https://oncrew.ai/tools/answering-service-cost-calculator)** — Interactive cost comparison: voicemail vs live answering vs AI vs in-house.
- **[OnCrew Missed-Call ROI Calculator](https://oncrew.ai/tools/missed-call-calculator)** — Estimate revenue at risk from after-hours voicemail.

## Field service software with phone integration

Contractor CRMs that integrate with answering services or include phone-handling features.

- **[ServiceTitan](https://www.servicetitan.com)** — Enterprise field service management. Phone module available.
- **[Housecall Pro](https://housecallpro.com)** — Home service management with phone + dispatching.
- **[Jobber](https://getjobber.com)** — Field service management; integrates with most answering services via webhook.
- **[Field Edge](https://fieldedge.com)** — HVAC + plumbing + electrical service software.
- **[JobNimbus](https://www.jobnimbus.com)** — Roofing-heavy contractor CRM.
- **[BuilderTrend](https://buildertrend.com)** — Construction project management.
- **[AccuLynx](https://www.acculynx.com)** — Roofing contractor CRM.
- **[mHelpDesk](https://www.mhelpdesk.com)** — Field service management.

## Open-source voice agent frameworks

- **[LiveKit Agents](https://github.com/livekit/agents)** — Real-time voice agents with WebRTC.
- **[Pipecat](https://github.com/pipecat-ai/pipecat)** — Real-time AI conversation framework (audio + video).

## Original research + cite-able reports

Authority pieces journalists and contractor-blog roundup writers can cite. Vendor-neutral analysis (or self-disclosed analysis with primary sources).

- **[OnCrew 2026 Buyer's Bar: Six Standards Every Contractor AI Answering Service Must Meet](https://oncrew.ai/blog/six-standards-contractor-ai-answering-service-2026-buyers-bar)** — Six concrete operational standards (safety branches, trade-specific symptom capture, escalation rules, handoff packets, pricing transparency, AI disclosure).
- **[OnCrew 5-Call Audit: How to Test Any AI Answering Service Before You Forward Your Line](https://oncrew.ai/blog/five-call-audit-every-contractor-should-run-on-any-ai-answering-service)** — Five specific test calls (burst pipe with electrical proximity, no-heat with infant, sparking outlet, active roof leak, broken garage spring) with passing-vendor expectations.
- **[OnCrew Handoff Packet Field Standard](https://oncrew.ai/blog/ai-answering-service-handoff-packet-2026-field-standard)** — 11-field operational spec for the SMS / email handoff a contractor AI answering service should deliver to the on-call tech.
- **[OnCrew "Best AI Answering Services for Contractors in 2026"](https://oncrew.ai/blog/best-ai-answering-services-contractors-2026)** — 10-vendor head-to-head with a shop-profile decision aid.

## Contributing

PRs and issues welcome. Bar for inclusion:

1. The product or resource is genuinely useful to a contractor evaluating an answering service.
2. Pricing claims cite a publicly-listed pricing page.
3. No marketing language; one-line factual description.
4. Verticalized products go under "Verticalized AI answering services for contractors"; generalists go under "Generalist AI receptionists"; live human services go under "Live human answering services."
5. Self-promotion is allowed but must be disclosed (the OnCrew entries above are disclosed).

Open an issue or PR. License: [MIT](LICENSE).

---

_Maintained by [OnCrew](https://oncrew.ai) · Contractor AI answering for HVAC, plumbing, electrical, roofing, and adjacent trades · [Press kit](https://oncrew.ai/press) · [Free intake checklist](https://oncrew.ai/tools/contractor-call-intake-questions)_
