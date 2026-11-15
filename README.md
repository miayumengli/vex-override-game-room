# VEX V5RC Override — YouTube research

Research into YouTube coverage of the **Override** season (V5RC 2026–2027): robot design,
skills runs and competition footage published **since 1 August 2026**. Data collected
14 November 2026.

> The season is called **Override**, not "Overrider".

## Files

| File | What it is |
|---|---|
| `override-war-room.html` | **VEX/RECF 2026-2027 War Room — Override/Pinnacle** — the full write-up as a standalone page. Three tabbed views: the season 50, the recent 20, and the channels. Each list has a summary per video; the season view also carries trends, an events table and the below-cut sections. Open it in a browser. |
| `videos-top50.csv` | The ranked 50 since 1 Aug: rank, title, channel, category, publish date, duration, views, URL. |
| `videos-top20-last30days.csv` | The ranked 20 published 14 Oct – 14 Nov 2026, same columns (22 rows: the top 20 plus the two just outside). |
| `videos-below-cut.csv` | Ranks 51–68 in the August window, plus five videos deliberately excluded (with the reason). |

The same page is published as a private Claude artifact:
<https://claude.ai/artifact/EZVjNUpmo4mrGsb4bcfKNE>

`override-war-room.html` in this folder is the **source of truth** for that artifact.
Edit it here and republish to the URL above; the artifact keeps the same link across
versions. Do not keep a second copy elsewhere.

## How the list was built

1. Candidates gathered from YouTube searches across reveal, pits-and-parts, finals, skills
   and analysis queries, sorted by view count.
2. For every candidate, the **exact** publish date, duration and view count were read from
   the video's own page rather than from YouTube's rounded search labels ("3 mo ago").
3. Two windows, same method:
   - **Season list** — 68 videos published on or after 1 Aug 2026 screened, top 50 ranked.
   - **Last 30 days** — 130 videos published 14 Oct – 14 Nov 2026 screened, top 20 ranked.

The two lists do not overlap: the newest video in the fifty published 13 October.

That third step matters: four popular videos that YouTube listed as "3 mo ago" actually
published in late July and are therefore outside the window. They are in
`videos-below-cut.csv` marked `excluded - before Aug 2026`.

## Category breakdown of the 50

| Category | Count | What it means |
|---|---|---|
| `reveal` | 24 | 35–100 second team robot reveals |
| `match` | 9 | Elimination and qualification footage |
| `build` | 8 | Pit walkthroughs and build explanations |
| `analysis` | 5 | Design/strategy breakdowns and winner interviews |
| `skills` | 4 | Driver and autonomous skills runs |

## What changed in the last 30 days

The composition flipped. Reveals are 24 of the 50 across the season — nearly half — but
**none** of the top 10 in the last month, and only 5 of the top 20, all from rank 11 down.

Category split, last 30 days (top 20): build 5, reveal 5, skills 4, analysis 4, match 2.

What rose instead:

- **Mechanism explainers.** Joseph973 took two of the top 10 (ratcheting claw at #1 with
  18,480 views, cascade elevator at #9) by teaching one mechanism at a time with linked
  reference photos. Nothing like this appears in the season top 50.
- **Skills runs.** Four of the twenty, including 66799T matching the 256-point world record
  on 25 Oct and 1698z at 236.
- **Match analysis over match footage.** Luke does robotics holds #3 and #8; the latter
  breaks down a 156–165 local final, the highest-scoring match of the season so far. Only
  two of the twenty are raw match footage.
- **Cascades are the story of the month.** 33344C Catastrophe and 2394V Formula 5 each got
  an analysis video *and* a builder-side explanation (#10 + #18, #11 + #17). Watching each
  pair back to back is the best design study in either list.

Read together: the season list is a record of what teams built, and the last-30-days list is
a record of what the community is now trying to learn.

## Findings (season list)

- **The double reverse four-bar is the dominant lift.** Cascade elevators and differential
  lifts are the live alternatives. 16610A's differential elevator (rank 1) set the early
  template.
- **The skills ceiling doubled in eight weeks** — 128 pts (18 Aug) → 226 (22 Sep) →
  256 world record (12 Oct, 8737M ROKKR at Smoky Mountain Forge).
- **Strategy beat mechanism in September.** The top analysis video (rank 12) argues that
  fighting for toggles loses, and that swapping roles with your alliance partner matters
  more than any single mechanism. 471B won the Speedway signature playing that way.
- **Build tutorials are scarce.** Exactly one video in the 50 teaches a mechanism step by
  step (rank 36, 1069A's optical-sensor roller). Design knowledge is moving through pit
  interviews instead.
- **Best single source for design depth:** FUN Robotics Network's *Pits & Parts* series,
  which holds six of the 50 and covers the robots that go on to win signature events.
- **Deepest single build video:** 11811A's 30-minute MOA robot explanation (rank 49).
- **Rare concrete numbers:** 3946E stated their power budget in their reveal (rank 43) —
  55W drive, 22W lift, 11W intake.

## Channels worth following

Entry counts are across both ranked lists; subscriber figures from 14 Nov 2026.

| Channel | Entries | Subscribers | What they do |
|---|---|---|---|
| [FUN Robotics Network](https://www.youtube.com/@FUNRoboticsNetwork) | 7 | 48.4K | *Pits & Parts* — pit walkthroughs of top robots, explained by their builders |
| [Luke does robotics](https://www.youtube.com/@lukedoesrobotics) | 4 | 16.9K | Strategy and match analysis, usually via interviews with teams who just won |
| [The VEX Analyst](https://www.youtube.com/@TheVEXAnalyst) | 4 | 1.58K | Design reviews of individual robots; running coverage of the meta |
| [Joseph973](https://www.youtube.com/@Joseph973) | 2 | 4.92K | One mechanism per video, close up, with linked reference photos |

## Events in the window

| Event | When | Winning alliance |
|---|---|---|
| Mall of America Signature (UND) | 8–9 Aug | 10102A & 1028A |
| Silk Road Link, Changji | early Sep | — |
| Speedway Signature, Indiana | 18–20 Sep | 3946E & 471B |
| The Highlander Summit, Newark | 27 Sep | 12125A & 96Z |
| Great Planes Signature, Nebraska | 2–3 Oct | 1069A & 5813R |
| Smoky Mountain Forge | mid-Oct | skills world record set here |

Teams recurring across reveals, pit interviews and eliminations: 471B, 3946E, 10102A,
1028A, 16610A, 10B, 2393S, 8682A, 1239E, 66799T, 20850Z, 8737M.

## Caveats

- View counts are a snapshot from 14 Nov 2026 and keep moving, so the order near the cut
  line (rank 50 at 6,215 vs rank 51 at 6,164) will drift.
- Summaries come from each video's own title, description and chapter list. Where a team
  posted no description, the summary says only what the title and series format establish.
- **Scope vs. title.** The page is titled "VEX/RECF 2026-2027 War Room — Override/Pinnacle",
  but the searches behind it targeted Override. RECF Pinnacle appears only where a team said so
  themselves — 23851C and 31218W in their reveals, 11811A in its robot explanation. No
  Pinnacle-specific sweep has been run, so Pinnacle coverage here is incidental, not
  systematic. Worth a dedicated pass if Pinnacle matters as much as Override.
- The VEX World Championship 2027 location reveal falls inside the window and outdraws
  everything here at 959K views, but it is a venue announcement rather than design, skills
  or competition footage, so it is excluded from the ranking.
