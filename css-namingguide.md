# CSS-NamingGuide

용어정리
1. prefix //
  타이틀
  |- tit      #일반적인 타이틀

  영역
  |- section  #제목태그 포함 영역 (중첩사용 지양)
  |- wrap     #일반 영역 묶음 (중첩사용 지양)
  |- inner    #부모 wrapper가 존재할 경우, 자식 묵음이 단독으로 있어야 할 경우

  네비게이션
  |- gnb      #서비스 전체 네비게이션
  |- inb      #지역 네비게이션 (gnb 영역)
  |- snb      #사이드 네비게이션

  탭
  |- tab

  테이블
  |- tbl

  목록
  |- list     #일반 목록 ul, ol형식의 dl

  폼
  |- tf       #textfield
  |- inp      #input타입 radio,checkbox,file 등
  |- opt      #selectbox
  |- lab label
  |- fld      #fieldset

  버튼
  |- btn

  박스
  |- box

  아이콘
  |- ico

  선
  |- line_방향
  |- line_dot_방향

  배경
  |- bg

  썸네일
  |- thumb

  페이징
  |- paging

  배너
  |- bnr/banner

  텍스트
  |- txt        #일반텍스트
  |- txt_bar    #구분선 텍스트
  |- num        #ex 숫자 사용시 언더바 사용X
  |- copyright
  |- time       #날짜 및 시간

  강조
  |- emph

  링크
  |- link       #일반 링크
  |- link_more  #더보기 링크

  순서
  |- fst, mid, lst

  팝업
  |- popup

  레이어
  |- layer

  광고
  |- ad

  스페셜
  |- spe

  위젯
  |- widget_소재명

  상세내용
  |- desc

  댓글
  |- cmt

2. subfix // 하부 기호로서 subfix는 prefix와 함께 부가설명 용도로 사용한다.
  |- comm       #공용/ 전역으로만 사용
  |- top/mid/bot/left/right
  |- fst/lst    #순서변화
  |- shadow     #그림자
  |- arr        #화살표
  |- nor        #버튼 상태변화
  |- hori/vert  #방향
  |- cate       #카테고리
  |- rank       #순위

3. suffix // 접미사를 의미하는 것으로, prefix와 함께 부가설명 용도로 사용하며 주로 상태를 나타내는 데 사용된다.
  |- on/off/over/hit/focus  #상태변화
  |- top/mid/bot/left/right #위치변화
  |- fst/lst    #순서변화
  |- prev/next  #이전/다음

4. 조합
  |- prefix-subfix
  |- prefix-subfix-suffix
  |- ex) 2list_notice ( x )

5. id 네이밍 규칙 // 클래스와 이름이 가급적 겹치지 않게
  |- camelcase 방식   #ex)btnSearch

6. 기타
  |- 태그선택자 사용 자제
  |- 탐색레벨을 깊게 써선안됨  ex).article > .foot p > .auth-info
