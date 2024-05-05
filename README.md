# cpp_and_sqlite3
dev-c로 c++파일을 실행하고 진행할시 오류가 발생하여
vscode를 가지고 실행을 해야합니다.
다만 vscode도 컴파일 부분을 c++로 작동이 되도록 설정을 변경해 주어야 합니다.
https://webnautes.tistory.com/1854
이 링크를 통해서 vscode에서 c++이 컴파일이 되도록 설정을 변경해 주어 실행하였습니다.

폴더에 sqlite3.c, sqlite.h, sqlite.dll, sqlite.def 파일을 sqlite3홈페이지에서 다운받은것을 토대로 위 4개의 파이을 한곳에 담아두어야합니다.
폴더에서 cmd로 명령어 프롬프트를 열어 sqlite3 sj.db로 db를 만든후 create~~~~로 학생 3명의 kor, eng 2개의 성적을 입력하여 저장하였습니다.
score.cpp 파일을 만들어 c++에서 3명의 학생의 학생별 총점과 평균, 과목별 총점과 평균을 구하도록 만들었습니다. 
