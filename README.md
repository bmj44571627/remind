<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Resoft</title>
    <link rel="shortcut icon" href="./image/web.png" type="image/x-icon" />
    <link rel="stylesheet" href="./css/header.css" />
    <link rel="stylesheet" href="./css/icon.css" />
    <link rel="stylesheet" href="./css/item.css" />
    <link rel="stylesheet" href="./css/animate.css" />
    <link rel="stylesheet" href="./css/biglogo.css" />
    <link rel="stylesheet" href="./css/map.css" />
    <link rel="stylesheet" href="./css/top.css" />
    <link rel="stylesheet" href="./css/card.css" />
    <link rel="stylesheet" href="./css/footer.css" />

    <link rel="stylesheet" type="text/css" href="./css/slide card.css" />
    <link rel="stylesheet" type="text/css" href="./css/slick.css" />
    <link rel="stylesheet" type="text/js" href="./css/reset.css" />
    <link rel="stylesheet" type="text/js" href="./css/animate.css" />
    <link rel="stylesheet" type="text/js" href="./css/jquery.bxslider.css" />

    <script src="./js/wow.min.js"></script>
    <script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.js"></script>
    <script src="./js/jquery.bxslider.min.js"></script>
    <script src="./js/wow.min.js"></script>
    <script>
      new WOW().init();
    </script>
    <script
      type="text/javascript"
      src="https://dapi.kakao.com/v2/maps/sdk.js?appkey=841c3df5b9304ec5a4a4a954d55bd878"
    ></script>
    <script
      charset="UTF-8"
      src="http://t1.daumcdn.net/mapjsapi/js/main/4.4.5/kakao.js"
    ></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
      integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="./css/bootstrap.min.css" />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2"
      crossorigin="anonymous"
    ></script>
    <script src="./js/bootstrap.bundle.js.map"></script>
  </head>

  <body>
    <!-- 탑 버튼 시작-->
    <div id="top">
      <button class="move">
        <!-- 헤더 만드신 분 헤더로 연결시키면 헤더(TOP)로 이동 -->
        <a href="#"><i class="fa-solid fa-angle-up"></i></a>
        <p>TOP</p>
      </button>
    </div>
    <!-- 탑 버튼 끝 -->

    <header class="header">
      <div class="wrapper">
        <div class="top_wrap">
          <div class="img-wrap">
            <a href="/"><img src="./image/리소프트로고.png" alt="logo" /></a>
          </div>
        </div>
      </div>
      <div class="banner-wrap">
        <div class="bannerText-wrap wow fadeInLeft" data-wow-delay="0.3s">
          <div class="bannerText">
            <p>
              Evolution<br />
              With New Software
            </p>
            <p>
              <span>Mobile APP(Android/iOS) Development, </span
              ><span>AI Bigdata Analysis, MetaVerse, </span>
              <span
                ><span>Responsive WEBsite, Brand Design Launch, </span
                ><span>ICT Consulting</span></span
              >
            </p>
          </div>
        </div>
        <div class="img-wrap">
          <img
            src="./image/메인뇌.png"
            alt=""
            class="wow fadeInRight"
            data-wow-delay="0.5s"
          />
        </div>
      </div>
    </header>

    <!-- card섹션 -->
    <div class="wrap">
      <div class="content_wrap">
        <ul class="business_list">
          <div class="flip">
            <li class="front flip-item">
              <a href="javascript:void(0);">
                <p class="title">앱(APP) 개발</p>
                <p class="subTitle">android/ios app</p>
                <div class="image _wrap">
                  <img src="./image/앱개발아이콘.png" />
                </div>
              </a>
            </li>
            <div class="back flip-item">
              <a
                href="javascript:void(0)"
                id="test"
                onclick="preventClick(event)"
                class="layoutimage"
              ></a>
              <img src="./image/앱개발.jpg" style="height: 100%; width: 100%" />

              <div class="text">
                Android 앱 개발 <br />iOS 앱 개발 <br />플랫폼 기획 및 설계
              </div>
            </div>
          </div>

          <div class="flip">
            <li class="front flip-item">
              <a href="javascript:void(0);">
                <p class="title">웹(WEB) 구축</p>
                <p class="subTitle">responsive web</p>
                <div class="image _wrap">
                  <img src="./image/web.png" />
                </div>
              </a>
            </li>
            <div class="back flip-item">
              <a
                href="javascript:void(0)"
                id="test"
                onclick="preventClick(event)"
                class="layoutimage"
              ></a>
              <img src="./image/웹구축.jpg" style="height: 100%; width: 100%" />

              <div class="text">
                반응형 홈페이지 구축 <br />데이터베이스 구축 <br />빅데이터 구축
              </div>
            </div>
          </div>

          <div class="flip">
            <li class="front flip-item">
              <a href="javascript:void(0);">
                <p class="title">AI 기반 기술개발</p>
                <p class="subTitle">ai bigdata</p>
                <div class="image _wrap">
                  <img src="./image/bigdata.png" />
                </div>
              </a>
            </li>
            <div class="back flip-item" ;>
              <a
                href="javascript:void(0)"
                id="test"
                onclick="preventClick(event)"
                class="layoutimage"
              ></a>
              <img
                src="./image/AI기술개발.jpg"
                style="height: 100%; width: 100%"
              />

              <div class="text">
                AI 대화형 챗봇 <br />자동 객체인식 검출기 <br />딥러닝 학습 모델
              </div>
            </div>
          </div>
          <div class="flip">
            <li class="front flip-item">
              <a href="javascript:void(0);">
                <p class="title">XR 콘텐츠 구현</p>
                <p class="subTitle">metaverse</p>
                <div class="image _wrap">
                  <img src="./image/metaverse.png" />
                </div>
              </a>
            </li>
            <div class="back flip-item">
              <a
                href="javascript:void(0)"
                id="test"
                onclick="preventClick(event)"
                class="layoutimage"
              ></a>
              <img
                src="./image/XR콘텐츠.jpg"
                style="height: 100%; width: 100%"
              />

              <div class="text">
                실감형 플랫폼 구축<br />가상현실 콘텐츠 제작<br />게임콘텐츠제작
              </div>
            </div>
          </div>
        </ul>
      </div>
    </div>

    <script>
      $(document).ready(function () {
        $("#slide3>ul>li").hide();
        $("#slide3>ul>li:first-child").show();
        setInterval(function () {
          $("#slide3>ul>li:first-child")
            .fadeOut()
            .next()
            .fadeIn()
            .end(5000)
            .appendTo("#slide3>ul");
          $("#slide_title1").toggle();
          $("#slide_title2").toggle();
        }, 6000);

        var active_num = $("input:radio[name=tab]:checked").val();

        $("input:radio[name=tab]").change(function () {
          /* var chk_tab = $(":input:radio[name=tab]:checked").val();
    
    $(".content1_wrap").hide();
    $("#con"+chk_tab).show(); */

          var click_num = $(this).val();

          //alert("active_num : "+active_num+", click_num : "+click_num);

          if (active_num - click_num > 0) {
            prev(active_num - click_num);
          } else if (active_num - click_num < 0) {
            next(click_num - active_num);
          }

          active_num = click_num;
        });

        $(".news_list").slick({
          slidesToShow: 4,
          slidesToScroll: 1,
          autoplay: true,
          autoplaySpeed: 3000,
          arrows: false,
          dots: false,
          pauseOnHover: false,
          responsive: [
            {
              breakpoint: 940,
              settings: {
                slidesToShow: 3,
              },
            },
            {
              breakpoint: 767,
              settings: {
                slidesToShow: 2,
              },
            },
            {
              breakpoint: 430,
              settings: {
                slidesToShow: 1,
              },
            },
          ],
        });
      });

      function prev(cnt) {
        var move_width = 1910 * cnt;

        $(".content_slide").css({
          left: "-=" + move_width + "px",
        });

        for (var i = 0; i < cnt; i++) {
          $(".content_slide")
            .children(":last")
            .insertBefore($(".content_slide").children(":first")); // first 이전에 last 삽입
        }

        /* $(".content_slide").stop(true).animate({left : "0"}, 500, function() {
    $(this).css({left : "0"});
}); */

        $(".content_slide").stop(true).css({
          opacity: 0,
          left: "0",
        });
        $(".content_slide").stop(true).animate(
          {
            opacity: 1,
          },
          500
        );
      }

      function next(cnt) {
        var move_width = 1910 * cnt;

        for (var i = 0; i < cnt; i++) {
          $(".content_slide")
            .children(":first")
            .insertAfter($(".content_slide").children(":last"));
        }
        $(".content_slide").stop(true).css({
          opacity: 0,
          left: "0",
        });
        $(".content_slide").stop(true).animate(
          {
            opacity: 1,
          },
          500
        );
      }

      var fileArr = new Array();
      var noImg = false;

      function fnDetail(flag, idx) {
        window.location.href =
          "user/boardDetailDir.action?flag=" + flag + "&idx=" + idx;
      }
    </script>
    <div class="news_wrap">
      <div class="news_content_wrap">
        <div class="title tit_center">
          <h2 class="h_tit">프로젝트</h2>
          <p class="subTitleEng">resoft projects</p>
        </div>
        <div class="btn_wrap">
          <!-- <a href="#" class="more"><span>more</span></a> -->
        </div>
      </div>

      <div class="container_slide">
        <section class="news_list slider">
          <div class="slide">
            <a href="javascript:void(0);">
              <div
                class="new_img"
                style="height: 300px; background-color: #ffffff"
              >
                <div class="cont">
                  <p class="work-title">
                    송파구청 송파둘레길 비대면 걷기대회<br />
                  </p>
                  <img class="logo" src="./image/송파둘레길.png" alt="[APP]" />
                </div>
              </div>
            </a>
          </div>

          <div class="slide">
            <a href="javascript:void(0);">
              <div
                class="new_img"
                style="height: 300px; background-color: #ffffff"
              >
                <div class="cont">
                  <p class="work-title">대구인문사회대학<br /></p>
                  <img class="logo" src="./image/inmun_logo.png" alt="[WEB]" />
                </div>
              </div>
            </a>
          </div>

          <div class="slide">
            <a href="javascript:void(0);">
              <div
                class="new_img"
                style="height: 300px; background-color: #ffffff"
              >
                <div class="cont">
                  <p class="work-title">
                    제15회 달서 하프 비대면 마라톤대회<br />
                  </p>
                  <img
                    class="logo"
                    src="./image/달서구청로고.png"
                    alt="[APP]"
                  />
                </div>
              </div>
            </a>
          </div>

          <div class="slide">
            <a href="javascript:void(0);">
              <div
                class="new_img"
                style="height: 300px; background-color: #ffffff"
              >
                <div class="cont">
                  <p class="work-title">
                    제8회 한성백제 비대면 마라톤대회<br />
                  </p>
                  <img
                    class="logo"
                    src="./image/한성백제마라톤.png"
                    alt="[APP]"
                  />
                </div>
              </div>
            </a>
          </div>

          <div class="slide">
            <a href="javascript:void(0);">
              <div
                class="new_img"
                style="height: 300px; background-color: #ffffff"
              >
                <div class="cont">
                  <p class="work-title">
                    2020 대구 마스크 쓰GO 코로나 극복 레이스<br />
                  </p>
                  <img
                    class="logo"
                    src="./image/컬러풀대구로고.jpg"
                    alt="[APP]"
                  />
                </div>
              </div>
            </a>
          </div>
        </section>
      </div>
    </div>

    <div class="cus_wrap">
      <!-- data-wow-delay : 페이지 로딩 후 애니메이션이 실행되기까지 간격-->
      <img
        src="./image/에코스봇.png"
        alt=""
        class="ecoce-bot wow fadeInDown"
        data-wow-delay="0.3s"
      />

      <img
        src="./image/환경부탄소중립기본법.png"
        alt=""
        class="ministry-Environ-img wow fadeInRight"
        data-wow-delay="0.3s"
      />

      <div class="ecoce-img-wrap">
        <img
          src="./image/에코스모바일원.png"
          alt=""
          class="ecoce-img wow fadeInLeft"
          data-wow-delay="0.3s"
        />
      </div>

      <div class="eco-clean-earth wow fadeInRight" data-wow-delay="0.6s">
        <p>
          국내 최초<br />
          '탄소중립 실천인증 플랫폼'
        </p>
        <p>ECO-Clean Earth</p>
      </div>
    </div>

    <div class="box_wrap">
      <div class="img_btn">
        <img
          src="./image/리소프트로고_big.png"
          alt=""
          class="wow fadeInDown"
          data-wow-delay="0.3s"
        />
        <div class="box_btn btn-holder"></div>
      </div>
    </div>

    <div class="customer_icon">
      <ul>
        <li class="wow fadeInUp customer_list" data-wow-delay="0.1s">
          <div class="img-wrap">
            <img src="./image/대구광역시 건축사회.png" alt="" />
          </div>
          <p>대구광역시 건축사회</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.2s">
          <div class="img-wrap">
            <img src="./image/대구광역시.png" alt="" />
          </div>
          <p>대구광역시</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.3s">
          <div class="img-wrap">
            <img src="./image/매일신문.png" alt="" />
          </div>
          <p>매일신문</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.4s">
          <div class="img-wrap">
            <img src="./image/경북대학교.png" alt="" />
          </div>
          <p>경북대학교</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.5s">
          <div class="img-wrap">
            <img src="./image/대구MBC문화원.png" alt="" />
          </div>
          <p>대구MBC문화원</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.6s">
          <div class="img-wrap">
            <img src="./image/대구광역시 체육회.png" alt="" />
          </div>
          <p>대구광역시 체육회</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.7s">
          <div class="img-wrap">
            <img src="./image/대구가톨릭대학교.png" alt="" />
          </div>
          <p>대구가톨릭대학교</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.8s">
          <div class="img-wrap">
            <img src="./image/송파구청.png" alt="" />
          </div>
          <p>송파구청</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="0.9s">
          <div class="img-wrap">
            <img src="./image/국민의힘.png" alt="" />
          </div>
          <p>국민의힘</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.8s">
          <div class="img-wrap">
            <img src="./image/국제라이온스협회.png" alt="" />
          </div>
          <p>국제라이온스협회</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.7s">
          <div class="img-wrap">
            <img src="./image/한국전기공사협회.png" alt="" />
          </div>
          <p>한국전기공사협회</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.6s">
          <div class="img-wrap">
            <img src="./image/즐거운세상.png" alt="" />
          </div>
          <p>(주)즐거운 세상</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.5s">
          <div class="img-wrap">
            <img src="./image/해양대학교.png" alt="" />
          </div>
          <p>한국해양대학교</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.4s">
          <div class="img-wrap">
            <img src="./image/상공회의소.png" alt="" />
          </div>
          <p>대구상공회의소</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.3s">
          <div class="img-wrap">
            <img src="./image/대한건설협회.png" alt="" />
          </div>
          <p>대한건설협회</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.2s">
          <div class="img-wrap">
            <img src="./image/한국청년회의소.png" alt="" />
          </div>
          <p>한국청년회의소</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.1s">
          <div class="img-wrap">
            <img src="./image/계명대.png" alt="" />
          </div>
          <p>계명대학교</p>
        </li>

        <li class="wow fadeInUp customer_list" data-wow-delay="1.0s">
          <div class="img-wrap">
            <img src="./image/목포해양대학교.png" alt="" />
          </div>
          <p>목포해양대학교</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.0s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/대구공고.png" alt="" />
          </div>
          <p>대구공업고등학교</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.1s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/대경산업협회.png" alt="" />
          </div>
          <p>대경ICT산업협회</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.2s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/한국조리기능장협회.png" alt="" />
          </div>
          <p>한국조리기능장협회</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.3s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/여성기업인협회.png" alt="" />
          </div>
          <p>IT여성기업인협회</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.4s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/중소기업융합연합회.png" alt="" />
          </div>
          <p>중소기업융합연합회</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.5s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/대구신용보증재단.png" alt="" />
          </div>
          <p>대구신용보증재단</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.6s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/달서구청.png" alt="" />
          </div>
          <p>달서구청</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.7s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/대구디지털산업진흥회.png" alt="" />
          </div>
          <p>대구디지털산업진흥원</p>
        </li>

        <li
          class="wow fadeInUp customer_list"
          data-wow-delay="2.8s"
          data-wow-offset="-30"
        >
          <div class="img-wrap">
            <img src="./image/국제라이온스협회.png" alt="" />
          </div>
          <p>국제로타리클럽</p>
        </li>
      </ul>

      <button class="load"><i class="fa-solid fa-circle-plus"></i></button>
    </div>

    <script>
      // 아이콘 8개
      if (window.matchMedia("screen and (max-width: 1217px)").matches) {
        $(function () {
          $(".customer_list").hide();
          var array = [];
          var list = document.getElementsByClassName("customer_list");

          for (var i = 0; i < list.length; i++) {
            array.push(list[i]);
          }

          var visiArray = [];
          visiArray = array.slice(0, 8);
          visiArray = visiArray.concat(array.slice(8, 16).reverse());
          visiArray = visiArray.concat(array.slice(16, 24));

          var second = 0;
          for (var i = 0; i < visiArray.length; i++) {
            second = second + 0.1;
            visiArray[i].setAttribute("data-wow-delay", second + "s");
            visiArray[i].style.display = "block";
          }

          var load = document.getElementsByClassName("load")[0];
          //숨겨진 아이콘
          load.addEventListener("click", function (e) {
            e.preventDefault();
            var hiddenArray = [];
            hiddenArray = array.slice(24, 27);

            var hSecond = 0;
            for (var i = 0; i < hiddenArray.length; i++) {
              hSecond = hSecond + 0.1;
              hiddenArray[i].setAttribute("data-wow-delay", hSecond + "s");
              hiddenArray[i].style.display = "block";
            }
            load.style.display = "none";

            window.scrollTo(0, window.pageYOffset + 1);
            window.scrollTo(0, window.pageYOffset - 1);

            // if (document.querySelectorAll('.customer_list[style="display:none;"]').length == 0) {
            // 	load.style.display = "none";
            // }
          });
        });
      }

      // 아이콘 4개
      if (window.matchMedia("screen and (max-width: 940px)").matches) {
        $(function () {
          $(".customer_list").hide();
          var list = document.getElementsByClassName("customer_list");
          var hiddenArray = [];
          var openArray = [];
          $(".customer_list").slice(0, 12).show();
          for (var i = 0; i < list.length; i++) {
            if (list[i].style.display == "none") {
              hiddenArray.push(list[i]);
            } else {
              openArray.push(list[i]);
            }
          }
          // 보여진 아이콘
          var second = 0;
          for (var i = 0; i < openArray.length; i++) {
            second = second + 0.1;
            openArray[i].setAttribute("data-wow-delay", second + "s");
          }
          //숨겨진 아이콘
          var hSecond = 0;
          $(".load").click(function (e) {
            e.preventDefault();
            for (var i = 0; i < hiddenArray.length; i++) {
              hSecond = hSecond + 0.1;
              hiddenArray[i].setAttribute("data-wow-delay", hSecond + "s");
              hiddenArray[i].style.display = "block";
              if ($(".customer_list:hidden").length == 0) {
                $(".load").hide();
              }
            }
          });
          window.scrollTo(0, window.pageYOffset + 1);
          window.scrollTo(0, window.pageYOffset - 1);
        });
      }
      function preventClick(e) {
        e.preventDefault();
      }
    </script>

    
    <!-- 지도 인포  -->
    <div class="map-wrap">
      <div id="map" class="indexKakaoMap wow fadeIn" data-wow-delay="0.3s" style="animation-delay: 0.3s; animation-name:fadeIn;"></div>
      <div class="map-info-wrap wow fadeInRight" data-wow-delay="0.5s" style="animation-delay: 0.5s; animation-name: fadeInRight;">
          <div class="map-info">
              <p class="map-info-t">TEL</p>
              <a href="tel:053-475-2100;" style="cursor:text">
              <p class="map-info-p">(053) 475-2100</p></a>
          </div>
          <div class="map-info">
              <p class="map-info-t">FAX</p>
              <a href="javascript:void(0);" style="cursor:text">
          <p class="map-info-p">(0504) 257-5966</p></a>
          </div>
          <div class="map-info">
              <p class="map-info-t">E-MAIL</p>
              <p class="map-info-p">call@resoft.kr</p>
          </div>
          <div class="map-info">
              <p class="map-info-t">ADDRESS</p>
              <p class="map-info-p">(41260) <br>
                  대구광역시 동구 동구대로 465, 대구스케일업허브
                  (DASH) 713호<br>
                  (주)리소프트
              </p>
          </div>
      </div>
  </div>
  
  <!-- 지도인포 끝 -->
  
  <!-- 지도 시작-->
  
  
  
      <script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=841c3df5b9304ec5a4a4a954d55bd878"></script><script charset="UTF-8" src="http://t1.daumcdn.net/mapjsapi/js/main/4.4.5/kakao.js"></script>
      
      
      
      <script>
          // 카카오 지도 api
          var container = document.getElementById('map'); //지도를 담을 영역의 DOM 레퍼런스
          var options = { //지도를 생성할 때 필요한 기본 옵션
              center: new kakao.maps.LatLng(35.871691843254716, 128.62496478375644), //지도의 중심좌표.
              level: 2 //지도의 레벨(확대, 축소 정도)
          };
      
          
      var map = new kakao.maps.Map(container, options); //지도 생성 및 객체 리턴
          // 마커가 표시될 위치입니다 
          var markerPosition = new kakao.maps.LatLng(35.871691843254716, 128.62496478375644);
      
      
      
          var imageSrc = './image/지도마커.png', // 마커이미지의 주소입니다    
              imageSize = new kakao.maps.Size(220, 45), // 마커이미지의 크기입니다
              imageOption = {
                  offset: new kakao.maps.Point(27, 69)
              }; // 마커이미지의 옵션입니다. 마커의 좌표와 일치시킬 이미지 안에서의 좌표를 설정합니다.
      
          // 마커의 이미지정보를 가지고 있는 마커이미지를 생성합니다
          var markerImage = new kakao.maps.MarkerImage(imageSrc, imageSize, imageOption),
              markerPosition = new kakao.maps.LatLng(35.871691843254716, 128.62496478375644); // 마커가 표시될 위치입니다
      
      
          // 마커를 생성합니다
          var marker = new kakao.maps.Marker({
              position: markerPosition,
              image: markerImage
          });
      
          // 마커가 지도 위에 표시되도록 설정합니다
          marker.setMap(map);
      
          </script>
    
  
  
    <!-- 지도 끝-->

    <!-- 푸터 -->
    <footer>
      <div class="footer_wrap">
        <div class="img-wrap">
          <img src="./image/푸터로고.png" alt="footer_logo" />
        </div>
        <div class="footer_content">
          <p class="footer_content_wht">
            주식회사 리소프트는 새로운 소프트웨어로 진화하여 여러분께
            응답드리고자 노력하겠습니다.
          </p>
          <div class="footer_info_wrap">
            <div class="footer_info">
              <p><span>상호. </span><span>(주)리소프트</span></p>
              <p><span>대표이사. </span><span>오유나</span></p>
              <p><span>사업자등록번호. </span><span>722-81-02219</span></p>
              <p><span>개인정보책임자. </span><span>이현지</span></p>
              <br /><br />
              <pre></pre>
              <p>
                <span>주소. </span
                ><span
                  >(41260) 대구광역시 동구 동대구로 465, 대구스케일업허브(DASH)
                  704호 (신천동 106)</span
                >
              </p>
              <p>
                <span>전화. </span
                ><a href="tel:053-475-2110" style="cursor: text"
                  ><span>(053) 475-2110</span></a
                ><i class="fa-solid fa-pipe"></i>
              </p>
              <p>
                <span>팩스. </span
                ><a href="javascript:void(0);" style="cursor: text"
                  ><span>(0504) 257-5966</span></a
                >
              </p>
              <p><span>이메일. </span><span>call@resoft.kr</span></p>
            </div>
          </div>
          <br />
          <p class="copyright">
            Copyright(c) RESOFT CO.LTD. All right reserved.
          </p>
        </div>
      </div>
    </footer>



    <script>
      // 카카오 지도 api
      var container = document.getElementById("map"); //지도를 담을 영역의 DOM 레퍼런스
      var options = {
        //지도를 생성할 때 필요한 기본 옵션
        center: new kakao.maps.LatLng(35.871691843254716, 128.62496478375644), //지도의 중심좌표.
        level: 2, //지도의 레벨(확대, 축소 정도)
      };
      var map = new kakao.maps.Map(container, options); //지도 생성 및 객체 리턴
      // 마커가 표시될 위치입니다
      var markerPosition = new kakao.maps.LatLng(
        35.871691843254716,
        128.62496478375644
      );

      var imageSrc = "./리소프트 홈페이지 이미지/지도마커.png", // 마커이미지의 주소입니다
        imageSize = new kakao.maps.Size(220, 45), // 마커이미지의 크기입니다
        imageOption = { offset: new kakao.maps.Point(27, 69) }; // 마커이미지의 옵션입니다. 마커의 좌표와 일치시킬 이미지 안에서의 좌표를 설정합니다.

      // 마커의 이미지정보를 가지고 있는 마커이미지를 생성합니다
      var markerImage = new kakao.maps.MarkerImage(
          imageSrc,
          imageSize,
          imageOption
        ),
        markerPosition = new kakao.maps.LatLng(
          35.871691843254716,
          128.62496478375644
        ); // 마커가 표시될 위치입니다

      // 마커를 생성합니다
      var marker = new kakao.maps.Marker({
        position: markerPosition,
        image: markerImage,
      });

      // 마커가 지도 위에 표시되도록 설정합니다
      marker.setMap(map);
    </script>
  </body>
</html>
