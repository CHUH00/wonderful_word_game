# Wonderful Word Game

## 📊 사용한 데이터셋
- `한국어_단발성_대화_데이터셋.xlsx`  
- 한국어 단발성 대화(질문–응답 형태)의 문장을 포함한 엑셀 파일  
- 게임에 사용되는 단어/문장을 이 데이터셋에서 불러와 활용

---

## 🔑 대응 기준
- 데이터셋에서 불러온 **질문 → 응답** 구조를 기반으로 게임 로직 구성  
- 예시:
  - 질문 문장을 **문제(제시어)**로 제시  
  - 올바른 응답을 맞히면 정답 처리  
- 대응 방식은 **데이터셋 컬럼 간 1:1 매칭**으로 진행

---

## 🖼️ 실행 결과 화면
<img width="1110" height="348" alt="image" src="https://github.com/user-attachments/assets/aaeffdb6-200c-43a7-9414-fa5ec23a9140" />
![전처리 전](images/start.png)
*전처리 전*

![전처리 후](images/start.png)
*전처리 후*

![단어 유사도 확인](images/start.png)
*단어 유사도 확인*

![게임 화면](images/start.png)
*게임 화면*
