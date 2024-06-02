# 리눅스 명령어
_*1. top


-시스템의 현재 상태와 프로세스 정보를 실시간으로 제공해줌

-리소스 사용량, 프로세스 목록, 부하, 메모리 사용량, CPU 사용량 등을 확인하는 데 사용

-top 명령을 실행하면 터미널 창에 실시간으로 갱신되는 시스템 상태가 나타남

2. top 명령어 옵션

a : 메모리 사용량에 따라 정렬

b : Batch 모드 작동

C : 명령행/프로그램 이름 토글

d. 지연 시간 간격은 다음과 같다.-d ss. tt (seconds.tenths)

h : 도움말

H : 스레드 토글

i : 유휴 프로세스 토콜

3. ps

ps 명령어는 Process State의 약자로 현재 실행 중인 프로세스와 상태를 출력하는 명령어입니다. 

4. ps 명령어 옵션

A 모든 프로세스를 출력

a (BSD) 터미널과 연관된 프로세스를 출력, x 옵션과 같이 사용하여 모든 프로세스를 출력할 때 사용

-a 세션 리더를 제외하고 데몬 프로세스처럼 터미널에 종속되지 않은 모든 프로세스를 출력

-e 커널 프로세스를 제외한 모든 프로세스를 출력

-f 출력을 풀 포맷으로 표기 (유닉스 스타일) UID, PID , PPID 등이 함께 표시

-l (System V)l (BSD) 출력을 긴 포맷으로 표기 프로세스의 정보를 길게 보여주는 옵션으로 우선순위와 관련된 PRI 값과 NI 값을 확인

-o 출력 포맷을 지정

-M 64비트 프로세스들을 출력

-m 프로세스뿐만 아니라 커널 스레드도 출력

-p 특정 PID를 지정하여 출력

-r 현재 실행 중인 프로세스 출력

5. jobs

jobs 명령어는 작업의 상태를 표시하는 명령어이다.

6.
