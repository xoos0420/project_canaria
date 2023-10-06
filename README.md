## 1. Canaria
<div align="center">
  <img width="80%" height="60%" src="https://github.com/xoos0420/project_dmz/assets/131944211/5991f4a1-c4ef-45e6-9907-2af22a66a7cd"/>
</div>

## 1. Canaria
Canaria는 2022년 8월 14일 부터 8월 31일 까지 개발된 프로젝트입니다.<br>
기존 화재 탐지기와 함께 화재 영상의 Detection과 함께 선제적 알림을 목표로 합니다.<br>

## 2. 프로젝트 내용
<div align="center">
  <img width="80%" height="60%" src="https://github.com/xoos0420/project_dmz/assets/131944211/0085749c-7c48-4669-9923-558c85a5ef4a"/>
</div>
사용자의 폐쇠회로를 표시하는 장치에서 exe로 프로그램을 실행합니다.<br>
불꽃과 연기를 감지하여 정해진 임계값을 넘어서는 확률로 감지될 경우 화재 발생으로 간주합니다.<br>
관리자 또는 관할 소방서에 화재 발생 알림이 전달되로록 하여 신속한 초동 조치가 가능하도록 합니다..<br>

## 3. 활용 데이터 셋
AI HUB 화재 발생 예측 영상<br>
화재 발생 전 발생되는 불꽃과 연기를 촬영한 동영상을 frame으로 나누어 사용<br>
images와 labels로 구분<br>
json -> csv -> text<br>
<br>
화재씬 : fire, smoke(black, white, grey)<br>
유사씬 : cloud, leaf, etc...<br>
무관씬 : non_object<br>
<div align="center">
  <img width="80%" height="80%" src="https://github.com/xoos0420/project_dmz/assets/131944211/bbcf7c50-3147-4362-8262-d9fc0a0ce364"/>
</div>

## 4. 사용 모델
YOLOv5를 사용

## 5. INSTALL

1. [다운로드](https://drive.google.com/file/d/1ZdzsureZVJel8r-7yBuSwnkzArOVhKx2/view?usp=sharing) 클릭 후 폴더안의 run.zip 압축을 해제
2. 그 안의 run.exe 파일을 실행한다.
3. 원하는 영역만큼 왼쪽 위에서 오른쪽 아래로 드래그 하여 cctv화면(동영상의 화면)의 크기에 맞춤
4. 테스트 해볼 영상을 재생하거나 띄움

## 6. 작동
<div align="center">
    <img width="40%" height="20%" src="https://github.com/xoos0420/project_dmz/assets/131944211/945f5ae3-8353-4778-8de2-20440240c21f"/>
</div>
<div align="center">
  <img width="40%" height="20%" src="https://github.com/xoos0420/project_dmz/assets/131944211/9b5a0f00-bb65-4cf2-9eb5-9c6b4d015597"/>
</div>

## 7. STACKS
<div align="center">
  <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">
  <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/pycharm-000000?style=for-the-badge&logo=pycharm&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/fastapi-009608?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <br>
