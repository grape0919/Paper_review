
# Data Crawler for OCR Installation
법령 데이터를 수집할 수 있는 크롤러이다.

repository :[https://gitlab.com/lh_kr/ovo/datacrawler.git](https://gitlab.com/lh_kr/ovo/datacrawler.git)
### Install & Run

레포지토리를 클론하여 사용합니다.
```bash
git clone [https://gitlab.com/lh_kr/ovo/datacrawler.git](https://gitlab.com/lh_kr/ovo/datacrawler.git)
git checkout develop
```

파이썬 실행을 통해 간단하게 크롤링할 수 있습니다.
```bash
python app.py
```
크롤링 타켓은 `ListOfLaw.txt` 파일에 들어있으며, 기본적으로 pdf 파일을 다운로드 합니다.
