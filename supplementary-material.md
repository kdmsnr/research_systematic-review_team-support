# Supplementary material: search methods and included reports

This supplement presents the search strategies and 227 included report entries, followed by their available characteristics and JBI appraisal decisions. Reports are not assumed to be independent studies. Details of individual JBI item rationales and the full description-level coding index are not reproduced here.

The authors' original contributions are available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); any third-party material remains subject to its own rights.

## Search strategies and information sources

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

## Source locations for the selected comparison

The following four accounts inform the comparison of how contributions were handled and participants' experiences. Page numbers are physical PDF pages. The accounts concern different people and situations and do not establish a common causal pathway.

- Vermeulen et al. (2014), telecare products and services. <https://doi.org/10.2196/jmir.3195>. Physical PDF pages: 5, 6.
- Nendauni (2026), university writing-centre resources. <https://doi.org/10.1080/07294360.2026.2643245>. Physical PDF page: 9.
- Honey et al. (2026), mental-health recovery app co-design. <https://doi.org/10.1186/s12913-026-15335-y>. Physical PDF page: 25.
- Wojciechowski et al. (2026), family-planning co-design in Kenya. <https://doi.org/10.1080/15710882.2026.2711792>. Physical PDF pages: 15, 17.

## Included report characteristics and appraisals

Report and case scopes are distinguished. A missing characteristic means it was not extracted; it does not establish that it was not reported. Some text is withheld where it overlaps source passages.

The review lead reported on 15 November 2026 that AI-generated candidates across the review were checked and approved by a human. This report does not establish approval of candidates created after that statement.

Appraisal decisions are shown by checklist item, not combined into a quality score.
Y = Yes; N = No; U = Unclear; NA = Not applicable. Full checklists and selected
items are identified separately. Outcome and result labels identify the scope
assessed and do not extend an assessment to other outcomes or results. Separate
source records for the same report remain separate. Recorded part-specific
assessment states and limitations are retained. JBI item-by-item rationales
and their physical page references are not reproduced in this presentation.

Checklist abbreviations:

