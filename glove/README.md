# 한국어 GloVe

## [개요]

한국어 어절 단위 GloVe 임베딩 파일입니다. (100차원)



## [ 학습 데이터 ]

출처: 세종 코퍼스

문장 수: 62,343

단어 수: 197,997 (어절 단위)



## [ 모델 ]

### :: co-occurence ::

window-size = 10

min-count = 10



### :: glove ::

vector-size = 100

iterations = 25

learning-rate = 0.05



## [ 임베딩 예시 ]

원자론을 0.003327470646364432 0.0023967049260820764 0.0018002954775683355 0.0005108058532675697 ... ..
나가는가. -0.0029350388208459945 -0.00010133777110966185 -0.0019622735540850513 0.0004467412251418614 ...



## [ 문의 ]

남궁 영

한국해양대학교 자연언어처리실험실

young_ng@kmou.ac.kr



## [ 참고 ]

[1] <https://nlp.stanford.edu/projects/glove/>

[2] <http://www.foldl.me/2014/glove-python/>

[3] <https://github.com/hans/glove.py> : for Python2

[4] <https://github.com/maierhofert/glove.py> : for Python3

