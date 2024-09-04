## 오늘 한 내용
저번시간에 배웠던거 이여서 배워 html과 css를 복습하는 시간을 가졌다.

![image](https://github.com/user-attachments/assets/113cc813-8137-41b6-b81e-d00341cdea07)

복습 화면

<details>
  
    @charset "utf-8";
    
    /* CSS(Cascading Style Sheet) */
    /* 선택자가 중요하다 */
    *{
        font-family: "굴림";
        margin: 0 auto;
        text-decoration: none;
        color: #333;
        list-style: none;
    }
    h1{
        font-family: "함초롬바탕";
        clear: both;
        margin: 20px;
    }
    .클래스{
        font-family: "궁서체";
    }
    #아이디{
        font-family: "바탕체";
        color: red;
    }
    /* 아이디가 여러개일때 */
    img{
        display: block;
    }
    
    ul{
        width: 100%;
        height:  40px;
        list-style: none;
    }
    
    ul>li{
        float: left;
        line-height: 20px;
        height: 40%;
        margin: 0 20px;
    }
    
    ol{
        width: 100%;
        height: 40px;
        margin-left: 50px;
    }
    
    table{
        margin: 10px;
    }
    
    table, td{
        border: 1px solid black;
        border-collapse: collapse;
        padding: 10px 20px;
    }
    
    .symbol li{
        list-style: url("logo.png");
    }

</details>

<details>
  
![image](https://github.com/user-attachments/assets/4c060866-acea-4512-a5ba-37712ce8df62)

![image](https://github.com/user-attachments/assets/0613bff0-d2cd-4c02-b503-8b26a873a9df)

![image](https://github.com/user-attachments/assets/8c28cdb3-2cbb-436a-85bb-b3e6db1f36b2)

![image](https://github.com/user-attachments/assets/0162d962-f3c3-4ec4-8d5a-d3968cdcd63f)


      /* 1번 화면
        .one{
            box-sizing: border-box; 전체크기를 우선시 한다 
        } 
        .two{
            box-sizing: content-box; 콘텐츠의 크기를 우선시 한다 
        } 
         */
  
        /* 2번 화면
        .one{
            background-color: red;float: left;
        }
        .two{
            background-color: orange;
        }
        .three{
            background-color: yellow;
        } */

        /* 3번 화면
        .one{
            background-color: red;float: left;
        }
        .two{
            background-color: orange;float: left;
        }
        .three{
            background-color: yellow;float: left;
        }*/

        /* 4번째 화면
           .boomo{
                width: 432px;
                height: 150px;
                background-color: green;
            }
        */
</details>

<details>

    <!DOCTYPE html>
    <html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>MAR</title>
        <style>
            
            div{
                width: 100px;
                height: 100px;
                border: 2px solid black;
                background-color: gold;
                border-radius: 1pc;
                margin: 10px;
                padding: 10px;
            }
            /* 1번 화면
            .one{
                box-sizing: border-box; 전체크기를 우선시 한다 
            } 
            .two{
                box-sizing: content-box; 콘텐츠의 크기를 우선시 한다 
            } 
            */
    
            
            .one{
                background-color: red;float: left;
            }
            .two{
                background-color: orange;float: left;
            }
            .three{
                background-color: yellow;float: left;
            } 
            .boomo{
                width: 432px;
                height: 150px;
                background-color: green;
            }
    
    
        </style>
    </head>
    <body>
        <div class="boomo">
            
            <div class="one"> 
            </div>
    
            <div class="two">
            </div>
        
            <div class="three">   
            </div>
        </div>
    
    </body>
    
</details>
