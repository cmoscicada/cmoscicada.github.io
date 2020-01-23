---
title: "Projects"
permalink: /projects/
layout: single

toc: true
---

진행했던, 진행하고 있는 프로젝트 정리.

# Python 개발 환경 설정
***

# github.io 블로그 세팅 
***
+ [github.io 블로그 TODO list](/blog/blog-todo)

# TT-Camel: table tennis equipment price tracker
***
용품점마다 웹 크롤링을 통해서 알고 싶은 용품의 가격 추이를 분석. 우선 네이버쇼핑에서 검색을 해서 네이버쇼핑이 크롤링 해놓은 결과를 사용해서 구현해보고, 네이버쇼핑이 커버하지 못하는 부분들을 추가해 나가는 방식으로 시작.

+ 타겟 플랫폼
 + 네이버 스마트스토어
 + 네이버 블로그 스토어
 + 일반 쇼핑몰
 + 카페(네이버,다음): 주로 회원제로 운영되고, 현금장사를 하는 곳들. 제일 크롤하기 어렵지 않을까 생각.

+ 타겟 쇼핑몰들 [탁구닷컴](http://www.tak9.com/shop/main/index.php), [탁구존](https://www.takkuzone.com/), [두보스포츠](http://dbtak.co.kr/), [더블스포츠](https://smartstore.naver.com/doublesports?NaPm=ct%3Dk5q3qykl%7Cci%3Dcheckout%7Ctr%3Dds%7Ctrx%3D%7Chk%3D5b9e46f40513bdfe8cae88dc07fd3663a44e5020), [리베로스포츠](http://www.liberott.com/type6/index/index.htm?NaPm=ct%3Dk5q3rcss%7Cci%3Dcheckout%7Ctr%3Dds%7Ctrx%3D%7Chk%3D8d7612a4726a6218d70ead656fff58ba28931b7d) 

# U-Camel: 중고나라 알리미
***
내가 구매하고 싶은 제품 키워드(이름, 사이즈, 색상 등) 를 입력하면 중고나라 글을 실시간으로 검색해서 알려주는 기능. 텔레그램 봇으로 만들면 더 좋겠다.

# Korail/SRT 예약 Bot
***
크롬 익스텐션으로 사용하고 있던 봇을 더 편하게 바꿔보자.
## 기존 솔루션의 문제점
+ 빈 좌석을 잡으면 바로 결제가 이루어지지 않는다. 빨리 잡히면 별 문제가 없겠지만, 빈 좌석이 잘 나지 않아 오래 매크로를 돌려야 하면 매크로 창을 계속 모니터링 해야한다. 
+ 언제 어디에서나 매크로를 돌릴 수 없다. 익스텐션이 설치된 크롬이 있어야만 매크로를 돌릴 수 있다.

## 해결방안
+ 도커 콘테이너에 매크로 서비스를 올리고 항상 구동되는 컴퓨터에서 실행시킨다. 
+ 계정을 넣어두고 실행 
+ 텔레그램봇으로 인터페이스를 구현하자

## Functions
+ 설정: 날짜/시간대역

## 참고 자료
+ [KTX macro with Telegram push function](https://github.com/youngjin-k/ktx-macro)

# B2B Inquiry Sorter
*** 
친척이 소매/도매업을 하신다. 소매 판매는 네이버 스마트 스토어를 이용하면 체계적으로 진행이 가능하지만 도매 주문은 채널이 중구난방이라, 채널을 통일하고 정돈할 필요가 있다고 한다.

## Functions
+ 카카오톡 메시지를 이용한 주문
 + 카카오챗봇으로 구현 (best)
 + 카카오톡 메시지 텍스트 기반으로 주문 상품을 추출해 낸 후, 반영 (good)
+ 스마트 스토어 재고와 연동
 + 전체 재고를 엑셀에서 처리
 + 스마트 스토어 매출과 도매 매출이 더해져서 한 엑셀파일에서 모두 관리 가능하게 구현


## 참고하면 좋을 것 같은 사이트/자료
+ [도매매](http://domeme.com/index/): 배송대행 B2B 이고 스마트 스토어와 연동이 편하게끔 [엑셀 주문 서비스](http://domemedb.domeggook.com/index/notice/view.php?no=42)를 제공하는 것으로 보인다.

# 스마트 스토어 관리
***
친척이 운영하는 스마트 스토어를 전반적으로 봐달라는 요청이 있어서 요청들을 정리하고 시간이 남을때마다 하나씩 해보려고 한다.

## 참고하면 좋을 것 같은 사이트/자료
+ [상품 업로드](https://blog.naver.com/tripblog/221509453575)