Data set name: PMST Ranglong

Data set developer(s): Hunter L. Brown, Sandra Auderset

Data sheet author(s): Hunter L. Brown, Sandra Auderset

Others who contributed to this document: Jessi Ranglong


# Motivation

**For what purpose was the data set created?**

This data set was created to investigate the dynamics of person marking in Ranglong and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. 2026. Full citation: Auderset, Sandra \& Brown, Hunter L. \& Reich, Jonathan \& Gerber, Pascal \& Zakaria, Muhammad \& Konnerth, Linda. 2026. A Database of Person Marking in South-Central Trans-Himalayan. Journal of Open Humanities Data 12(1), 58. (doi:https://doi.org/10.5334/johd.505).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.

# Composition

This Paralex data set documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Ranglong, it is a version of the community orthography used by speakers.

**How many instances are there in total?**

-   Number of inflected forms: 255

-   Number of unique inflected forms: 77

-   Number of unique scenarios (person, number, TAM, polarity combinations): 142

-   Number of inflected forms per paradigm and subparadigm:

|paradigm |paradigm_tag |variants_tag |overabundance_tag |  n|
|:--------|:------------|:------------|:-----------------|--:|
|pron     |             |unspecified  |                  |  6|
|fut.aff  |rang_fut     |unspecified  |optional_plural   | 15|
|fut.aff  |rang_fut     |unspecified  |                  | 34|
|fut.aff  |ti_fut       |unspecified  |optional_plural   | 16|
|fut.aff  |ti_fut       |unspecified  |                  | 26|
|fut.neg  |             |unspecified  |optional_plural   | 16|
|fut.neg  |             |unspecified  |                  | 34|
|nfut.aff |             |unspecified  |optional_plural   | 16|
|nfut.aff |             |unspecified  |                  | 34|
|nfut.neg |             |dialect_var  |optional_plural   |  2|
|nfut.neg |             |dialect_var  |                  |  5|
|nfut.neg |             |unspecified  |optional_plural   | 17|
|nfut.neg |             |unspecified  |                  | 34|



**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: rang1271
-   Language variety description: Ranglong is a South Central Trans-Himalayan language spoken at the tri-state border area of Tripura, Assam, and Mizoram, India. It is considered to be a variety of the 'Halam' language for official purposes, but linguistically speaking it is a distinct language exhibiting low mutual intelligibility with other Halam varieties. The ISO639 code refers to 'Halam' and not to Ranglong specifically, which is why the Glottocode should be used for most purposes.

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**

The data was collected in villages straddling the border of the Northeast Indian states of Tripura and Assam. It therefore exhibits characteristics of both known Ranglong varieties, which geographically align roughly with the two areas on either side of the state line.

**Does the data set contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 

The data set contains all person forms found in the language, both verbal indexes and pronouns, with the exception of hortative forms, which were not included in the data set.

**Is any information missing from individual instances?** 

There are two person scenarios in a particular future-affirmative paradigm that could not be elicited due to semantic restrictions. These are: 2SG>1SG.FUT.AFF and 2SG>1PL.FUT.AFF.

**Are there any errors, sources of noise, or redundancies in the data set?** 

No.

**Is the data set self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other data sets)?** 

The data set is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionaries), were there any complex decisions in the matching of entries from this data set to those of the vocabularies (eg. inexact language code) ?**
NA

**Does the data set contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The data set pertains to small or indigenous language communities, namely those of the Ranglong people in Tripura and Assam.
The data are published here with the consent of the community.


# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other data sets ?** 

The data comes from fieldwork conducted by Hunter L. Brown. Specific forms were taken from a combination of a text corpus, elicitation, and field notes. This work also forms the basis for the segmentation. 

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**What is the expertise of the contributors with the documented language ?** 

Hunter L. Brown: linguist specializing in South-Central Trans-Himalayan, currently preparing a reference grammar of Ranglong

Jessi Ranglong: native speaker and linguist

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 

The data was collected predominantly in fall and winter 2024.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**

All forms were collected from speakers. See above.

**How were the phonological or phonemic transcriptions obtained?** 

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes (not publicly available yet).

**Is the software that was used to preprocess/clean/label the data available?** 

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the data set been used for any published work already?** 

No.

**What (other) tasks could the data set be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the data set should not be used?**

No.


# Distribution.

**Will the data set be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the data set was created?**

No.

**How will the data set be distributed (for example, tarball on website, API, GitHub)?** 

The data set is available on GitHub at https://github.com/isw-unibe-ch and on Zenodo as part of the Paralex collection at https://doi.org/10.5281/zenodo.17881855.

**Will the data set be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 

The data set is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the data set, is there a mechanism for them to do so?** 

For suggestions or error reports please open an issue on GitHub.