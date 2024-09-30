# 참고문헌 메타 추출 데이터(Extraction data from reference metadata)

## Outline
- The corpus for extracting metadata from multilingual journal references.
- The corpus contains the tokens of reference string with IOB labels corresponding to metadata field types.
- The file named as “automatic_inspection_data(train_set).txt” was constructed through the fully automatic inspection process. It contains a total of 3,680,620 labeled references, and was used as training set for training our BERT-based parsing model in our study.
- The file named as “manual_insepction_data_(validation_set).txt” was developed through the manual inspection process by several annotators. It contains a total of 63,878 labeled references, and was used as validation set.
- The file named as “manual_inspection_data_(test_set).txt” was built through the manual inspection process. It contains a total of 71,489 labeled references, and was used as test set.
In the files, each reference is separated by a newline character. In each first line of references, a unique identifier and language type are listed.

## Data format(TXT)
- CoNLL 2002 Format, https://paperswithcode.com/dataset/conll-2002

![docimage4](https://github.com/user-attachments/assets/4715824c-c4d4-4456-bb63-7652f0fe13ce)

## Data statistics
- Number of labeled references: 3,815,987

##  Data download
http://doi.org/10.23057/47

## License
CC BY-NC
<br>(Copyright Holder : Korea Institute of Science and Technology Information)
