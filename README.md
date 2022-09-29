# Prepare
깃허브, dacon 좋은 코드를 정리해놓았습니다. 괜찮은 자료가 있다면 언제든 PR하면됩니다. 그리고 설명이 부족하다면 issue 남기면 추가하겠습니다. 

[issue 예시](https://github.com/AI-in-DIDC/Prepare/issues/1)


## 깃허브 사용법
[Pull Request](https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/)
```
Pull Request(PR)로 작성한 코드를 올린다. 그러면 각자 코드를 보고 리뷰를 남기거나 그냥 그 코드 가져와서 학습해보면된다.
```
## 자료 및 코드

### 자료
* [pytorch tutorial](https://tutorials.pytorch.kr/beginner/basics/intro.html)
```
pytorch는 딥러닝 프레임워크이다. 딥러닝 할때 필요한 optimizer, model, train 등 손쉽게 가져오고 만들 수 있다. 
전부 읽기보다는 [파이토치 기본 익히기](https://tutorials.pytorch.kr/beginner/basics/intro.html)에서 
[7.모델 저장하고 불러오기](https://tutorials.pytorch.kr/beginner/basics/saveloadrun_tutorial.html)
까지 보면 된다.
거의 전부 다 사용하기에 꼭 알아야한다.
```
* [다양한 learning rate scheduler](https://dacon.io/competitions/official/235697/codeshare/2373?page=1&dtype=recent)
```
자주 쓰이는 scheduler를 정리해놓았다. matplotlib으로 그래프로 잘 설명되어있다. 
댓글에서 글쓴이가 사용하는 schduler와 왜 쓰는지도 보면 좋다.
```

### 코드

* [간단한 이미지 학습](https://dacon.io/competitions/official/235870/codeshare/4171?page=3&dtype=recent)
```
colab환경이자 깔끔하게 필요한 코드로만 학습을 진행한다.(vision 한정)
```
* [EDA 관련 자료](https://dacon.io/competitions/official/235870/codeshare/4213?page=1&dtype=recent)
```
주어진 데이터를 활용해 분석을 많이함. Vision데이터에서 뭐가 부족하고 있는지 분석. 
이미지에 box를 쳐서 어느 부분이 문제가 있는지 보여주고 어떤 작물에 병이 많은지 없는지를 잘 분석했다.
```
* [NLP](https://dacon.io/competitions/official/235717/codeshare/2674?page=1&dtype=recent)
```
로그 기록을 보고 보안 위험도 분석하는 대회. 
주목할 부분으로 중복된 값 제거, 필요없는 텍스트 제거, oversampling 등이 있다.
특히 oversampling은 vision에도 쓰인다. 필요없는 텍스트 제거, 중복된 값 제거는 NLP에서 많이 쓰이는 기법이다. 
유심하게 보면 좋다.
```

* [SAM optimizaer](https://dacon.io/competitions/official/235697/codeshare/2370?page=2&dtype=recent)
```
현재 글 필자가 많이 쓰는 optimizer인데 설명도 좋고 optimizer의 문제도 잘 지적되어 있다.
```

* [augmentation](https://dacon.io/competitions/official/235697/codeshare/2360?page=3&dtype=recent)
```
우리는 albumentation을 사용 안하지만 우리가 쓰게될 기법들이 있다. 
간단히 보면서 '이런 기법이고 이미지가 이렇게 되는구나'보면 된다.(vision 한정)
```
* [TTA](https://dacon.io/competitions/official/235697/codeshare/2361?page=3&dtype=recent)
```
inference때 사용 할 확률이 높다. TTA에 관한 설명이 자세히 설명되어 있어서 좋다.(vision 한정)
```

* [인원 예측 AI](https://dacon.io/competitions/official/235743/codeshare/2983?page=1&dtype=recent)

```
인원 예측하는 대회이다. 데이터 전처리와 모델을 돌리는 코드까지 자세히 나와있어서 배우기 좋다.
```

* [임베딩](https://dacon.io/competitions/official/235743/codeshare/2817?page=2&dtype=recent)

```
데이터셋을 활용하여 새로운 모델 입력값을 만든다. 데이터 전처리로 좋은 코드이다.
```

* [주차수요 예측 AI](https://dacon.io/competitions/official/235745/codeshare/3015?page=1&dtype=recent)
```
위 인원 예측 AI와 비슷한 코드다.
```

* [문서요약 AI](https://dacon.io/competitions/official/235829/codeshare/4047?page=1&dtype=recent)
```
kobert라는 모델을 쓴다. 원래 Bert 모델 한국어 버전으로 konlpy 같은 라이브러리 숙지가 매우 중요하다. 특정 모델과 데이터 전처리를 통해 좋은 예측 결과를 가져올 수 있다.
```

* [태양광 발전량 예측 AI](https://dacon.io/competitions/official/235680/codeshare/2033?page=1&dtype=recent)
```
위에 인원 예측하는 코드와 비슷하지만 좀더 정돈되어있고 기본적인 코드라 우선 이 코드를 참고해서 감을 잡으면 좋다.
```
