# TREC-2022 Clinical Trials Track
# This document summarizes the ClinicalBERT Term extraction process of the TREC-2022 project.

* TREC-2022 프로젝트의 ClinicalBERT 용어 추출(Term extraction) 과정을 개별 정리한 문서입니다.

```
https://trec.nist.gov/
https://trec-cds.org/2022.html
```

## Large Storage Flies
* cce_assets/blstm/model.data-00000-of-00001
```
https://mega.nz/file/Sk8kjQBS#QQ7NW0nX2xkzEr0VZwFos7tUULWZvyFZRgqayWLUpgo
```

* cce_assets/elmo/mimic_wiki.hdf5
```
https://mega.nz/file/DkFwmRbQ#oerd2GVL0je9h4ylo1tG_-EHijGSYrtfpHW1I5n-Bns```
```
## Getting Started

* 아래의 파이썬 라이브러리를 설치
```
! 수정 예정 !
```

## Process in .ipynb

### 1. Preprocessing_docs
* TREC-CDS Track 의 임상 시험 문서에 대한 전처리 작업

### 2. CB_extractor
### 2-1. simple_sentence_segment & Library Install
* 필요한 라이브러리 삽입

### 2-2. Load 100 Documents
* 전처리가 끝난 문서 100개 로드

### 2-3. ClinicalTerms Extraction
* ClinicalBERT 를 이용한 Terms 추출



## ClinicalBERT Origin & Techniques
* https://github.com/EmilyAlsentzer/clinicalBERT.git
