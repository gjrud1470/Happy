# Madcamp Week1 Project
Usage of tabs on android application
Made by 허경 and 이제인 (https://github.com/HelloJaneJane)

홈 탭 + 3개의 탭이 있는 안드로이드 앱 \
(탭 사이 swipe기능은 홈과 그림판에 방해되어 제거됨) \
   (0) Splash : 로딩화면 \
   (1) 홈 (메인) : Happy New Year 배경과 함께 여기저기 폭죽이 터짐. \
   터치함으로써 폭죽을 터트릴 수 있으며, 드래그 밑 홀딩으로 작은 폭죽들을 터트릴 수 있음 \
      가끔 아주 큰 폭죽이 터짐 \
      Particle, Particle Pool 클래스를 직접 구현하였으며 SurfaceView를 이용한 Custom View로 화면에 표시하였음 \
   (2) 연락처 : RecyclerView로 핸드폰에서 가져온 연락처를 보여줌. 연락처에 사진이 있다면, 사진을 표시하며 없다면, 기본 이미지에 랜던한 색깔을 입혀서 보여줌. \
   연락처를 터치하면 그룹을 포함한 자세한 사항을 볼 수 있음. \
   전화버튼과 문자버튼으로 전화를 보내거나 문자앱으로 들어갈 수 있음 \
   (3) 사진첩 : RecyclerView로 사진 보여줌. 기본 이미지 20장 들어있음. 상단 업로드 버튼으로 갤러리에서 원하는 이미지 선택 해 추가 가능. \
   (4) 그림판 : 터치하는 대로 그 점들 사이에 drawLine으로 그림이 그려짐. 펜 색깔 바꾸기, 지우개, undo, reset, 캡쳐 가능. 캡쳐 시 지정된 경로로 그림 파일이 저장되고, 왼쪽 사진첩 탭에 추가됨. \
