# S24Corpus-final

written by Woochang Jung

### 1. Introduction
Understanding English grammar well help learners use English more accurately as a second language (L2). One common challenge for learners of English as a foreign language (EFL) is mastering the passive voice. Learners from different first language (L1) backgrounds often find English passives difficult (Loan, 2019). Those whose L1 does not have the passive voice struggle more with English passives (Cowan, 2008). Even learners whose L1 includes some passive forms face challenges. For example, L1-Thai speakers, whose language mainly uses passives in a negative way, often make mistakes with English passive constructions (Simargool, 2008). In addition to the 'be-passive' (be + past participle), the 'get-passive' (get + past participle) is also widely used in spoken English (Leech, Hundt, Mair, & Smith, 2009). Many studies based on language corpora highlight the prevalence of get-passives in various English dialects (e.g., Carter & McCarthy, 1999; Mair, 2006). Granger (1983) compared the use of 'get-passives' between British and American English, noting that they are less common in British English, while 'be-passives' are more frequent than 'get-passives' in both dialects. Additionally, Weiner and Labov (1983) found that the use of 'get-passives' is increasing among American English speakers.

This article examines the distribution of the English 'get-passive' compared to the 'be-passive.' A corpus study is used to find out the frequency of 'get-passive' and 'be-passive' in written and spoken texts. The findings of this study provide valuable insights for teaching 'get-passives' in the EFL context.

### 2. Literature Review

#### 2.1 Characteristics of Central Get-Passives

##### 2.1.1 Absence of an Agent By-Phrase
Central get-passives often lack an agent. Studies confirm that get-passives typically "do not include an expressed animate agent" (Quirk et al., 1985, p. 161). In Collins' (1996) research, 92% of get-passives did not have an agent, and Carter and McCarthy (1999) found a similar result with 93% being agentless, as shown in example (1):
(1) Henry got beaten last night.

