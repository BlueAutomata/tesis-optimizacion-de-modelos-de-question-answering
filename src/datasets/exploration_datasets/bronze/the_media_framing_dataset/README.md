# Framing Across Borders: News Media Corpus Framing in Mexico and Colombia

This README accompanies the dataset containing 140 labeled articles from two relevant news outlets in Colombia and Mexico.

## Datastet Description
The data set contains 140 labeled articles from two relevant news outlets in Colombia and Mexico.

The newspapers in the study were chosen for their audience scope, considering they inform on general topics, and have national coverage in print and digital versions. 

The articles were collected using the search engine on each outlet’s website covering a period of seven semesters: from May 2022 to August 2023. The process produced a unit of analysis of N=140 articles from the two outlets. El Universal 68, El Tiempo 72.

### Included Files

- [labels.csv]: Summary of labels and other metadata.
- [articles.zip]: Contains a folder of .txt files with the body of the articles.

## Data Format

The input documents are news articles. Each article is contained in its own UTF8-encoded .txt file. 
The title is on the first row. The content of the article starts after the first row.
The name of the files of the input articles have the following structure: Noticia_{ID}.txt, where {ID} is a unique numerical identifier. For example Noticia_1.txt

## CSV File Format

The CSV file contains the following information:

- **id**: Article ID.
- **frames**: Frames associated with the article.
- **tone**: Tone of the article.
- **principal_frames**: Principal frames of the article.
- **economic**: Label related to economics.
- **capacity_and_resources**: Label related to capacity and resources.
- **morality**: Label related to morality.
- **fairness_and_equality**: Label related to fairness and equality.
- **legality_constitutionality_and_jurisprudence**: Label related to legality and jurisprudence.
- **policy_prescription_and_evaluation**: Label related to policy and policy evaluation.
- **crime_and_punishment**: Label related to crime and punishment.
- **security_and_defense**: Label related to security and defense.
- **health_and_safety**: Label related to health and safety.
- **quality_of_life**: Label related to quality of life.
- **cultural_identity**: Label related to cultural identity.
- **public_opinion**: Label related to public opinion.
- **political**: Label related to politics.
- **external_regulation_and_reputation**: Label related to external regulation and reputation.

This is an example of a section of the gold file for the articles with ids 1 - 2:
```
id	frames	tone	principal_frames	economic	capacity_and_resources	morality	fairness_and_equality	legality_constitutionality_and_jurisprudence	policy_prescription_and_evaluation	crime_and_punishment	security_and_defense	health_and_safety	quality_of_life	cultural_identity	public_opinion	political	external_regulation_and_reputation
Noticia_1.txt	['external_regulation_and_reputation', 'legality_constitutionality_and_jurisprudence', 'policy_prescription_and_evaluation', 'crime_and_punishment']	neutral	legality_constitutionality_and_jurisprudence	0	0	0	0	1	1	1	0	0	0	0	0	0	1
Noticia_2.txt	['policy_prescription_and_evaluation', 'political', 'economic', 'morality', 'public_opinion', 'external_regulation_and_reputation']	neutral	political	1	0	1	0	0	1	0	0	0	0	0	1	1	1
```

## Folder Structure

- [Articles Folder]:
  - Noticia_1.txt
  - Noticia_2.txt
  - Noticia_3.txt
  - Noticia_4.txt
  - Noticia_5.txt
  - ...

