# webcrawling.py는 selenium을 사용하여 웹크롤링을 하기
1. 구글 혹은 네이버에서 alt 속성을 통해 관련 키워드를 가진 이미지를 찾는다.
2. 가지고 있는 이미지에서 중복 된 이미지를 제거
3. 제거되고 남은 이미지를 다운 받는다.
4. 다운 받은 이미지를 같은 사이즈로 리사이즈 한다.

# chromedriver를 크롬 버전에 맞게 설치한 후 같은 디렉토리 안에 넣어줘야 한다



# download_img.py 는 webcrawling의 클래스와 request를 이용하여 이미지를 다운 받는 스크립트입니다