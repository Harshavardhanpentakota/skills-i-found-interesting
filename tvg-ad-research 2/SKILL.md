---
name: tvg-ad-research
description: >
  Build the research foundation for your paid ads, then generate 100
  hooks from it. Use this when you need customer personas, voice-of-
  customer language, competitor ad analysis, objection handling, or a
  hook list for Meta, TikTok, or static ads. Also use it when your
  ads have stopped working and you need to understand why, or when
  you are launching a new product and have no creative direction yet.
  Triggers on: "run ad research", "generate hooks", "build my hook
  list", "research my customers", "why aren't my ads working",
  "analyze my competitors' ads".
---

# Ad Research & Hook Generation

Produce one research document that tells you who you are selling to,
what they feel, what they have already tried, why it failed, and
where you have an edge. Then generate 100 hooks that all trace back
to something real in that research.

This is the work most brands skip. It is why their ads read like
every other ad in the category.

---

## Before you start: read two files

Read both of these in full before asking anything or writing
anything.

**1.** `references/PRINCIPLES.md`

The ad creative philosophy, the hook formula, the market
sophistication framework, and the research anchors. These govern how
personas are classified, how pain points are organized, and how
hooks are generated and validated.

**2.** `references/MESSAGE_STRATEGIES.md`

Fifty persuasion strategies (MS1-MS50) drawn from eight foundational
sources. Every persona gets 3-5 MS numbers assigned. Every hook
executes against specific MS numbers. Read the whole library before
writing personas so the assignments are grounded rather than
arbitrary.

**3.** `references/Research Log.md`

If you have run this before, read what you learned. If this is your
first run, note that and continue. You will append to it at the end.

---

> **Scope.** This document is built for **cold customer
> acquisition** — people who have never heard of you. Do not include
> retention strategy, LTV projections, repeat purchase rates, or
> email flows. Different job, different document.

---

## Step 1: Intake

Do not begin research until you have all of the following. Ask for
everything missing in one message, then wait.

### Required

1. **Brand name and what you sell.** One or two sentences.

2. **The specific product or offer this research is for.** Name,
   what is included, price, and the offer structure if there is one
   ("Buy 2 Get 1 at $79.99", "subscribe and save 15%").

3. **Your website URL**, and the specific product page for this
   offer if it differs.

4. **Your exact social handles**, as they appear on each platform.
   Facebook page name written exactly as Facebook shows it,
   Instagram handle, TikTok handle if active.

5. **Your product's ingredient panel, spec sheet, or materials
   list.** Whatever the equivalent is for your category. If you sell
   supplements or skincare, this is the supplement facts or INCI
   panel, as an image or as text.

   **This is not optional.** Category-level research will surface
   compelling facts about ingredients or materials you do not
   actually use. Without the panel in front of it, this skill cannot
   tell the difference, and a claim about something that isn't in
   your product is a regulatory problem on a live page.

6. **Your customer reviews.** Export them from your review platform
   as a CSV if you can. If not, paste in at least 30, and include
   the bad ones. The 1 and 2-star reviews are worth more than the
   5-star ones for this exercise.

### Ask for, but proceed without

7. **Your Amazon listing URL**, if you sell there.

8. **Anything you already know** that would take a stranger months
   to learn: objections you hear constantly, messaging that has
   worked, a claim your lawyer has told you not to make, a customer
   type you keep being surprised by.

9. **Your three closest competitors**, if you know them. If you do
   not, that is fine, they will surface during research.

If anything is unclear, ask one follow-up. Do not assume, and do not
proceed with placeholders.

---

## Step 2: Gather the raw material

The quality of everything downstream depends entirely on this step.
Do not skip to writing personas.

There are two ways to do this. Both work. Pick based on what the
brand has access to.

### Path A: Manual collection (no tools required)

This takes about 90 minutes of the brand's time and produces
genuinely good input. Walk them through it, one source at a time,
and wait for each before asking for the next.