- Q: JBI Critical Appraisal Checklist for Qualitative Research (JBI 2020; [tool](https://jbi.global/sites/default/files/2020-08/Checklist_for_Qualitative_Research.pdf)).
- CS: JBI revised risk of bias for analytical cross-sectional studies (Barker et al. 2026; [tool](https://jbi.global/sites/default/files/2026-03/the_revised_jbi_critical_appraisal_tool_for_the.2.pdf)).
- QE: JBI revised risk of bias for quasi-experimental studies (Barker et al. 2024; [tool](https://doi.org/10.11124/JBIES-23-00268)).
- P: JBI tool for studies reporting prevalence data (Munn et al. 2014; [tool](https://doi.org/10.15171/ijhpm.2014.71)).

### 1. Elena Barbera; Iolanda Garcia; Marc Fuertes-Alpiste (2017). A Co-Design Process Microanalysis: Stages and Facilitators of an Inquiry-Based and Technology-Enhanced Learning Scenario. *The International Review of Research in Open and Distributed Learning*. https://doi.org/10.19173/irrodl.v18i6.2805

**Study design:** Qualitative design-based research; one case study.

**Setting:**

- Report: The report examines one case: redesigning an online Sustainable Development course in a tourism degree at the UOC.
- Case — Reported online-course co-design case: Redesign of an online Sustainable Development course in a tourism degree.

**Participants:**

- Report: The focal co-design team comprised a teacher, two students and research-team members; the workshops also involved five teachers from other disciplines.
- Case — Reported online-course co-design case: The focal co-design team included one teacher, two students and research-team members.

**Support:**

- Case — Reported online-course co-design case: Workshops used activities and representation instruments to support co-design.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:U; 9:U; 10:Y.

### 2. Williams, Irith; Brereton, Margot; Donovan, Jared; McDonald, Karalyn; Millard, Tanya; Tam, Alex; Elliott, Julian H. (2014). A Collaborative Rapid Persona-Building Workshop: Creating Design Personas with Health Researchers. *International Journal of Sociotechnology and Knowledge Development*. https://doi.org/10.4018/ijskd.2014040102

- Bibliographic note: the PDF title above differs from the source-record title.
- PDF bibliographic note: The checked PDF is an author-submitted manuscript; the publisher version was not independently checked for the title.

**Study design:** Qualitative action research case study with separate practitioner interviews.

**Setting:**

- Report: The report examines a persona-building workshop within an Australian HIV self-management design project and compares it with practitioner interviews.
- Case — HealthMap design case: An Australian design project investigated self-management support for people living with HIV.

**Participants:**

- Report: The study also included interviews with five practising senior designers.
- Case — HealthMap design case: The core team included a social researcher, a clinical researcher and an occupational-therapy postgraduate.

**Support:**

- Case — HealthMap design case: A designer facilitated a workshop with the HealthMap team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:Y.

### 3. Anna Charlotte Morris; Stephen Douch; Teodora Popnikolova; Chris McGinley; Faith Matcham; Edmund Sonuga-Barke; Johnny Downs (2024). A framework for remotely enabled co-design with young people: its development and application with neurodiverse children and their caregivers. *Frontiers in Psychiatry*. https://doi.org/10.3389/fpsyt.2024.1432620

**Study design:** Qualitative applied co-design case.

**Setting:**

- Report: The report presents a remote co-design framework illustrated by a paediatric wearable-activity-tracker project in childhood ADHD.
- Case — PACES remote co-design case: The framework was applied with neurodiverse children in a healthcare context.

**Participants:**

- Report: Eight children and their caregivers were recruited for in-depth participation from an advisory group of approximately 30 caregivers.
- Case — PACES remote co-design case: Eight children and their caregivers were recruited for in-depth participation.

**Support:**

- Case — PACES remote co-design case: Caregivers helped children access technology for online interviews.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 4. Srivastava, Pallavi; Jain, Shilpi (2017). A leadership framework for distributed self-organized scrum teams. *Team Performance Management*. https://doi.org/10.1108/tpm-06-2016-0033

**Study design:** Two-phase qualitative interview study.

**Setting:**

- Case — Distributed Scrum interview study: The interview study selected projects from an organisation providing IT services.
- Report: The two-phase study drew on projects in an IT services organisation developing software applications and services using an offshore-outsourcing model.

**Participants:**

- Report: Eighteen Scrum Masters agreed to participate in second-phase interviews.
- Case — Distributed Scrum interview study: Seventy-five Scrum masters were contacted and 32 participated in the first phase.

**Support:**

- Case — Distributed Scrum interview study: Managers or Scrum masters used tools to enhance communication.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 5. Nicola Antaki (2021). A learning architecture: Developing a collective design pedagogy in Mumbai with Muktangan School children and the Mariamma Nagar community. *Research for All*. https://doi.org/10.14324/rfa.05.1.09

**Study design:** Participatory practice-led design research.

**Setting:**

- Report: The pedagogical experiments involved a class at Muktangan Love Grove School and interventions for the school and local neighbourhood.
- Case — Reported pedagogical experiments: Pedagogical experiments in Mumbai, India.

**Participants:**

- Case — Reported pedagogical experiments: The same class of schoolchildren took part in four workshop series.
- Report: The reported projects involved the same class of schoolchildren across four workshop series, with school staff and the local community.

**Support:**

- Case — Reported pedagogical experiments: The author ran workshops with loose support from class teachers.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:Y.

### 6. Mazzarella, Francesco; May, Andrew; Mitchell, Val (2021). A methodological framework for crafting situated services. *Journal of Service Management*. https://doi.org/10.1108/josm-05-2020-0188

**Study design:** Participatory qualitative case studies.

**Setting:**

- Report — Participatory cases and framework evaluation: The framework drew on two participatory case studies with textile artisans in the United Kingdom and South Africa and was subsequently evaluated. Note: The cases are distinguished from the subsequent evaluation; the expert interview location is not inferred from the case locations.
- Case — Textile artisan case studies: Participatory case studies were conducted in Nottingham and Cape Town.

**Participants:**

- Report: The evaluation also included interviews with six specialists in designing services for social innovation.
- Case — Textile artisan case studies: The cases involved textile artisan communities.

**Support:**

- Case — Textile artisan case studies: Both cases used co-creation workshops and roundtable discussions.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 7. Binkhorst, F.; Poortman, C.L.; Van Joolingen, W.R. (2017). A qualitative analysis of teacher design teams: In-depth insights into their process and links with their outcomes. *Studies In Educational Evaluation*. https://doi.org/10.1016/j.stueduc.2017.10.001

**Study design:** Qualitative multiple-case study.

**Setting:**

- Report — Three teacher design team cases: The study monitored three networked teacher design teams organized by a university in the Netherlands during the 2014–2015 academic year. Note: The three teams are distinguished from one another; a separate common outcome or identical team experience is not assumed.
- Case — Three teacher design teams: The teams met at a university in the Netherlands.

**Participants:**

- Report: The researchers interviewed teacher design team participants and team coaches.
- Case — Three teacher design teams: Teams consisted of six to nine science teachers from different schools.

**Support:**

- Case — Three teacher design teams: Team coaches chaired meetings and provided pedagogical expertise.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 8. Keogh, Kathleen; Sterling, Leon; Venables, Anne (2007). A scalable and portable structure for conducting successful year-long undergraduate software team projects. *Journal of Information Technology Education*. https://doi.org/10.28945/230

- Repository record DOI: https://doi.org/10.25916/sut.26253986. This separate identifier was retained from the source record; the repository landing page was not independently retrieved in this check.

**Study design:** Qualitative descriptive educator case account.

**Setting:**

- Report: The structure had been implemented at no fewer than three universities in Australia and at several remote partner sites abroad.
- Case — Reported student team with a non-performing member: The paper reports on capstone project units at three institutions.

**Participants:**

- Report — Students described in the project framework: The authors discuss year-long software projects undertaken by later-year students in teams with external clients. Note: Describes the type of student project addressed by the report; it does not assert a single study cohort or aggregate participant count.
- Case — Reported student team with a non-performing member: A supervisor worked with a team.

**Support:**

- Case — Reported student team with a non-performing member: The supervisor urged the team to be tolerant and document contributions and attempts to engage the member.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- University of Ballarat student survey on working with real clients: tool not applicable. The authors report a survey in which 19 of 20 respondents answered yes to a positive statement about working with a real client, and 9 of 20 reported difficulties. These are actual survey data summarised as counts; timing, sampling, response rate and selection are not specified. The report gives no exposure-outcome comparison or distinct pre/post comparison for these results, so the current analytical cross-sectional and quasi-experimental JBI tools do not fit this particular survey. Applicability of a descriptive-survey or prevalence tool remains unconfirmed. This record does not judge the article non-empirical or negate its separately appraised qualitative account.

### 9. Letourneau, Susan M.; Bennett, Dorothy; McMillan Culp, Katherine; Mohabir, Priya; Schloss, Dana; Liu, ChangChia James; Honey, Margaret (2021). A Shift in Authority: Applying Transformational and Distributed Leadership Models to Create Inclusive Informal STEM Learning Environments. *Curator The Museum Journal*. https://doi.org/10.1111/cura.12418

**Study design:** Reflective qualitative institutional case accounts.

**Setting:**

- Report: The paper presents three cases concerning exhibit design, facilitation and activity development at the New York Hall of Science.
- Case — Rethinking Authority and Visitor Agency workshop: NYSCI hosted a workshop in May 2019.

**Participants:**

- Report: Across the cases, the report describes a workshop for science-centre professionals, youth facilitators known as Explainers, and project staff involved in activity development. The groups are not summed.
- Case — Rethinking Authority and Visitor Agency workshop: About thirty science-centre professionals attended.

**Support:**

- Case — Rethinking Authority and Visitor Agency workshop: Members of research, exhibits and youth-development teams planned and facilitated the conference. Note: The source uses conference here. Its identification with the workshop is inferred from consecutive descriptions, rather than explicitly defined, and a different event is not ruled out.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:U; 9:U; 10:Y.

### 10. Gururaj Fattepur; B. B. Kotturshettar; S. B. Burli; G. Jangali Satish (2016). A Systematic Approach for the Conduct of Engineering Design Projects. *Journal of Engineering Education Transformations*. https://doi.org/10.16920/jeet/2016/v0i0/85522

**Study design:** Teacher observational account with descriptive annual marks.

**Setting:**

- Report — Engineering design course projects: The report describes engineering design projects for third-semester industrial and production engineering students, with project marks compared across 2012–13 to 2014–15. Note: The three years are separate cohorts; the comparison does not establish a controlled effect.
- Case — Engineering design course projects: Engineering design projects were conducted in an Industrial and Production Engineering department.

**Participants:**

- Report: The course teacher divided students into groups of five.
- Case — Engineering design course projects: Third-semester undergraduate Industrial Production engineering students undertook projects.

**Support:**

- Case — Engineering design course projects: An activity sheet was prepared weekly and shared with the students.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Academic-year comparison of mean project marks: not assessable. Table 3 reports class sizes and annual mean marks for 2012-13, 2013-14 and 2014-15; the article does not specify when the teaching initiatives began or which cohorts were exposed. Therefore a before-after intervention comparison cannot be defined from this report. This concerns the marks comparison only; the educator account was separately appraised and the numerical data do not establish a causal effect.

### 11. Xie, Lei; Kogut, Ashlynn; Beyerlein, Michael; Boehm, Rodney (2021). A temporal model of team mentoring: a grounded theory approach. *European Journal of Engineering Education*. https://doi.org/10.1080/03043797.2021.1946680

**Study design:** Qualitative grounded theory study.

**Setting:**

- Report: The report investigates team mentoring in an intensive engineering design competition at a large US university.
- Case — Engineering design competition: An engineering design competition took place at a large US university.

**Participants:**

- Report: The researchers interviewed nine mentors from an engineering competition.
- Case — Engineering design competition: Students formed teams of four to six members.

**Support:**

- Case — Engineering design competition: Mentors asked teams to explain their design process.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 12. Jaime Perales-Puchalt; Mariola Acosta-Rullán; Mariana Ramírez-Mantilla; Paul Espinoza-Kissell; Eric D. Vidoni; Michelle Niedens; Edward F. Ellerbeck; Ladson Hinton; Linda Loera; A. Susana Ramírez; Esther Lara; Amber Watts; Kristine Williams; Jason Resendez; Jeffrey Burns (2022). A Text Messaging Intervention to Support Latinx Family Caregivers of Individuals With Dementia (CuidaTEXT): Development and Usability Study. *JMIR Aging*. https://doi.org/10.2196/35625

**Study design:** Qualitative description and thematic analysis.

**Setting:**

- Case — CuidaTEXT advisory development: Advisory meetings informed development of an SMS intervention.

**Participants:**

- Case — Advisory boards: Five advisory meetings involved up to six caregivers and sixteen health professionals.

**Support:**

- Case — Advisory-board feedback: The advisory board suggested edits to make keyword names simpler.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.

### 13. Brown, Phil; Baldassarre, Brian; Konietzko, Jan; Bocken, Nancy; Balkenende, Ruud (2021). A tool for collaborative circular proposition design. *Journal of Cleaner Production*. https://doi.org/10.1016/j.jclepro.2021.126354

**Study design:** Qualitative component of mixed methods design science evaluation.

**Setting:**

- Report — Tool demonstration and evaluation: The reported evaluation used six workshops to demonstrate a collaborative circular proposition design tool. Note: Report-wide account of the tool demonstration; workshop settings and challenge types may differ.
- Case — Six tool-demonstration workshops: The tool was demonstrated through six workshop sessions.

**Participants:**

- Report — Tool demonstration participants: Participants included practitioners and circular economy researchers across six workshop sessions. Note: Participant roles are reported at the level of the demonstration; workshop attendance and feedback-form counts are not interchangeable.
- Case — Six tool-demonstration workshops: Participants included practitioners and circular-economy researchers.

**Support:**

- Case — Six tool-demonstration workshops: Teams used a canvas while being facilitated.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.


**Part-specific limitations and assessment status:**

- Pooled descriptive user ratings for perceived usefulness and ease of use across six workshops: tool not applicable. The existing review description includes pooled descriptive ratings from 52 evaluation forms. In the main report these ratings describe tool perceptions without an identified exposure-outcome comparison for the pooled means; the available analytical cross-sectional and quasi-experimental tools therefore do not fit this specific descriptive result. The article reports incomplete form collection and refers to supplementary forms not read in this appraisal. This does not establish that all quantitative results in the paper are inapplicable to all appraisal methods; the qualitative component remains separately assessed. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is pooled usefulness and ease-of-use ratings; the existing assessment does not identify a target-population prevalence estimate. Six workshops, 52 evaluation forms and incomplete form collection affect interpretation; forms must not automatically be equated with independent people. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 14. Elizabeth A O’Donnell; Aricca D Van Citters; Inas S Khayal; Matthew M Wilson; David Gustafson; Amber E Barnato; Andrea C Buccellato; Colleen Young; Megan M Holthoff; Eugene Korsunskiy; Stephanie C Tomlin; Amelia M Cullinan; Alexandra C Steinbaugh; Jennifer J Hinson; Kristen R Johnson; Andrew Williams; Ruth M Thomson; Janet M Haines; Anne B Holmes; Ann D Bradley; Eugene C Nelson; Kathryn B Kirkland (2024). A Web-Based Peer Support Network to Help Care Partners of People With Serious Illness: Co-Design Study. *JMIR Human Factors*. https://doi.org/10.2196/53194

**Study design:** Descriptive co-design process with a reported design outcome; Descriptive group-weighted priority ratings in a co-design process.

**Setting:**

- Case — Regional network co-design: A regional network for care partners of adults with serious illness, focused on New Hampshire and Vermont, United States.

**Participants:**

- Case — Regional network co-design: An 18-member co-design team including care partners, people with serious illness, clinicians and support-service staff.

**Support:**

- Case — Regional network co-design: Researchers facilitated the co-design process and the team reviewed design exercises during sessions.

**JBI appraisal**

**Selected items only:** Q. Part: Reported clarification of the network objective during the facilitated co-design process. Design recorded: Descriptive co-design process with a reported design outcome.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Selected items only:** P. Part: Participant group-weighted priority rankings for co-design network specifications. Design recorded: Descriptive group-weighted priority ratings in a co-design process.


**Selected items:** 1:U; 4:Y; 6:U; 8:U.


**Part-specific limitations and assessment status:**

- Reported clarification of the network objective during the facilitated co-design process.: tool not applicable. The selected outcome is a descriptive design-process account, not a separately specified qualitative methodology. Selected qualitative items address documentation of evidence and conclusions.
- Participant group-weighted priority rankings for co-design network specifications.: tool not applicable. The outcome is a participatory design priority ranking, not a prevalence estimate; selected questions address the respondent frame, description, measurement and analysis.

### 15. Manuela Taboada; Jane Turner; Jen Seevinck; Marcus Foth (2024). A worldbuilding approach for pluriversality in codesign. *CoDesign*. https://doi.org/10.1080/15710882.2024.2349607

**Study design:** Qualitative narrative inquiry with two case studies.

**Setting:**

- Report: The paper examines two cases: a role-playing worldbuilding workshop and analogue board-game workshops.
- Case — Tabletop RPG worldbuilding workshop: A tabletop role-playing workshop formed part of an initiative to engage students with science.

**Participants:**

- Report: The tabletop workshop involved seven practising scientists; the board-game workshops involved researchers, including a postgraduate group of twelve. These are different workshop groups and are not summed.
- Case — Tabletop RPG worldbuilding workshop: The workshop involved seven participants from different scientific disciplines.

**Support:**

- Case — Tabletop RPG worldbuilding workshop: Facilitators answered questions and offered provocations to deepen the design work.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:U; 8:U; 9:Y; 10:U.

### 16. Katerina Kourentzi; Kristen Brosamer; Binh Vu; Richard C. Willson (2024). Accelerated Development of a COVID-19 Lateral Flow Test in an Academic Setting: Lessons Learned. *Accounts of Chemical Research*. https://doi.org/10.1021/acs.accounts.4c00075

**Study design:** Descriptive development case with laboratory tests and user feedback.

**Setting:**

- Report: The report describes the accelerated development of a SARS-CoV-2 lateral flow test by a University of Houston laboratory during the pandemic.
- Case — Glow LFA development: A University of Houston laboratory developed point-of-care diagnostic methods.

**Participants:**

- Report: The account concerns an academic development team working with expert consultants; the cited account does not establish a total team size.
- Case — Glow LFA development: An academic team worked on translation of an early-stage technology.

**Support:**

- Case — Glow LFA development: The RADx team advised the developers to focus on nasal swab extract.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 17. Sarah M. Wilson; Judith Montenegro; Lisvel A. Matos; Carrie B. Dombeck; Carolina Mejia; Jamilah Taylor; Aleida Espinal; Megan A. Reaves; Cristofer Navas; Samantha Fortier; Reeva Kandel; Amy Corneli (2026). Acción PrEP: A Multi‐Method Pilot Design to Assess the Feasibility of Community Co‐Designed Implementation Strategies to Advance PrEP Uptake Among Latines in the U.S. South. *Journal of the International AIDS Society*. https://doi.org/10.1002/jia2.70196

**Study design:** Qualitative thematic analysis of pilot implementer interviews within multimethod implementation study.

**Setting:**

- Report — Community co-design and implementation pilot: A workgroup from Mecklenburg County in North Carolina co-developed PrEP strategies that were later piloted at a health centre and a nonprofit healthcare organization. Note: The workgroup location and the subsequent pilot stages are distinguished; the two organizations are not treated as workgroup sites.
- Case — Acción PrEP co-design workgroup: A workgroup developed PrEP implementation strategies.

**Participants:**

- Report: Six individuals implementing the pilot and 17 potential adopters were interviewed as key informants.
- Case — Acción PrEP co-design workgroup: Workgroup members included people taking PrEP and people living with HIV.

**Support:**

- Case — Acción PrEP co-design workgroup: LITS and Duke co-facilitated the workgroup meetings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Optional co-design workgroup exit survey on group process and participation: tool not applicable. The workgroup exit survey reports descriptive ratings after the co-design process only. The reviewed revised JBI analytical cross-sectional tool requires an exposure-outcome association; the reviewed quasi-experimental tool requires an intervention comparison. Neither tool applies to this descriptive result. The workgroup survey result is distinct from the previously appraised pilot implementer interviews. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is optional, post-workgroup feedback; the existing assessment does not identify a target-population prevalence estimate. Voluntary response and the survey response denominator are pertinent to interpretation; the existing record does not establish the extent of nonresponse. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 18. Groen, Robert P. (2024). Action learning within the Dutch public sector: tools for facilitators. *Action Learning Research and Practice*. https://doi.org/10.1080/14767333.2023.2293400

**Study design:** Qualitative practitioner case account.

**Setting:**

- Report — Public-sector IT change programme: The action learning project took place within an IT change programme in a Dutch public-sector organization. Note: The report describes an organizational change project; the setting is not generalized to the Dutch public sector as a whole.
- Case — Dutch public-sector change program: A change program developed an IT system for complex hiring.

**Participants:**

- Report — Action learning sets: Two action learning sets were formed, each with around ten members. Note: The numbers are approximate set sizes, not a verified count of unique individuals across the project.
- Case — Dutch public-sector change program: Two action learning sets initially had ten members each.

**Support:**

- Case — Dutch public-sector change program: The facilitator and sets used and adapted conceptual tools to analyse change and make decisions.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:U; 9:U; 10:Y.

### 19. Mulec, Kina; Roth, Jonas (2005). Action, reflection, and learning – coaching in order to enhance the performance of drug development project management teams. *R&D Management*. https://doi.org/10.1111/j.1467-9310.2005.00405.x

- Bibliographic note: the PDF title above differs from the source-record title.
- Bibliographic note: the PDF title above differs from the linked-item title.

**Study design:** Qualitative component of mixed methods action research.

**Setting:**

- Report: Within AstraZeneca's research and development, the study examined two global management teams working across functions on drug development.
- Case — Drug development management teams: The study examined drug development management teams in AstraZeneca research and development.

**Participants:**

- Report: Sixteen interviews were held; five people were members of both teams.
- Case — Drug development management teams: The study included two global, cross-functional management teams.

**Support:**

- Case — Drug development management teams: Coaches met the respective project leaders between team meetings and coached them in their leadership roles.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:Y; 8:Y; 9:U; 10:Y.


**Part-specific limitations and assessment status:**

- Team interaction pre-post questionnaire changes: not assessable. The article reports the direction of questionnaire changes but the main paper provides no pre or post numerical values, respondent counts specific to this questionnaire or numerical test results. It describes t tests and Wilcoxon tests but does not provide enough information to assess a specific numerical result; the direction itself is reported and is not treated as absent. The separately assessed interview and observation findings remain unchanged.

### 20. Stacie Attrill; Kristen Foley; Chris Brebner (2025). Action-research of co-designed practice-placement models that ‘worked’ in shifting contexts of allied health industry, workforce and policy. *BMC Health Services Research*. https://doi.org/10.1186/s12913-025-13758-7

**Study design:** Realist qualitative action research.

**Setting:**

- Report: The action-research report concerns Australian disability-sector allied-health placement models developed within a workforce project.
- Case — Placement model project: An Australian workforce project addressed declining placement numbers during a disability-sector funding transition.

**Participants:**

- Report: The qualitative data included placement facilitators, service providers, placement coordinators, peak-body representatives, chief financial officers and students.
- Case — Placement model project: Eight service providers participated as project partners.

**Support:**

- Case — Placement model project: Placement facilitators liaised with service providers and bridged them to the university research team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 21. Salihu, Yazidu; Bass, Julian; Iyawa, Gloria (2024). ACTIVITIES TAILORING WITHIN AGILE SCRUM ROLES: A CASE OF NIGERIAN HEALTHCARE INFORMATION SYSTEMS DEVELOPMENT. *Journal of international technology and information management*. https://doi.org/10.58729/1941-6679.1603

**Study design:** Qualitative case study with grounded-theory-informed analysis.

**Setting:**

- Report: The study investigated the development of healthcare information systems in Nigeria.
- Case — Medical records project described by H3: A medical records project.

**Participants:**

- Report: Twelve agile practitioners working on healthcare information systems in Nigeria were interviewed.
- Case — Medical records project described by H3: The medical-records project involved a UI/UX designer and a Scrum master.

**Support:**

- Case — Medical records project described by H3: The Scrum master organised agile training for the team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 22. Áine Aventin; Stephan Rabie; Sarah Skeen; Mark Tomlinson; Moroesi Makhetha; Zanele Siqabatiso; Maria Lohan; Mike Clarke; Lynne Lohfeld; Allen Thurston; Jackie Stewart (2021). Adaptation of a gender-transformative sexual and reproductive health intervention for adolescent boys in South Africa and Lesotho using intervention mapping. *Global Health Action*. https://doi.org/10.1080/16549716.2021.1927329

**Study design:** Not extracted.

**Setting:**

- Report — Intervention adaptation: The intervention adaptation was conducted in Lesotho and South Africa.

**Participants:**

- Case — Intervention-mapping process: The mapping process involved whole-team discussion and consultation with project advisory groups.

**Support:**

- Case — Intervention-mapping discussion: Whole-team discussion was structured using a set of questions.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Whole-team intervention mapping and advisory consultations: not assessable. The adaptation account is a facilitated planning process. The focus-group thematic analysis concerns another component and does not assess the decision-making narrative.

### 23. Istanboulian, Laura; Rose, Louise; Yunusova, Yana; Dale, Craig (2023). Adapting co-design methodology to a virtual environment: co-designing a communication intervention for adult patients in critical care. *Research Involvement and Engagement*. https://doi.org/10.1186/s40900-023-00514-6

**Study design:** Qualitative descriptive feedback component.

**Setting:**

- Report — Virtual co-design intervention study: The co-design study concerned a 17-bed medical-surgical intensive care unit in a community-based Toronto hospital; the meetings were virtual. Note: The setting concerns the whole co-design study; virtual meetings are distinguished from the physical care setting.
- Case — COPE co-design committee: The study was conducted in a community hospital ICU in Toronto.

**Participants:**

- Report: The co-design committee comprised 11 participants.
- Case — COPE co-design committee: The committee included a patient and family member, nurses and other health professionals.

**Support:**

- Case — COPE co-design committee: The first author facilitated the meetings and encouraged participants to share and reflect.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 24. Tari Forrester‐Bowling; James J. Lucas; Andrew D. Brown; Stephanie Bennetts; Renae Carolin; Josh Hayward; Debbie Scott; Anna Peeters; James McLure (2024). Adapting Group Model Building for Mental Healthcare: A Participatory Co‐Design Approach. *International Journal of Mental Health Nursing*. https://doi.org/10.1111/inm.13451

**Study design:** Qualitative participatory process evaluation.

**Setting:**

- Report: The setting was Barwon Health, specifically its Mental Health, Drugs and Alcohol Services.

**Participants:**

- Report: Recruitment by expression of interest yielded eighteen participants.

**Support:**

- Report: The first group model-building workshop used an initial hopes-and-fears activity.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 25. Pádraig Cantillon-Murphy; John McSweeney; Louise Burgoyne; Colm O’Tuathaigh; Siún O’Flynn; George Shorten (2015). Addressing Biomedical Problems Through Interdisciplinary Learning: A Feasibility Study. *International Journal of Engineering Education*. [DOI not recorded]

- PDF bibliographic note: Publisher proof; first-page proof header identifies volume 31, number 1(B), 2015; final pagination and version are not confirmed.

**Study design:** Qualitative focus-group feedback within a feasibility study.

**Setting:**

- Report — Biomedical design module and one laparoscopic retraction team: An Irish university biomedical design module delivered in 2011/12 with clinically mentored student teams.

**Participants:**

- Report — Biomedical design module and one laparoscopic retraction team: Twenty-six students remained enrolled, including five medical students and 21 engineering or postgraduate research students, in six teams with clinical mentors.

**Support:**

- Report — Biomedical design module and one laparoscopic retraction team: A clinical mentor provided feedback during one team’s selection of a laparoscopic retraction design.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 26. Claudia L. Leung; Priscilla Kukua Goka; Barnabas Atangongo; Mansur Mohammed Musah Bingle; Ishmael Adu; Abdul Rashid Atchulo; Laud Boateng; Keng-Yen Huang; Neda Laiteerapong; Gbana Limann; Anna Volerman; Peter Mintir Amadu; William Frank Hill Koomson (2025). Adolescents as co-designers: adapting human-centered design to develop school-based mental health strategies in northern Ghana. *BMC Public Health*. https://doi.org/10.1186/s12889-025-25012-0

**Study design:** Rapid qualitative analysis of adolescent co-design workshops.

**Setting:**

- Report: The study was conducted in Tamale, Ghana.

**Participants:**

- Report: Twenty-four students from twelve public senior high schools participated in two workshops.

**Support:**

- Report: The researchers incorporated scaffolded facilitation, peer-led engagement and hands-on activities.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:U.

### 27. Olszewski, Mieszko Franciszek (2026). Agile Coach or Creativity Coach? How Scrum Masters and Agile Coaches Foster Creativity‐Conducive Spaces in Agile Software Teams. *Creativity and Innovation Management*. https://doi.org/10.1111/caim.70038

**Study design:** Qualitative interviews with scrum masters and agile coaches and literature-informed content analysis.

**Setting:**

- Report: Most interview participants were dispersed across cities in Poland.

**Participants:**

- Report: Twenty-eight participants were recruited, comprising 15 men and 13 women.

**Support:**

- Report: Interviewees reported supporting teams in planning activities.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:U.

### 28. Paasivaara, Maria; Lassenius, Casper (2014). Agile coaching for global software development. *Journal of Software Evolution and Process*. https://doi.org/10.1002/smr.1577

- Bibliographic note: the source record lists 2012; the journal year above follows the verified PDF.

**Study design:** Qualitative single-case study.

**Setting:**

- Report: An international Nordic-based software company.

**Participants:**

- Report: The interviewees included coaching team members and staff from four projects that received coaching.

**Support:**

- Report: During mentoring, coaches provided daily support and facilitated activities including planning, estimation, retrospectives and daily meetings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 29. Wim Som de Cerff; John van de Vegte; Reinout Boers; Theo Brandsma; Marijn de Haij; Wim van Moosel; Jan Willem Noteboom; Giuliano Andrea Pagani; Gerard van der Schrier (2018). Agile Development in Meteorological R&D: Achieving a Minimum Viable Product in a Scrum Work Setting. *Bulletin of the American Meteorological Society*. https://doi.org/10.1175/bams-d-17-0273.1

**Study design:** Descriptive questionnaire within a three-team practitioner case.

**Setting:**

- Report: At the Royal Netherlands Meteorological Institute, the work covered three innovation projects.

**Participants:**

- Report: Multidisciplinary project teams included scientists and software engineers.

**Support:**

- Report: Experienced Scrum Masters trained product owners before the sprint weeks.

**JBI appraisal**

**Selected items only:** P. Part: Descriptive quantitative retrospective survey of the three Scrum project teams. Design recorded: Descriptive questionnaire within a three-team practitioner case.


**Selected items:** 1:U; 2:U; 3:U; 4:Y; 5:U; 6:U; 7:U; 8:U.


**Part-specific limitations and assessment status:**

- Qualitative appraisal of the meteorological Scrum practice report: tool not applicable. The prior review identified a practical account of Scrum implementation rather than an identifiable qualitative research study suitable for the qualitative checklist. The excerpt locates the intervention and does not prove absence of research procedures.
- Descriptive quantitative retrospective survey of the three Scrum project teams: tool not applicable. This is an empirical three-case practitioner study with a descriptive post-sprint survey and reported response percentages, not merely advice or an absence of empirical data. The revised JBI analytical cross-sectional tool targets exposure-outcome associations, and the quasi-experimental tool targets a comparison; neither fits this single descriptive questionnaire result. The 2014 JBI prevalence checklist (Munn et al., doi:10.15171/ijhpm.2014.71; source: Consensus excerpts of body and appendix, full PDF and later edition not directly checked) provides applicable methodological questions but is not applied wholesale as an item-level prevalence study because a target-population prevalence study is not established. Relevant items: context and participants (item 4): three Scrum project teams over two one-week sprints are described, but the number of survey respondents is not stated in the reported results. Sampling (items 1–3): staff volunteered or were invited to teams; the completeness or representativeness of the retrospective respondents is unclear. Coverage (item 5): Table 3 states that not all members answered every question; denominators and item-level missingness are not given. Measurement (items 6–7): questions and response percentages are tabulated, but questionnaire development and reliability are not reported in this paper. Statistical reporting (item 8): percentages are reported, but denominators and precision are not specified, limiting verification. The percentages describe a participant retrospective and do not establish causal effects. Physical pages 3, 9 and 10, Table 3; the excerpt identifies the incomplete-response statement and does not prove absence of other details.

### 30. Campagnaro, Cristian; Passaro, Raffaele; Curtabbi, Giorgia (2023). Alimenta: A design-led systemic action against homelessness-related food poverty. *International Journal of Food Design*. https://doi.org/10.1386/ijfd_00063_1

**Study design:** Qualitative participatory design research.

**Setting:**

- Report: The Alimenta project addressed food poverty among homeless people in Turin.

**Participants:**

- Case — Initial cooking workshop: The cooking activity involved guests of the city shelter.
- Report: The researchers engaged homeless individuals and frontline workers at public shelters through field research.

**Support:**

- Case — Initial cooking workshop: The research team initiated a twice-weekly participatory cooking workshop at a city shelter.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:U; 8:U; 9:U; 10:U.

### 31. Laduca, Brian; Ausdenmoore, Adrienne; Katz-Buonincontro, Jen; Hallinan, Kevin Patrick; Marshall, Karlos (2017). An Arts-Based Instructional Model for Student Creativity in Engineering Design. *International Journal of Engineering Pedagogy (iJEP)*. https://doi.org/10.3991/ijep.v7i1.6335

**Study design:** Descriptive stakeholder-feedback account within an interdisciplinary action-research pilot.

**Setting:**

- Case — Unmanned-aircraft team: A student team worked on a lifesaver-drone concept.

**Participants:**

- Report — Two summer pilots: Each summer pilot supported twelve student interns from multiple disciplines.

**Support:**

- Case — Unmanned-aircraft team: Police and emergency medical professionals gave input on the team’s proposed drone.

**JBI appraisal**

**Selected items only:** Q. Part: Police and emergency-care professionals’ input to the unmanned-air-systems team and the reported maturation of its final concept. Design recorded: Descriptive stakeholder-feedback account within an interdisciplinary action-research pilot.


**Selected items:** 3:U; 4:U; 10:U.


**Part-specific limitations and assessment status:**

- Police and emergency-care professionals’ input to the unmanned-air-systems team and the reported maturation of its final concept.: tool not applicable. The paper reports stakeholder input to an identified project team, but does not describe a separate qualitative research methodology for this specific feedback-to-concept account. Selected qualitative items examine evidence documentation and inference.

### 32. Salihu, Yazidu Buba; Bass, Julian Michael; Iyawa, Gloria Ejehiohen (2026). An Empirical Process Model for Agile Practitioners Developing Healthcare Software. *IET Software*. https://doi.org/10.1049/sfw2/6862755

**Study design:** Qualitative interviews and model evaluation across four phases.

**Setting:**

- Report: The study investigated agile approaches in medical software development.

**Participants:**

- Report: The interviews involved 30 agile practitioners based in the UK, Nigeria and India.

**Support:**

- Case — Nigerian practitioner P20: A practitioner described removing obstacles and facilitating sprint ceremonies.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 33. Spiegler, Simone V.; Heinecke, Christoph; Wagner, Stefan (2021). An empirical study on changing leadership in agile teams. *Empirical Software Engineering*. https://doi.org/10.1007/s10664-021-09949-5

**Study design:** Constructivist grounded theory.

**Setting:**

- Report: The study was conducted at Robert Bosch GmbH.

**Participants:**

- Case — Second and third interview rounds: The later two interview rounds included Scrum Masters, Product Owners and members of both software and non-software project teams.
- Report: The grounded theory study included 75 practitioners from 11 divisions at Robert Bosch.

**Support:**

- Report: Some Scrum Masters reported adapting the Scrum method to teams.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:U.

### 34. Anna Jolliff; Ryan J. Coller; Hannah Kearney; Gemma Warner; James A. Feinstein; Michelle A. Chui; Steve O'Brien; Misty Willey; Barbara Katz; Theodore D. Bach; Nicole E. Werner (2024). An mHealth Design to Promote Medication Safety in Children with Medical Complexity. *Applied Clinical Informatics*. https://doi.org/10.1055/a-2214-8000

- PDF bibliographic note: The accepted manuscript appeared online in 2023; the journal article was published online in January 2024.
- Bibliographic note: the source record lists 2023; the journal year above follows the verified PDF.
- Bibliographic note: bibliographic metadata list 2023; the journal year above follows the checked PDF.

**Study design:** Qualitative co-design analysis.

**Setting:**

- Case — Medication-safety co-design: Co-design participants were recruited through a pediatric complex care program.

**Participants:**

- Case — Medication-safety co-designers: Co-designers included family caregivers and secondary caregivers.

**Support:**

- Case — Co-design facilitation: The facilitator invited quieter participants to contribute.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.

### 35. Fülscher, Jan; Powell, Stephen G. (1999). Anatomy of a process mapping workshop. *Business Process Management Journal*. https://doi.org/10.1108/14637159910283029

**Study design:** Descriptive qualitative observational case study.

**Setting:**

- Report: A mid-size Swiss insurance company.

**Participants:**

- Report: The workshop involved two facilitators and five representatives of organizational and business functions.

**Support:**

- Report: The workshop used the IDEF0 process-mapping tool.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Participant ratings of workshop and result quality at two points on day 3: tool not applicable. During the workshop the facilitator asked participants to rate the results and workshop quality; most initial ratings were low (physical p.17). The research paper later compares these with uniformly positive ratings in the final hour (physical p.25). These are real repeated participant ratings and the authors interpret their change; the report gives no individual ratings, numeric scale definitions or exact counts. Facilitation was already underway at the first rating and no separately introduced intervention or control comparison is specified, so the current quasi-experimental and analytical cross-sectional tools do not fit this particular descriptive comparison. This is not a claim that the paper lacks empirical data or analysis; the observation narrative is separately appraised.

### 36. Marcos, Esperanza; Hens, Roberto; Puebla, Teresa; Vara, Juan Manuel (2021). Applying Emotional Team Coaching to Software Development. *IEEE Software*. https://doi.org/10.1109/ms.2020.3007658

- PDF bibliographic note: The checked PDF states that it is accepted for a future issue and has not been fully edited; the linked item gives 2021, but the definitive publication year remains unconfirmed.
- Bibliographic note: the review lead selected the year above; the source record lists 2020. This choice does not establish the relationship between versions.

**Study design:** Uncontrolled single-team before-and-after comparison in a practice report.

**Setting:**

- Report: An outsourced IT team.

**Participants:**

- Report: The team comprised one project leader and five developers.

**Support:**

- Report: Two emotional intelligence coaches conducted the process.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: Reported proportion of maintenance projects that included automated tests:** 5:N; 6:U; 7:U.

**Outcome: Reported proportion of maintenance projects that included automated tests; result: Reported automated-test inclusion below 7 percent before and above 50 percent by the end of the experience:** 8:U; 9:N.

**Study:** 1:Y; 2:N; 3:U; 4:N.


**Part-specific limitations and assessment status:**

- Qualitative appraisal of the emotional team-coaching practice report: tool not applicable. The prior review identified a coaching practice report rather than a separately identifiable qualitative research study suitable for the qualitative checklist. The excerpt locates the coaching process and does not prove absence of research procedures.

### 37. Byers, Lynn; Bellocchio, Andrew; Crawford, Bobby (2010). Applying Physics to an Undergraduate Design for an Unmanned Aerial System. *International Journal of Mechanical Engineering Education*. https://doi.org/10.7227/ijmee.38.4.6

**Study design:** Mixed descriptive educational evaluation; Non-randomized historical cohort comparison.

**Setting:**

- Report: A senior-year capstone design at the United States Military Academy.

**Participants:**

- Report: Student design teams at UAS completed a survey concerning the Alpha .60 laboratory.
- Case — First and second project years: In the first year there were two teams; in the second year there were three different teams.

**Support:**

- Case — Third project year: A hands-on laboratory guided cadets through aerodynamic modeling and performance analysis; students were required to complete it on an existing airframe. Note: Support describes both the laboratory instruction and its required use on an existing airframe.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Mixed descriptive educational evaluation.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Full checklist:** QE. Design recorded for the assessment: Non-randomized historical cohort comparison.


**Outcome: Self-reported ability to formulate engineering problems and apply mathematics and science:** 5:N; 6:Y; 7:U.

**Outcome: Self-reported ability to formulate engineering problems and apply mathematics and science; result: Course-end ratings for D1 comparing the 2006/07 and 2007/08 UAS teams:** 8:NA; 9:U.

**Outcome: Self-reported confidence applying mathematics and science in the design process:** 5:N; 6:Y; 7:U.

**Outcome: Self-reported confidence applying mathematics and science in the design process; result: Course-end ratings for E4 comparing the 2006/07 and 2007/08 UAS teams:** 8:NA; 9:U.

**Outcome: Self-reported familiarity with basic mathematics and sciences and applying advanced mathematics:** 5:N; 6:Y; 7:U.

**Outcome: Self-reported familiarity with basic mathematics and sciences and applying advanced mathematics; result: Course-end ratings for D2 comparing the 2006/07 and 2007/08 UAS teams:** 8:NA; 9:U.

**Study:** 1:Y; 2:Y; 3:U; 4:U.

### 38. Jane Farmer; Karen Carlisle; Virginia Dickson-Swift; Simon Teasdale; Amanda Kenny; Judy Taylor; Felicity Croker; Karen Marini; Mark Gussy (2018). Applying social innovation theory to examine how community co-designed health services develop: using a case study approach and mixed methods. *BMC Health Services Research*. https://doi.org/10.1186/s12913-018-2852-0

**Study design:** Abductive qualitative comparative case study.

**Setting:**

- Report: Six rural Australian communities.

**Participants:**

- Report: Eighty-eight volunteer community-based participants were engaged.

**Support:**

- Report: External facilitation brought resources together.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:U; 9:Y; 10:Y.

### 39. Keefe, M.; Glancey, J.; Cloud, N. (2007). Assessing Student Team Performance in Industry Sponsored Design Projects. *Journal of Mechanical Design*. https://doi.org/10.1115/1.2722791

**Study design:** Analytical comparison of project-level records.

**Setting:**

- Report: Team-based courses culminating in an industry-sponsored senior capstone design.

**Participants:**

- Report: Student teams were assessed by faculty and industry sponsors.

**Support:**

- Report: At the end of each phase, faculty and industry sponsors assessed student-team performance using the same rubric.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Faculty-assigned final team grade:** 2:NA; 4:U; 6:Y.

**Outcome: Faculty-assigned final team grade; result: Table 1 faculty-advisor factor in three-factor ANOVA of final team grades p 0.59:** 7:U.

**Study:** 1:U; 3:Y; 5:U; 8:U.

### 40. Zeivots, Sandris; Sun, Jennifer Z.; Kennedy, Amanda; Cram, Andrew; Liao, Yuan (2026). Assessment design through co-design: reimagining assessment design practices in higher education. *Assessment & Evaluation in Higher Education*. https://doi.org/10.1080/02602938.2026.2643341

**Study design:** Practitioner inquiry into assessment co-design across three courses.

**Setting:**

- Report: Three courses at an Australian business school.

**Participants:**

- Case — Connect:In workshops: Students, educators, educational developers, learning designers and industry partners took part in the Connect:In workshops.
- Report: A total of 102 stakeholders participated across three courses and four interconnected interventions.

**Support:**

- Case — Connect:In workshops: Workshop facilitators used reflective prompts and structured visual mapping.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 41. Bart Daemen; Konstantinos Tsilionis; Oktay Turetken (2025). Balancing organizational alignment, team autonomy, and control in large-scale agile organizations. *Information and Software Technology*. https://doi.org/10.1016/j.infsof.2025.107998

**Study design:** Interpretive qualitative case study.

**Setting:**

- Report: The IT Architecture Competence was the unit of analysis.

**Participants:**

- Report: Ten people participated in interviews.

**Support:**

- Report: Standards were collectively established and disseminated across the organization.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 42. Adrienne M. Young; Anja Christoffersen; Dale Trevor; Suzanne Stringer; Tim Cudmore; Leonie Sanderson; Gillian Nasato; Lisa Anemaat; Katrina L. Campbell (2026). Better Healthcare Together: Co‐Designing a Framework for Health Service Co‐Design. *Health Expectations*. https://doi.org/10.1111/hex.70784

**Study design:** Qualitative content analysis within co-design.

**Setting:**

- Report: A metropolitan health service in Queensland, Australia.

**Participants:**

- Case — Workshop and online forum: The workshop and online forum involved 63 health service staff and 19 health consumers.
- Report: In total, 128 people participated over 12 months: 100 were health-service staff and 28 were health consumers.

**Support:**

- Report: Project co-leads co-planned and co-facilitated activities with input from design experts and a peer mentor.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.

### 43. Williams, Suzanne; Keogh, Samantha; Herd, David; Riggall, Sharonn; Glass, Roselyn; Douglas, Clint (2022). Building effective engagement for implementation with i-PARIHS: a collaborative enquiry into paediatric pain care in the emergency department. *BMC Health Services Research*. https://doi.org/10.1186/s12913-022-07740-w

**Study design:** Qualitative synthesis within mixed-methods implementation study.

**Setting:**

- Report: An Australian children’s hospital emergency department.

**Participants:**

- Report: The Kids Pain Collaborative engaged emergency department clinicians and researchers.

**Support:**

- Report: Facilitation used curious questioning and active listening.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 44. Yue, Kwok-Bun; De Silva, Dilhar; Kim, Dan; Aktepe, Mirac; Nagle, Stewart; Boerger, Chris; Jain, Anubha; Verma, Sunny (2009). Building Real World Domain-Specific Social Network Websites as a Capstone Project. *Journal of Information Systems Education*. [DOI not recorded]

**Study design:** Mixed descriptive project case.

**Setting:**

- Report: Two capstone teams built a social networking site for a swimming team.

**Participants:**

- Report: Nine students were involved across the two capstone teams.

**Support:**

- Report: Both teams refined requirement and design models in consultation with the mentor, head coach and instructor.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Mentor and student course-outcome satisfaction ratings: tool not applicable. The authors report end-of-semester ratings of 4 or 5, with most being 5, from the mentors and nine students; the breakdown by respondent and exact counts are not provided. This is a descriptive one-time rating with no reported exposure-outcome association or intervention comparator, so the currently available analytical cross-sectional and quasi-experimental checklists are not appropriate. Applicability of a descriptive prevalence checklist remains unresolved. Page 7 was inspected visually because the existing text layer lacks word spaces; the cited heading confirms location only.

### 45. Samantha Scarpinella; Courtney Cole; Sarah Ritter; Susan Mohammad; Kathryn Jablokow; Scarlett Miller (2023). Can We Get an Intervention, Please? The Utility of Teaming Interventions on Engineering Design Student Psychological Safety. *Journal of Mechanical Design*. https://doi.org/10.1115/1.4062395

**Study design:** Non-randomized historical cohort comparison.

**Setting:**

- Report — First-year engineering design course: First-year cornerstone engineering design course at a northeastern university. Note: The paper reports this feature for the specified course and cohorts.

**Participants:**

- Report — First-year engineering design course: The intervention cohort included 148 students in 38 teams; a prior course cohort included 263 students in 69 teams. Note: The paper reports this feature for the specified course and cohorts.

**Support:**

- Report — First-year engineering design course: Instructor-led reflection and staged videos introduced team psychological safety and four role assignments. Note: The paper reports this feature for the specified course and cohorts.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: Team psychological safety measured at five time points using the seven-item scale and team means.:** 5:N; 6:Y; 7:U.

**Outcome: Team psychological safety measured at five time points using the seven-item scale and team means.; result: Repeated-measures comparison of team psychological safety between the video-and-role intervention cohort and the earlier no-intervention cohort, including overall group effect, interaction and time-point 5 means.:** 8:U; 9:U.

**Study:** 1:Y; 2:Y; 3:U; 4:N.

### 46. Wan, Jiangping; Zhu, Yahui; Zeng, Ming (2013). Case study on critical success factors of running Scrum. *Journal of Software Engineering and Applications*. https://doi.org/10.4236/jsea.2013.62010

**Study design:** Descriptive case study with survey data.

**Setting:**

- Report: A Scrum team in J group.

**Participants:**

- Report: The Scrum team comprised a Scrum Master, product leader and team.

**Support:**

- Case — J group agile team: Agile team members collected and distributed key information before daily team meetings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- J group retrospective survey of teamwork and related change: tool not applicable. The report gives the proportions of J group respondents reporting improvement, no change or decrease; it does not report separate baseline and follow-up measurements or an exposure-outcome comparison. It describes over 600 people across 50 projects, but does not specify the number of respondents for Table 1 or the survey instrument. The analytical cross-sectional and quasi-experimental tools are therefore not appropriate to this descriptive retrospective survey; suitability of a descriptive prevalence checklist remains unresolved. This does not assess the distinct five-company questionnaire.

### 47. Jeanette Kirk; Thomas Bandholm; Ove Andersen; Rasmus Skov Husted; Tine Tjørnhøj-Thomsen; Per Nilsen; Mette Merete Pedersen (2021). Challenges in co-designing an intervention to increase mobility in older patients: a qualitative study. *Journal of Health Organization and Management*. https://doi.org/10.1108/jhom-02-2020-0049

**Study design:** Qualitative thematic content analysis of a co-design case.

**Setting:**

- Report: Two hospitals in Denmark.

**Participants:**

- Case — Patient and relative workshop: A workshop included five patients and five relatives.
- Report: Five co-design workshops involved health professionals, patients and relatives.

**Support:**

- Report: Researchers facilitated smaller groups during the workshops.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:U; 10:Y.

### 48. Claudia Virdun; Gursharan K. Singh; Gillian Harvey; Patsy Yates; Jane L. Phillips; Alison Mudge (2026). Clinician perspectives of an improvement bundle to improve integrated palliative care: a qualitative study. *BMC Palliative Care*. https://doi.org/10.1186/s12904-026-02361-0

**Study design:** Qualitative post-implementation clinician and manager interviews.

**Setting:**

- Report: The site was a large public tertiary hospital in an Australian metropolitan area.

**Participants:**

- Report: There were 27 interviews: 20 with nursing staff, six with medical staff and one with allied health staff.

**Support:**

- Report: During co-design meetings, the facilitator presented baseline patient-reported experience findings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 49. Conyers, Hayley; Sakuma, Yoshiko; Jannaway, Tracey; Cowan, Alex; Tucker, Joseph D.; Kpokiri, Eneyi Edith; Wu, Dan (2025). Co-creating inclusive sexual health services for middle-aged and older adults, including disabled people, in England: an innovative participatory approach within the field of sexual health. *Sexual Health*. https://doi.org/10.1071/sh25022

**Study design:** Qualitative facilitator evaluation of participatory co-creation.

**Setting:**

- Report: In the UK, a project co-created improvements to sexual healthcare for middle-aged people and older adults, including people with disabilities.

**Participants:**

- Report: The research reported community engagement with middle-aged, older and/or disabled populations.

**Support:**

- Report: Community leaders with lived experience partnered with the research team to co-design and co-organise sessions.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 50. Nendauni, Lutendo (2026). Co-creating writing support: reimagining students as pedagogical partners in a South African writing centre. *Higher Education Research & Development*. https://doi.org/10.1080/07294360.2026.2643245

**Study design:** Participatory action research.

**Setting:**

- Report: A South African university writing centre.

**Participants:**

- Report: Five tutors from a writing centre and ten student writers took part.

**Support:**

- Report: Tutors and student co-researchers planned the workshops and facilitated them together.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 51. Tay, Brenda S. J.; Edney, Sarah M.; Brinkworth, Grant D.; Cox, David N.; Wiggins, Bonnie; Davis, Aaron; Gwilt, Ian; Haveman-Nies, Annemien; Ryan, Jillian C. (2021). Co-design of a digital dietary intervention for adults at risk of type 2 diabetes. *BMC Public Health*. https://doi.org/10.1186/s12889-021-12102-y

**Study design:** Participatory qualitative co-design workshops.

**Setting:**

- Report: Three workshops held online were used to develop and review app prototypes for people at risk of type 2 diabetes.

**Participants:**

- Report: Across workshops, the study involved 20 end-users and four experts.

**Support:**

- Report: The workshops used trained facilitators and at least two assistant facilitators.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:Y.

### 52. Mary Anne Lagmay Tanay; Jo Armes; Catherine Oakley; Lesley Sage; Deb Tanner; Jose Roca; Liz Bryson; Barbara Greenall; Lauren Urwin; Toni Wyatt; Glenn Robert (2022). Co-designing a cancer care intervention: reflections of participants and a doctoral researcher on roles and contributions. *Research Involvement and Engagement*. https://doi.org/10.1186/s40900-022-00373-7

**Study design:** Reflexive qualitative thematic analysis of co-design experiences.

**Setting:**

- Report: The project co-designed a cancer care intervention.

**Participants:**

- Report: Ten reflections were collected from clinicians, patient participants or public involvement group members, a doctoral researcher and a visual illustrator.

**Support:**

- Report: An oncology nurse and doctoral student facilitated all the co-design workshops.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 53. Anita MY Goh; Colleen Doyle; Ellen Gaffy; Frances Batchelor; Meg Polacsek; Steven Savvas; Sue Malta; David Ames; Margaret Winbolt; Anita Panayiotou; Samantha M Loi; Claudia Cooper; Gill Livingston; Lee-Fay Low; Anne Fairhall; Jason Burton; Briony Dow (2022). Co-designing a dementia-specific education and training program for home care workers: The ‘Promoting Independence Through Quality Dementia Care at Home’ project. *Dementia*. https://doi.org/10.1177/14713012211065377

**Study design:** Participatory co-design qualitative component.

**Setting:**

- Report: The work took place with service providers in Victoria, Australia.

**Participants:**

- Case — Four World Café workshops: Across four workshops, 46 participants included people living with dementia, family carers and home care staff.
- Report: In an earlier qualitative stage, 43 participants took part in interviews or focus groups.

**Support:**

- Case — Four World Café workshops: A facilitator introduced the World Café principles and participation ground rules.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:U; 9:Y; 10:Y.

### 54. Patricia Abril-Jiménez; Beatriz Merino-Barbancho; Cecilia Vera-Muñoz; María Teresa Arredondo Waldmeyer (2021). Co-designing a remote rehabilitation tool for Parkinson’s disease: exploratory values and challenges. *BMC Neurology*. https://doi.org/10.1186/s12883-021-02519-8

**Study design:** Qualitative co-design sessions with interviews and focus groups.

**Setting:**

- Report — Parkinson co-design sessions: A remote Parkinson rehabilitation tool was co-designed in Spain.

**Participants:**

- Report — Seven workshops, as reported in body: The body reports 84 participants across seven workshops; the abstract reports six sessions, and Table 1 professional subcategories sum to 23 while the body and Figure 2 give 24.

**Support:**

- Case — Researcher-guided sessions: The research team guided the discussion in each workshop.

**JBI appraisal**

**Selected items only:** Q. Part: Reported identification of design requirements during collaborative sessions. Design recorded: Qualitative co-design sessions with interviews and focus groups.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Reported identification of design requirements during collaborative sessions: not assessable. The broader study analyses focus-group transcripts, but the selected aggregate claim is not traceable to an identified group or a discrete analytic step.

### 55. Pamela Napier; Terri Wada (2015). Co-Designing for Healthcare: Visual Designers as Researchers and Facilitators. *Visible Language*. [DOI not recorded]

**Study design:** Qualitative participatory design case account.

**Setting:**

- Report: MESH is a public-private partnership supporting healthcare providers in responding to emergencies.

**Participants:**

- Case — Pre-consult meeting: The MESH team participated in the pre-consult meeting.
- Report: The professional project involved clients and their staff, end-users, technology facilitators and an external graphic design team.

**Support:**

- Case — Pre-consult meeting: The team discussed while the facilitators captured their thoughts on whiteboards.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 56. David Clarke; Karolina Gombert-Waldron; Stephanie Honey; Geoffrey Cloud; Ruth Harris; Alastair Macdonald; Christopher McKevitt; Glenn Robert; Fiona Jones (2021). Co-designing organisational improvements and interventions to increase inpatient activity in four stroke units in England: a mixed-methods process evaluation using normalisation process theory. *BMJ Open*. https://doi.org/10.1136/bmjopen-2020-042723

**Study design:** Qualitative process evaluation within mixed-methods case comparison.

**Setting:**

- Report: Rehabilitation stroke units in England.

**Participants:**

- Report: The process evaluation included 76 staff and 53 stroke survivors in interviews.

**Support:**

- Report: The Point of Care Foundation led EBCD or AEBCD training attended by members from each stroke team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Quantitative patient-activity findings mentioned in the CREATE study context: outside appraisal scope. This scope decision concerns only the quantitative patient-activity summary mentioned in the introduction of this process-evaluation report. The four existing review descriptions extract site-specific co-design activities and qualitative observations of work and participation; they do not identify a quantitative patient-activity result as an extracted outcome. On physical page 2 the authors say that the CREATE findings are reported elsewhere and briefly summarise the quantitative activity data without a result-level analysis here. The source page and the current review descriptions were checked; this does not decide the relevance or appraisal of the separately reported CREATE publications or of every quantitative result in the programme.

### 57. Madison Leggatt; Nicole C. George; Syrine Gamra; Paola Leal; Catherine Paquet; Alayne M. Adams (2025). Co-designing social prescribing pathways: guidance on the use of deliberative dialogues for inclusive implementation. *BMC Primary Care*. https://doi.org/10.1186/s12875-025-03041-3

**Study design:** Qualitative synthesis of participatory activities.

**Setting:**

- Case — Two local online deliberative dialogues: Two online deliberative dialogues were held.
- Report: The project included online local dialogues and an in-person workshop at an international social prescription conference in Toronto, Canada.

**Participants:**

- Report: In the first online dialogue there were three family doctors, one social worker and one physiotherapist; three social workers attended the second. A separate conference workshop had approximately 70 attendees. Whether participants overlapped is unknown.
- Case — First local deliberative dialogue: The first dialogue brought together three family doctors, one social worker and one physiotherapist.

**Support:**

- Case — Local deliberative dialogues: The facilitator asked breakout-room participants whether anyone wanted to add to or modify each listed barrier.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:U; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Descriptive provider polls during outreach preceding the Montréal deliberative dialogues: outside appraisal scope. The existing active review description extracts the later facilitated deliberative dialogues and participants’ identified pathway features. The paper reports that initial clinic-outreach polls asked providers about social needs and barriers before those dialogues; the current description does not extract the poll proportions as results of the dialogue or a supported team outcome. The initial outreach and existing active description were checked for this limited scope. This does not classify all survey data or other activities in the paper, and the separate conference-workshop description has its existing needs_revision status.

### 58. Jill Hanass-Hancock; Thakasile Ndlovu; Samantha Willan; Nolufefe Zulu; Siqiniseko Mhlongo; Annah Mabunda; Thesandree Padayachee; Jacques Lloyd; Thobeka Mthethwa; Bradley Carpenter (2025). Co-designing the disability awareness toolkit for disability-inclusive and accessible health and post-GBV clinical services in South Africa. *International Journal for Equity in Health*. https://doi.org/10.1186/s12939-025-02664-3

**Study design:** Qualitative co-design study with descriptive field-testing.

**Setting:**

- Report: The South African project addressed health services and clinical services following gender-based violence.

**Participants:**

- Report: A diverse group of interested parties took part in workshops, including persons with disabilities.

**Support:**

- Case — Facility feedback: The team shared reports in a joint meeting where results were discussed and solutions brainstormed.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Field-test facility disability-accessibility assessment scores: outside appraisal scope. The quantitative field-test data describe disability-accessibility features of healthcare facilities, and do not directly measure the co-design team’s work, participation, or developed product. They were used as feedback for planning local facility changes. These facility scores are not the target team outcome appraised here; the separately appraised co-design consultations and reported development of the checklist remain in scope.

### 59. James Durl; Jakob Trischler; Timo Dietrich (2017). Co-designing with young consumers – reflections, challenges and benefits. *Young Consumers Insight and Ideas for Responsible Marketers*. https://doi.org/10.1108/yc-08-2017-00725

**Study design:** qualitative study of youth co-design sessions within a broader trial.

**Setting:**

- Report: A co-design project for an alcohol education program with an interactive virtual reality component.

**Participants:**

- Report: The sample comprised 22 participants aged 14 to 16.

**Support:**

- Report: Research team members observed and facilitated the co-design session.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 60. Mary Darking; Helen Ayles; Steve Belemu; Paloma Chausa; Francisco J. Gárate; Enrique J. Gómez; Melleh Gondwe; David Lane; Deborah Kaluba-Milimo; Monde Mwamba; Musonda Simwinga; Jennifer Whetham; Jaime H. Vera (2026). Co-producing access to care with young people living in Zambia through digital and vending machine-enabled innovation in sexual and reproductive health: A place-based, human-centred design research approach. *PLoS ONE*. https://doi.org/10.1371/journal.pone.0356398

**Study design:** Place-based qualitative co-production and design research.

**Setting:**

- Report: Participants were required to live in Lusaka.

**Participants:**

- Report: Across two phases, 56 young people served as workshop participants or as co-design leads.

**Support:**

- Case — Phase One workshops: Youth co-design leads and the research team set out potential pathway components around the workshop space.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 61. Lynn M. Rose; Fiona Wills; Connie Bourassa-Shaw; Terri L. Butler; Jeanette Griscavage Ennis; Kim Emmons; Patrick Shelby; Meher Antia; Kim Folger Bruce (2017). Collaborative academic medical product development: An 8-year review of commercialization outcomes at the Institute of Translational Health Sciences. *Journal of Clinical and Translational Science*. https://doi.org/10.1017/cts.2017.13

**Study design:** Descriptive retrospective interview questionnaire within an institutional program review.

**Setting:**

- Case — DDAC consultation: A biomedical advisory committee consulted individual investigators on product development.

**Participants:**

- Case — DDAC interview respondents: Seventeen investigators were included in the reported DDAC interviews.

**Support:**

- Case — DDAC consultation: The committee supplied scientific and regulatory guidance.

**JBI appraisal**

**Selected items only:** P. Part: Survey responses on whether DDAC discussions changed or informed investigators’ development and commercialization plans. Design recorded: Descriptive retrospective interview questionnaire within an institutional program review.


**Selected items:** 1:U; 2:U; 3:U; 4:U; 5:Y; 6:U; 7:U; 8:Y.


**Part-specific limitations and assessment status:**

- Survey responses on whether DDAC discussions changed or informed investigators’ development and commercialization plans.: tool not applicable. The selected result is a descriptive proportion from 17 interviews, not a population prevalence study. Selected Munn 2014 items are used for sampling, measurement, coverage and descriptive analysis only.

### 62. Hanna Aarnio; Kaiju Kangas; Maria Clavert; Auli Toom (2025). Collaborative assessment in design-based technology education. *International Journal of Child-Computer Interaction*. https://doi.org/10.1016/j.ijcci.2025.100779

**Study design:** Qualitative ethnographic video study.

**Setting:**

- Report: A board-game design project in a Finnish primary school.

**Participants:**

- Report: Two craft teachers and six pupils worked in two small groups.

**Support:**

- Case — A teacher–pupil interaction: A teacher helped a pupil choose a background colour for game cards.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:Y.

### 63. Potari, Despina; Psycharis, Giorgos; Sakonidis, Charalampos; Zachariades, Theodossios (2019). Collaborative Design of a Reform-Oriented Mathematics Curriculum: Contradictions and Boundaries across Teaching, Research, and Policy. *Educational Studies in Mathematics*. https://doi.org/10.1007/s10649-018-9834-3

**Study design:** Qualitative activity-theory case study of curriculum design.

**Setting:**

- Report: The context was a national mathematics curriculum reform in compulsory education in Greece.

**Participants:**

- Report: The curriculum design team involved teachers, academic researchers and policy-makers.

**Support:**

- Report: The coordinator brought educational policy products to the design team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:Y.

### 64. Jason D. Christopher; Michael L. Anderson; Ioan I. Feier (2024). Collaborative Senior Design Capstone at Two Geographically Separated Universities. *ASEE Computers in Education*. https://doi.org/10.18260/b259-8e-38724

**Study design:** Descriptive mixed survey with qualitative open responses.

**Setting:**

- Report — Three distributed engineering capstone teams: Three year-long mechanical engineering capstone design projects involving students at two geographically separated universities and three Department of Defense project sponsors. Note: Practice-connected engineering design context; projects differ.

**Participants:**

- Report — Three distributed engineering capstone teams: Three student teams and three sponsors. Table 1 totals 12 USAFA and 6 BYU students (18), while the Limitations section states 17 students; the discrepancy is unresolved. The student response rate is reported as 88% after the preliminary design review and 47% after the later two milestones, but the Limitations section gives a maximum of 87%; question-specific response counts are not reported. Note: Preserves discrepancies in original rather than determining a single total or calculating survey denominators.

**Support:**

- Report — Three distributed engineering capstone teams: Faculty provided and promoted digital tools for remote collaboration, including Microsoft Teams, a whiteboard tool and collaborative CAD software. Note: Specific faculty provision rather than title alone; no claim that each tool was independently effective.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 65. Maria Paasivaara; Casper Lassenius (2014). Communities of practice in a large distributed agile software development organization – Case Ericsson. *Information and Software Technology*. https://doi.org/10.1016/j.infsof.2014.06.008

**Study design:** qualitative longitudinal case study.

**Setting:**

- Report: An Ericsson organization with 400 people in 40 Scrum teams across three sites.

**Participants:**

- Report: The study collected data from 52 semi-structured interviews at two sites.

**Support:**

- Case — Scrum Master community of practice: Participants in the Scrum Master community of practice discussed team challenges and tried to find solutions together.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 66. Brad Morse; Marvyn Allen; Lisa M. Schilling; Andrey Soares; Kristen DeSanto; Brooke Dorsey Holliman; Rita S. Lee; Bethany M. Kwan (2023). Community Engagement in Research and Design of a Transgender Health Information Resource. *Applied Clinical Informatics*. https://doi.org/10.1055/s-0043-1763290

**Study design:** Qualitative engagement process analysis.

**Setting:**

- Report: The work took place at the University of Colorado Anschutz Medical Campus, including the Strauss Health Sciences Library.

**Participants:**

- Report: The community advisory board included 20 individuals.

**Support:**

- Case — Initial kick-off meeting: The team used a Purpose-to-Practice exercise to define how the community advisory board would collaborate with the research team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- End-of-project advisory board participation engagement survey: tool not applicable. The PEIRS survey reports an aggregate engagement score at the end of one project, with community and research members included, without a reported exposure-outcome comparison. The reviewed revised JBI analytical cross-sectional and quasi-experimental tools are not applicable to this descriptive survey result. This concerns the survey only and does not supersede the qualitative appraisal. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is a single-project, pooled engagement score; the existing assessment does not identify a target-population prevalence estimate. The mixture of community and research members is relevant when interpreting the aggregate; the record does not establish subgroup differences. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 67. Noora Al-Thani; Zubair Ahmed; Jolly Bhadra (2025). Concurrent training and reflection model (CTRM) for in-service teachers. *Frontiers in Education*. https://doi.org/10.3389/feduc.2025.1583071

**Study design:** Qualitative evaluation component of mixed-methods training study.

**Setting:**

- Report: Teachers from public schools in Qatar.

**Participants:**

- Report: Seventeen teachers participated in the training program.

**Support:**

- Report: The research team offered mentorship, feedback and troubleshooting support through concurrent follow-up sessions.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.


**Part-specific limitations and assessment status:**

- Pre-post teacher self-reported research knowledge total in Table 4: outside appraisal scope. The questionnaire assesses the 17 teachers who each supervised student groups. The main article does not establish whether the teachers are members of the student design teams. This teacher-level result is recorded in the existing description but was not added to the team-outcome appraisal because that relationship could not be established. This does not determine that the result is irrelevant or that the article as a whole is outside scope.

### 68. Janie Roberson; Allison Wrenn; John Poole; Andrew Jaeger; Isam A. Eltoum (2013). Constructing a modern cytology laboratory: A toolkit for planning and design. *CytoJournal*. https://doi.org/10.4103/1742-6413.107983

**Study design:** Practice-based laboratory relocation account.

**Setting:**

- Case — UAB cytology relocation: The University of Alabama at Birmingham cytology laboratory planned a relocation.

**Participants:**

- Case — Laboratory design project: Laboratory staff, architects and engineers contributed to the design process.

**Support:**

- Case — Laboratory work explanation: Tours and process-flow diagrams informed architects and engineers about daily laboratory work.

**JBI appraisal**

**Selected items only:** Q. Part: Laboratory tours and process diagrams used to explain work to designers. Design recorded: Practice-based laboratory relocation account.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Laboratory tours and process diagrams used to explain work to designers: not assessable. The article reports a practice-based construction account but does not specify a separate qualitative methodology or participant data analysis for the selected learning account.

### 69. Melissa M. Norberg; Ronan D. King; Alexis Muller; Ann T. Gregory; Jessica Hannah; Jane Neville; Coralie Roll; Catherine Sarre (2025). Consumer co-design as a framework for enhancing a novel self-guided online program to reduce overconsumption. *Journal of Contextual Behavioral Science*. https://doi.org/10.1016/j.jcbs.2025.100930

**Study design:** Qualitative component of mixed methods co-design evaluation.

**Setting:**

- Report: Consumers and researchers collaboratively revised the program over five workshops.

**Participants:**

- Report: Five consumer advisors brought lived experience of distress about overconsumption.

**Support:**

- Report: The lead author facilitated each workshop.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- PPEET ratings and observer AIUROS tallies about the co-design group experience: tool not applicable. The existing description reports consumers feeling heard and valued and two observer-perceived dismissive responses. The paper presents PPEET responses and AIUROS tallies as descriptive data on the workshop experience; these ratings do not specify an exposure-outcome association or independent comparison for the available analytical cross-sectional or quasi-experimental checklists. This does not decide whether another descriptive-study appraisal tool could be appropriate or assess the earlier unrelated programme trial; the qualitative feedback is appraised separately. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component combines participant experience ratings and observer tallies for a co-design group; the existing assessment does not identify a target-population prevalence estimate. Participant and observer reports use different sources and must remain distinguishable; no disagreement between the two is presumed. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 70. Nathan Davies; Megan Armstrong; Jennifer S. Pigott; Danielle Nimmons; Joy Read; Benjamin Gardner; Bev Maydon; Anette Schrag; Kate Walters (2024). Co‐Design of a Facilitated Self‐Management Toolkit for People With Parkinson's Disease. *Health Expectations*. https://doi.org/10.1111/hex.70104

**Study design:** Iterative toolkit co-design with think-aloud user tests.

**Setting:**

- Report — Toolkit co-design: Co-design included health and care professionals from community and hospital settings in the Greater London region.

**Participants:**

- Case — Prototype user testing: Not reproduced because of quotation or overlap with source text.

**Support:**

- Case — Think-aloud testing: Users vocalized their thoughts while performing prototype tasks.

**JBI appraisal**

**Selected items only:** Q. Part: Think-aloud testing and its reported influence on toolkit iterations. Design recorded: Iterative toolkit co-design with think-aloud user tests.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Think-aloud testing and its reported influence on toolkit iterations: not assessable. The report states that user testing informed iterations but does not describe a sufficiently detailed qualitative analysis or specific changes for a full checklist.

### 71. Vosz, Meaghan; Hughes, Mark; Cartwright, Colleen (2026). Co‐Design to Improve Palliative Care for LGBTIQ+ People: Evaluating the Development of eLearning. *Health & Social Care in the Community*. https://doi.org/10.1155/hsc/5532573

**Study design:** Critical-participatory qualitative process evaluation.

**Setting:**

- Report: The national project involved co-design team members from multiple Australian states.

**Participants:**

- Report: Interviews were conducted with eight co-design team members.

**Support:**

- Report: The team was facilitated by an employee acting as project lead and co-design facilitator.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 72. Melody Taba; Julie Ayre; Kirsten McCaffery; Diana Vassilenko; Ivan C. K. Ma; Tara Haynes; Julie Leask; Andrew Wilson; Carissa Bonner (2025). Co‐Designing a Framework for Social Media Health Communication to Young People: A Participatory Research Study. *Health Expectations*. https://doi.org/10.1111/hex.70203

**Study design:** Participatory action research with qualitative co-design workshops.

**Setting:**

- Report — Youth co-design workshops: Youth workshops were held in person and the professional stakeholder workshop was held online.

**Participants:**

- Report — Youth workshops: Twenty-one young people participated across two youth workshops.

**Support:**

- Case — Workshop live illustration: Participants gave a professional illustrator feedback on an evolving workshop graphic.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:U.

### 73. Kernot, Joclyn; Kiriam, Shoshannah; Seekamp, Sarah; Little, Kate; Hunt, Kellie; Lister, Erin; Maher, Carol; Brinsley, Jacinta (2026). Co‐Designing Wellbeing Initiatives With Rural Adolescents: What Works, What Doesn't, and Why. *Health Promotion Journal of Australia*. https://doi.org/10.1002/hpja.70221

**Study design:** Qualitative component of participatory mixed methods evaluation.

**Setting:**

- Report: Kimba, South Australia.

**Participants:**

- Report: The abstract reports 20 participants: 13 young people and seven adults (physical PDF page 1). The Results section reports nine young people and lists eight adults: three OTK staff, two teachers, two council staff and one parent (physical PDF page 5). These counts cannot be reconciled from the text reviewed. Note: The abstract and Results section report conflicting participant compositions; both passages are retained, and the discrepancy is unresolved.

**Support:**

- Case — Workshop 1: Facilitators used video to introduce an overview of wellbeing.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 74. Kimberly Bediako; Ashton Margarete Moseley; Pia McFindlay (2025). Critical Pedagogy and Intersectionality: The Interdisciplinary Development of a Transformative Learning Board Game in Design Higher Education. *The International Journal of Design Education*. https://doi.org/10.18848/2325-128x/cgp/v19i02/137-156

**Study design:** Critical participatory action research qualitative educational project.

**Setting:**

- Report — Whole reported project: An interdisciplinary second-year design project in higher education in Johannesburg, South Africa. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Second-year students in fashion and industrial design participated as co-researchers. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Lectures introduced students to critical and speculative design and to the intersectionalities of gender. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.

### 75. Ian C. Odland; Joseph Borrello; Layla Fattah; Tyree D. Williams; Kevin D. Costa; David Putrino; Brian Nickerson; Holly Oemke; Turner Baker; James McKay; Dov B. Shamir; Juan Quijano; Janice Gabrilove (2025). Design and implementation of a Targeted HealthcaRe InnoVation & Entrepreneurship (THRIVE) fellowship program. *PLOS One*. https://doi.org/10.1371/journal.pone.0328153

**Study design:** Descriptive post-program questionnaire within a retrospective program evaluation.

**Setting:**

- Report — THRIVE 2022–2023 fellowship cohort: A Mount Sinai healthcare technology innovation and entrepreneurship fellowship in New York, United States.

**Participants:**

- Report — THRIVE 2022–2023 fellowship cohort: The program formed five interdisciplinary teams of three to five fellows with three mentors.

**Support:**

- Report — THRIVE 2022–2023 fellowship cohort: Faculty mentors supported teams with expertise and prototyping-related synthesis; program mentors helped with project challenges.

**JBI appraisal**

**Selected items only:** P. Part: End-of-program ratings of fellows’ experience with faculty and program mentors. Design recorded: Descriptive post-program questionnaire within a retrospective program evaluation.


**Selected items:** 1:U; 2:U; 3:U; 4:Y; 5:U; 6:U; 7:U; 8:U.


**Part-specific limitations and assessment status:**

- End-of-program ratings of fellows’ experience with faculty and program mentors.: tool not applicable. The selected result is a post-program mean rating, not a prevalence estimate or isolated pre-post effect; selected items concern sample, measurement and analysis.

### 76. Lee, Kung Jin; Martin, Caitlin Kennedy; Björling, Elin A.; Rubio, Juan; McLean, Ryan; Lee, Jin Ha (2026). Design cookbook card deck in facilitating effective co-design in library contexts. *Journal of Librarianship and Information Science*. https://doi.org/10.1177/09610006241307385

- Bibliographic note: the source record lists 2025; the journal year above follows the verified PDF.

**Study design:** Qualitative component of mixed-methods co-design case study.

**Setting:**

- Report — Whole reported project: Three co-design teams worked in public libraries in the United States. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The project involved librarians and teens, with researchers also contributing reflections. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A customized card deck supported discussion and programming on teen mental health in the libraries. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:Y.

### 77. Connor T. Dodd; Marc T. P. Adam; Samantha J. Stewart; Janelle L. Windus; Megan E. Rollo (2024). Design of a Semi-Automated System for Dietary Assessment of Image-Voice Food Records. *IEEE Access*. https://doi.org/10.1109/access.2024.3505199

**Study design:** Design science co-design, formative feedback component.

**Setting:**

- Report — VISIDA CMS co-design: Interdisciplinary research project developing a web-based dietary assessment system, with collaborators working in-country and remotely. Note: Context concerns the CMS development team, rather than dietary-record respondents.

**Participants:**

- Report — VISIDA CMS co-design: Researchers from nutrition and computing collaborated; the team included eventual system users, identified as Australian research dietitians. Team size is not reported. Note: The 178 individuals providing dietary data are not the development team.

**Support:**

- Report — VISIDA CMS co-design: Research dietitians and nutrition stakeholders evaluated prototypes and shared practical input during iterative development and after using the system. Note: Support refers to expert feedback informing system development, not the system assisting dietary-data users.

**JBI appraisal**

**Selected items only:** Q. Part: Formative user testing and stakeholder feedback during development. Design recorded: Design science co-design, formative feedback component.


**Selected items:** 7:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Summative evaluation of automated food-item matching performance: tool not applicable. The reported result assesses agreement of automated suggestions with analyst-selected entries; it does not establish an exposure-outcome cross-sectional study or intervention comparison. The currently registered analytical cross-sectional and quasi-experimental JBI tools do not directly fit. This status does not appraise other components.
- Formative user testing and stakeholder feedback during development: not assessable. The article reports iterative co-design and feedback-informed changes but does not describe a distinct qualitative data collection and analysis procedure in sufficient detail for a full qualitative JBI checklist. Lack of reporting is not proof that a procedure did not occur. Scope is this component only.

### 78. Lawson, Hal A.; Anderson-Butcher, Dawn; Petersen, Nancy; Barkdull, Carenlee (2003). Design Teams as Learning Systems for Complex Systems Change: Evaluation Data and Implications for Higher Education. *Journal of Human Behavior in the Social Environment*. https://doi.org/10.1300/j137v07n01_11

- Bibliographic note: the PDF title above differs from the source-record title.
- PDF bibliographic note: The publisher-added cover lists a shorter title; the article title page includes the subtitle shown above.

**Study design:** Qualitative interviews and facilitator action research.

**Setting:**

- Report — Whole reported project: A four-state child-welfare and cross-sector initiative used collaborative design teams. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Twenty-two long-standing design-team members were interviewed, including university facilitators and family, child-welfare and other service-system representatives. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Faculty facilitators were assigned to the design teams to help develop and evaluate them. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 79. David Marcus; Amanda Simone; Lauren Block (2020). Design thinking in medical ethics education. *Journal of Medical Ethics*. https://doi.org/10.1136/medethics-2019-105989

- PDF bibliographic note: Published journal brief report; online supplementary material not examined

**Study design:** Inductive thematic analysis of open-ended student survey responses; Uncontrolled before and after session survey.

**Setting:**

- Report — 2017–2018 ethics workshop: First-year ethics curriculum at one US medical school.

**Participants:**

- Report — 2017–2018 ethics workshop: Body results report 102 first-year medical students in the 2017–2018 workshop; the abstract reports 100.

**Support:**

- Report — 2017–2018 ethics workshop: A guide provided design-thinking instructions and faculty and guests guided students and answered questions during teams of five.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Inductive thematic analysis of open-ended student survey responses.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.


**Full checklist:** QE. Design recorded for the assessment: Uncontrolled before and after session survey.


**Outcome: Students’ self-reported understanding of the current liver allocation system:** 5:N; 6:U; 7:U.

**Outcome: Students’ self-reported understanding of the current liver allocation system; result: 1–5 self-rating mean before vs after the whole session (2.3 vs 3.7, p<0.01):** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:U; 4:N.

### 80. Christine M. Kava; Jeffrey R. Harris; Michelle Strait; Margaret Winch; Noah Pylvainen; Peggy A. Hannon (2025). Design Workgroups: An Approach to Adapting Evidence-Based Health Interventions. *Journal of Public Health Management and Practice*. https://doi.org/10.1097/phh.0000000000002282

- Bibliographic note: the PDF title above differs from the linked-item title.

**Study design:** Descriptive practice-based workgroup evaluation.

**Setting:**

- Report — Whole reported project: A virtual design workgroup adapted tobacco-control resources for a workplace wellness program. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The workgroup recruited employers, employees, and health department staff. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A research team and consulting and communications firm cofacilitated the workgroup meetings. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.


**Part-specific limitations and assessment status:**

- Final anonymous survey on feedback incorporation and meeting process: tool not applicable. The final workgroup evaluation was an anonymous, one-time 28-item questionnaire completed during the fifth meeting, rather than an exposure-outcome association or a pre/post comparison. The main report describes a purposeful group of 13 members, including employees, employers and health-department staff (physical page 3); approximately 10 of 13 completed the survey, and 90% of respondents reported their feedback was incorporated well or very well and, separately, endorsed the workgroup process statements including meeting productivity (page 9). The initial participant composition and recruitment are described, and respondents are the survey completers, not necessarily all 13 members; some employees stopped attending and replacements were recruited (pages 3 and 9). Assessable aspects informed by the 2014 JBI prevalence checklist, not a formal full checklist assessment: item 4, context and members described: Yes for the workgroup, but the roles of survey respondents are not reported; item 5, coverage: Unclear because completion is approximate and item-specific missingness is not stated; items 6 and 7, outcome measurement: Unclear because the questionnaire was developed with CRNW based on previous evaluation work, but validity and reliability are not reported in the examined main paper (page 6); item 8, analysis: the authors state that survey responses were summarised in Excel (page 8), but the exact respondent counts underlying each reported percentage are not given, so precision and reproducibility are limited. The two 90% findings are distinct descriptions and do not establish an effect of any individual facilitation practice. Revised JBI analytical cross-sectional and quasi-experimental scales do not match this one-time descriptive survey, and full application of the prevalence tool is not claimed because a wider target-population prevalence estimate is not identified. The separate group-discussion qualitative JBI assessment remains unchanged; visual examination of all cited pages was performed, and the page-9 supporting quotation was additionally matched to the text layer.

### 81. Angeline Baldapan Elegio (2026). Design-Led Innovation and Triple-Helix Collaboration for MSME Product Development: The PROPEL Project in Bohol, Philippines. *Advances in Technology Innovation*. https://doi.org/10.46604/aiti.2026.15898

**Study design:** qualitative single case study.

**Setting:**

- Report — Whole reported project: The PROPEL product-development project was conducted in Bohol, Philippines. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Industrial design students, faculty advisers, and micro, small and medium enterprises participated in product development. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Students and faculty advisers supplied structured design methods and technical refinement; government actors coordinated institutional linkages. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:U; 9:U; 10:U.

### 82. Johannes Matschewsky; Marianna Lena Kambanou; Tomohiko Sakao (2017). Designing and providing integrated product-service systems – challenges, opportunities and solutions resulting from prescriptive approaches in two industrial companies. *International Journal of Production Research*. https://doi.org/10.1080/00207543.2017.1332792

**Study design:** Qualitative multiple industrial case study.

**Setting:**

- Report — Whole reported project: Two Swedish industrial companies undergoing transition to integrated product-service systems. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Respondents in the two case companies included participants with different functions and backgrounds. Note: The cited passage directly supports this description.

**Support:**

- Case — Navitas case: At Navitas, management created a PSS facilitator position to organize greater cooperation between product and service design. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 83. Sangiorgi, Daniela (2015). Designing for public sector innovation in the UK: design strategies for paradigm shifts. *foresight*. https://doi.org/10.1108/fs-08-2013-0041

**Study design:** qualitative interview based field study.

**Setting:**

- Report — Whole reported project: An exploratory study of UK design agencies working in and for the public sector. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The study reports interviews with designers working at seven agencies. Note: The cited passage directly supports this description.

**Support:**

- Case — NHS Experience-Based Design exemplar: In one NHS service-improvement project, a patient and staff video was used in a co-design workshop to identify improvements. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 84. Kimberly Edginton Bigelow (2012). Designing for Success: Developing Engineers Who Consider Universal Design Principles. *Journal of Postsecondary Education and Disability*. [DOI not recorded]

**Study design:** Descriptive student-attribution account within a mixed-methods educational study.

**Setting:**

- Case — University design-course project: A first-year engineering design course at the University of Dayton.

**Participants:**

- Report — Two course sections: Forty-eight first-year engineering students participated across two course sections.

**Support:**

- Case — Accessibility panel: Four guest speakers shared insights relevant to the redesign project.

**JBI appraisal**

**Selected items only:** Q. Part: Students’ reported attribution of their design direction to the universal-design guest panel. Design recorded: Descriptive student-attribution account within a mixed-methods educational study.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Students’ reported attribution of their design direction to the universal-design guest panel.: tool not applicable. The paper uses mixed methods to compare team decision matrices, but the specific claim about what students said of the panel is a descriptive attribution without a separately specified qualitative procedure for that claim.

### 85. Kathryn Hymes; Jessica Hammer; Hakan Seyalioglu; Carol Dow-Richards; Deidra Brown; Trish Hambridge; Jill Ventrice; Meguey Baker; Yeonsoo Julian Kim; Tim Hutchings; William S. Evans (2021). Designing Game-Based Rehabilitation Experiences for People with Aphasia. *Proceedings of the ACM on Human-Computer Interaction*. https://doi.org/10.1145/3474697

**Study design:** Qualitative participatory game design with interviews and reflective thematic analysis.

**Setting:**

- Report — Whole reported project: Remote co-design of games for people with aphasia. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The co-design group brought together people with aphasia, speech-language pathologists, game designers and the director of an aphasia nonprofit. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Workshop communication support included slowed speech and writing. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:U; 10:Y.

### 86. Susanna Nordin; Aaron Davis; France Légaré; Allyson Jones; Louise Meijering; Marie Elf (2026). Designing Meaningful Engagement for Older Adults: An Evaluation of Participation in a Five‐Day Co‐Design Sprint. *Health Expectations*. https://doi.org/10.1111/hex.70555

**Study design:** Qualitative case study of participant experience in an online design sprint.

**Setting:**

- Report — Whole reported project: A wholly online co-design sprint recruited participants from across Sweden. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The sprint included 10 older adults, four healthcare professionals, and four technology and architecture professionals. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A professional facilitator experienced with digital services for older adults helped the project team plan the co-design process. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 87. Johansen, Kelsey M.; Konu, Henna (2026). Designing transformative nature-based wellbeing tourism experiences: a case study from the Finnish Lakeland Region. *Tourism Recreation Research*. https://doi.org/10.1080/02508281.2024.2443983

- Bibliographic note: the source record lists 2025; the journal year above follows the verified PDF.

**Study design:** qualitative exploratory case study.

**Setting:**

- Report — Whole reported project: A tourism business and Japanese partners co-designed wellbeing tourism experiences in southeastern Finland. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The case involved SaimaaLife and its Japanese collaborators, including the Japanese Elämä Project and EcoConscious Japan. Note: The cited passage directly supports this description.

**Support:**

- Case — EcoConscious Japan ekotri sharing sessions: The Japanese partner uses post-trip sharing sessions for purposes including co-designing tours. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 88. Hill, Jordan R; Ganci, Aaron; Campbell, Noll L; Pickett, Andrew C; Chui, Michelle A; Abebe, Ephrem; Holden, Richard J (2026). Developing mHealth IT for Older Adult Medication Safety: Remote Participatory Co-Design Using the RAPID Method. *JMIR Human Factors*. https://doi.org/10.2196/82366

**Study design:** Qualitative practice-based co-design reflections.

**Setting:**

- Report — Whole reported project: Remote participatory design concerning medication safety with participants recruited from a US pharmacy chain. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Two groups each included five participants: older adult pharmacy patients and pharmacy staff. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Each session was supported by three to four research-team members, including a lead facilitator. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:Y; 8:U; 9:Y; 10:Y.

### 89. Helen McLaren; Ros Wong; Emi Patmisari; Michelle Jones; Jane Fischer; Keren Sutton; Yasmin Sinclair (2025). Developing the Linker/Navigator Service Blueprint: Evaluating Domains of Power Following Concept Co‐Design Through to Readiness for Prototyping. *Health & Social Care in the Community*. https://doi.org/10.1155/hsc/8757146

**Study design:** Qualitative component of sequential mixed methods evaluation.

**Setting:**

- Report — Whole reported project: The Linker Service project addressed poverty in South Australia. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Living-experience consultants, NGO representatives, Wyatt employees, evaluators, and facilitators participated in the blueprint phase. Note: The cited passage directly supports this description.

**Support:**

- Case — Initial concept co-design workshops in 2022: A child carer supported parents in participating in the initial two-day co-design workshops. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.

### 90. Free Coulston; Alicia Spittle; Cassie McDonald; Rachel Toovey; Kate L. Cameron; Kimberley Attard; Loni Binstock; Isaac Fletcher; Adie Delaney; Tayla Murphy; Caroline Keating; Kath Sellick (2024). Development and Evaluation of a Framework for Authentic Online Co‐Design: Partnership‐Focussed Principles‐Driven Online Co‐Design. *Health Expectations*. https://doi.org/10.1111/hex.14138

**Study design:** Qualitative interviews within a convergent mixed methods study.

**Setting:**

- Report — Whole reported project: Eight online co-design workshops developed an intervention related to physical activity for children born extremely preterm. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The co-design group included end-users, coaches, clinicians and academics. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A researcher with prior co-design experience provided workshop facilitation support. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 91. Mursyidhan Ariefbillah A.M.; Royana Afwani; Ramaditia Dwiyansaputra; Akhmad Saufi (2024). Development of Android Based Halal Tourism Application For Travelers Using Scrum Method. *Journal of Information System Research (JOSH)*. https://doi.org/10.47065/josh.v5i4.5588

**Study design:** Software project account with sprint reviews and a separate usability survey.

**Setting:**

- Case — Tourism application project: Workshops at the Grand Madani Hotel informed the tourism application project.

**Participants:**

- Case — Application development: Academics and the development team took part in sprint reviews.

**Support:**

- Case — Sprint-3 product-owner review: Academics suggested a date-range selection for the order interface.

**JBI appraisal**

**Selected items only:** Q. Part: Sprint-3 product-owner advice and next-sprint improvement list. Design recorded: Software project account with sprint reviews and a separate usability survey.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Sprint-3 product-owner advice and next-sprint improvement list: not assessable. The source describes advice and planned improvements but does not state how the sprint-review narrative was systematically collected and analysed; the separate usability survey is not assessed here.

### 92. Julie M Pike; Courtney M Moore; Lisa G Yazel; Dustin O Lynch; Kathryn M Haberlin-Pittz; Sarah E Wiehe; Tamara S Hannon (2021). Diabetes Prevention in Adolescents: Co-design Study Using Human-Centered Design Methodologies. *JOURNAL OF PARTICIPATORY MEDICINE*. https://doi.org/10.2196/18245

**Study design:** Qualitative formative human-centred design.

**Setting:**

- Report — HCD co-design sessions: Study sessions were held in community and school settings.

**Participants:**

- Report — Four co-design sessions: The reported sessions included professionals, adolescents and parents.

**Support:**

- Case — Drawing activities: Research Jam facilitated the HCD sessions and used drawing activities.

**JBI appraisal**

**Selected items only:** Q. Part: Reported brainstorming during facilitated drawing activities. Design recorded: Qualitative formative human-centred design.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Reported brainstorming during facilitated drawing activities: not assessable. The full study uses qualitative HCD analysis, but the specific process claim is not linked to a distinct analytic procedure or participant account.

### 93. Audrey Guskey (2022). DIARY OF A SENIOR MARKETING PROFESSOR: ADVICE ON HOW TO GET THE MOST FROM STUDENT PROJECTS. *Global Journal of Business Pedagogy*. https://doi.org/10.47177/gjbp.06.01.2022.075

**Study design:** Exploratory qualitative observational and reflective report.

**Setting:**

- Report — Whole reported project: A new product development project was embedded in an introduction to marketing course. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Student groups invented a product or service and developed a marketing plan. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Students received a detailed assignment sheet describing the required presentation and paper. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Proposed before-and-after evaluation of student learning: result not reported. The article proposes measuring student learning before and after the project as future research. It does not report that this proposed pre-post comparison was carried out or provide its result. This status concerns only the proposed comparison; it does not override the previously appraised student self-critiques and teaching observations.

### 94. April Savoy; Himalaya Patel; Umber Shahid; Alexis D Offner; Hardeep Singh; Traber D Giardina; Ashley N D Meyer (2022). Electronic Co-design (ECO-design) Workshop for Increasing Clinician Participation in the Design of Health Services Interventions: Participatory Design Approach. *JMIR Human Factors*. https://doi.org/10.2196/37313

**Study design:** Participatory design case study of online clinician workshops.

**Setting:**

- Report — Whole reported project: Virtual clinician co-design workshops developed interventions to improve test-result management. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Twenty-eight clinicians attended the workshop. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Breakout sessions had experienced facilitators, with another facilitator recording, taking notes and monitoring chat. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.

### 95. Dr. Warda Gul; Prof. Dr. Mohyuddin Tahir Mahmood; Mishal Hasnain Naqvi (2026). Emotional Resilience and Team Performance in Hybrid Agile Fintech Startups in Punjab, Pakistan. *Social science review archives.*. https://doi.org/10.70670/sra.v4i1.2329

**Study design:** Constructivist grounded-theory interview and observation study.

**Setting:**

- Report — Whole reported project: Hybrid Agile fintech startups in Punjab, Pakistan. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The interview sample comprised 27 participants. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Leaders used traffic-light polls during stand-ups, with members indicating their state using coloured emojis. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:U; 4:U; 5:U; 6:Y; 7:U; 8:U; 9:Y; 10:U.


**Part-specific limitations and assessment status:**

- Traffic-light-poll use and timing of stressor identification: not assessable. The article reports a 2.3-day difference but does not specify the comparison sample, measurement of discovery time or timing sufficiently to establish a quantitative design and appropriate checklist.

### 96. Fay O'Donoghue; Máire T O'Donnell; Tomás P. Griffin; Eileen Fahy; Elaine Newell; Ann‐Marie Creaven (2025). Enablers and Barriers to an Experience‐Based Co‐Design Process to Develop Service Improvements in Enhanced Community Care in Ireland: A Qualitative Study. *Health Expectations*. https://doi.org/10.1111/hex.70206

**Study design:** Qualitative thematic process evaluation.

**Setting:**

- Report — Whole reported project: The study was situated in Ireland’s Enhanced Community Care programme. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Seventeen service users and staff took part at two sites. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A document helped service users prepare accounts of their care experiences before the first session. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 97. Bowen, Simon; Sustar, Helena; Wolstenholme, Daniel; Dearden, Andy (2013). Engaging teenagers productively in service design. *International Journal of Child-Computer Interaction*. https://doi.org/10.1016/j.ijcci.2014.02.001

**Study design:** Qualitative research through design action research case study.

**Setting:**

- Report — Whole reported project: Family support groups in South Yorkshire, UK participated in a diabetes service-design project. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Ten young people with diabetes participated in the project. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Three designers acted as facilitators in a series of workshops. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:U; 9:U; 10:Y.

### 98. Martiyana, Linda; Indriyani , Tuti; Zas Pendi, Hamdi (2026). ENTREPRENEURSHIP MANAGEMENT IN ENHANCING STUDENT CREATIVITY AT STATE VOCATIONAL HIGH SCHOOL. *Edukasi Islami Jurnal Pendidikan Islam*. [DOI not recorded]

**Study design:** Qualitative descriptive study of school entrepreneurship programme.

**Setting:**

- Report — Whole reported project: An entrepreneurship program in a public vocational high school in Muaro Jambi. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Twelve participants included a school principal, three entrepreneurship teachers, and eight vocational students. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: The school provided students with entrepreneurship training and workshops. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:N; 9:U; 10:N.

### 99. Roisin Donnelly; Terry Maguire (2020). Establishing and sustaining national partnerships in professional development and the recognition of open courses in teaching and learning through digital badges. *Australasian Journal of Educational Technology*. https://doi.org/10.14742/ajet.5892

**Study design:** Qualitative case study of national course-development partnership.

**Setting:**

- Report — Whole reported project: An Irish higher-education initiative developed badged professional-development courses. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The course-development partnership included lead developers of professional-development courses. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: The National Forum supported course developers through workshops and an online collaborative space. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 100. Wakeling, Simon; Garner, Jane; Hider, Philip; Godfrey, Annie; Jamali, Hamid R. (2026). Evaluating the Effectiveness of a Public Library Codesign Workshop Process. *Journal of the Australian Library and Information Association*. https://doi.org/10.1080/24750158.2025.2540229

- Bibliographic note: the source record lists 2025; the journal year above follows the verified PDF.

**Study design:** Qualitative thematic analysis of interviews field notes and free-text workshop feedback.

**Setting:**

- Case — Library One codesign workshops: The workshops were held onsite at participating libraries.
- Report — Whole report: Two public library spaces were co-designed in two series of three workshops. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Library One codesign workshops: Community members and library and council staff participated in Library One.
- Report — Whole report: The workshops included members of the public and library and council staff at both sites. Note: The cited Library One total is 12, while the stated categories sum to 13; no total is adopted in the value.

**Support:**

- Case — Library One codesign workshops: A facilitator prompted the community group to move its plan into the library space to help visualisation.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Descriptive participant ratings of contribution and collaboration after library workshops: tool not applicable. The existing review descriptions concern participation and decision making at both library sites. The paper also summarises post-workshop survey ratings of ability to contribute and work collaboratively. These are descriptive responses pooled across workshops, not an identified exposure-outcome association or independent comparison for the available analytical cross-sectional or quasi-experimental tools; repeated responses from the same participants cannot be excluded. This status concerns the descriptive survey ratings, not the separately appraised observations and interviews or every possible quantitative result. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is pooled post-workshop participation and collaboration ratings; the existing assessment does not identify a target-population prevalence estimate. The existing assessment notes that repeat responses by the same participant cannot be excluded. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 101. Hatcher, Gillian; Ion, William; Maclachlan, Ross; Marlow, Marion; Simpson, Barbara; Wodehouse, Andrew (2018). Evolving improvised ideation from humour constructs: A new method for collaborative divergence. *Creativity and Innovation Management*. https://doi.org/10.1111/caim.12256

**Study design:** Sequential workshops method development; Workshop based action research qualitative component.

**Setting:**

- Case — Design improv workshop 4: The fourth workshop used a small meeting room with seating.
- Report — Whole report: A series of workshops explored and developed humour-based approaches to design ideation. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Design improv workshop 4: Four product design undergraduates participated in workshop 4.
- Report — Whole report: Workshop participants included students, professional humourists and engineering practitioners. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Design improv workshop 4: From workshop 4, the facilitator took responsibility for switching between Yes And and If Then.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Workshop based action research qualitative component.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:Y; 8:U; 9:U; 10:Y.


**Full checklist:** QE. Design recorded for the assessment: Sequential workshops method development.


**Outcome: Group ideas generated per minute from recorded workshop discussions:** 5:N; 6:U; 7:U.

**Outcome: Group ideas generated per minute from recorded workshop discussions; result: Descriptive comparison of aggregate idea-generation rate in development workshop 3 and workshop 4:** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:U; 4:N.

### 102. Masharipova, A.V.; Derbissalina, G. A.; Zhunussova, D. K.; Nagashybek, G.; Amangeldiyeva, D. (2022). Experience in using the service design in the development of nursing services in the republic of Kazakhstan. *THE NEW ARMENIAN MEDICAL JOURNAL*. https://doi.org/10.56936/18290825-2022.16.3-43

**Study design:** Descriptive service-design case.

**Setting:**

- Report — Service-design experience: The report describes service-design training in Kazakhstan and a subsequent nursing-service project at a private medical centre in Astana. Note: The training and subsequent project are distinguished; the Astana project is not treated as the location of all training activity.
- Case — Astana Medical University service design project: The team conducted its study at a private medical centre.

**Participants:**

- Report — Project team and intended interview groups: The Astana project team included university academic staff, graduate students and two practising nurses; the planned interviews targeted ten patients and ten nurses. Note: The interview targets are planned numbers, not established completed interviews or a total count of unique project participants.
- Case — Astana Medical University service design project: The project involved academic staff, graduate students and two practising nurses.

**Support:**

- Case — Astana Medical University service design project: Group discussions in online conferences facilitated information exchange.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 103. Vermeulen, Joan; Verwey, Renée; Hochstenbach, Laura MJ; van der Weegen, Sanne; Man, Yan Ping; de Witte, Luc P (2014). Experiences of Multidisciplinary Development Team Members During User-Centered Design of Telecare Products and Services: A Qualitative Study. *Journal of Medical Internet Research*. https://doi.org/10.2196/jmir.3195

**Study design:** Qualitative interview study across four development teams.

**Setting:**

- Case — Four telecare research and development projects: The study ran alongside four research and development projects.
- Report — Whole report: The study examined four research and development projects developing telecare products and services. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Four telecare research and development projects: Twenty-five core members were identified across the four projects.
- Report — Whole report: Twenty-five core members across the projects included end users, engineers, managers and researchers. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Four telecare research and development projects: Researchers visited team members at home or work to provide information or updates.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:Y.

### 104. Wheeler, Bella; Williams, Oli; Meakin, Becki; Chambers, Eleni; Beresford, Peter; O’Brien, Sarah; Robert, Glenn (2024). Exploring Elinor Ostrom's principles for collaborative group working within a user-led project: lessons from a collaboration between researchers and a user-led organisation. *Research Involvement and Engagement*. https://doi.org/10.1186/s40900-024-00548-4

**Study design:** Participatory observation interviews and joint reflection.

**Setting:**

- Case — Inclusive Involvement Movement project: The IIM group co-designed services intended to increase Disabled people’s inclusion in decision-making.
- Report: The report examines a collaboration between academic researchers and a user-led organisation on co-design of services to support Disabled people’s inclusion.

**Participants:**

- Case — Inclusive Involvement Movement project: The IIM project group had seven members from Shaping Our Lives and one staff member.
- Report — Whole report: The project involved an IIM co-design group and a study group of academic researchers and Shaping Our Lives representatives. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Inclusive Involvement Movement project: Group members used Principle 2 to consider payment and reward for the mentor role.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 105. Víctor Alonso-Prieto; Yannis Dimitriadis; Sara Lorena Villagrá-Sobrino; Alejandro Ortega-Arranz; Paraskevi Topali; Alejandra Martínez-Monés (2025). Exploring How Teacher Agency Unfolds Within the Co-design of a Smart Learning Environment-Supported Learning Activity: A Case Study. *Journal of Information Technology Education Research*. https://doi.org/10.28945/5615

**Study design:** Qualitative interpretive single case component with interviews and observed co-design.

**Setting:**

- Report: The single-case study took place in an undergraduate school organisation course at a Spanish university.
- Case — SCARLETT-supported course activity: The study took place during an undergraduate course at a Spanish university.

**Participants:**

- Report: The co-design involved the course teacher, a lead researcher and two co-researchers; the course had 71 first-year kindergarten pre-service teachers. The co-design team and course enrollment are distinct.
- Case — SCARLETT-supported course activity: The study involved the course teacher, a lead researcher and two co-researchers; the course included 71 first-year kindergarten pre-service teachers.

**Support:**

- Case — SCARLETT-supported course activity: A beta-testing session familiarised the teacher with the system interface and dashboard.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:Y.

### 106. Erin Hurley; Jakob Trischler; Timo Dietrich (2018). Exploring the application of co-design to transformative service research. *Journal of Services Marketing*. https://doi.org/10.1108/jsm-09-2017-0321

**Study design:** qualitative co-design workshops with descriptive comparisons.

**Setting:**

- Case — Alcohol education co-design sessions: Two co-design sessions were conducted in a restaurant.
- Report — Whole report: Two co-design sessions developed ideas for alcohol education programmes for parents. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Alcohol education co-design sessions: Twenty-four people participated across the two sessions.
- Report — Whole report: The two sessions involved 24 participants, including parents. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Alcohol education co-design sessions: A facilitator asked participants to review activity cards and started a discussion.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 107. Mariam El Mezouar; Daniel Alencar da Costa; Daniel M. German; Ying Zou (2021). Exploring the Use of Chatrooms by Developers: An Empirical Study on Slack and Gitter. *IEEE Transactions on Software Engineering*. https://doi.org/10.1109/tse.2021.3109617

**Study design:** Comparative cross-sectional survey of chatroom users; Qualitative survey and follow-up interviews in mixed-methods study.

**Setting:**

- Report — Slack and Gitter comparison: The report compares developer chatroom use in Slack and Gitter, including open communities and corporate teams. Note: Study-wide setting; open communities and corporate teams are not assumed to occur in identical proportions on each platform.
- Case — Slack and Gitter chatroom study: The study examined Slack and Gitter using surveys, interviews and repository data.

**Participants:**

- Case — Slack and Gitter chatroom study: The survey received 114 responses from Slack users and 48 from Gitter users.
- Report — Whole report: The main survey obtained 163 responses, followed by 21 interviews. Note: Slack and Gitter account for 162 responses; the 163rd response identified Discord. The 21 interviews are follow-up interviews, not additional survey respondents.

**Support:**

- Case — Slack and Gitter chatroom study: Interviewees reported that corporate teams used chatrooms for mentorship to help onboard new members.

**JBI appraisal**

**Full checklist:** CS. Design recorded for the assessment: Comparative cross-sectional survey of chatroom users.


**Outcome: Survey response coded as describing an impact of the chatroom on group awareness; not a direct measure of team awareness.:** 2:NA; 4:U; 6:N.

**Outcome: Survey response coded as describing an impact of the chatroom on group awareness; not a direct measure of team awareness.; result: Table 2 reports the group-awareness theme in 62% for Slack and 15% for Gitter, with column labels n=114 and n=48.:** 7:U.

**Study:** 1:Y; 3:Y; 5:Y; 8:Y.


**Full checklist:** Q. Design recorded for the assessment: Qualitative survey and follow-up interviews in mixed-methods study.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 108. Yin, Shengchen; Kasraian, Dena; Wang, Gubing; Van Wesemael, Pieter (2026). Facilitating children’s co-design workshops: insights and challenges from a case study. *CoDesign*. https://doi.org/10.1080/15710882.2026.2685869

**Study design:** Qualitative component of mixed methods case study.

**Setting:**

- Case — Rotterdam school workshop: The workshop involved students from a technical secondary school in Rotterdam.
- Report — Whole report: Children in a Rotterdam technical secondary school explored a nature path and co-designed digital game prototypes. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Rotterdam school workshop: Twenty-three children from one class participated.
- Report — Whole report: Twenty-three children participated; the teacher and two researchers acted as facilitators. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Rotterdam school workshop: Facilitators helped children focus on tasks and prompted them to expand and present their narratives.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Numerical ratings from children’s post-workshop feedback survey: tool not applicable. The article presents children’s satisfaction and toolkit ratings from a single feedback survey following one facilitated workshop, without reporting an analytical exposure-outcome comparison or a pre-post comparison. The reviewed analytical cross-sectional and quasi-experimental JBI scales therefore do not apply to this descriptive survey. The previously assessed qualitative observations and free-text material remain separate. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is post-workshop satisfaction and toolkit ratings; the existing assessment does not identify a target-population prevalence estimate. Participant selection and the number of responses relative to surveys sent are relevant to interpretation; the present status does not establish the response rate. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 109. Backåberg, Sofia; Strandberg, Susanna; Freeman, Georgina; Katz, Larry; Rafiei Milajerdi, Homa; Wylant, Barry; Oehlberg, Lora; Ekstedt, Mirjam (2025). Facilitating co-design among older adults in a digital setting: methodological challenges and opportunities. *CoDesign*. https://doi.org/10.1080/15710882.2024.2372595

- Bibliographic note: the source record lists 2024; the journal year above follows the verified PDF.

**Study design:** Qualitative methodological case reflection on co-design workshops.

**Setting:**

- Case — Swedish remote co-design cohort: Five online workshops were conducted with the Swedish cohort.
- Report — Whole report: Four online workshops were held with a Canadian cohort and five with a Swedish cohort. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Swedish remote co-design cohort: Each cohort included six older adults organised in three pairs.
- Report — Whole report: Two cohorts of older co-designers were recruited, one in Canada and one in Sweden; each comprised six people in three pairs. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Swedish remote co-design cohort: In the first Swedish workshop, a live mind map was visible after the break and at the end.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:Y; 8:Y; 9:Y; 10:U.

### 110. Saliba‐Gustafsson, Erika A.; Neufeld, Nicole S. Rodriguez; Hanson, Claudia; Chipeta, Effie Kondwani; Alvesson, Helle Mølsted (2026). Facilitators’ experiences of co-designing an intrapartum care intervention in four sub-Saharan African countries: a qualitative study. *BMJ Open*. https://doi.org/10.1136/bmjopen-2025-109931

**Study design:** qualitative interview study using reflexive thematic analysis.

**Setting:**

- Case — ALERT hospital co-design project: ALERT was launched in maternity units in four countries.
- Report — Whole report: ALERT was implemented in maternity units of 16 hospitals across Benin, Malawi, Tanzania and Uganda. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — ALERT hospital co-design project: Workshops involved maternity care providers, and birthing parents with companions.
- Report — Whole report: The qualitative study interviewed ten co-design facilitators working in the four countries. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — ALERT hospital co-design project: Facilitators shared interview findings and workshop discussions between the provider and parent groups.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 111. Alan B. Dogan; Janeline Wong; Katelyn Stebbins; Christopher Arena (2025). Feasibility of Integrating Medical Student Mentors into Undergraduate Biomedical Engineering Capstone Teams. *Biomedical Engineering Education*. https://doi.org/10.1007/s43683-025-00203-8

**Study design:** Analytical cross-sectional post-course survey.

**Setting:**

- Case — Biomedical engineering capstone mentoring: The setting was the senior design capstone program at Virginia Tech.
- Report — Whole report: The Virginia Tech capstone study compared mentorship led by faculty, by medical students, and by a mixed group. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Biomedical engineering capstone mentoring: Participants eligible for the study were senior biomedical engineering students in the 2024–2025 course.
- Report — Whole report: Of 66 enrolled students, 25 responded to the survey and 20 complete responses were analysed. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Biomedical engineering capstone mentoring: An engineering student reported receiving advice from medical students when the team had a problem or was unsure of project direction.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Respondent-reported project outcome satisfaction on a five-point scale:** 2:NA; 4:U; 6:N.

**Outcome: Respondent-reported project outcome satisfaction on a five-point scale; result: Mann–Whitney comparison of faculty-led and combined medical-student or mixed-led project outcome satisfaction U 24.5 p 0.77:** 7:U.

**Study:** 1:Y; 3:Y; 5:Y; 8:U.

### 112. Gilbuena, Debra M.; Sherrett, Benjamin U.; Gummer, Edith S.; Champagne, Audrey B.; Koretsky, Milo D. (2015). Feedback on Professional Skills as Enculturation into Communities of Practice. *Journal of Engineering Education*. https://doi.org/10.1002/jee.20061

- Bibliographic note: the source record lists 2014; the journal year above follows the verified PDF.

**Study design:** Qualitative ethnographic discourse analysis.

**Setting:**

- Case — Team B in the Virtual CVD project: Students worked on a virtual semiconductor process development project.
- Report — Whole report: The Virtual CVD project asked student teams to optimise an industrial-scale reactor for manufacturing. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Team B in the Virtual CVD project: Team B was one of four teams with three students each.
- Report — Whole report: Four teams of three students each participated in the study. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Team B in the Virtual CVD project: The coach guided Team B with questions about confidence in its calculations.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 113. Støre-Valen, Marit (2021). FM and clinical employees' involvement in the design of eight Norwegian hospital projects. *Facilities*. https://doi.org/10.1108/f-06-2020-0076

**Study design:** qualitative multiple case study.

**Setting:**

- Case — SNR project technical-solution meeting: A technical solution for the SNR project was discussed at a meeting.
- Report — Whole report: The study examined eight new hospital projects in Norway. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — SNR project technical-solution meeting: Operations and maintenance staff from four hospitals attended a meeting.
- Report — Whole report: The author conducted 22 interviews, using guides for facilities management employees, clinical employees and project leaders. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — SNR project technical-solution meeting: A half-day meeting was arranged and travel costs offered for operations and maintenance staff.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 114. Ashraf Badir; Robert O’Neill; Kristoph-Dietrich Kinzli; Simeon Komisar; Jong-Yeop Kim (2023). Fostering Project-Based Learning through Industry Engagement in Capstone Design Projects. *Education Sciences*. https://doi.org/10.3390/educsci13040361

**Study design:** Comparative cross-sectional surveys of student and practitioner roles.

**Setting:**

- Case — Ponce de Leon Park capstone project: Students redesigned Ponce de Leon Park in 2015 for the City of Punta Gorda.
- Report — Whole report: The report covers civil and environmental engineering capstone courses during four spring semesters from 2014 to 2017. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Ponce de Leon Park capstone project: The project involved a group of four students.
- Report — Whole report: Feedback was collected from students and practitioners; the practitioner survey was sent to 26 mentors, judges or clients. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Ponce de Leon Park capstone project: City staff provided the project programme, guided site visits and offered assistance.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Self-reported agreement that practitioner involvement bridges the gap between curriculum and industry expectations.:** 2:NA; 4:U; 6:N.

**Outcome: Self-reported agreement that practitioner involvement bridges the gap between curriculum and industry expectations.; result: Agreed or strongly agreed: 94% of practitioner respondents versus 77% of student respondents; separate surveys and differing cohort coverage.:** 7:U.

**Study:** 1:Y; 3:Y; 5:N; 8:N.


**Part-specific limitations and assessment status:**

- Practice and project examples in the industry-engaged capstone report: not assessable. Prior review did not identify a qualitative analytic procedure for the examples. A separate analytical cross-sectional assessment is already saved; the excerpt identifies a reported survey limitation and is not proof of absence.

### 115. Huizinga, Tjark; Handelzalts, Adam; Nieveen, Nienke; Voogt, Joke (2014). Fostering teachers' design expertise in teacher design teams: conducive design and support activities. *The Curriculum Journal*. https://doi.org/10.1080/09585176.2014.990395

**Study design:** Qualitative multiple case study.

**Setting:**

- Case — Plato teacher design team: The team worked on the foreign language curriculum.
- Report — Whole report: The study examined two teacher design teams developing language tasks during a CEFR project. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Plato teacher design team: Five foreign language teachers formed the team.
- Report — Whole report: Plato’s team comprised five foreign-language teachers and Thales involved all 16; at Plato four began and a fifth joined later. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Plato teacher design team: Jill provided just-in-time support aligned with the team’s design work and expressed needs.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 116. Grass, Anastasia; Backmann, Julia; Hoegl, Martin (2020). From Empowerment Dynamics to Team Adaptability: Exploring and Conceptualizing the Continuous Agile Team Innovation Process. *Journal of Product Innovation Management*. https://doi.org/10.1111/jpim.12525

**Study design:** Qualitative interview study using modified grounded theory.

**Setting:**

- Case — Team described by interviewee 18: Not checked Note: The specific project associated with the retrospective Scrum Master example was not established in the examined passages; the current project listed for interviewee 18 cannot be assumed to be that example.
- Report — Whole report: The study examined agile teams in three organisations: two German and one multinational European firm. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Team described by interviewee 18: The account concerns a team and its Scrum Master.
- Report — Whole report: Forty-four interviews involved team members and leaders from teams at the three organisations. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Team described by interviewee 18: The Scrum Master kept trivialities away from the team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 117. Kaygan, Pınar (2023). From forming to performing: team development for enhancing interdisciplinary collaboration between design and engineering students using design thinking. *International Journal of Technology and Design Education*. https://doi.org/10.1007/s10798-022-09736-3

- Bibliographic note: the review lead selected the year above; the source record lists 2022. This choice does not establish the relationship between versions.

**Study design:** Qualitative interpretive interviews and classroom observations.

**Setting:**

- Report — Interdisciplinary university course: The research concerned an interdisciplinary design studio course at Middle East Technical University, offered in the 2018–19 and 2019–20 fall semesters. Note: The two course editions are reported as the context; observational and interview data collection need not cover identical periods.
- Case — Collaborative Design course: An elective course at Middle East Technical University brought industrial design and food engineering students together.

**Participants:**

- Report — Students in course and interviews: Across both course editions, 20 industrial design and 11 food engineering students took the course; 22 of the 31 students were interviewed. Note: The course enrolment and interview sample are distinct; interviewees are a subset of the students.
- Case — Collaborative Design course: Twenty industrial design and eleven food engineering students worked in nine teams.

**Support:**

- Case — Collaborative Design course: The author joined teams needing inspiration and brainstormed with them.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:U; 10:U.

### 118. Geraldine O'Callaghan; Martin Fahy; Patricia Hall; Deirdre McCartan; Peter Langhorne; Rose Galvin; Frances Horgan (2024). From Hospital to Home: Applying a Co‐Design Approach to Determine the Key Components of an Intervention to Support Transition‐To‐Home After Stroke. *Health Expectations*. https://doi.org/10.1111/hex.70040

**Study design:** Facilitated co-design workshop and collective prioritisation.

**Setting:**

- Report — Three co-design workshops as reported: A co-design process held in a semi-rural Irish setting to develop a stroke transition-to-home pathway.

**Participants:**

- Report — Three co-design workshops as reported: The co-design process involved 12 people with stroke, six caregivers, 26 healthcare professionals and six representatives of other support services; attendance varied by workshop.

**Support:**

- Report — Three co-design workshops as reported: Researchers and a stroke champion facilitated workshops, using multi-stakeholder subgroups and a structured process to consolidate priorities.

**JBI appraisal**

**Selected items only:** Q. Part: Workshop 3 collective prioritisation and consensus on intervention components. Design recorded: Facilitated co-design workshop and collective prioritisation.


**Selected items:** 3:U; 4:U; 8:U; 10:Y.


**Part-specific limitations and assessment status:**

- Workshop 3 collective prioritisation and consensus on intervention components: tool not applicable. The workshop reports co-design decision making and group outputs, but does not identify a qualitative research methodology for the collective prioritisation account. The entire qualitative checklist is therefore not applicable; only selected questions were assessed for this component.

### 119. Andreas Kornmaaler Hansen; Linda Nhu Laursen (2026). From waste materials to product design through micro industrial symbiosis. *Discover Sustainability*. https://doi.org/10.1007/s43621-026-04361-9

**Study design:** qualitative multiple case study with action research.

**Setting:**

- Case — ReshapeWaste design field experiments: The project conducted design field experiments using manufacturing waste.
- Report — Whole report: Nineteen design field experiments examined waste reuse and product proposals across manufacturing sectors. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — ReshapeWaste design field experiments: Manufacturing companies and industrial designers were paired for collaborations.
- Report — Whole report: Interviewees included lead designers and contact persons at manufacturing companies. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — ReshapeWaste design field experiments: University facilitators paired manufacturing companies with compatible designers.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:Y; 10:U.

### 120. Przybyłek, Adam; Albecka, Marta; Springer, Olga; Kowalski, Wojciech (2022). Game-based Sprint retrospectives: multiple action research. *Empirical Software Engineering*. https://doi.org/10.1007/s10664-021-10043-z

- Bibliographic note: the source record lists 2021; the journal year above follows the verified PDF.

**Study design:** Multiple action research qualitative component.

**Setting:**

- Case — OKE_A software team: OKE_A implemented a business-to-business platform for outsourcing and hiring.
- Report — Whole report: The action research was a collaboration with three software development companies. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — OKE_A software team: The team included two junior programmers, a tester and a lead programmer.
- Report — Whole report: Two Scrum teams participated from each of the three companies. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — OKE_A software team: Two games were deployed in OKE_A.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:U; 10:Y.

### 121. Gren, Lucas; Torkar, Richard; Feldt, Robert (2016). Group development and group maturity when building agile teams: A qualitative and quantitative investigation at eight large companies. *Journal of Systems and Software*. https://doi.org/10.1016/j.jss.2016.11.024

**Study design:** Analytical cross-sectional survey component of mixed methods study; Qualitative interview component of mixed-methods study.

**Setting:**

- Report: The study covered eight different companies.

**Participants:**

- Report: Ten interviews involved coaches, Scrum Masters and managers responsible for agile processes.

**Support:**

- Case — Company F: At Company F, agile start-up squads sometimes facilitated stand-ups, iteration planning and retrospectives.

**JBI appraisal**

**Full checklist:** CS. Design recorded for the assessment: Analytical cross-sectional survey component of mixed methods study.


**Outcome: Individual self-report of effective group work measured using Group Development Questionnaire scale 4:** 2:NA; 4:Y; 6:N.

**Outcome: Individual self-report of effective group work measured using Group Development Questionnaire scale 4; result: Table 3 correlation of leadership-style agility factor with GDQ4 rho 0.277 p less than 0.05:** 7:U.

**Study:** 1:U; 3:U; 5:N; 8:U.


**Full checklist:** Q. Design recorded for the assessment: Qualitative interview component of mixed-methods study.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 122. Lee, Eun Ah; Gans, Nicholas; Grohman, Magdalena; Tacca, Marco; Brown, Matthew J. (2020). Guiding Engineering Student Teams’ Ethics Discussions with Peer Advising. *Science and Engineering Ethics*. https://doi.org/10.1007/s11948-020-00212-6

**Study design:** Qualitative cognitive ethnography and activity-theory case analysis.

**Setting:**

- Report: A senior engineering design project course.

**Participants:**

- Report: Researchers closely observed three student teams, each under a different peer-advising condition.

**Support:**

- Case — TAR design team: Ethics advisors asked about how an emergency shutdown would be handled.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:Y.

### 123. Akira-Sebastian Poncette; Pablo-David Rojas; Joscha Hofferbert; Alvaro Valera Sosa; Felix Balzer; Katarina Braune (2020). Hackathons as Stepping Stones in Health Care Innovation: Case Study With Systematic Recommendations. *Journal of Medical Internet Research*. https://doi.org/10.2196/17004

**Study design:** Qualitative organiser field study and reflective case account.

**Setting:**

- Case — February 2017 hackathon: A hackathon in February 2017.
- Report — Whole report: The report centres on a February 2017 Berlin hackathon and also describes two later hackathons. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — February 2017 hackathon: The hackathon had 30 participants.
- Report — Whole report: The first hackathon had 30 participants; the two later events each had about 75 active participants. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — February 2017 hackathon: Teams were supported by mentors during the event.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:N; 9:U; 10:N.

### 124. Sergio BotelhoJunior; Sharon O’Brien; John Organ; Bill O’Gorman (2024). Hackathons: a challenged-based learning (CBL) tool in entrepreneurship education. *The Irish Journal of Management*. https://doi.org/10.2478/ijm-2024-0005

**Study design:** Qualitative observation focus group and student interviews in mixed-method hackathon case.

**Setting:**

- Report: A residential hackathon using challenge-based learning to address circular economy issues.

**Participants:**

- Report — Hackathon participants and survey one: Eleven students participated; all completed a post-event satisfaction survey using nine five-point items. Note: The report states that all eleven students completed survey one; this does not establish the item-specific response count.
- Report: An interdisciplinary group of university students.

**Support:**

- Report: Lecturers and researchers facilitated the hackathon and its workshops.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:N.


**Part-specific limitations and assessment status:**

- Descriptive survey rating of interaction and collaboration during the hackathon: tool not applicable. The existing review description includes feedback ratings on interaction and collaboration at one hackathon. The checked article describes a post-event survey question and pooled event-wide feedback without an independent comparison or an exposure-outcome association; analytical cross-sectional and quasi-experimental checklists therefore do not fit that descriptive rating. The responses are not attributed to either team and do not establish a change caused by the hackathon. This status concerns this rating only; qualitative observations and interviews are assessed separately. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is event-wide feedback; the existing assessment does not identify a target-population prevalence estimate. The assessment already identifies a limitation: responses cannot be attributed to either team, and no change caused by the event is established. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 125. Michele V. Manuel; Ann McKenna; Gregory B. Olson (2008). Hierarchical model for coaching technical design teams. *International Journal of Engineering Education*. [DOI not recorded]

**Study design:** Qualitative preliminary interview study.

**Setting:**

- Report: The setting was a junior-level capstone design course in materials science and engineering.

**Participants:**

- Report: Six graduate student coaches and two undergraduate students were interviewed.

**Support:**

- Case — Undergraduate student account: A student reported that mentors helped the team work out the project goal.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 126. Mark Steiner; Junichi Kanai; Cheng Hsu; Richard Alben; Lester A. Gerhardt (2011). Holistic assessment of student performance in multidisciplinary engineering capstone design projects. *International journal of engineering education*. [DOI not recorded]

**Study design:** Descriptive course evaluation using surveys and student memos.

**Setting:**

- Report: A capstone design course at Rensselaer.

**Participants:**

- Case — Fall 2008 and spring 2009 surveys: The surveys included 168 students across both semesters.
- Report — Whole report: Surveys covered 15 teams in fall 2008 and 20 in spring 2009, with 168 students responding across the semesters. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Report: The course assigned two instructors per project team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Correlation of peer evaluations and instructor milestone grades: tool not applicable. The main paper reports a 0.78 correlation between mean student peer evaluations and instructor milestone grades for 20 projects across two semesters (physical page 8); the authors state the included projects had representative data but do not explain project selection or provide the denominator of eligible projects. Both measurements are assessments of the same teams; the reported result is an association of ratings, not an exposure-outcome comparison of a support intervention. The currently registered JBI analytical cross-sectional and quasi-experimental exposure-outcome tools therefore do not directly fit this agreement question. The correlation does not by itself establish agreement, validity, or an effect of team teaching. The article reports multiple simultaneous course changes (page 7), and no comparison isolates the effect of the support arrangement. This state records design-specific concerns for this quantitative result, which is included in the review description, and does not exclude or appraise other results.
- Potential qualitative research analysis of instructor-written assessments and narratives: not assessable. The report describes instructor feedback and observations as part of course practice, but does not identify a separate qualitative research analysis of those instructor narratives. The quotation locates the instructor feedback practice; it does not prove absence of a research analysis. The student reflective memos are a separate component that is now appraised in the qualitative JBI candidate, with their integration with course-survey findings explicitly noted as unclear.

### 127. Klünder, Jil; Trommer, Felix; Prenner, Nils (2022). How agile coaches create an agile mindset in development teams: Insights from an interview study. *Journal of Software Evolution and Process*. https://doi.org/10.1002/smr.2491

**Study design:** Qualitative exploratory coach interview study.

**Setting:**

- Report: The study examined support for agile transformation.

**Participants:**

- Report: The interview study involved nine agile coaches from Germany and Spain.

**Support:**

- Report: Interviewees reported using agile simulations.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 128. Kude, Thomas; Mithas, Sunil; Schmidt, Christoph T.; Heinzl, Armin (2019). How Pair Programming Influences Team Performance: The Role of Backup Behavior, Shared Mental Models, and Task Novelty. *Information Systems Research*. https://doi.org/10.1287/isre.2019.0856

**Study design:** Analytical cross-sectional team survey.

**Setting:**

- Report: Software development teams at Alpha.

**Participants:**

- Report: Data came from 377 software developers and Scrum Masters and Product Owners of 62 teams.

**Support:**

- Report: For three weeks, specialists coached the teams in the setting where they normally worked.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.:** 2:NA; 4:Y; 6:Y.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of pair programming with team performance via backup at high task novelty: bias-corrected 95% CI [−0.74; 1.42].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of pair programming with team performance via backup at low task novelty: bias-corrected 95% CI [−2.35; −0.05].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of pair programming with team performance via backup at medium task novelty: bias-corrected 95% CI [−1.18; 0.39].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of shared mental models with team performance via backup at high task novelty: bias-corrected 90% CI [−0.25; 0.64].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of shared mental models with team performance via backup at low task novelty: bias-corrected 90% CI [−1.20; −0.05].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Conditional indirect association of shared mental models with team performance via backup at medium task novelty: bias-corrected 90% CI [−0.52; 0.13].:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 1: pair-programming coefficient -1.05; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 1: shared-mental-model coefficient 0.01; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 2: backup coefficient -0.17, evaluated at mean-centered task novelty; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 2: pair-programming coefficient -0.55; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 2: shared-mental-model coefficient -0.16; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 3: backup coefficient -0.28, evaluated at mean-centered task novelty; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 3: backup-by-task-novelty interaction coefficient 0.42, clustered SE=0.18, p<0.05.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 3: pair-programming coefficient -0.31; reported without a significance star.:** 7:U.

**Outcome: Product-owner-rated team performance, using four adapted seven-point items concerning perceived team success and stakeholder expectations.; result: Table 2 performance model 3: shared-mental-model coefficient -0.07; reported without a significance star.:** 7:U.

**Outcome: Team-level average of developers’ ratings of dyadic mutual backup behavior using a seven-point scale.:** 2:NA; 4:Y; 6:Y.

**Outcome: Team-level average of developers’ ratings of dyadic mutual backup behavior using a seven-point scale.; result: Bias-corrected bootstrap 95% confidence interval for pair programming association with backup behavior via shared mental models: [0.04, 1.00], 1000 resamples.:** 7:U.

**Outcome: Team-level average of developers’ ratings of dyadic mutual backup behavior using a seven-point scale.; result: Table 3 model 4: pair programming coefficient for backup behavior, b=1.07 and SE=0.25, p<0.01.:** 7:U.

**Outcome: Team-level average of developers’ ratings of dyadic mutual backup behavior using a seven-point scale.; result: Table 3 model 5: pair programming coefficient for backup behavior with shared mental models included, b=0.75 and SE=0.29, p<0.05.:** 7:U.

**Outcome: Team-level average of developers’ ratings of dyadic mutual backup behavior using a seven-point scale.; result: Table 3 model 5: shared-mental-model coefficient for backup behavior, b=0.41 and SE=0.15, p<0.01.:** 7:U.

**Outcome: Team-level average of developers’ ratings of dyadic shared task-related mental models using a seven-point scale.:** 2:NA; 4:Y; 6:Y.

**Outcome: Team-level average of developers’ ratings of dyadic shared task-related mental models using a seven-point scale.; result: Table 3 model 2: pair programming coefficient for shared mental models, b=0.75 and SE=0.35, p<0.05.:** 7:U.

**Study:** 1:Y; 3:Y; 5:Y; 8:U.

### 129. Jeana M. Holt; AkkeNeel Talsma; Murad H. Taani; Heidi L. Bertram; Ilya Avdeev (2026). Human-Centered Design in Occupational Therapy Education: A Pragmatic Teaching Strategy. *Occupational Therapy In Health Care*. https://doi.org/10.1080/07380577.2026.2702546

- PDF bibliographic note: Published online on 11 July 2026; issue publication year is not established in the PDF.

**Study design:** Not extracted.

**Setting:**

- Report — Occupational therapy HCD workshops: Graduate occupational therapy course at an urban research university.

**Participants:**

- Report — Occupational therapy HCD workshops: Eighty-five graduate occupational therapy students across three workshops.

**Support:**

- Report — Occupational therapy HCD workshops: Facilitators provided design teams with a prompt and introduced the Mission Model Canvas.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Analysis of student reflective comments: not assessable. The article gives examples of student reflections and an author summary, but does not specify a qualitative research design, analysis procedures or sampling of quotations. An appraisal of qualitative methodology cannot be completed from the reported methods; this does not deny that the comments are empirical material or rate the entire report.
- Quantitative pre/post comparison of creative self-efficacy, psychological empowerment and design-thinking traits: not assessable. The article states that surveys were administered before and after the workshop and reports improvements but gives no numerical estimates, analysis details or outcome-specific sample sizes. Appraisal of the reported quantitative effect estimates is not currently possible; the paper does contain directional outcome statements. This status does not rate the whole report or establish that an absent item was not collected.

### 130. Sanaz Monsef; Shaghayegh Haghjooy Javanmard; Mostafa Amini-Rarani; Mohammad H. Yarmohammadian; Youseph Yazdi; Abbas Haghshenas (2022). Idea Generation Through Hackathon Event in Emergencies and Disasters, with Emphasis on Managing Flash Flood Disaster. *Disaster Medicine and Public Health Preparedness*. https://doi.org/10.1017/dmp.2021.30

- PDF bibliographic note: First published online 18 May 2021; journal issue dated 2022
- Bibliographic note: the source record lists 2021; the journal year above follows the verified PDF.

**Study design:** Not extracted.

**Setting:**

- Report — ISFHACK 2019: An educational hackathon at Isfahan University of Medical Sciences in Iran, focused on solutions to flood-related emergencies. Note: The source report gives inconsistent mentor totals.

**Participants:**

- Report — ISFHACK 2019: Sixty students from diverse disciplines in ten teams; the text variously reports nine or twelve mentors. Note: The source report gives inconsistent mentor totals.

**Support:**

- Report — ISFHACK 2019: Teams received mentoring during the event; winning teams were introduced to an accelerator and university innovation center and were supported financially and scientifically afterwards. Note: The source report gives inconsistent mentor totals.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Descriptive report of hackathon and team outcomes: not assessable. The report describes a single event and its reported results, but does not specify a data collection or outcome ascertainment procedure, qualitative analysis, or analytical comparison. An appropriate existing JBI appraisal form and item-level assessment have not been established; this is a candidate for review rather than an appraisal of the whole report.

### 131. Ashraf, Muhammad; Ali, Natash (2013). Impact Agile Project Management: Identification And Analysis Of Problems In Scrum Implementation. *VAWKUM Transactions on Computer Sciences*, 1(1), 60–67. https://doi.org/10.21015/vtcs.v2i2.99 [Analysed PDF: VFAST Transactions on Computer Sciences, 1(1), 60–67 (2013). The formal relationship between VAWKUM volume 2, issue 2 in the earlier screening record and VFAST volume 1, issue 1 in the PDF is unknown. The retained DOI is not printed in the PDF. Journal citation supplied by a review author: https://vfast.org/journals/index.php/VTCS/article/view/99 (not independently retrieved); the review author reported that the DOI returned Not Found. The relationship between the retained DOI and the analysed PDF is unconfirmed.]

**Study design:** Qualitative focus-group component of mixed-methods study.

**Setting:**

- Report: A software company in Lahore.

**Participants:**

- Report: The study population comprised developers, including some who had served as Scrum Masters.

**Support:**

- Report: The report describes daily Scrum, sprint planning and sprint review meetings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Support-related percentages for Scrum Master or Product Owner interruptions in the Scrum survey: tool not applicable. The cited result is a descriptive percentage about interruptions rather than a reported association between an independently measured exposure and an outcome, so the revised JBI analytical cross-sectional checklist is not applicable to this result. The separately identified descriptive survey needs consideration under an appropriate prevalence checklist; this status does not assess that checklist or the full article. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded survey percentage alone does not establish that a defined target-population prevalence was the estimand, or that the prevalence checklist is suitable. The separately recorded qualitative appraisal notes that the focus group and survey are not consistently distinguished; that limitation must not be treated as evidence that no prevalence study exists. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 132. Ben Sherrett; John P. Parmigiani (2011). Implementation of the house of quality as a tool to assess products of design in a capstone design course. *International journal of engineering education*. [DOI not recorded]

**Study design:** Descriptive course case with an instructor’s retrospective observations.

**Setting:**

- Report: Oregon State University’s mechanical, industrial and manufacturing engineering capstone course.

**Participants:**

- Report: Student teams interacted with sponsor mentors.

**Support:**

- Report: The sponsor mentor provided guidance and clarified requirements through direct interaction with the student team.

**JBI appraisal**

**Selected items only:** Q. Part: Course instructor observations about the house-of-quality approach. Design recorded: Descriptive course case with an instructor’s retrospective observations.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Course instructor observations about the house-of-quality approach: not assessable. The main paper describes the course and reports the instructor’s retrospective perception of changes after the House of Quality implementation (physical pages 7–8). Applicable methodological considerations: the source of the observations is identified as the course instructor, but methods for collecting or analysing the perceptions, researcher positioning and reflexivity, detailed participant evidence, and ethics review are not reported; these are unreported, not assumed absent. The report gives no measured instructor time or comparable control, and the authors themselves call for more objective research. The historical sponsor-funding series in Figure 1 is a separate quantitative record and does not measure the instructor-time outcome. The qualitative JBI checklist does not directly fit this unstructured practitioner account as documented; the relevant appraisal concerns are stated here without inventing item-level study methods. This evaluation concerns only the instructor-perceived outcome and does not make a paper-wide quality judgment.

### 133. Bstieler, Ludwig; Hemmert, Martin (2010). Increasing Learning and Time Efficiency in Interorganizational New Product Development Teams. *Journal of Product Innovation Management*. https://doi.org/10.1111/j.1540-5885.2010.00731.x

- Bibliographic note: the PDF title above differs from the linked-item title.

**Study design:** Same-wave analytical cross-sectional comparison within a two-wave survey.

**Setting:**

- Report: Interorganizational new product development teams.

**Participants:**

- Report: The empirical study included 50 collaborative new product development projects.

**Support:**

- Report: The study reported shared problem solving and caring behavior in interorganizational teams.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Perceived project time efficiency from two key-informant items:** 2:NA; 4:U; 6:Y.

**Outcome: Perceived project time efficiency from two key-informant items; result: Table 1 bivariate association of shared problem solving with time efficiency r 0.559 p less than 0.01 two-tailed:** 7:U.

**Study:** 1:Y; 3:Y; 5:Y; 8:U.

### 134. Lynne Margaret Maher; Brooke Hayward; Patricia Hayward; Chris Walsh (2017). Increasing sustainability in co-design projects: A qualitative evaluation of a co-design programme in New Zealand. *Patient Experience Journal*. https://doi.org/10.35680/2372-0247.1150

**Study design:** qualitative programme evaluation using interviews and workbooks.

**Setting:**

- Report: A co-design programme for teams of healthcare providers.

**Participants:**

- Report: Project teams included 56 healthcare professionals and 17 patients.

**Support:**

- Report: Teams received guidance through coaching calls and email.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 135. Lam, Chi Yan; Shulha, Lyn M. (2015). Insights on Using Developmental Evaluation for Innovating: A Case Study on the Cocreation of an Innovative Program. *American Journal of Evaluation*. https://doi.org/10.1177/1098214014542100

- Two source records identify the same report; the 2015 full title and year above follow the journal PDF. The other record uses a shortened title and 2014.

**Study design:** Qualitative developmental evaluation case study.

**Setting:**

- Report: An educational program developed from conceptualization to pilot implementation.

**Participants:**

- Report: Clients and a developmental evaluator co-created the program.

**Support:**

- Case — Social media tinkering session: The evaluator explained and demonstrated social media and led practice using the technology.

**JBI appraisal**

### Source record 1 of 2

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.


### Source record 2 of 2

No separate checklist or selected-item assessment is recorded for this source record. An assessment for the other source record linked to this same bibliographic entry is shown in its section.

### 136. Jennifer L. Rodis; Timothy R. Ulbrich; Brandon T. Jennings; Betsy M. Elswick; Rebekah Jackowski (2015). Integrating a Patient Care Development Model to Enhance Community Pharmacy Residency Programs. *INNOVATIONS in pharmacy*. https://doi.org/10.24926/iip.v6i4.406

**Study design:** Qualitative descriptive thematic content analysis of resident reflections.

**Setting:**

- Report: Five community pharmacy residency programs in the United States.

**Participants:**

- Report — Residency programme roles: The five residency programmes incorporated roles for pharmacy residents and student pharmacist teams; the approaches differed across programmes. Note: This describes participant roles and programme variation, not a single aggregated participant count.
- Case — Ohio State University residency program: Residents mentored student-driven projects.

**Support:**

- Case — Ohio State University residency program: Residents mentored student-driven projects.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 137. Powers, Lance M.; Summers, Joshua D. (2009). Integrating Graduate Design Coaches in Undergraduate Design Project Teams. *International Journal of Mechanical Engineering Education*. https://doi.org/10.7227/ijmee.37.1.2

**Study design:** Qualitative pilot case study.

**Setting:**

- Report: A senior undergraduate team worked on developing an inexpensive, low-volume machine for plastic injection modeling.

**Participants:**

- Report: A mechanical engineering graduate student served as design coach for a senior undergraduate design team.

**Support:**

- Report: The coach developed tutorials on design tools and coached students on when and why to use methodologies.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 138. Peter Scalia; Farhan Ahmad; Danielle Schubbe; Rachel Forcino; Marie-Anne Durand; Paul James Barr; Glyn Elwyn (2021). Integrating Option Grid Patient Decision Aids in the Epic Electronic Health Record: Case Study at 5 Health Systems. *Journal of Medical Internet Research*. https://doi.org/10.2196/22766

**Study design:** Qualitative exploratory multi-site case study.

**Setting:**

- Report: Five academic medical centers in the United States.

**Participants:**

- Report: A clinical champion at each institution worked with the local Epic EHR team.

**Support:**

- Report: The study team's Epic technologist shared a build guide they had developed with each institution.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 139. Annika Grynne; Maria Browall; Sofi Fristedt; Karin Ahlberg; Frida Smith (2021). Integrating perspectives of patients, healthcare professionals, system developers and academics in the co-design of a digital information tool. *PLoS ONE*. https://doi.org/10.1371/journal.pone.0253448

**Study design:** Qualitative group interview component of participatory design.

**Setting:**

- Report: A radiotherapy department in a Swedish university hospital.

**Participants:**

- Case — Initial needs-assessment workshop: Healthcare professionals and administrative staff participated in an initial workshop.
- Report — Whole report: The needs-assessment survey included 45 patients, and a subsequent pilot included 11 participants. Note: The survey and later pilot are distinct stages; the source does not establish whether their participants overlapped.

**Support:**

- Case — Initial needs assessment: The project management group searched the literature on virtual reality technology as a cancer-care information tool.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:U; 9:Y; 10:Y.

### 140. Katarina Braune; Pablo-David Rojas; Joscha Hofferbert; Alvaro Valera Sosa; Anastasiya Lebedev; Felix Balzer; Sylvia Thun; Sascha Lieber; Valerie Kirchberger; Akira-Sebastian Poncette (2021). Interdisciplinary Online Hackathons as an Approach to Combat the COVID-19 Pandemic: Case Study. *Journal of Medical Internet Research*. https://doi.org/10.2196/25283

**Study design:** Descriptive post-event survey and case report.

**Setting:**

- Report: An online health hackathon.

**Participants:**

- Report: Forty-eight participants and 52 mentors participated and developed 14 projects.

**Support:**

- Report: Two experts offered pitch training to help teams develop final pitches.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:U; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Hackathon organisation and mentor feedback account: not assessable. Prior review did not identify qualitative analysis for this account. This hold does not adjudicate a distinct quantitative component; the excerpt identifies the context and is not proof of absence. The recorded passage states that 13 people completed feedback forms; it does not itself identify qualitative coding or analysis, and the completion count is not treated as a response rate. Full-text review 2026-11-08: The reported research collected and analysed participant-survey responses in Google Forms (physical page 5); the saved PDF ends a sentence with “A thematic” at the bottom of that page, and the following page does not continue that sentence. The qualitative analytic method and its connection to the mentor-feedback accounts therefore remain unclear from this PDF; no thematic method is inferred from a partial sentence. A separate descriptive quantitative participant-survey component is recorded independently.
- Participant survey of project progress and mentoring: tool not applicable. The report is an empirical descriptive case using participant and mentor surveys. Of 48 event participants, 30 provided feedback; 18 of the 30 said they would not have started their project without this event, and the authors report participant-rated reasons for progress, including mentor insights. This post-event descriptive survey has no reported pre/post or exposure-outcome comparison to which the registered quasi-experimental or analytical cross-sectional tools apply. Response selection and retrospective self-report matter; an item-level appraisal with a different tool has not been performed. This concerns only the participant survey, not other evidence or the quality of the paper as a whole.

### 141. Gestwicki, Paul; McNely, Brian (2016). Interdisciplinary Projects in the Academic Studio. *ACM Transactions on Computing Education*. https://doi.org/10.1145/2732157

**Study design:** Design-based research using ethnography and case studies.

**Setting:**

- Report: Academic studios for interdisciplinary undergraduate project-oriented education.

**Participants:**

- Report: The model brought faculty, students and community partners together.

**Support:**

- Case — 2013 studio: In the 2013 studio, a composer and programmer used pair programming to incorporate music into the game.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 142. Kyza, Eleni A.; Agesilaou, Andria (2022). Investigating the Processes of Teacher and Researcher Empowerment and Learning in Co-design Settings. *Cognition and Instruction*. https://doi.org/10.1080/07370008.2021.2010213

**Study design:** Qualitative instrumental case study component.

**Setting:**

- Report: A co-design team developed a module for elementary school science education.

**Participants:**

- Case — Focal co-design team: The team consisted of a researcher and seven in-service science teachers.
- Report — Whole report: The professional development programme involved 27 teachers in five groups; the reported focal team comprised seven teachers and one researcher. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Focal co-design team: The researcher encouraged other teachers to share when only two were contributing.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:Y.


**Part-specific limitations and assessment status:**

- Wider programme teacher confidence and professional development needs pre-post questionnaire: outside appraisal scope. Table 5 pools 18 teachers with paired data across the professional development programme, while the co-design team described for this review comprises seven teachers and a researcher. The paper does not identify the seven team members’ separate survey results; the pooled result cannot be attributed to the focal team and is not included in this team-outcome appraisal. This does not mean the result is irrelevant in every context.

### 143. R. Akif; H. Majeed (2012). Issues and challenges in Scrum implementation. *International Journal of Scientific & Engineering Research*. [DOI not recorded]

**Study design:** Mixed-method survey and interviews.

**Setting:**

- Report — Whole reported project: Two software companies were surveyed about Scrum implementation. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The study involved employees including project managers, Scrum masters, development and quality-assurance team members. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: The report describes team members gaining Scrum knowledge from colleagues or Scrum masters. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 144. Matuk, Camillia; Hurwich, Talia; Prosperi, Jonathan; Ezer, Yael (2020). Iterations on a Transmedia Game Design Experience for Youth’s Autonomous, Collaborative Learning. *International Journal of Designs for Learning*. https://doi.org/10.14434/ijdl.v11i1.24911

**Study design:** Qualitative iterative educational design case.

**Setting:**

- Report — Whole reported project: A week-long workshop engaged seventh-grade students in designing non-digital science games. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The workshop involved seventh-grade students working collaboratively. Note: The cited passage directly supports this description.

**Support:**

- Case — First workshop iteration: In the first iteration, facilitators guided student teams through brainstorming, prototyping, playtesting, and refinement. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Individual students’ pre–post science-content assessment in both game-design workshop iterations: not assessable. The authors report little change in students’ responses on science-content assessment items from pre to post in both workshop iterations. The article does not give the pre- and post-test scores or quantitative change, the number of paired respondents for this comparison, or sufficient scoring detail to appraise a specific numerical result. The finding refers to individual students, not a measured team-level outcome; it is distinct from the existing qualitative appraisal of the collaborative design process. The narrative direction is reported and is not treated as absent. The existing two review descriptions concern the science included in the teams’ game designs and observed collaboration; they do not report this individual science-knowledge assessment as an extracted outcome. Its relevance as a participant-level outcome under the review scope has not been established, so this record does not classify it as an eligible team-related result.

### 145. Irene J.M. Muller-Schoof; Marjolein E. A. Verbiest; Miranda Snoeren; Katrien G. Luijkx (2023). Lessons Learned From Co-Designing Educational Programs for Student and Practicing Healthcare Professionals in Nursing Homes: A Participatory Qualitative Study. *Journal of Participatory Research Methods*. https://doi.org/10.35844/001c.57529

**Study design:** participatory qualitative multiple-case descriptive study.

**Setting:**

- Report — Whole reported project: Two teams co-designed educational programs concerning evidence-based instruments for nursing-home healthcare professionals. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Eleven members joined the two co-design teams; one researcher belonged to both. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: The facilitator scheduled monthly meetings and prepared minutes. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:U.

### 146. Fox, Garey A.; Weckler, Paul; Thomas, Dan (2015). Linking First-Year and Senior Engineering Design Teams: Engaging Early Academic Career Students in Engineering Design. *Advances in Engineering Education*. [DOI not recorded]

**Study design:** Historical cohort comparison before and after course redesign.

**Setting:**

- Report — Whole reported project: First-year and senior engineering design teams were linked through capstone projects. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: First-year and senior engineering students worked in linked design teams. Note: The cited passage directly supports this description.

**Support:**

- Case — Fall 2013 cohort: In fall 2013, the senior-design instructor included mentoring first-year teams in the senior course grade. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: Faculty evaluation score for first-year team project poster presentations:** 5:Y; 6:U; 7:U.

**Outcome: Faculty evaluation score for first-year team project poster presentations; result: T-test of research-based 2010–2011 versus senior-linked design-based 2012–2013 poster scores reported p 0.57:** 8:U; 9:U.

**Study:** 1:Y; 2:Y; 3:U; 4:N.

### 147. Paretti, Marie; Layton, Richard; Laguette, Stephen; Speegle, Greg (2011). Managing and Mentoring Capstone Design Teams: Considerations and Practices for Faculty. *International journal of engineering education*. [DOI not recorded]

- Bibliographic note: the PDF title above differs from the source-record title.

**Study design:** Qualitative synthesis of recorded panel discussion.

**Setting:**

- Report — Whole reported project: A panel at the 2010 Capstone Design Conference discussed how student design teams were managed. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Panelists and session participants discussed managing and mentoring student teams. Note: The cited passage directly supports this description.

**Support:**

- Case — Faculty accounts of team formation: Some faculty reported allowing students to select their own teams, sometimes subject to requirements for a mix of skills and roles. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:Y; 8:U; 9:U; 10:U.

### 148. Goffin, Keith; Koners, Ursula; Baxter, David; Van Der Hoven, Chris (2010). Managing Lessons Learned and Tacit Knowledge in New Product Development. *Research-Technology Management*. https://doi.org/10.1080/08956308.2010.11657639

**Study design:** Qualitative multiple case study.

**Setting:**

- Report — Whole reported project: The research examined five German companies. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The researchers interviewed experienced new-product-development personnel. Note: The cited passage directly supports this description.

**Support:**

- Case — AppliancesCo: At AppliancesCo, senior managers encouraged reflection and attended post-project reviews. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 149. Federico P. Zasa; Andrea Patrucco; Elena Pellizzoni (2021). Managing the Hybrid Organization: How Can Agile and Traditional Project Management Coexist?. *Research-Technology Management*. https://doi.org/10.1080/08956308.2021.1843331

**Study design:** Qualitative exploratory coach interview study.

**Setting:**

- Report — Whole reported project: The study investigated agile implementation in non-software industries. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Eight Agile coaches were interviewed. Note: The cited passage directly supports this description.

**Support:**

- Case — One anonymised company described by a coach: A coach described holding a self-evaluation workshop in which teams assessed their knowledge. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 150. Kadenic, Maja Due; Koumaditis, Konstantinos; Junker-Jensen, Louis (2023). Mastering scrum with a focus on team maturity and key components of scrum. *Information and Software Technology*. https://doi.org/10.1016/j.infsof.2022.107079

- Bibliographic note: the source record lists 2022; the journal year above follows the verified PDF.

**Study design:** Analytical cross-sectional survey.

**Setting:**

- Report — Whole reported project: The surveyed Scrum teams were mainly located in Denmark. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The analysis included 182 fully responding Scrum team members. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Most respondents had received Scrum training through formats including company workshops and courses. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.:** 2:NA; 4:U; 6:N.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master coaches team members in self-management (SR16); chi-square=3.065, table marks p<0.10 but not p<0.05.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master enables team to improve Scrum practices (SR20); chi-square=3.177, table marks p<0.10 but not p<0.05.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master ensures all Scrum events take place (SR14); chi-square=4.180, p<0.05.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master ensures events remain time-boxed (SR15); chi-square=1.037, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master facilitates stakeholder collaboration for the product owner when needed (SR17); chi-square=0.354, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master has domain technical skills and knowledge (SR19); chi-square=0.022, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master is vital for ensuring teamwork (SR21); chi-square=0.108, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master removes barriers between stakeholders and team (SR22); chi-square=2.457, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: Scrum master trains and coaches the organization in Scrum adoption (SR18); chi-square=0.995, no p<0.05 indication.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: agile training for Scrum team members (TC5); chi-square=22.396, p<0.001.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Chi-square: respondent belief that the Scrum master contributes to successful Scrum use (SR13); chi-square=12.580, p<0.01.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Reduced Scrum-master-role logistic model: Scrum master ensures all events take place (SR14), beta=0.922, Wald=3.988, p<0.05.:** 7:U.

**Outcome: Respondent-reported team success at applying the Scrum framework, binary successful versus needs improvement, in the 182 complete individual survey responses.; result: Reduced team-composition logistic model: agile training for Scrum team members (TC5), beta=0.490, Wald=7.773, p<0.01.:** 7:U.

**Study:** 1:Y; 3:U; 5:N; 8:Y.

### 151. Anne Honey; Gemma Smart; Helen Glover; Naseem Ahmadpour; Yidan Cao; Justin Scanlan; Andrew Povolny; Asha Zappa; Grenville Rose; Lorraine Smith; Mark Orr; Fadzi Marasha; Nicola Hancock (2026). Maximising the ‘co’ in co-design through facilitator actions: co-designers’ perspectives on what makes their participation in co-design meaningful. *BMC Health Services Research*. https://doi.org/10.1186/s12913-026-15335-y

**Study design:** Qualitative interview study.

**Setting:**

- Report — Whole reported project: The project used co-design labs to develop a mental-health recovery app. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Nineteen co-designers participated in iterative co-design labs. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: After an initial information gap was identified, project information was provided at the start of the second lab. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 152. Muhammad Inam Shahzad; Tasleem Mustafa; Fahad Jan; Muhammad Ashraf; Ahmad Adnan (2011). Maximization of return on investment (ROI) by hyper productive software development through scrum. *International Journal of Managment, IT and Engineering*. [DOI not recorded]

**Study design:** Not extracted.

**Setting:**

- Case — FESCO software project: A software project at the Faisalabad Electric Supply Company computer centre.

**Participants:**

- Case — Project PMII: Three developers and one Scrum Master worked on the project.

**Support:**

- Case — Sprint hurdles: The Scrum Master handled hurdles and barriers during a sprint.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Project account of Scrum Master handling hurdles and sprint delay: not assessable. The selected hurdle-and-delay account is an author narrative without a clearly described independent data-collection and analysis procedure. The separate historical project comparison is not assessed by this status.

### 153. Aurelia Engelsberger; Jillian Cavanagh; Timothy Bartram; Beni Halvorsen (2023). Maximizing team development for open innovation in digital product development: the role of collaborative HRM and relational leadership. *Personnel Review*. https://doi.org/10.1108/pr-09-2022-0657

**Study design:** Qualitative longitudinal case study.

**Setting:**

- Report — Whole reported project: A cross-functional team worked on digital product development at a large fashion house in Germany. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Ten interviews involved project-team members, and six involved external knowledge-exchange partners. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: An external knowledge-exchange partner described training people at the organization to use the partner’s software. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.

### 154. Alicia Fernandez-Fernandez; Walter Lee Murfee; Jeffrey A. LaMack; Teresa A. Murray (2023). Mentoring for INnovative Design Solutions (MINDS): Key Design Considerations and Collaborative Teamwork across Universities for Clinical Translation. *Biomedical Engineering Education*. https://doi.org/10.1007/s43683-022-00090-3

- PDF bibliographic note: The journal issue is dated July 2023; the article was published online on 28 November 2022.
- Bibliographic note: the source record lists 2022; the journal year above follows the verified PDF.
- Bibliographic note: bibliographic metadata list 2022; the journal year above follows the checked PDF.

**Study design:** Inductive constant-comparative qualitative analysis.

**Setting:**

- Report — MINDS program: An inter-university mentoring program addressed biomedical design.

**Participants:**

- Report — MINDS cohorts 2015–2022: Not reproduced because of quotation or overlap with source text.

**Support:**

- Case — Presentation feedback: Mentors gave a student feedback about their presentation.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 155. Haase, Eileen (2020). Moving a Team-Based Freshmen Biomedical Engineering and Design Course Online. *Biomedical Engineering Education*. https://doi.org/10.1007/s43683-020-00005-0

**Study design:** Descriptive end-of-semester course questionnaire.

**Setting:**

- Report — Whole reported project: A team design project moved to a virtual environment during the COVID-19 pandemic. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The course enrolled 124 students in teams of five. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Virtual mentoring panels included upperclassmen and alumni. Note: The cited passage directly supports this description.

**JBI appraisal**

**Selected items only:** P. Part: Descriptive end-of-semester questionnaire on teamwork and course objectives. Design recorded: Descriptive end-of-semester course questionnaire.


**Selected items:** 1:U; 2:U; 3:U; 4:Y; 5:U; 6:U; 7:U; 8:U.


**Part-specific limitations and assessment status:**

- Descriptive end-of-semester questionnaire on teamwork and course objectives: tool not applicable. This empirical teaching report includes a descriptive end-of-semester questionnaire, participant statements and peer-review ratings, not just unsupported reflection. The author reports 124 students in teams of five (physical page 1), 81% agreeing that course objectives were met and 75% that team assignments were useful (page 3), and average peer-review grades between 1 and 2 over three reviews (page 4). Neither the revised JBI analytical cross-sectional tool, which targets exposure-outcome associations, nor the quasi-experimental tool, which targets comparisons, fits the isolated one-time survey percentages. Applicable methodological questions, informed by JBI prevalence checklist domains but not a full checklist assessment: setting and target class are described (2014 item 4); the survey sampling/completeness and denominators for the percentages are not given in the report section examined (items 1–3 and 5); Figure 2 describes the rated statement and shows agreement categories (physical PDF page 3); the exact original survey question, reliability and validity are not established (items 6–7); percentages are descriptive and cannot be independently verified without denominators or attributed causally to online support (item 8). The report also provides individual students’ quotations, without describing a systematic analysis of those comments. This is a scoped method appraisal, not a full formal JBI checklist assessment.
- Potential qualitative analysis of the move to online team-based teaching: not assessable. The prior review could not identify a separately assessable qualitative research analysis in the online course report. The excerpt locates the reported course transition and does not prove absence of an analysis.

### 156. Dorcas Adedoja; Lisa M Kuhns; Asa Radix; Robert Garofalo; Maeve Brin; Rebecca Schnall (2024). MyPEEPS Mobile App for HIV Prevention Among Transmasculine Youth: Adaptation Through Community-Based Feedback and Usability Evaluation. *JMIR Formative Research*. https://doi.org/10.2196/56561

**Study design:** Descriptive advisory-board review with a reported prototype revision.

**Setting:**

- Case — MyPEEPS advisory-board adaptation: A US project adapting a mobile HIV-prevention app for young transgender men and transmasculine youth.

**Participants:**

- Case — MyPEEPS advisory-board adaptation: A youth advisory board of 11 members and expert advisors contributed feedback to the adaptation.

**Support:**

- Case — MyPEEPS advisory-board adaptation: A youth advisory board and expert advisors reviewed proposed adaptations and provided feedback across repeated rounds.

**JBI appraisal**

**Selected items only:** Q. Part: Youth advisory-board feedback and subsequent reported removal of an app activity. Design recorded: Descriptive advisory-board review with a reported prototype revision.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Youth advisory-board feedback and subsequent reported removal of an app activity.: tool not applicable. The selected finding reports feedback and a revision, not a separately specified qualitative analysis methodology. Selected qualitative items concern evidence and conclusions.

### 157. Signe Pedersen; Søsser Brodersen (2023). Navigating co-design of actor-networks. *International Journal of Healthcare Technology and Management*. [DOI candidates unresolved]

- The two source records give DOI candidates https://doi.org/10.1504/ijhtm.2023.10056910 and https://doi.org/10.1504/ijhtm.2023.131516. Their relationship and the DOI to use for the journal report remain unconfirmed.

**Study design:** qualitative retrospective case study.

**Setting:**

- Report — Whole reported project: A pharmaceutical company explored insulin accessibility for people with diabetes in India. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: People with diabetes participated in discussions about the design. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Cards were used in discussions with people with diabetes. Note: The cited passage directly supports this description.

**JBI appraisal**

### Source record 1 of 2

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:U; 8:U; 9:U; 10:U.


### Source record 2 of 2

No separate checklist or selected-item assessment is recorded for this source record. An assessment for the other source record linked to this same bibliographic entry is shown in its section.

### 158. Durmusoglu, Serdar S.; Hirunyawipada, Tanawat; McNally, Regina C. (2017). New Product Development Process Implementation in a Business-To-Business Firm: The Driving and Moderating Factors for Improved Program Performance and Time-To-Market. *Journal of Business-to-Business Marketing*. https://doi.org/10.1080/1051712x.2016.1275823

**Study design:** Cross-sectional employee survey within single-company mixed methods case study; Qualitative interview component of mixed-methods case study.

**Setting:**

- Report — Whole reported project: The company implemented a phased new-product-development process involving cross-functional teams. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: The study interviewed new-product-development team members and middle and senior managers. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: An interviewee described team mentors who called meetings, took minutes and ensured attendance. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** CS. Design recorded for the assessment: Cross-sectional employee survey within single-company mixed methods case study.


**Outcome: Employee-perceived company-wide improvement in new product development program success relative to a few years previously, assessed by one item.:** 2:NA; 4:U; 6:U.

**Outcome: Employee-perceived company-wide improvement in new product development program success relative to a few years previously, assessed by one item.; result: Table 6: association of perceived product approval committee decision-making quality with perceived improved program performance, B = .30, SE = .15, p < .05, in a multiple regression of 46 employee responses from one firm.:** 7:U.

**Study:** 1:Y; 3:U; 5:N; 8:Y.


**Full checklist:** Q. Design recorded for the assessment: Qualitative interview component of mixed-methods case study.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 159. Epifelward Niño O. Amora; Kennery V. Romero; Rennan C. Amoguis; Evangeline N. Olandria; Joseph James Olavides (2022). OJT AtTRACK – On the Job Trainee Remote Attendance Monitoring System using Face Recognition System. *IOER International Multidisciplinary Research Journal*. https://doi.org/10.54476/6376954

**Study design:** Not extracted.

**Setting:**

- Report — OJT AtTRACK development: A university-based development project for a remote on-the-job trainee attendance monitoring system. Note: The developing collective and future system users are distinguished.

**Participants:**

- Report — OJT AtTRACK development: The development team worked with a dean, chairpersons and on-the-job training coordinators; the size and individual makeup of the development team are not specified. Note: Stakeholders are not automatically counted as developers.

**Support:**

- Report — OJT AtTRACK development: University stakeholders discussed problems in existing trainee-attendance processes with the development team, contributing information used to formulate requirements and backlogs. Note: The body establishes stakeholder input; the daily Scrum meeting appears only in the abstract.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Stakeholder requirement elicitation and organisation into development backlogs: not assessable. The report presents practitioner activity, user stories and backlog prioritisation, but does not identify a formal qualitative sampling and analytic method sufficient for a complete qualitative JBI checklist. This is a component-specific appraisal limitation; unreported procedures are not assumed not to exist.
- Reported prototype satisfaction after stakeholder and developer review: not assessable. The report asserts 100% satisfaction but does not provide the number or selection of respondents, the assessment instrument, or numerical results from which the percentage can be verified. No full JBI appraisal or causal effect of stakeholder input is claimed.

### 160. Katherine Kulyk; Caitlyn Cater; Edward Quine; Kyra (Alecx) Motus; Erin Ozarko; Danielle Robitaille; Sophie Offen; Jung-In Choi; David Wood (2026). Operationalising the i-PARiHS framework through iterative PDSA cycles to redesign a transcatheter aortic valve implantation program: a theory-driven implementation study. *Implementation Science Communications*. https://doi.org/10.1186/s43058-026-01118-3

**Study design:** Framework-informed qualitative process evaluation.

**Setting:**

- Report — Whole reported project: A TAVI program was redesigned at Vancouver General Hospital in British Columbia, Canada. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Clinical stakeholders included physician leaders, nurses, and knowledge-translation and research partners. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Facilitating stakeholders supported program staff through education, iterative workflow redesign, audit and feedback, and team huddles. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:U; 9:Y; 10:U.

### 161. Handayani Madania Insani; Afifah Mu’minah; R. Moch Rizal Hafiyan; Wafi Ulya Az Zahra; Mimin Sa’adah; Sri Ayu Rismayanti (2025). Optimizing Bamboo Utilization Through Hihid Product Design Innovation in Sukaluyu Village. *Abdimas Umtas: Jurnal Pengabdian Kepada Masyarakat*. https://doi.org/10.35568/abdimas.v8i3.6554

**Study design:** Not extracted.

**Setting:**

- Report — Sukaluyu community hihid programme: A community-based bamboo hihid design and production programme in Sukaluyu Village, Indonesia. Note: The source describes community-based development and training.

**Participants:**

- Report — Sukaluyu community hihid programme: Community members took part in craft training and collective reflection; the authors report a difficulty involving some participants aged 40 and over. The number of participants is not reported. Note: The source does not identify the number of affected or total participants.

**Support:**

- Report — Sukaluyu community hihid programme: Facilitators and community participants jointly introduced colour-coded bamboo strips in response to difficulty distinguishing the materials. Note: This describes the specific reported adaptation, not general training claims.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Observation and adaptation for participants who had difficulty distinguishing bamboo strips: not assessable. The report describes an observed difficulty, a collaborative colour-coding adaptation and an author-reported improvement but does not specify participant counts, observation procedures or an analysis of the participant experience. A full qualitative JBI checklist cannot be completed for this component from the information reported. This is not a judgment on the whole article.

### 162. Juliette Brun; Pascal Le Masson; Benoit Weil (2019). Out of the picture? How incompatible knowledge and distant visual stimuli may foster idea generation. *Creat Innov Manag.*. https://doi.org/10.1111/caim.12311

**Study design:** Qualitative case study of a facilitated idea-generation session.

**Setting:**

- Report — Renault EV service development: A Renault team explored a community-based approach to electric-vehicle charging.

**Participants:**

- Case — Preparatory team meeting: Not reproduced because of quotation or overlap with source text.

**Support:**

- Case — Picture-based idea generation: A freelance designer facilitated a preparatory meeting using a deck of pictures as prompts for brainstorming.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:U; 9:U; 10:Y.

### 163. Rees Lewis, Daniel G.; Easterday, Matthew W.; Harburg, Emily; Gerber, Elizabeth M.; Riesbeck, Christopher K. (2018). Overcoming barriers between volunteer professionals advising project‐based learning teams with regulation tools. *British Journal of Educational Technology*. https://doi.org/10.1111/bjet.12550

- PDF bibliographic note: The checked PDF displays 2017 and placeholder volume and issue numbers; its relationship to the linked-item 2018 date remains unconfirmed.
- Bibliographic note: the review lead selected the year above; the source record lists 2017. This choice does not establish the relationship between versions.

**Study design:** Qualitative field study of design coaching tool.

**Setting:**

- Report — Whole reported project: Student teams created a product to address a local social challenge. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Twelve undergraduates participated. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: A facilitator taught teams a weekly goal-setting script used with the StandUp feed. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:Y.

### 164. Wojciechowski, Lauren; Woubishet Teklu, Emnet; Cheruiyot, Nelson; Gebremeskel, Ruth; Otieno, Christine; Kramer, Julia (2026). Participant satisfaction with workshops to co-design family planning interventions in Ethiopia and Kenya. *CoDesign*. https://doi.org/10.1080/15710882.2026.2711792

**Study design:** Qualitative comparative case study.

**Setting:**

- Report — Whole reported project: Seven workshops were held in person, at Addis Ababa in Ethiopia and Nairobi in Kenya. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Participants included married men, contraceptive users and providers of family planning. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: On-site daycare was available for participants’ children when needed. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 165. Jonathan Steinke; Berta Ortiz-Crespo; Jacob van Etten; Anna Müller (2021). Participatory design of digital innovation in agricultural research-for-development: insights from practice. *Agricultural Systems*. https://doi.org/10.1016/j.agsy.2021.103313

**Study design:** Qualitative author deliberation and inductive comparison of project cases.

**Setting:**

- Report: The report draws on participatory digital-agriculture design projects in sub-Saharan Africa and Latin America. Note: The original report describes this study-level context or research sample.
- Case — Seed Information Exchange Platform: The Seed Information Exchange Platform was developed in Ethiopia. Note: The cited passage directly supports this description.

**Participants:**

- Case — Seed Information Exchange Platform: The project involved Integrated Seed Sector Development Ethiopia and public seed companies. Note: The cited passage directly supports this description.

**Support:**

- Case — Seed Information Exchange Platform: The team created eleven personas in a workshop to bring different user perspectives into prototyping. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:Y; 6:Y; 7:U; 8:U; 9:U; 10:Y.

### 166. Jacki Liddle; Peter Worthy; Dennis Frost; Eileen Taylor; Dubhglas Taylor (2022). Partnering with people living with dementia and care partners in technology research and design: Reflections and recommendations. *Australian Occupational Therapy Journal*. https://doi.org/10.1111/1440-1630.12843

**Study design:** Qualitative shared meta-reflection across three projects.

**Setting:**

- Report: A shared reflection covered three participatory research and technology-design studies. Note: The original report describes this study-level context or research sample.
- Case — Florence Project: The Florence Project was a participatory design research program involving technology. Note: The cited passage directly supports this description.

**Participants:**

- Report: Five research-team members, including living-experience experts, an occupational therapist and an interaction designer, conducted the shared reflection. Note: The original report describes this study-level context or research sample.
- Case — Florence Project: Experts with lived experience helped guide the Florence Project and gave feedback on the technology being designed. Note: The cited passage directly supports this description.

**Support:**

- Case — Florence Project: People were asked what accessibility supports they required. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:Y.

### 167. Farr, Michelle (2018). Power dynamics and collaborative mechanisms in co-production and co-design processes. *Critical Social Policy*. https://doi.org/10.1177/0261018317747444

- PDF bibliographic note: The checked PDF displays a 2017 copyright date and pages 1–22 without an issue; its relationship to the linked-item 2018 date remains unconfirmed.
- Bibliographic note: the review lead selected the year above; the source record lists 2017. This choice does not establish the relationship between versions.

**Study design:** Qualitative comparative realist evaluation.

**Setting:**

- Report: Two cases compared an NHS breast-cancer service and a local-government innovation team. Note: The original report describes this study-level context or research sample.
- Case — NHS breast cancer services: The NHS case involved experience-based co-design in breast cancer services at two urban hospitals. Note: The cited passage directly supports this description.

**Participants:**

- Report: The NHS evaluation included interviews with seven patients and 17 staff; the local-government evaluation included interviews with 17 staff and two focus groups. Note: The original report describes this study-level context or research sample.
- Case — NHS breast cancer services: The NHS case included patients and staff participating in co-design activities. Note: The cited passage directly supports this description.

**Support:**

- Case — NHS breast cancer services: Facilitators helped create space for co-design groups to identify shared goals and means of achieving them. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 168. Ingrid Zechmeister‐Koss; Sandra Aufhammer; Herbert Bachler; Annette Bauer; Philipp Bechter; Anna Buchheim; Hanna Christiansen; Maria Fischer; Marianne Franz; Martin Fuchs; Melinda Goodyear; Nadja Gruber; Alex Hofer; Laura Hölzle; Evi Juen; Flora Papanthimou; Mathias Prokop; Jean Lillian Paul (2023). Practices to support co‐design processes: A case‐study of co‐designing a program for children with parents with a mental health problem in the Austrian region of Tyrol. *International Journal of Mental Health Nursing*. https://doi.org/10.1111/inm.13078

- PDF bibliographic note: The repository cover cites the 2023 journal issue; the article text is dated 2022.
- Bibliographic note: the source record lists 2022; the journal year above follows the verified PDF.
- Bibliographic note: bibliographic metadata list 2022; the journal year above follows the checked PDF.

**Study design:** Qualitative case study using partner reflections and content analysis.

**Setting:**

- Report — Whole reported project: A six-month co-design process developed a mental-health program in Tyrol, Austria. Note: The cited passage directly supports this description.

**Participants:**

- Report — Whole reported project: Twenty-six community and thirteen research partners took part across the co-design process. Note: The cited passage directly supports this description.

**Support:**

- Report — Whole reported project: Workshop communication practices included plain language and repeating technical terms. Note: The cited passage directly supports this description.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.

### 169. Moonen, Faas; Veeger, Tom (2015). Preparing Students Towards the Complexity of Today’s Practice: Start-Up in a Multidisciplinary Assignment. *Open House International*. https://doi.org/10.1108/ohi-02-2015-b0008

**Study design:** Uncontrolled historical semester-cohort comparison.

**Setting:**

- Report: The Multi-project was a semester-long assignment in the final year of a bachelor program at Eindhoven University of Technology. Note: The original report describes this study-level context or research sample.
- Case — Multidisciplinary Multi-project assignment: The Multi-project was a multidisciplinary assignment in the BSc ABP curriculum.

**Participants:**

- Report: Students undertaking the assignments were asked to complete enquiries across multiple years. Note: The original report describes this study-level context or research sample.
- Case — Multidisciplinary Multi-project assignment: A design team generally had six students.

**Support:**

- Case — Multidisciplinary Multi-project assignment: Workshop supervisors prepared issues related to the semester’s problem for students.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: Student responses to the project planning clarity item:** 5:Y; 6:U; 7:U.

**Outcome: Student responses to the project planning clarity item; result: Semester-level planning-clarity ratings around the 2011-2012 project-description and planning-script change in Figure 3:** 8:N; 9:U.

**Study:** 1:Y; 2:Y; 3:U; 4:U.

### 170. Miller, Luke; Shanley, Dianne C.; Page, Marjad; Webster, Heidi; Liu, Wei; Reid, Natasha; Shelton, Doug; West, Karen; Marshall, Joan; Hawkins, Erinn (2022). Preventing Drift through Continued Co-Design with a First Nations Community: Refining the Prototype of a Tiered FASD Assessment. *International Journal of Environmental Research and Public Health*. https://doi.org/10.3390/ijerph191811226

**Study design:** Qualitative narrative component of mixed-methods co-design workshop; Single-group pre-post workshop evaluation.

**Setting:**

- Report — Second community consultation workshop: The study focused on a two-day community consultation workshop in north-west Queensland, Australia, to refine a neurodevelopmental assessment prototype. Note: The study focuses on the second broad consultation in a larger project and is not attributed to all earlier co-design activities.
- Case — Second Yapatjarrathati community workshop: The workshop was held over two days in north-west Queensland, Australia.

**Participants:**

- Report — Workshop attendance and quantitative analysis: Forty-seven health providers and community members attended the workshop; the final quantitative analysis included 23 participants. Note: Workshop attendance and the smaller analysis sample are not interchangeable; the findings also draw on facilitator reflections.
- Case — Second Yapatjarrathati community workshop: Forty-seven community members and regional health-sector employees attended.

**Support:**

- Case — Second Yapatjarrathati community workshop: The workshop used assessment demonstrations, hands-on practice and scoring of hypothetical cases.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Qualitative narrative component of mixed-methods co-design workshop.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.


**Full checklist:** QE. Design recorded for the assessment: Single-group pre-post workshop evaluation.


**Outcome: Workshop attendees’ mean self-reported confidence in completing the assessment process:** 5:N; 6:Y; 7:Y.

**Outcome: Workshop attendees’ mean self-reported confidence in completing the assessment process; result: Paired mean confidence score before versus immediately after the workshop:** 8:U; 9:U.

**Outcome: Workshop attendees’ mean self-reported perceived competence in assessment and support:** 5:N; 6:Y; 7:Y.

**Outcome: Workshop attendees’ mean self-reported perceived competence in assessment and support; result: Paired mean perceived competence score before versus immediately after the workshop:** 8:U; 9:U.

**Outcome: Workshop attendees’ seven-item FASD and neurodevelopmental assessment knowledge score:** 5:N; 6:Y; 7:U.

**Outcome: Workshop attendees’ seven-item FASD and neurodevelopmental assessment knowledge score; result: Paired mean knowledge score before versus immediately after the workshop:** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:NA; 4:U.

### 171. Yeon Kim; Suk Lee; Changsun Ahn (2021). Project-based learning in a graduate course on home appliance engineering. *International Journal of Electrical Engineering & Education*. https://doi.org/10.1177/00207209211013445

- PDF bibliographic note: Published online-first article; issue and final publication year not established from this PDF

**Study design:** Inductive thematic analysis of student interviews; Nonrandomized comparison of PBL and non-PBL students.

**Setting:**

- Report — whole study: Graduate home appliance engineering course at one South Korean university; industry supplied project briefs.

**Participants:**

- Report — whole study: Graduate students worked in teams of two or three from at least two majors; 37 PBL students and 36 comparison students were surveyed across two years.

**Support:**

- Report — whole study: Not reproduced because of quotation or overlap with source text.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Inductive thematic analysis of student interviews.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:Y.


**Full checklist:** QE. Design recorded for the assessment: Nonrandomized comparison of PBL and non-PBL students.


**Outcome: Surveyed graduate students’ engineering attitude score:** 5:N; 6:Y; 7:U.

**Outcome: Surveyed graduate students’ engineering attitude score; result: Pooled postsemester mean PBL 112.4 vs non-PBL 105.7, t=3.22, p<.01:** 8:U; 9:U.

**Study:** 1:Y; 2:Y; 3:U; 4:N.

### 172. Kiran Kulkarni; Anila Puttannanavara (2023). PROMOTING START-UPS AMONG STUDENTS BY IDEATION WORKSHOP. *International Journal of Engineering Applied Sciences and Technology*. https://doi.org/10.33564/ijeast.2023.v07i09.030

- PDF bibliographic note: The header states 2022, while the same page states that the article was published online in January 2023; the precise issue-year interpretation remains uncertain.

**Study design:** Student ideation program description and participant survey.

**Setting:**

- Report — University ideation workshops: Ideation workshops were conducted at constituent colleges of the University of Agricultural Sciences, Dharwad. Note: Counts of workshop participants and questionnaire respondents differ elsewhere in the report.

**Participants:**

- Report — Groups presenting ideas: The report states that 70 student groups presented ideas. Note: Counts of workshop participants and questionnaire respondents differ elsewhere in the report.

**Support:**

- Report — Ideation workshop orientation: Students were oriented to the ideation process and design-thinking concepts. Note: Counts of workshop participants and questionnaire respondents differ elsewhere in the report.

**JBI appraisal**

**Selected items only:** Q. Part: Student ideation orientation and reported group prototypes. Design recorded: Student ideation program description and participant survey.


**Selected items:** 3:U; 4:U; 8:U; 10:U.


**Part-specific limitations and assessment status:**

- Student ideation orientation and reported group prototypes: not assessable. The report states group and prototype counts but does not specify an analytic procedure linking individual group prototypes to the orientation; survey respondents are a separate component with discrepant denominators.

### 173. Judith Nicogossian; Stéphane Héas; Claire Thénié; Margaux Noel; Laurent Misery; Sebastien Barbarot; Fabienne Martin Juchat (2024). Questions a patient with moderate to severe atopic dermatitis would like to be asked: Data from a qualitative study conducted by anthropologists. *JEADV Clinical Practice*. https://doi.org/10.1002/jvc2.423

**Study design:** Exploratory qualitative group study.

**Setting:**

- Report — Atopic-dermatitis focus groups: Patients took part in group interviews about their care experiences.

**Participants:**

- Report — Prestudy and main study: Four prestudy patients and twenty main-study patients participated.

**Support:**

- Case — Patient group discussions: Anthropologists facilitated patient expression during group interviews.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 174. Danielle DuPlessis; Emily Lam; Fanny Hotze; Ajmal Khan; Hiba Al-Hakeem; Stephanie McFarland; Andrea Hickling; Michael Hutchison; F. Virginia Wright; Nick Reed; Elaine Biddiss; Shannon E. Scratch (2022). R2Play development: Fostering user-driven technology that supports return-to-play decision-making following pediatric concussion. *Frontiers in Rehabilitation Sciences*. https://doi.org/10.3389/fresc.2022.1051579

**Study design:** Not extracted.

**Setting:**

- Case — R2Play initial design: An interdisciplinary team developed an assessment concept for youth athletes after concussion.

**Participants:**

- Case — Initial design team: The team included health practitioners, engineers, athletes and researchers.

**Support:**

- Case — Team knowledge sharing: Clinical and engineering partners shared knowledge and demonstrated practices or technologies.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Team knowledge sharing and development of initial design objectives: not assessable. The selected component is a narrative of the design team process. The separately conducted stakeholder interviews and their content analysis do not establish a qualitative data-collection method for the team knowledge-sharing account.

### 175. Samenjo, Karlheinz Tondo (2025). Realizing Accessible and Environmentally Sustainable Medical Devices in Low-Resource Healthcare Settings in Sub-Saharan Africa: Personal Narrative of the Designer’s Roles and Competencies. *She ji*. https://doi.org/10.1016/j.sheji.2025.01.005

**Study design:** Qualitative action-research case account.

**Setting:**

- Report — Longitudinal medical-device design narrative: The report narrates the design and integration of a medical device for low-resource healthcare settings in Kenya. Note: The setting is the design narrative and its healthcare context, not a claim about all low-resource healthcare settings in the region.
- Case — Kenyan medical device design project: The project addressed a healthcare challenge in low-resource settings in Kenya.

**Participants:**

- Report — Designer and healthcare collaborators: The designer collaborated with healthcare professionals; after discussions involving six hospitals, two hospitals agreed to join further collaboration. Note: The hospital counts describe institutional engagement at one stage and do not establish the number of individual participants in the narrative.
- Case — Kenyan medical device design project: The two-hospital collaboration included clinicians and other hospital staff.

**Support:**

- Case — Kenyan medical device design project: The author initiated visits, roundtables and brainstorming with healthcare professionals.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:Y; 8:U; 9:Y; 10:Y.

### 176. Agustin, Abang Edwin Syarif; Widyanto, David (2026). Reframing Design Practice: Ethical Design as a Practice of Inclusion and Empowerment in Marginalized Communities. *Jurnal Desain Indonesia*. https://doi.org/10.52265/jdi.v8i2.821

**Study design:** Qualitative participatory design case study.

**Setting:**

- Report: Participatory design projects were conducted in community schools in Bintaro, Tangerang Selatan, Indonesia. Note: The original report describes this study-level context or research sample.
- Case — Bintaro community school design study: The study was conducted in privately run community schools serving low-income families.

**Participants:**

- Report — School participatory design participants: Teachers, school administrators and students participated, alongside university design students who facilitated. Note: The reported roles are study-wide; no overall participant count or linkage between individual workshop cases is inferred.
- Case — Bintaro community school design study: Participants included teachers, administrators, pupils and product design students who facilitated.

**Support:**

- Case — Bintaro community school design study: Design facilitators worked with students to develop furniture sketches.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:U.

### 177. Maissa Khatib; Rushabh Shah; Ehiremen Azugbene; Matthew Paul Buman (2026). Rethinking participation: design studios for health as a scalable co-design framework for health equity. *Frontiers in Public Health*. https://doi.org/10.3389/fpubh.2025.1681798

**Study design:** Qualitative component of mixed-methods design studio evaluation.

**Setting:**

- Report — Locations of eleven design studios: The methods locate eleven sessions in the Phoenix metropolitan area and Austin, Texas, while the discussion describes eleven studios in Arizona. Note: The locations are reported as written and remain inconsistent; neither account is silently preferred.
- Case — Design Studios for Health sessions: The methods report eleven sessions in the Phoenix metropolitan area and Austin, Texas; the discussion describes all eleven as conducted in Arizona. Note: The methods list Phoenix and Austin, while the discussion describes eleven studios in Arizona; the relationship between these statements is not clarified.

**Participants:**

- Report — Design studio participants with inconsistent table totals: The methods report 90 community members, 15 community organization representatives and 10 researchers; the community-member sex categories in Table 1 total 89. Note: The 90 reported in the methods and the 34 plus 55 in the table do not match; neither number is silently corrected.
- Case — Design Studios for Health sessions: The methods report 90 community members, 15 community health organisation representatives and 10 researchers; Table 1 lists 34 male and 55 female community members, totalling 89. Note: The methods total and the Table 1 male and female counts differ; both are retained without resolving the discrepancy.

**Support:**

- Case — Design Studios for Health sessions: Each session was facilitated through three core roles.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:Y; 10:U.


**Part-specific limitations and assessment status:**

- Quantitative comparisons of session-level collaboration and trust ratings: not assessable. The extracted review description concerns collaboration and trust ratings across sessions. The article reports a session 5 collaboration mean of 8.8 while describing the collaboration measure as 0–5 on physical page 5; it also gives conflicting directions for change in trust in the abstract and results. The session samples and whether individuals recur across sessions are not established in the report. These inconsistencies and uncertain comparability prevent a dependable result-level appraisal of the stated session comparison; this status is limited to these quantitative comparisons and does not assess the separately recorded qualitative findings.

### 178. Josep Petchamé; Dubravka Novkovic; Paul Fox; Lisa Kinnear; Ricardo Torres-Kompen (2026). SDG-Driven Entrepreneurship Through Technology Solutions in Higher Education Enhanced by Problem-Based Learning: An Active Learning Approach in a Smart Classroom Environment. *Sustainability*. https://doi.org/10.3390/su18041849

**Study design:** Qualitative post-activity open-ended BLA survey.

**Setting:**

- Report — First-year project-based learning activity and its anonymous respondent sample: First-year technology-related degree activity at La Salle, Ramon Llull University, during the 2024–2025 academic year.

**Participants:**

- Report — First-year project-based learning activity and its anonymous respondent sample: The activity involved 71 student teams; 84 responses to the later survey were valid. The authors noted that anonymous responses could not be linked to teams.

**Support:**

- Report — First-year project-based learning activity and its anonymous respondent sample: The activity included instructors acting as guides or mentors, with structured class sessions and peer assessment.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:U; 9:Y; 10:U.

### 179. Hoda, Rashina; Noble, James; Marshall, Stuart (2013). Self-Organizing Roles on Agile Software Development Teams. *IEEE Transactions on Software Engineering*. https://doi.org/10.1109/tse.2012.30

**Study design:** Classic grounded theory qualitative study.

**Setting:**

- Report: The study involved software organizations in New Zealand, India and North America. Note: The original report describes this study-level context or research sample.
- Case — Observed New Zealand team meeting: A combined meeting was held for three teams in New Zealand.

**Participants:**

- Report: The methods report 58 participants from 23 software organizations: 26 in New Zealand, 28 in India and four in North America. Note: The original report describes this study-level context or research sample.
- Case — Observed New Zealand team meeting: Members of three teams and an Agile coach participated in the meeting.

**Support:**

- Case — Observed New Zealand team meeting: A team member who had contacted the customer provided requirements and clarified doubts.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 180. Gomes, Jorge; De Weerd–Nederhof, Petra C.; Pearson, Alan; Fisscher, Olaf A.M. (2001). Senior management support in the new product development process. *Creativity and Innovation Management*. https://doi.org/10.1111/1467-8691.00226

**Study design:** Analytical cross-sectional questionnaire phase of mixed-methods study.

**Setting:**

- Report: The first survey covered companies in the UK and the Netherlands; subsequent interviews were conducted in the UK. Note: The original report describes this study-level context or research sample.
- Case — Chemicals manufacturer customer visits: A chemicals manufacturer was discussed in an interview.

**Participants:**

- Report: The first phase surveyed 55 project managers in 40 companies; the second comprised 70 interviews with project team members and managers across 25 companies. Note: The original report describes this study-level context or research sample.
- Case — Chemicals manufacturer customer visits: Technical and commercial staff made joint customer visits.

**Support:**

- Case — Chemicals manufacturer customer visits: Senior management promoted joint customer visits by technical and commercial staff.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.:** 2:NA; 4:U; 6:N.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 partial correlation between commitment support and project cost: reported value -0.28; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 partial correlation between resources support and project cost: reported value -0.16; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 regression coefficient between commitment support and project cost: reported value -0.30; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 regression coefficient between resources support and project cost: reported value -0.17; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 simple correlation between commitment support and project cost: reported value -0.35; unadjusted bivariate association.:** 7:U.

**Outcome: Project manager rating of development cost relative to initial goals and other projects; Appendix Table A2 defines the average of two cost items.; result: Table 1 simple correlation between resources support and project cost: reported value -0.28; unadjusted bivariate association.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.:** 2:NA; 4:U; 6:N.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 partial correlation between commitment support and product quality: reported value +0.12; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 partial correlation between resources support and product quality: reported value +0.03; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 regression coefficient between commitment support and product quality: reported value +0.04; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 regression coefficient between resources support and product quality: reported value +0.09; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 simple correlation between commitment support and product quality: reported value +0.08; unadjusted bivariate association.:** 7:U.

**Outcome: Project manager rating of end-product quality relative to initial goals and other products; Appendix Table A2 defines the average of two quality items.; result: Table 1 simple correlation between resources support and product quality: reported value +0.09; unadjusted bivariate association.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.:** 2:NA; 4:U; 6:N.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 partial correlation between commitment support and project time: reported value -0.26; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 partial correlation between resources support and project time: reported value -0.33; partial association with the other support dimension in the model.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 regression coefficient between commitment support and project time: reported value -0.26; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 regression coefficient between resources support and project time: reported value -0.33; model also includes the other support dimension.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 simple correlation between commitment support and project time: reported value -0.40; unadjusted bivariate association.:** 7:U.

**Outcome: Project manager rating of recently completed multifunctional project development time relative to its initial goals; Appendix Table A2 specifies a single retained time item.; result: Table 1 simple correlation between resources support and project time: reported value -0.32; unadjusted bivariate association.:** 7:U.

**Study:** 1:Y; 3:U; 5:N; 8:N.

### 181. Holtzhausen, Nico; De Klerk, Jeremias J. (2018). Servant leadership and the Scrum team’s effectiveness. *Leadership & Organization Development Journal*. https://doi.org/10.1108/lodj-05-2018-0193

**Study design:** Analytical cross-sectional questionnaire survey.

**Setting:**

- Report: The Scrum survey included respondents from up to 17 companies in Western Cape, South Africa. Note: The original report describes this study-level context or research sample.
- Case — Scrum practitioner survey: The surveyed organisations were active in software development in Western Cape, South Africa.

**Participants:**

- Report — Scrum survey respondents with conflicting counts: The abstract reports 71 Scrum team members and 22 Scrum masters, whereas the sample description reports 73 team members and 22 Scrum masters. Note: The numbers conflict; neither the discrepancy nor a corrected total is resolved here.
- Case — Scrum practitioner survey: The abstract reports responses from 71 Scrum team members and 22 Scrum masters. Note: The count is attributed to the abstract: the sample description also reports 73 non-Scrum-master respondents, which does not match the abstract or the n=93 total.

**Support:**

- Case — Scrum practitioner survey: Not checked Note: The examined sections report survey ratings of leadership dimensions, but do not describe a specific performed support action; a general definition or questionnaire item was not substituted.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.:** 2:NA; 4:U; 6:N.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Accountability with perceived team effectiveness: r=0.33, p<0.01; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Authenticity with perceived team effectiveness: r=0.38, p<0.01; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Courage with perceived team effectiveness: r=0.12, not significant at p<0.05; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Empowerment with perceived team effectiveness: r=0.42, p<0.001; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Forgiveness with perceived team effectiveness: r=-0.13, not significant at p<0.05; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Humility with perceived team effectiveness: r=0.51, p<0.001; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Standing back with perceived team effectiveness: r=0.45, p<0.001; reported table n=71.:** 7:U.

**Outcome: Perceived Scrum team effectiveness measured by the team effectiveness questionnaire, as reported by non-Scrum-master team members; Table I Pearson correlations.; result: Table I, non-Scrum-master team-member Pearson correlation of Stewardship with perceived team effectiveness: r=0.51, p<0.001; reported table n=71.:** 7:U.

**Study:** 1:U; 3:U; 5:N; 8:N.

### 182. Pan-Wei Ng (2014). Software Process Improvement and Gaming using Essence: An Industrial Experience. *Journal of Industrial and Intelligent Information*. https://doi.org/10.12720/jiii.2.1.45-50

**Study design:** Descriptive workshop votes within an industrial case.

**Setting:**

- Report — Industrial process-improvement workshop: The report concerns a two-day software process-improvement workshop at an embedded-device company. Note: The company and workshop are the reported context; outcomes are not generalized to the entire company.
- Case — Embedded product company workshop: A workshop was conducted with an embedded product company.

**Participants:**

- Report — Workshop participants: Thirty-eight engineers with different roles participated in the workshop. Note: The 38 participants are not equated with the company division’s 500 engineers.
- Case — Embedded product company workshop: Thirty-eight participants worked in four groups with a range of roles.

**Support:**

- Case — Embedded product company workshop: Facilitators guided participants to describe their existing software development process using Essence.

**JBI appraisal**

**Selected items only:** P. Part: Workshop votes and counts for process-improvement priorities. Design recorded: Descriptive workshop votes within an industrial case.


**Selected items:** 1:U; 2:U; 3:U; 4:Y; 5:U; 6:U; 7:U; 8:U.


**Part-specific limitations and assessment status:**

- Potential qualitative analysis of experiences in the Essence gaming workshop: not assessable. The prior review could not identify a qualitative research analysis behind the reported workshop experience. The excerpt locates the reported activity and does not prove that an analysis was absent. The recorded passage identifies 38 engineers with different roles at a two-day workshop; it does not by itself establish how qualitative experiences were analysed.
- Workshop votes and counts for process-improvement priorities: tool not applicable. This empirical practitioner case describes an actual two-day workshop with 38 staff in four groups; participants identified and ranked problems, and the authors tabulated the number of participants rating practices as strongly contributing to improvement areas and plotted the results (physical pages 4–5). The reported choices are not evidence that the backlog was implemented afterward. Neither the revised JBI analytical cross-sectional association tool nor the quasi-experimental comparison tool fits these one-time descriptive counts. Applicable methodological questions informed by JBI prevalence checklist domains, not a full item-level checklist appraisal: setting, composition and participant count are stated (2014 item 4); the selection process and representativeness beyond this one company are not established (items 1–3); how many participants voted on each item is not clear in the examined results (item 5); the voting task is described but measurement reliability is not reported (items 6–7); descriptive counts are shown but do not establish comparative or causal effects (item 8). The separate end-of-workshop narrative feedback is not silently treated as coded qualitative analysis.

### 183. Giuseppe Ng; Rey Vincenzo Cruz (2020). Student and Faculty Adviser Insights in an Agile Methodology Integrated Filipino Company-Sponsored I.T. Capstone Program. *International Journal of Hybrid Information Technology*. https://doi.org/10.21742/ijhit.2020.13.2.03

**Study design:** Qualitative content analysis of capstone feedback.

**Setting:**

- Report: The study concerned a Filipino company-sponsored IT capstone program integrating Agile methodology. Note: The original report describes this study-level context or research sample.
- Case — Student group affected by illness: An Agile software-development capstone project in a Bachelor of Science in IT program.

**Participants:**

- Report: Survey data covered 90 IT students across four academic years; faculty advisers also wrote observations about their student groups. Note: The original report describes this study-level context or research sample.
- Case — Student group affected by illness: Group members worked with a faculty adviser.

**Support:**

- Case — Student group affected by illness: A faculty adviser helped the group assess and plan around illness during weekly scrums.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Students’ reported proportion of ticket-task time spent researching: outside appraisal scope. Figure 1 summarizes individual students’ reported research time across the programme without connecting the numerical ratings to the identified faculty-adviser support in the extracted cases, teams, or specific projects. Therefore this descriptive numeric result is not appraised as the reported outcome of those supported cases; the student responses and adviser observations assessed qualitatively remain separate.

### 184. Nuala McLaughlin-Borlace; Stephanie Craig; Tara Anderson; Nuala Flood; Laura Steele; Tracy Levett-Jones; Fadwa Alhalaiqa; Dalal Hammoudi Halat; Norfadzilah Ahmad; Jesus Sánchez-Martín; Charlotte McArdle; Naomi Tutticci; Sara Lynch; Rose Gallagher; Gary Mitchell (2026). Student participation in accelerated experience-based co-design for healthcare decarbonisation education: a focused ethnographic study. *BMC Medical Education*. https://doi.org/10.1186/s12909-026-10015-1

**Study design:** Qualitative focused ethnographic study.

**Setting:**

- Report: Three workshops were held in person at a UK university and the final workshop online. Note: The original report describes this study-level context or research sample.
- Case — Healthcare decarbonisation e-resource workshops: Four workshops developed an e-resource on healthcare decarbonisation.

**Participants:**

- Report — Workshop and focus-group student participants: Four co-design workshops involved 15 pre-registration students in nursing and pharmacy; focus groups followed. Note: The count refers to students participating in the workshops; it is not an item-specific attendance count or a count of the separate international observer panel.
- Case — Healthcare decarbonisation e-resource workshops: Fifteen pre-registration health professional students took part in the workshops.

**Support:**

- Case — Healthcare decarbonisation e-resource workshops: Facilitators synthesised ideas into an e-resource design.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 185. Kirkscey, Russell; Attaluri, Anilchandra (2022). Student Technical Editors as Writing Consultants for Mechanical Engineering Capstone Design Teams: A Case Study in Interdisciplinary Curriculum Development. *Programmatic Perspectives*. [DOI not recorded]

**Study design:** qualitative component of educational case study.

**Setting:**

- Report: The study took place in a mechanical-engineering capstone course and technical-writing program at Penn State Harrisburg. Note: The original report describes this study-level context or research sample.
- Case — Mechanical engineering capstone writing initiative: Mechanical engineering teams undertook research and development projects with industry clients.

**Participants:**

- Report: Five mechanical-engineering students, two student editors, the course instructor and internship adviser consented to participate in the research. Note: The original report describes this study-level context or research sample.
- Case — Mechanical engineering capstone writing initiative: Two technical writing students supported five teams with sixteen students.

**Support:**

- Case — Mechanical engineering capstone writing initiative: Student editors created or adapted a style guide and templates for the teams.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:Y; 10:U.

### 186. Alessandra Napoli; Kevin Nyaga; Dhinesh Radhakrishnan; Jennifer J. DeBoer (2020). Students Becoming Supervisors: Student Transformation during a Cross-National, Collaborative Community Engineering Project. *Purdue Journal of Service-Learning and International Engagement*. https://doi.org/10.5703/1288284317243

**Study design:** Qualitative narrative analysis of two student authors.

**Setting:**

- Report — Cross-national community engineering project: The report examines student experiences in a collaborative community gym engineering project at Tumaini Innovation Center in Eldoret, Kenya. Note: The community project is distinguished from other activities mentioned at the center.
- Case — Kenyan community gym project: The project developed a community gym in Eldoret, Kenya.

**Participants:**

- Report: The analysis drew on written reflections by two authors, an interview with the second author and first-author project notes. Note: The original report describes this study-level context or research sample.
- Case — Kenyan community gym project: Graduate and undergraduate students from PU worked with management and students at TIC.

**Support:**

- Case — Kenyan community gym project: The first author reported that her team and mentors showed confidence in her and created space to experiment.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:U.

### 187. Mchunu, K.J.; Moodley, S. (2019). Students’ reflection on co-design: A cross-disciplinary collaboration between two SADC countries. *South African Journal of Higher Education*. https://doi.org/10.20853/33-2-2829

**Study design:** Qualitative student reflection study.

**Setting:**

- Case — Polar Project collaboration: A cross-disciplinary project included students from a Windhoek-based university.

**Participants:**

- Report — Polar Project participants: The project included students in computing and informatics at the Windhoek-based university.

**Support:**

- Case — EKO classroom team: A mentor arranged a school visit for the team during a later iteration.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Mentors’ account of EKO project support and design change: not assessable. The reported mentoring sequence is a project-process narrative. The separate student reflective analysis has its own qualitative appraisal; that appraisal does not appraise this account.

### 188. Higgins, Erin; Oliver, Zaria; Hamidi, Foad (2025). Supporting Campus Activism through Creating DIY-AT in a Social Justice Aligned Makerspace. *ACM Transactions on Accessible Computing*. https://doi.org/10.1145/3715965

**Study design:** Qualitative case series with inductive thematic analysis.

**Setting:**

- Report: A university makerspace supported participatory design of assistive technology with people connected to disability advocacy. Note: The original report describes this study-level context or research sample.
- Case — P3 turn-signal extender project: P3 developed a turn-signal extender for driving.

**Participants:**

- Report: The study involved four undergraduates and one graduate student with disabilities, a medical professional, and a university disability-services staff member. Note: The original report describes this study-level context or research sample.
- Case — P3 turn-signal extender project: P3 was a computer science student.

**Support:**

- Case — P3 turn-signal extender project: P3 received three basic CAD sessions and research-team guidance.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 189. Aino Ahtinen; Kirsikka Kaipainen; Salla Jarske; Kaisa Väänänen (2023). Supporting Remote Social Robot Design Collaboration with Online Canvases: Lessons Learned from Facilitators’ and Participants’ Experiences. *International Journal of Social Robotics*. https://doi.org/10.1007/s12369-023-00966-6

**Study design:** Qualitative component of mixed methods study.

**Setting:**

- Report: The study combined short-term social-robot design workshops and a seven-week university social-robotics course project. Note: The original report describes this study-level context or research sample.
- Case — Tampere social robotics course: The design project took place in Tampere University’s social robotics course.

**Participants:**

- Report: The projects included high-school and university students in short workshops and a university-course project. Note: The original report describes this study-level context or research sample.
- Case — Tampere social robotics course: Nineteen university students formed seven teams.

**Support:**

- Case — Tampere social robotics course: The facilitator followed group work on canvases and supplied written feedback, questions and comments.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Post-project participant feedback ratings on workshops and course: tool not applicable. The questionnaire reports descriptive ratings for three different workshop or course settings, including participant experience and participation, without an analytical exposure-outcome comparison or a pre-post intervention comparison. The reviewed revised JBI analytical cross-sectional and quasi-experimental checklists are therefore not applicable to these descriptive survey results. This is separate from the qualitative appraisal of participants and facilitators. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is descriptive feedback in three workshop or course settings; the existing assessment does not identify a target-population prevalence estimate. The setting and relevant response unit are material to interpretation; similarity of results across settings is not assumed. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 190. Senapathi, Mali; Drury‐Grogan, Meghann L. (2021). Systems Thinking Approach to Implementing Kanban: A case study. *Journal of Software Evolution and Process*. https://doi.org/10.1002/smr.2322

- Bibliographic note: the review lead selected the year above; the source record lists 2020. This choice does not establish the relationship between versions.

**Study design:** qualitative interview component of case study.

**Setting:**

- Report: The research examined a 35-person government digital-product unit in New Zealand, focusing on content design and development teams. Note: The original report describes this study-level context or research sample.
- Case — New Zealand digital services unit: A government digital-services unit developed public-facing information websites.

**Participants:**

- Report: Seven interviews covered a developer, product owner, three content designers, a Kanban coach, and lead product owner. Note: The original report describes this study-level context or research sample.
- Case — New Zealand digital services unit: The study focused on the content design and development teams.

**Support:**

- Case — New Zealand digital services unit: An external coach helped the team make its existing workflow explicit and visualise it.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 191. Steel, Jill; Williams, Joanne M.; McGeown, Sarah (2022). Teacher-researcher collaboration in animal-assisted education: Co-designing a reading to dogs intervention. *Educational Research*. https://doi.org/10.1080/00131881.2021.2016061

**Study design:** Qualitative evaluation of a teacher researcher co-design framework.

**Setting:**

- Report — Teacher–researcher co-design: The study co-designed a reading-to-dogs intervention for primary-aged children through collaboration between a researcher and teachers from different school contexts. Note: The reported setting is the intervention co-design process, not implementation across all primary schools.
- Case — Reading-to-dogs co-design: The group co-designed a reading-to-dogs intervention for primary school children.

**Participants:**

- Report — Teachers and researcher in co-design: Three teachers from different school contexts and one researcher collaborated to co-design the intervention. Note: The count concerns the co-design collaborators; it is not a count of children who might later receive the intervention.
- Case — Reading-to-dogs co-design: One researcher and three teachers co-designed the intervention.

**Support:**

- Case — Reading-to-dogs co-design: The teachers received a research and policy brief.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 192. Michel F. Couturier; Guida Bendrich (2021). Teaching process design in a multidisciplinary capstone design course. *The Canadian Journal of Chemical Engineering*. https://doi.org/10.1002/cjce.24063

- PDF bibliographic note: The PDF shows 2021 and provisional pages 1–13; final volume and issue publication year are not confirmed.

**Study design:** Not extracted.

**Setting:**

- Report — Process design section of the multidisciplinary capstone: Full-year multidisciplinary capstone design course at the University of New Brunswick.

**Participants:**

- Report — Process design section of the multidisciplinary capstone: The process design section included 93 students in the 2018–2019 and 2019–2020 offerings. Teams were co-mentored by faculty and practising engineers.

**Support:**

- Report — Process design section of the multidisciplinary capstone: Faculty and industry co-mentors provided feedback on reports at design milestones.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

**Part-specific limitations and assessment status:**

- Author account of students using co-mentor feedback to improve milestone designs and reports: tool not applicable. The article reports this practice and outcome in the authors’ own descriptive account. The qualitative JBI research checklist does not fit this specific account because the report provides no identified qualitative research methodology or participant data for this observation. This does not rate the paper as a whole or the separate quantitative peer-rating analysis.

### 193. Trischler, Jakob; Kristensson, Per; Scott, Don (2018). Team diversity and its management in a co-design team. *Journal of service management*. https://doi.org/10.1108/josm-10-2016-0283

**Study design:** Controlled field experiment with team allocation method unreported; qualitative component of mixed method field experiments.

**Setting:**

- Report: Two studies concerned service innovation at four libraries: Study 1 at Library 1 and Study 2 at Libraries 2–4. Note: The original report describes this study-level context or research sample.
- Case — Library 1 design experiments: Two field experiments took place at Library 1.

**Participants:**

- Report: The professional samples comprised 20 people in Study 1 and 25 in Study 2; 46 and 60 library users respectively registered for the two studies. Note: The original report describes this study-level context or research sample.
- Case — Library 1 design experiments: Each experiment included three co-design teams of two users and two professionals each.

**Support:**

- Case — Library 1 design experiments: The principal researcher introduced each design stage and allocated design tools and equipment.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: qualitative component of mixed method field experiments.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.


**Full checklist:** QE. Design recorded for the assessment: Controlled field experiment with team allocation method unreported.


**Outcome: Independent judges’ user-benefit rating of each team design concept:** 5:N; 6:Y; 7:Y.

**Outcome: Independent judges’ user-benefit rating of each team design concept; result: Experiment A A3 mixed team concept versus A1 professional-only concept user-benefit mean difference 1.21 t 5.14 as reported:** 8:Y; 9:N.

**Study:** 1:Y; 2:Y; 3:N; 4:Y.

### 194. Witherell, C.J.; Maar, Aliaa; Dougherty, Presley; Menold, Jessica (2026). The Art of Facilitation: Building Trust and Psychological Safety in Design Teams. *Journal of Mechanical Design*. https://doi.org/10.1115/1.4071514

**Study design:** Exploratory cross-sectional behavioral and survey association.

**Setting:**

- Report — Design-thinking workshop and five teams: The study observed five design teams in a three-hour workshop held after a design-thinking conference at Pennsylvania State University. Note: All five teams were observed in this workshop; the workshop setting is not generalized to other facilitation studies.
- Case — Post-conference Design Thinking workshop: A three-hour Design Thinking workshop followed a conference at Pennsylvania State University.

**Participants:**

- Report: Thirty-three participants included five facilitators and 28 design-team members. Note: The original report describes this study-level context or research sample.
- Case — Post-conference Design Thinking workshop: Twenty-eight participants were assigned to five teams, each with a facilitator.

**Support:**

- Case — Post-conference Design Thinking workshop: The teams received a design challenge and guidance through four stages of design thinking.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Team members self-reported psychological safety on a seven-item scale:** 2:NA; 4:Y; 6:Y.

**Outcome: Team members self-reported psychological safety on a seven-item scale; result: Table 2 Spearman association of facilitator verbal engagement frequency and psychological safety rs 1.00 p less than 0.001 as reported:** 7:U.

**Study:** 1:U; 3:U; 5:Y; 8:Y.

### 195. Jade Davies; Ben Redmayne; Leon Allain; Lucy Portway; Will Mandy; Kate Cooper; Laura Crane (2024). The Codesign and Initial Evaluation of a Peer Support Program for Autistic Young Adults. *Autism in Adulthood*. https://doi.org/10.1089/aut.2023.0153

- PDF bibliographic note: The checked PDF is a manuscript noting a published journal version; the publisher version was not independently checked for this author list.

**Study design:** Qualitative team reflection on co-design within mixed feedback evaluation.

**Setting:**

- Report — Online peer-support programme development and evaluation: The study co-designed and initially evaluated a six-session online peer-support programme for autistic young adults. Note: The six programme sessions are not equated with the separate co-design sessions.
- Case — Autistic young adults co-design panel: Three co-design sessions were held virtually on Zoom.

**Participants:**

- Report: Ten autistic young adults joined the co-design team; 60 autistic young adults subsequently attended program iterations, of whom 39 completed the pre-program questionnaire and 16 completed both questionnaires. Note: The original report describes this study-level context or research sample.
- Case — Autistic young adults co-design panel: Ten autistic young adults were selected for the co-design panel.

**Support:**

- Case — Autistic young adults co-design panel: Panel members received agendas and staff profiles before each session.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:U; 8:U; 9:Y; 10:Y.

### 196. Aneta Ozierańska; Agnieszka Skomra; Dorota Kuchta; Paweł Rola (2016). The critical factors of Scrum implementation in IT project – the case study. *Journal of Economics and Management*. https://doi.org/10.22367/jem.2016.25.06

- Bibliographic note: the PDF title above differs from the source-record title.
- Bibliographic note: the PDF title above differs from the linked-item title.

**Study design:** Participatory qualitative case study.

**Setting:**

- Report — Single organizational case study: The empirical case study concerned Scrum implementation at a French IT enterprise. Note: The paper describes a single case; the accompanying literature review is distinct from the observed organizational project.
- Case — Scrum implementation in French IT enterprise: The case study took place at a French IT enterprise. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Scrum team in the observed project: The observed Scrum team had five or six permanent members in one approximately three-month project cycle. Note: The reported number concerns permanent team members in one cycle, not necessarily every person involved in the project.
- Case — Scrum implementation in French IT enterprise: The Scrum team had five or six permanent members during one project cycle. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Case — Scrum implementation in French IT enterprise: The Scrum Master was available to the development team for half of working time. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 197. Shih-Yao Lai; Liang-Gui Yu; Shang-Hsien Hsieh; Mei-Mei Song; Te-Sheng Chang (2019). The Development and Application of Co-design Modules for Multidisciplinary Collaboration and Facilitating Creativity: An Experience from D-School@NTU. *International Journal of Information and Education Technology*. https://doi.org/10.18178/ijiet.2019.9.2.1179

**Study design:** Qualitative observations and focus group component of mixed-method workshop study; Uncontrolled sequential within-workshop comparison.

**Setting:**

- Report — Co-design module workshop: The reported module test was a two-day workshop at D-School@NTU in 2017, using a Taipei neighbourhood as its learning project. Note: The 2017 workshop is distinguished from the earlier project that informed the module development.
- Case — 2017 D-School workshop: A two-day workshop was held at D-School@NTU in 2017. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Co-design workshop students: Twenty-four undergraduate and postgraduate students from different disciplines participated in the workshop. Note: This count concerns the 2017 workshop; it is not transferred to the earlier project.
- Case — 2017 D-School workshop: Twenty-four students attended the workshop. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Case — 2017 D-School workshop: Students used co-design toolkits with instruction booklets; tutors and teaching assistants observed and advised as needed. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q. Design recorded for the assessment: Qualitative observations and focus group component of mixed-method workshop study.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Full checklist:** QE. Design recorded for the assessment: Uncontrolled sequential within-workshop comparison.


**Outcome: Student-reported effectiveness of within-group communication on a 1–10 questionnaire following workshop activities.:** 5:U; 6:Y; 7:U.

**Outcome: Student-reported effectiveness of within-group communication on a 1–10 questionnaire following workshop activities.; result: Figure 14 compares student ratings of effective intra-group communication for similar-discipline and multidisciplinary grouping; 19 valid questionnaire responses are reported.:** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:U; 4:N.

### 198. Sarin, Shikhar; McDermott, Christopher (2003). The Effect of Team Leader Characteristics on Learning, Knowledge Application, and Performance of Cross-Functional New Product Development Teams. *Decision Sciences*. https://doi.org/10.1111/j.1540-5414.2003.02350.x

- Bibliographic note: the PDF title above differs from the linked-item title.

**Study design:** Analytical cross-sectional team survey.

**Setting:**

- Report — Survey of new product development teams: The study examined cross-functional new product development teams in high-tech industries. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Survey of new product development teams: The analysis used 229 surveys from 52 teams. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Report — Survey of new product development teams: The study examined the extent to which team leaders involved members in decisions. Note: This is a measured leadership practice across teams; it is not a separately observed intervention.

**JBI appraisal**

**Full checklist:** CS.


**Outcome: Respondent-reported team learning and knowledge application measured with six items:** 2:NA; 4:Y; 6:Y.

**Outcome: Respondent-reported team learning and knowledge application measured with six items; result: Table 3 unstandardized participation coefficient for team learning b 0.23 df 219 p less than 0.001:** 7:U.

**Study:** 1:Y; 3:Y; 5:Y; 8:U.

### 199. Boyle, Bryan; Arnedillo-Sanchez, Inmaculada (2022). The Inclusion of Children on the Autism Spectrum in the Design of Learning Technologies: A Small-Scale Exploration of Adults’ Perspectives. *Frontiers in Education*. https://doi.org/10.3389/feduc.2022.867964

**Study design:** qualitative exploratory study with grounded-theory-informed sampling and thematic analysis.

**Setting:**

- Case — Participatory literacy app design project: Children and adult co-designers worked on a literacy app for a special education classroom. Note: The passage identifies this characteristic within the specified scope.
- Report — Whole report: Four design workshops over six weeks developed a literacy application for a special education classroom. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Participatory literacy app design project: Five autistic children participated with teachers and technology developers. Note: Only the number of children is stated here because the paper reports inconsistent adult role counts across sections.
- Report — Whole report: Five autistic children joined the design workshops alongside five adult co-designers; the study collected adult perspectives. Note: Five adult participants and five children are distinguished. The abstract reports three teachers and two developers, while the results refer to three designers and two teachers; this role-count inconsistency is not resolved.

**Support:**

- Case — Participatory literacy app design project: Adults supported the children to create visual and audio artefacts during the second workshop. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:U; 9:Y; 10:Y.

### 200. Kirwin B Matthews; Maureen C Tanner (2022). THE INFLUENCE OF NATIONAL CULTURE DIMENSIONS ON AGILE PRACTICES: THE CASE OF SOUTH AFRICAN SOFTWARE DEVELOPMENT TEAMS. *IADIS INTERNATIONAL JOURNAL ON COMPUTER SCIENCE AND INFORMATION SYSTEMS*. https://doi.org/10.33965/ijcsis_2022170206

**Study design:** Qualitative interpretive practitioner interviews.

**Setting:**

- Report — South African Agile interview study: The study examined Agile practices in South African software development teams. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — South African Agile interview study: The study conducted 26 interviews with project team members and stakeholders across teams and companies. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Case — Account of interviewee P26: P26 described using planning poker to obtain different perspectives and reach agreement on a sprint commitment. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:U; 10:U.

### 201. Candice Oster; Ashleigh Powell; Claire Hutchinson; Debra Anderson; Bill Gransbury; Martin Walton; Jenny O'Brien; Susan Raven; Svetlana Bogomolova (2024). The process of co‐designing a model of social prescribing: An Australian case study. *Health Expectations*. https://doi.org/10.1111/hex.14087

**Study design:** qualitative workshop component of co-design case.

**Setting:**

- Report — Regional Australian social prescribing project: The project co-designed a social prescribing model in a regional area of Australia. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Regional Australian social prescribing project: Four workshops involved health and social care professionals and community members. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Report — Regional Australian social prescribing project: Members of the steering committee facilitated workshops and participated in project design and recruitment. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:U; 8:U; 9:Y; 10:U.


**Part-specific limitations and assessment status:**

- Provider workshop vote on the draft social prescribing model: tool not applicable. The 15-of-16 count records a single facilitated design-workshop vote on whether participants liked a draft model, not a separately designed quantitative evaluation of a support-outcome association or a before-after comparison. The analytical cross-sectional and quasi-experimental checklists are therefore not applicable to this vote; the status does not assess the qualitative study as a whole.

### 202. Nadia Rene Odlum; Morwenna Collett (2022). The Right to Play: Snakes and Ladders. *The Journal of Public Space*. https://doi.org/10.32891/jps.v7i2.1501

**Study design:** Qualitative descriptive case narrative.

**Setting:**

- Case — Snakes and Ladders mural: The public art project created a mural in Sydney Olympic Park. Note: The passage identifies this characteristic within the specified scope.
- Report — Whole report: The public art project created a 50-metre ground mural in Sydney Olympic Park commissioned by its authority. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — Snakes and Ladders mural: The artists Digby Webster and Nadia Odlum collaborated on the artwork. Note: The passage identifies this characteristic within the specified scope.
- Report — Whole report: Two artists collaborated; one had an art mentor, and volunteers helped during painting. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — Snakes and Ladders mural: Art mentor Rosell Flatley supported Digby Webster in the studio and on site. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:U; 8:Y; 9:U; 10:Y.

### 203. Talar B. Yacoubian; Dena A. Al-Thani; Michael Aupetit (2021). The Role of a Facilitator in Co-Design Applications for Exploratory Analysis in Domains of High Complexity: The Case of MAHiCGO. *IEEE Access*. https://doi.org/10.1109/access.2021.3063468

**Study design:** Qualitative interview observation and usability evaluation component of mixed-method co-design case.

**Setting:**

- Case — MAHiCGO visualisation project: The co-design project developed MAHiCGO for the visualisation of biological data. Note: The passage identifies this characteristic within the specified scope.
- Report — Whole report: The project co-designed MAHiCGO to visually explore biological data including gene expression, Hi-C and Gene Ontology. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Participants:**

- Case — MAHiCGO visualisation project: The process included four domain experts. Note: The passage identifies this characteristic within the specified scope.
- Report — Whole report: Four domain experts participated, working with a principal investigator, an HCI researcher and a visualisation expert. Note: Whole-report overview; the cited passages support the elements of the stated characteristic.

**Support:**

- Case — MAHiCGO visualisation project: The principal investigator facilitated four requirement-gathering interviews. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Participant reports of prototype usefulness after summative evaluation: tool not applicable. The reported usefulness results are individual users' verbal observations and the summary that all users found the prototype useful. Appendix F presents verbatim observations rather than a separate quantitative association or pre-post comparison. The analytical cross-sectional and quasi-experimental checklists are not applicable to this reported component; this does not assess the article as a whole.

### 204. Boukje Compen; Wouter Schelfhout (2020). The Role of External and Internal Team Coaches in Teacher Design Teams. A Mixed Methods Study. *Education Sciences*. https://doi.org/10.3390/educsci10100263

**Study design:** Analytical cross-sectional component of mixed methods study; Qualitative coach interviews in explanatory sequential mixed-methods study.

**Setting:**

- Report — Flemish teacher design team trajectory: The study examined teacher design teams in Flanders, Belgium. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Flemish teacher design team trajectory: Sixty-three teachers in 18 teacher design teams completed questionnaires. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Case — Team coached by Coach E: Coach E reported encouraging the team to set goals. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** CS. Design recorded for the assessment: Analytical cross-sectional component of mixed methods study.


**Outcome: Teacher-reported psychological safety within teacher design teams:** 2:NA; 4:U; 6:N.

**Outcome: Teacher-reported psychological safety within teacher design teams; result: Table 2 psychological-safety comparison external versus internal coaching t minus 2.61 p at most 0.05:** 7:U.

**Study:** 1:Y; 3:Y; 5:N; 8:Y.


**Full checklist:** Q. Design recorded for the assessment: Qualitative coach interviews in explanatory sequential mixed-methods study.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 205. Vivek Rao; George W. Moore; Osita Anders Udekwu; Björn Hartmann (2020). Tracing stories across the design process: a study of engineering students’ engagement with storytelling in an undergraduate human-centered design course. *International journal of engineering education*. [DOI not recorded]

**Study design:** Not extracted.

**Setting:**

- Report — Human-centered design course: A university course in the United States.

**Participants:**

- Report — Course cohort: Twenty undergraduate students were enrolled in the course.

**Support:**

- Case — Prototype assignment prompt: The assignment required students to represent the experience created by their solution.

**JBI appraisal**

No checklist or selected-item assessment is recorded for this source record.

### 206. Taylor, Dorothy G.; Magleby, Spencer P.; Todd, Robert H.; Parkinson, Alan R. (2001). Training faculty to coach capstone design teams. *International journal of engineering education*. [DOI not recorded]

**Study design:** Qualitative component of mixed-methods team study.

**Setting:**

- Report — Brigham Young University capstone program: The capstone program involved industrially sponsored design-and-build projects. Note: The passage identifies this characteristic within the specified scope.

**Participants:**

- Report — Brigham Young University capstone program: Students worked in teams of five or six. Note: The passage identifies this characteristic within the specified scope.

**Support:**

- Report — Brigham Young University capstone program: Coaches helped teams prepare for and reflect on periodic design reviews. Note: The passage identifies this characteristic within the specified scope.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Survey correlations of coach indicators with design team success: not assessable. The article reports positive correlations but does not identify the survey-specific sample, measurement and timing sufficiently to determine the study design and apply a quantitative JBI checklist.

### 207. Mark Goodhew; Sonia Matiuk; Carmen Axisa; Chris Gough; Jo River (2025). Transforming Alcohol and Other Drug Education Through Co‐Design. *International Journal of Mental Health Nursing*. https://doi.org/10.1111/inm.70009

**Study design:** qualitative descriptive interview study.

**Setting:**

- Report: A co-design process for an alcohol and other drugs clinical education program.

**Participants:**

- Report: Five people with lived experience, three clinicians and three academics co-designed the program.

**Support:**

- Report: An experienced co-design facilitator facilitated the co-design meetings.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:Y; 10:Y.

### 208. Jasneet Parmar; Tanya L’Heureux; Richard Lewanczuk; Jonathan Lee; Lesley Charles; Laurel Sproule; Isabel Henderson; Esha Ray Chaudhuri; Jim Berry; Kimberly Shapkin; Linda Powell; David Nicholas; Glenda Tarnowski; Myles Leslie; Michelle Lobchuk; Joanne Kaattari; Ambere Porter; Vivian Ewa; Linda Podlosky; Jacqueline Pei; Sarah Mosaico; Jamie Penner; Shannon Saunders; Sharon Anderson (2025). Transforming Care Through Co-Design: Developing Inclusive Caregiver-Centered Education in Healthcare. *Healthcare*. https://doi.org/10.3390/healthcare13030254

**Study design:** Qualitative focus group study.

**Setting:**

- Report: A CCCE co-design group.

**Participants:**

- Report: The co-design group included 155 collaborators.

**Support:**

- Report: A research team of five convened and facilitated the co-design group.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:Y; 8:Y; 9:Y; 10:U.

### 209. Timothy E. Burdick; Daniel S. Moran; Brant J. Oliver; Amy Eilertsen; Jennifer Raymond; Shoshana J. Hort; Stephen J. Bartels (2022). Transitional Care Management Quality Improvement Methods That Reduced Readmissions in a Rural, Primary Care System. *The Journal of the American Board of Family Medicine*. https://doi.org/10.3122/jabfm.2022.03.190435

**Study design:** Uncontrolled interrupted before-and-after quality improvement evaluation.

**Setting:**

- Report: Dartmouth Health, an integrated system serving a predominantly rural catchment area.

**Participants:**

- Report: The primary care service line included 107 adult primary care providers.

**Support:**

- Report: The improvement support team created standardized transitional care management job aids.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: System-wide monthly number of transitional care management episodes documented in the electronic health record.:** 5:Y; 6:N; 7:Y.

**Outcome: System-wide monthly number of transitional care management episodes documented in the electronic health record.; result: Average monthly documented episodes during pre-rollout baseline (84) versus improvement support team engagement (444); reported P < .01.:** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:N; 4:U.

### 210. Bagot, Kathleen L; Cadilhac, Dominique A; Kim, Joosup; Vu, Michelle; Savage, Mark; Bolitho, Les; Howlett, Glenn; Rabl, Justin; Dewey, Helen M; Hand, Peter J; Denisenko, Sonia; Donnan, Geoffrey A; Bladin, Christopher F (2017). Transitioning from a single-site pilot project to a state-wide regional telehealth service: The experience from the Victorian Stroke Telemedicine programme. *Journal of Telemedicine and Telecare*. https://doi.org/10.1177/1357633x17734004

**Study design:** Qualitative naturalistic service case study.

**Setting:**

- Report: The Victorian Stroke Telemedicine programme operated with 16 hospitals in 2017.

**Participants:**

- Report: The Florey housed the operational and research teams together.

**Support:**

- Report: Co-housing the operational and research teams supported ongoing liaison.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:U; 8:U; 9:U; 10:U.

### 211. Shen, Luyao; Zhang, Zhongyue; Wei, Qianjie; Lik-Hang, Lee; Hui, Pan; Fan, Mingming (2026). Understanding and Designing Technology to Support Mentoring Functions in Chinese Design Teams. *International Journal of Human-Computer Interaction*. https://doi.org/10.1080/10447318.2026.2651347

**Study design:** qualitative interview study.

**Setting:**

- Report: Chinese design teams.

**Participants:**

- Report: Twenty-three Chinese designers took part in in-depth interviews.

**Support:**

- Report: Mentors tailored their guidance to mentees’ educational backgrounds.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:Y; 7:U; 8:Y; 9:Y; 10:U.

### 212. Binkhorst, F.; Handelzalts, A.; Poortman, C.L.; Van Joolingen, W.R. (2015). Understanding teacher design teams – A mixed methods approach to developing a descriptive framework. *Teaching and Teacher Education*. https://doi.org/10.1016/j.tate.2015.07.006

**Study design:** Cross-sectional questionnaire within explanatory sequential mixed methods study; Qualitative interview component of explanatory sequential mixed-methods study.

**Setting:**

- Report — Networked teacher design teams: The study concerned networked teacher design teams organized by a university in the Netherlands, with questionnaire and interview components. Note: The questionnaire covers a wider set of teams than the four teams interviewed; the two samples are not treated as identical.
- Case — Teacher design team A: Team A worked on educational modules.

**Participants:**

- Case — Teacher design team A: All members of team A taught the same subject.
- Report: Ninety-four respondents from 14 teacher design teams completed the questionnaire.

**Support:**

- Case — Teacher design team A: The team coach coordinated joint definition of a shared goal.

**JBI appraisal**

**Full checklist:** CS. Design recorded for the assessment: Cross-sectional questionnaire within explanatory sequential mixed methods study.


**Outcome: Teacher-reported satisfaction with teacher design team participation and results, measured by a two-item scale.:** 2:NA; 4:Y; 6:N.

**Outcome: Teacher-reported satisfaction with teacher design team participation and results, measured by a two-item scale.; result: Table 3 reports the correlation between the perceived team coach scale and satisfaction as r = .73, p < .01, among questionnaire respondents.:** 7:U.

**Study:** 1:Y; 3:U; 5:N; 8:Y.


**Full checklist:** Q. Design recorded for the assessment: Qualitative interview component of explanatory sequential mixed-methods study.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 213. Sandholdt, Catharina Thiel; Srivarathan, Abirami; Kristiansen, Maria; Malling, Gritt Marie Hviid; Olesen, Kathrine Vingum Møller; Jeppesen, Mette; Lund, Rikke (2022). Undertaking graphic facilitation to enable participation in health promotion interventions in disadvantaged neighbourhoods in Denmark. *Health Promotion International*. https://doi.org/10.1093/heapro/daac034

**Study design:** Qualitative ethnographic participatory intervention case.

**Setting:**

- Report: A health promotion intervention in a multi-ethnic disadvantaged neighbourhood in Denmark.
- Case — Neighbourhood health promotion workshop: A two-hour workshop took place in the neighbourhood community house.

**Participants:**

- Report — Target residents and later interviews: Middle-aged and older residents were invited; in a later phase, seven residents were interviewed about lockdown experiences. Note: The two phases are distinct; overlap and the total number of unique residents across phases are not established.
- Case — Neighbourhood health promotion workshop: Twenty-six residents, three researchers and a graphic facilitator attended.

**Support:**

- Case — Neighbourhood health promotion workshop: The graphic facilitator created a visual record of residents’ ideas.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:Y; 8:Y; 9:U; 10:Y.

### 214. Laura J. Gardner; Justin Brunson; Megan McIntyre; John Langell (2018). Use of an Interdisciplinary Student Medical Innovation and Entrepreneurship Program to Create Affordable Global Health Care Solutions. *Surgical Innovation*. https://doi.org/10.1177/1553350618813437

- PDF bibliographic note: Published online-first article; issue and final publication year not established from this PDF

**Study design:** Historical program-wide before and after comparison.

**Setting:**

- Report — whole study: University of Utah medical-technology innovation and entrepreneurship program.

**Participants:**

- Report — whole study: Interdisciplinary student teams in the Bench to Bedside program; annual enrolled and competing team counts varied.

**Support:**

- Report — whole study: The program provided student teams resources, mentoring and a global-health-specific prize and funding.

**JBI appraisal**

**Full checklist:** QE.


**Outcome: Yearly proportion of competing teams assessed as having global-health technologies:** 5:Y; 6:U; 7:U.

**Outcome: Yearly proportion of competing teams assessed as having global-health technologies; result: Mean annual proportion 2011–2013 versus 2014–2018: 11.4% vs 24.8% (p=.003):** 8:U; 9:U.

**Study:** 1:Y; 2:N; 3:U; 4:N.

### 215. Hazell, Eleanor; Goldman, Ian; Rabie, Babette; Norins, Jen; Chirau, Takunda; Gupta, Taruna (2024). Using co-creation to address monitoring and evaluation challenges: The experience of South Africa’s evaluation hackathon. *Evaluation*. https://doi.org/10.1177/13563890231223174

**Study design:** Participatory action research and retrospective organiser-led case narrative.

**Setting:**

- Report: Nine teams worked in an evaluation hackathon from 8 to 22 October 2021.
- Case — Evaluation evidence-map hackathon team: A team worked on an evidence map during a hackathon.

**Participants:**

- Report: The hackathon had 150 participants.
- Case — Evaluation evidence-map hackathon team: An evidence-map team worked with input from experts.

**Support:**

- Case — Evaluation evidence-map hackathon team: Experts shared their experience developing evidence maps.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:U; 4:U; 5:U; 6:U; 7:U; 8:U; 9:U; 10:U.

### 216. Jacqueline Rojo; Ajesh George; Yenna Salamonson; Leanne Hunt; Lucie M. Ramjan (2023). Using Codesign to Develop a Novel Oral Healthcare Educational Intervention for Undergraduate Nursing Students. *International Journal of Environmental Research and Public Health*. https://doi.org/10.3390/ijerph20064919

**Study design:** Qualitative co-design process evaluation.

**Setting:**

- Report — Oral health education co-design: The study used two online workshops to co-design an oral healthcare educational intervention for undergraduate nursing students. Note: The two workshops are distinguished from subsequent classroom delivery; the reported participant-count discrepancy remains unresolved.
- Case — Oral health education co-design workshops: The co-design workshops were conducted online via Zoom.

**Participants:**

- Report: The authors report eight workshop participants, then state that one of two students who did not attend joined only the second workshop; the total across workshops is unclear. Note: The source reports eight attendees but also describes another student as attending only the second workshop; the unique total across workshops is unclear.
- Case — Oral health education co-design workshops: The first workshop had two mixed groups of students and faculty staff.

**Support:**

- Case — Oral health education co-design workshops: A research assistant facilitated one group and the researcher facilitated the other.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 217. Laura Sheard; Claire Marsh; Thomas Mills; Rosemary Peacock; Joseph Langley; Rebecca Partridge; Ian Gwilt; Rebecca Lawton (2019). Using patient experience data to develop a patient experience toolkit to improve hospital care: a mixed-methods study. *Health Services and Delivery Research*. https://doi.org/10.3310/hsdr07360

**Study design:** Participatory action research with qualitative thematic analysis.

**Setting:**

- Report: Six ward-based teams in three hospital trusts participated throughout the study.
- Case — Emergency department A(i): A(i) was an emergency department.

**Participants:**

- Report — Toolkit co-design participants: Ward staff and patient representatives were involved in co-designing the patient experience toolkit. Note: The statement identifies co-design roles and does not represent a total count or the full set of participants in all research stages.
- Case — Emergency department A(i): Nurses led a communication intervention.

**Support:**

- Case — Emergency department A(i): A quality improvement specialist created a leaflet and took it through approval for the team.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:Y; 8:Y; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Longitudinal patient-experience survey in the separate process-evaluation chapter: outside appraisal scope. The selected descriptions concern six ward teams' supported improvement activities. This separate patient survey measures downstream patient experience, with responses combined across wards and a post-hoc chart for three wards; it does not report a team-work, team-member or development-process measure corresponding to those descriptions. The status is limited to appraisal for the currently selected team outcomes and does not judge the quality of the patient survey or its relevance to other questions.

### 218. Juliane Jarke; Ulrike Gerhard (2018). Using Probes for Sharing (Tacit) Knowing in Participatory Design: Facilitating Perspective Making and Perspective Taking. *i-com*. https://doi.org/10.1515/icom-2018-0014

**Study design:** qualitative participatory case study.

**Setting:**

- Report — Co-creation fieldwork in district 1: The paper reports co-creation fieldwork in one district of a German city, although the broader project also worked in another district. Note: Only district 1 is reported here; its examples are not extended to district 2.
- Case — German district 1 neighbourhood guide: The reported co-creation fieldwork took place in district 1 in Germany.

**Participants:**

- Report — Older residents in reported fieldwork: Twelve older adults living in district 1 were recruited for the reported co-creation process; eleven probe bags were returned. Note: Recruitment count and returned materials are distinct and neither is assumed to apply to the other district.
- Case — German district 1 neighbourhood guide: Twelve older adults living in the district were recruited.

**Support:**

- Case — German district 1 neighbourhood guide: Researchers provided participants with a district map as a probe.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:Y; 6:Y; 7:U; 8:Y; 9:U; 10:Y.

### 219. Kitunen, Anna; Carins, Julia; Isbanner, Sebastian; Rundle-Thiele, Sharyn (2025). Using segmentation to co-design a healthy eating program. *Health Marketing Quarterly*. https://doi.org/10.1080/07359683.2025.2478350

**Study design:** Segmented co-design qualitative preference analysis.

**Setting:**

- Report — Healthy eating co-design sessions: Three co-design sessions developed healthy eating programme ideas for Australian Defence Force personnel. Note: The three sessions address different trainee segments; results from individual segments are not combined as a single group response.
- Case — Healthy eating co-design sessions: The sessions developed a healthy eating programme for Australian Defence Force personnel.

**Participants:**

- Report — Trainees in co-design sessions: Seventy-three Australian Defence Force trainees took part in the three co-design sessions. Note: The participant total is for the sessions; it is not a count of groups or individual comments.
- Case — Healthy eating co-design sessions: Seventy-three ADF trainees participated in three co-design sessions.

**Support:**

- Case — Healthy eating co-design sessions: Each team received paper, pens, markers and sticky notes for the design process.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:U; 6:U; 7:U; 8:Y; 9:Y; 10:Y.

### 220. Arbogast, Doug; Butler, Peter; Faulkes, Eve; Eades, Daniel; Deng, Jinyang; Maumbe, Kudzayi; Smaldone, David (2020). Using social design to visualize outcomes of sustainable tourism planning: a multiphase, transdisciplinary approach. *International Journal of Contemporary Hospitality Management*. https://doi.org/10.1108/ijchm-02-2019-0140

**Study design:** Qualitative participatory social-design and workshop account within multiphase mixed-method study.

**Setting:**

- Report: A rural tourism development project supporting the Tucker County Cultural District Authority in West Virginia.
- Case — Tourism asset inventory: The project collected an inventory of tourism assets.

**Participants:**

- Report — Multiphase tourism research participants: The research drew on resident and visitor perspectives and interviews with key informants before later participatory design activities. Note: The research stages and participant roles are distinguished; no total number of unique participants is inferred.
- Case — Tourism asset inventory: A university faculty member and a CDA Americorps volunteer worked on the asset inventory.

**Support:**

- Case — Tourism asset inventory: A university faculty member developed an online form for a volunteer to enter asset data.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:U; 5:Y; 6:U; 7:U; 8:U; 9:U; 10:U.


**Part-specific limitations and assessment status:**

- Study 1 resident and visitor surveys and tourism economic impact analysis: outside appraisal scope. This scope decision concerns only the Study 1 resident and visitor surveys and tourism economic-impact analysis described in this paper. The existing review description extracts the subsequent participatory mapping, landscape-design and graphic-design activities and their reported outputs; it does not identify a Study 1 survey or economic estimate as an outcome of those supported activities. The abstract on physical page 1 and existing review description were checked; this does not classify every result in the paper or assert that those Study 1 data lack value for other questions.

### 221. Thiago Andrade; Renata Araujo; Sean Siqueira (2022). What can move non-IS developers towards open and collaborative development initiatives?. *iSys - Brazilian Journal of Information Systems*. https://doi.org/10.5753/isys.2022.2152

**Study design:** Qualitative interpretive interview study.

**Setting:**

- Case — UNIGRANRIO hackathons: Not reproduced because of quotation or overlap with source text.

**Participants:**

- Case — Hackathon participant L: The cited account came from a participant in the UNIGRANRIO hackathons.

**Support:**

- Case — Hackathon mentoring: A mentor gave prototyping tips and suggested the Ionic Creator tool.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:U; 6:U; 7:U; 8:Y; 9:U; 10:U.

### 222. Maricel Krügel; Charmaine van der Merwe; Hanelie Adendorff (2025). What Does it Take to Become a Team? Group Work in a Final Year Food Science Capstone Module. *Journal of Food Science*. https://doi.org/10.1111/1750-3841.70688

**Study design:** Qualitative phenomenological thematic analysis of student reflections.

**Setting:**

- Report — Food science capstone module: The study examined group work within a final-year undergraduate food science module on trial design and new product development. Note: The module provides the study context; group outcomes are not assumed to be identical.
- Case — Food science capstone project: The project was part of a final-year undergraduate Food Science module.

**Participants:**

- Report — Food science student groups: Final-year food science students were assigned to groups for a year-long product development project. Note: This identifies the student population; it does not assert a total count or number of reflection respondents.
- Case — Food science capstone project: Students worked in groups on the new product development project.

**Support:**

- Case — One group in the food science capstone project: A facilitator helped the group identify and address its problems.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:U; 7:U; 8:Y; 9:Y; 10:U.

### 223. Julie Bosak; Mari‐Lynn Drainoni; Cheri Bryer; Daisy Goodman; Lisa Messersmith; Eugene Declercq (2023). ‘It opened my eyes, my ears, and my heart’: Codesigning a substance use disorder treatment programme. *Health Expectations*. https://doi.org/10.1111/hex.13908

**Study design:** Qualitative process evaluation.

**Setting:**

- Report — Residential treatment service co-design: The study evaluated a co-design process to launch a residential substance-use treatment service for pregnant or parenting women and their children. Note: The service being co-designed is distinguished from the location and attendance of individual co-design activities.
- Case — Families Flourish Northeast programme co-design: A nonprofit was established to create a long-term residential substance-use treatment service for pregnant and parenting women.

**Participants:**

- Report: The full implementation sample comprised 13 women with lived experience and 21 substance-use-disorder staff.
- Case — Families Flourish Northeast programme co-design: Across all stages, the study included 34 distinct individuals.

**Support:**

- Case — Families Flourish Northeast programme co-design: The launch event shared interview quotes describing provider and lived-experience perspectives.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 224. A. Dominello; S. Lu; A. De Los Santos; M. Murphy; R. Clay‐Williams; C. Cheek (2026). “ There Was a Light Bulb Moment ”: Using Persona Dyads to Empathise, Explore and Develop Person‐Centred Solutions in Mental Health Service Co‐Design. *Health Expectations*. https://doi.org/10.1111/hex.70797

**Study design:** Qualitative deductive content analysis of two co-design workshops within mixed-method evaluation.

**Setting:**

- Report: Two experience-based co-design workshops addressed emergency department care for people with mental health concerns.
- Case — Mental health co-design workshop 1: Workshop 1 used an Ana/Darius persona pair for co-design of emergency care for people with mental health concerns.

**Participants:**

- Report: Participants across the workshops and individual online sessions included four patients, one carer and nine healthcare professionals.
- Case — Mental health co-design workshop 1: Patient and provider participants joined the workshop discussions.

**Support:**

- Case — Mental health co-design workshop 1: A facilitator introduced the clinical scenario and persona pair.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:U; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.


**Part-specific limitations and assessment status:**

- Descriptive questionnaire responses on persona dyads in the co-design workshops: tool not applicable. The questionnaire reports descriptive participant feedback by workshop, including perceived helpfulness and communication, without an independently measured exposure-outcome association or before-after comparison. The analytical cross-sectional and quasi-experimental checklists are not applicable to these descriptive results. Whether a prevalence-oriented appraisal is appropriate remains to be considered separately; this does not assess the qualitative component or the whole article. Method source: Munn et al. 2014, doi:10.15171/ijhpm.2014.71, body and appendix excerpts accessed through Consensus; the full PDF and later JBI editions were not independently checked. The tool was developed for prevalence estimates in a defined target population. The recorded component is workshop-specific participant feedback; the existing assessment does not identify a target-population prevalence estimate. The cited survey evidence reports 11 of 14 unique workshop participants completing surveys; this response count is not itself an outcome prevalence. This is a design-fit explanation and scoped methodological consideration, not an item-level appraisal.

### 225. Leshell Hatley; Maha Al-Freih; Brenda Bannan (2018). “I’m Just Guiding You”: An Exploration of Software Design Mentorship within a Software Engineering Firm. *Journal of Software Engineering and Applications*. https://doi.org/10.4236/jsea.2018.116019

**Study design:** qualitative interpretivist case study.

**Setting:**

- Report — Software design mentoring case study: The case study examined mentoring during design meetings in a software engineering firm. Note: The setting is one organizational design case; findings are not generalized to all mentoring relationships.
- Case — Code Theory software design meeting: Two developers in a software firm designed a cloud-based software tool.

**Participants:**

- Report — Two design team members: The observed design interaction involved two team members, one novice and one expert. Note: The two roles refer to the observed case; no wider employee sample is inferred.
- Case — Code Theory software design meeting: The designers included an experienced and a novice software engineer.

**Support:**

- Case — Code Theory software design meeting: The expert used questions to prompt further thought from the novice.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:U; 5:U; 6:Y; 7:U; 8:Y; 9:U; 10:U.

### 226. Chew, Kimberly Ann; Ponsford, Jennie Louise; Gould, Kate Rachel (2025). “This is a lifesaver”: co-designing a novel cyberscam psychosocial recovery intervention framework for people with acquired brain injury. *Disability and Rehabilitation*. https://doi.org/10.1080/09638288.2025.2457511

**Study design:** Qualitative co-design interview study.

**Setting:**

- Report — Hybrid co-design meetings: The study developed a cyberscam recovery intervention framework through eight hybrid co-design focus-group meetings; clinicians also attended additional meetings. Note: The eight hybrid group meetings and additional clinician meetings are distinguished; no single physical meeting site is assumed.
- Case — Cyberscam recovery intervention co-design: Eight weekly focus groups were held in a hybrid format.

**Participants:**

- Report: The co-design groups included five people with acquired brain injury, three close others and seven clinicians or service providers.
- Case — Cyberscam recovery intervention co-design: Fifteen participants joined the co-design groups.

**Support:**

- Case — Cyberscam recovery intervention co-design: Facilitators led stakeholder-specific breakout groups.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.

### 227. Ishbel Orla Whitehead; Mark Adley; Alexandra Thompson; Elizabeth Westhead; Marina Politis; Philip Mordue; Amy O'Donnell; Barbara Hanratty (2026). “We Don't Normally Go Down This Avenue; This Is Normally Taboo”: Using Co‐Design to Develop a Training Intervention for Spiritual Health in Primary Care. *Health Expectations*. https://doi.org/10.1111/hex.70737

**Study design:** Qualitative deductive thematic evaluation of co-design workshops.

**Setting:**

- Report — Primary-care training co-design workshops: The study evaluated five co-design workshops developing training on spiritual health for primary care. Note: The five workshops are the setting of this process evaluation; views from participants and survey responses are not equated with unique attendance counts.
- Case — SHARP spiritual-health training workshops: Five co-design workshops addressed spiritual health training in primary care.

**Participants:**

- Report: The five workshops recorded 38 attendances from 27 unique participants.
- Case — SHARP spiritual-health training workshops: Twenty-seven distinct people attended across the five workshops.

**Support:**

- Case — SHARP spiritual-health training workshops: Two participants were offered one-to-one meetings with a researcher to provide space for their contributions.

**JBI appraisal**

**Full checklist:** Q.


**Study:** 1:Y; 2:Y; 3:Y; 4:Y; 5:Y; 6:Y; 7:Y; 8:Y; 9:Y; 10:Y.
