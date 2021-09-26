---
title: "Introduction to Scientific Reproducibility"
teaching: 0
exercises: 0
questions:
- "How is 'reproducibility' defined?"
- "Why is scientific reproducibility important?"
objectives:
- "Differentiate among various definitions of 'reproducibility' and other related concepts."
- "Recall historical and contemporary imperatives for scientific reproducibility."
keypoints:
- "The term 'reproducibility' has been used in different ways in different disciplinary contexts."
- "Computational reproducibility, which is the focus of this and follow-up lessons, refers to the duplication of reported findings by re-executing the analysis with the same data and code used by the original researcher to generate their findings."
- "Scientific reproducibility is not a novel concept, but one that has been reiterated by prominent scholars throughout history as a cornerstone of scientific practice."
- "Failed attempts to reproduce published scientific resarch are considered by some to be reflective of an ongoing crisis in scientific integrity, which may affect public trust in science."
---
## Defining "Reproducibility"
The term, *reproducibility*, can carry very different meanings depending on the context in which it is used.  Thus, it is important for us to begin by disambiguating among these various terms and their meanings.  To do this, we define three specific types of reproducibility that articulate the primary distinctions among the various conceptions of reproducibility defined by Victoria Stodden (2015): *empirical reproducibility*, *statistical reproducibility*, and *computational reproducibility*.

### Empirical Reproducibility
Empirical reproducibility assumes the presence of comprehensive documentation of research methods and protocols for a research study that allow subsequent studies that apply the same research methods and protocols to yield results that corroborate those reported by the original investigators.

### Statistical Reproducibility
Statistical reproducibility relies on the application of appropriate statistical methods to yield defensible results.  Studies that suffer from statistical irreproducibility have weaknesses in the statistical methods and analysis, which precludes the possibility of repeating the study and yielding the same results.

### Computational Reproducibility
Computational reproducibility considers scientific practice that relies on computational methods to produce results.  That ability to use the original same data and code to produce identical results as those of the original study describes computational reproducibility. 

