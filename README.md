Linux 명령어


1. top [옵션] : 시스템 프로세스/메모리 사용 현황을 실시간으로 출력


OS: 리눅스에서만 지원


경로: /usr/bin/top


> top 명령어
 -b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.
 -d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력
 -i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.
 -n num : 지정한 시간(num)만큼 업데이트 정보를 출력
 -p pid : 지정한 프로세스 ID(pid)의 정보만을 출력
 -q : 시간의 간격 없이 계속하여 업데이트 정보를 출력
 -s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).
 -S : 누적된 정보를 출력한다(cumulative 모드).
>
> 
2. ps [옵션]: 프로세스의 현재 상태를 출력
 OS: 유닉스와 리눅스 모두에서 명령어와 옵션이 같음
 경로: /bin/ps
>
>
> 전체 프로세스와 관련된 옵션
-A : 모든 프로세스를 출력
-N : -A 옵션과 비슷하나 ps 프로세스를 제외하고 출력>-a : 세션 리더 및 터미널에 속하지 않는 프로세스를 제외하고 출력
-d : 세션 리더를 제외한 모든 프로세스를 출력
-e : 커널 프로세스를 제외한 모든 프로세스를 출력
T : 현재 터미널에서의 모든 프로세스를 출력
a : 현재 터미널의 사용자 고유 프로세스를 출력
r : 현재 실행 중인 프로세스를 출력
x : 터미널이 없는 프로세스를 출력
--deselect : -N 옵션과 같다.


>특정 프로세스를 선택하여 보여주는 옵션
-C [명령어]: 지정한 명령어의 이름에 관련된 정보를 출력
-G [그룹 ID/이름]: 그룹 ID에 관련된 정보를 출력
-U [사용자 ID/이름]: 사용자 ID에 관련된 정보를 출력
-g [세션 리더/그룹명]: 지정한 세션 리더 혹은 그룹명에 관련한 정보를 출력
-p [프로세스 ID]: 프로세스 ID를 출력
-s [세션 ID]: 세션에 속한 프로세스를 지정
-t [tty]: tty를 지정
u [사용자 ID/이름]: 사용자 ID를 지정
U [사용자 ID/이름]: 지정한 사용자의 프로세스를 출력
-p [프로세스 ID]: 프로세스 ID를 지정
-t [tty]: tty를 지정


추가 옵션:
