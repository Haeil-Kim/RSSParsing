-------- 필요한 모듈 ------
pip install feedparser beautifulsoup4 requests

전부 json 형태로 저장되니 파일 읽어서 돌려주기만 하면됨

파이썬 파일은 자동으로 시간마다 실행되는 방식이 아니라 
crontab 같은 프로그램 필요

실행은 그냥 python3 main.py 실행시키면 자동으로 업데이트됨