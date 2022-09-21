# TIL

## 2022-09-21

### Linux commend line 기초

1. `pwd` print working directory  

2. `cd` change directory  

3. `ls` list
     `-a` 나 `-l` 등의 옵션을 붙일 수 있음  
    `ls -a`: 숨김파일도 표시  
    `ls -l`: 자세히 표시  
    `ls -al`: 숨김파일+자세히

### vim 사용법

     window에서 git bash를 설치할 때, default editor로 vim을 사용했기 때문에 git을 사용하려면 반드시 vim을 사용할 줄 알아야 함.   

#### 명령모드
1. vim editor를 켤 때는 명령모드로 진입 -> 이 때는 입력이 불가능함.   

2. 입력모드로 바꿔야 하는데, 키보드 `i` (insert) 등의 키를 누름.

3. 입력이 끝나고 저장 등의 모드로 돌아가려면 키보드 `esc` 키를 누르면 됨.
     - `:q` quit 종료
     - `:w` write 저장
     - `:wq` write & quit 저장&종료