# 클래스로(Classro) 회사 소개 웹사이트

`00_회사소개.md`를 바탕으로 만든 회사 소개 웹사이트입니다.

> 수업용 가상 회사입니다. 등장하는 회사·인물·수치는 모두 지어낸 것입니다.

## 실행 방법

설치할 것은 없습니다. `index.html` 파일을 더블클릭하면 브라우저에서 열립니다.

## 폴더 구조

```
test/
├── index.html        # 메인 페이지
├── css/
│   └── style.css     # 디자인 (색상, 레이아웃, 반응형)
├── js/
│   └── main.js       # 동작 (메뉴, 스크롤 효과, 숫자 애니메이션)
└── 00_회사소개.md     # 원본 회사 소개 자료
```

## 페이지 구성

| 섹션 | 내용 |
| --- | --- |
| 소개 | 설립, 대표, 직원, 서비스, 제휴 공방, 수익 모델 |
| 클래스 | 도자기 · 베이킹 · 가죽공예 · 플라워 · 드로잉 · 향수 |
| 숫자로 보기 | 제휴 공방 420곳, 월 예약 7천 건, 평균 결제액 42,000원, 지역별 공방 비율 |
| 이용 방법 | 방문 → 검색/탐색 → 클래스 상세 → 날짜·인원 선택 → 결제 → 예약 완료 |
| 목표 | 2026년 4분기 목표 3가지 (전환율, 리뷰 평점, CAC) |
| 소식 | 최근 있었던 일 타임라인 |
| 팀 | 직무별 인원 |

## 주요 기능

- 모바일 화면에서 햄버거(☰) 메뉴로 전환
- 스크롤하면 내용이 서서히 나타나는 효과
- 숫자 카운트업 애니메이션
- 현재 보고 있는 섹션에 맞춰 메뉴 강조
- 맨 위로 이동 버튼

## 사용 기술

- HTML, CSS, JavaScript (라이브러리 없음)
- 글꼴: Google Fonts (Noto Sans KR, Gowun Batang)

---

# 깃허브 사용 첫번째 

git init  # 한번만

git add README.md  

git add .(모든파일)
git commit -m "first commit"

git add README.md 
git commit -m "second commit"

# 여러번 구간

git remote add origin https://github.com/alsj1642/test.git  #한번만

git branch -M main  # main 대신 다른이름으로 사용가능 branch마다 한번만 사용

git push -u origin main   #main branch 이름 , 여러번 사용가능


깃 연습 하는 중