Read Stodden’s article that defines the various types of reproducibility:<br/>
**Stodden, V. (2015). Reproducing statistical results. *Annual Review of Statistics and Its Application*, *2*(1), 1–19. [https://doi.org/10.1146/annurev-statistics-010814-020127](https://doi.org/10.1146/annurev-statistics-010814-020127)**

### The Definitive Definition of "Reproducibility"
In discussions of reproducibility, you also may have seen the terms *replicability*, *verifiability*, *repeatability*, and *transparency* used to describe any one of the three definitions provided above.  These terms have been used interchangeably and with conflating definitions, ultimately obfuscating their intended meanings.  However, it does seem that the scientific community is converging on clearer definitions that capture the nuances of these related terms.

A recent report published by the National Academies of Sciences, Engineering and Medicine (2019) makes a clear distinction between reproducibility and replicability as a means to resolve ambiguities in the use of these and related terms.  Their definitions are below as presented in the report:

> *Reproducibility* is obtaining consistent results using the same input data; computational steps, methods, and code; and conditions of analysis.  This definition is synonymous with “computational reproducibility”...
>
> *Replicability* is obtaining consistent results across studies aimed at answering the same scientific question, each of which has obtained its own data (p. 46).

Read the full report here:<br/>
**National Academies of Sciences, Engineering, and Medicine. (2019). *Reproducibility and replicability in science*. National Academies Press. [https://doi.org/10.17226/25303](https://doi.org/10.17226/25303)**

> ## Reproducibility vs. Reproducibility
> Read the descriptions of real-life instances in which published research findings were discovered to be non-reproducible. Based on the definitions of reproducibility types, determine which—**empirical**, **statistical**, or **computational**—applies to the scenario in each description.
>
> **Scenario 1: Wansink - Slicing and Dicing Food Data**<br/>
> If you believe that shopping hungry compels you to make poor food purchasing decisions or that the size of your plate can influence how much you eat, you have Brian Wansink and the Cornell Food and Brand Lab to thank.  Over the past three decades, Wansink has had over 250 articles published describing results of studies of food-related behavior, many of which have entered the popular imagination through mainstream media outlets that published many digestible news articles about Wansink’s studies.  Some of these studies informed Wansink’s work as an executive director of the USDA’s Center for Nutrition Policy and Promotion, which issues dietary guidance for the National School Lunch Program, Supplemental Nutrition Assistance Program (SNAP), and other federally sponsored nutrition programs.
>
> A closer look at his research by other scientists and statisticians, however, revealed considerable problems that would prevent them from repeating Wansink’s analyses.  What they discovered was rampant p-hacking, a dubious practice in which statistical tests are run repeatedly on a dataset in an attempt to yield statistically significant results, irrespective of the research question or hypothesis—if any—at hand.  Beyond p-hacking, scientists also found calculation errors including unfeasible means and standard deviations.  This was perhaps no accident, as evidenced by an email from Wansink to a lab member that instructed her to dig through a dataset to find significant relationships among variables.  Wrote Wansink, “I don’t think I’ve ever done an interesting study where the data ‘came out’ the first time I looked at it.”  A few years later after these discoveries, several of Wansink’s publications were retracted and an academic misconduct investigation prompted his removal from teaching and research duties at Cornell University.
>
> **Scenario 2:  Reinhart & Rogoff – Excel Fail**<br/>
> Thomas Herndon, a graduate student at the University of Massachusetts Amherst was assigned a class project to select an article from an economics journal and attempt to reproduce its findings.  After several attempts, Herndon was unsuccessful, assuming that he had made some mistake in his own analysis. Even after obtaining the underlying analysis data from the authors themselves, Herndon was still unable to reproduce the results from the well-respected authors.  Upon closer inspection of the spreadsheet of data he was given, however, he found a critical discovery that would shock the entire field of economics.
>
> That discovery was a basic Excel miscalculation, one that tested the veracity of the findings from the influential Reinhart and Rogoff article, “Growth in a Time of Debt,” cited over 4,000 times and used by governments to justify specific austerity measures to address economic crises.  While corrections to the analysis yielded different results (which Herndon later published) from those in the original article, the authors insisted that these differences did not change their central findings.  However, the authors did acknowledge their error in a public statement: “It is sobering that such an error slipped into one of our papers despite our best efforts to be consistently careful.  We will redouble our efforts to avoid such errors in the future.”
>
> **Scenario 3:  Cuddy – The Powerless Power Pose**<br/>
> With over 60,000 views, Amy Cuddy’s TED Talk, “Your body language may shape who you are,” convinced many people that “power posing” induces an actual sense of increased power.  Cuddy, a social psychologist, along with co-authors Dana Carney and Andy Yap published results of a study that investigated the physiological and behavioral effects of posing in open, expansive postures: wide stance, hands on hips.  The authors found that embodiments of power (i.e., power posing) cause a decrease of cortisol (the stress hormone) while increasing testosterone and risk tolerance.  They concluded that power posing manifests actual feelings of power.
>
> After other scientists repeated the study and failed to yield comparable results to demonstrate the robustness of the original power pose findings, some in the scientific community cast doubt on the soundness of the original study design and protocols. One of the most vocal skeptics was co-author Carney, who later announced that “I do not believe that ‘power pose’ effects are real.”  Aside from the small sample size and a questionable participant selection process, Carney explained that the experiment involved male and female participants (not distinguished by gender) who performed risk-taking tasks and subsequently were informed that they had won small cash prizes. Because the act of winning increases testosterone levels, there was no way to determine whether the increase in testosterone was an effect of the power pose as the paper concluded, or if it was merely an effect of winning.  Despite this controversy, studies on power posing continue, with some attesting to and some challenging the power of power posing.
>
>> ## Solution
>> **Scenario 1:  Statistical Reproducibility (Wansink)**<br/>
>> In this scenario, research results were generated using an inappropriate, dubious statistical technique. Statistical analyses were also rife with errors and miscalculations, which would make it impossible for anyone to arrive at the same results.  This example demonstrates lack of *statistical reproducibility*.
>>
>> **Scenario 2:  Computational Reproducibility (Reinhart & Rogoff)**<br/>
>> In this scenario, Herndon attempted to reproduce the findings in a journal article by using the authors’ own data used to generate the results reported in the article. Unfortunately, Herndon was unable to do so, which demonstrates a failure to *computationally reproduce* the published results.
>>
>> **Scenario 3:  Empirical Reproducibility (Cuddy)**<br/>
>> In this scenario, researchers repeated the steps of the original power pose experiment but arrived at different results.  Problems with the study design and protocols rendered the original power pose study *empirically irreproducible*.
>>
> {: .solution}
>
{: .challenge}

> ## What about Qualitiative Research?
> Qualitative research methodologies do not rely on analyses of quantitatively measurable variables, which is why some scholars have argued that reproducibility standards do not or cannot apply to qualitative research. There is no doubt, however, that findings from qualitative studies must be subject to the same level of scrutiny as those produced by their quantitative counterparts. Certainly, the credibility of qualitative research is just as important as the credibility of quantitative research.  Assessing the reproducibility of qualitative research is conceivable, albeit with a focus on transparency.
>
> Considering the more constructivist nature of qualitative research (in contrast to positivist quantitative research), assessments of research integrity emphasize production transparency and analytic transparency.  Production transparency requires that the processes for research participant selection, data collection, and analytic interpretation—and the decisions that informed these processes—be documented in explicit detail.  Analytic transparency demands clear descriptions and explanations of the methods and logic used to draw conclusions from the data.  For qualitative research, a high degree of production and analytic transparency is prerequisite for demonstrating research rigor and credibility.
>
> Read more about reproducibility and transparency in qualitative research here:<br/>
> **Elman, C., Kapiszewski, D., & Lupia, A. (2018). Transparent social inquiry: Implications for social science. *Annual Review of Political Science*, *21*, 29–47. [https://doi.org/10.1146/annurev-polisci-091515-025429](https://doi.org/10.1146/annurev-polisci-091515-025429)**
>
> **TalkadSukumar, P., & Metoyer, R. (2019). *Replication and transparency of qualitative research from a constructivist perspective* [Preprint]. Open Science Framework. [https://doi.org/10.31219/osf.io/6efvp](https://doi.org/10.31219/osf.io/6efvp)**
>
{: .callout}

## The Impetus for Scientific Reproducibility
The notion that autism is linked to vaccines first appeared in two articles by Andrew Wakefield, which reported results of a study of a small group of children who had received the MMR vaccine and subsequently diagnosed with autism.  A subsequent examination of the study protocols and data from health records, however, revealed that no interpretation of the data could have reasonably concluded that instances of autism diagnoses were linked to the vaccine. The Wakefield articles eventually were retracted by the Lancet journal that published them, and Wakefield was found guilty of scientific misconduct and fraud.  Our understanding of the relationship between autism and vaccines is more reliably supported by the many studies and meta-analyses of studies on the subject that have consistently shown that vaccines do not cause autism.  

Research findings are considered to be rigorous and valid if subsequent attempts by the scientific community to produce the same findings are successful. For scientific claims to be credible, they must be able to stand up to scrutiny, which is a hallmark of science. The scientific community promotes the credibility of its claims through systems of peer review and research replication.  

With scientific research increasingly becoming computationally intensive, reproducibility has become fundamental for demonstrating the integrity of reported research findings. Confirmation of the reproducibility of research results adds another necessary element of research checks and balances.
The ability of a researcher to obtain and use the data and analysis code from the author of published scientific findings to re-produce those findings is an essential standard by which the scientific community judges the integrity of research data and their associated publications.  

### Mertonian Norms
In their discussions of the reproducibility, many scholars have made reference to Robert Merton’s “Ethos of Science” in which he defines four norms of research, or Mertonian Norms: universalism, communalism, disinterestedness, and organized skepticism.  *Universalism* establishes the use of unbiased criteria for verifying knowledge claims, *communalism* posits that science is a collaborative enterprise that requires scientific outputs to be in the public domain, *disinterestedness* addresses scientific integrity unfettered by self-interest with scientists held to a standard of rigor, and *organized skepticism* calls for the formal institutionalization of testable, objective science.  

Arguments for reproducibility often associate the Mertonian Norms to the principles of reproducibility, particularly when making the case for open data access (communalism and disinterestedness) and independent verification of reproducibility (universalism and organized skepticism), citing the Mertonian Norms as being central to productive and moral scientific practice and culture. 

Read the essay that introduced the Mertonian Norms and learn more here:<br/>
**Merton, R. K. (1973). The normative structure of science. In *The sociology of science: Theoretical and empirical investigations*. University of Chicago Press. [http://www.panarchy.org/merton/science.html](http://www.panarchy.org/merton/science.html)**

**Berkeley Initiative for Transparency in the Social Sciences. (2016, June 2). *What are Merton’s norms?* [https://youtu.be/00btFojQPiU](https://youtu.be/00btFojQPiU)**

### The Reproducibility "Crisis"
In a 2016 survey conducted by the journal Nature, researchers were asked if there was a reproducibility crisis.  Of the 1,576 who responded to the survey, 90% agreed that there was at least a slight crisis. 70% conceded that they were unable to reproduce a study conducted by another scientist, with over half admitting to being unable to reproduce a study that they, themselves, conducted! 

There are plenty of high-profile examples of research that were found to be irreproducible such as those described in the previous section that have prompted the question of whether or not science is experiencing a reproducibility crisis.  Recent studies to determine the extent to which published research is or is not reproducible have been concerning to many given that investigators were unable to successfully reproduce findings from a significant portion of published research.

The reasons for irreproducibility are plenty, but an issue that appears quite often is the lack of access to the materials and documentation necessary to repeat the analysis. 

> ## Yet Another Term: "Preproducibility"
> In a 2018 article published in the journal Nature, Phillip Stark offered another term for consideration for use in discussions of reproducibility:  *preproducibility*.  He wrote, “An experiment or analysis is preproducible if it has been described in adequate detail for others to undertake it.  Preproducibility is a prerequisite for reproducibility...” (p. 613).  The question of reproducibility, according to Stark, is irrelevant if documentation of research methods and protocols are insufficient or unavailable.  Stark declared his unequivocal stance on the subject, declining to review any manuscript that is not preproducible.    
>
> Read the article that introduces the concept of preproducibility here: <br/>
> **Stark, P. B. (2018). Before reproducibility must come preproducibility. *Nature*, *557*(7707), 613–613. [https://doi.org/10.1038/d41586-018-05256-0](https://doi.org/10.1038/d41586-018-05256-0)**
>
{: .callout}

> ## Averting the Reproducibility Crisis
> Consider one of the three scenarios from the previous exercise (“Reproducibility vs. Reproducibility”).  Provide responses to the following questions about the scenario you selected.
> - What may have been some consequences of the discovery that the study was not reproducible?
> - What were the causes of non-reproducibility?
> - What could the researchers of the original study have done differently to avoid the issues that rendered the research non-reproducible?
>
>> ## Solution
>> **Scenario 1 (Wansink)**:  All of the research outputs from the Cornell Food and Brand Lab have been called into question since the discovery of various problems in research led by Brian Wansink. The nutrition policies and programs in which Wansink played a part may need to be reconsidered in light Scenario 1 (Wansink):  All of the research outputs from the Cornell Food and Brand Lab have been called into question since the discovery of various problems in research led by Brian Wansink. The nutrition policies and programs in which Wansink played a part may need to be reconsidered in light of accusations of scientific misconduct.  Wansink’s published research findings were not reproducible because of his failure to provide access to documentation and data that could demonstrate the integrity of his analytic methods and results. Without it, Wansink’s scientific claims are indefensible.  Beyond providing access to documentation, data, and code, pre-registration could have been an effective strategy for preventing the problems seen in Wansink’s work.  Pre-registering a study obliges researchers to declare their hypothesis, study design, and analysis plan publicly prior to the start of research activities. Deviations from the plan require explanation, which makes the research more transparent. 
>>
>> **Scenario 2 (Reinhart & Rogoff)**: Governments who implemented austerity measures based on Reinhart & Rogoff’s findings may not have yielded the expected outcomes and exacerbated the economic crisis in their respective countries as a result.  The causes of non-reproducibility were primarily due to errors made in the Excel spreadsheet used by the original authors for calculations.  Rather than rely on a spreadsheet program, the authors could have used statistical software designed for data analysis to write and execute code to generate results. The code itself reveals the analytic steps taken to arrive at the reported results, which would have enabled the authors (and secondary users) to inspect and verify the validity of their analytic workflow and outputs. 
>>
>> **Scenario 3 (Cuddy)**: The publication of Cuddy’s power pose research and the scrutiny it was met with happened in the midst of heated arguments among psychologist about the scientific rigor of research produced in their disciplinary domain. Some scholars in the field took umbrage against published studies that presented seemingly unlikely findings and set to work to assess the validity of these findings. What they discovered was widespread abuse of researchers’ degrees of freedom as a means of generating positive, and likely more publishable, results.  Because of the publicity it received, Cuddy’s research became something of a poster child of the so-called reproducibility crisis in psychology with its questionable methods and perhaps overstated positive results.  This cast widespread doubt not only on her research findings, but also on those from the field of psychology writ large.  Clear and comprehensive documentation and justification of research protocols used in Cuddy’s experiments would have helped bolster the replicability of her research claims. 
>>
> {: .solution}
>
{: .discussion}

## Reproducibility Mandates
In light of consequential reproducibility failures, various research stakeholders have taken steps to promote and protect the integrity of scientific research.  

####Funding Agencies
Funding agencies make enormous scientific investments by sponsoring grant programs that provide support to research projects. To maximize their investments, many funders have issued policies that require grant awardees to make the materials produced in the course of funded research activities publicly available.  By doing so, the scientific community can reuse datasets, analysis code, and other research artifacts to extend and verify results. Below are examples of funding agencies that have data policies in place.

| Funding Agency | Summary |
| --- | --- | 
| [Alfred P. Sloan Foundation](https://sloan.org/storage/app/media/files/application_documents/Sloan-Grant-Proposal-Guidelines-Research-Projects.pdf) | "Scientific progress depends on the sharing of information, on the replication of findings, and on the ability of every individual to stand of the shoulders of her predecessors...potential grantees are asked to attend to the outputs their research will create and how those outputs can best be put in service to the larger scientific community." | 
| [Institute for Museum and Library Services (IMLS)](https://www.imls.gov/sites/default/files/digitalproduct.pdf) | "The digital products you create with IMLS funcing require effective stewardship to prtect and enhance their value, and they should be freely and readily available for use and reuse by librarries, archives, museums, and the public." |
| [NASA](https://science.nasa.gov/earth-science/earth-science-data/data-information-policy/data-rights-related-issues) | "...scientific data product algorithms and data products or services produced through the [Earth Science] program shall be made available to the user community on a nondiscriminitory basis, without restriction, and at no more than the marginal cost of fulfilling user requests." |
| [National Institutes of Health (NIH)](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-03-032.html) | "Data sharing enables researchers to rigorously test the validity of research findings, strengthen analyses through combined datasets, reuse hard-to-generate data, and explore new frontiers of discovery.  In addition, NIH emphasizes the importance of good data management practices, which provide the foundation for effective data sharing and improve the reproducibility and reliability of research findings. NIH encourages data management and data sharing practices consistent with the FAIR data principles." |
| [National Science Foundation (NSF)](https://www.nsf.gov/bfa/dias/policy/dmp.jsp) | "Investigators are expected to share with other researchers, at no more than incremental cost and within a reasonable time, the primary data, samples, physical collections and other supporting materials created or gathered in the course of work under NSF grants. Grantees are expected to encourage and facilitate such sharing." |

### Scholarly Journals
As stewards of the scientific record, journals bear responsibility for ensuring that the articles they publish contain verifiable claims.  Moreover, journals recognize the role they play in traditional tenure and promotion structures, which appraise scientific productivity based on publication of articles in scholarly journals.  Thus, journal policies that make publication contingent on data sharing and verification are considered a promising tool for advancing research reproducibility.  Below are examples of journals with rigorous data policies.

| Scholarly Journal | Summary |
| --- | --- |
| [American Journal of Political Science (AJPS)](https://ajps.org/ajps-verification-policy/) | "The corresponding author of a manuscript that is accepted for publication in the American Journal of Political Science must provide materials that are sufficient to enable interested researchers to verify all of the analytic results that are reported in the text and supporting materials...When the draft of the manuscript is submitted, the materials will be verified to confirm that they do, in fact, reproduce the analytic results reported in the article." |
| [American Economic Association (AEA) Journals](https://www.aeaweb.org/journals/data/data-code-policy) | "Authors of accepted papers that contain empirical work, simulations, or experimental work must provide, prior to acceptance, information about the data, programs, and other details of the computations sufficient to permit replication, as well as information about access to data and programs...The AEA Data Editor will assess compliance with this policy, and will verify the accuracy of the information prior to acceptance by the Editor." |
| [eLife](https://reviewer.elifesciences.org/author-guide/journal-policies) | "Regardless of whether authors use original data or are reusing data available from public repositories, they must provide program code, scripts for statistical packages, and other documentation sufficient to allow an informed researcher to precisely reproduce all published results." |
| [Personality Science](https://ps.psychopen.eu/index.php/ps/open-science) | "*Personality Science* (PS) takes good, transparent, reproducible, and open science very seriously. This means that all published papers will have underwent screening regarding to what extent they have fulfilled [Transparency and Openness Promotion (TOP) Guidelines](https://www.cos.io/initiatives/top-guidelines)." |
| [Science](https://www.science.org/content/page/science-journals-editorial-policies#research-standards) | "All data used in the analysis must be available to any researcher for purposes of reproducing or extending the analysis...In general, all computer code central to the findings being reported should be available to readers to ensure reproducibility...Materials/samples used in the analysis must be made available to any researcher for purposes of directly replicating the procedure." |

### Academic Societies
Academic societies have taken up the issue of reproducibility in updated professional codes of conduct or ethics.  Citing responsibility to advance research in their discipline, these formal documents obligate researchers to enable others to evaluate their knowledge claims through transparent research practices and public access to data and materials underlying those knowledge claims. Below is a list of academic societies that have issued policies or statements promoting data access and research transparency.

| Academic Society | Summary |
| --- | --- |
| [American Geophysical Union (AGU)](https://www.agu.org/-/media/Files/AGU-Data-Position-Statement-Final-2015.pdf) | "The	cost of collecting, processing,	validating,	documenting, and submitting data to a repository should be an integral part	of research	and	operational	programs.	The	AGU	scientific community	should recognize the professional value of	such activities." |
| [American Psychological Association (APA)](https://www.apa.org/ethics/code) | "After research results are published, psychologists do not withhold the data on which their conclusions are based from other competent professionals who seek to verify the substantive claims through reanalysis and who intend to use such data only for that purpose, provided that the confidentiality of the participants can be protected and unless legal rights concerning proprietary data preclude their release." |
| [American Sociological Association (ASA)](https://www.acm.org/code-of-ethics) | "Consistent with the spirit of full disclosure of methods and analyses, once findings are publicly disseminated, sociologists permit their open assessment and verification by other responsible researchers, with appropriate safeguards to protect the confidentiality of research participants...As a regular practice, sociologists share data and pertinent documentation as an integral part of a research plan." |


{% include links.md %}
