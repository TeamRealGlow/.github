# <img src="img/ico_clbg.png" width="30" height="30"> Project RealGlow 

<div style="text-align: center;">
    <a href="playstore 링크">
        <img src="img/MZTOX.png" />
    </a>
</div>

## 1. 프로젝트 소개

생필품, 가전제품 등은 온라인으로 구매하는데 화장품을 온라인으로 살 순 없을까? 라는 물음에서 시작된 우리의 프로젝트는 
RealGlow 어플리케이션을 이용해 소비자들은 제품의 실제 효과를 시각적으로 확인하고 온라인상에서도 자신에게 가장 적합한 제품을 선택해 구매 링크를 제공하는 쇼핑 도우미 프로젝트 입니다.
<br>
[사용방법](#6-데모-사이트)

## 2. 팀원 소개 
| 이름     | 소속                                | 역할                  | 기술 스택                                                                                                                                                             | 소개                                           | 
|:---------|:-------------------------------------|:---------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------|
| 강병준   | 한국 폴리텍 대학 <br> 서울정수캠퍼스 <br> 인공지능소프트웨어과 <br> 교수 | 지도교수             |                                                                                                                                                                    | 지도 교수님                           |
| 조원우   | HD한국조선해양   | 멘토             |                                                                                                                                                                    | 프로젝트 총괄 멘토링                         |
| 유승호   | 한국 폴리텍 대학 <br> 서울정수캠퍼스 <br> 인공지능소프트웨어과 <br> 2학년 | 팀장<br>인공지능 백엔드 서버 구축 <br> 인공지능 모델학습 <br> 컴퓨터 시연용 GUI 작성              | ![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white) <br> ![Flask](https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white) <br> ![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) <br> ![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white) <br> ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) | 프로젝트 총괄 담당 <br> 인공지능 서버 구축 <br> 인공지능 모델 구축 <br> 화장 알고리즘 작성 <br> AWS EC2 기반 서버 구축 |
| 박명연   | 한국 폴리텍 대학 <br> 서울정수캠퍼스 <br> 인공지능소프트웨어과 <br> 2학년 | 프론트엔드 앱 개발자  | ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white) <br> ![Kotlin](https://img.shields.io/badge/Kotlin-7F52B9?style=flat-square&logo=kotlin&logoColor=white) | 앱 어플리케이션 제작 <br> 앱 어플리케이션 UI  제작                       |
| 이은송   | 한국 폴리텍 대학 <br> 서울정수캠퍼스 <br> 인공지능소프트웨어과 <br> 2학년 | 프론트엔드 앱 개발자  | ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white) <br> ![Kotlin](https://img.shields.io/badge/Kotlin-7F52B9?style=flat-square&logo=kotlin&logoColor=white) | 앱 어플리케이션 제작  <br>  앱 어플리케이션 UI  제작           |


## 3. 개요
- **프로젝트 이름**: RealGlow 
- **프로젝트 지속 기간**: 2024.04.01 ~ 2024.10.22
- **서버 제공**: ![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
- **OS**: ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
- **개발 언어**: ![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52B9?style=flat-square&logo=kotlin&logoColor=white) 
- **개발 프레임워크**: ![Flask](https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white) ![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)
- **서버**: ![Gunicorn](https://img.shields.io/badge/Gunicorn-5996D6?style=flat-square&logo=gunicorn&logoColor=white)

## 4. 구현 일정
### 1 차시
| 구분   | 추진 내용                                          | 1주 | 2주 | 3주 | 4주 | 5주 | 6주 | 7주 | 8주 | 9주 | 10주 | 11주 | 12주 | 13주 | 14주 | 15주 | 16주 |
|--------|----------------------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| 팀 구성   | 팀 구성 |                                 ■  |   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| 주제선정   | 주제선정       |                                   |■   |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
| 기획   | 요구사항 분석 및 UML 도출 |                                   | ■  |  ■   |   ■  |     |     |     |     |     |     |     |     |     |     |     |     |
| 기술분석   | 관련기술 분석 |                                   |   |     |  ■   |  ■   |     |     |     |     |     |     |     |     |     |     |     |
| 1차 발표   | 1차 발표 |                                   |   |     |     |     |     |   ■  |  ■   |     |     |     |     |     |     |     |     |
| 모델 개발 | 웹 호스팅 및 디버깅         |                                   |   |     |     |    U I  | 제    | 작    |     |     | 앱    | 개발    |  및   |  모델   |  포팅   |     |     |
| 2차 발표 | 2차 발표         |                                   |   |     |     |     |     |     |     |     |     |     |     |     |     |  2차   |  발표   |


### 2 차시
| 구분   | 추진 내용                      | 1주 | 2주 | 3주 | 4주 | 5주 | 6주 | 7주 | 8주 |9주 |10주 |11주 |
|--------|-------------------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| 앱 개발   | 앱 개발 및 모델 포팅 |            ■ | ■  |   ■ |     |     |     |     |     |     |
| 모델 개선   | 모델 개선      |    ■ | ■   | ■   |  ■   |   |     |     |     |     |
| 서버 구축   | AWS를 이용한 Flask 서버구축 |                         |     |     |    | ■   |   ■  |  ■   |     |     |
| 테스트   | 단위 테스트, 통합 테스트 |                              |     |     |    |    |     |  단위 <br> 테스트   |   통합 <br> 테스트   |    |
| 발표 | 최종 발표        |                                  |     |     |     |     |    |    |    |    |   | ■ |


## 5. 구현 핵심 기술
### AI 서버
- Instance Segmentation <br> Bisnet 를 통한 Segmentation 을 통해 얼굴을 인식하고 얼굴 부위 분할을 통해 얼굴 데이터를 얻습니다.
- Image-Prop

### 안드로이드 프론트 앱



<!-- ### 학습 데이터 구축 및 가공

- 국립국어원 우리말샘 사전 및 AI-Hub 연령대별 특징적 발화(은어·속어) 음성데이터의 사전 데이터, 2023~2024년 신조어 수집으로 학습데이터 구축

- Python, Pandas를 이용한 데이터 전처리

- PySide를 이용한 라벨링 프로그램 AnnoText 제작

- AnnoText를 이용한 학습데이터 라벨링 -->

## 6. 데모 사이트
<!-- 우리가 만든 애플리케이션을 직접 체험해 보세요!

[**데모 사이트 방문하기**](http://mztox.aikopo.net/) (2024.08.22 까지 운영 예정)


[**로그인 없이 사용시**]

![데모 사이트](img/demo_unlogin.gif)



[**로그인 후 사용시**]

![데모 사이트](img/demo_login.gif) -->

## 7. 업데이트 내역

## 8. 후기
- 추후 작성 예정

## 9. Reference
- 추후 작성 예정