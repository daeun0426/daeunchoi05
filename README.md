# daeunchoi05
<!doctype html>
<html lang="ko">
<head>
	<title>온라인 프로필</title>
	<meta charset="utf-8">
  <link rel="stylesheet" href="css/style.css">
  <style>
    table {
      width:70%;  /* 표의 너비 */
      border:1px solid #222; /* 1픽셀짜리 표 테두리 */
      border-collapse: collapse; /* 중복되는 표와 셀의 테두리를 한 줄로 표시 */
    }
    thead {
      background:#eee;  /* 제목 행의 배경 색 */
    }
    th, td {
      border:1px solid #ccc; /* 1픽셀짜리 셀 테두리 */
      padding:5px;  /* 셀 테두리와 셀 내용 사이의 여백(패딩) */
      font-size:0.8em;  /* 셀의 글자 크기 */
    }
  </style>
</head>

<body>
    <div id="container">
        <!-- 사이드바 -->
        <aside>
            <div id="namecard">
                <img src="images/pf.jpg" alt="">
                <h1>daeun choi</h1>    
                <p>오늘은 남은 인생이 시작되는 첫째날</p>
            </div>
            <div id="detail">
                <p> </p>                                 
            </div>
            <div iㅊd="sns">
                <ul>                    
					<li>
						<a href="https://www.facebook.com/funnycom">github</a>
					</li>
					<li>
						<a href="https://www.google.com/search?q">google</a>
					</li>
				</ul>  
                <h2></h2>
  
            </div>           
        </aside>
        <div id="main">
            <!-- 자기 소개 -->
            <section>
                <h2 class="subtitle">Who am I?</h2>
                <p><mark>나는 음악 듣는것에 관심이 많습니다. <br>현재 영광의 한 시골 마을에서 코딩 중입니다.</p>
            </section>

            <!-- 경력 -->
            <section>
                <h2 class="subtitle">Experience</h2>
                <ul>
                    <li>세븐틴
                        <ul>
                            <li>멤버 </li>
                            <li>캐럿 </li>
                            <li>공연일정</li> 
                        </ul>
                    </li>
                    <li>미스터트롯
                        <ul>
                            <li> 멤버 </li>
                            <li>방송일정</li>
                        </ul>                        
                    </li>
                </ul>             
            </section>

            <!-- 숙련도 -->
            <section>
                <h2 class="subtitle">Skills</h2>

            </section>

            <!-- 학력 -->
            <section>
                <h2 class="subtitle">Education</h2>
                <table>
                  <caption>학력 사항</caption>
                  <thead>
                      <tr>
                          <th>홍농초등학교</th>
                          <th>홍농중학교</th>
                          <th>전공</th>
                          <th>기간</th>
                          <th>구분</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>ㅁㅁ대학교</td>
                          <td>컴퓨터공학</td>
                          <td>2004.3 ~ 2008.2</td>
                          <td>졸업</td>
                      </tr>
                      <tr>
                          <td>영광 공업고등학교</td>
                          <td> - </td>
                          <td>2001.3 ~ 2004.2</td>
                          <td>졸업</td>
                      </tr>
                  </tbody>-*/
                </table>
            </section>
        </div>        
    </div>
</body>
</html>
