마크다운 사용법 정리
====================

Overview
--------

-	**Why?**
	-	**제일 큰 이유는 내가 필요해서**
	-	빠르게 배우고 싶은 사람들을 위해 정리
	-	항상 써먹지 않으면 잊어먹을 수 있는 걸 기록하여 상기시키도록

### Content

-	#### Basic
    - **제목 쓰기**
    	<pre>
      <code>
      # 제목1
      ## 제목2
      ### 제목3
      #### 제목4
      ##### 제목5
      ###### 제목6
      </code></pre>
    - **인용구**
      <pre><code> > 인용 Text
      </code></pre>
    - **목록**
      <pre><code>
      + 가능한 기호
      - 가능한 기호
      * 이것도 가능함
        + 서브 목록은 이렇게
        - 이거도
        * 가능하다
          1. 번호도          
          2. 가능함</code></pre>       
    - **이텔릭 스타일**
      <pre><code>*이텔릭 스타일*  
      _이텔릭 스타일_</code></pre>
       - EX : *이텔릭*, _이텔릭_
    - **강조**
      <pre><code>**highlight**
      </code></pre>
    - **Escape**
      <pre><code>마크다운에 사용하는 기호를 텍스트로 표기할 땐 \을 붙여 표기
      \\ 백슬래시
      \` backtick
      \* 아스테리스크
      \_ 언더바
      \{\} 중괄호
      \[\] 대괄호
      \(\) 소괄호
      \# 샾
      \+ 플러스 기호
      \- 마이너스 기호
      \. 닷 기호
      \! 느낌표
      </code></pre>
    - **코드**
      `<code> 코드 블럭 형식 </code>`
    - **취소선**
      <code> `~~취소선~~` ->  ~~취소선~~ </code>
    - **테이블**
      <pre><code>
      | Left-Aligned  | Center Aligned  | Right Aligned |
      | :------------ |:---------------:| -------------:|
      | col 3 is      | some wordy text | $1600         |
      | col 2 is      | centered        |   $12         |
      | zebra stripes | are neat        |    $1         |
      </code></pre>
      | Left-Aligned  | Center Aligned  | Right Aligned |
      | :------------ |:---------------:| -------------:|
      | col 3 is      | some wordy text | $1600         |
      | col 2 is      | centered        |   $12         |
      | zebra stripes | are neat        |    $1         |
    - **체크박스**
      - [ ] -> `[ ]` _unchecked_
      - [x] -> `[x]` _checked_
    - **외부링크**
      `[구글](http://www.google.com)` -> [구글](http://www.google.com)
      `http://www.google.com` -> http://www.google.com
    - **참조링크**
      `[참조1] [참조1]:http://google.com` ->  
      [ref]
      [ref]:http://www.google.com
    - **이미지링크**
      `![이미지](링크주소)` ->  
      ![이미지](https://pbs.twimg.com/profile_images/994409572117790720/NF8KMjNX_400x400.jpg)
  - #### 응용법
