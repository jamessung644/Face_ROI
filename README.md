# Face_ROI

## 객체 추적을 위한 MeanShift 알고리즘

이 프로젝트는 OpenCV를 사용하여 웹캠에서 객체를 추적하는 간단한 예제입니다. MeanShift 알고리즘을 사용하여 초기 프레임에서 관심 영역(ROI)를 선택하고, 

그 영역을 추적하여 웹캠 스트림 상의 객체를 계속해서 따라다니는 예제입니다.

### 사용법

#### 1. 필수 라이브러리 설치:
이 프로젝트를 실행하려면 OpenCV를 설치해야 합니다. 아래 명령어를 사용하여 OpenCV를 설치하세요.
```
pip install opencv-python
```
#### 2. 프로그램 실행:
이 예제를 실행하려면 다음 단계를 따르세요.

#### 3. 종료:
프로그램을 실행한 후, 객체 추적 중에 ESC 키를 누르면 프로그램이 종료됩니다.

### 알고리즘

이 프로젝트는 다음과 같은 단계로 객체 추적을 수행합니다.

웹캠에서 비디오 스트림을 시작합니다.
첫 번째 프레임에서 ROI(Region of Interest)를 선택합니다.
선택한 ROI를 사용하여 MeanShift 알고리즘을 초기화합니다.
MeanShift를 사용하여 객체를 추적합니다.
추적 중에 ESC 키를 누르면 프로그램이 종료됩니다.

