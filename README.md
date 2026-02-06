# MODIC: Moroccan Dialect Corpus

The **MODIC (Moroccan Dialect Corpus)** is a fully annotated corpus of Moroccan Arabic (Darija) collected from social media, primarily Facebook. It is designed for **linguistic research, NLP, and computational analysis** of the Moroccan dialect.

---

## Corpus Overview

- **Language:** Moroccan Arabic (Darija)  
- **Corpus Type:** User-generated content (posts, dialogues)  
- **Format:** JSON  
- **Available at:** [GitHub Repository](https://github.com/ILC4CWALM/Corpus_annotated)

---

## Annotation Layers

Each token in the corpus is annotated with multiple layers to support detailed linguistic analysis:

- **TOKEN:** Original token as it appears in the text.  
- **Vocalised Token:** Fully vocalised version in Arabic script.  
- **Arabic-msd:** Morphological description in **MSD** (Morpho-Syntactic Description).  
- **Buckwalter-msd:** Buckwalter transliteration combined with MSD.  
- **Lemma:** Lemmatized or canonical form of the token.  
- **Glosses:** English glosses describing the meaning(s) of the token.

These layers allow researchers to study morphology, syntax, and lexical semantics in Moroccan Arabic.

---

## Realization Steps

1. **Data Collection:**  
   - Collected posts, interactions, and dialogues in Moroccan Arabic from Facebook.  
   - Focused on informal and spontaneous language use.

2. **Preprocessing:**  
   - Tokenization and sentence segmentation.  
   - Removal of duplicates and irrelevant content.

3. **Morphological Analysis:**  
   - Annotated tokens using the **DiMORPH Morphological Analyzer**.  
   - Generated morpho-syntactic descriptions (MSD) for each token.

4. **Transliteration:**  
   - Applied **Buckwalter transliteration** to all Arabic tokens.

5. **Glossing:**  
   - Added English glosses for each token to support analysis and NLP applications.

6. **Manual Verification:**  
   - Linguists reviewed and corrected annotations to ensure accuracy.

7. **Compilation:**  
   - Combined all stories into a structured JSON format, preserving sentence and token-level annotations.

