---
layout: base
title:  'Spanish Sign Language UD'
udver: '2'
---

# UD for SPANISH SIGN LANGUAGE (LSE) <span class="flagspan"><img class="flag" src="../../flags/svg/AQ.svg" /></span>

## Tokenization and Word Segmentation

* The Spanish Sign Language treebank depends on the sign glosses provided in the source material, so the source texts is already tokenized.
* Note that linearizing and transcribing or glossing a signed language is not trivial, and results in some degree of information loss. The gloss provided correspond to dominant hand (i.e., in most cases, right hand) articulations. However, non manual components are not included.
* Sign glosses consist of uppercase Spanish rough equivalents. Depicting constructions (also known as "classifier constructions") are preceded by "cl"
* Sign glosses are always delimited by whitespace.
* There is no punctuation.
* Multiword tokens are not used. 

---
**Instruction**: Describe the general rules for delimiting words (for example, based on whitespace and punctuation) and exceptions to these rules. Specify whether words with spaces and/or multiword tokens occur. Include links to further language-specific documentation if available.

---

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

---
**Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any.

---

## Syntax

* The following subtypes are used for Spanish Sign Language:
    * compound:redup
    * compound:svc for serial verb construction
    * compound:vsc

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There are [N](../treebanks/LCODE-comparison.html) LANGUAGE UD treebanks:

  * [LANGUAGE-A](../treebanks/LCODE_a/index.html)
  * [LANGUAGE-B](../treebanks/LCODE_b/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
