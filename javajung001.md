# 기본, 단축키

**정리**

1.javac.exe-자바 컴파일러, 사람이 작성한 문장을 기계어로 번역. 소스파일(*.java)을 클래스파일(*.class)로 변환

2.java.exe-자바 인터프리터. 자바 프로그램(클래스파일)을 실행

3.클래스-자바 프로그램의 단위, 자바 프로그램은 클래스들로 구성.

4.main매서드**(=펑션=함수!!!**)-자바 프로그램의 시작점. 이 메서드 없이 실행불가

이클립스의 기본 화면-퍼스펙티브

클래스파일은 안보이는데

윈도우-네비게이터를 확인하면 생성된건지 확인 가능함

앞에 .(콤마)가 붙은 파일은 이클립스가 생성한 파일이니까 건드리지 마

정리-이크립스에서 자바 프로그램을 작성하는 순서

1.프로젝트를 생성한다

-Menu File>New>Java Project

2.클래스를 생성한다.

-프로젝트 이름 위에서 우클릭>New>Class

>>Build 관련 메뉴 설명

*Build란?!!!

-소스파일(*.java)로부터 프로그램을 만들어 내는 전 과정

*Project>Build All

-workspace의 모든 프로젝트를 빌드

*Project>Build Project

-현재 프로젝트를 빌트 (변경된 소스 파일만 새로 컴파일)

*Project>Clean

-이전 빌드의 정보를 모두 삭제(모든 소스 파일을 새로 컴파일)

가끔 제대로 실행 안될때 해보기!!!

*Project>Build Automatically

-소스 파일을 변경 후, 저장할 떄마다 자동 컴파일

단축키

ctrl+shift+L 단축키 전체 목록 보기

ctrl+ +,- 폰트 크기 증가/감소

ctrl+D 한 줄 삭제

ctrl+alt+down 행단위 복사 - 이건 노트북에서 쓰면 상하반전되니까 바꿈. 

윈도우 프리퀀시 제네럴 키스>copy line 에서 바꿈 ctrl+alt+shift+down

alt+shit+A 멀티컬럼 편집 여러줄을 한번에

alt+up, down 행단위 이동

tab 들여쓰기 

ctrl+i 자동 들여쓰기 맞춤

ctrl+/ 주석 (토글)

/*    */ 여러줄 주석

//

ctrl+space 자동완성기능

Window-프리퍼런시-자바-템플릿.

system.out.println이 sysout로 등록되어 있는데 이걸 sop로 바꿔서 사용하자. 클릭하고 no

보통 콤마(.)를 누를때 나오는 자동완성은 윈도-프리퍼런시-자바-에디터-콘텐트 어시스트.

오토 엑티베이션 트리거에 콤마(.)만 설정되어 있는데 abcdefg~~~쓰면 모든키가 자동완성

프로젝트 임포트할때 카피 프로젝트 워크스페이스에 체크 copy project workspace

익스포트 할때는 export -save in zip format. 

print()출력 후 줄바꿈 안함

println() 출력후 줄바꿈