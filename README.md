# fleact - Flask & React.js

Make Full Stack Web Application on Flask & RCA template
 
1. 프론트엔드 작업

 (1) cd react-app  
 (2) npm run start
 - http://localhost:3000 접속
 - hot-reloading 기능 유지, 화면 개발에만 집중 가능
 - 기존 create-react-app 템플릿을 통한 화면 개발 플로우와 동일하게
 
 
2. Flask 서버 연동

 (1) cd react-app  
 (2) npm run build 
 (3) cd ../server  
 (4) python main.py (혹은 python3 main.py)
 - http://0.0.0.0:8080 접속
 - react 빌드 모듈은 server/build 에 생성됨
 - Flask static folder 는 기본적으로 server/build 로 설정
 
 
