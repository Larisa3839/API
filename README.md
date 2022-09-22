# API
POST https://blog.kata.academy/api/users
body: 
{
  "user": {
    "username": "larisa3839",
    "email": "larisa.chikovkina97@gmaill.com",
    "password": "123123"
  }
}
Response:
{
    "user": {
        "username": "larisa3839",
        "email": "larisa.chikovkina97@gmaill.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmNiMTczM2NmNzA1MWIwMDgyYTY3ZiIsInVzZXJuYW1lIjoibGFyaXNhMzgzOSIsImV4cCI6MTY2OTA1NzM5NSwiaWF0IjoxNjYzODczMzk1fQ.U4NKUbIWKr0pwEm0uLLvYrGGInsiPApWD-KFIN_Wxao"
    }
}


POST https://blog.kata.academy/api/users/login
body:
{
  "user": {
    "email": "larisa.chikovkina97@gmaill.com",
    "password": "123123"
  }
}
{
    "user": {
        "username": "larisa3839",
        "email": "larisa.chikovkina97@gmaill.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmNiMTczM2NmNzA1MWIwMDgyYTY3ZiIsInVzZXJuYW1lIjoibGFyaXNhMzgzOSIsImV4cCI6MTY2OTA1ODYzMywiaWF0IjoxNjYzODc0NjMzfQ.lpvLVCgiBaEvTQAl4VRtbFXs8GH6UsYmDK-v2Vo9yPk"
    }
}
Response:
{
    "user": {
        "username": "larisa3839",
        "email": "larisa.chikovkina97@gmaill.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmNiMTczM2NmNzA1MWIwMDgyYTY3ZiIsInVzZXJuYW1lIjoibGFyaXNhMzgzOSIsImV4cCI6MTY2OTA1ODM4MSwiaWF0IjoxNjYzODc0MzgxfQ.eIBA1My1gl98BP-x5LlYoUD_XP5ogIWn2Vlhmv-RqBk"
    }
}


GET https://blog.kata.academy/api/user
Token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmNiMTczM2NmNzA1MWIwMDgyYTY3ZiIsInVzZXJuYW1lIjoibGFyaXNhMzgzOSIsImV4cCI6MTY2OTA1ODM4MSwiaWF0IjoxNjYzODc0MzgxfQ.eIBA1My1gl98BP-x5LlYoUD_XP5ogIWn2Vlhmv-RqBk
Response:
{
    "user": {
        "username": "larisa3839",
        "email": "larisa.chikovkina97@gmaill.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmNiMTczM2NmNzA1MWIwMDgyYTY3ZiIsInVzZXJuYW1lIjoibGFyaXNhMzgzOSIsImV4cCI6MTY2OTA1ODYzMywiaWF0IjoxNjYzODc0NjMzfQ.lpvLVCgiBaEvTQAl4VRtbFXs8GH6UsYmDK-v2Vo9yPk"
    }
}
