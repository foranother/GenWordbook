# :books:GenWordbook
Python을 기반으로 영단어장을 생성하는 프로그램
- 미드 'Friends' 스크립트 활용
- DAUM 영어사전 활용

## :heavy_check_mark:Develop Environment
- Language: [Python 3.7](http://www.python.org/)
- IDE Tool: [Pycharm](https://www.jetbrains.com/ko-kr/pycharm/)
- Package Manager: [Anaconda](https://www.anaconda.com/)
- Using Library: requests, beautifulsoup4, numpy, pandas, matplotlib, wordcloud, nltk

## 📔Contents
#### 1. 미드 'Friends' 대본 수집
- url : 'https://fangj.github.io/friends/season/0101.html'

#### 2. 단어만 추출(전처리 작업)
- nltk 라이브러리 활용해서 전처리 및 단어만 추출

#### 3. 단어 빈도수 순으로 나열 및 시각화
- nltk 라이브러리 활용해서 단어수, 단어수(중복단어 제거) 출력 및 단어 빈도수 순으로 출력

#### 4. 영단어 정보 웹 크롤링 및 매칭
- requests, beautifulsoup4 라이브러리를 활용하여 Daum 영어사전에서 해당 단어 정보를 수집 및 매칭

#### 5. 영단어장 생성 및 Excel 저장
- Pandas 라이브러리를 활용하여 영단어장(표 형태) 생성 => [단어, 뜻1, 뜻2, 뜻3, 뜻4, 뜻5] 형식
- Excel로 저장

#### 6. WordCloud 시각화
- numpy, wordcloud 라이브러리를 활용하여 wordcloud 시각화
