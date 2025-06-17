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

# API 서버
```
- 사용자
    - 회원가입(/api/register)
    - 로그인(/api/login)
    - 사용자 정보 조회(/api/user/user_id)
- 상품
    - 전체상품 조회(/api/products)
    - 상품 상세조회(/api/products/{product_id})
    - 상품 등록(/api/products)
    - 상품 수정(/api/products/{product_id})
    - 상품 삭제(/api/products/{product_id}) ->RESTful Delete 호출
- 장바구니
    - 장바구니 담기(/api/cart)
    - 장바구니 조회(/api/cart)
    - 수량 수정(/api/cart/{cart_id})
    - 장바구니 상품 삭제
- 주문
    - 주문하기
    - 주문 목록 조회
    - 주문 상세 조회
    - 주문 상태 변경
```