<!DOCTYPE html>
<html>
  <head>
    <title>HOME</title>
    <style>
      @import url(writing.css);
      @import url(order.css);
      #top-button {
        width: 860px;
        height: 50px;
      }
      #top-button > div {
        float: right;
        margin: 10px 0px;
      }
      #contents {
        display: inline-block;
        padding:29px 29px 0px;
        width: 860px;
        
        border: 1px solid;
        border-color: rgba(196, 196, 196, 0.966);
        border-radius: 6px 6px;
        box-sizing  : border-box;
      }
      #contents-title{
        margin: 0px 0px 20px;
        padding: 0px 0px 20px;
        border-bottom: 1px solid;
        border-color: rgba(196, 196, 196, 0.966);
      }
      #writing-list {
        display: inline-block;
      }
      .code > span{
        color:purple;
      }
    </style>
    <script>
      function writeStr(str){
        document.write(str);
      }

    </script>
  </head>
  <body link="black" vlink="black" alink="navy">
    <div id="top"></div>
    <div id="nb1">
      <div id="home">
        <a class="home" href="../index.html">
          <img
            src="../img/onmouseout.png"
            alt="homeImg"
            height="40"
            onmouseover="this.src='../img/onmouseover.png'"
            onmouseout="this.src='../img/onmouseout.png'"
          />
        </a>
      </div>
      <div id="grapics">
        <a class="grapics" href="grapics.html"
          ><span style="font-family: 'Malgun Gothic'; font-size: 1.5em"
            ><b>grapics</b></span
          ></a
        >
      </div>
      <div id="algorithm">
        <a class="algorithm" href="algorithms.html"
          ><span style="font-family: 'Malgun Gothic'; font-size: 1.5em"
            ><b>algorithm</b></span
          ></a
        >
      </div>
      <div id="muchineLearning">
        <a class="muchineLearning" href="muchineLearning.html"
          ><span style="font-family: 'Malgun Gothic'; font-size: 1.5em"
            ><b>muchine Learning</b></span
          ></a
        >
      </div>
    </div>
    <hr />
    <div id="front"></div>
    <div id="search">
      <div id="form_">
        <form name="search">
          <input name="query" type-="text" />
          <button type="button">검색</button>
        </form>
      </div>
    </div>
    <div id="content-area">
      <div id="group-area">
        <div id="border">
          <div id="header"><h3>카테고리</h3></div>
          <div id="border-body">
            <div>
              <ul id="body-list">
                <li><a href="index.html">전체글 보기</a></li>
                <li><a href="index.html">전체글 보기</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div id="main-area">
        <div id="top-button">
          <div>
            <button type="button">이전글</button>
            <button type="button">다음글</button>
            <button type="button">목록</button>
          </div>
        </div>
        <div id="contents">
            <div id="contents-title">
                <span style="font-size: 30px;"><b>자바스크립트 공부</b></span>
            </div>
            <div id="contents-body">
              <span style="font-family: 'Malgun Gothic'; font-size: 40;">
                
            </div>
            
        </div>
        <div id="writing-list">
            
            <table id="main-table">
              <thead>
                <tr>
                  <th colspan="2">
                    <div id="table-top">글제목</div>         
                  </th>
                </tr>
              </thead>
              <tbody id="table-body">
                <tr id="tr2" class="item2">
                    <td id="table-title"><a href="javascripts-study.html"><div>새글</div></td>
                    <td id="table-date"><div>22.12.22</div></td>
                  </tr>
                <tr id="tr1" class="item1">
                  <td id="table-title"><a href="javascripts-study.html"><div>자바스크립트 공부</div></td>
                  <td id="table-date"><div>22.12.22</div></td>
                </tr>
                
                
              </tbody>
            </table>
        </div>
      </div>
    </div>
  </body>
</html>