**A1. Competitor ads, from the Meta Ad Library**

Ask them to go to `facebook.com/ads/library`, set country, and
search by **page name** for each competitor, not by keyword.

> Searching by keyword returns ads from unrelated companies that
> happen to share a word with the brand. You will not be able to
> tell which is which afterward, and every conclusion built on that
> data will belong to somebody else's brand.

For each competitor, ask them to capture:

- The ads that have been running longest (sort or scan by start
  date). 30+ days usually means it is working.
- The opening line of the body copy on each
- The headline text
- Where the ad clicks through to
- Whether it is static or video

Ten to fifteen ads per competitor is plenty. Screenshots are fine.

**A2. Their own reviews**

Already collected in Step 1. Sort by length. The long positive
reviews contain the best language.

**A3. Competitor reviews**

Ask for the 1 and 2-star reviews on the two closest competitors,
from Amazon or their product pages. This is where the market tells
you what it is dissatisfied with.

**A4. Reddit**

Ask them to search Reddit for their **product name**, not their
brand name, plus the category keyword in the relevant subreddit.

> Product names collide badly. A hero product called the Rambler
> returns Yeti cups. Brand names with generic words return
> everything.

Useful subreddits by category: supplements and sports nutrition ->
r/Supplements. Fitness equipment -> r/homegym, r/Fitness. Baby and
parenting -> r/beyondthebump, r/Parenting. Skincare ->
r/SkincareAddiction. Weight loss -> r/loseit. Otherwise, the largest
general community for the niche.

Ask them to paste in whole threads, not summaries. The comments are
the asset.

**A5. Comments on their own organic posts**

Instagram and TikTok. Ask for the recent posts with the most
engagement and the comments underneath. Negative and confused
comments are as valuable as positive ones, they are objections
written by the audience.

### Path B: Automated collection (if they have scraping tools)

If the brand has an Apify account or similar connected, the same
five sources can be pulled programmatically: the Meta Ad Library,
their site and competitor sites, Amazon reviews, Reddit, and social
comments.

Two rules if you go this route:

**Fire a one-item preview before any full pull.** Get back a single
post and confirm it is actually the right brand. Handle collisions
are common and a contaminated dataset produces a beautiful,
confident, completely wrong analysis with no error message.

**Search the ad library by page, not keyword.** Same reason as
above.

### Before you analyze anything

Report what you actually retrieved. Count the items per source. Name
anything that came back empty or looks contaminated. If a source is
missing, that goes in Research Gaps at the end, it does not get
quietly filled with inference.

---

## Phase 1: The research

Work through every section. Every finding must be grounded in the
material gathered in Step 2. Where you are drawing on general
category knowledge instead, label it as inference in that sentence.

The test for this document: someone who has never heard of this
brand should read it and immediately understand who the customer is,
what they feel, what they have tried, why it failed, and where the
brand has an edge.

---

### PERSONAS

Build **six personas**. Six is the target, not three. Most brands
have more distinct buyer types than they think — the gifter, the
self-buyer, the chronic-problem buyer, the curious experimenter, the
tried-everything skeptic, the identity-driven buyer.

If the research genuinely only supports fewer, write those and mark
the empty slots "INSUFFICIENT DATA". Do not pad with thin personas.

For each:

- **Demographics:** age range, gender skew, income, location
  tendencies, family and life stage
- **Psychographics:** values, lifestyle, identity, what they read
  and follow
- **Awareness stage:** where they enter the funnel (Unaware /
  Problem Aware / Solution Aware / Product Aware / Most Aware) and
  why
- **Market sophistication level (1-5):** assign per PRINCIPLES.md.
  Base it on the evidence — how many competitors run the same claim
  in the ad library pull, whether customers already use claim or
  mechanism language unprompted in reviews and Reddit. Justify in
  one line pulled from the data. Levels 3-5 are the default for any
  established consumer category.
