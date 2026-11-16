# Search strategies and information sources

The authors' original contributions are available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); any third-party material remains subject to its own rights.

The searches, settings, and coverage below are based on retained search records. Times are UTC where shown.

### OpenAlex and ERIC

The primary search refresh was conducted on 22 October 2026 through the OpenAlex works API (`https://api.openalex.org/works`) and the public ERIC API (`https://api.ies.ed.gov/eric/`). OpenAlex used the recorded language filter `language:en`, `corpus:all` and a page size of 100. The ERIC expressions include the recorded `language:English` filter; requests used a page size of 200. OpenAlex expressions were submitted using `search.title_and_abstract.exact`; ERIC expressions were submitted using `search`. The query expressions below reproduce the recorded text.

#### ERIC 1

```text
(("agile coach" OR "agile coaches" OR "agile coaching" OR "scrum master" OR "scrum masters" OR scrummaster OR scrummasters OR "team mentoring" OR "team mentor" OR "team mentors" OR "mentoring teams")) AND language:English
```

#### ERIC 2

```text
((coach OR coaches OR coaching OR mentor OR mentors OR mentoring OR facilitator OR facilitators OR advisor OR advisors OR adviser OR advisers OR advising) AND ("product development" OR "product design" OR "new product" OR "new products" OR "service development" OR "service design" OR ("software development" OR "software engineering" OR "software project" OR "software projects" OR "software team" OR "software teams" OR "software design" OR "agile software") OR prototype OR prototypes OR prototyping OR "engineering design" OR "design project" OR "design projects" OR "design team" OR "design teams" OR "design studio" OR "design studios" OR "game design") AND (team OR teams OR collaborative OR collaboration OR workgroup OR workgroups OR practicum OR practicums OR studio OR studios OR capstone)) AND language:English
```

#### ERIC 3

```text
(((("team support" OR "supporting teams" OR "support for teams" OR "support of teams" OR "team development") AND (practitioner OR practitioners OR coach OR coaches OR mentor OR mentors OR facilitator OR facilitators OR manager OR managers OR supervisor OR supervisors OR leader OR leaders OR consultant OR consultants)) OR ((team OR teams OR workgroup OR workgroups) AND (multisource OR "external support" OR "internal support" OR "managerial support" OR "supervisory support"))) AND ("product development" OR "product design" OR "new product" OR "new products" OR "service development" OR "service design" OR software OR prototype OR prototypes OR prototyping OR "engineering design" OR "design project" OR "design projects" OR "design team" OR "design teams" OR "design studio" OR "design studios" OR "game design")) AND language:English
```

#### ERIC 4

```text
((("design facilitation" OR "design facilitator" OR "design facilitators") OR ((facilitating OR facilitation) AND ("design thinking" OR "co-design" OR codesign OR "co design" OR "product design" OR "service design" OR "design project" OR "design projects")) OR (("design based learning" OR "design-based learning") AND (coach OR coaches OR coaching)))) AND language:English
```

#### OpenAlex 1

```text
("agile coach" OR "agile coaches" OR "agile coaching" OR "scrum master" OR "scrum masters" OR scrummaster OR scrummasters OR "team mentoring" OR "team mentor" OR "team mentors" OR "mentoring teams")
```

#### OpenAlex 2

```text
(coach OR coaches OR coaching OR mentor OR mentors OR mentoring OR facilitator OR facilitators OR advisor OR advisors OR adviser OR advisers OR advising) AND ("product development" OR "product design" OR "new product" OR "new products" OR "service development" OR "service design" OR ("software development" OR "software engineering" OR "software project" OR "software projects" OR "software team" OR "software teams" OR "software design" OR "agile software") OR prototype OR prototypes OR prototyping OR "engineering design" OR "design project" OR "design projects" OR "design team" OR "design teams" OR "design studio" OR "design studios" OR "game design") AND (team OR teams OR collaborative OR collaboration OR workgroup OR workgroups OR practicum OR practicums OR studio OR studios OR capstone)
```

#### OpenAlex 3

```text
((("team support" OR "supporting teams" OR "support for teams" OR "support of teams" OR "team development") AND (practitioner OR practitioners OR coach OR coaches OR mentor OR mentors OR facilitator OR facilitators OR manager OR managers OR supervisor OR supervisors OR leader OR leaders OR consultant OR consultants)) OR ((team OR teams OR workgroup OR workgroups) AND (multisource OR "external support" OR "internal support" OR "managerial support" OR "supervisory support"))) AND ("product development" OR "product design" OR "new product" OR "new products" OR "service development" OR "service design" OR software OR prototype OR prototypes OR prototyping OR "engineering design" OR "design project" OR "design projects" OR "design team" OR "design teams" OR "design studio" OR "design studios" OR "game design")
```

#### OpenAlex 4

```text
(("design facilitation" OR "design facilitator" OR "design facilitators") OR ((facilitating OR facilitation) AND ("design thinking" OR "co-design" OR codesign OR "co design" OR "product design" OR "service design" OR "design project" OR "design projects")) OR (("design based learning" OR "design-based learning") AND (coach OR coaches OR coaching)))
```

#### Identifiers observed in the primary refresh

The saved successful responses were parsed for provider-native identifiers. Repeated observations mean the same provider ID appeared more than once in the saved results; they are not a count of duplicate reports or studies. The summed distinct IDs remain separate by provider, and no cross-provider report deduplication is implied.

| Source | Result observations | Distinct provider IDs | Repeated observations |
| --- | ---: | ---: | ---: |
| ERIC | 355 | 351 | 4 |
| OpenAlex | 10213 | 9966 | 247 |

