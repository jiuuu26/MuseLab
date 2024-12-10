<div align="center">
  
# MuseLab
캡스톤디자인과창업프로젝트 스타트 14팀 <br/><br/>

</div>

## 🤖프로젝트명
> AI 이론은 학습했지만 코딩을 할 줄 모르는 비전공자의 AI 교육을 돕기 위한 <br/>
> **노코드 AI 모델 생성기**

## 🌟키워드
① No-coding<br/>
② AI 모델제작<br/>
③ 블록 neural network layer<br/>

## 👩‍💻무엇을 만들고자 하는가
[노코드 기반 AI 모델 생성기]

코딩에 미숙한 비전공자라도, 학습한 이론 지식에 근거하여 블록 기반의 모델을 구축하고, 그러한 모델이 오류가 발생하는 형식으로 설계되지 않도록 가이드를 제시함으로써 보다 **비전공자 친화적인 서비스**를 만들고자 합니다. 생성하는 AI 모델의 범주는 이미지 분류 모델로 한정합니다.

## 🤚고객
[AI 기술을 활용하고 싶은 20-30대 IT 비전공자]

본인의 분야에서 AI 기술을 접목하고자 **이론은 학습했으나, 비전공자이기에 코딩에 미숙한 사람**을 대상으로 합니다. 이들은 학습한 이론에 대한 온전한 이해는 물론이고, 모델 생성이라는 실전적인 적용에 어려움을 겪게 됩니다. 따라서 코드나 오류를 모르더라도 에러가 나지 않게 AI 모델을 직접 생성하고 이론을 적용해보고자 하는 니즈를 가진 이들을 상정했습니다.

## 💁‍♀️기술 시연 Repo
[핵심 요소 기술을 시연한 AI 코드 레포]

아래와 같은 기술을 시연하였습니다. [요소기술 시연 영상 바로가기](https://youtu.be/XEnxanlAJJI)

1. 사용자 친화적인 AI 모델 설계
- 모듈: TensorFlow/Keras
- 데모 시나리오: 
	(1) 사용자는 UI에서 Conv2D 블록을 선택한다.
	(2) 필터 크기, 커널 크기, 활성화 함수 등 매개변수를 설정한 후, 추가적으로 레이어를 통해 모델을 확장한다.
	(3) "코드 생성" 버튼을 누르면 Keras 기반 Python 코드가 자동으로 생성된다.
	(4) 최종적으로 사용자는 생성된 코드를 학습에 바로 활용할 수 있다.

2. GPT API를 활용한 모델 오류 분석 및 수정
 - 모듈: OpenAI GPT-4 API, Python subprocess 및 traceback 모듈
 - 데모 시나리오: 
	(1) 사용자가 만든 모델로 생성한 Keras 코드 실행 중 오류가 발생한다.
	(2) 위에서 생성된 keras 코드를 GPT API로 전송한다.
	(3) GPT는 오류를 분석한 후 수정된 코드를 반환하며, 사용자에게 해결 방법을 제시한다.
	(4) 사용자는 수정된 코드를 UI에서 확인하고 재학습을 실행하며 문제를 해결한다.

3. 학습 결과 기반의 모델 성능 분석 및 튜닝
- 모듈: TensorFlow/Keras History, OpenAI GPT-4 API
- 데모 시나리오: 
	(1) 사용자는 모델 학습을 완료한 후 학습 결과(loss, accuracy 등)를 시각적으로 확인한다.
	(2) 학습 결과로 출력된 정확도 및 손실을 확인하며, GPT API를 통해 성능 개선을 위한 레이어 추가, 하이퍼파라미터 변경, 또는 전처리 옵션 수정 등의 구체적인 제안을 받을 수 있다.
	(3) 사용자는 제안된 내용을 반영하여 모델 구조를 수정하거나 하이퍼파라미터를 조정한다.
 	(4) 수정된 모델을 재학습하여 성능이 개선되었는지 확인한다.
   
