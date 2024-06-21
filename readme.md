##

o_v 가상환경 설정

설치 파일

- pip django


  // My SQL
  <details>
<summary>
- pip install mysqlclient  
  settings.py 수정
</summary>
수정 예시
DATABASES = {
'default': {
'ENGINE': 'django.db.backends.mysql',
'NAME': 'MYTEST',
'USER': 'root',
'PASSWORD': '1234',
'HOST': 'localhost',
'PORT': '3306',
}
}

</details>