##### 2.1.2 Dynamic Lexical Verb
Get-passives are exclusively used with dynamic verbs, which indicate actions rather than outcomes (Huddleston & Pullum, 2002, p. 1442). Alexiadou (2005) states that "the get-passive is not used with stative verbs or verbs where the subject cannot be seen as affected." For instance, be cannot be replaced by get in sentences like example (2) (Huddleston & Pullum, 2002, p. 1442):
(2) It was/*got believed that the letter was a forgery.

Get-passives frequently occur with verbs related to daily activities (e.g., get changed, cleaned) and informal expressions (e.g., get kicked out, muddled up), highlighting their informal nature.

##### 2.1.3 Responsibility of the Subject
Subjects in get-passives often have some responsibility for initiating the event. Huddleston (1984) points out that "get" suggests that the subject has some degree of initiative, unlike "be." For example, in (3) (Givón & Yang, 1994, p. 120), the subject of the get-passive bears some responsibility:
(3) He got caught by the police.
    He was caught by the police.

Additional evidence is found in constructions like 'try + to/and + get Ven' and 'manage + to + get Ven' (Collins, 1996, p. 51):
(4) Our advice is for both to go and get involved in the new technology.
(5) He managed to get transferred to the combat forces.

##### 2.1.4 Animacy of the Subject
Animate human referents often connect the concepts of subject animacy, control, and responsibility. Toyota (2007) found that 85.7% of subjects in get-passives are animate, with 84.7% being human. However, get-passives with inanimate subjects, which cannot bear responsibility, are not uncommon (Givón, 1993). Example (6) illustrates this:
(6) Peter’s video recorder got fixed last week.

##### 2.1.5 Semantic Implication
Hatcher (1949) observed that central get-passives are used for events with non-neutral outcomes. Fleisher (2006) noted that these events have either fortunate or unfortunate consequences for the subject. Most get-passives signal unfortunate events (Carter & McCarthy, 1999). For example, verbs like get arrested, beaten, criticized, and penalized typically refer to adverse events (Hatcher, 1949; Budwig, 1990). Collins (1996) found that 67% of get-passives had adversative meanings, while Leech et al. (2009) noted an increase in adversative get-passives from 60.3% to 66.3% between the 1960s and 1990s.

Corpus studies show that central get-passives often convey emotive or interpersonal meanings, reflecting either the speaker’s attitude or the subject's situation, unlike the neutral be-passives (Stubbs, 2001; Fryd, 2008). Thus, be- and get-passives are not pragmatically equivalent (Siewierska, 1984; Guerrero Medina, 2009). Biber et al. (1999) concluded that get-passives usually select verbs with negative connotations, indicating actions that are difficult or disadvantageous for the subject. Rühlemann (2007) emphasized that the central get-passive prefers verbs with an 'adversative' core meaning.

### 3. Data Collection Methodology

#### 3.1 Spoken Data Collection

**Data Source**
The spoken data were collected from TED, specifically focusing on the 100 most viewed video clips within the communication section. TED videos are selected for their high engagement and diverse range of topics, providing a rich source for linguistic analysis (TED, n.d.).

**Selection Criteria**
- **Popularity**: Videos were selected based on view count to ensure that only the most popular presentations were included.
- **Category**: Only videos categorized under the "communication" section were considered to maintain thematic coherence.
- **Speaker Criteria**: Only videos featuring native-like or native speakers of English were included to ensure linguistic consistency and relevance.

**Data Cleaning**
- **Transcription**: The audio content of each video was transcribed using automated transcription tools, followed by manual verification to ensure accuracy.
- **Timestamp Removal**: All timestamps were removed from the transcripts to maintain a continuous flow of text.
- **Exclusion of Non-verbal Elements**: Elements such as laughter, applause, and other non-verbal cues were excluded to focus solely on the spoken language.
- **Consistency Check**: The final transcripts were reviewed for formatting consistency and to confirm the removal of non-verbal elements.

#### 3.2 Written Data Collection

**Data Source**
Written data were extracted from the News on the Web (NOW) corpus, a comprehensive linguistic resource comprising a vast collection of online news articles. This corpus is designed to support research in linguistics, language variation, and diachronic change (Davies, 2013).

**Content and Scope**
The NOW corpus includes millions of words from web-based news articles across a broad spectrum of news websites, ensuring a diverse representation of contemporary online language use.

**Sample Selection and Cleaning**
- For this study, samples from the NOW corpus collected between 2010 and 2016 were used. The sample data consists of 2,916 texts, totaling approximately 1.7 million words.
- **Downloading and Preprocessing**: The samples were downloaded from the NOW corpus. Python scripts were utilized to remove unnecessary characters such as HTML tags (`<p>`, `<h>`), and to split the text IDs. This preprocessing step ensured that the data was clean and ready for analysis.

#### 3.3 Rationale for Comparison

The reason for comparing TED talks from the communication section and the NOW corpus is to ensure the authenticity and level of language proficiency in both spoken and written data. This comparison is crucial for achieving the research objective: to find out the frequency of 'be passives' and 'get passives'. By selecting sources that are comparable in terms of language use and authenticity, the study ensures that the analysis of passive constructions is legitimate and reflective of contemporary usage in both modes of communication.

#### 3.4 Combined Data Set

The combined dataset for this research includes:
- **Spoken Data**: Cleaned transcripts from 100 TED video clips featuring native-like or native speakers of English, ensuring high-quality spoken language data.
- **Written Data**: Samples from the NOW corpus collected between 2010 and 2016, comprising 2,916 texts with 1.7 million words, representing a wide array of online news articles.

This meticulously curated dataset provides a robust foundation for the analysis of language use in both spoken and written forms, supporting the validity and reliability of the research findings.

## 4. Result and discussion
![Alt text](https://github.com/Alexwcjung/S24Corpus-final/blob/main/Corpus/Percentage%20of%20Passives%20in%20Spoken%20and%20Written%20Texts.png)
![Percentage of Passives in Spoken and Written Texts](https://github.com/Alexwcjung/S24Corpus-final/blob/main/Corpus/Table%201.png)
![Chi-Squared Test Results](https://github.com/Alexwcjung/S24Corpus-final/blob/main/Corpus/Chi-Squared%20Test%20Results.png)

#### Interpretation
The Chi-square test yielded a statistic of 359.143 with a p-value of 4.327e-80, indicating a highly significant result. With a degrees of freedom of 1, the extremely low p-value allows us to reject the null hypothesis, which posited no difference in the usage of passive constructions between spoken and written texts.

## 5. Conclusion and future research
The analysis shows that the use of passive constructions ('be + past participle' and 'get + past participle') is significantly different between spoken and written texts. Specifically, 'be + past participle' is much more common in both spoken and written forms. However, 'get + past participle' is found more often in spoken texts than in written texts, though it is still less common overall. These findings indicate that while both forms of passive constructions are used in English, their usage depends on the context, highlighting differences between spoken and written communication. The higher frequency of 'get + past participle' in spoken texts may be due to its more conversational nature, while 'be + past participle' remains the standard in written texts. This insight is useful for linguistic studies, helping us understand how language varies in different communication modes.


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
