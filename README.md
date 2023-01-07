# python-study
## 2023 - 01-07

- 백준 3003문제
  - 체스는 총 16개의 피스를 사용하며, 킹 1개, 퀸 1개, 룩 2개, 비숍 2개, 나이트 2개, 폰 8개로 구성되어 있다.
  - 입력조건
  - 첫째 줄에 동혁이가 찾은 흰색 킹, 퀸, 록, 비숍, 나이트, 폰의 개수가 주어진다. 이 값은 0보다 크거나 같고 10보다 작거나 같은 정수이다.
    - 에제입력                  예제 출력
```
 0 1 2 2 7                 1 0 0 0 0 1
```
 3003번문제  <https://www.acmicpc.net/problem/3003>
 ```python
    
q = [1,1,2,2,2,8]
a = [0,1,2,2,2,7]
l = []
cnt = 0
for i in q:
    l.append(i - a[cnt])
    cnt += 1
print(l)
```
 
 # 라즈베리파이 한글깨짐
 $ sudo apt-get install fonts=unfonts-core
 $ sudo apt-get install ibus ibus-hangul
 $ sudo reboot
 -> iBus 환경설정
- 기본 디렉토리 명령어
  - ls
    - 현재 경로 파일 리스트
  - cd
    - 디렉토리 변경
  - mkdir
    - 디렉토리 생성
  - pwd
    - 현재 디렉토리
- 운영 관련 명령어
  - ps -aux
    - 현재 실행중인 프로세스
  - netstat -tnl
    - 현재 사용중인 TCP 포트
  - ufw
    - 방화벽 설정
  - history
    - 명령어 history
