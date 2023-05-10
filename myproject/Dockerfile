

# 베이스 이미지 설정
FROM python:3.8-slim

# 작업 디렉토리 설정
WORKDIR /myproject

# 종속성 파일 복사
COPY requirements.txt requirements.txt


# pip 업그레이드
RUN python -m pip install --upgrade pip

# 종속성 설치
RUN pip install --no-cache-dir -r requirements.txt

# 애플리케이션 복사
COPY . .


# flask 애플리케이션 위치 지정
ENV FLASK_APP=pybo/__init__.py

# config 파일 위치 지정
ENV APP_CONFIG_FILE=/myproject/config/development.py

# 애플리케이션 실행
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]