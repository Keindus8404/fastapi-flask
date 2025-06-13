# FAST API 설치
```
pip install fastapi uvicorn sqlalchemy
```

# FAST API 실행 - main.py가 있는 api 폴더에서 실행
```
cd api
uvicorn main:app --reload
```

# API 테스트
```
http://localhost:8000/docs
http://127.0.0.1:8000/docs
```

# flask 설치
```
pip install flask
```

# flask 실행
```
새 터미널 - cd frontend
python app.py
```

# 주요 에러
```
CROS
pydantic으로 API서버에서 데이터정의를 했기때문에 타입에 맞게 데이터를 넘겨줘야함
```