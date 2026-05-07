# Product Metrics Overview

This page is an evergreen reference and monthly snapshot for understanding whether Cross Benefits product experiences are healthy, useful, and improving. It is intentionally lightweight: the goal is to identify notable shifts that may need investigation.

# Monthly summary

**Reporting period:** April 2026

**Overall read**

April 2026: 4 improved, 1 declined, 1 held roughly steady.

Still TBD: Reliability health check.


**Notable positive movement**

Evidence request response / completion rate — mobile (+4.8 pts, +30.2%)

CST usage — mobile (+65,837 monthly active users, +12.5%)

CSAT positive rating — CST, web (+4.9 pts, +7.5%)


**Notable negative movement**

Evidence request response / completion rate — web (-2.8 pts, -11.5%)


# Monthly scorecard

| Question | Primary metric | Latest month | Previous month | Month-over-month change | Source |
| --- | --- | --- | --- | --- | --- |
| Are Veterans reaching CST? | CST usage — web | **511,698 monthly active users**<br>3.16% of total users<br>Apr 2026 | **520,523 monthly active users**<br>3.12% of total users<br>Mar 2026 | **-8,825 monthly active users**<br>-1.7% | CST analytics / GA |
| Are Veterans reaching CST? | CST usage — mobile | **591,076 monthly active users**<br>33.02% of total users<br>Apr 2026 | **525,239 monthly active users**<br>28.89% of total users<br>Mar 2026 | **+65,837 monthly active users**<br>+12.5% | Mobile app analytics |
| Are communications driving action? | Decision letter email click-through rate | **58.36%**<br>April 2026 | **56.02%**<br>March 2026 | **+2.3 pts**<br>+4.2% | Comms team weekly export (SharePoint Excel) |
| Are Veterans completing key follow-up actions? | Evidence request response / completion rate — web | **21.65%**<br>April 2026 | **24.45%**<br>March 2026 | **-2.8 pts**<br>-11.5% | CST evidence request dashboard |
| Are Veterans completing key follow-up actions? | Evidence request response / completion rate — mobile | **20.71%**<br>April 2026 | **15.91%**<br>March 2026 | **+4.8 pts**<br>+30.2% | VA mobile evidence requests |
| Does CST build trust? | CSAT positive rating — CST, web | **70.4%**<br>Apr 2026 | **65.5%**<br>Mar 2026 | **+4.9 pts**<br>+7.5% | CSAT report dashboard |
| Is the experience technically healthy? | Reliability health check | TBD | TBD | TBD | RUM / Datadog |

# Investigation notes

Use this section only when a scorecard metric moves enough to need explanation.

No notable shifts this month.

# Quarterly / deeper-dive metrics

These metrics are useful, but they do not need to be pulled every month unless the Summary or scorecard points to a reason to investigate.

| Area | Metric / analysis | Why it matters | Metric | Source |
| --- | --- | --- | --- | --- |
| Claim letters | Claim letter downloads by letter type and device | Helps understand which communications drive document access and follow-through. |  | Julie's CST dashboard / GA |
| Benefit letters | Benefits letter downloads by letter type and device | Helps understand demand for letters and documents beyond claim status. |  | GA benefits letters dashboard / mobile app analytics |
| Communications | Decision letter email delivery success rate | Confirms whether email delivery is healthy before interpreting click-through. |  | DOMO / SharePoint Excel sheet |
| Communications | Mobile app push notification engagement | Helps understand whether mobile notifications are being noticed and acted on. |  | SharePoint Excel |
| Reliability | RUM performance indicators, backend errors, upload success, cumulative layout shift | Helps explain whether technical health is affecting user behavior or trust. |  | RUM / Datadog |
| Claim types & audiences | Claim volume by type, channel, and claimant type | Helps identify coverage gaps and prioritization opportunities. |  | DOMO / GA / claims data |
| Trust | CSAT negative rating and response count | Provides context for the primary CSAT positive rating. |  | CSAT report dashboard |
| Veteran pain points | Top pain points, shipped improvements, and adoption of related features | Connects product delivery to known Veteran pain points. |  | Research / Medallia / roadmap / release notes |

# Appendix: historical scorecard

Running list of values per scorecard metric. Add new rows by rolling over each month.

## CST usage — web

| Period | Monthly active users | Share | MoM change |
| --- | --- | --- | --- |
| Jan 2026 | 497,845 | 3.05% | — |
| Feb 2026 | 502,310 | 3.08% | +4,465 monthly active users (+0.9%) |
| Mar 2026 | 520,523 | 3.12% | +18,213 monthly active users (+3.6%) |
| **Apr 2026** (latest) | 511,698 | 3.16% | -8,825 monthly active users (-1.7%) |

## CST usage — mobile

| Period | Monthly active users | Share | MoM change |
| --- | --- | --- | --- |
| Jan 2026 | 498,102 | 27.45% | — |
| Feb 2026 | 510,887 | 28.10% | +12,785 monthly active users (+2.6%) |
| Mar 2026 | 525,239 | 28.89% | +14,352 monthly active users (+2.8%) |
| **Apr 2026** (latest) | 591,076 | 33.02% | +65,837 monthly active users (+12.5%) |

## Decision letter email click-through rate

| Period | Value | MoM change |
| --- | --- | --- |
| Mar 2026 | 55.64% | — |
| March 2026 | 56.02% | +0.4 pts (+0.7%) |
| **April 2026** (latest) | 58.36% | +2.3 pts (+4.2%) |

### Weekly breakdown — March 2026

| Week | Clicks | Delivered | Click rate |
| --- | --- | --- | --- |
| 2/23/2026 – 3/1/2026 | 53,843 | 97,192 | 55.4% |
| 3/2/2026 – 3/8/2026 | 54,603 | 98,132 | 55.64% |
| 3/9/2026 – 3/15/2026 | 54,358 | 98,332 | 55.28% |
| 3/16/2026 – 3/22/2026 | 54,308 | 94,706 | 57.34% |
| 3/23/2026 – 3/29/2026 | 58,915 | 104,328 | 56.47% |
| **Total** | **276,027** | **492,690** | **56.02%** |

### Weekly breakdown — April 2026

| Week | Clicks | Delivered | Click rate |
| --- | --- | --- | --- |
| 3/30/2026 – 4/5/2026 | 59,265 | 97,240 | 60.95% |
| 4/6/2026 – 4/12/2026 | 56,845 | 94,584 | 60.1% |
| 4/13/2026 – 4/19/2026 | 57,902 | 99,575 | 58.15% |
| 4/20/2026 – 4/26/2026 | 54,308 | 99,809 | 54.41% |
| **Total** | **228,320** | **391,208** | **58.36%** |

## Evidence request response / completion rate — web

| Period | Value | MoM change |
| --- | --- | --- |
| March 2026 | 24.45% | — |
| **April 2026** (latest) | 21.65% | -2.8 pts (-11.5%) |

## Evidence request response / completion rate — mobile

| Period | Value | MoM change |
| --- | --- | --- |
| March 2026 | 15.91% | — |
| **April 2026** (latest) | 20.71% | +4.8 pts (+30.2%) |

## CSAT positive rating — CST, web

| Period | Value | MoM change |
| --- | --- | --- |
| Jan 2026 | 64.8% | — |
| Feb 2026 | 67.2% | +2.4 pts (+3.7%) |
| Mar 2026 | 65.5% | -1.7 pts (-2.5%) |
| **Apr 2026** (latest) | 70.4% | +4.9 pts (+7.5%) |
