# Mathematical-Explorations
한양대학교 ERICA 캠퍼스 수리데이터사이언스학과 1학년 1학기(2023) 수학탐험 실습 코드입니다. 코드는 Google Colab으로 작성했습니다. 

코드 한줄한줄 완벽히 이해하지 않아도 괜찮습니다! 수업 중 배우는 개념들이 이런 식으로 활용되는구나 정도 감만 잡는 용도입니다!!

궁금한 점 있으시면 alsh02@hanyang.ac.kr 로 문의해주세요.

## Python 문법 기초 🖥️
다음 링크를 참고하시기 바랍니다. (위 코드를 이해하는데 이 정도 문법이면 충분합니다 😀)

https://wikidocs.net/book/2

## 설치해야하는 라이브러리 🔥
아래 라이브러리를 설치해야 수업을 원활하게 진행할 수 있습니다.
```matplotlib : 시각화 라이브러리
numpy   : 수치 계산 라이브러리
pandas  : 데이터 분석 라이브러리
csv     : 엑셀파일을 읽어오는 라이브러리
librosa : 음원 데이터 분석 라이브러리
scipy   : 과학기술계산 라이브러리
pillow  : 이미지 처리 라이브러리
```

* 설치 방법

Windows의 경우 ```cmd``` , MacOS의 경우 ```terminal``` 을 연 뒤 아래 명령어를 입력하세요.
```python
# 로컬에 설치하는 경우
pip install matplotlib
pip install numpy
pip install pandas
pip install csv
pip install librosa
pip install scipy
pip install pillow

# Anaconda로 설치하는 경우
# conda activate [생성한 가상환경 이름]을 먼저 입력한 뒤 아래 명령어를 입력하세요.
# Anaconda도 pip를 통해 설치할 수 있지만, 
# 아래 명령어로 설치할 때 오류가 나지 않는다면 conda로 설치하는 걸 권장합니다.
conda install matplotlib
conda install numpy
conda install pandas
conda install csv
conda install librosa
conda install scipy
conda install pillow
```

## Google Colab 사용해보기 📝
Colab은 Google에서 제공하는 클라우드 기반 대화형 Python 스크립트 메모장입니다. 우리의 컴퓨팅 자원을 사용하는 것이 아니라 Google의 클라우드를 이용하는 것이기 때문에 컴퓨터 성능이 부족하더라도 머신러닝이나 딥러닝 연산을 수월하게 수행할 수 있습니다.

아래 링크로 접속해서

https://colab.research.google.com/?hl=ko


```파일 > 새 노트``` 를 클릭하여 아래 코드를 작성해봅시다.

```
print("Hello World!")
```
![스크린샷 2023-02-26 오후 9 24 24](https://user-images.githubusercontent.com/48062593/221410361-f741814f-83d2-4c8f-a6c7-ef069b333b2d.png)

코드 옆 실행 버튼을 누르거나 ```cmd⌘ + enter(ctrl + enter)``` 를 눌러서 실행결과를 확인합니다.

새로운 코드 쉘을 추가하려면 위의 ```+코드``` 를 누르거나 ```cmd⌘ + M, B(ctrl + M, B)``` 를 누르세요.


## ChatGPT 다뤄보기 😀
1. 링크로 들어갑니다. https://openai.com/blog/chatgpt/
2. 계정을 만들어 로그인하고 여러가지 질문을 해봅시다.(넌 누구야, 삼성전자 주식이 어떻게 될 거 같아 등등...)