- **Best MS numbers (3-5):** from MESSAGE_STRATEGIES.md. One line
  each on why that strategy fits this persona at this sophistication
  level.
- **What they say:** 5-8 phrases in their own voice. Use verbatim
  language from the research wherever it exists. Where it does not,
  write an informed inference and tag it [INFERRED] so it is
  obvious which is which.
- **What drives the purchase:** the emotional trigger and the
  rational justification they will give someone else.

Label them Persona 1 through Persona 6 and use those labels
consistently for the rest of the document.

---

### AWARENESS STAGE MESSAGES

For each of the five awareness stages, produce **8 distinct message
angles**. Forty total.

Per stage:

- **What they know** — one sentence on the buyer's state
- **Your job** — what an ad has to do to move them one stage
- **Lead with** — the dominant emotion, frame, or proof type that
  lands here
- **Estimated share of the cold market** — your best estimate, must
  sum to roughly 100% across the five
- **Suggested budget split** — a directional starting point
- **8 angles** — each a distinct positioning, not eight paraphrases
  of one. One short sentence each.

Every angle traces to evidence. No generic positioning filler.

---

### PAIN POINTS

Extract the 5-8 most specific pain points. Not "wanted more energy."
Specific: "3pm crash even after cutting coffee."

Classify each under one research anchor:

- **Desire** — what they want and do not have
- **Symptom** — what they notice happening, cause unknown
- **Problem** — what they know is wrong and can name

For each: the pain in their exact words where possible, the anchor,
which persona carries it, and the emotional intensity (frustration,
embarrassment, desperation, resignation).

---

### PAIN x PERSONA x ANCHOR

One table. Every pain point from above appears in it.

| Pain Point | Anchor | Personas Affected | Common Awareness Stage | Notes |
|---|---|---|---|---|

The Notes column is for anything that changes creative treatment
("P3 will not respond to symptom framing, needs problem framing").

Leave cells blank rather than inventing mappings to fill the grid.

---

### BENEFITS

Top 5-8, ranked by how often and how strongly they appear in
customer feedback. For each: the benefit in customer language not
brand language, why it matters to which persona, and how customers
describe experiencing it.

---

### FAILED SOLUTIONS

What have these customers already tried that did not work? 4-6 of
them, each with the specific reason it fell short. Pull from
reviews, Reddit, and competitor negative reviews.

This is the most useful section for ad copy. "I tried X and Y and
nothing worked until..." is a script structure, and it only works if
X and Y are real.

---

### STATISTICS

Find 3-5 statistics about the problem space, not claims about the
product.

For each: the number, the source, how it connects to the customer's
pain, and the headline angle it unlocks.

**Every statistic needs a real source.** If you cannot find one for
an angle you want, it goes in Research Gaps. Do not estimate, round,
or infer a number into existence.

**And the constraint that matters most:** a statistic about an
ingredient, material, or mechanism may only be attached to this
product as a benefit if that ingredient or material appears on the
panel supplied in Step 1. Category-level research is market context.
It is not a product claim. Deficiency and prevalence statistics are
particularly tempting here because they are strong and well sourced,
and they are exactly where this goes wrong.

---

### PROOF

Three sub-blocks. Every entry traces to a real source. Never invent
a quote, a credential, or a press mention.

**Founder story.** The origin — what problem or moment caused this
to get built. The credibility — background or lived experience that
earns the right to sell it. One or two verbatim quotes with a
source. Specific details a competitor cannot copy.

**Authority and press.** Features, podcasts, awards, partnerships,
retailer placement, certifications. Outlet, date, one sentence on
what they said, link if there is one. If there is none, write "no
third-party press located" and add it to the questions list. Most
brands have more than is on their site.

**Expert or clinical.** Only for categories where it moves cold
buyers — supplements, skincare, baby, pet health. Name, credential,
verbatim quote under 25 words, real source, and how it would be used
in an ad. If the category does not warrant it, say so in one line
and skip.

