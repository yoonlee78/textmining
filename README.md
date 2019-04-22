# Text mining

## 1. 깃헙 레포지토리 설치: 

Terminal 또는 git bash에서 

```git clone https://github.com/yoonlee78/textmining.git```

이미 clone을 했다면 업데이트를 위해 git pull을 한다. 

```git pull```



## 2. Anaconda 환경 설정 

- 맥일 경우:  

Anaconda Python 3.7 ver. Mac용

Git = 설치 필요 없음


- 윈도우일 경우: 

윈도우 10 이상 *권장*

Anaconda Python 3.7 Ver. Window용

Git bash 설치 필요

- Anaconda 환경은:


1. 주피터 노트북이 있어야하고

2. 파이썬 버전은 3 이상


위 사항이 충족되었다면, 주피터 노트북에서 다음 패키지 로딩에 문제가 없으면 됩니다.


1. 파이썬 분석 및 시각화: Numpy, pandas, matplotlib, seaborn, wordcloud


2. 텍스트 분석: nltk, KoNLPy, gensim, pyLDAvis, sklearn

* 참조: 윈도우에서 KoNLPy 설치하기 [링크1](https://konlpy-ko.readthedocs.io/ko/v0.4.3/install/) [링크2](https://junprogramer.tistory.com/103)

  2.1. 추가로 다음 코퍼스와 데이터를 다운로드 받는다. (강의 자료 내에 포함되어있습니다).

- nltk.download('wordnet')
- nltk.download('brown')
- 국민청원데이터(다운로드 링크: https://s3.ap-northeast-2.amazonaws.com/data10902/petition/petition.csv 출처: https://github.com/akngs/petitions에서 전체 데이터인 ```petetion.csv``` 다운로드)


** 참고 자료 및 문헌
- Stanford NLP: https://nlp.stanford.edu/
- Text Mining : https://ko.coursera.org/learn/text-mining
- 국민청원데이터 분석 : https://github.com/akngs/petitions, https://github.com/corazzon/petitionWrangling
- LDA : https://nlpforhackers.io/topic-modeling/, https://ai.stanford.edu/~ang/papers/nips01-lda.pdf
* 그 외 참고 자료는 노트북 파일에 기재 
