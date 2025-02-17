### 리눅스 기본 명령어

## 0.명령어의 기본형식

command [options] [arguments]

- command : 실행할 명령어, 프로그램
- options : 명령어의 옵션
- argumunts : 명령어에 전달할 인자

## 1. 파일 및 디렉토리 관리

디렉토리는 윈도우로 치면 폴더라고 생각하면 된단다. 
파일을 정리하고 저장하는 공간

## ls(List)

- 디렉토리 내용 목록을 보여준다.  
- ex: ls -1 (한 줄에 하나씩 폴더 보여줌)
- ex: ls -a (숨김 파일 표시)

## cd(change directory)

- 현재 작업 디렉토리를 변경
- cd .. : 상위 디렉토리로 이동
- cd ~  : 내 홈 디렉토리로 이동
- cd  / : 루트 디렉토리로 이동

## pwd(print working directory)

- 현재 작업 중인 디렉토리의 전체 경로를 출력

## mkdir(make directory)

- 새로운 디렉토리 생성.
- mkdir 축구  -> 축구 폴더 생성
- mkdir "축구" -> 축구 폴더 생성
    (큰따옴표 덕분에 글자간 공백 가능)
- mkdir {축구, 농구, 야구}
    (여러 폴더 한번에 생성 가능)

# 알아두면 좋은 것 - rmdir "" -> 폴더 삭제

## rm(remove)

- 파일 삭제
- rm -r "축구" -> 폴더 삭제 가능

## cat(conatenate)

- 파일의 내용을 출력