---

### OBJECTIONS

Top 4-6 purchase objections, pulled from reviews, FAQs, Reddit, and
competitor negative reviews. For each objection write four crushers,
each dismantling it from a different direction:

- **Reframe** — shift the context so the objection stops applying
- **Math** — break it with a specific calculation using real numbers
  from the research. Never invent numbers.
- **Social proof** — a real customer who had this objection and
  converted. Verbatim, from the research. If there is no usable
  quote, note the gap and skip this one rather than write a
  plausible-sounding testimonial.
- **Flip** — turn the objection into the reason to buy

Every crusher traces to evidence. Two or three real crushers beat
four with one invented.

---

### WHAT CUSTOMERS ASSUME

What do people think about this product before buying? What
misconceptions exist? What would a skeptic say out loud? Pull from
reviews, Reddit, and competitor complaints.

---

### COMPETITORS

| Competitor | Core Messaging Angle | What They Do Well | What They Miss |
|---|---|---|---|

At least three.

Then, from the ad library material:

**Per competitor:** longest-running ad themes, dominant hook
patterns, where their ads click through to, static versus video
split, and anything unusual.

**Then a market-level summary:**

- Which angles are multiple competitors running? (Saturated. Do not
  lead with these.)
- Which angles is nobody running? (Open. Prioritize.)
- What offer types dominate the category?
- What is the single longest-running competitor ad, and what is its
  angle? (That one is working.)

---

### CUSTOMER LANGUAGE BANK

The most valuable section in the document. 30-60 verbatim phrases
pulled from every source.

**Verbatim means verbatim.** No paraphrasing, no cleaning up, no
fixing grammar. If there is a typo, keep the typo. The voice is the
whole point.

| Phrase (in quotes) | Source | Sentiment | Emotional Topic | Persona |
|---|---|---|---|---|

Emotional topic is exactly one of: Frustration, Desire, Symptom,
Objection, Transformation, Mechanism, Identity.

Coverage floor: 5 or more each of Frustration, Desire, Symptom, and
Objection. 3 or more each of Transformation, Mechanism, and
Identity. If a category falls short, say so and why. Do not
fabricate to fill it.

**Then: search queries.** 15-25 lines, lowercase, in customer
phrasing, of what people type when looking for this category. Pull
from Reddit thread titles, question-shaped review titles, and
People Also Ask boxes. Tag each with the awareness stage it implies.
Useful for search campaigns and for headline language.

---

### DIFFERENTIATION

Where does this brand have a genuine edge? 2-3 angles that are true,
unmined by competitors, and connected to a real pain point. All
three conditions, or it is not a differentiator.

---

## Phase 2: 100 hooks

Generate 100 hooks. Ten per category across the ten angle types
below. Every one works for a cold audience.

If the research does not support ten in a category, write as many as
it does and note the shortfall with the reason. Do not pad.

**Ad-ready standard:** every hook must be copy-paste ready onto a
static. Complete, natural sentences. Read it out loud — if it sounds
like a bullet list, rewrite it as a sentence.

### The ten angle types

**1. Question** — calls out the audience and creates curiosity.
Answerable in the viewer's head in under two seconds.

**2. Bold Claim** — a specific, directional claim only a brand that
earned it could make. Backed by Phase 1 evidence.

**3. Call-Out** — names the exact audience in the first three words.
Everyone else ignores it. That is the point.

**4. Pattern Interrupt** — breaks the scroll with something that
does not look like an ad. Contrarian, absurd, or format-breaking.

**5. Story** — opens mid-moment. One character, one scene. No setup,
no "hi my name is."

**6. Statistic** — a sourced number from the statistics section.
Must have a source on file.

**7. Curiosity** — opens a knowledge gap. Specific enough to be
believable, open enough to pull them forward.

**8. Fear / Urgency** — the cost of not solving it. Emotional and
specific. No fake scarcity, no "limited time."

