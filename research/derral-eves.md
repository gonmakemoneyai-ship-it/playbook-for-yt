# Derral Eves — Research Dossier for YouTube Growth Playbook

## Access Note (read before anything else)

In this research session, direct `WebFetch` access to essentially every external domain was blocked at the network-egress level, including YouTube itself (`youtube.com`), all four suggested transcript-extraction tools (`youtubetotranscript.com`, `tactiq.io`, `notegpt.io`, `downsub.com`), every podcast/article host tested (Smart Passive Income, Hustle & Flowchart, Substack, Wikipedia, Uscreen — even `example.com` as a control), and raw `curl` from Bash (blocked by the same organization policy at the proxy layer, confirmed via `/__agentproxy/status`). Only the `WebSearch` tool had live access, returning search-engine-crawled snippets and short synthesized summaries (with source links) rather than full page text.

**Practical consequence: no full transcript could be retrieved for any of the five sources below.** Every source is marked **TRANSCRIPT NOT FULLY AVAILABLE**. All extracted material comes from `WebSearch`-surfaced quotes, paraphrased excerpts, and coverage of show notes/articles — not from a verified line-by-line transcript. Quotes reproduced below are given only where the search tool returned them as apparent direct quotations from crawled source text; nothing has been invented. Where I could not find a specific figure (episode runtime, exact publish date) with confidence, I say so rather than guessing.

---

## Credibility Summary

Derral Eves is one of the longest-tenured YouTube strategists in the industry, active since the platform's early years:

- **Founder/CEO of Creatus**, a video marketing agency whose clients have included Amazon, Netflix, Nintendo, Red Bull, Epic Games, Bill Gates, ABC, NBC, and ESPN.
- **Founder of VidSummit**, the creator-economy conference — MrBeast (Jimmy Donaldson) is now a part-owner and attended VidSummit as a relatively unknown 6M-subscriber creator in 2017, a moment Eves has publicly described as an early inflection point in their relationship.
- **Author of "The YouTube Formula: How Anyone Can Unlock the Algorithm to Drive Views, Build an Audience, and Grow Revenue"** (Wiley, 2021), a Wall Street Journal bestseller, with a foreword written by MrBeast. MrBeast's quoted line from that foreword: "I have one of the three most viewed channels on YouTube and I still talk about YouTube data and strategy with Derral because no one is on the same wavelength as him."
- **Self-reported track record figures vary by source and date** (a sign these are updated over time rather than fixed): different articles cite having generated somewhere between 54 billion and 101 billion cumulative YouTube views for clients, and having taken somewhere between 24 and 34 channels from zero to 1M+ subscribers, including The Piano Guys and Squatty Potty. Treat the exact numbers as directionally true ("tens of billions of views, dozens of channels to seven figures") rather than precise — I could not verify a single authoritative up-to-date figure.
- Executive producer credits include Squatty Potty's viral "ice cream pooping unicorn" ad campaign and the hit series **The Chosen**.
- Search Engine Journal has reportedly called him the "godfather of YouTube optimization" (per secondary source; not independently verified against the original SEJ piece).

