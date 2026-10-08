# Curated YouTube tutorials for building and running AI avatar / AI persona channels (as of 2026-10-08)

Method notes for the report writer:
- All videos were found with the NexLev `youtube_search` tool between upload filters "month" and "year". Views, length and age ("3w ago" etc.) are as YouTube showed them on 2026-10-08. Exact publish dates are given only where `youtube_video_details` confirmed them.
- "Deep-verified" means I checked the content itself. Two videos were watched with Gemini (`watch_youtube_video_and_ask`) before the tool's 5-calls-per-day LITE limit ran out. Two more were checked from full transcripts, and six from their full descriptions and chapter lists.
- **Bias flags:** "Affiliate" means the description has an affiliate or referral link (`fpr=`, `/s/…`, `?via=`, `ref=`, `tolt.link`, coupon codes). "Vendor" means the tool company's own channel.
- **Higgsfield links are everywhere.** Most English AI-influencer and Claude-automation tutorials from Sept and Oct 2026 carry Higgsfield affiliate links. Treat any "best tool" claim in them with caution.
- URL format is always `https://www.youtube.com/watch?v=VIDEO_ID`.

---

## Q1. Creating a consistent AI influencer / AI persona (images + video)

### Takeaway
The current (Sept–Oct 2026) English tutorials teach one dominant workflow. You lock a "master" face, using Higgsfield AI Influencer 2.0 / Soul, Nano Banana Pro/2.1, OpenArt characters or Google Flow. You then keep it consistent with reference images and "keep everything else unchanged" prompts, and animate it with Seedance 2.5 or Kling 3.0 motion control. A free/local LoRA route through ComfyUI exists but is older (4–7 months) and more technical. Almost every recent English video is Higgsfield- or OpenArt-affiliated.

### Cited Findings
**Deep-verified**
- Aftab Khan's AI-influencer video (Hindi, published 2026-09-15) teaches this sequence. Build the base character in Higgsfield "AI Influencer" with parameter sliders, then upscale with Topaz inside the platform. Keep the face consistent across outfits and locations with Nano Banana Pro reference images and "keep everything else unchanged" prompts. Make lifestyle clips with Seedance 2.0/2.5 and motion control or dance with Kling 3.0. Higgsfield is promoted throughout. (Verified by watching with Gemini, first 10 minutes.) — [Source](https://www.youtube.com/watch?v=vfuTJbF9HJo)

