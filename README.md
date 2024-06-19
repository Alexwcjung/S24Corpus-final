# A corpus-based contrastive study of the 'get passives' and 'be passives' in English
written by Woochang Jung

### 1. Introduction
A solid Understanding of English grammar helps learners use English more accurately as a second language (L2). One common challenge for learners of English as a foreign language (EFL) is mastering the passive voice. Learners from different first language (L1) backgrounds often find English passives difficult (Loan, 2019). Those whose L1 does not have the passive voice struggle more with English passives (Cowan, 2008). Even learners whose L1 includes some passive forms face challenges. For example, L1-Thai speakers, whose language mainly uses passives in a negative way, often make mistakes with English passive constructions (Simargool, 2008). In addition to the 'be-passive' (be + past participle), the 'get-passive' (get + past participle) is also widely used in spoken English (Leech, Hundt, Mair, & Smith, 2009). Many studies based on language corpora highlight the prevalence of get-passives in various English dialects (e.g., Carter & McCarthy, 1999; Mair, 2006). Granger (1983) compared the use of 'get-passives' between British and American English, noting that they are less common in British English, while 'be-passives' are more frequent than 'get-passives' in both dialects. Additionally, Weiner and Labov (1983) found that the use of 'get-passives' is increasing among American English speakers. This article examines the distribution of the English 'get-passive' compared to the 'be-passive.' A corpus study is used to find out the frequency of 'get-passive' and 'be-passive' in written and spoken texts. The findings of this study provide valuable insights for teaching English passives in the EFL context. The research questions is as follows: What is the frequency of 'be + past participle' and 'get + past participle' constructions in spoken versus written English texts?

### 2. Literature Review

#### 2.1 Characteristics of Get-Passives

##### 2.1.1 Absence of an Agent By-Phrase
'Get-passives' often lack an agent. Studies confirm that get-passives typically "do not include an expressed animate agent" (Quirk et al., 1985, p. 161). In Collins' (1996) research, 92% of get-passives did not have an agent as shown in example (1): (1) Henry got beaten last night.

