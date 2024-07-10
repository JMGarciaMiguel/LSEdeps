---
layout: base
title:  'Spanish Sign Language UD'
udver: '2'
---

# UD for SPANISH SIGN LANGUAGE (LSE) <span class="flagspan"><img class="flag" src="../../flags/svg/AQ.svg" /></span>

## Tokenization and Word Segmentation

* The Spanish Sign Language treebank depends on the sign glosses provided in the source material, so the source texts is already tokenized. Each token corresponds to an id-gloss, i.e. a word that uniquely identifies each LSE sign. Sign glosses consist of uppercase Spanish rough equivalents. English equivalents are also provided as Gloss_en. Depicting constructions (also known as "classifier constructions") are preceded by "cl"
* Note that linearizing and transcribing or glossing a signed language is not trivial, and results in some degree of information loss. The gloss provided correspond to dominant hand (i.e., in most cases, right hand) articulations. However, non manual components are not included.
* Sign glosses are always delimited by whitespace.
* There is no punctuation.
* Multiword tokens are not used. 


## Morphology

### Tags

* Spanish Sign Language uses *** of the universal tags
* The following tags are not used:
    *

---
**Instruction**: Specify any unused tags. Explain what words are tagged as PART. Describe how the AUX-VERB and DET-PRON distinctions are drawn, and specify whether there are (de)verbal forms tagged as ADJ, ADV or NOUN. Include links to language-specific tag definitions if any.

---

### Features

* No UD morphological features are used for Spanish Sign Language treebank


## Syntax

* The following subtypes are used for Spanish Sign Language:
    * [compound:redup]()
    * [compound:svc]() for serial verb construction
    * [compound:vsc]()

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

