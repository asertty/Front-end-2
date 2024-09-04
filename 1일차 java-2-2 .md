### 전에 배운 웹페이지 만들기 복습

1. <!DOCTYPE html> 은 html5 버전이다.
2. <html lang="ko">은 lang 이라는 속석인데 변역과도 연관이 있다. 
3. <title> 타이클 태그
4. ul태그는 학급의 반을 나누는 거 처럼 관리하기 위해 리스트를 만드는 걸 말한다. 
5. a 태그는 href속성을 이용해 링크를 건다.
6. img 태그는 경로(속성)에 있는 이미지를 출력한다. ait는 이미지가 없을때 나오는 엑박(그림)이나 텍스트
7. h태그는 html을 열때 가장 부터 탐색한다.(+크기가 크고 굵은 글씨체를 가졌다.)


1. css의 우선순위는 큰 순에서 작은 순이다 예를 들면 *는 전체 h1는 *안에 있는 h1이며 h1이 우선순위를 갖게 된다.(우선순위 id<class)


수업했던 코드
-
    
       </li> <!DOCTYPE html>
        <html lang="ko">
        <head>
            <meta charset="UTF-8">
            <title>sdmhls</title>
            <link rel="stylesheet" href="css.css">
        </head>
        <body>
            <header>
                <img src="main_img.png" alt="그림 없음">
            </header>
            
            <nav>
                <ul>
                    <li><a href="#">학교소개 |</a></li>
                    <li><a href="#">학과소개 |</a></li>
                    <li><a href="#">입학안내 |</a></li>
                    <li><a href="#">학교생활 |</a></li>
                    <li><a href="#">열린학교 |</a></li>
                </ul> 
            </nav>
            <section>
                
                    <h1>+학교소개</h1>
        
                    <ol>
                        <li>
                            
                            <h3>1. 견학이념</h3>
                            <div>
        
                                <table>
                                    <tr>
                                        <td>설립자훈</td>
                                        <td>대망과 신념을 지닌 인간상 구현</td>
                                    </tr>
                                    <tr>
                                        <td>교훈</td>
                                        <td>성실한 사람, 실력 있는 사람, 생산적인 사람</td>
                                    </tr>
                                </table>
        
                            </div>
                        </li>
                        <li>
                            
                            <h3>2. 학교상징</h3>
                            <ul>
        
                                <li>교화 : 철쭉 - 사랑의 기쁨</li>
                                <li>교목 : 은행나무 - 용기, 진취적임, 풍요로운 결실</li>
                                <li>교조 : 독수리 - 도전정신</li>
        
                            </ul>    
        
                        </li>
                             <h3>3. 오시는 길</h3>
                            <img src="map.png" alt="">
        
                        <li>
        
                            
                    </ol>    
        
            </section>
        
        
        </body>
</html>

