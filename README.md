# KakaoBot

## Rest API
### 1. 내 애플리케이션 -> 제품 설정 -> 카카오 로그인

활성화 설정 및 Redirect URI 등록: https://blahblah.com


### 2. "https://kauth.kakao.com" + "/oauth/authorize?client_id={REST_API_KEY}&redirect_uri={REDIRECT_URI}&response_type=code"

위 링크에 REST API 키와 REDIRECT URI 대입 


### 3. 2번에 따라 연결된 링크의 code 뒷부분이 Access Token
다음 코드에 따라 access token 과 refresh 토큰을 추출함


### 4. 
