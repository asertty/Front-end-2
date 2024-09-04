## 오늘 한 내용
저번시간에 배웠던거 이여서 배워 html과 css를 복습하는 시간을 가졌다.

![image](https://github.com/user-attachments/assets/113cc813-8137-41b6-b81e-d00341cdea07)

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
