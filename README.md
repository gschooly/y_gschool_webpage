<!DOCTYPE html>
<html>

<head>
  <meta charset='utf-8'>
  <meta http-equiv='X-UA-Compatible' content='IE=edge'>
  <title>(사)교육실험실21</title>
  <meta name='viewport' content='width=device-width, initial-scale=1'>
  <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
  <script src="https://kit.fontawesome.com/becfdfcff8.js" crossorigin="anonymous"></script>
  <script src='main.js'></script>
  <style>
    @import url(//fonts.googleapis.com/earlyaccess/nanumgothic.css);

    .nanumgothic * {
      font-family: 'Nanum Gothic', sans-serif;
    }

    .header {
      display: flex;
      justify-content: space-around;
      padding-left: 15px;
      padding-right: 15px;
      height: 90px;
    }

    .head {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .head:nth-child(1) {
      padding-bottom: 10px;
      padding-left: 10px;
      flex: 1;
    }

    .head:nth-child(2) {
      justify-content: space-evenly;
      padding-bottom: 10px;
      flex: 2;
    }

    .head:nth-child(3) {
      padding-bottom: 10px;
      flex: 1;
    }

    .gschool {
      font-family: "Nanum Gothic";
      font-size: 27px;
    }

    .contents {
      font-size: 15px;
    }

    .contents:hover {
      color: mediumblue;
    }

    .box {
      font-size: 13px;
      color: gray;
      border: 1px solid gray;
      padding-top: 10px;
      padding-bottom: 10px;
      padding-left: 30px;
      padding-right: 30px;
      -moz-transition: all, 0.5s;
      -o-transition: all, 0.5s;
      -webkit-transition: all, 0.5s;
      transition: all, 0.5s;
    }

    .box:hover {
      background-color: navy;
      color: white;
    }

    .video {
      height: 550px;
      width: 100vw;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }

    #videoIFrame {
      height: 100vw;
      width: 100vw;
    }

    .introduce {
      height: 120px;
      margin-top: 50px;
      margin-bottom: 65px;
    }

    .main_text {
      font-size: 27px;
    }

    .sub_text {
      font-size: 15px;
      color: gray;
      position: relative;
      top: 25px;
      line-height: 25px;
    }

    .box_contents {
      display: flex;
      justify-content: center;
    }

    .bluebox {
      background-color: mediumblue;
      height: 215px;
      width: 350px;
    }

    .navy_box {
      background-color: navy;
      height: 215px;
      width: 350px;
    }

    .box_contents_text {
      padding-top: 30px;
      padding-left: 25px;
      color: white;
    }

    .box_contents_main_text {
      font-size: 17px;
      margin-bottom: 6px;
    }

    .box_contents_sub_text {
      font-size: 14px;
      line-height: 25px;
    }

    .box_contents_arrow {
      font-size: 12px;
      margin-top: 65px;
    }
  </style>
</head>

<body>
  <div class="header">
    <div class="head">
      <div class="gschool"><strong>거꾸로캠퍼스</strong></div>
    </div>
    <div class="head">
      <div class="contents">연구 원칙</div>
      <div class="contents">연구 과정</div>
      <div class="contents">연구 활동</div>
      <div class="contents">법인소식</div>
      <div class="contents">거꾸로캠퍼스 소개</div>
    </div>
    <div class="head">
      <div class="box"><i class="far fa-edit"></i> 입학 상담 및 지원</div>
    </div>
  </div>
  <div class="video">
    <iframe id="videoIFrame"
      src="https://player.vimeo.com/video/427031436?title=0&muted=1&autoplay=1&autopause=0&controls=0&loop=1&background=1&app_id=122963&autoplay=1"
      frameborder="0"></iframe>
  </div>
  <center>
    <div class="introduce">
      <div class="main_text"><strong>새로운 시대를 열어갈 다음 세대를 위한 새로운 학교</strong></div>
      <div class="sub_text">사단법인 교육실험실21의 거꾸로캠퍼스는 21세기 학습자를 위한 미래 역량 중심 교육을 제공하는 실험 학교입니다.<br> 미래 사회에서 주체적인 삶을 살며 협력을 통해
        긍정적인 변화를 이끄는 인재를 양성합니다.</div>
    </div>
  </center>
  <div class="box_contents">
    <div class="bluebox">
      <div class="box_contents_text">
        <div class="box_contents_main_text"><strong>배움의 원칙</strong></div>
        <div class="box_contents_sub_text">거꾸로캠퍼스가 실현하는<br>21세기 배움의 원칙 아홉 가지</div>
        <div class="box_contents_arrow"><strong>자세히보기</strong> <i class="fas fa-long-arrow-alt-right"></i></div>
      </div>
    </div>
    <div class="navy_box">
      <div class="box_contents_text">
        <div class="box_contents_main_text"><strong>교육과정</strong></div>
        <div class="box_contents_sub_text">거꾸로캠퍼스의 교육 과정과<br>교육 프로그램에 대한 안내</div>
        <div class="box_contents_arrow"><strong>자세히보기</strong> <i class="fas fa-long-arrow-alt-right"></i></div>
      </div>
    </div>
    <div class="bluebox">
      <div class="box_contents_text">
        <div class="box_contents_main_text"><strong>학교생활</strong></div>
        <div class="box_contents_sub_text">거꾸로캠퍼스를 만들어가는<br>학생과 교사들의 이야기</div>
        <div class="box_contents_arrow"><strong>자세히보기</strong> <i class="fas fa-long-arrow-alt-right"></i></div>
      </div>
    </div>
  </div>
</body>

</html>