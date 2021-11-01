# OCT-Segmentation  
## 메인화면
![image](https://user-images.githubusercontent.com/93498639/139611092-434c0266-9b6c-4d1c-8936-84a5cc3cd3e2.png)
## 결과화면
![image](https://user-images.githubusercontent.com/93498639/139611039-7c54c98f-7923-45bb-9a6f-d783889b876c.png)

## Unet + Keras_flask_deploy_web_app이 합쳐진 모듈

참고링크1 : https://github.com/zhixuhao/unet  
참고링크2 : https://github.com/mtobeiyf/keras-flask-deploy-webapp

# 01. 사용법

## 1.1) 가상환경 로드  

	#conda activate keras_flask

## 1.2) 코드실행

	#python app.py


# 02. 핵심소스코드  
## 2.1) Python  
app.py : 훈련된 모델 호출 및 Segmentation 수행하는 코드  
data.py : Segmentation 함수가 포함된 코드  
model.py : AI 모델 코드  
## 2.2) Javascript
main.js : 웹 상의 이미지 로드 등 함수가 포함된 코드  
## 2.3) HTML
index.html : 프론트엔드 페이지 코드  