This is a creator/strategist whose claims are corroborated by third parties (MrBeast's own foreword, VidSummit's continued existence and MrBeast's ownership stake, named brand clients), not just self-promotion — which is why he was assigned to this playbook section.

---

## Source 1

**Creator:** Derral Eves (guest)
**Title:** SPI 355: "How to Build a Successful YouTube Channel in 2019 — with Derral Eves"
**Publication date:** January 23, 2019
**URL:** https://www.smartpassiveincome.com/podcasts/how-to-build-a-successful-youtube-channel-in-2019-with-derral-eves/
**Length:** Not confirmed (SPI episodes typically run 45–75 min; exact runtime not found)
**Format:** Podcast interview (Pat Flynn's Smart Passive Income)

**Main subjects covered:** Titles and thumbnails as the entry point to everything else on YouTube; the "impression-to-click-through-rate" analytics metric (new to YouTube Studio at the time); why CTR gates all downstream algorithmic distribution.

**Why selected:** This is the most quote-dense, specific source found on the single highest-leverage topic in the assignment brief — titles/thumbnails/CTR — stated in Eves's own words as reported by the search engine's crawl of the show notes/transcript excerpt.

**Transcript availability:** TRANSCRIPT NOT FULLY AVAILABLE. Used: WebSearch-surfaced quotations attributed to the episode's show notes/transcript (the underlying page could not be fetched directly).

### Extracted principles

1. **Title + thumbnail = "billboard to your video."** Quoted: *"the most fundamental, most important step because if they don't click on it, YouTube's never going to promote it."*
   — Tag: **EXPERT OPINION.** Affects: the click/discovery stage of the viewer journey (top of funnel, before watch time even begins). Universal, applies to long-form primarily (thumbnails are less load-bearing on Shorts, which autoplay). Why he believes it: the algorithm cannot promote what nobody clicks — so CTR is a gate every other quality signal sits behind. When to use: for every long-form upload; less relevant for Shorts feed distribution.

2. **Impression-to-click-through-rate as a diagnostic metric.** Eves reportedly walks through how creators should read this specific YouTube Studio metric (percentage of people who saw the thumbnail/title for ≥1 second and then clicked) to evaluate whether a thumbnail/title pairing is working, rather than judging by view count alone.
   — Tag: **FACT/PLATFORM INFORMATION** (this is a real, documented YouTube Analytics metric) combined with **EXPERT OPINION** on how to interpret it. Affects: analytics/iteration stage. Universal across niches; long-form specific (this metric is most actionable for videos where thumbnail/title are shown in feeds/search, less so for Shorts).

---

## Source 2

**Creator:** Derral Eves (guest)
**Title:** SPI 459: "The Right Formula to Win on YouTube with Derral Eves"
**Publication date:** February 3, 2021 (per search-engine metadata; not independently re-verified against the raw page)
**URL:** https://www.smartpassiveincome.com/podcasts/formula-to-win-on-youtube/
**Length:** Not confirmed
**Format:** Podcast interview (Smart Passive Income), timed around the launch of "The YouTube Formula" book

**Main subjects covered:** How YouTube's multiple discovery surfaces work (Browse/Home, Suggested, Trending, Notifications, Search) and what each is optimized for; "session watch time" as a ranking factor; the algorithm's core objective; general framework from the book (thumbnails, video quality, title, captions, engagement, subscribers, analytics).

**Why selected:** This is the richest available source on **how the YouTube algorithm/recommendation system actually functions** — directly addresses the "analytics," "channel strategy," and "why videos go viral/fail" parts of the assignment brief with structural, non-generic detail (naming the five distinct surfaces rather than talking about "the algorithm" as a monolith).

**Transcript availability:** TRANSCRIPT NOT FULLY AVAILABLE. Used: WebSearch-synthesized summary drawing on the episode's show notes and a related Derral Eves blog post ("Session Watch Time — Most Important Factor in Ranking your YouTube Videos," derraleves.com) that the search tool surfaced alongside it.

### Extracted principles

1. **YouTube distribution is not one algorithm — it's five distinct surfaces, each optimized for a different "hit rate."** Named: Browse (Home + Subscriptions feed), Suggested (up-next/sidebar), Trending, Notifications, Search — each tuned to maximize how often a viewer actually watches what it recommends them.
   — Tag: **FACT/PLATFORM INFORMATION** as reported by Eves (he is characterizing YouTube's actual system, not offering a personal theory), though the specific "hit rate" framing/emphasis is his own explanatory device, so also partly **EXPERT OPINION**. Affects: discovery/distribution stage, broadly. Universal across niches. Applies to long-form and Shorts differently (Shorts has its own dedicated feed/algorithm not covered in this source).

2. **"Session watch time" — YouTube rewards the video/channel that starts a viewing session, because it wants to keep people on the platform longer, not just on one video.** Reported figure: roughly 75% of all views on YouTube happen because YouTube found the viewer for the creator (i.e., algorithmic discovery, not the creator's own promotion/subscriber base).
   — Tag: **FACT/PLATFORM INFORMATION** (a real, YouTube-confirmed ranking signal Eves is explaining) — the 75% figure and exact weighting are Eves's interpretation/estimate, so treat the number itself as **EXPERT OPINION** unless independently corroborated. Affects: session-level retention and channel-level distribution, not just single-video CTR. Why it matters: explains why "keeping people watching more of YOUR content" (via end screens, playlists, session-starting hooks) compounds algorithmic favor beyond any single video's own retention curve. Long-form specific — session watch time is most legible in the context of longer sit-down viewing sessions.

3. **Core algorithm objective = keep users on YouTube longer, satisfied.** Framing: don't fight the algorithm, align with its actual goal.
   — Tag: **EXPERT OPINION** (a simplification/interpretation of Google's stated goals, not a verbatim platform statement). Affects: overall channel strategy. Universal, format-agnostic.

---

## Source 3

**Creator:** Derral Eves (guest), interviewed on Hustle & Flowchart (hosted by Joe Fier / Matt Wolfe)
**Title:** "Derral Eves — The Real Secret To Growth On YouTube"
**Publication date:** Search-engine metadata suggested January 28, 2025, but this could not be cross-confirmed against a second source — treat with caution; possible this is a re-syndication/re-index date rather than original air date.
**URL:** https://hustleandflowchart.com/derral-eves-the-real-secret-to-growth-on-youtube/
**Length:** Not confirmed
**Format:** Podcast interview

**Main subjects covered:** Psychographics-driven audience research; the Squatty Potty viral ad case study (title/thumbnail testing at scale); thumbnail design frameworks ("blink rule," contrast, faces, thumbnail templates); a stated iterative methodology ("Try → Fail → Analyze → Adjust"); why he treats YouTube as "a data-centered human formula" rather than an SEO problem; caution against ad-revenue dependency.

**Why selected:** This is the most **specific, example-rich, non-generic** source found — it includes an actual named case study with a concrete number (165 title variations tested) and a named winning title, which is exactly the kind of "evidence/example given" detail the assignment calls for, rather than platitudes.

**Transcript availability:** TRANSCRIPT NOT FULLY AVAILABLE. Used: WebSearch-surfaced direct quotations and paraphrase apparently drawn from the episode's show notes/recap page.

### Extracted principles

1. **"It's a data-centered human formula. It's how do humans respond to your content and what are the data points you need to look at."** Eves explicitly rejects treating YouTube growth as a keyword/SEO exercise; frames it as applied audience psychology validated by data.
   — Tag: **EXPERT OPINION.** Affects: whole-funnel (ideation → title/thumbnail → retention). Universal principle, but the specific data points he means (CTR, retention, session time) are long-form-centric; Shorts have thinner data surfaces.

2. **Psychographics over demographics.** He describes obsessing over a target viewer's morning routine, likes/dislikes, "what makes them tick," what else they watch, and what they're doing on and off the platform — as the input that should drive topic and content decisions, not just age/gender demographic buckets.
   — Tag: **EXPERT OPINION / HYPOTHESIS-CREATIVE PRINCIPLE** (a qualitative research approach, not a testable platform fact). Affects: ideation/topic-selection stage, upstream of everything else. When to use: channel strategy and content planning, especially in a saturated niche where demographic targeting alone isn't differentiating. Universal across long-form and Shorts.

3. **Squatty Potty case study — systematic title/thumbnail testing at scale.** Eves and team reportedly created **165 title variations** for the Squatty Potty "unicorn" campaign and ran them through paid (Facebook) ad testing before settling on the eventual winning framing ("This Unicorn Changed the Way I Poop"), which is reported to have produced roughly **10x the CTR** versus an untested title.
   — Tag: **FACT-adjacent EXPERT ACCOUNT** (a first-person case study Eves has told; the exact 10x figure and 165 count should be treated as his self-reported claim, not independently audited). Affects: title/thumbnail (top-of-funnel) stage specifically. Evidence given: the concrete before/after CTR multiplier. When to use: high-stakes launches or paid-amplified content where testing budget exists; not a claim that every channel needs 165 variants — the principle generalizes to "test more title variations than feels necessary, quantitatively, before committing." Long-form/thumbnail-driven format specifically; less applicable to Shorts (no separate thumbnail to test in the same way).

4. **Thumbnail design frameworks: the "blink rule," contrast, faces, and named templates** (e.g., 3-panel, face-and-object, face-and-face).
   — Tag: **HYPOTHESIS/CREATIVE PRINCIPLE** (design heuristics, not measurable platform facts). "Blink rule" = a thumbnail should communicate its core idea in the time it takes to blink/glance at a feed. Affects: CTR/click stage. Context-dependent: works differently by niche (faces perform differently in gaming vs. how-to vs. vlogging content, which the source does not fully disaggregate). Long-form only (thumbnails).

5. **"Try → Fail → Analyze → Adjust" as his stated core methodology** for both content strategy and channel growth broadly — an explicit iterative-testing loop rather than a one-shot formula.
   — Tag: **EXPERT OPINION.** Affects: whole-channel strategy / long-term growth process, not any single video. Universal, format-agnostic. Why it matters for the "why videos fail" angle: implies failure of an individual video is treated as a data point, not a verdict on the channel.

6. **Warning against ad-revenue dependency.** Reported advice: ad revenue is inherently unpredictable/fluctuating, so treat it as one revenue stream among several (sponsorship, product, affiliate, etc.) rather than the business model.
   — Tag: **EXPERT OPINION.** Affects: channel-as-business strategy, not viewer-journey mechanics. Universal.

---

## Source 4

**Creator:** Derral Eves (guest), interviewed by Tim Schmoyer, Video Creators
**Title:** "Use This Audience Growth Strategy When Starting from Scratch [with Derral Eves]"
**Publication date:** YouTube upload ~April 25, 2019; article republish on videocreators.com ~May 1, 2019 (per search-engine metadata; not independently re-verified)
**URL (article):** https://videocreators.com/use-this-audience-growth-strategy-when-starting-from-scratch-with-derral-eves/
**URL (video):** https://www.youtube.com/watch?v=q_K2NWB_aBo
**Length:** Not confirmed
**Format:** YouTube interview / podcast, hosted by a fellow YouTube-education specialist (Tim Schmoyer, whose whole channel is aimed at the same audience as this playbook)

**Main subjects covered:** A concrete step-by-step process for growing a channel "from scratch" (zero subscribers/zero data); psychographics research feeding into audience definition; the idea that basic production skills (editing, filming, camera presence, design) sometimes need to be built up before growth tactics can work at all.

**Why selected:** Distinct from the SPI/Hustle & Flowchart sources by focusing specifically on the **zero-to-one problem** (most other sources assume an existing channel with data) — directly useful for the "ideation/topic selection" and "channel strategy" parts of the brief for creators with no audience data yet, and it's from a fellow subject-matter expert's platform (Tim Schmoyer / Video Creators), which tends to produce more technically precise interviews than general business podcasts.

**Transcript availability:** TRANSCRIPT NOT FULLY AVAILABLE. Used: WebSearch-surfaced summary of the article's content; the underlying YouTube video and article page could not be fetched directly (both blocked by network egress).

### Extracted principles

1. **When you have no data, you're guessing — and you should say so.** Reported line (paraphrase, not verbatim quote confirmed): starting a channel without data means creators are working from an imagined "avatar" of their viewer rather than evidence, and Eves is explicit that this is a real limitation, not something to paper over with confidence.
   — Tag: **EXPERT OPINION.** Affects: ideation stage for brand-new channels specifically. Context-dependent: only applies pre-launch/early growth, before analytics exist; becomes moot once a channel has meaningful watch-time data (at which point Source 2 and 3's data-driven methods take over).

2. **Sequence: research psychographics → define target audience → select content that specific audience wants → produce it.** A four-step funnel presented as the replicable process, explicitly built on the same psychographics concept as Source 3 (consistent across his appearances, suggesting it's a stable core framework, not one-off talking points).
   — Tag: **EXPERT OPINION / HYPOTHESIS-CREATIVE PRINCIPLE.** Affects: ideation and topic-selection stage. Universal starting framework; execution specifics will vary hugely by niche.

3. **Production competency as a gate before growth tactics work.** Reported point: sometimes a creator needs to spend real time getting better at core craft (editing, filming, camera presence, thumbnail/graphic design) before audience-growth strategy can have any effect — i.e., strategy cannot compensate for a floor of execution quality.
   — Tag: **EXPERT OPINION.** Affects: pre-conditions for the entire viewer journey — if production quality is below a threshold, none of the CTR/retention tactics from other sources will work. When to use: honest self-assessment for brand-new or stalled channels. Universal, long-form and Shorts both (though the specific skills differ).

---

## Source 5

**Creator:** Derral Eves (interviewee)
**Title:** "How to Grow on YouTube in 2026 — Derral Eves' Playbook (Full Interview)"
**Publication date:** Search-engine metadata suggested February 9, 2026 (i.e., earlier this year relative to today's date). This could not be independently verified against the raw page — flagged as lower-confidence than the other four dates.
**URL (video):** https://www.youtube.com/watch?v=C6E6KvjcijQ
**URL (companion article):** https://balasabas.substack.com/p/how-to-grow-on-youtube-in-2026-derral
**Length:** Not confirmed ("Full Interview" in the title implies long-form, likely 45+ minutes, but unverified)
**Format:** YouTube long-form interview, with a companion Substack recap (Rob Balasabas, who covers creator-economy news)

**Main subjects covered:** What actually drives sustainable growth in the current (2026) environment vs. chasing hacks/virality; the role of creator "intention" — being explicit about who the content is for and what promise it makes; a direct rebuttal of the "shrinking attention span" excuse for stalled growth; what happens after a channel achieves growth (building a real business rather than pure platform dependency).

**Why selected:** This is the **most current** source in the set (matches "today" in the playbook's timeline) and is the only one that directly addresses two brief-relevant topics the older sources don't: (a) **viewer psychology around attention spans / long-form viability**, and (b) **post-growth business scaling**, both explicitly named in the assignment.

**Transcript availability:** TRANSCRIPT NOT FULLY AVAILABLE. Used: WebSearch-surfaced quotations apparently drawn from the Substack recap article, which itself is a secondhand summary of the interview — this is the least direct of the five sources (a summary of a summary), which should be weighted accordingly when using it.

### Extracted principles

1. **Rebuttal of the "attention spans are shrinking, so long-form is dying" narrative.** Quoted (per search synthesis): *"humans, once they are curious, they're sucked into great storytelling"* — offered as the reason people will sit through three-hour podcasts or hour-long livestreams despite supposedly shrinking attention spans. A related line attributed to him: *"we have short attention spans when we have sucky content."*
   — Tag: **HYPOTHESIS/CREATIVE PRINCIPLE** (this is an assertion about human psychology/behavior, not a citable platform fact — no data source is given in the material I could access). Affects: retention/hook stage broadly, and channel-strategy decisions about format length. Why he believes it: implicitly, that curiosity and narrative quality — not raw runtime — govern whether someone keeps watching. Evidence given: appeal to existing long-form formats' popularity (podcasts, livestreams) rather than his own channel data in what I could access. Universal vs. context-dependent: presented as universal, but it is a strong claim without disclosed evidence — flag for the playbook as "expert opinion, not proven," and note it's specifically a defense of **long-form**; the source doesn't address whether/how it applies to Shorts.

2. **Growth comes from "intention": clarity on who the content is for and what promise it makes, delivered consistently.** Reported framing: sustainable growth is less about hacks and more about a repeatable trust contract with a defined audience.
   — Tag: **EXPERT OPINION.** Affects: channel-strategy/positioning stage — upstream of any single video's title or thumbnail. Consistent with the psychographics framework from Sources 3 and 4 (audience-definition-first), suggesting this is a durable through-line in his teaching across 7 years of appearances, not a new 2026 pivot. Universal, format-agnostic.

3. **Post-growth: build a real business on top of YouTube, not total platform dependence.** Echoes the ad-revenue-dependency warning from Source 3, extended into a broader "don't let YouTube be your only business" framing for channels that have already achieved growth.
   — Tag: **EXPERT OPINION.** Affects: monetization/business-strategy stage, after the growth phase — outside the pure viewer-journey mechanics the rest of this dossier focuses on, but directly relevant to the playbook's "scaling" topic.

---

## Cross-Source Observations

- **A consistent throughline across 2019–2026 appearances**: psychographics-first audience definition → title/thumbnail as the CTR gate → data-driven iteration (Try/Fail/Analyze/Adjust) → don't over-index on ad revenue. This consistency across seven years of separate interviews is itself a form of corroboration — it isn't a shifting story.
- **The most genuinely novel/non-generic finding** across all five sources is the **Squatty Potty 165-title-variant case study** (Source 3): a specific, numbers-backed example of systematic, high-volume title/thumbnail testing rather than "try a few titles and pick your favorite." Most creator-education content gestures at "test your thumbnails" as a platitude; Eves is one of the few sources with a concrete, extreme example of what disciplined testing at scale actually looks like.
- **Weakest-evidence claim to flag**: the "humans get sucked into great storytelling regardless of attention span" position (Source 5) is asserted without disclosed data in the material accessible to this research pass — treat it in the playbook as an expert's belief worth including, but not as a proven mechanism.

## Overall Caveat

Every quote and figure in this document was obtained through `WebSearch` result synthesis, not direct verification of primary-source pages, because `WebFetch` and raw HTTP egress were both blocked network-wide during this research session (confirmed by testing multiple unrelated control domains, including Wikipedia and example.com). Dates, episode numbers, and reported view-count/channel-count figures should be spot-checked against the primary URLs listed above before being treated as final in the published playbook, and quotations should be understood as "as reported by search-engine-crawled secondary text," not as transcript-verified direct speech.
