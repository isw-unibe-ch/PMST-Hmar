---
editor_options: 
  markdown: 
    wrap: sentence
---

Data set name: PMST Hmar

Data set developer(s): Jonathan Reich, Marina Infimate, Sandra Auderset

Data sheet author(s): Jonathan Reich, Sandra Auderset


# Motivation

**For what purpose was the dataset created?**

This data set was created to investigate the dynamics of person forms in Hmar and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. (in prep).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.


# Composition

This Paralex dataset documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Hmar, it is a version of the community orthography used by speakers.

**How many instances are there in total?**

-   Number of inflected forms: 267

-   Number of unique inflected forms: 137

-   Number of unique scenarios (person, number, TAM, polarity combinations): 163

-   Number of inflected forms per paradigm and subparadigm:

    +----------+--- -+----------------+----+
    | Paradigm | n   | Tags           | n  |
    +==========+====:+================+===:+
    | Pronouns | 7   | default        | 7  |
    +----------+-----+----------------+----+
    | NFUT.AFF |  39 | default        | 39 |
    +----------+-----+----------------+----+
    | NFUT.NEG |  39 | default        | 39 |
    +----------+-----+----------------+----+
    | FUT.AFF  |  78 | default        | 39 |
    |          |     |                |    |
    |          |     | pragm.m        | 39 |
    +----------+-----+----------------+----+
    | FUT.NEG  | 104 | default        | 37 |
    |          |     |                |    |
    |          |     | pragm.m        | 39 |
    |          |     |                |    |
    |          |     | emph           | 28 |
    +----------+-----+----------------+----+

**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: hmar1241

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**
The data was collected in a few villages in the state of Manipur, specifically in the subdivisions of Churachandpur, Tipaimukh, and Jiribam. Most of the data comes from the town of Churachandpur.

**Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 
The dataset contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the dataset (see below for explanation).

**Is any information missing from individual instances?** 
The perfective forms for transitives are not included. The language is tonal, but tone is not marked because the tone system is insufficiently analysed at this point.

**Are there any errors, sources of noise, or redundancies in the dataset?** 
No.

**Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)?** 
The dataset is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this dataset to those of the vocabularies (eg. inexact language code) ?**
NA

**Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**
The dataset pertains to small or indigenous language communities, namely those of the Hmar people in Manipur.
The data are published here with the consent of the community.

**Any other comments?**
NA

# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other datasets ?** 
The data comes from fieldwork conducted by Marina Infimate. Specific forms were taken from a combination of elicitation and field notes. This work also forms the basis for the segmentation, but this was further elaborated on by Jonathan Reich.

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**
Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**
Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**What is the expertise of the contributors with the documented language ?** 
Jonathan Reich: linguist specializing in South-Central Trans-Himalayan morphosyntax
Marina Infimate: native speaker and linguist

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**
Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 
The data was collected predominantly in 2016 and checked in 2023-2025.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**
All forms were collected from speakers. See above.

**How were the phonological or phonemic transcriptions obtained?** 
The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the current phonological analysis of the language.

**If relevant, how were the forms segmented?**
Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 
No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**
No.

**Is the software that was used to preprocess/clean/label the data available?** 
The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the dataset been used for any published work already?** 
No.

**What (other) tasks could the dataset be used for?**
It can be used for descriptive and comparative analyses.

**Are there tasks for which the dataset should not be used?**
No.


# Distribution.

**Will the dataset be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the dataset was created?**
No.

**How will the dataset be distributed (for example, tarball on website, API, GitHub)?** 
The dataset is available on GitHub at X and on Zenodo as part of the Paralex collection at X.

**Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 
The dataset is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?** 
For suggestions or error reports please open an issue on GitHub.
