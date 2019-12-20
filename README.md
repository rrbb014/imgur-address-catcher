# Imgur-address-catcher

markdown에 그림을 올릴때 imgur에 업로드 하고 주소를 하나씩 복사+붙여넣기 
하는 작업이 지루해서 만든 스크립트.
실행 후, Ctrl+V를 하면 주소가 복사되어 있습니다!

## Requirement
```pip install -r requirements.txt```

## Usage
```python imgac.py 'image-path'```

## Example
```python imgac.py sample.png```

## CAVEAT

.env내부에 IMGUR_CLIENT_ID에 imgur 계정의 클라이언트 ID를 바꿔주어야합니다.

확인 방법은 [imgur.com](https://imgur.com) 사이트에서 계정 생성 후

settings -> application 에 들어가면 client id 값을 복사 후, 붙여넣으시면 됩니다.

## License
[MIT license](https://github.com/nishanths/license/blob/master/LICENSE)