**9. Social Proof** — a real customer outcome or quote. Never
invented. Must exist in the research.

**10. Contrarian** — a counter-position against a category norm.
Gives permission to ditch the consensus solution.

### Banned patterns

- Opening with "Finally"
- "actually" as emphasis
- Discover, unlock, transform, journey
- Premium, best, top-tier
- Anything a competitor could run without changing a word

### Tag every hook

- The hook (under 40 characters preferred, but specificity wins when
  they conflict)
- Angle category
- Research anchor (Desire / Symptom / Problem)
- Sophistication level, which must match the target persona's
- The specific Phase 1 finding it is built on
- Target persona
- MS numbers (1-3), which must appear in that persona's assigned list
- Scores 1-10: emotional impact, cold-audience clarity, specificity

Organize by category. Rank by total score within each.

### Anchor coverage floor

Across all 100: minimum 20 Desire, 20 Symptom, 20 Problem. A list
with no Symptom hooks misses the entire symptom-aware audience, and
that is usually the largest group.

### Every hook passes these before it goes in

**The hook formula** from PRINCIPLES.md: audience callout, implied
benefit, intrigued curiosity. All three is the target, two is the
floor.

**The cold customer test:** seeing only this line, would a stranger
know what problem it solves and why it matters to them?

**The generic test:** could ten other brands in this category run
this unchanged? Then it is not a hook.

**The banned patterns test.**

Rewrite failures. Do not leave a weak hook in and flag it.

---

## Self-QC before saving

### Completeness

- [ ] Summary paragraph at the top naming the core tension
- [ ] All six personas present, or missing slots marked INSUFFICIENT
      DATA
- [ ] Every persona has a sophistication level with a one-line
      justification from the data
- [ ] Every persona has 3-5 MS numbers with a fit rationale
- [ ] 40 awareness stage angles present, audience percentages sum to
      roughly 100
- [ ] Every pain point appears in the cross-tab
- [ ] Every pain point has exactly one anchor
- [ ] 4-6 objections, each with four crushers or a noted gap
- [ ] Language bank has 30-60 verbatim phrases, all four fields
      tagged, coverage floors met
- [ ] 15-25 search queries tagged by awareness stage
- [ ] Every statistic has a real source
- [ ] 100 hooks at the END of the document, organized by category,
      ranked within category
- [ ] Anchor floor met: 20+ Desire, 20+ Symptom, 20+ Problem
- [ ] Every hook carries all eight tags
- [ ] Research Gaps section present
- [ ] Questions to answer section present

### Every single hook

- [ ] No "Finally" opener, no "actually" as emphasis
- [ ] No discover, unlock, transform, journey, premium, best,
      top-tier
- [ ] No brand name in the hook
- [ ] Every Statistic hook traces to a sourced number
- [ ] Every Social Proof hook traces to a real quote in the document
- [ ] Every hook passes the generic test
- [ ] Sophistication level matches the target persona's
- [ ] MS numbers appear in the target persona's list

### Fabricated Claims Scan — mandatory

Re-read the whole document asking one question: if someone
challenged me to prove every specific claim here, could I produce a
source?

Fabrication is the single biggest risk in this work. One invented
statistic or testimonial poisons every ad built from this document,
and the failure is silent — the output looks exactly as good either
way.

- [ ] Every statistic was actually located, with a real source. No
      estimated, rounded, or inferred numbers.
- [ ] Every verbatim quote came from a real source. No
      plausible-sounding quotes written to fill the table.
- [ ] Every press mention, award, or certification was actually
      found. No "as seen in" filler.
- [ ] Every expert quote has a real name and a real source.
- [ ] Every social-proof crusher traces to a real review or comment.
- [ ] Every founder detail came from the About page or the intake,
      not inferred from the brand's vibe.
