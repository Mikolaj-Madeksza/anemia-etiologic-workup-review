# Search strategies

Searches were run on 7 November 2026. Exact database queries are preserved below. Database contents change, so rerunning these queries may return different counts.

No language/date/age/geography filters. Explicit exclusions for ineligible indexed publication types; PubMed also excludes Animals[mh] NOT Humans[mh]. Available subscribed database coverage.

## PubMed/MEDLINE

Platform: NLM PubMed E-utilities. Records exported: 5,917.

```text
(("Anemia"[Mesh] OR anemi*[tiab] OR anaemi*[tiab]) AND ("Hospitals"[Mesh] OR "Inpatients"[Mesh] OR "Hospitalization"[Mesh] OR hospital*[tiab] OR inpatient*[tiab] OR in-patient*[tiab] OR ward*[tiab] OR laborator*[tiab]) AND ((workup*[tiab] OR "work up"[tiab] OR "work-up"[tiab]) OR ((investigat*[tiab] OR evaluat*[tiab] OR diagnos*[tiab] OR etiolog*[tiab] OR aetiolog*[tiab] OR test*[tiab] OR ferritin[tiab] OR transferrin[tiab] OR "iron studies"[tiab] OR "iron status"[tiab] OR "vitamin B12"[tiab] OR folate[tiab] OR reticulocyt*[tiab] OR endoscop*[tiab] OR gastroscop*[tiab] OR haematinic*[tiab] OR hematinic*[tiab]) AND (audit*[tiab] OR underus*[tiab] OR overus*[tiab] OR misus*[tiab] OR utiliz*[tiab] OR utilis*[tiab] OR appropriat*[tiab] OR adheren*[tiab] OR uninvestigat*[tiab] OR undertest*[tiab] OR underdiagnos*[tiab] OR "clinical practice"[tiab] OR "routine care"[tiab] OR "routine clinical"[tiab] OR "diagnostic inertia"[tiab] OR "quality improvement"[tiab] OR "diagnostic pathway"[tiab] OR "testing practice"[tiab] OR "practice patterns"[tiab] OR "hospital practice"[tiab] OR infrequent*[tiab] OR underinvestigat*[tiab] OR "under-investigated"[tiab] OR "incomplete investigation"[tiab] OR "incomplete evaluation"[tiab] OR "inadequate investigation"[tiab])) OR ((anemi*[ti] OR anaemi*[ti]) AND (investigat*[ti] OR evaluat*[ti] OR diagnos*[ti] OR etiolog*[ti] OR aetiolog*[ti])))) NOT (Review[pt] OR Systematic Review[pt] OR Meta-Analysis[pt] OR Guideline[pt] OR Practice Guideline[pt] OR Editorial[pt] OR Comment[pt] OR Case Reports[pt] OR (Animals[mh] NOT Humans[mh]))
```

## Scopus

Platform: Elsevier Scopus. Records exported: 11,864.

```text
(TITLE-ABS-KEY(anemi* OR anaemi*) AND TITLE-ABS-KEY(hospital* OR inpatient* OR "in-patient*" OR ward* OR laborator*) AND (TITLE-ABS-KEY(workup* OR "work up" OR "work-up") OR (TITLE-ABS-KEY(investigat* OR evaluat* OR diagnos* OR etiolog* OR aetiolog* OR test* OR ferritin OR transferrin OR "iron studies" OR "iron status" OR "vitamin B12" OR folate OR reticulocyt* OR endoscop* OR gastroscop* OR haematinic* OR hematinic*) AND TITLE-ABS-KEY(audit* OR underus* OR overus* OR misus* OR utiliz* OR utilis* OR appropriat* OR adheren* OR uninvestigat* OR undertest* OR underdiagnos* OR "clinical practice" OR "routine care" OR "routine clinical" OR "diagnostic inertia" OR "quality improvement" OR "diagnostic pathway" OR "testing practice" OR "practice patterns" OR "hospital practice" OR infrequent* OR underinvestigat* OR "under-investigated" OR "incomplete investigation" OR "incomplete evaluation" OR "inadequate investigation")) OR (TITLE(anemi* OR anaemi*) AND TITLE(investigat* OR evaluat* OR diagnos* OR etiolog* OR aetiolog*)))) AND NOT (DOCTYPE(re) OR DOCTYPE(ed) OR DOCTYPE(ab) OR DOCTYPE(cr))
```

## Web of Science Core Collection

Platform: Clarivate; Editions All. Records exported: 7,176.

```text
(TS=(anemi* OR anaemi*) AND TS=(hospital* OR inpatient* OR "in-patient*" OR ward* OR laborator*) AND (TS=(workup* OR "work up" OR "work-up") OR (TS=(investigat* OR evaluat* OR diagnos* OR etiolog* OR aetiolog* OR test* OR ferritin OR transferrin OR "iron studies" OR "iron status" OR "vitamin B12" OR folate OR reticulocyt* OR endoscop* OR gastroscop* OR haematinic* OR hematinic*) AND TS=(audit* OR underus* OR overus* OR misus* OR utiliz* OR utilis* OR appropriat* OR adheren* OR uninvestigat* OR undertest* OR underdiagnos* OR "clinical practice" OR "routine care" OR "routine clinical" OR "diagnostic inertia" OR "quality improvement" OR "diagnostic pathway" OR "testing practice" OR "practice patterns" OR "hospital practice" OR infrequent* OR underinvestigat* OR "under-investigated" OR "incomplete investigation" OR "incomplete evaluation" OR "inadequate investigation")) OR (TI=(anemi* OR anaemi*) AND TI=(investigat* OR evaluat* OR diagnos* OR etiolog* OR aetiolog*)))) NOT DT=(Review OR "Editorial Material" OR "Meeting Abstract")
```

## Export and validation notes

The Scopus export comprised 11,863 original records plus one verified missing result. Search validation retrieved all located seed reports: 12/12 in PubMed, 11/11 in Scopus and 10/10 in Web of Science. These checks do not establish complete retrieval of all eligible studies.

## Database exports

The exports are gzip-compressed; decompress them before importing the RIS or NBIB files into a reference manager. Their contents are unchanged by compression.

These files preserve the search results before deduplication. They complement the search strategies because database contents and indexing can change.

| Database | File | Records |
| --- | --- | ---: |
| PubMed | [NBIB export](2026-11-07_pubmed.nbib.gz) | 5,917 |
| Scopus | [RIS export](2026-11-07_scopus.ris.gz) | 11,864 |
| Web of Science | [RIS export](2026-11-07_wos.ris.gz) | 7,176 |

The PubMed and Web of Science files are the original exports. The Scopus file is the final reconciled export, including the recovered record and documented identifier corrections. These files contain bibliographic metadata and available abstracts, not full-text articles. Third-party content is not covered by the repository's MIT license; database and publisher terms still apply.

## Supplementary searching

The available search log records partial backward citation checks; forward citation searching and remaining reference checks were still pending. The additional Norfolk geriatric audit was already present in the project, and its original discovery route is unknown.
