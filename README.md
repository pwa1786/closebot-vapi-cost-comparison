# CloseBot vs Vapi: what each one really costs, how voice stacks up against SMS appointment setting, and which one fits your setup

Two tools keep showing up in the same conversations about AI appointment setting, and they are not the same kind of product. CloseBot is a conversational AI agent that lives inside your CRM and handles text. Vapi is a developer platform for building voice agents over the phone. Comparing them head-to-head on features misses the point; the useful question is which one solves the problem you actually have, and what the bill looks like once you stack everything up.

Here is the short version before the details: if your leads arrive as SMS, website chat or email and you live in GoHighLevel or HubSpot, CloseBot is the cheaper and more direct path to booked appointments. If your leads call you — or you need to call them — Vapi is built for that job, and it charges like infrastructure rather than like a product.

## What each tool actually is

CloseBot builds AI agents that qualify leads, handle objections, follow up, and put appointments on a calendar. It sits on top of your CRM and takes over the text-based channels inside it. Setup is a drag-and-drop job flow builder plus knowledge and tools, with objectives rather than rigid keyword trees: you tell the agent what to accomplish and it reasons through the conversation.

Vapi is the opposite shape. It orchestrates the voice pipeline — speech-to-text, language model, voice synthesis and telephony — and lets you swap each component independently through an API. Vapi's own pricing page describes it as hosting plus model pass-through. You assemble the rest.

That difference drives everything else, including price.

|  | CloseBot | Vapi |
| --- | --- | --- |
| Core job | Lead qualification and appointment booking over text | Building and deploying voice AI agents (phone calls) |
| Buyer | Agencies and businesses using GoHighLevel, HubSpot or a custom CRM | Developers and engineering-led teams |
| Build model | No-code drag-and-drop, objective-based agents | API and dashboard, provider-by-provider assembly |
| Billing unit | Monthly platform fee + messages (included on business plans) | Per minute of call time + pass-through model costs |
| Native voice | No — text channels only | Yes — that is the product |
| White-label and rebilling | Yes, built for agencies | Not a resale product |

CloseBot's own homepage frames it as taking over "all text-based channels within your CRM." Independent write-ups say the same thing from the other direction: an Insighto overview notes CloseBot "lacks voice agent functionality and focuses primarily on chat-based automation," and a Fin comparison labels it text-only with no voice or video. If you need a phone agent, CloseBot is not it.

## Where the comparison actually overlaps

The overlap is narrower than the search results suggest. Both tools can book appointments, and both can run SMS. Vapi launched native SMS for its agents and a Chat API that lets the same agent configuration work across voice and chat, with messages priced at $0.005 each on the self-serve plan.

So if you want one brain handling both phone calls and texts, Vapi technically does that. What you give up is the layer that makes text appointment setting work without maintenance: CRM-native conversation handling, templates, a testing portal, and the agency plumbing for reselling. That is CloseBot's entire focus.

A practical detail people run into when they try both: the two systems do not share conversation memory. One agency owner described the failure mode plainly — a lead chats on Monday and calls on Tuesday, and the voice agent has no idea the chat happened. Nothing in either product fixes that for you. If your leads move between phone and text, the integration is your problem to solve.

## CloseBot pricing: the full current lineup

CloseBot runs two tracks on the same page — business plans with message costs baked into the base price, and agency plans with client rebilling. Here is what the pricing page shows.

| Plan | Price | Billing | What you get | Get it |
| --- | --- | --- | --- | --- |
| Free | $0 | Free forever | 100 messages/mo, 1 agent, 1 user seat, 1 MB storage, unlimited account connections | Start CloseBot free |
| Core — business | from $64/mo | Monthly | Message costs included in the base price, 15+ templates, human support, add-on users, storage and agents | Get the CloseBot business plan |
| Core — business | from $53/mo | Annual, billed as $640/yr | Same as above, plus the larger 50+ template library on annual plans | Get the CloseBot business plan |
| Core — agency | $397/mo | Monthly | Unlimited agents across unlimited sources, white-label client portal, rebill all costs, $0.012 per message rebillable | Get the CloseBot agency plan |
| Core — agency | $331/mo equivalent | Annual | Same as above; the annual discount is reported by third-party reviews rather than shown in the monthly view | Get the CloseBot agency plan |
| Growth | Custom | Contact sales | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates | Talk to CloseBot about Growth |

The business track is volume-priced. The base tier covers 100 to 500 messages a month at $64; from there the price steps up with the monthly ceiling you choose — third-party reviews verified in August 2026 list $84 at 1,000 messages, $109 at 2,000, $176 at 5,000, $454 at 20,000 and $806 at 50,000.

The official help centre still documents the older job-flow tiers, which are worth knowing if a quote mentions them:

| Business tier | Monthly price | Job flows |
| --- | --- | --- |
| Base | $64/mo | 1 |
| Growth | $197/mo | 3 |
| Scale | $297/mo | 10 |
| Unlimited | $397/mo | Unlimited |

Two pricing mechanics that matter more than they look:

- A message equals one segment, unless you enable the Agent Node's unlimited potential, in which case you are billed token costs and a single message can consume several segments.
- Business plans carry a 500-message ceiling by default. Go over it and overage is charged at 2x from a wallet balance. Agency accounts are billed a flat $0.012 per message with whatever markup you set.
- Additional seats cost $5 each on both tracks, and agencies can mark those up too.

There is no refund window. CloseBot offers a free-forever plan under 100 messages and a 7-day trial of any paid plan, then bills are final. Plans run month to month with no contract, and you cannot bring your own API key — CloseBot treats that as a security trade-off, which means your model spend is inside the plan rather than on a separate invoice.

## Vapi pricing: the headline versus the stack

Vapi publishes a $0.05 per minute hosting fee and passes model costs through at cost. Here is the current structure.

| Plan | Price | Billing | Key limits |
| --- | --- | --- | --- |
| No Success Package | $0 to start, then $0.05/min | Pre-paid, usage-based | 2 organisations, 1 phone number, 4 concurrent calls, 14 days raw data retention, Discord and email support |
| Core | $29/mo | Monthly, auto-renew | 2 organisations, 5 numbers, 10 concurrent calls, 30 days retention, ZDR included, 2 business day response SLA |
| Pro | 10% of Vapi hosting fee, $999/mo minimum | Monthly minimum | 10 organisations, 10 numbers, 30 concurrent calls, 180 days retention, RBAC + ZDR, Slack support, 99% uptime SLA |
| Premier | Custom | Contact sales | Custom concurrency and retention, named support team, 99.9% uptime SLA, SSO |

Add-ons stack on top: HIPAA-eligible data handling runs $2,000 per month, extra concurrent call lines are $10 per line per month, and extra organisations are $20 each per month.

Vapi's own calculator shows what a small deployment looks like at 1,000 minutes a month: $50 hosting, roughly $10 for Deepgram transcription, $8 to $45 for the intelligence model, and $15 to $24 for ElevenLabs voice — landing at $82 to $129 monthly.

Independent breakdowns argue that range is optimistic at scale. CloudTalk's September 2026 analysis puts a realistic assembled stack at roughly $0.12 to $0.24 per minute before the language model is counted, and flags that Build keeps only 14 days of call history and carries no native SSO, RBAC or SOC 2. Those are competitor claims rather than Vapi's numbers, but the arithmetic behind them is just the published provider list prices added together, which is why they keep appearing.

## The cost comparison, translated into the same unit

CloseBot bills per message. Vapi bills per minute. To make them comparable you have to know your own volume.

If you send 2,000 messages a month, CloseBot's business track lands around $109/mo with message costs included. To approximate that conversation volume with a voice agent, you would be talking minutes, not messages — and at a mid-tier all-in rate near $0.24 per minute, 2,000 minutes runs into the high hundreds before you have paid anyone to build and maintain the agent.

Flip the volume and the picture reverses. A clinic taking 500 minutes of after-hours calls a month is looking at roughly $122 on a stacked Vapi setup. CloseBot does not answer that call at any price.

The unit economics are not better or worse. They measure different work.

## Integration, compliance and channel reality

**CRM fit.** CloseBot is native to HighLevel and HubSpot — the HubSpot integration has been live since December 2025 — and also lists Salesforce, Podio, LeadConnector and custom CRM connections. Vapi's site lists a GoHighLevel integration among its connectors, but it is an integration you wire up, not a product built around that CRM's conversation streams.

**Standalone use is genuinely disputed.** CloseBot's own comparison table lists "Standalone Compatible: works even without a CRM" as a feature. Reviewers dispute it in practice, pointing out that CloseBot's coverage is "chats across all channels in your CRM" — meaning if you have no CRM, you are buying two products. Treat that as untested until you check it against your own stack.

**Compliance.** CloseBot includes HIPAA on the Growth tier with quarterly audits and 99.99% priority uptime. Vapi offers HIPAA as a $2,000/mo add-on available on either self-serve or higher packages, and third-party reviews note SOC 2, SSO and RBAC arrive with the annual Scale contract rather than the self-serve plan.

**Languages.** CloseBot's FAQ states 40+ languages, reasoning that it inherits whatever Claude and ChatGPT support. One competitor comparison claims English-primary support and flags multi-language depth as configuration-dependent, so test your own language before committing.

## What real users complain about

Neither tool is frictionless, and the complaints are consistent enough to plan around.