These historical observations do not establish a deduplicated report count, the subsequent screening sequence or final eligibility.

### Google Scholar

The Google Scholar search used SerpApi from 2026-11-01T06:04:25.562938Z to 2026-11-01T06:28:48.201284Z (UTC), with 8 general expressions, a 200-position bound per expression, English-language results, and citations and patents excluded. Of 107 attempts, 80 saved a full 20-result response, giving 1600 displayed observations. Across attempts, 80 of 80 planned query-and-start coordinates had a full response. The responses include retries and do not constitute one contemporaneous ranking; displayed observations are not independent reports or eligibility decisions. Previously identified records were also assessed.

For the 1 November search, the saved fixed parameters echoed by each successful response were `{"engine":"google_scholar","hl":"en","lr":"lang_en","num":"20","filter":"1","scisbd":"0","as_sdt":"0","as_vis":"1","as_rr":"0"}`.
The request implementation specifies `no_cache=true` and `output=json`; those two settings were not among the fixed parameters echoed in the saved responses.

The eight recorded search expressions were:

#### SUP-Q01

```text
"team coaching"
```

#### SUP-Q02

```text
"team mentoring"
```

#### SUP-Q03

```text
"agile coaching"
```

#### SUP-Q04

```text
"scrum master"
```

#### SUP-Q05

```text
"design facilitation"
```

#### SUP-Q06

```text
"group facilitation"
```

#### SUP-Q07

```text
"team support"
```

#### SUP-Q08

```text
"enabling leadership"
```

### Consensus

Consensus was queried in pro mode using four expressions and a bound of 20 positions per initial response. The saved records contain 80 positions and 78 distinct provider identifiers, not independent studies or a complete index search. Times below are recorded request start and completion times (UTC).

| Query | Expression | Started (UTC) | Completed (UTC) |
| --- | --- | --- | --- |
| Consensus 1 | `"agile coach" "scrum master" software development teams` | 2026-10-20T14:55:35.120Z | 2026-10-20T14:55:37.747Z |
| Consensus 2 | `facilitation support product development design teams practitioner perceptions` | 2026-10-20T14:55:37.944Z | 2026-10-20T14:55:40.738Z |
| Consensus 3 | `manager support facilitation product development teams collaboration learning adaptation` | 2026-10-20T14:55:40.901Z | 2026-10-20T14:55:43.844Z |
| Consensus 4 | `project based design learning student teams tutors mentors facilitation development projects` | 2026-10-20T14:55:44.000Z | 2026-10-20T14:55:47.957Z |

### Search development and peer review

The search strategy was not independently peer reviewed by a search specialist. The retained search-development record reports that the strategies were developed for this project and identifies no adopted published methodological search filter or previous-review strategy. The record does not establish the absence of all external influences.

### Limited citation-graph test

A separate OpenAlex graph test on 19 October used exactly two prespecified seeds, one backward and one forward generation, with a 500-work ceiling per seed and direction, `corpus=all`, and no date, language, publication-type or open-access restriction. Backward links came from `referenced_works`, not the printed bibliography; forward links used `cites`. Retrieved works were not recursively added as seeds. The four graph collections reached their source-reported ends at that time.

| Prespecified seed | DOI | Backward graph IDs | Forward graph IDs |
| --- | --- | ---: | ---: |
| Doing complexity leadership theory: How agile coaches at Spotify practise enabling leadership (2019) | 10.1111/caim.12303 | 82 | 102 |
| A temporal model of team mentoring: a grounded theory approach (2021) | 10.1080/03043797.2021.1946680 | 45 | 4 |

These graph counts are source identifiers, not reports, independent studies or eligibility decisions. Six purposive printed-reference checks were limited spot checks and cannot establish graph recall or reference-list completeness. This historical test preceded separate, partially completed reference-list work. The previously planned review-wide citation search was not completed, and no further citation tracking is planned.

### Partial reference-list work

Before version 1.14, backward and forward citation searches were planned from included reports and the following five nearby reviews. The reference lists of four reviews were transcribed in part of the preparatory work: 241 reference positions were recorded and their order checked against the source lists. The reference list for Zheng, Mejia & Henriksen was not obtained through the checked routes. These positions are not a count of distinct eligible studies, and most corresponding reports have not been identified or selected. Apart from the earlier two-seed OpenAlex citation-graph test, the planned review-wide forward citation search was not performed. No further backward or forward citation tracing is planned.

| Predefined review seed | Title | DOI |
| --- | --- | --- |
| Traylor, Stahr & Salas (2020) | Team coaching: Three questions and a look ahead: A systematic literature review | [10.53841/bpsicpr.2020.15.2.54](https://doi.org/10.53841/bpsicpr.2020.15.2.54) |
| Obode et al. (2025) | Agile Coaching Research: A Systematic Mapping Study | [10.1007/978-3-031-94544-1_2](https://doi.org/10.1007/978-3-031-94544-1_2) |
| Mosely et al. (2025) | The role of expertise in design facilitation practice: A systematic review | [10.1016/j.destud.2025.101342](https://doi.org/10.1016/j.destud.2025.101342) |
| Zheng, Mejia & Henriksen (2025) | Directing, collaborating or suggesting: a literature review on co-design facilitation | [10.1080/15710882.2025.2540926](https://doi.org/10.1080/15710882.2025.2540926) |
| van den Biggelaar, Joshi & Dahl (2026) | Conceptual lenses for understanding facilitation in Participatory Design | [10.1080/15710882.2026.2648668](https://doi.org/10.1080/15710882.2026.2648668) |
