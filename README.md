# **capstone_musicgen**
## **텍스트 데이터를 활용한 컨텐츠 BGM제작 : Meta의 MusicGen을 이용하여**

## **목차**

<b> 

-📝[배경&목표](### 1.캡스톤디자인의 배경과 목표)
  
### 1.캡스톤디자인의 배경과 목표
##### *배경*
-  글로벌 오디오북 시장 규모의 성장과 웹툰에 OST가 제작되는 등, 다양한 컨텐츠에서 청각 요소의 비중이 높아지고 있음.
  
##### *목표*
- 다양한 컨텐츠에서 청각 요소를 적절히 활용할 경우 작품의 몰입도를 높이고, 새로운 홍보효과도 기대할 수 있음
- 소설, 블로그, 게임 시나리오, 독립영화대본 등 스토리와 감정이 존재하는 텍스트에서 음악적 요소를 추출하여 맞품형 컨텐츠 BGM을 생성하고자함.


### 2.프로젝트 주요 내용
결과적으로 음악을 생성하는 것은 생성형 AI인 Meta의 MusricGen을 사용하며 MusicGen이 해당 텍스트에 어울리는 음악을 생성할 수 있도록 텍스트에서 요약, 감정, 음악적 요소 등을 추출하는 모델을 제작

### 3. 사용된 기술 및 도구
##### python(pandas, matplotlib, pyplot)
- 수집한 데이터의 전처리 및 시각화
##### BERT
- 감정을 추출하는 모델
- 악기를 추출하는 모델
- 장르를 추출하는 모델

##### ChatGpt
- 텍스트를 추상적으로 요약하는 데 사용

##### MusicGen
- 최종적으로 음악을 생성하는 데 사용

##### 솔트룩스 감정분석기
- 감정을 할 때 사용
- 최종에는 사용되지 않음

##### Google GoEmotions
- 감정 분석에 사용
- 최종에는 사용되지 않음

### 4.프로젝트 결과 및 성과
음악은 창작의 영역이기 때문에 좋다,나쁘다 또는 분위기에 어울린다,어울리지 않는다는 개인적인 생각이 많이 반영되며 이는 수치로 표현하거나 정확도로 표현하는것에는 많은 한계가 존재하여 정량적인 측정방식 대신 정성적인 지표를 통해 프로젝트 결과를 기술

1. 설문조사
   - 총 94명(남 47명/ 여 47명)을 대상으로 설문조사
   - 6개의 샘플을 2가지 유형으로 나누어 제시
       유형 1)원본 영상에서 음원을 분리 후, 샘플을 삽입하여 새롭게 만든 영상 제공
       유형 2)원본 텍스트와 샘플을 제공
   - 긍정 65% 부정 13%
  
2. 인터뷰
   - 독립영화 현장에서 활동하는 현업자 인터뷰
   - 어울리지 않는 지점도 존재하나 기술적인 문제가 보완된다면 프로젝트 자체는 긍정적으로 생각함
   - 비용적인 문제와 시간적인 문제를 해결하는 것이 가장 강점이라고 여겨짐

### 5.결론 및 평가
 - 텍스트에서 음악적 요소를 추출하고 생성형 AI와 결합하여 맞춤형 컨텐츠 BGM을 제작하였으며, 설문조사와 인터뷰를 통해 긍정적인 반응을 얻었음.
 - 경험 부족으로 인해 데이터의 일관성/객관성을 지킬 수 있는 명확한 데이터 수집 기준을 세우지 못한 채 수집을 시작함
 - 모델 구축을 위한 노력에 비해 쓰지 못하는 것과 원하는 성능이 나오지 않아 아쉬움이 존재
 - 좋은 데이터를 생성하기 위해 고려해야할 점이 많다는 사실을 실감하였음

