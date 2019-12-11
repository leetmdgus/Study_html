## HTML이란

***HTML***은 HyperText Markup Language의 약자로 웹 페이지를 위한 마크업 언어다.

 <아래는 html 구조 예시입니다.>

	<html>
	<head>
	    <title>탭의 이름입니다.<title>
		<link href = "style.css" rel = "styleheet" 
		type ="text/css"/>
		<meta name ="description" content = "tmdgus의 문서">
		<style>
			.item {
				color: red;
			}
		</style>
	</head>
	<body>
		<!-- 택스트 관련 태그들 -->
		<h1>크기를 바꿔주는 태그입니다.</h1>
		<h2>크기를 바꿔주는 태그입니다.</h2>
		<h3>크기를 바꿔주는 태그입니다.</h3>
		<h4>크기를 바꿔주는 태그입니다.</h4>
		<h5>크기를 바꿔주는 태그입니다.</h5>
		<h6>크기를 바꿔주는 태그입니다.</h6>
		
		<b>굵은 글씨</b>
		<i>기울은 글씨</i>
		<p>안녕하세요 문맥입니다.</p>
		
		<!-- 미디어 관련 태그 -->
		<img src ="http:///이미지 주소"/>
		<img src ="http:///동영상 주소" controls />
		
		<!-- 링크 관련 태그 -->
		<a href = "google.com">구글</a>
		<a href = "google.com" traget = "_blank">구글</a>
	    
	    <!-- 테이블 관련 태그-->
	    <table border="1">
	    	<thead>
	    		<tr>
	    			<th>컬럼1</th>
	    			<th>컬럼2</th>	
	    		</tr>
	    	</thead>
	    	<tbody>
	    		<tr>
	    			<td>컬럼 1의 내용 1</td>
	    			<td>컬럼 2의 내용 1</td>
	    		</tr>
	    		<tr>
	    			<td>컬럼 1의 내용 2</td>
	    			<td>컬럼 2의 내용 2</td>
	    		</tr>
	    	</tbody>
	    </table>
		<!-- 목록 태그 -->
		<ol>
			<li>1. 첫 번째 목록</li>
			<li>2. 두 번째 목록</li>
		</ol>
		<ul>
			<li>ㅁ 첫 번째 목록</li>
			<li>ㅁ 번째 목록</li>
		</ul>
		<!-- 구역을 나누는 태그 -->
		<div class ="top">상단</div>
		<div class = "mid">중간</div>
		<div class = "bot">하단</div>
		
		<!-- 인풋 태그 -->
		텍스트 <input type= "text" />
		체크박스 <input type ="checkbos"/>
		라디오 <input type = "radio" />
		색깔 <input type="color" />
		여러 문장 <textarea></textarea>
		드랍다운 <select name="name">
			<option value="옵션 1">옵션 1</option>
			<option value="옵션 2">옵션 2</option>
		</select>
	</body>
	</html>
+ ### head

  + #### title

    > 탭의 이름 설정하는 태그

  + #### link

    > 다른 곳에 저장되어 있는 파일들을 html문서에 불러오는 태그 
    >
    > + href 파일의 위치
    > + rel, type 어떤 파일인지 말함

  + #### meta

    > 웹사이트가 어떤 정보를 담고 있는지 알려주는 태그

  + #### style

    > style태그 안에서 css코드를 쓸 수 있게 하는 태그

+ ### body

  + #### 택스트 관련 태그
  
    + ##### h1: 글씨 크기를 제목처럼 바꾸어주는 태그, h6까지 존재
    
    + ##### b: 글씨체를 굵게 합니다.
    
    + ##### i: 기울은 글씨를 쓰게 합니다.
    
    + ##### p: 글의 문단을 나타냅니다. 
    
  + #### 미디어 관련 태그
  
    + ##### img src = "이미지 주소"/
    
      + 동영상일때 img src ="동영상 주소"controls / 를 하면 재생할 수 있다. 
    
  + #### 링크 태그
  
  + #### 테이블 태그
  
    + ##### border: 테두리를 만듦
    
    + ##### thead: 컬럼의 개수를 정함
    
    + ##### tbody: 표의 내용을 정함
    
  + #### 목록 태그
  
  + #### 구역 나누는 태그
  
    + div
  
      > html문서를 여러 구역으로 나누고 싶을 때 사용
      >
      > 한 줄 전체 공간을 차지
  
    + span
  
      > html 문서를 여러 구역으로 나누고 싶을 때 사용
      >
      > 내용물 만큼의 공간 차지
  
  + #### 인풋태그
  
    + 텍스트
    + 체크박스
    + 라디오
    + 색깔
    + 여러 문장
    + 드랍다운

## CSS란 

***CSS*** 란 Cascading Style Sheets로 꾸미는 역할을 담당한다.

	.item{
		color: blue;
	}

