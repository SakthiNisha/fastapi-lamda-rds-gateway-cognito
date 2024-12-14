venv creation:
python -m venv fastlamrdsgatecognito

venv activation:
./fastlamrdsgatecognito/Scripts/activate

Installed packages:
pip install fastapi mangum mysql-connector-python uvicorn

Generate a requirements.txt file:
pip freeze > requirements.txt

Installing dependencies into package folder:
pip install -r requirements.txt -t package

Lambda function name:
fastapi-lambda-rds

RDS instance name:
fastapi-lambda-rds
DB name: fastapilambdards
username:admin
password:admin1234

Start your FastAPI application using Uvicorn:
uvicorn main:app --reload
