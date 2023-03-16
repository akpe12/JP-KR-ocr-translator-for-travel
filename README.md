# JP-KR OCR translator(for travel)
일본 여행 시에 쓰일 수 있도록 학습된 일한 이미지 번역기입니다. 코로나 바이러스에 대한 방역 지침이 완화되면서 해외 여행을 하는 여행객들이 증가하고 있는 추세입니다. 그 중에서도, 일본은 한국인이 가장 많이 방문하는 해외 여행지 1순위였습니다. 해외 여행을 하다보면 대중교통이나 식당 등에서 언어의 장벽을 느끼게 되는 경우가 발생합니다. 이럴 때, 이미지 번역기를 사용하지만 성능에 아쉬움을 겪곤 했습니다. 이러한 아쉬움을 해소하고 싶었고, 한국의 여행객들이 언어의 장벽을 느끼지 않는 여행을 할 수 있도록 돕고자 일본 여행에 특화된 일한 이미지 번역 모델을 만들게 되었습니다.

<img width="617" alt="스크린샷 2023-03-16 오후 8 03 51" src="https://user-images.githubusercontent.com/77143331/225598211-5a6a9fde-faed-4d8b-9c57-41f9027a15f1.png">
사진 출처: https://www.ytn.co.kr/_ln/0103_202301311118041696

# 일한 이미지 번역기
<a href='https://www.youtube.com/watch?v=pfFJb5qGbL8' target='_blank'> 모델 시연 영상 </a>
<a href='https://www.youtube.com/watch?v=pfFJb5qGbL8'> <img src="https://user-images.githubusercontent.com/77143331/225528850-d2a75fa6-7baf-49d4-8208-f55ab55beaa6.png"> </a>

# 성능 평가
- 평가 방법: BLUE score(1-gram)
<img width="935" alt="스크린샷 2023-03-16 오후 3 57 54" src="https://user-images.githubusercontent.com/77143331/225591180-8b90d645-6c1b-48f1-8770-54dbc90effae.png">
- 테스트 데이터(400개)
<img width="575" alt="스크린샷 2023-03-16 오후 7 41 10" src="https://user-images.githubusercontent.com/77143331/225592661-c2133a23-f4ba-4936-93e0-af6423c925d0.png">
