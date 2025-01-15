## [2025] PROJECT2 <Streamlit DashBoard>
* * *
<div align="center">
    네이버 뉴스를 토대로 특정 카테고리의 토픽을 분석하고,
    이를 워드클라우드 형태로 시각화합니다. 동시에 국내 주식을 시각화하여 
    직관적이고 효율적인 데이터분석 경험을 사용자에게 제공합니다.
</div>

# project2 폴더 구조
DASHBOARD_PROJECT/
├── 📁data/
│    ├── articles_IT.csv
│    ├── articles_db.csv
│    ├── articles_g.csv
│    ├── articles_g.csv
│    └── articles_.csv
└── 📁naver_news_crawling/
    ├── __pycache__
    ├──📁view/
    │   ├── __pycache__
    │   ├── home.py
    │   ├── main.py
    │   ├── page_1.py
    │   ├── page_2.py
    │   └── style.py
    ├────── crawl_marketindex.py
    ├────── naver_news_crawling.py
    └────── topic_modeling.py


파일 설명
1. main.py
- Streamlit 앱의 메인 파일.
- 기본 홈 화면 역할을 하며, 사이드바를 통해 다른 페이지로 이동할 수 있도록 구성.

폴더명|폴더 설명
---|---|
pages|- Streamlit에서 자동으로 인식하는 페이지 파일들이 포함된 폴더.
- 각 파일은 독립적인 페이지로 동작|

2.1 home.py
- 홈 화면 페이지.
- 앱의 기본 정보와 환율 정보를 표시.

2.2 page_1.py
- 첫 번째 추가 페이지.
- 

2.3 page_2.py
- 두 번째 추가 페이지.
- crawl/ 폴더 내의 파일(example.py)과 연동된 기능이 포함.

폴더명|폴더 설명
---|---|
2.4 crawl|crawl.py
- 보조 기능이나 유틸리티를 제공하는 파일.
- 예를 들어, 크롤링 관련 함수 정의.|



참고 문서
- 불용화사전 google docs
    https://docs.google.com/document/d/e/2PACX-1vRn9KiLOzqSgx8hCzhJnctvy6n0lxSWTXUEN04WjHcauHhKpOIWXPFQdh32RWPjGtU2IJlr2GzhnWSZ/pub
- 