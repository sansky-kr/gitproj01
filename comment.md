1. 댓글 기능
git config --global credential.<URL>.username <USERNAME>
https://github.com/sansky-kr/gitproj01

@sansky-kr
https://github.com/sansky-kr/gitproj01


remote url에 사용할 계정을 명시하는 것이었다.

1. 회사 repository는 회사 github 계정 이름을 포함해서 remote url 설정
git remote set-url origin https://username-company@github.com/company

2. 개인 repository는 개인 github 계정 이름을 포함해서 remote url 설정
git remote set-url origin https://username-personal@github.com/personal



--token
git remote set-url origin https://sansky-kr@github.com/sansky-kr/gitproj01
--shop old
git remote set-url origin https://sansky-kr@github.com/personal

sansky-kr@github.com 계정 삭제함.
