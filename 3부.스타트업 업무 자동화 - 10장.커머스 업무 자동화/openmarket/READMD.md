# Open Market자동화

## Overview

### 개발 리스트

  1. 복수 오픈마켓 주문정보 수집하여 메일로 알림
  2. 복수 오픈마켓 재고정보 수집하여 메일로 알림
  3. 복수 오픈마켓 부가세 신고자료 취합하여 엑셀로 정리

### Open Market List

- 지마켓 (http://www.gmarket.co.kr)
- 옥션 (http://www.auction.co.kr/
- 11번가 (https://www.11st.co.kr/html/main.html)
- 스마트스토어 (https://sell.smartstore.naver.com)

## 1. 복수 오픈마켓 주문정보 수집하여 메일로 알림

### REST API 미사용 버전

#### <공통> (각 사이트마다)

0. 각 OpenMarket 점검 시간인지 checking
1. 로그인 페이지 접속
2. 로그인 시도
3. 주문정보 확인 사이트로 이동
4. 주문정보 확인 필터링 걸기
5. 엑셀 다운로드 or crawling
6. 데이터 가공(엑셀 합치기 or HTML 만들기)
7. 메일 보내기

## 2. 복수 오픈마켓 재고정보 수집하여 메일로 알림

0. 각 OpenMarket 점검 시간인지 checking
1. 로그인 페이지 접속
2. 로그인 시도
3. 재고 정보 확인 사이트로 이동
4. 재고 정보 수집 필터링 걸기
5. 엑셀 다운로드 or crawling
6. 데이터 가공(엑셀 합치기 or HTML 만들기)
7. 메일 보내기

## 3. 복수 오픈마켓 부가세 신고자료 취합하여 엑셀로 정리

0. 각 OpenMarket 점검 시간인지 checking
1. 로그인 페이지 접속
2. 로그인 시도
3. 부가세 확인 사이트로 이동
4. 부가세 정보 수집 필터링 걸기
5. 엑셀 다운로드 or crawling
6. 데이터 가공(엑셀 합치기 or HTML 만들기)
7. 메일 보내기

#### REST API 사용 버전

**(보류)**