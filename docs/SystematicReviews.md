# Systematic Reviews 
<standard name="Systematic Reviews">
<em>A study that appraises, analyses, and synthesizes primary or secondary literature to provide a complete, exhaustive summary of current evidence regarding one or more specific topics or research questions</em>

## Application 

-   Applies to studies that systematically find and analyze existing literature about a specified topic
-   Applies both to secondary and tertiary studies
-   Does not apply to ad-hoc literature reviews, case surveys or advanced qualitative synthesis methods (e.g. meta-ethnography)

## Specific Attributes 

### Essential Attributes 
<checklist name="Essential">

<intro>

- [ ]   clearly establishes the need to conduct a systematic review (e.g. lack of a similar review on the subject, need to provide stronger evidence regarding a research question)
- [ ]	identifies type of review (e.g. scoping review, meta-analysis, systematic mapping study, narrative synthesis, case survey, critical review)

<method>

- [ ]   defines the research goal and the associated research questions
- [ ]   characterizes the research question, preferably using PICO attributes (population, intervention, control, outcomes)
- [ ]	defines clear inclusion and exclusion criteria for the selection of sources of studies
- [ ]   defines a generic search expression considering each attribute of PICO and their synonyms
- [ ]   evaluates the efficacy of the search expression with respect to a quasi-golden standard or to a set of pre-selected papers (i.e. the search expression matches the quasi-golden standard or the set of pre-selected papers?)
- [ ]   evaluates the efficiency of the search expression with respect to a quasi-golden standard or to a set of pre-selected papers (i.e. the search expression matches not many papers that does not belong to the quasi-golden standard or to the set of pre-selected papers?)
- [ ]	presents step-by-step, systematic, replicable description of search process including search terms<sup>[1](#myfootnote1)</sup>  
- [ ]	defines clear inclusion and exclusion criteria for the selection of studies
- [ ]	specifies the data extracted from each primary study<sup>[2](#myfootnote2)</sup>  ; explains relationships to research questions
- [ ]	describes in detail how data were extracted
- [ ]   specifies the synthesis method used for the systematic review
- [ ]	describes in detail how data were synthesized (can be qualitative or quantitative)
- [ ]	if using qualitative methods for synthesis, describes coding scheme(s) and their use

<results>

- [ ]	clear chain of evidence from the extracted data to the answers to the research question(s)

<discussion>

- [ ]	presents conclusions or recommendations for practitioners/non-specialists

<other>		

</checklist>

### Desirable Attributes 
<checklist name="Desirable">
	
- [ ]	provides supplementary materials such as protocol, search terms, search results, selection process results; complete dataset, analysis scripts; coding scheme, examples of coding, decision rules, descriptions of edge cases
- [ ]	mitigates sampling bias and publication bias, using some (not all) of:  
(i) manual and keyword automated searches;   
(ii) backward and forward snowballing searches;  
(iii) checking profiles of prolific authors in the area;   
(iv) searching both formal databases (e.g. ACM Digital Library) and indexes (e.g. Google Scholar);   
(v) searching for relevant dissertations;   
(vi) searching pre-print servers (e.g. arXiv);   
(iiv) soliciting unpublished manuscripts through appropriate listservs or social media;  
(iiiv) contacting known authors in the area. 
- [ ]	demonstrates that the search process is sufficiently rigorous for the systematic review goals<sup>[3](#myfootnote3)</sup>  
- [ ]	assesses quality of primary studies using an a priori coding scheme (e.g. the *Systematic Reviews Standard*); explains how quality was assessed; excludes low quality studies (ok) or models study quality as a moderating variable (better) 
- [ ]	assesses coverage using funnel plots or percentage of known papers found
- [ ]	(positivist reviews), uses 2+ independent analysts; analyzes inter-rater reliability (see the [IRR/IRA Supplement](https://github.com/acmsigsoft/EmpiricalStandards/blob/master/Supplements/InterRaterReliabilityAndAgreement.md)); explains how discrepancies among coders were resolved<sup>[4](#myfootnote4)</sup> 
- [ ]	(interpretivist reviews) reflects on how researcher’s biases may have affected their analysis
- [ ]	consolidates results using tables, diagrams, or charts; PRISMA flow diagram (cf. Moher et al. 2009)
- [ ]	performs analysis through an existing or new conceptual framework (qualitative synthesis)
- [ ]	uses meta-analysis methods appropriate for primary studies; does not use vote counting 
- [ ]	integrates results into prior theory or research; identifies gaps, biases, or future directions
- [ ]	presents results as practical, evidence-based guidelines for practitioners, researchers, or educators
- [ ]	clearly distinguishes evidence-based results from interpretations and speculation<sup>[5](#myfootnote5)</sup>	
</checklist>
     
### Extraordinary Attributes
<checklist name="Extraordinary">

- [ ]	two or more researchers independently undertaking the preliminary search process before finalizing the search scope and search keywords
- [ ]	contacted primary study authors to ensure interpretations are correct, and elicit additional details not found in the papers such as access to raw data
</checklist>

## Examples of Acceptable Deviations 

-   No attempts to mitigate publication bias in a study explicitly examining a specific venue's (e.g. CACM or ICSE) coverage of a given topic.
-   Using probability sampling on primary studies when there are too many to analyze (i.e. thousands).
-   No recommendations for practitioners in a study of a methodological issue (e.g. representative sampling).

## Antipatterns 

-   A laundry-list description of the studies (A found X, B found Y, ...), rather than a synthesis of the findings.
-   Relying on characteristics of the publication venues as a proxy for the quality of the primary studies instead of assessing primary studies' quality explicitly.
-   Reviewing an area in which there are too few high-quality primary studies to draw reliable conclusions.

## Suggested Readings 

Moher D, Liberati A, Tetzlaff J, Altman DG, The PRISMA Group (2009).
*P*referred *R*eporting *I*tems for *S*ystematic Reviews and
*M*eta-*A*nalyses: The PRISMA Statement. PLoS Med 6, 7: e1000097.
doi:10.1371/journal.pmed1000097

Michael Borenstein and Larry V. Hedges and Julian P.T. Higgins and
Hannah R. Rothstein. 2009. *Introduction to Meta-Analysis.* John Wiley &
Sons Ltd.

Daniela S. Cruzes and Tore Dybå. 2010. Synthesizing evidence in software
engineering research. In Proceedings of the 2010 ACM-IEEE International
Symposium on Empirical Software Engineering and Measurement (ESEM '10).
Association for Computing Machinery, New York, NY, USA, Article 1,
1–10. DOI:10.1145/1852786.1852788

Barbara Kitchenham and Stuart Charters. 2007. Guidelines for performing
Systematic Literature Reviews in Software Engineering.

Matthew B. Miles and A. Michael Huberman and Jonny Saldana. 2014.
Qualitative Data Analysis: A Methods Sourcebook. Sage Publications Inc.

Kai Petersen, Robert Feldt, Shahid Mujtaba, and Michael Mattsson. 2008.
Systematic mapping studies in software engineering. In *12th
International Conference on Evaluation and Assessment in Software
Engineering (EASE).* (Jun. 2008), 1–10.

---
<footnote><sup>[1](#myfootnote1)</sup> Searches can be manual or automated or a combination of both.</footnote><br>
<footnote><sup>[2](#myfootnote2)</sup> Primary studies are the studies that are being reviewed. In a tertiary study, the “primary studies” are themselves reviews.</footnote><br>
<footnote><sup>[3](#myfootnote3)</sup> e.g. formal meta-analysis of experiments has higher requirements for completeness than mapping studies of broad topic areas.</footnote><br>
<footnote><sup>[4](#myfootnote4)</sup>By discussion and agreement, voting, adding tie-breaker, consulting with study authors, etc.</footnote><br>
<footnote><sup>[5](#myfootnote5)</sup> Simply separating results and discussion into different sections is typically sufficient. No speculation in the results section.</footnote><br>
</standard>
