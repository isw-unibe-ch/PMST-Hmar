---
editor_options: 
  markdown: 
    wrap: sentence
---
# Person Marking in South-Central Trans-Himalayan: Hmar

This PARALEX set contains person markers in Hmar, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in "Paper in JOHD". Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ
 as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source_form column in the forms file contains the data exactly as it appears within the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purporses.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered. It also contains csv tables with matrix layouts of the paradigms (similar to what we usually find in published sources) and a plot showing the distribution of each morph across most relevant grammatical categories.

## Additional information specific to Hmar

* Gaps: For future negative there is an additional emphatic paradigm, but it has gaps for first on second person, 1PL.EXCL on third person, 1PL.INCL on third person and for 2PL on third person. The default paradigm has a gap for 2SG on first person.
* Tone: Hmar has contrastive tone, but a thorough analysis is outstanding, which is why tone is not marked in the source forms.
* Tags (according to native speaker intuition) for future paradimgs:
    * default: most frequent form, reportedly "very certain" that the future event will occur
    * pragmatically marked: second most frequent form, "more general statement" 
    * emphatic: these forms are constructed with a copula and seem to be associated with strong emotions (e.g. "I really won't see you!")
* Tags for nonfuture paradimgs and pronouns: only one form per cell -> all tagged as default




