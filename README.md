# 5emotion_KoBert
2022.07 5emotion KoBert 모델 학습

## 요약
- SKTBrain에서 만든 사전 학습된 한국어 맞춤 자연어 처리 모델인 KoBERT를 사용함
- 5가지 감정으로 다중 분류하는 모델로 만들고 만들어 둔 데이터셋으로 학습시킴
- KoBERT 깃허브에 있는 Naver Sentiment Analysis Fine-Tuning with pytorch 코드 활용
  
## 참고 사이트
- SKTBrain/KoBERT : https://github.com/SKTBrain/KoBERT
- KoBERT로 다중분류 모델 만들기: <br/>
https://velog.io/@seolini43/KOBERT%EB%A1%9C-%EB%8B%A4%EC%A4%91-%EB%B6%84%EB%A5%98-%EB%AA%A8%EB%8D%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-%ED%8C%8C%EC%9D%B4%EC%8D%ACColab
- 조기 종료를 이용한 성능 최적화: https://thebook.io/080289/0631/
- pytorch에서 EarlyStop 이용하기: https://quokkas.tistory.com/37
