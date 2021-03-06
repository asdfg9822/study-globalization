
# study-globalization
study internalization, globalization, localization

## 세계화, 국제화, 현지화의 의미

1) 세계화(Internalization, I18N)
- 전 세계 시장을 하나의 시장으로 보고 동일한 전략을 수행하는 것. 국제화와 현지화를 포함하는 전체적인 기획 단계

2) 국제화(Globalization)
- 세계화 기획을 실현시킬 수 있는 기능을 구현하는 단계
- 언어 입력 및 표시, 날짜 및 시간 표기 문자 정렬 순서 데이터 교환 등을 포함하고 다양한 데이터를 지정 언어와 지역에 맞는 형식으로 표현

3) 현지화(Localization)
- 특정 언어 또는 지역에 맞게 적용시키는 프로세스

## Locale 구분
[언어]_[국가]
```
- ko_KR : 한국어
- en_GB : 독일식 영어
- en_US : 미국식 영어
```
## Locale에 따라 달라질 수 있는 동작
1) 시간

시간은 12, 24시간제가 있음. 시간/분/초의 구분자는 - : . 로 구분

```
- 12:00:00 PM
- 12:00:00 p.m.
- 12-00-00 pm
- 오후 12시 00분 00초
- 23時59分00秒
```

2) 날짜
```
- 07/12/31
- 7/12/31
- 2011년 07년 16일
```
3) 숫자
```
- 123,456.00 : 한국
- 123456,00 : 아랍
- 123 456,00 : 독일
- 1,23,456.00 : 인도
```
4) 통화
```
- ￦ 1 : 원
- $US 0.000809 : 달러
- £UK 0.000579 : 파운드
```
5) 언어
```
- 단어간 구분자로 공백문자가 쓰이는 문자가 있는 반면 중국어 일본어 등은 띄어쓰기가 없는 경우가 있음
- 정렬 순서가 다를 수 있음 (영어와 한국은 순서가 다름)
- 일본어의 경우 표의문자, 히라가나, 가타가나가 혼합되어 사용
- 중국어의 경우 30000자 정도의 글자가 있을 수 있음

```

6) 이름과 직함
7) 정부 지정 번호 (주민등록번호 미국의 사회보장번호 등)과 여권
8) 전화 번호, 주소 국제 우편 번호
9) 전화 번호 주소 국제 우편 번호
10) 중량과 치수
11) 종이 크기

##유니코드 (TODO)

##폰트 (TODO)

##언어 패키징 (TODO)


## 국제화 라이브러리
1) i18next
 - https://www.i18next.com/for-enterprises.html

## 국제화 참고 사이트
1) 자바스크립트 국제화 정리 사이트
 - http://rxaviers.github.io/javascript-globalization/
2) 오라클 국제 언어 환경 설명서
 - https://docs.oracle.com/cd/E26925_01/html/E27145/toc.html
3) Apple 국제화 가이드
 - https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/Introduction/Introduction.html