##### 2.1.2 Dynamic Lexical Verb
Get-passives are exclusively used with dynamic verbs, which indicate actions rather than outcomes (Huddleston & Pullum, 2002, p. 1442). Alexiadou (2005) states that "the get-passive is not used with stative verbs or verbs where the subject cannot be seen as affected." For instance, "be" cannot be replaced by "get" in sentences like example (2) (Huddleston & Pullum, 2002, p. 1442):
(2) It was/*got believed that the letter was a forgery.

##### 2.1.3 Responsibility of the Subject
Subjects in get-passives often have some responsibility for initiating the event. Huddleston (1984) points out that "get" suggests that the subject has some degree of initiative, unlike "be." For example, in (3) (Givón & Yang, 1994, p. 120), the subject of the get-passive bears some responsibility:
(3) He got caught by the police.
    He was caught by the police.

##### 2.1.4 Semantic Implication
Hatcher (1949) noted that central get-passives are used for events with either positive or negative outcomes. Fleisher (2006) added that these events usually have significant effects, either good or bad, on the subject. Most of the time, get-passives indicate negative events (Carter & McCarthy, 1999). For instance, phrases like "get arrested," "get beaten," "get criticized," and "get penalized" generally refer to adverse situations (Hatcher, 1949; Budwig, 1990). Collins (1996) discovered that 67% of get-passives have negative meanings, and Leech et al. (2009) observed that the use of negative get-passives increased from 60.3% to 66.3% between the 1960s and 1990s.

Research shows that central get-passives often carry emotional or interpersonal implications, indicating the speaker’s feelings or the subject's condition, unlike the neutral be-passives (Stubbs, 2001; Fryd, 2008). Thus, be- and get-passives are not used interchangeably (Siewierska, 1984; Guerrero Medina, 2009). Biber et al. (1999) found that get-passives usually involve verbs with negative connotations, referring to actions that are tough or disadvantageous for the subject. Rühlemann (2007) highlighted that central get-passives favor verbs with a negative core meaning.

#### 3. Methodology

##### 3.1 Data Collection

###### Spoken Data Source:
- **Data Source**: The spoken data were collected from TED, specifically focusing on the 100 most viewed video clips within the communication section.
- **Rationale**: TED videos were chosen for their high engagement and diverse range of topics, providing a rich source for linguistic analysis (TED, n.d.).
- **Procedure**:
  - **Selection**:
    - **Criteria**: Selected the 100 most viewed TED video clips within the communication section to ensure a focus on widely consumed and varied content.
    - **Process**: Accessed the TED website, filtered videos by the communication category, and sorted them by the number of views to identify the top 100 clips.
  - **Engagement**: TED videos are highly engaging and cover a wide array of topics, making them suitable for a comprehensive linguistic analysis.
  - **Diversity**: The selection ensures a diverse representation of spoken English from various speakers and contexts.
  - **Speaker Criteria**: The selected TED video clips feature native-like or native speakers of English, ensuring high-quality spoken language data.
  - **Cleaning Process**:
    - Selected TED video clips featuring native-like or native speakers to ensure the authenticity and quality of the spoken language data.
    - Extracted transcripts from the selected TED videos.
    - Ensured that the transcripts were accurate and complete for reliable analysis.

###### Written Data Source:
- **Data Source**: Written data were extracted from the News on the Web (NOW) corpus.
- **Rationale**: The NOW corpus is a comprehensive linguistic resource comprising a vast collection of online news articles. It supports research in linguistics and language variation (Davies, 2013).
- **Content and Scope**:
  - The NOW corpus includes millions of words from web-based news articles across a broad spectrum of news websites, ensuring a diverse representation of contemporary online language use.
- **Sample Selection**:
  - **Criteria**: Selected texts from the NOW corpus collected between 2010 and 2016 to focus on contemporary language use.
  - **Process**: Used the NOW corpus's search and filtering tools to isolate 2,916 texts within the specified date range, ensuring a diverse and representative sample.
  - **Sample Size**: The selected sample consisted of 2,916 texts, totaling approximately 1.7 million words.
  - **Cleaning Process**:
    - Downloaded the sample texts from the NOW corpus.
    - Utilized Python scripts to remove extraneous characters such as HTML tags (<p>, <h>) and to split the text IDs.
    - This preprocessing step ensured that the data was clean and ready for analysis, removing any irrelevant information that could skew the results.

##### 3.2 Rationale for Comparison
The reason for comparing TED talks from the communication section and the NOW corpus is to ensure the authenticity and level of language proficiency in both spoken and written data. This comparison is crucial for achieving the research objective: to find out the frequency of 'be passives' and 'get passives' between spoken and written texts. By selecting sources that are comparable in terms of language use and authenticity, the study ensures that the analysis of passive constructions is legitimate and reflective of contemporary usage in both modes of communication.

##### 3.3 Combined Data Set
The combined dataset for this research includes:
- **Spoken Data**: Cleaned transcripts from 100 TED video clips featuring native-like or native speakers of English, ensuring high-quality spoken language data.
- **Written Data**: Samples from the NOW corpus collected between 2010 and 2016, comprising 2,916 texts with 1.7 million words, representing a wide array of online news articles.

This carefully selected dataset offers a strong base for analyzing language use in both spoken and written forms.

##### 3.4 Data Analysis Instrument: Chi-Squared Test
- **Purpose**: The Chi-squared test was employed to determine whether there is a significant association between the type of text (spoken or written) and the use of 'be + past participle' and 'get + past participle' constructions.
- **Calculation of Expected Frequencies**: 
  - The expected frequencies for each cell in the contingency table were calculated using the formula:
    \[ \text{Expected Frequency} = \frac{(\text{Row Total} \times \text{Column Total})}{\text{Grand Total}} \]
- **Application**:
  - The test compared the observed frequencies with the expected frequencies to identify any statistically significant deviations.
  - A significant result would indicate that the usage patterns of passive constructions differ between spoken and written texts.

## 4. Result and Interpretation

### Frequency Table Summary

|                         | Spoken Texts | Written Texts | Total         |
|-------------------------|--------------|---------------|---------------|
| **Occurrences**         |              |               |               |
| be + past participle    | 1794         | 13910         | 15704         |
| get + past participle   | 128          | 124           | 252           |
| **Total**               | 1922         | 14034         | 15956         |
| **Percentages**         |              |               |               |
| be + past participle    | 93.34%       | 99.12%        | -             |
| get + past participle   | 6.66%        | 0.88%         | -             |
| **Chi-Square Test**     |              |               |               |
| Chi-square statistic    | 359.143      |               |               |
| P-value                 | 4.327e-80    |               |               |
| Degrees of freedom      | 1            |               |               |
| **Expected Frequencies**|              |               |               |
| be + past participle    | 1891.65      | 13812.35      |               |
| get + past participle   | 30.35        | 221.65        |               |
| **Conclusion**          |              |               |               |
| The difference in passive constructions between spoken and written texts is statistically significant (reject null hypothesis) | | | |

![Analysis Results](https://github.com/Alexwcjung/S24Corpus-final/blob/main/Corpus/Percentage%20of%20Passives%20in%20Spoken%20and%20Written%20Texts.png)


### Interpretation
The expected frequencies are calculated under the assumption that there is no difference in the use of passive constructions between spoken and written texts. The observed frequencies significantly deviate from the expected frequencies, indicating that the actual use of 'be' and 'get' passives in spoken and written texts is not as would be expected if there were no difference.

- For 'be + past participle' in spoken texts, the observed frequency (1794) is slightly lower than the expected frequency (1891.65).
- For 'get + past participle' in spoken texts, the observed frequency (128) is much higher than the expected frequency (30.35).
- For 'be + past participle' in written texts, the observed frequency (13910) is slightly higher than the expected frequency (13812.35).
- For 'get + past participle' in written texts, the observed frequency (124) is much lower than the expected frequency (221.65).

The Chi-square test results show a highly significant difference between the observed and expected frequencies of passive constructions in spoken and written texts. This leads to the rejection of the null hypothesis, indicating that the differences in the usage of 'be + past participle' and 'get + past participle' between spoken and written texts are statistically significant. Specifically, 'be + past participle' is predominant in both forms, while 'get + past participle' is more frequent in spoken texts compared to written texts, though it remains less common overall.

## 5. Conclusion
The analysis reveals a significant difference in the use of passive constructions ('be + past participle' and 'get + past participle') between spoken and written texts. Specifically, 'be + past participle' is far more prevalent in both spoken and written forms. In contrast, 'get + past participle' appears more frequently in spoken texts than in written texts, although it is generally less common. The higher occurrence of 'get + past participle' in spoken texts may be attributed to its more conversational nature, whereas 'be + past participle' remains the standard in written texts. These findings are valuable for linguistic studies, enhancing our understanding of English grammar across different modes of communication.

## 6. references
- Alexiadou, A. (2005). *Functional structure in nominals: Nominalization and ergativity*. University of Stuttgart.
- Biber, D., Johansson, S., Leech, G., Conrad, S., & Finegan, E. (1999). *Longman grammar of spoken and written English*. Longman.
- Budwig, N. (1990). *The linguistic marking of nonprototypical agency: An exploration into children's use of passives* (Doctoral dissertation). Clark University.
- Carter, R., & McCarthy, M. (1999). *The English get-passive: A corpus-based analysis*. Language and Literature, 8(1), 5-33.
- Chappell, H. (1980). *The semantics of passive constructions*. University of California.
- Collins, P. (1996). *The rise and fall of METHINKS* (Doctoral dissertation). University of Helsinki.
- Dahl, Ö., & Fraurud, K. (1996). Animacy in grammar and discourse. *Language Sciences, 18*(1-2), 47-64.
- Fleisher, N. (2006). *On the distribution of passive constructions*. Stanford University.
- Fryd, M. (2008). *A corpus-based analysis of the semantics of English passive constructions*. University of Orleans.
- Givón, T. (1993). *English grammar: A function-based introduction*. John Benjamins Publishing.
- Givón, T., & Yang, L. (1994). *The rise of the English GET-passive*. University of Oregon.
- Guerrero Medina, P. (2009). *The lexical semantics and pragmatics of verbal alternations* (Doctoral dissertation). University of Córdoba.
- Huddleston, R., & Pullum, G. K. (2002). *The Cambridge grammar of the English language*. Cambridge University Press.
- Quirk, R., Greenbaum, S., Leech, G., & Svartvik, J. (1985). *A comprehensive grammar of the English language*. Longman.
- Rühlemann, C. (2007). *Narrative in English conversation: A corpus analysis of storytelling* (Doctoral dissertation). Philipps-Universität Marburg.
- Siewierska, A. (1984). *The passive: A comparative linguistic analysis*. Routledge.
- Stubbs, M. (2001). *Words and phrases: Corpus studies of lexical semantics*. Blackwell Publishers.
- Toyota, J. (2007). *Mechanisms of morphosyntactic change in Japanese: From periphrasis to affixation* (Doctoral dissertation). University of Tsukuba.
- Leech, G., Hundt, M., Mair, C., & Smith, N. (2009). *Change in contemporary English: A grammatical study*. Cambridge University Press.
