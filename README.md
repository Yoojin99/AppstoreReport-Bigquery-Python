# AppstoreReport-Bigquery-Python
:scroll:Upload appstore report data to google cloud bigquery through python

## 소개

### 이걸 할 수 있어요

1. **Python으로 App Store Sales and Trends Reports 다운받기/출력하기**.
2. **로컬 파일(데이터셋, csv 파일) Bigquery에 업로드하기**.

### 폴더 및 파일 설명

```
.
├── 1. Basic Python Slack Bot
│   └── BasicSlackBot.py # 기본 슬랙 파이썬 봇. 간단한 텍스트를 설정하여 슬랙에 보냅니다.
├── 2. Python-Bigquery 
│   └── BigqueryBot.py # Bigquery 데이터를 python을 이용하여 바로 가져옵니다.
└── 3. Python-Google Spreadsheet
    └── SpreadsheetBot.py # Google spreadsheet에 데이터를 쓰거나, 데이터를 읽습니다.
```

### 따라하기 및 설명

:closed_book: [1. Donwload app store report]()

:orange_book: [2. UPload data file to bigquery]()


### 이걸 만들게 된 이유

App Store의 sales&trend report 들을 다운받아 리포트의 데이터들을 Google cloud bigquery에 업로드하는 작업을 했습니다.

App store에 개발자들을 위해 존재하는 document에서 api에 대한 설명과 사용하기 위해 필요한 uri가 나와있지만, 보고 바로 이해하여 사용하기 어렵습니다. 
또한 코드로 구현하려는 사람들을 위한 예시가 나와 있지 않고, 검색했을때 찾을 수 있는 라이브러리도 오류가 있는 부분이 있었으며, 한글 자료가 아예 없었기 때문에 한글 자료가 있으면 좋을 것 같아 기록으로 남깁니다.