CloseBot's recurring criticism is the learning curve. One GoHighLevel user on Reddit said they were "immediately turned off by the learning curve — it just didn't seem simple or intuitive." A separate reviewer scored setup effort 3 out of 5, estimating 5 to 10 hours of initial configuration to build knowledge bases and connect webhooks. Another Reddit commenter liked the workflow builder concept but found the testing and live experience unreliable. The counter-argument, made by users who stuck around, is that the Agent Node release made builds considerably easier.

Vapi's friction is engineering time. A developer post in the n8n community described spending four months, logging 760 calls and over 100 hours building on Vapi, concluding the AI was about 20% of the work and error handling was the rest. Reddit threads on Vapi cost frequently cite effective rates of $0.25 per minute. Vapi's G2 rating sits at 4.2/5, though from only three reviews — which is an anecdote, not a verdict.

CloseBot's G2 rating is 4.8/5 across 124 reviews. That is a much larger sample, and it comes from the buyer CloseBot was designed for: agencies reselling AI setters.

## Which one should you actually pick

Run through these in order.

**Do your leads need to hear a voice?** If yes, CloseBot is the wrong tool and no amount of message pricing fixes it. You are shopping for a voice platform.

**Do you already run GoHighLevel or HubSpot?** If yes, CloseBot slots into conversations you are already having, with templates and a testing portal covering the setup work. That is the case where it is close to unbeatable on price for the volume.

**Are you selling AI to clients?** The agency plan at $397/mo, or $331/mo annual per third-party reviews, is built around rebilling at $0.012 per message. Some agencies bill clients $500+/month for AI lead qualification, so a single client can cover the platform cost.

**Is your volume under 100 messages a month?** The free plan covers it, permanently, with no card required.

**Are you a solo operator with no CRM?** Check the standalone claim before you buy. If it does not hold up in your setup, you are pricing a CRM subscription on top of the agent.

**Do you want one agent across phone and text?** Vapi can do both, but you are buying an engineering project. Budget the build time, not just the per-minute rate.

If you want the fastest path to testing whether AI booking works for your pipeline at all, the free tier answers that question without a credit card: 👉 Try CloseBot on the free plan.

## The hybrid setup most agencies end up with

The comparison framing implies you pick one. In practice, a lot of agencies run both — CloseBot handling SMS, web chat and email follow-up inside the CRM, with a voice agent handling inbound calls and outbound campaigns. The person selling that combination usually charges for both.

The catch is the one mentioned earlier: no shared memory between the voice agent and the text agent unless someone builds it. If a lead calls, then texts, then calls again, each system starts from scratch unless you bridge the context yourself. Plan for that before you sell the bundle.

## FAQ

**Is CloseBot or Vapi better for GoHighLevel?**
CloseBot. It is built natively around HighLevel's conversation streams and includes agency tools — white-label portal, seat reselling, per-message rebilling. Vapi lists a HighLevel integration, but you are responsible for connecting and maintaining it.

**Can CloseBot make phone calls?**
No. CloseBot handles text-based channels inside your CRM. Several sources describe it as text-only with no voice capability. Voice requires a separate platform.

**How much does Vapi really cost per minute?**
Vapi's published hosting fee is $0.05 per minute with model costs passed through at cost. Vapi's own calculator puts a 1,000-minute month at $82 to $129 all-in. Third-party analyses argue $0.12 to $0.24 per minute is more realistic before language model costs, so price your actual stack rather than the headline.

**Does CloseBot have a free plan?**
Yes — $0 forever with 100 messages a month, one agent, one seat and 1 MB of storage. Over 100 messages you can pay as you go at $0.08 per message, which is a sign you should move to a paid tier instead.

**Is there a CloseBot free trial?**
Yes, 7 days on any paid plan before billing starts, plus the free-forever tier. CloseBot states plainly that there are no refunds, so the trial is where you do your testing.

**Can I use my own OpenAI or Anthropic API key with CloseBot?**
No. CloseBot does not allow bring-your-own-key, which it frames as a security decision. Your model costs are inside the plan. It does support multiple providers internally, and HIPAA accounts are routed to Anthropic.

**What happens if I go over my CloseBot message limit?**
On business plans, overage is charged at 2x the normal rate from a wallet balance. Raising your monthly ceiling before you hit it is cheaper, because higher ceilings unlock bulk pricing.

## Bottom line

These two products only look like competitors from a search results page. CloseBot is a text-based appointment setter with pricing designed so an agency can mark it up and resell it. Vapi is voice infrastructure with honest pass-through pricing and a build project attached.

Pick CloseBot if your leads talk to you in writing and you are already in a CRM. Pick Vapi if your leads talk to you out loud and you have someone who can own the stack. Pick both only if you are prepared to solve the memory gap between them yourself.

If you are still at the "does this even work for my pipeline" stage, the cheapest way to find out is the free tier: 👉 Create your free CloseBot account and build the first agent before spending anything.
