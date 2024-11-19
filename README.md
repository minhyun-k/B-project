<div align="center">

<!-- logo -->
<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/loading-1.png" width="400" height="400"/>

### IEUM 🖍️

</div> 

## 📝 프로젝트 소개

# B-Project는 순수 HTML, CSS, JavaScript만을 활용하여 제작한 웹 프로젝트로, 다음과 같은 목표를 가지고 개발되었습니다.

1. **웹 기본기를 다지기 위한 학습 목적**

- 웹 표준 기술을 활용해 구조적이고 유지보수 가능한 코드를 작성하는 데 중점을 두었습니다.

2. **반응형 웹사이트 제작 경험 강화**

- 다양한 디바이스 환경에 적합한 레이아웃과 스타일을 구현하며, Flexbox와 Grid를 실전에서 효과적으로 사용하는 방법을 익혔습니다.

3. **UI/UX 개선 및 디자인 구현 능력 향상** 

- 사용자 친화적인 인터페이스를 구축하고, CSS 애니메이션과 상호작용을 통해 동적인 웹페이지를 설계했습니다.

> 프로젝트를 통해 HTML, CSS, JavaScript의 기초를 강화하며, 디자인과 개발 간의 유기적인 연결성을 이해하는 데 기여했습니다.

---

[배포사이트 링크](https://b-project-lilac.vercel.app/)  
[GitHub Repository](https://github.com/minhyun-k/B-project.git)
<br />

## 🗓 프로젝트 일정
**총 일정 2024.06 ~ 2024.08**


<br />

## 💁‍♂️ 프로젝트 팀원
강민현(팀장&기획&배포), 고유나(기획), 박지연(디자인), 박민지(자료수집)


<br />
## 🛠 화면 구성

|화면 명|
|:---:|
|로딩 화면|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/loading.gif" width="450"/>|
|처음 어플리케이션 실행 시 로딩화면 출력|
|메인 홈|
|:---:|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/Home.gif" width="450"/>|
|홈 화면은 서버요청을 통해 베스트셀러, 신간 등 카테고리에 맞는 데이터가 출력되어 사용자가 도서 목록을 확인할 수 있습니다.|
|도서목록|
|:---:|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/list.gif" width="450"/>|
|홈 화면에서 각 카테고리별 더보기 클릭시, 혹은 헤더 메뉴 클릭시 각 카테고리에 맞는 도서 목록이 페이지에 출력됩니다.|
|상세페이지|
|:---:|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/detail.gif" width="450"/>|
|홈, 도서목록에서 사용자가 관심있는 도서 컨텐츠를 클릭 시, 클릭한 도서의 상세정보가 포함된 페이지가 열립니다. 이 페이지에서는 도서의 상세내용, 북마크, 코멘트 작성이 가능하며, 베스트셀러의 경우 베스트 순위, 신간의 경우 신간도서 표시가 제공됩니다.|
|북마크 등록 및 코멘트 작성|
|:---:|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/detail2.gif" width="450"/>|
|북마크 클릭시 '읽는중', '읽고싶어요' 등록 가능, firebase를 통해 각 로그인한 사용자 개인 북마크 기능 활성화, 코멘트 작성 시 별점과 리뷰(댓글형식)가 표시됩니다.|
|마이페이지|
|:---:|
|<img src="https://github.com/minhyun-k/Book-IEUM/blob/main/public/mypage.gif" width="450"/>|
|로그인 시 firebase를 사용하여, 각 사용자가 사용한 북마크와 코멘트가 출력되어 사용자의 경험, 히스토리를 확인할 수 있습니다.|

<br />

## ⚙ 기술 스택

이 프로젝트는 다양한 최신 기술을 활용하여 구현되었습니다.

- **Frontend**: HTML5, CSS3, JavaScript (ES6), Sass
- **Design**: Figma (와이어프레임 및 프로토타입 설계)
- **Vercel**: 배포 플랫폼 (배포 사이트: [https://b-project-lilac.vercel.app/](https://b-project-lilac.vercel.app/))
- **GitHub**: 버전 관리 및 협업 도구

<br />

## :wrench: 주요 기능 및 특징

1. **다양한 디바이스를 지원하는 반응형 디자인**  
   - `@media` 쿼리를 활용해 모바일, 태블릿, 데스크톱 등 화면 크기에 따라 레이아웃이 자동으로 조정됩니다.  
   - 주요 콘텐츠는 Flexbox와 Grid 레이아웃을 통해 가독성 높은 구조로 배치되었습니다.  

2. **사용자 인터랙션 향상**  
   - 버튼 클릭, 링크 호버, 이미지 확대 등 CSS 애니메이션을 활용해 시각적으로 즐거운 사용자 경험을 제공합니다.  
   - JavaScript 이벤트 핸들러를 활용해 사용자와의 상호작용을 동적으로 처리했습니다.  

3. **재사용 가능한 UI 컴포넌트**  
   - 프로젝트 내 다양한 섹션(헤더, 푸터, 카드 등)은 재사용 가능한 구조로 설계되어 유지보수가 용이합니다.  

4. **다양한 콘텐츠 관리**  
   - 이미지를 포함한 정적 리소스와 텍스트 콘텐츠가 깔끔히 정리되어 있어 사용자에게 직관적인 정보 전달이 가능합니다.  

---
<br />

## 🤔 기술적 이슈와 해결 과정

# 이슈 1: 반응형 레이아웃 문제  
- **문제**: 화면 크기에 따라 특정 요소가 겹치거나 비율이 왜곡되는 문제가 발생.  
- **원인 분석**:  
  - 고정된 `px` 단위 사용으로 인해 유연한 크기 조정이 어려웠음.  
  - Flexbox, Grid의 설정이 올바르지 않아 의도한 배치가 이루어지지 않음.  
- **해결 과정**:  
  1. CSS 단위를 `px`에서 `%, rem, vh/vw`로 변경하여 유연성을 확보.  
  2. 레이아웃 구성 시 Flexbox의 `align-items`와 `justify-content`를 활용해 중앙 정렬 및 비율 조정을 적용.  
  3. `@media` 쿼리를 통해 화면 크기별로 레이아웃을 세분화.  
- **결과**: 모든 화면 크기에서 UI가 안정적으로 표시되도록 개선.  

# 이슈 2: JavaScript 이벤트 처리  
- **문제**: 특정 버튼 클릭 이벤트가 제대로 작동하지 않거나, 이벤트가 중복 발생하는 현상.  
- **원인 분석**:  
  - 이벤트 리스너가 잘못된 DOM 요소에 연결되었거나, 이벤트 버블링 처리가 미흡했음.  
- **해결 과정**:  
  1. `document.querySelector`를 통해 정확한 DOM 요소를 선택.  
  2. 이벤트 위임(Event Delegation)을 적용하여 효율적으로 이벤트를 관리.  
  3. 디버깅 도구(Chrome DevTools)와 `console.log`를 활용해 코드 실행 흐름을 추적.  
- **결과**: 버튼 클릭 시 기대한 동작이 일관되게 수행됨. 

<br />

##  :file_folder: 폴더 구조
B-project/ 
├── 📂css/ # 스타일 관련 파일 
<br />
├── 📂data/ # 데이터 파일들 
<br />
├── 📂img/ # 이미지 파일들 
<br />
├── 📂js/ # JavaScript 파일들 
<br />
│ ├── 📄animal.js # 동물 페이지 
<br />
│ ├── 📄aqua.js # 아쿠아 페이지 
<br />
│ ├── 📄common.js # CEO 소개 페이지 
<br />
│ ├── 📄cure.html # 치료 관련 페이지 
<br />
│ ├── 📄cure.habitat.js # 상세 정보 페이지 
<br />
│ ├── 📄detail.js # 서식지 정보 페이지 
<br />
│ ├── 📄index.js 
<br />
│ ├── 📄info.js # 정보 페이지 
<br />
│ ├── 📄map.js # 지도 및 위치 정보 페이지 
<br />
│ ├── 📄rescue.js # 구조 관련 페이지 
<br />
│ ├── 📄research.js # 연구 관련 페이지 
<br />
│ ├── 📄study-detail.js # 연구 세부 정보 페이지 
<br />
│ ├── 📄study.js # 연구 관련 일반 페이지 
│ ├── 📄subPage.js 
│ └── 📄top_btn.js # 스크롤업 버튼(반응형)
├── 📄animal.html # 동물 페이지 
├── 📄aqua.html # 아쿠아 페이지 
├── 📄ceo.html # CEO 소개 페이지 
├── 📄cure.html # 치료 관련 페이지 
├── 📄detail.html # 상세 정보 페이지 
├── 📄habitat.html # 서식지 정보 페이지 
├── 📄header.html # 헤더 템플릿 
├── 📄index.html # 메인 페이지 
├── 📄info.html # 정보 페이지 
├── 📄map.html # 지도 및 위치 정보 페이지 
├── 📄rescue.html # 구조 관련 페이지 
├── 📄research.html # 연구 관련 페이지 
├── 📄study-detail.html # 연구 세부 정보 페이지 
├── 📄study.html # 연구 관련 일반 페이지 
├── 📄video.html # 비디오 페이지 
└── 📄README.md # 프로젝트 소개 파일






