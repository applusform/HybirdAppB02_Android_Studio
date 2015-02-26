* 프로젝트 구성

- 시작 페이지 : /assets/moml/ui/main.xml 의 WEBVIEW.homePage 를 변경하십시오.

- 시작 로고 이미지 : /assets/moml/ui/logo.png 파일을 수정하거나 교체하십시오.

- 앱 이름 : 
  한국어 : /res/values-ko/strings.xml 에서 name 이 app_name인 string 태그 사이를 수정하십시오.
  영어 :  /res/values/strings.xml 에서 name 이 app_name인 string 태그 사이를 수정하십시오.
 
- 앱 아이콘: 해상도별로 아래 파일을 수정하거나 교체하십시오.
  /res/drawable-hdpi/ic_launcher.png : 72x72
  /res/drawable-ldpi/ic_launcher.png : 36x36
  /res/drawable-mdpi/ic_launcher.png : 48x48
  /res/drawable-xhdpi/ic_launcher.png : 96x96
  /res/drawable-xxhdpi/ic_launcher.png : 144x144
  

!!! 주의 사항  !!!

- 본 프로젝트는 안드로이드 용으로 개발된 단순한 웹앱 형태의 하이브리드앱입니다.
  iOS AppStore에 등록하기 위해서는 추가적인 MOML UI의 구현이나 Native 구현이 필요합니다. 

- 디지탈 카메라로 촬영한 이미지는 반드시 크기를 줄여서 사용하십시오. (1080x1920 이하 권장) 
      너무 큰 이미지를 사용하면 저사양의 폰에서는 느려지거나 올바로 동작하지 않을 수 있습니다. 

- 파일이름에 한글은 사용할 수 없습니다.


* 이용 안내

- 본 프로젝트는 Applusform 서비스에 포함된 템플릿의 일부로 원본 그대로 자유롭게 배포가 가능합니다.

- 수정한 프로젝트나 개발한 앱을 제 3자에게 배포하는 경우 Applusform.com의 서비스 이용약관에 동의하는 것으로 간주합니다.
