# MODIC: Moroccan Dialect Corpus

**MODIC (Moroccan Dialect Corpus)** is a morphologically annotated corpus of Moroccan Arabic (Darija), developed to support linguistic research, Natural Language Processing (NLP), and computational analysis of Moroccan Arabic. The corpus consists of user-generated language data collected primarily from public Facebook pages and processed through a combination of automatic morphological analysis and manual linguistic verification.

## Corpus Overview

- **Name:** MODIC (Moroccan Dialect Corpus)
- **Language:** Moroccan Arabic (Darija)
- **Corpus Type:** User-generated content (posts and dialogues)
- **Data Format:** JSON
- **Annotation Level:** Token-level morphological and lexical annotation
- **Main Repository:** [GitHub Repository](https://github.com/ILC4CWALM/Corpus_annotated)

## Annotation Layers

Each token in the corpus is enriched with multiple annotation layers to support detailed morphological and lexical analysis:

- **TOKEN:** Original token as it appears in the source text.
- **Vocalised Token:** Vocalised representation of the token in Arabic script.
- **Arabic-MSD:** Morphological description using Morpho-Syntactic Description (MSD) tags.
- **Buckwalter-MSD:** Buckwalter transliteration combined with morphological descriptions.
- **Lemma:** Lemmatized or canonical form of the token.
- **Glosses:** English glosses describing the meaning of the token.

Together, these annotation layers provide information for studying the morphology, lexical properties, and linguistic structure of Moroccan Arabic.

## Corpus Development and Annotation Workflow

The corpus was developed through the following stages:

1. **Data Collection**
   - Collection of Moroccan Arabic posts, interactions, and dialogues from public Facebook pages.
   - Focus on informal and spontaneous language use.

2. **Preprocessing**
   - Tokenization and sentence segmentation.
   - Removal of duplicate and irrelevant content.

3. **Morphological Analysis**
   - Automatic morphological analysis using the **DiMORPH Morphological Analyzer**.
   - Generation of morpho-syntactic descriptions (MSD) for individual tokens.

4. **Transliteration**
   - Application of the **Buckwalter transliteration scheme** to Arabic-script tokens.

5. **Glossing**
   - Addition of English glosses to facilitate linguistic interpretation and support NLP applications.

6. **Manual Verification and Validation**
   - Review and correction of automatically generated annotations by linguists.
   - Expert supervision and final validation to improve annotation consistency and accuracy.

7. **Corpus Compilation**
   - Integration of the annotated texts into structured JSON files.
   - Preservation of sentence-level and token-level annotation information.

## Data Availability

The annotated data are available in this repository:

[https://github.com/ILC4CWALM/Corpus_annotated](https://github.com/ILC4CWALM/Corpus_annotated)

A versioned archival copy will also be made available through Zenodo, with a persistent DOI to be added upon publication.

## Licence

The annotated data and original documentation in this repository are intended to be distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** licence, subject to the applicable rights and permissions.

For licence details, see:

[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

## Citation

If you use MODIC in your research, please cite the corpus as follows:

**MODIC: Moroccan Dialect Corpus.** Version 1.0.0. Zenodo. [DOI to be added].

Please provide appropriate attribution to the corpus creators when using, sharing, or adapting the annotated data.
