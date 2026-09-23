# FMGE Study Blueprint

> **Status:** Official subject blueprint integrated  
> **Last verified:** 23 September 2026

## Purpose

This page separates the **official FMGE examination blueprint** published by the National Board of Examinations in Medical Sciences (NBEMS) from the additional topic-level study guidance developed by this project.

The official blueprint tells us the marks allocated to each subject.

It does **not** tell us which individual topics or questions will appear in a future examination.

---

## 1. Official FMGE Blueprint

The FMGE blueprint published by NBEMS allocates **300 marks** across pre/para-clinical and clinical subjects.

### Pre/Para-clinical subjects — 100 marks

| Subject | Marks |
|---|---:|
| Anatomy | 17 |
| Physiology | 17 |
| Biochemistry | 17 |
| Pathology | 13 |
| Microbiology | 13 |
| Pharmacology | 13 |
| Forensic Medicine | 10 |
| **Total** | **100** |

### Clinical subjects — 200 marks

| Subject | Marks |
|---|---:|
| Medicine | 33 |
| Psychiatry | 5 |
| Dermatology & STD | 5 |
| Radiotherapy | 5 |
| General Surgery | 32 |
| Anaesthesiology | 5 |
| Orthopedics | 5 |
| Radiodiagnosis | 5 |
| Pediatrics | 15 |
| Ophthalmology | 15 |
| ENT | 15 |
| Obstetrics & Gynaecology | 30 |
| Community Medicine | 30 |
| **Total** | **200** |

**Grand total: 300 marks**

Source: NBEMS FMGE Information Bulletin. See [`data/fmge-blueprint.csv`](../../data/fmge-blueprint.csv).

---

## 2. What the Official Blueprint Means

The official subject distribution is the highest-confidence information available for planning study time.

For example:

- Medicine — 33 marks
- General Surgery — 32 marks
- Obstetrics & Gynaecology — 30 marks
- Community Medicine — 30 marks
- Anatomy — 17 marks
- Physiology — 17 marks
- Biochemistry — 17 marks

These allocations can be used to establish the broad structure of a preparation plan.

However, the official blueprint does **not** provide a guaranteed topic-by-topic distribution.

---

## 3. What This Project Will Add

The FMGE Open Guide will progressively build a second layer of evidence below the official blueprint.

### Layer 1 — Official examination structure

Source:

- NBEMS information bulletins
- NBEMS official notices
- Other authoritative examination documents

Confidence:

**Highest**

---

### Layer 2 — Topic taxonomy

The project maintains a structured list of subjects, topics and subtopics.

See:

[`data/fmge-topics.csv`](../../data/fmge-topics.csv)

This taxonomy is intended to make the study guide searchable and structured.

It is **not** presented as an official NBEMS topic list.

---

### Layer 3 — Question-level evidence

Future versions of this project may collect structured information from:

- Previous-year questions
- Legally available question banks
- User-contributed recall data
- Publicly documented examination discussions
- Repeated concepts reported across multiple sources

Each source should be labelled according to its evidence level.

---

### Layer 4 — Study recommendations

Only after sufficient evidence is collected should the project make recommendations such as:

- high-frequency topics
- commonly tested concepts
- revision priorities
- subject-specific study strategies
- question-solving priorities

These are **study recommendations**, not official examination specifications.

---

## 4. Evidence Classification

The study guide distinguishes between the source of a claim and the strength of the evidence supporting it.

Repeated reports are not automatically independent evidence. If multiple websites or posts appear to reproduce the same underlying recall or source, they should not be counted as separate independent observations.

### Evidence levels

| Level | Evidence type | Description |
|---|---|---|
| **E1 — Official** | NBEMS/NMC documentation | Directly stated in an official examination document, notice, regulation, or bulletin |
| **E2 — Primary examination evidence** | Documented question/paper | Question or examination material that can be directly verified from a reliable primary source |
| **E3 — Independent repeated observation** | Multiple independent reports | The same concept is reported independently by multiple credible sources |
| **E4 — Single candidate/community report** | Recall or discussion | A candidate-reported question or observation that cannot yet be independently verified |
| **E5 — Interpretation** | Analytical conclusion | A conclusion derived from available evidence |
| **E6 — Recommendation** | Study advice | A practical recommendation made by this project |

---

### Independence of sources

Source count should not be treated as the same thing as evidence count.

For example:

> Candidate A reports a question → Website B copies Candidate A → Telegram channel C copies Website B.

This represents **one underlying observation**, not three independent observations.

Where the original source cannot be established, the project should record the information conservatively.

---

### Confidence

Topic-level confidence should be assigned separately from raw frequency.

Suggested values:

- **High**
- **Moderate**
- **Low**
- **Unverified**

Confidence should consider:

1. Source reliability
2. Whether the underlying evidence is directly verifiable
3. Number of genuinely independent observations
4. Consistency between sources
5. Recency
6. Whether the observation can be mapped unambiguously to a topic

---

### Frequency

`frequency` in `data/fmge-question-evidence.csv` refers to the number of **documented observations represented by that record**, not the number of websites or social-media posts mentioning it.

Frequency should never be interpreted as a prediction of future examination questions.

---

### Recommended evidence record

Each documented observation should ideally contain:

- Source identifier
- Source type
- Examination session
- Subject
- Topic
- Subtopic
- Question reference, where available
- Evidence type
- Frequency
- Confidence
- Notes
- Verification date

The structured schema is maintained in:

[`data/fmge-question-evidence.csv`](../../data/fmge-question-evidence.csv)

---

### What should not be treated as evidence

The following should not automatically be converted into high-yield claims:

- Coaching-institute predictions
- "Most important" lists without methodology
- Unverified Telegram lists
- Anonymous social-media posts
- A single recalled question
- Repeated copies of the same recall
- Personal impressions about what is "frequently asked"

These may still be useful as leads for further investigation, but they should be labelled accordingly.

---

## 5. Topic-Level Blueprint

The topic-level blueprint is currently under development.

See:

[`data/fmge-topics.csv`](../../data/fmge-topics.csv)

At present, the topic taxonomy provides the structural framework but does not assign unsupported probabilities or mark distributions to individual topics.

### Future topic-level fields

As evidence is collected, topics may eventually receive fields such as:

- frequency
- number of observed questions
- source count
- evidence strength
- last observed year
- confidence
- recommended priority

These should only be populated when there is sufficient supporting evidence.

---

## 6. Study Priority

The project should avoid arbitrary labels such as "must study" or "ignore" unless they are supported by evidence.

A useful future priority system could combine:

1. Official subject weight
2. Historical question frequency
3. Recency of appearance
4. Repetition across independent sources
5. Clinical importance
6. Candidate difficulty
7. Time required to master the topic

This would allow study priorities to be transparent rather than based solely on personal opinion.

---

## 7. Question-Based Learning

The study guide is intended to be question-oriented.

For each topic, the eventual guide should aim to connect:

**Topic → Questions → Concept → Explanation → Revision**

A well-structured topic entry might eventually contain:

- Core concept
- Common question formats
- Important differentials
- Classic associations
- Image-based clues
- Common traps
- Previous-question evidence
- Related topics
- Revision prompts

---

## 8. Revision Framework

The eventual study guide may support a layered revision system.

### First pass

Understand the core concept.

### Second pass

Solve questions and identify weaknesses.

### Third pass

Review errors and high-frequency concepts.

### Final revision

Rapid review of:

- formulas
- classifications
- criteria
- drug associations
- image recognition
- clinical algorithms
- frequently confused concepts

The exact revision schedule should remain adaptable to the candidate's available preparation time.

---

## 9. Mock Examination Strategy

Mock examinations should eventually be treated as a separate dataset.

Useful fields may include:

- mock source
- date
- subject
- topic
- question type
- candidate performance
- error category
- confidence before answering
- explanation quality

This could eventually allow candidates to identify **knowledge gaps versus exam-technique errors**.

---

## 10. Important Limitation

No blueprint can reliably predict the exact questions that will appear in a future FMGE examination.

The purpose of this project is therefore not to create a "sure-shot questions" list.

The objective is to build a transparent evidence base that helps candidates decide:

> **What should I study, why should I study it, and how strong is the evidence behind that recommendation?**

---

## 11. Data Sources

The official subject distribution is maintained separately in:

[`data/fmge-blueprint.csv`](../../data/fmge-blueprint.csv)

The broader study taxonomy is maintained in:

[`data/fmge-subjects.csv`](../../data/fmge-subjects.csv)

Topic taxonomy:

[`data/fmge-topics.csv`](../../data/fmge-topics.csv)

General project source methodology:

[`SOURCES.md`](../../SOURCES.md)

---

## 12. Development Roadmap

The study blueprint will be developed progressively.

### Completed

- [x] Official subject blueprint
- [x] Subject taxonomy
- [x] Topic taxonomy
- [x] Evidence classification framework

### Next

- [ ] Align subject taxonomy with the official blueprint
- [ ] Add historical question data
- [ ] Build topic-frequency dataset
- [ ] Identify repeated concepts
- [ ] Develop evidence-based topic priorities
- [ ] Build subject-specific study guides
- [ ] Develop revision tables
- [ ] Add image-based learning resources
- [ ] Develop mock-analysis framework

---

## Guiding principle

> **Official information should be presented as official.  
> Observations should be presented as observations.  
> Recommendations should be presented as recommendations.**

The FMGE Open Guide should never blur these categories.
