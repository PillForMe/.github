# PillForMe 

![첫화면](https://github.com/user-attachments/assets/b60f46a5-6307-4bcb-b15e-eb3d354e8ffa)

"Pill for Me"는 개인 맞춤형 영양제 조합 추천 서비스입니다.  
사용자가 성별, 연령, 건강 고민 및 기존에 섭취 중인 영양제 정보를 사진으로 입력하면,  
OCR과 GA(Genetic Algorithm) 기반 최적화 기법을 활용하여 맞춤형 영양제 조합을 도출합니다.  

이후, 유저가 원하는 효능 정보에 대한 우선순위를 토너먼트 형식으로 정하는 동안 
사용자 영양제 구매 추정 그래프 데이터를 반영하여 LLM을 Finetuning한 GLRec 모델을 통해 유저의 구매 의향 정도를 추론합니다.

결론적으로 OCR과 GA를 통해 도출된 맞춤형 영양제 조합들 중
유저가 원하는 효능 정보와 GLRec를 통해 추론된 유저의 구매 의향 정도를 반영해 우선순위를 매겨
최적의 Top 3 영양제 조합을 추천합니다.

[GLRec는 다음 코드 베이스를 활용했습니다 : GLRec Official GitHub Repository](https://github.com/WLiK/GLRec)

![아키텍처](https://github.com/user-attachments/assets/eb557a70-e7f9-48bf-82d4-08c1074f410c)
<br/>

### ✨ 발표 자료 링크
https://www.slideshare.net/slideshow/20-boaz-19-boaz-pill-az-pill-for-me/270919517
<br/>

### 📽️ 발표 및 시연 영상  
[![영상 재생](https://img.youtube.com/vi/-ulZOF3TM_0/0.jpg)](https://www.youtube.com/watch?v=-ulZOF3TM_0)  
<br/>  