**Video list (newest/strongest first)**
- **"How to Make Consistent Characters with AI (Full Course)"** — Creating with Conor · 2w ago · 17,843 views · 10:39 · Teaches: building one character and keeping it consistent across shots on Higgsfield · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=ytgApiFpvSA)
- **"How to Create Consistent Character AI Influencers(Step by Step 2026)"** — Mariana Montoya · 3w ago · 16,541 views · 10:24 · Teaches: consistent face, style, personality and visual identity for an AI influencer · Bias: none visible in snippet (not verified) — [Source](https://www.youtube.com/watch?v=nr2vf8O6_5k)
- **"The Only AI Influencer Guide You'll Ever Need in 2026"** — Isa does AI · 2w ago · 23,886 views · 8:57 · Teaches: Higgsfield Influencer Studio + GPT workflow · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=bp3p4btteo0)
- **"How I Create 100% Realistic AI Influencers with Seedance 2.5!"** — Isa does AI · 2w ago · 28,579 views · 17:26 · Teaches: turning a consistent character into realistic video with Seedance 2.5 · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=bLVlxxLun4s)
- **"How to Make Consistent AI Influencers for Instagram"** — Isa does AI · 12d ago · 23,056 views · 11:44 · Teaches: an Instagram-ready consistent influencer from scratch · Bias: tolt.link affiliate — [Source](https://www.youtube.com/watch?v=zV8EPHM1d4c)
- **"STOP Wasting Credits & Master Higgsfield AI in 18 Minutes"** — Youri van Hofwegen · 2w ago · 193,919 views · 18:09 · Teaches: full Higgsfield feature tour and credit-efficient settings · Bias: Higgsfield affiliate + "bonus package" — [Source](https://www.youtube.com/watch?v=M73BrFnVPA8)
- **"How to Use Higgsfield AI Better than 99% of People"** — Roboverse · 12d ago · 109,704 views · 17:02 · Teaches: advanced Higgsfield workflow · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=dJSJMt4ESEU)
- **"Nano Banana 2.1 Is FINALLY Here (I Tested Everything)"** — Youri van Hofwegen · 1d ago · 26,991 views · 13:59 · Teaches: what the new Nano Banana 2.1 image model does, including character/reference edits · Bias: OpenArt affiliate — [Source](https://www.youtube.com/watch?v=0_uKFqBPS9Q)
- **"Best AI Influencer Generator for 2026 (Full Guide & Comparison)"** — Artturi Jalli · 6d ago · 3,836 views · 19:41 · Teaches: side-by-side tool comparison with the exact prompts shown · Bias: OpenArt affiliate — [Source](https://www.youtube.com/watch?v=oCytAiD7TDM)
- **"How To Use Google Flow to Create Consistent AI Characters & Videos | Full Tutorial for Beginners"** — AI Edge Mastery · 3mo ago · 125,984 views · 9:26 · Teaches: free Google Flow character consistency · Bias: none visible — [Source](https://www.youtube.com/watch?v=oCcU1C8WilI)
- **"How to Build a Realistic AI Influencer - The ONLY Guide You Need"** (older but a foundational, high-view guide) — Dan Kieft · 7mo ago · 259,361 views · 16:25 · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=IN7bo1_ZPDg)

**LoRA / free-local route (older; best available)**
- **"Create an Ultra Realistic AI Influencer From Scratch (LoRa + FREE Workflow)"** — Json · 4mo ago · 36,958 views · 6:04 · Teaches: training a character LoRA on Z-Image Turbo from a dataset · Bias: free workflow — [Source](https://www.youtube.com/watch?v=xgVLleA0yZM)
- **"How to Create an AI Influencer from scratch Without Training a LoRA"** — Json · 4mo ago · 16,828 views · 8:18 — [Source](https://www.youtube.com/watch?v=_mN1AAzcBT4)
- **"Create HYPERREALISTIC AI Characters That INTERACT | FREE & LOCAL"** — Mickmumpitz · 2mo ago · 66,402 views · 34:28 · Teaches: a cast of consistent characters placed together with bounding boxes, run locally — [Source](https://www.youtube.com/watch?v=ghFYDG0DF1w)
- **"ULTIMATE KREA 2 LoRA Training! Get PERFECT RESULTS!"** — Aitrepreneur · 3mo ago · 53,673 views · 24:37 — [Source](https://www.youtube.com/watch?v=OCsqHdHf81M)

### Inferences
- Model and tool names in the Oct 2026 titles are useful for a "current stack" list. These include Higgsfield AI Influencer 2.0 + Genjutsu (motion transfer), Higgsfield Cinema Studio 4.0, Seedance 2.5, Nano Banana 2.1 (released about 2026-10-07), Kling 3.0 motion control, OpenArt and Google Flow.
- A beginner should start with Creating with Conor or Mariana Montoya, then Isa does AI for video. LoRA/ComfyUI is only worth it for someone who wants zero per-generation cost and has a GPU.

### Gaps
- I found no strong 2026 dedicated "Higgsfield Soul ID" tutorial separate from the Influencer 2.0 videos above.
- The OpenArt "Characters" feature was covered only by affiliate creators (Isa does AI, Youri). I found no neutral comparison besides Artturi Jalli's, which is also affiliate.

---

## Q2. AI talking avatars and lip-sync (HeyGen, Hedra, Kling, OmniHuman, Captions…)

### Takeaway
HeyGen Avatar V, launched about 5 months ago, is the best-documented talking-avatar tool, and HeyGen's own channel has the most tutorials. Google's Gemini Omni / Omni-Flash, inside Flow and Vids, is the main free alternative; the catch is that Flow gives 8–10 s clips that you have to stitch together. For lip-syncing a custom AI character, creators combine Higgsfield or Kling with ElevenLabs voices.

### Cited Findings
- **"Make the BEST AI Avatar of Yourself in 2026 (Full HeyGen Walkthrough)"** — HeyGen · 1mo ago · 3,897,489 views · 5:37 · Teaches: a Digital Twin in seven steps · Bias: vendor — [Source](https://www.youtube.com/watch?v=yKhZb4Ny_I0)
- **"How to Use HeyGen Avatar V (Complete Tutorial + Best Practices)"** — HeyGen · 5mo ago · 47,939 views · 8:36 · Bias: vendor — [Source](https://www.youtube.com/watch?v=6JaW8si98q8)
- **"Beginner workshop: Create your first video with Avatar V and the Video Agent"** — HeyGen · streamed 3w ago · 2,226 views · 1:02:56 · Teaches: hands-on zero-to-first-video session · Bias: vendor — [Source](https://www.youtube.com/watch?v=PeIYBJT-5xk)
- **"How I Make Realistic AI Avatars with Heygen's Avatar V!"** — Isa does AI · 5mo ago · 26,859 views · 8:01 · Teaches: cloning face and voice from a 15-second phone clip — [Source](https://www.youtube.com/watch?v=ZI_cIAqKcKs)
- **"How I Make LONG Talking AI Avatars in Google Flow (Full Tutorial)"** — Founder Stack By Naz · 3d ago · 14,967 views · 17:49 · Teaches: stitching 12–15 eight-to-ten-second Flow clips into a 2-minute avatar ad — [Source](https://www.youtube.com/watch?v=4aqdVFYk2Sg)
- **"Higgsfield AI + ElevenLabs Creates Perfectly Lip Synced AI Videos"** — Grow With Miz · 3w ago · 2,157 views · 13:05 · Teaches: lip-syncing a custom AI character — [Source](https://www.youtube.com/watch?v=X2D8b52uksg)
- **"How to Use Gemini Omni (Step-by-Step Tutorial)"** — Kevin Stratvert · 4mo ago · 143,485 views · 6:05 · Bias: none visible — [Source](https://www.youtube.com/watch?v=TyaKXdKbL98)
- **"I Compared Top 4 AI Talking Avatar Video Generator, So You Don't Have To"** — The AI Hustle · 2mo ago · 5,061 views · 4:18 · Teaches: HeyGen 4 vs Creatify Aurora vs Veed Fabric 1.0 vs OmniHuman 2.5 — [Source](https://www.youtube.com/watch?v=ybxN6BmszEI)
- **"How to Lip Sync any Audio to Video with any AI Model (Wan 2.6, Omnihuman 1.5, etc...)"** — ElevenLabs · 8mo ago · 75,231 views · 4:03 · Bias: vendor — [Source](https://www.youtube.com/watch?v=FI2s06CTvHg)
- **"My AI Avatar Clone is So Realistic It Replaced Me"** — Dan Kieft · 4mo ago · 194,877 views · 18:01 · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=xUdKBqP81k8)
- **"Create Realistic AI AVATARS That Look And Talk EXACTLY Like You! | FREE ComfyUI Tutorial"** — MDMZ · 10mo ago · 88,007 views · 10:02 · Teaches: free, local talking heads with Nano Banana Pro and InfiniteTalk — [Source](https://www.youtube.com/watch?v=2yeo3D76a4s)
- Google Vids replaced Veo 3.1 with a new model called "Omni-Flash" and added avatar lip-sync, per a 9-day-old tutorial (Maria AI, 222 views) — [Source](https://www.youtube.com/watch?v=rmas1V0kRGM)

### Inferences
- The HeyGen video's 3.9M views in about a month on the vendor channel most likely include paid promotion. View count is not a quality signal for vendor content.
- For a persona channel, as opposed to a clone of yourself, the Higgsfield/Kling + ElevenLabs route (Grow With Miz, Aftab Khan) fits better than HeyGen Digital Twin.

### Gaps
- No recent (≤3 months), substantial-view tutorials were found specifically for **Hedra**, **Captions (Mirage)** or **OmniHuman 2.5** on its own. A search combining HeyGen/Hedra/Kling returned zero results.

---

## Q3. Recurring AI character formats that went viral ("how I made" breakdowns)

### Takeaway
"How I made" breakdowns exist for most viral formats: historical POV, time-travel vlogs, Bigfoot/Yeti vlogs, baby podcasts, AI cartoons/stickman, 2D history and animal/pet niches. The most-viewed recent ones come from affiliate-heavy channels (Roboverse, Money Degree, Mark Ai Guy). Bigfoot-vlog and baby-podcast breakdowns specifically have low view counts in 2026, which suggests those formats have peaked.

### Cited Findings
- **"How to Make Videos Like Chloe vs History With AI (Full Guide)"** — Roboverse · 3mo ago · 98,970 views · 14:25 · Teaches: recreating a viral recurring-character history format · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=OxyynOXX6mY)
- **"How To Make Time Travel Vlogs With AI"** — AI Century · 6mo ago · 218,314 views · 6:23 · Bias: Higgsfield — [Source](https://www.youtube.com/watch?v=F2dyaOk-deQ)
- **"How to Make Viral AI Vlogs with Grok Bot + Seedance 2.5 (Full Breakdown)"** — Sulfur · 1mo ago · 12,792 views · 5:49 — [Source](https://www.youtube.com/watch?v=JjsDPTpz6qU)
- **"How to Make Viral AI Vlogs (Bigfoot, Yeti… & James?!)"** — Max Automates · 2mo ago · 93 views · 8:03 · Teaches: Bigfoot morning-routine and Yeti vlog formats (low views, but the most direct breakdown found) — [Source](https://www.youtube.com/watch?v=0VmwF40ow00)
- **"How to Create a Talking Baby Podcast with AI"** — Mariana Montoya · 1mo ago · 1,959 views · 9:06 — [Source](https://www.youtube.com/watch?v=J_ZKPmebOYE)
- **"How to Make Cartoon Videos With AI (Full Guide)"** — Roboverse · 3w ago · 106,870 views · 13:30 · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=v7Qv2QrRv1c)
- **"How to Make Stickman Animation with AI 100% FREE (Full Course)"** — Money Degree · 1mo ago · 136,814 views · 24:05 · Teaches: the fast-growing stick-figure niche — [Source](https://www.youtube.com/watch?v=jglonMYLI6g)
- **"I Cloned a VIRAL Faceless History Channel With AI (FULL COURSE)"** — Money Degree · 1d ago · 7,690 views · 25:04 · Bias: Higgsfield link — [Source](https://www.youtube.com/watch?v=F2osLU69olM)
- **"👉 How I Built a VIRAL 2D History Channel With AI Full Tutorial"** — MonetizeMind by Sam · 3w ago · 24,530 views · 10:09 — [Source](https://www.youtube.com/watch?v=bm4qlXmtcfE)
- **"How to Make Viral AI Story Videos Like His Story"** — Sam Lee · 2w ago · 10,731 views · 14:43 — [Source](https://www.youtube.com/watch?v=Psmb72lh1V4)
- **"Make Historical POV Videos with AI (Step by Step)"** — Flow Ai · 3mo ago · 11,430 views · 3:38 — [Source](https://www.youtube.com/watch?v=w85daio-4-w)
- **"This Secret AI Pet Niche Got 687M Views! (Using FREE AI Tools)"** — Profit Hub · 2w ago · 30,745 views · 6:03 — [Source](https://www.youtube.com/watch?v=NLH5Hn647sY)
- **"Create This New Ai Niche & Go Viral In 24hrs | 100% FREE Tools"** (AI plant-growth time-lapse) — Mark Ai Guy · 1mo ago · 257,964 views · 13:13 — [Source](https://www.youtube.com/watch?v=HsRHMaN3SVY)
- **"Built a Kids Animation Channel Using Free AI! (Full Tutorial)"** — AI Foundry · 9d ago · 11,949 views · 9:55 — [Source](https://www.youtube.com/watch?v=FsOiEE2qZ_c)

### Inferences
- Strong "invent your own format" examples come from Mark Ai Guy, who has published a series of new-niche videos (plant time-lapse, AI cooking, car-mod transformations, anime), each at 137K–566K views.
- Recurring-character formats (Chloe vs History, Bigfoot) depend on character consistency, so they should be studied after Q1.

### Gaps
- Bigfoot/Yeti and AI-baby-podcast breakdowns from 2026 are all low-view (<2K) or 8–11 months old. I found no authoritative recent "I grew a Bigfoot channel to X" case study.

---

## Q4. Niche research for faceless/AI channels (outlier method, NexLev, vidIQ, 1of10, untapped/new niches)

### Takeaway
The best recent niche-research tutorials combine outlier/competitor data (from NexLev, vidIQ's Claude connector or TubeLab) with Claude/Claude Code analysis. vidIQ adds an "empty-square" principle: take a proven format and point it at an untouched topic. Most creators here sell coaching, and NexLev tutorials are almost all affiliate (20% coupon codes).

### Cited Findings
- **"How I find UNTAPPED youtube niches using AI [CLAUDE CODE]"** — Leo Grundström Biz · 4mo ago · 16,576 views · 14:52 · Teaches: automating niche research with Claude Code · Bias: coaching upsell — [Source](https://www.youtube.com/watch?v=LsAW25l5JBk)
- **"How I find UNSATURATED youtube niches with AI [EASY METHOD]"** — Leo Grundström Biz · 5mo ago · 29,029 views · 21:38 · Bias: free course and coaching — [Source](https://www.youtube.com/watch?v=X3VMKwnJniU)
- **"How I Find Faceless YouTube Niches That Make $10k/month+"** — Chris Barrera · 3mo ago · 13,514 views · 16:14 · Bias: 1-1 coaching upsell — [Source](https://www.youtube.com/watch?v=D1Hm7hNfbSM)
- **"how i find profitable faceless niches for free (full method)"** — moneyboymax · 2mo ago · 17,687 views · 16:24 · Bias: mentorship upsell — [Source](https://www.youtube.com/watch?v=gGrz__zc-5k)
- **"I Found 20 Faceless AI YouTube Niches With 0 COMPETITION"** — Steffen Miro · 1mo ago · 15,865 views · 28:02 · Bias: 1/1 calls — [Source](https://www.youtube.com/watch?v=IYHX0c_UOvE)
- **"The 30 Most Profitable Faceless AI Niches Right Now 2026"** — Steffen Miro · 1mo ago · 6,580 views · 40:01 — [Source](https://www.youtube.com/watch?v=ByBklSnWw7E)
- **"Exposing The New YouTube Automation Goldrush (October 2026)"** — TubeLab · 5d ago · 51,566 views · 6:57 · Bias: promotes its own TubeAvatar product — [Source](https://www.youtube.com/watch?v=W7L2rZVyYmY)
- **"The New Way Small Channels Get Views in 2026"** — vidIQ · 2mo ago · 89,989 views · 7:35 · Bias: vendor — [Source](https://www.youtube.com/watch?v=AMlVWoRNszc)
- **"Nexlev Full Tutorial for Beginners 2026 (Step by step)"** — Toolysto · 1mo ago · 673 views · 1:08:37 · Bias: affiliate, 25% coupon — [Source](https://www.youtube.com/watch?v=pO94ChB-BG0)
- **"NexLev Niche Finder Tutorial: Find Unsaturated Niches"** — Software Scope · 5mo ago · 3,979 views · 5:35 · Bias: affiliate. The same channel's critical review is "NexLev Review: Don't Waste Your Money!" (8mo ago) — [Source](https://www.youtube.com/watch?v=Z0TrSTdT2rI); [Review](https://www.youtube.com/watch?v=IcckysZNZ7E)
- **"How I Find Viral YouTube Niches & Steal Competitor Strategy Using Claude + NexLev (2026)"** — Mr Hassnain 2.0 · 3mo ago · 2,015 views · 31:39 (likely Urdu/Hindi; language not verified) — [Source](https://www.youtube.com/watch?v=Eq4w5M-T03w)
- **"The Complete Guide to Viral Ideas in 2026 (YouTube Ideation Masterclass)"** — 1of10 Podcast · 11mo ago · 10,447 views · 1:12:23 · Bias: vendor, 1of10 (older) — [Source](https://www.youtube.com/watch?v=Bxch8wSzEkc)
- vidIQ's transcript-verified "empty square" method: plot proven formats on one axis and topics on the other, then "slide that format sideways" into a topic nobody covers (e.g. sleep stories on naval history or on a single industry). Gut check: "If your channel could be swapped out for any other channel in the niche and nobody would notice… you've got a problem." — [Source](https://www.youtube.com/watch?v=d_csri5M9xw)

### Inferences
- A learner who already has NexLev MCP access gets the most from the Leo Grundström Claude Code video plus the vidIQ "empty square" framing. Together they cover both data-driven outlier finding and inventing a new niche.

### Gaps
- No official NexLev-channel tutorial surfaced in search. All NexLev walkthroughs found were third-party affiliate videos.
- No strong 2026 1of10 hands-on outlier tutorial; the 1of10 masterclass is 11 months old.

---

## Q5. Virality and packaging: hooks, retention, thumbnails, Shorts/Reels/TikTok algorithm 2026

### Takeaway
Paddy Galloway's 2h45m masterclass (published 2026-09-14) is the most authoritative recent source on ideation, packaging and retention. Isaac's 7-day Shorts experiment and DecodingYT's Shorts formula (698K views) are the best practical short-form guides. On Reels and TikTok, Brock Johnson (Build Your Tribe) and Robert Benjamin publish frequent algorithm updates; the latest are from October 2026.

### Cited Findings
**Deep-verified**
- **"2-Hour Youtube Masterclass From The World's Highest-Paid Strategist"** — Open Residency (guest: Paddy Galloway) · published 2026-09-14 · 256,122 views · 4,704 likes · 2:45:08 — [Source](https://www.youtube.com/watch?v=Z2uoA3bhJT0)
  - The chapters cover the CCN framework, a "100 ideas to make 1 video" funnel, "20% Better Thumbnail, 40x the Views", "Ten Titles, Three Thumbnails, Every Video", a "45-Second Intro Formula", "The Only Two Metrics He Trusts" and "The One Thing AI Still Can't Do".
  - Bias: podcast sponsors (Ketone IQ, Wispr Flow, Momentous, beehiiv), a 1of10 affiliate link, and Paddy's paid accelerator.
- **"How to Make VIRAL YouTube Shorts in 2026"** — DecodingYT · published 2026-08-28 · 698,144 views · 14,145 likes · 15:27 — [Source](https://www.youtube.com/watch?v=VUT6HhqKkBA)
  - Covers hooks, editing, topics, proven formats and curiosity gaps, and gives away a free Shorts safe-zone template.
  - Bias: Epidemic Sound sponsor and vidIQ affiliate. The keywords target Hindi-speaking searchers ("viral kaise kare"); spoken language not verified.
- **"I Blew Up a Shorts Channel in 7 Days!"** — Isaac · 4d ago · 318,440 views · 18:29 · Bias: sponsored by .STORE Domains — [Source](https://www.youtube.com/watch?v=QXfugR3ZIAs) (verified by watching with Gemini)
  - Niche and persona: picked "Business Stories" with a consistent low-poly AI art style and a recurring persona.
  - Scripting: used ChatGPT to reverse-engineer the structure of viral scripts (e.g. Zack D. Films) and a "roleplay" hook that casts the viewer in the story.
  - Retention: fast cuts, auto-captions, trending music and SFX, and a clear payoff at the end.
  - Results: Shorts got about 1.1K–21K views each; the final video passed 140K on IG and TikTok after cross-posting.

**Video list**
- **"How I Actually Write Viral Scripts"** — Isaac · 7mo ago · 260,205 views · 17:30 · Bias: .store sponsor — [Source](https://www.youtube.com/watch?v=cX8c3R2LFd4)
- **"12 Thumbnail Formats That Keep Going Viral"** — DecodingYT · 3mo ago · 143,701 views · 14:16 · Bias: sponsored by 1of10 — [Source](https://www.youtube.com/watch?v=abZz4IWGtcM)
- **"The New Thumbnails Dominating YouTube in 2026"** — vidIQ · 7mo ago · 147,713 views · 23:53 · Teaches: 11 thumbnail styles · Bias: vendor — [Source](https://www.youtube.com/watch?v=Yv6RLQv889M)
- **"5 Claude Skills To Grow Faster Than 99% of People on Social Media"** — Kallaway · 2mo ago · 122,606 views · 23:14 · Teaches: Claude Skills for short-form content systems · Bias: free guide funnel — [Source](https://www.youtube.com/watch?v=Cnk9NQ8JpCs)
- **"NEW Instagram Algorithm: How To Go Viral And Get Followers"** — Build Your Tribe (Brock Johnson) · 2d ago · 29,341 views · 17:27 — [Source](https://www.youtube.com/watch?v=dzYQ2bTku2U)
- **"Instagram's NEW Algorithm Changes Explained for October 2026"** — Robert Benjamin · 1d ago · 3,369 views · 11:53 — [Source](https://www.youtube.com/watch?v=zHWHRejp7SY)
- **"The FASTEST Way to Go Viral on TikTok in 2026 (TikTok Algorithm Explained)"** — Robert Benjamin · 3w ago · 14,310 views · 11:43 — [Source](https://www.youtube.com/watch?v=Oy88ZOJ7Igo)
- **"Why 90% Of Instagram Reels Die At 200 Views (and how to break out)"** — Ryan Sterling · 13d ago · 16,162 views · 7:33 · Bias: free-course funnel — [Source](https://www.youtube.com/watch?v=LaC_nxv9N8Q)
- **"give me 15 minutes, I'll make your hooks 89% better"** — heyDominik · 3d ago · 7,903 views · 15:16 — [Source](https://www.youtube.com/watch?v=3e9y95qsKlg)
- **"17 Things The New YouTube Algorithm Loves (YouTube Automation Guide)"** — Romayroh · 3w ago · 33,107 views · 12:45 · Bias: Skool and tool affiliates — [Source](https://www.youtube.com/watch?v=FWE3fu_0Sfc)

### Inferences
- A sensible packaging sequence is Paddy Galloway for principles, then Isaac and DecodingYT for Shorts execution, then Build Your Tribe and Robert Benjamin for monthly Reels/TikTok algorithm changes.

### Gaps
- No primary-source (Meta/TikTok/YouTube official) algorithm explainer from 2026 was found in YouTube search; all algorithm videos are creator interpretations.

---

## Q6. Automation: n8n/Make faceless pipelines, Claude Code / Claude API / MCP pipelines, auto-posting

### Takeaway
In mid/late 2026 the automation tutorials have moved from n8n toward Claude Code plus MCP servers, especially the Higgsfield MCP, which is heavily promoted with affiliate links. The best n8n faceless-channel tutorials are 8–11 months old. Auto-posting is mostly taught with Blotato, in both n8n and Claude Code.

### Cited Findings
**Deep-verified**
- **"How I Make $24,937/mo Posting YouTube Shorts (Using Claude AI)"** — Kellan Henneberry · 3mo ago · 1,305,467 views · 12:44 — [Source](https://www.youtube.com/watch?v=V_t51u1tBJc) (about the first 12 of 12:44 minutes read from the transcript)
  - Claims: $24K in 28 days and about $250K over 365 days on one channel, plus one Short at 16.8M views earning about $3.2–3.8K at a $0.42 Shorts RPM.
  - Niche: "ranking" compilation Shorts. The workflow installs the free vidIQ Chrome extension to connect vidIQ to Claude.ai, then runs a "competitor breakdown" on an inspiration channel's ID and asks Claude for its best-performing topics.
  - Production: clips come from viral TikToks and are edited in viblo.ai (affiliate, 7-day trial). The video recommends 5–7 clips, a 2-line title with colored keywords, and a shuffled "custom playback order" for retention.
  - Posting: 1–2 Shorts every day without skipping.
  - Risk: the method reuses other creators' clips, which carries reused-content risk (see Q9).
- **"Build ANY Faceless YouTube Channel with Claude (Full Automation)"** — Zinho Automates · 1mo ago · 132,907 views · 15:58 · Bias: Higgsfield × Claude affiliate — [Source](https://www.youtube.com/watch?v=EChXCPolIDQ)
- **"I Fully Automated My Video Editing Using Claude Code (Full Walkthrough)"** — Christian Peverelli · 3d ago · 163,786 views · 16:59 · Teaches: a Claude Code editing pipeline (Tella, Hyperframes) · Bias: free editing skill via Skool — [Source](https://www.youtube.com/watch?v=HzXD4GVqXwM)
- **"Watch Me Make a Faceless YouTube Video With Claude Code"** — Make Money Matt · 4mo ago · 75,497 views · 17:35 · Bias: Higgsfield MCP affiliate — [Source](https://www.youtube.com/watch?v=Kgdms--LQ-g)
- **"Claude Code Just Changed YouTube Forever!"** — Danny Why · 4mo ago · 1,706,593 views · 9:22 · Bias: Higgsfield CLI affiliate — [Source](https://www.youtube.com/watch?v=WODnqHPLR38)
- **"I Used Higgsfield AI + Claude Fable 5 to Build a $39,500/Month Faceless Channel"** — Higgsfield AI · 3mo ago · 852,149 views · 14:22 · Bias: vendor — [Source](https://www.youtube.com/watch?v=wU_bmWb6bhg)
- **"Claude AI + YouTube = $10,401 In 30 Days"** — Leo Grundström Biz · 5d ago · 7,177 views · 21:00 · Bias: Higgsfield MCP affiliate — [Source](https://www.youtube.com/watch?v=99RVWGYJqnw)
- **"I Let Claude Opus 5.5 Run My Entire AI Video Project — Higgsfield MCP"** — James Tech AI · 12d ago · 26,966 views · 7:08 · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=U6iS83PNME4)
- **"How I Automated 30 Days of AI Influencer TikToks With One Prompt Using Claude and Higgsfield"** — Andy Lo · 4mo ago · 19,334 views · 12:41 — [Source](https://www.youtube.com/watch?v=B5zYOW6NXxM)
- **"Generate Content for 9 Socials on Autopilot with Claude Code"** — Nate Herk | AI Automation · 6mo ago · 53,628 views · 17:29 · Teaches: auto-posting · Bias: Blotato affiliate — [Source](https://www.youtube.com/watch?v=4Zaoo0YbYaw)
- **"Claude Code Runs My Social Media Now (Full Setup)"** — Zubair Trabzada · 7mo ago · 87,888 views · 24:08 · Bias: Blotato, Skool — [Source](https://www.youtube.com/watch?v=Fnw1_YAYEAc)
- **"These 7 Claude Automations Run My YouTube Channel on Autopilot (copy them)"** — Robert Benjamin · 4mo ago · 8,026 views · 13:47 · Bias: vidIQ affiliate — [Source](https://www.youtube.com/watch?v=z4Zu3uLRfVI)
- **"How I Automated Faceless Shorts with Claude + n8n (One Prompt | Full Template)"** — Krish Nagrani · 3w ago · 1,742 views · 16:39 · Bias: Gumroad affiliate templates — [Source](https://www.youtube.com/watch?v=d1h3Swh37KM)

**n8n (older but still the best n8n-specific)**
- **"I Used N8N to Automate a $10M/yr AI Influencer - Here's How (AI Influencer Toolkit Tutorial)"** — Jay E | RoboNuggets · 11mo ago · 109,468 views · 26:07 — [Source](https://www.youtube.com/watch?v=DqY797MuQio)
- **"Automating Faceless Shorts with AI for beginners (No Code)"** — Sabrina Ramonov · 8mo ago · 49,901 views · 37:54 · Bias: Blotato promo — [Source](https://www.youtube.com/watch?v=6bBWmnv8Q8o)
- **"How To Create YouTube Automation Videos With N8N & AI Agents"** — Zinho Automates · 10mo ago · 65,458 views · 13:59 · free template — [Source](https://www.youtube.com/watch?v=3qZtFv5ShUM)
- **"100% Automated Sora 2 Home Camera Shorts in n8n (Full Guide)"** — Koen | AI Content Systems · 11mo ago · 192,447 views · 26:38 · Bias: Skool, Blotato — [Source](https://www.youtube.com/watch?v=ci-1OnPMl3E)
- **"N8N Instagram Automation | Step-by-Step Guide (Free Template)"** — Rajeevdaz · 11mo ago · 96,115 views · 16:58 — [Source](https://www.youtube.com/watch?v=m02TeQ9kHVo)

### Inferences
- For a learner who already uses Claude Code with MCP tools, the most relevant current videos are Zinho Automates, Christian Peverelli and Make Money Matt. The n8n videos are best kept for scheduled, server-side jobs such as auto-posting.
- The Higgsfield MCP affiliate campaign means many "Claude automation" videos are partly ads, and creators' revenue claims (e.g. "$39,500/month") are unverified.

### Gaps
- No relevant 2026 **Make.com** faceless-automation tutorial with meaningful views was found.
- No tutorial was found that uses the Claude API directly (rather than Claude Code or claude.ai with MCP) for a content pipeline.

---

## Q7. Monetization: digital products (Whop, Skool, Gumroad, Stan Store), affiliate, brand deals, ManyChat funnels

### Takeaway
The most concrete AI-influencer monetization case studies come from DIGITAL INCOME PROJECT: grow an AI influencer on Instagram, then sell a Claude-built digital product automated with Zapier. Richard Yu and Nathan Nazareth have the strongest 2026 digital-product courses. ManyChat comment-to-DM funnels are covered well by ManyChat's official channel and Modern Millie. Aftab Khan's Hindi video covers brand deals: views alone don't win sponsors; you need trust and product/UGC content.

### Cited Findings
**Deep-verified**
- **"This instagram account is printing from digital products built with Claude"** — DIGITAL INCOME PROJECT · published 2026-09-24 · 77,806 views · 1,505 likes · 12:51 · Bias: Higgsfield affiliate, Zapier link, paid IG growth service — [Source](https://www.youtube.com/watch?v=h_KMRUYNThE)
  - Grew an AI influencer from scratch to more than 10K followers.
  - Built the landing page and app with Claude (Code) and automated delivery with Zapier.
  - Shares the prompts used and points to a real case study (Sarah / "hothighpriestess" and her app Stella).
- **"How to Create an AI Influencer That Actually Gets Brand Deals"** — Aftab Khan · published 2026-09-15 · 78,590 views · 17:33 · Hindi · Bias: Higgsfield affiliate — [Source](https://www.youtube.com/watch?v=vfuTJbF9HJo)
  - The chapter list includes "Why AI Avatars Don't Get Brand Deals", "Creating Product Content & Building Trust" and "The Actual Cost".

**Video list**
- **"I Tried Selling AI Digital Products on instagram to prove its NOT luck"** — DIGITAL INCOME PROJECT · 2mo ago · 101,153 views · 13:18 — [Source](https://www.youtube.com/watch?v=RZyl1XSVWI4)
- **"I Created a Viral AI influencer on instagram that got Monetized (Full Course)"** — DIGITAL INCOME PROJECT · 4mo ago · 191,276 views · 18:34 — [Source](https://www.youtube.com/watch?v=rF5OzmFlxq0)
- **"How to build & sell AI Digital Products (2026 full guide)"** — Nathan Nazareth · 1mo ago · 202,233 views · 21:34 · Bias: his program; Whop affiliate on the channel — [Source](https://www.youtube.com/watch?v=6cm2o8zzuNw)
- **"FULL COURSE: How to Build & Sell Digital Products With AI (Step by Step)"** — Richard Yu · 2mo ago · 162,224 views · 43:48 · Bias: Base44 affiliate — [Source](https://www.youtube.com/watch?v=gjffmgucDSw)
- **"How an AI Avatar Made $320,000 in 3 Months"** — Richard Yu · 4mo ago · 32,598 views · 14:10 — [Source](https://www.youtube.com/watch?v=9Q4yxEygG84)
- **"How To Sell Digital Products on Whop - Full Tutorial"** — Charlie Newnham · 11mo ago · 41,271 views · 24:48 · Bias: Whop affiliate (older) — [Source](https://www.youtube.com/watch?v=1AOVyMKS3Nk)
- **"Create Your First Manychat Automation (step-by-step tutorial)"** — Manychat (official) · 8mo ago · 454,068 views · 7:16 · Bias: vendor — [Source](https://www.youtube.com/watch?v=aGqK67lXw6M)
- **"How to Make Money on Social Media Using Automations (Complete Manychat Tutorial)"** — Modern Millie · 3mo ago · 11,979 views · 24:35 — [Source](https://www.youtube.com/watch?v=kzW0nBmkazQ)
- **"The Best Way to Use Manychat 2026 | Manychat Tutorial"** — Jade Beason · 3mo ago · 10,730 views · 13:42 — [Source](https://www.youtube.com/watch?v=9yosBXHB2wg)
- **"How to Make $120k/Year with An Army of AI Influencers"** — The Koerner Office · 8mo ago · 96,224 views · 13:52 · Bias: Higgsfield — [Source](https://www.youtube.com/watch?v=QIX0lnr3qfo)
- **"I Tried The LAZIEST Way to Make Money With AI"** — Mark Tilbury · 2w ago · 5,630,917 views · 33:19 · Bias: disclosed Higgsfield affiliate (code TILBURY) — [Source](https://www.youtube.com/watch?v=LlhTEttKcwQ)
- **"How to Launch an AI Influencer Business With Fanvue (Step-by-Step)"** — Blog With Ben · 2mo ago · 12,844 views · 12:20 · Bias: Fanvue affiliate — [Source](https://www.youtube.com/watch?v=DNAKnhyey10)

### Inferences
- Several AI-influencer monetization videos route to Fanvue, an adult-leaning subscription platform. For a brand-safe persona channel in Pakistan, the DIGITAL INCOME PROJECT digital-product route and the ManyChat funnel route are the relevant models.

### Gaps
- No strong, recent dedicated tutorials were found for **Skool**, **Stan Store** or **Gumroad** specifically for AI-persona pages. A combined Whop/Stan/ManyChat search returned only 2 off-topic results.

---

## Q8. Urdu/Hindi tutorials (AI avatar/influencer, faceless channels, automation, policy)

### Takeaway
There is good Urdu/Hindi coverage, much of it by Pakistani creators. It is strongest for n8n/automation (Kamran AI Insights, Badar Munir/Aaghaz), long-form AI story videos (Syed Yasir Abbas, Technical Bilal Jahangir) and YouTube AI-policy explainers (Technical Yogi, Manoj Dey). Hindi AI-influencer tutorials are recent and well viewed (Aftab Khan, Tech Plus AI, Hindi AI Gyaan).

### Cited Findings
**Deep-verified**
- **"n8n Masterclass 2026: AI Agents, RAG & How to Sell What You Build (Full Course)"** — Kamran AI Insights (Pakistan) · published 2026-08-19 · 89,138 views · 2,965 likes · 7:44:47 · free — [Source](https://www.youtube.com/watch?v=vamZqhpG3qI)
  - 11 classes covering agents vs chatbots, every trigger and node type, data flow, LLM parameters, vector DBs and a full RAG chatbot.
  - Part of a free 90-day "Agentic Pro" bootcamp that ends with Claude Code SaaS builds.
  - Bias: upsells a paid Pakistan program (Hustle Heroes).
- **"Make Instagram Ai Influencer that'll help you earn! (Full Masterclass)"** — Tech Plus AI · published 2026-09-21 · 157,145 views · 1,926 likes · 32:25 · Bias: sells an "AI bundle"; India-targeted (language not verified) — [Source](https://www.youtube.com/watch?v=ZyEBtFgkQfk)
  - Covers a character brief, a master reference image and the character in different environments.
  - Then turns it into talking videos with HeyGen, adds motion and cinematic B-roll in Google Flow, and ends with a monetization chapter.
- **"How to Create an AI Influencer That Actually Gets Brand Deals"** — Aftab Khan · Hindi (confirmed by watching with Gemini) · 2026-09-15 · 78,590 views — [Source](https://www.youtube.com/watch?v=vfuTJbF9HJo)

**Video list**
- **"Build & Sell n8n AI Agents & Automation (Full Detailed Course )"** — Make First Million - Badar Munir · 7mo ago · 619,090 views · 4:25:50 · Bias: Hostinger affiliate, Aaghaz upsell — [Source](https://www.youtube.com/watch?v=k4jKclPne9I)
- **"N8N Full Course: Building AI Agents in 2025 for Beginners! (Urdu/Hindi)"** — Aaghaz · 3mo ago · 1,237 views · 1:12:11 — [Source](https://www.youtube.com/watch?v=9KbSxXu1zlk)
- **"Learn n8n From ZERO 🔥 | Build Your First AI Automation (Hindi/Urdu)"** — Ali Builds Ai · 1mo ago · 796 views · 19:23 — [Source](https://www.youtube.com/watch?v=2OtS9tPu4-Q)
- **"Learn YouTube Automation From Zero to Advanced — Full 9+ Hour Course"** — Muhammad Nazeer · 12d ago · 2,512 views · 9:10:29 (language not verified) — [Source](https://www.youtube.com/watch?v=wUSCZ7YSgzY)
- **"How I Make Dollars with Viral Revenge Stories Channel Step-by-Step | YouTube Automation with AI 2026"** — Automation with Huzaifa YT · 13d ago · 30,783 views · 49:18 — [Source](https://www.youtube.com/watch?v=hyiuHvdc0-4)
- **"Long AI Video Kaise Banaye (15 Min) Using Just 1 Prompt🔥"** — Syed Yasir Abbas · 3w ago · 186,094 views · 11:24 · Bias: HitPaw VikPea sponsor — [Source](https://www.youtube.com/watch?v=E9RlJeGjWs4)
- **"How to Create Long AI Videos for FREE in 2026✅ | Free Text to Video AI Tool"** — Technical Bilal Jahangir · 12d ago · 147,914 views · 16:05 — [Source](https://www.youtube.com/watch?v=peJYFhptBSc)
- **"How To Clone Any AI Influencer Video with Just ONE Prompt 🤯"** — Hindi AI Gyaan · 2w ago · 76,840 views · 6:55 — [Source](https://www.youtube.com/watch?v=q2zSJGKy19A)
- **"Make Ultra Realistic Talking AI Avatars for FREE 🤯 | Perfect Lip Sync"** — Hindi AI Gyaan · 2mo ago · 94,259 views · 11:59 · Bias: Filmora sponsor — [Source](https://www.youtube.com/watch?v=6qnCUZeXPjg)
- **"AI Se Realistic Talking Avatar Kaise Banayein? Step by Step Tutorial 🔥"** — niqabi shagufta · 2w ago · 13,644 views · 13:12 · Teaches: a Google Flow talking avatar (Urdu-style narration, starts "Assalamu Alaikum") — [Source](https://www.youtube.com/watch?v=wv2t2vwO910)
- **"How to Create AI Influencer Business System | Full Guide"** — Lets Uncover (uses a letsuncover.pk domain) · 3mo ago · 13,044 views · 14:07 · Bias: Higgsfield MCP affiliate; language not verified — [Source](https://www.youtube.com/watch?v=hpEwFI98REg)
- **"5 EASY AI Faceless YouTube Channel Ideas for 2026 ( Fast Monetization)"** — Skillsiya · 2w ago · 39,075 views · 9:33 — [Source](https://www.youtube.com/watch?v=2zsU1ojzJAk)
- **"AI Generated Videos Monetization Rules 2026 | YouTube's New AI Content Policy & Monetization"** — Technical Yogi (Hindi) · 1mo ago · 207,481 views · 4:54 — [Source](https://www.youtube.com/watch?v=uJO7Nlh1_Dk)
- **"YouTube InAUTHENTIC Content Rule 2026 | Channel De-Monetise | अच्छे से समझ लो 😱"** — Manoj Dey (Hindi) · 5mo ago · 175,841 views · 7:24 — [Source](https://www.youtube.com/watch?v=WYwYpiP4DcY)
- **"Why AI Channels Get Demonetized | YouTube Monetization Policy 2026"** — Syed Yasir Abbas · 1mo ago · 12,788 views · 21:26 — [Source](https://www.youtube.com/watch?v=sdlxWuVhUTI)
- **"AI Story Channels in Danger? YouTube Is Demonetizing AI Story Channels?😱 3 BIG Mistakes to Avoid!"** — C For Concept · 2w ago · 63,894 views · 10:30 — [Source](https://www.youtube.com/watch?v=PKjmZQRIYus)
- **"My 2 AI Channels Got Demonetized 😢 | Inauthentic Content Reason + Real Solution"** — Blackflash · 6mo ago · 31,767 views · 4:31 · Teaches: a first-hand case of AI baby-content channels ("Baby Masti", "Mini Masti") being demonetized — [Source](https://www.youtube.com/watch?v=4TH07JYZKik)

### Inferences
- A Pakistani learner who writes Roman Urdu could start with Kamran AI Insights (n8n), Syed Yasir Abbas (AI video plus the policy video) and Aftab Khan (AI influencer brand deals, Hindi but easy to follow for Urdu speakers).

### Gaps
- Spoken language (Urdu vs Hindi vs English) was confirmed only for Aftab Khan (Hindi) and inferred for Kamran AI Insights (Pakistan-targeted description). The others are inferred from titles and descriptions; the watch tool's daily limit blocked further checks.
- No Urdu tutorial was found specifically on Claude Code / MCP content pipelines.

---

## Q9. YouTube policy on AI content / avoiding demonetization (inauthentic content) explained

### Takeaway
YouTube's own Creator Insider interview (2026-07-16) with VP of Trust & Safety Matt Halprin is the primary source. It splits "inauthentic content" into three YPP buckets and says YouTube is agnostic about which tool you use. vidIQ's transcript-verified video turns this into four practical defenses: a custom or cloned voice, a human channel trailer, editorial "taste", and an empty-square niche.

### Cited Findings
- **"YouTube's Inauthentic Content Policy - Explained!"** — Creator Insider (YouTube's official creator channel; Rene Ritchie with VP of Trust & Safety Matt Halprin) · published 2026-07-16 · 46,406 views · 1,958 likes · 10:13 — [Source](https://www.youtube.com/watch?v=14Vm0CiyUVE) (verified from the description and chapter list)
  - The three buckets are: (1) generic, repetitive or template-based content; (2) unsatisfying, off-putting, distressing or emotionally manipulative uploads; (3) AI personas discussing sensitive topics like health and finance.
  - Chapters also cover "Why YouTube is agnostic to tools: GenAI vs traditional creation", "The wrong tutorials to follow for monetization" and "Debunking the mass-flagging myth".
  - Appeals: a 21-day appeal window, and you can reapply after 90 days with fresh content.
- **"How to Build a Faceless Channel YouTube Won't Demonetize"** — vidIQ · 1mo ago · 151,349 views · 12:37 · Bias: vendor, demos vidIQ voice cloning — [Source](https://www.youtube.com/watch?v=d_csri5M9xw) (full transcript read)
  - Timeline and claims:
    - YouTube added "inauthentic content" to its monetization policy in July 2025.
    - In January 2026 YouTube's CEO publicly acknowledged "AI slop".
    - In the purge that followed, "16 of the biggest AI channels" were removed, totaling about 35M subscribers and about 5B views.
  - Fixes: replace stock AI voices with a cloned or custom voice; add a short human trailer (it can be unlisted) so the channel is "99.99% faceless"; research beyond Wikipedia, tell the story through a fresh lens and take a side; and slide a proven format into an untouched topic.
- **"New YouTube Monetization Update: Inauthentic Content Has Gone!"** — vidIQ · 2mo ago · 99,067 views · 10:09 — [Source](https://www.youtube.com/watch?v=JvZ0MXl70fc)
- **"YouTube Is Killing Faceless Channels"** — vidIQ · 2mo ago · 147,044 views · 10:50 — [Source](https://www.youtube.com/watch?v=oQVLxVuCa6Y)
- **"YouTube Employee: THIS is What Gets You Demonetized"** — vidIQ · 6mo ago · 66,855 views · 10:36 — [Source](https://www.youtube.com/watch?v=yfOvhJI7YcU)
- **"YouTube Just Made It Easier to Get Demonetized"** — TubeBuddy · 2mo ago · 20,484 views · 3:18 — [Source](https://www.youtube.com/watch?v=QZEh7dOJwJQ)
- **"Why AI STORY Channels Keep Getting Demonetized"** — Natalie Fong · 4mo ago · 120,830 views · 11:13 · Bias: risk-quiz product — [Source](https://www.youtube.com/watch?v=QxZR0gOC-dg)
- **"AI Channels Are Getting Demonetized Again, Here's How to Avoid It (2026)"** — Eddie Eizner · 7mo ago · 74,244 views · 25:36 · Teaches: "AI is not the filter YouTube is using" — [Source](https://www.youtube.com/watch?v=8UW7TNr2S5A)
- **"YouTube ENDS Faceless AI Channels? Here's What's Still Safe"** — The Zinny Studio · 5mo ago · 49,904 views · 22:27 — [Source](https://www.youtube.com/watch?v=hzn249szSTc)
- Hindi/Urdu policy explainers (Technical Yogi, Manoj Dey, Syed Yasir Abbas, Blackflash) are listed in Q8.

### Inferences
- Bucket 3 ("AI personas discussing sensitive topics like health and finance") applies directly to AI-avatar channels. An AI persona giving health or finance advice is a specific monetization risk.
- Reused-clip methods such as Kellan Henneberry's ranking Shorts (Q6) and "clone a viral channel" tutorials are the kind of content these policies target. Learners should treat them as format inspiration, not something to copy.

### Gaps
- I could not fetch YouTube's policy page (support.google.com is blocked by the proxy), so the policy wording rests on the Creator Insider video description, not the help-center text.
- vidIQ's "16 channels / 35M subs / 5B views" purge figures were not independently verified.

---

## Q10. Courses, playlists and official academies

### Takeaway
Free official learning paths exist for HeyGen (HeyGen Academy), n8n (docs.n8n.io learning path with Beginner and Advanced video courses) and Claude (Anthropic Academy on Skilljar). Higgsfield Academy is reported as a free AI-filmmaking school, but I could not confirm it has an AI-influencer course.

### Cited Findings
- **HeyGen Academy** is official and built into the platform. It goes from beginner (dashboard, ways to start a video, avatars, voices) to advanced features — [HeyGen Academy](https://community.heygen.com/en/public/resources/heygen-academy-your-hub-for-in-depth-video-tutorials); [HeyGen blog on free course](https://www.heygen.com/blog/free-heygen-course-community-guide)
- HeyGen's YouTube channel also has a live **"Beginner workshop: Create your first video with Avatar V and the Video Agent"** (1:02:56, streamed 3w ago) and a 58:55 **"HeyGen Avatar V — Complete Feature Walkthrough"** — [Workshop](https://www.youtube.com/watch?v=PeIYBJT-5xk); [Walkthrough](https://www.youtube.com/watch?v=G2auhfoA2os)
- **n8n official learning path:** two YouTube video courses. The Beginner course covers workflows, APIs/webhooks, nodes, data, error handling, debugging and collaboration. The Advanced course covers complex flows, sub-workflows, error workflows, files and enterprise. Text courses add community badges — [n8n Learning path](https://docs.n8n.io/learning-path); [n8n video courses](https://docs.n8n.io/video-courses/)
- **Anthropic Academy** (anthropic.skilljar.com) is free, with certificates. Courses include Claude Code 101, Claude Code in Action, Introduction to subagents, API and MCP courses. One source says 13 courses at launch, another 17 after an April 2026 update. These are secondary sources, not Anthropic's own pages — [pasqualepillitteri.it](https://pasqualepillitteri.it/en/news/371/anthropic-academy-free-courses-claude); [Stephen Turner blog](https://blog.stephenturner.us/p/free-claude-courses-from-anthropic)
- **Higgsfield Academy** is described as a free AI film school from the team behind the AI film "Hell Grind". Its flagship course is "The AI Filmmaking Pipeline" (Think, Set Up, Generate, Test), and it uses an @loc/@char/@prop asset-naming system. This comes from community posts and a TheWrap article; TheWrap and higgsfield.ai were blocked, so this is from search snippets only — [Skool post](https://www.skool.com/operatormode); [TheWrap (not fetched)](https://www.thewrap.com/creative-content/movies/create-ai-movies-for-free-higgsfield-academy/)
- **Paid or free creator programs mentioned in the verified videos:**
  - Paddy Galloway Accelerator (paid) — [Source](https://www.youtube.com/watch?v=Z2uoA3bhJT0)
  - Kamran AI Insights "Agentic Pro" 90-day free bootcamp, plus paid Hustle Heroes for Pakistan — [Source](https://www.youtube.com/watch?v=vamZqhpG3qI)
  - 1of10 Ideation Masterclass (free YouTube, 1:12:23) — [Source](https://www.youtube.com/watch?v=Bxch8wSzEkc)
  - Badar Munir's Aaghaz AI Institute (Pakistan, paid) — [Source](https://www.youtube.com/watch?v=k4jKclPne9I)

### Inferences
- Learning stages:
  1. **Foundations:** policy first (Creator Insider + vidIQ, Q9), then niche research (Leo Grundström + vidIQ "empty square", Q4).
  2. **Persona build:** consistent character (Creating with Conor / Mariana Montoya / Isa, Q1), then talking avatar and lip-sync (HeyGen Academy or Higgsfield + ElevenLabs, Q2), then a viral format breakdown (Roboverse / Money Degree, Q3).
  3. **Packaging:** Paddy Galloway, then Isaac, then DecodingYT (Q5).
  4. **Scale:** Claude Code / MCP pipelines (Zinho, Peverelli) plus the n8n fundamentals courses (Kamran, n8n official, Q6/Q8).
  5. **Monetize:** DIGITAL INCOME PROJECT, Richard Yu / Nathan Nazareth, then ManyChat (Q7).
- Anthropic Academy's Claude Code courses suit a learner already using Claude Code and MCP. They are free and do not push a third-party tool, unlike most YouTube automation tutorials.

### Gaps
- I could not confirm whether HeyGen Academy is fully free or which Higgsfield Academy courses exist today; both official sites were blocked or not shown in search.
- No official Google/YouTube "AI creator" course for 2026 was found.
- Watch-tool verification was capped at 2 videos (the daily 5-call LITE limit, partly used before this task). I verified four other videos from transcripts and descriptions instead.
