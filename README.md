# kr_invest_api
한국투자증권 API 코드

# poetry 실행방법
cmd창에 
poetry install : To install the defined dependencies for your project, just run the install command, 포트리에 기록된 의존성을 설치하며 설치후 포트리 기능을 사용가능
poetry run : poetry run python your_script.py와 같이 원하는 파일을 포트리를 통해 실행
poetry shell : The easiest way to activate the virtual environment is to create a new shell with poetry shell, 가상환경을 실행하듯 poetry shell기능을 활용하면 해당 환경이 실행됨
poetry add : add기능을 활용하여 pyproject.toml파일에 해당 패키지가 기록되며 자동으로 tool.poetry.repositores에 패키지가 저장됨 ex, poetry add pendulum

# config.yaml 파일 생성필요

APP_KEY:<br/>
APP_SECRET: <br/>
계좌번호 앞 8자리<br/>
CANO:<br/>
계좌번호 뒤 2자리<br/>
ACNT_PRDT_CD:<br/>

실전투자<br/>
URL_BASE: "https://openapi.koreainvestment.com:9443"<br/>
or<br/>
모의투자<br/>
URL_BASE: "https://openapivts.koreainvestment.com:29443"<br/>

Webhook URL<br/>
WEBHOOK_URL:<br/>

등의 정보 작성 필요 <br/>
