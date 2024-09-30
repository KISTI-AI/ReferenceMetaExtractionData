# ReferenceMetaExtractionData

## Outline
- The corpus for extracting metadata from multilingual journal references.
- The corpus contains the tokens of reference string with IOB labels corresponding to metadata field types.
- The file named as “automatic_inspection_data(train_set).txt” was constructed through the fully automatic inspection process. It contains a total of 3,680,620 labeled references, and was used as training set for training our BERT-based parsing model in our study.
- The file named as “manual_insepction_data_(validation_set).txt” was developed through the manual inspection process by several annotators. It contains a total of 63,878 labeled references, and was used as validation set.
- The file named as “manual_inspection_data_(test_set).txt” was built through the manual inspection process. It contains a total of 71,489 labeled references, and was used as test set.
In the files, each reference is separated by a newline character. In each first line of references, a unique identifier and language type are listed.

## Data format(TXT)
- CoNLL 2002 Format, https://paperswithcode.com/dataset/conll-2002

"""
Jou B-AUT
, I-AUT
<sp> I-AUT
J I-AUT
. I-AUT
<sp> I-AUT
H I-AUT
. I-AUT
<sp> I-AUT
et I-AUT
<sp> I-AUT
al I-AUT
. O
<sp> O
Plant B-TIT
<sp> I-TIT
growth I-TIT
<sp> I-TIT
absorption I-TIT
<sp> I-TIT
spectrum I-TIT
<sp> I-TIT
mimicking I-TIT
<sp> I-TIT
light I-TIT
<sp> I-TIT
sources I-TIT
. O
<sp> O
Materials B-JOU
<sp> O
8 B-VOL
, O
<sp> O
5265 B-PAGE
- I-PAGE
5275 I-PAGE
<sp> O
( O
2015 B-YEAR
) O
. O
"""

## Data statistics
- Number of labeled references: 3,815,987

##  Data download
http://doi.org/10.23057/47
