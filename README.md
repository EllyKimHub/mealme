# ✔ MEALME
### 먹은 음식을 기록하고 기록한 식단을 분석해 전문가에게 상담할 수 있는 공간
식단 기록, 관리, 컨설팅, 상품 구매까지 한번에 이용할 수 있는 사이트
  
</br>
</br>

# ✔ 개발 기간
### 2023.06.24 ~ 2023.07.24  
</br>
</br>

# ✔ 팀 구성 
| 구성  | 6인  |  작업 목록  |
| :---: | :---: | :---: |
| 팀장 | 이재우 | 회원가입, 로그인, 식단 작성, 작성 리스트 |
| 부팀장 | 이동재 | 관리자 |
| **팀원** | **김예슬** | **오늘 하루, 차트(일간,주간,월간), 리뷰(식단상담, 상품구매)** |
| 팀원 | 유정현 | 상담 |
| 팀원 | 정연재 | 전문가 선택 |  
  
</br>
</br>
  
# ✔ Stacks (SpringBoot Project) 
|   |   |
| :--- | :--- |
| 💻 IDE | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)  ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)  |  
| 📋 Language | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  |
| ⚙️ Framework | ![SpringBoot](https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=for-the-badge&logo=SpringBoot&logoColor=white)  ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo={MyBatis}&logoColor={black}) |
| 📚 Library | ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) |
| 💾 Database | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) |
| 🗄️ Server | ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black) |  
| 📤 Version Control | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) |
  
</br>
</br>

# 작업 목록
  - ### ✨오늘 하루 [🔗코드 보기](https://github.com/EllyKimHub/mealme/wiki/%F0%9F%93%86-%EC%98%A4%EB%8A%98-%ED%95%98%EB%A3%A8)
1. 회원 정보에 등록된 키, 몸무게, 나이에 따라 칼로리, 탄수화물, 단백질, 지방 섭취량 계산해 추천하기
2. 추천 칼로리, 탄수화물, 단백질, 지방 섭취량 사용자가 확인하기 유용하게 추천 섭취량과 실제 섭취량 차트로 비교해서 보여주기
3. 식사 코드에 따라 아침, 점심, 저녁, 간식의 합산 값 계산하기
4. 날짜 API인 date-picker를 사용해 기본 설정은 오늘로 보여주고 날짜를 이동하면 해당 날짜에 대한 식단의 사진과 섭취영양소 합산 차트 보여주기
5. 3대 영양소인 탄수화물, 단백질, 지방을 섭취 칼로리에 따라 비율 계산하기
6. chart.js를 사용해 하루 동안 등록한 식단의 영양성분 데이터 시각화 해 보여주기
7. 사진 탭 누르면 해당 날짜에 대해 기록한 식단의 사진 보여주기
8. 사진을 누르면 식단의 음식 이름, 사진, 칼로리 보여주기 
  - ### ✨차트 (일간, 주간, 월간) [🔗코드 보기](https://github.com/EllyKimHub/mealme/wiki/%F0%9F%93%8A-%EC%B0%A8%ED%8A%B8(%EC%9D%BC%EA%B0%84,-%EC%A3%BC%EA%B0%84,-%EC%9B%94%EA%B0%84))
1. 해당 기간 동안 섭취한 탄수화물, 단백질, 지방의 '섭취 g'을 하루 단위로 평균 값을 내어 차트를 통해 시각화
2. 해당 기간 동안 섭취한 하루 평균 '칼로리에 따른 3대 영양소의 비율'을 차트를 통해 시각화 
3. 해당 기간 동안 섭취한 하루 평균 칼로리
4. 해당 기간 동안 섭취한 하루 평균 칼로리에 따른 3대 영양소의 비율에 따라 퍼센트를 숫자로 비교
5. 해당 기간 동안 섭취한 하루의 평균 탄수화물, 단백질, 지방의 섭취 g을 추천하는 섭취g과 비교해 과다, 과소 영양소를 확인할 수 있도록 함
6. 해당 기간 동안 섭취한 하루 평균 영양성분 데이터를 시각화 
  - ### 리뷰 작성 (식단상담, 상품구매) [🔗코드 보기](https://github.com/EllyKimHub/mealme/wiki/%E2%AD%90-%EB%A6%AC%EB%B7%B0-(%EC%8B%9D%EB%8B%A8%EC%83%81%EB%8B%B4,-%EC%83%81%ED%92%88%EA%B5%AC%EB%A7%A4))
1. 컨설팅, 쇼핑몰 주문내역 받아오기, 페이지 이동처리
2. 주문 번호로 리뷰 작성하기 (별점 주기)
3. 리뷰 내역 받아오기, 페이지 이동처리(비동기)
4. 리뷰 번호로 리뷰 수정하기

</br>
</br>

# 구현 화면
|  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: |
| 오늘 하루 | ![오늘 차트m](https://github.com/EllyKimHub/mealme/assets/123884116/b386581a-1546-417b-b631-91bad2d05006) | ![오늘 하루 데이트 피커mm](https://github.com/EllyKimHub/mealme/assets/123884116/52b70a6e-af1e-4546-ae38-4dced54f8cb8) | ![오늘 사진m](https://github.com/EllyKimHub/mealme/assets/123884116/7c4f424e-5b85-4949-ba28-73ce339d67a2) | ![오늘하루mm](https://github.com/EllyKimHub/mealme/assets/123884116/464e9ca1-198d-4a6c-974d-d9febccde2e2) |
| 차트 | ![일간m](https://github.com/EllyKimHub/mealme/assets/123884116/74c6cd83-1489-4acb-86b7-a92d604f5279) 일간 | ![주간m](https://github.com/EllyKimHub/mealme/assets/123884116/dc3cbd2e-0231-4f10-90da-29318e10d3d4) 주간 | ![월간m](https://github.com/EllyKimHub/mealme/assets/123884116/1518c44c-ccf6-47e7-a0ef-2c576e6f76ad) 월간 |  |
| 리뷰 | ![상품 구매 내역m](https://github.com/EllyKimHub/mealme/assets/123884116/5f0084a8-582b-41e4-a41e-c2702f0c4294) | ![상품 리뷰 등록m](https://github.com/EllyKimHub/mealme/assets/123884116/5be78b35-4195-496c-ac51-37f3c8e525d5) | ![상품 리뷰내역m](https://github.com/EllyKimHub/mealme/assets/123884116/812f4e1a-bf24-4d2b-b4e3-78a916c0a0ba) | ![상품 리뷰 수정m](https://github.com/EllyKimHub/mealme/assets/123884116/d730bff3-b696-4fdd-ac81-09141746cde4) |

