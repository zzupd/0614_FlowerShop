주어진 결과화면을 참조하여
html 페이지를 제작합니다.

작업사항1.
헤더 GNB 메뉴와 푸터 GNB 메뉴에
마우스를 올렸을 때 해당 메뉴가 
선택되었다는 것을 표현할 수 있는 
스타일을 적용합니다. 적용할 스타일은 
작업자가 원하는 디자인을 적용합니다.

작업사항2.
꽃다발, 꽃바구니, 화환에 마우스를 올렸을 때
해당 영역이 선택되었다는 것을 표현할 수 있는
스타일을 적용합니다.  적용할 스타일은 
작업자가 원하는 디자인을 적용합니다.



--------------------------------------

[전체 레이아웃 emmet]
div#wrap>header#header+nav#gnb+main#main+div#contents+footer#footer


[JS에서 페이지 이동 코드]
location.href = "URL";
보기.
location.href = "https://www.naver.com";


--------------------------------

[작업 관리 기법]
=> 단위 테스트, 통합 테스트, 형상관리...

[형상관리 = 버전관리]
=> CVS, Git, ...

[Git(깃)을 사용한 형상관리]
1. 작업 중간중간 결과물을
   시간별로 저장한다.
2. 시간별로 저장할 수도 있으며
   작업자 별로 저장할 수도 있음.
3. 작업에서 수정, 삭제, 생성된
   모든 내용의 기록을 남길 수 있음
4. 인터넷이 연결된 어디에서라도
   버전별 내용을 확인할 수 있음.

참고. Git은 형상관리용 프로그램
       Git을 사용하여 시간별, 버전별
       파일을 저장하는 인터넷 공간은
       여러개가 있으나 Github를
        주로 사용함.


[Git을 사용한 형상관리 순서]
1. Git 프로그램 설치
   (= Git Bash 깃 배쉬 라고도 함)
   다운로드 URL =>
   https://git-scm.com/


2. Git 프로그램을 사용하여
   퍼블리셔가 만든 파일을
   저장하는 공간을 지정함.
   => Github, 깃허브
   URL => https://www.github.com/

3. 편집기에서 Git을 사용하여
   Github를 연동하는 플러그인 설치
   => Brackets Git 설치

4. 업로드/다운로드로 
   작업자가 만든 파일을 관리함.