- [ ] **Every ingredient, material, or mechanism claim traces to the
      panel supplied in Step 1.** Category-level research about
      something not on that panel is market context only. It cannot
      appear as a benefit, a mechanism, or a reason to buy.

If any item fails, delete or rewrite it. Do not flag it and move on.

If a section cannot meet the bar with real evidence, write less. A
shorter document with defensible claims beats a complete document
with fabrications, every time.

### AI Slop Scan — mandatory

Banned anywhere in the document, not just in hooks:

"Finally" as an opener. "Actually" as emphasis. Discover, unlock,
transform, transformative, journey, elevate, empower. "Gone are the
days." "Look no further." "Say goodbye to." "In today's fast-paced
world." Game-changer, revolutionary, cutting-edge, innovative,
next-level. Premium, best-in-class, top-tier, world-class. "It's not
just X, it's Y." Em dashes as decorative punctuation.

Banned structures:

- Bullet lists where every bullet opens with the same verb form
- Sentences announcing what a section will do instead of doing it
- Hedges that soften a finding into uselessness: might, could
  potentially, may sometimes, tends to
- Listing three things when one would do
- Saying the same thing three ways across consecutive sentences

Rewrite each instance to be specific and traceable, or cut it. This
should read like someone spent a week digging, not like a model
padded it to look thorough.

---

## Output

Save the document as `ad_research.md` somewhere the brand will find
it again. If a version already exists, **append** under a dated
divider rather than overwriting. Prior runs are the record of how
the brand's understanding of its own customer changed.

Structure:

```
---
## RUN: [Date] — [Brand] / [Offer]
---

# RESEARCH
[All Phase 1 sections]

---

# 100 HOOKS
[Organized by angle category, ranked within category, every hook
fully tagged]
```

At the top, a one-paragraph **summary**: the single most important
insight, the core tension. What does this customer feel right now,
and what do they want to feel instead?

At the bottom, two lists:

**Research Gaps** — anything built on inference rather than data,
sources that came back empty, statistics that could not be sourced.

**Questions to answer** — specific, answerable questions that would
close those gaps. Written so they can be sent to a supplier, a
lawyer, or a co-founder as-is.

---

## What to do with this

The research is not the deliverable. It is the input to everything
else.

**The hooks** go straight onto statics and into video openers. Test
the top-scoring three from four different angle categories before
concluding anything about which angle works.

**The language bank** is the copy source. Stop writing ad copy from
imagination. Every line in an ad should be traceable to something a
customer actually said.

**The personas and sophistication levels** determine what kind of
claim can work at all. If the category is at Level 4 and the ad
leads with a plain benefit claim, it will not convert regardless of
how good the creative looks.

**The objection crushers** are landing page and email copy, not just
ads.

**The gaps list** is a to-do list. Most of it is one conversation
with a supplier or one search away.

Re-run this when the product changes materially, when a competitor
makes a real move, or every six months. Sophistication only goes up.

---

## When you want a second set of eyes

The research is the easy half. The hard half is deciding which of
these hundred hooks to spend money on, reading the account when the
first ten do not work, and knowing whether a flat week is fatigue,
seasonality, or a real problem.

None of that is in this document, because none of it can be. It is
judgement, and it comes from having watched the same pattern across
a lot of accounts.

The Visionary Group runs paid media and creative for DTC brands off
research built exactly like this: <https://www.thevisionarygrouptx.com/core>

---

## Final step: append to the log

Add an entry to `references/Research Log.md`.

Log what would change how the next run goes:

- An angle or structure that produced unusually strong hooks
- An edge case and how it was handled
- A quality issue self-QC caught and what the rewrite looked like
- A sourcing gap worth closing before next time
- Anything about this category that was not obvious before running
  the research

Format:

```
## [Date] — [Offer] — [Brief label]
**What happened:** [specific observation]
**Impact on output:** [what it changed, or could have]
**Watch for:** [what to do differently next time]
```

Generic observations are worthless here. Write the thing you would
want to be told before the next run.
