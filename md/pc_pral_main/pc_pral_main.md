```html
<p>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />
</p>
<div id="pral-main-wrap">
  <div id="pc_view">
    <div id="main_header_pc">
      <div class="header-inner">
        <div class="left">
          <a href="https://www.lgpral.kr/">
            <h1>
              <img
                src="https://image2.lglifecare.com/pral/pc/resource/main/image/LG PraL_w.png"
                alt="LG Pral"
                class="default_log fr-fic fr-dii"
              />&nbsp;<img
                src="https://image2.lglifecare.com/pral/pc/resource/main/image/LG PraL_b.png"
                alt="LG Pral"
                class="scroll_logo fr-fic fr-dii"
              />
            </h1>
          </a>             
        </div>
        <div class="gnb-area">  
          <!-- 브랜드 메뉴 -->  
            <div class="main_title">
              <nuxt-link :to="{ path:'/eventExhibition/1457' }" class="main_txt">
                <span class="txt_underline">브랜드</span>
              </nuxt-link>
              <div class="sub_menu_inner">        
                <div class="sub_menu_list">
                  <div class="sub_menu_item">
                    <div class="sub_title">
                      <span>브랜드</span>
                    </div>
                    <nuxt-link :to="{ path:'/eventExhibition/1457' }" class="sub_txt">
                      <span>브랜드 필름</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/eventExhibition/1458' }" class="sub_txt">
                      <span>브랜드 스토리</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/eventExhibition/1459' }" class="sub_txt">
                      <span>브랜드 히스토리</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/eventExhibition/1460' }" class="sub_txt">
                      <span>브랜드 아키텍쳐</span>
                    </nuxt-link>
                  </div>
                  <div class="sub_img_box">
                    <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_01.jpg" alt="gnb_11월블랙프라이데이">
                    <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_02.jpg" alt="gnb_11월라이브커머스메인">                         
                  </div>
                </div>
              </div>
            </div>     
          
          <!-- VIEW 메뉴 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/event/1343' }" class="main_txt">
                <span class="txt_underline">VIEW</span>
              </nuxt-link>
              <div class="sub_menu_inner">        
                <div class="sub_menu_list">
                  <div class="sub_menu_item">
                    <div class="sub_title">
                      <span>VIEW</span>
                    </div>
                    <nuxt-link :to="{ path:'/event/1343' }" class="sub_txt">
                      <span>제품 리뷰</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/event/1344' }" class="sub_txt">
                      <span>프라엘 아티클</span>
                    </nuxt-link>  
                    <nuxt-link :to="{ path:'/event/1345' }" class="sub_txt">
                      <span>프라엘 영상</span>
                    </nuxt-link>        
                  </div>
                  <div class="sub_img_box bigBanner">
                    <nuxt-link :to="{ path:'/event/1293' }">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_BigBanner.jpg" alt="gnb_리뷰쎄라">
                    </nuxt-link>        
                  </div>
                </div>
              </div>
            </div>
          
          <!-- 전체 제품 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/products/detail/26416110' }" class="main_txt">
                <span class="txt_underline">전체 제품</span>
              </nuxt-link>
              <div class="sub_menu_inner">        
                <div class="sub_menu_list">
                  <div class="sub_menu_item type02">
                    <div class="sub_title">
                      <span>탄력/보습</span>
                    </div>       
                    <nuxt-link :to="{ path:'/products/detail/26416140' }" class="sub_img_box">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_01.jpg" alt="gnb_시그니처">
                    </nuxt-link>              
                    <nuxt-link :to="{ path:'/products/detail/26416110' }" class="sub_txt">
                      <span>더마쎄라</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26416130' }" class="sub_txt">
                      <span>더마쎄라X보상판매</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26416109' }" class="sub_txt">
                      <span>더마쎄라 카트리지</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26416111' }" class="sub_txt">
                      <span>인텐시브 멀티케어</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26416140' }" class="sub_txt">
                      <span>시그니처 탄력 패키지</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26419849' }" class="sub_txt">
                      <span>토탈 케어 솔루션</span>
                    </nuxt-link>
                  </div> 
                  
                  <div class="sub_menu_item type02">
                    <div class="sub_title">
                      <span>모공/피지</span>
                    </div>       
                    <nuxt-link :to="{ path:'/products/detail/26416114' }" class="sub_img_box">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_02.jpg" alt="gnb_에센셜">
                    </nuxt-link>              
                    <nuxt-link :to="{ path:'/products/detail/26416114' }" class="sub_txt">
                      <span>에센셜 부스터</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26416112' }" class="sub_txt">
                      <span>워시팝</span>
                    </nuxt-link>        
                  </div> 
            
                  <div class="sub_menu_item type02">
                    <div class="sub_title">
                      <span>탈모 케어</span>
                    </div>       
                    <nuxt-link :to="{ path:'/products/detail/26416126' }" class="sub_img_box">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_03.jpg" alt="gnb_메디헤어">
                    </nuxt-link>              
                    <nuxt-link :to="{ path:'/products/detail/26416126' }" class="sub_txt">
                      <span>메디헤어&거치대(HGN1)</span>
                    </nuxt-link>                              
                  </div> 
            
                  <div class="sub_menu_item type02">
                    <div class="sub_title">
                      <span>통증 케어</span>
                    </div>       
                    <nuxt-link :to="{ path:'/products/detail/26416117' }" class="sub_img_box">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_04.jpg" alt="gnb_메디페인">
                    </nuxt-link>              
                    <nuxt-link :to="{ path:'/products/detail/26416117' }" class="sub_txt">
                      <span>메디페인</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/products/detail/26419561' }" class="sub_txt">
                      <span>메디페인 전극패드</span>
                    </nuxt-link>       
                  </div> 
                </div>
              </div>
            </div>
          
          <!-- 라이브 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/gnb/liveshop' }" class="main_txt">
                <span class="txt_underline">라이브</span>
              </nuxt-link>
            </div>
          
          <!-- 회원 특가혜택 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/products/detail/26420093' }" class="main_txt">
                <span class="txt_underline">회원 특가 혜택</span>
              </nuxt-link>
            </div>
          
          <!-- 이벤트 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/eventExhibition/1464' }" class="main_txt">
                <span class="txt_underline">이벤트</span>
              </nuxt-link>
            </div>
          
          <!-- 고객지원 -->
            <div class="main_title">
              <nuxt-link :to="{ path:'/customer/notices' }" class="main_txt">
                <span class="txt_underline">고객지원</span>
              </nuxt-link>
              <div class="sub_menu_inner">        
                <div class="sub_menu_list">
                  <div class="sub_menu_item">
                    <div class="sub_title">
                      <span>고객지원</span>
                    </div>
                    <nuxt-link :to="{ path:'/customer/notices' }" class="sub_txt">
                      <span>공지사항</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/customer/faq' }" class="sub_txt">
                      <span>자주 묻는 질문</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/eventExhibition/1466' }" class="sub_txt">
                      <span>체험 매장 안내</span>
                    </nuxt-link>
                    <nuxt-link :to="{ path:'/eventExhibition/1467' }" class="sub_txt">
                      <span>부품/소모품 구매 </span>
                    </nuxt-link>
                  </div>
                  <div class="sub_img_box">
                    <nuxt-link :to="{ path:'/eventExhibition/1467' }" >
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_customer_01.jpg" alt="부품/소모품 구매 > 보유하고 계신 제품에 맞는 부품과 소모품을 만나보세요.">
                    </nuxt-link>
                    <a href="https://www.lge.co.kr/support/product-manuals?title=manual" target="_blank">
                      <img src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_customer_02.jpg" alt="제품 사용 설명서 > 제품명과 모델명 검색으로 제품 사용 설명서를 확인해주세요.">
                    </a>
                  </div>
                </div>
              </div>
            </div>
        </div>
        <div class="quick_menu_wrap">
          <nuxt-link :to="{ path:'/search' }" class="search"><span class="blind">검색</span></nuxt-link>
          <nuxt-link :to="{ path:'/mypage' }" class="member"><span class="blind">멤버</span></nuxt-link>
          <nuxt-link :to="{ path:'/cart' }" class="cart"><span class="blind">장바구니</span></nuxt-link>
        </div>
        <div class="search_form">
          <div class="input_wrap">
            <input type="text" placeholder="검색어를 입력하세요" />
            <button class="search_go" type="button"><span class="blind">검색하기</span></button>
          </div>
          <button class="search_close" type="button"><span class="blind">검색창 닫기</span></button>
        </div>
      </div>
    </div>
    <div id="main_movie_wrap">
      <span class="fr-video fr-deletable fr-fvc fr-dvi fr-draggable" contenteditable="false"
        ><video
          autoplay=""
          class="fr-fvc fr-dvi fr-draggable"
          controls=""
          id="video01"
          loop=""
          muted=""
          poster=""
        >
          <source
            src="https://img2.lgpral.kr/pral/pc/resource/main/video/pc_main_20231019.mp4"
          /></video
      ></span>
    </div>
  </div>
  <div id="mo_view">
    <!-- header -->
    <div id="main_header_mo">
      <div class="main_gnb_wrap">
        <div class="left">
          <h2>
            <img
              src="https://image2.lglifecare.com/pral/mo/resource/main/image/LG PraL_w.png"
              alt="LG Pral"
              class="default_logo fr-fic fr-dii"
            /><img
              src="https://image2.lglifecare.com/pral/mo/resource/main/image/LG PraL_b.png"
              alt="LG Pral"
              class="scroll_logo fr-fic fr-dii"
            />
          </h2>
        </div>
        <div class="quick_menu_wrap">
          <nuxt-link :to="{ path:'/search' }" class="search"><span class="blind">검색</span></nuxt-link>
          <nuxt-link :to="{ path:'/mypage' }" class="member"><span class="blind">멤버</span></nuxt-link>
          <nuxt-link :to="{ path:'/cart' }" class="cart"><span class="blind">장바구니</span></nuxt-link>
          <nuxt-link :to="{ path:'/gnbPopup' }" class="gnb_call"><span class="blind">GBN 메뉴</span></nuxt-link>
        </div>
      </div>
    </div>
    <!-- // header -->
    <div id="videw_wrap">
      <button class="btn_volume_mute" type="button"><span class="blind">볼륨제어</span></button
      ><span class="fr-video fr-deletable fr-fvc fr-dvi fr-draggable" contenteditable="false"
        ><video
          autoplay="autoplay"
          class="fr-fvc fr-dvi fr-draggable"
          id="video_mo"
          loop="loop"
          muted="muted"
          playsinline=""
        >
          <source
            src="https://img2.lgpral.kr/pral/mo/resource/main/video/mo_main_20231019.mp4"
          /></video
      ></span>
    </div>
  </div>
  <article class="buying-section">
    <div class="sec-inner">
      <div class="swiper buyingSwiper">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <div class="card-buying item1">
              <h3 class="tit-card-buying">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_buying1.png"
                  class="m-show fr-fic fr-dii"
                  alt="Dermathera LG 프라엘 더마쎄라"
                /><img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_buying1.svg"
                  class="pc-show fr-fic fr-dii"
                  alt="Dermathera LG 프라엘 더마쎄라"
                />
              </h3>

              <p class="txt-card-buying">
                피부 5대 코어를 잡아 무너진 얼굴 라인을 탄탄하고 <br />날렵하게 잡아주는 얼굴선 케어 디바이스
              </p>
              <nuxt-link
                :to="{ path:'/products/detail/26416110' }"
                class="btn-card-buying"
                style="display: inline-block"
                ><span>더마쎄라 구매하기</span></nuxt-link
              >
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-buying item2">
              <h3 class="tit-card-buying">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_buying2.png"
                  class="m-show fr-fic fr-dii"
                  alt="Medi Hair LG 프라엘 메디헤어"
                /><img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_buying2.svg"
                  class="pc-show fr-fic fr-dii"
                  alt="Medi Hair LG 프라엘 메디헤어"
                />
              </h3>

              <p class="txt-card-buying">
                레이저와 저출력 광선의 복합 빛 에너지가 모낭세포에 흡수되어 <br />영양 공급에 도움을 주는 집에서
                경험하는 탈모 치료 의료기기
              </p>
              <nuxt-link
                :to="{ path:'/products/detail/26416116' }"
                class="btn-card-buying"
                style="display: inline-block"
                ><span>메디헤어 구매하기</span></nuxt-link
              >
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-buying item3">
              <h3 class="tit-card-buying">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_buying3.png"
                  class="m-show fr-fic fr-dii"
                  alt="Intensive Multicare LG 프라엘 인텐시브 멀티케어"
                /><img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_buying3.svg"
                  class="pc-show fr-fic fr-dii"
                  alt="Intensive Multicare LG 프라엘 인텐시브 멀티케어"
                />
              </h3>

              <p class="txt-card-buying">
                하나의 기기에 담긴 강력한 쿼드러플 기술로 완성되어 <br />볼륨감 있는 탄력 피부로 도와주는 탄력
                케어 디바이스
              </p>
              <nuxt-link
                :to="{ path:'/products/detail/26416111' }"
                class="btn-card-buying"
                style="display: inline-block"
                ><span>인텐시브 멀티케어 구매하기</span></nuxt-link
              >
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-buying item4">
              <h3 class="tit-card-buying">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_buying4.png"
                  class="m-show fr-fic fr-dii"
                  alt="Essential Booster LG 프라엘 에센셜 부스터"
                /><img
                  src="/V2_pc/resource/images/common/Title.svg"
                  class="pc-show fr-fic fr-dii"
                  alt="Essential Booster LG 프라엘 에센셜 부스터"
                />
              </h3>

              <p class="txt-card-buying">
                세정, 각질, 보습 3단계 케어를 하나로 완성해 클렌징과 <br />동시에 빠르고 싶은 수분 케어를 도와주는
                2 IN 1 디바이스
              </p>
              <nuxt-link
                :to="{ path:'/products/detail/26416114' }"
                class="btn-card-buying"
                style="display: inline-block"
                ><span>에센셜 부스터 구매하기</span></nuxt-link
              >
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-buying item5">
              <h3 class="tit-card-buying">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_buying5.png"
                  class="m-show fr-fic fr-dii"
                  alt="Body SPA LG 프라엘 바디 스파"
                /><img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_buying5.svg"
                  class="pc-show fr-fic fr-dii"
                  alt="Body SPA LG 프라엘 바디 스파"
                />
              </h3>

              <p class="txt-card-buying">
                미세한 초음파 진동으로 만들어진 버블로 모공 속 노폐물을 <br />말끔하게 씻어내는 3단 바디 케어
                디바이스
              </p>
              <nuxt-link
                :to="{ path:'/products/detail/26416118' }"
                class="btn-card-buying"
                style="display: inline-block"
                ><span>바디스파 구매하기</span></nuxt-link
              >
            </div>
          </div>
        </div>
        <div class="btn-direction-box">
          <div class="swiper-button-prev">
            <br />
          </div>
          <div class="swiper-button-next">
            <br />
          </div>
        </div>
      </div>
    </div>
  </article>
  <article class="collection-section">
    <div class="sec-inner">
      <h3 class="sec-title">
        <img
          src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_collection.png"
          class="m-show fr-fic fr-dii"
          alt="Dermathera 더마쎄라"
        /><img
          src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_collection.svg"
          class="pc-show fr-fic fr-dii"
          alt="Dermathera 더마쎄라"
        />
      </h3>

      <p class="sec-txt">
        이마, 볼, 목, 턱 밑살, 눈가 등 피부의 5대 코어를 잡아 무너진 얼굴 라인 케어를 도와주는 더마쎄라의 6가지
        대표 기능
      </p>
      <div class="card-collection-wrapper">
        <div class="card-collection-list cardCollections">
          <div class="card-collection active" data-num="1">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item1.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>PERFECTING</h4>

              <p>신속, 정확, 균일하게 피부 속 3.0mm에 <br />텐서코어를 형성해 살아나는 피부 라인</p>
            </div>
          </div>
          <div class="card-collection" data-num="2">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item2.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>TEACHING</h4>

              <p>초보자도 쉽게 따라 할 수 있는 음성 가이드로 <br />어떠한 순간에도 정확한 탄력 케어</p>
            </div>
          </div>
          <div class="card-collection" data-num="3">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item3.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>DESIGN</h4>

              <p>인체공학적 디자인으로 사용하기 쉽고 <br />효율적인 탄력 케어</p>
            </div>
          </div>
          <div class="card-collection" data-num="4">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item4.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>HYGIENE</h4>

              <p>크래들의 UVC 기능으로 조사부 자동 살균과 <br />위생적인 관리</p>
            </div>
          </div>
          <div class="card-collection" data-num="5">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item5.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>PRIVATE</h4>

              <p>24시간 어디서나 피부 타입과 주기에 맞춰 앱으로 <br />관리 하는 나만을 위한 탄력 케어</p>
            </div>
          </div>
          <div class="card-collection" data-num="6">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_collection_item6.png"
                alt=""
                class="fr-fic fr-dii"
              />
            </div>
            <div class="txt-box">
              <h4>CUSTOMIZING</h4>

              <p>
                계란형, 하트형, 각진형, 둥근형 등 어떤 얼굴형에도 <br />샷을 촘촘하게 전달하는 나에게 꼭 맞춘 케어
              </p>
            </div>
          </div>
        </div>
        <!-- <span class="img-guide"><img src="https://img2.lgpral.kr/pral/pc/resource/main/img/icon/hand_white_click.svg" alt="클릭해보세요"></span> -->
      </div>
    </div>
  </article>
  <article class="reviews-section">
    <div class="sec-inner">
      <div class="tit-box">
        <h3 class="sec-title">
          <img
            src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_reviews.png"
            class="m-show fr-fic fr-dii"
            alt="Reviews 제품리뷰"
          /><img
            src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_reviews.svg"
            class="pc-show fr-fic fr-dii"
            alt="Reviews 제품리뷰"
          />
        </h3>
        <p class="sec-txt">LG 프라엘의 놀라운 효과를 먼저 체험한 고객들의 생생한 리얼 후기</p>
      </div>
      <div class="swiper reviewsSwiper">
        <div class="swiper-wrapper">
          <!-- 231101 review 추가 -->
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231101_01.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">시그니처 탄력 패키지</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  동생이 더마쎄라 구입했는데 한 번 써보라고 해서 써봤다가 너무 좋아서 라이브 기다렸다가 냉큼 구입했어요! 한 번 사용했었는데도 늘어진 피부 탄력이 쫙!!! 그리고 피부과에서 리프팅 받은적이 있는데 그 느낌이랑 너무 똑같아서 놀랬어요 +_+ (동생이랑 가까이살았으면 인텐시브만 구입했을텐데 멀리 살아서 패키지 둘다 구입해버렸네요 ㅎㅎ) 인테시브는 탄력 모공에 도움을 준다해서 구입했어요 인텐시브 모드는 화장품 영양분을 쏘옥 넣어주는 너낌이구요 쿨링은 진짜 아침 붓기 뺄때 완전 최고에유 ㅋㅋㅋ 그동안 피부 좋다는 말 진짜 많이 듣고 살았는데 30대 후반인 지금 모공도 눈에 보이고 탄력이 떨어지네요 ㅠ 피부과 다니면 더 좋겠지만, 꾸준하게 집에서 열심히 관리하려구요! 피부는 꾸준함이 정답이니까요 ㅎㅎ 열심히 홈케어해서 노화를 늦춰보려합니덩
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231101_02.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  워낙 더마쎄라 주변에서 극찬이라 고민에 라이브방송때 구매허고 써봣는데요 넘넘 좋아요 자극도 쎄기도 좋고 조절도 돠고 샷도 오류나거나 안맞게 샷 하면 날리지 않게 음성으로도 알려주고 역시 엘지규나 싶으면서 뷰티쪽 넘 잘 만들엇다 극찬을 안 할수가 없더라규요 넘 좋고 탄력 피뷰 관리능 역시 엘지네요
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231101_03.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">시그니처 탄력 패키지</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  뷰티 디바이스 처음 샀어요 6주년이라 세일할 때 두개를 사버렸지만용 ㅎㅎ 어머니랑 같이 사용중이에요 피부과에 쓰는 돈이 너무 많이 나가겠다 싶어 프라엘을 샀어요 집에서 꾸준히 할 수 있어 좋습니다 제품도 넘 고급지고 이뻐요 😭
                </p>
              </div>
            </nuxt-link>
          </div>
          <!-- // 231101 review 추가 -->
          <!-- 231016 review 추가 -->
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231016_01.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  홈**이랑 엄청 고민하다가 유튜브영상, 블로그 다 보고 비교해서 더마쎄라로 결정했어요. 무엇보다 엘지라는 대기업 제품이라는걸 무시못했고요. 후기도 너무 좋더라구요. 그리고 초보자인데 음성으로 안내해주는 부분도 맘에 들었어요. 또 디자인이 너무 이쁘게 잘나와서 더 눈이 가는 것도 있었어요. 처음받자마자 같이온 젤이랑 해봤는데 미세하게 리프팅된 느낌이 나고 팔자주름이 심한테 팔자쪽이 차오른거처럼 보였어요. 일시적인 건지는 시간이 지나봐야 알것같은데 모공개선과 리프팅이 잘됐으면 좋겠어요!! 한달후기도 가져올께요 ㅎㅎ 일단 현재로서는 만족하고 일주일에 한번씩 열심히 관리해보겠습니다.
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231016_02.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  임신출산 후 피부 컨디션이 너무 안 좋아져서 피부과를 다닐까 고민도 했는데 꾸준히 다니기엔 경제적으로도 시간적으로도 어렵더라구요....ㅜㅜ 고민고민 끝에 엘지프라엘 더마쎄라를 알게 되어 큰 마음 먹고 구입해봤습니다! 엘지프라엘은 전에 시리즈도 사용하고 있었고 효과를 봤기 때문에 큰 기대를 하고 있었는데 역시나 엘지 효과 좋더라구요! 홈케어 중에는 이게 원탑이지 싶어요~~^^ 사용팁은 수딩젤을 정말 많이 바르고 하셔야 된다는 것! 얇게 바르고 하면 너무 아파요...조금 따끔하긴 하지만 참아야 할 정도는 아니었고 간편하니 꾸준히 할수 있을 것 같아요~^^ 1회 300샷이고 어떻게 기계를 움직여야 되는지도 기계가 자세히 안내해줘서 처음에 하는데도 걱정없이 잘 했답니다! 또 피부에 잘 닿지 않으면 기계가 알려주기 때문에 실수할 일도 없어요~~^^ 역시 믿고 사는 엘지! 엘지프라엘 더마쎄라 역대급이었습니다 강추합니다!
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416112' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231016_03.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">워시팝</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  세안기를 써본적이 없어서 처음에는 진동이 약한거 아닌가 생각했는데, 기기 자체에서 진동이있고 실리콘 모에는 간접적으로 진동이 전달되더라구요.. 깨끗이 씻껴질까 반신반의 했었는데 세안 후 토너 패드로 닦아 냈는데.. 이게 왠일이야 하나도 안 묻어납니다! 그리고 뽀득뽀득한 느낌이나서 좋습니다. 알로에 크림도 바르고 기기 쓰고 있는데 세척도 쉬워서 좋네요!!~ 무엇보다도 다음날 화장할때 비비가 밀리지않고 스며든다는 느낌을 받았습니다!!~~ 지인들에게 추천하고있습니다ㅎㅎ
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416140' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_231016_04.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">시그니처 패키지</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>
                <p class="txt-reviews">
                  얼마전에 화질 좋은 카메라로 사진을 찍을 기회가 있었는데, 그동안 크게 관리 안하고 살던 내 얼굴에 주름이 너무 많고 푸석푸석하다는걸 진짜 강력하게 깨달았어요ㅜㅜ 그동안 살면서 크게 피부트러블이 없던 편이라 너무 안일하게 관리했던 탓이겠죠.. 그렇게 어느날 문득 눈에 들어온 주름을 보니 왜 다들 하루라도 어릴때 빨리 피부관리 주름관리를 하라고들 했는지 이해가 갔어요~ 마침 친구가 이미 이 더마쎄라를 사용하고 있어서 후기를 물어보니 강력추찬한다해서 저도 친구따라 질렀습니다.. 저는 마침 인텐시브케어까지 함께 구매시 할인이벤트 한다길래 같이 구매했는데 나름 많이 할인받아서 아주 잘산거 같아요♡ 일단 어플로 내 피부타입에 맞게 스케쥴 알람 관리가 되는게 너무 좋았습니다~ 홈케어 뷰티디바이스의 장점이 가볍게 매일할수 있지만 또 그만큼 꾸준히 하는게 힘들다는게 단점으로 작용할수있는데;; 이렇게 어플로 알림해주고 케어완료체크를 할수있어서 넘 유용했어요^^ 앞으로도 꾸준히 스케쥴 관리하면서 해볼 생각입니다~ 스케쥴상 인텐시브멀티케어를 먼저 사용해보았는데요.. 인텐시브케어 아이케어 쿨링케어로 나누어서 부분별로 집중관리할수 있어서 좋았어요~ 솔직히 한두번으로 효과를 봤다고 얘기하면 좀 과장일수 있는데;; 개인적인 느낌으로는 피부톤이 확실히 순간적으로나마 맑아지고 피부도 살짝 업된 느낌 물광이 확 차오르는 느낌이 있었습니다. 이게 유지가 되고 진짜 내 피부에 스며들려면 매일 꾸준히 해야겠지만요ㅎㅎ 인텐시브케어는 주3회 권장이라 2일에 한번 3일에 한번 꼴로 관리하면되구요~ 그 외의 날엔 쿨링케어로 열감을 식혀주고 모공을 조일수있습니다. 이게 은근 피부에 부담없이 가볍게 설렁설렁 시원하게 할수있어서 넘 좋았어요^^ㅋㅋ 그리고 아이케어는 볼같이 튀어나온 툴로 특별관리해주니 눈가같이 얇은 피부에 집중관리할수있어서 좋았어요~ 더마쎄라만 샀으면 땅치고 후회했을꺼같아요... 이 인텐시브멀티케어도 은근 물건입니다ㅎㅎ 그리고 대망의 더마쎄라도 사용해봤는데요~ 저는 피부가 약한 편이라 지금까지 피부과에서 가벼운 토닝정도만 관리 받아봤었어요.. 흉터도 잘 아물지않는 체질이라;; 아무리 효과가 확실하다해도 선뜻 관리받기가 두려웠었는데 이 더마쎄라는 그런 걱정없이 안전하게 케어받을수 있다는 점이 제일 좋았어요♡ 저처럼 흉터나 색소침착 걱정되시는 분들은 더마쎄라로 은근하게 주1회 관리하는게 확실히 더 유용하고 안전하게 케어받으실수 있을꺼같아요! 저는 1단계 2단계 얼굴부분별로 나눠서 사용했는데, 요즘 얼굴형이 점점 네모화 되가고있어서 고민이었거든요..근데 더마쎄라는 이중턱 목선 관리도 따로 할수 있어서 큰 도움이 되었던거 같아요ㅋㅋ 구석구석 가벼운 디바이스로 관리할수있어서 편하고 자극이 덜하면서 꾸준히 관리할수 있어서 확실히 노력하는 만큼 효과 볼꺼같아요^^♡ 한번만 해도 기분탓인지 모르지만;; 정말 얼굴형이 슬림해지고 V라인이 은근 드러나는 기분이었어요... 진심으로 은근 차이가 나서 비교사진 올릴수도 있을 정도인데 이게 계속 유지되려면 진짜 꾸준히 해줘야할꺼같아서 적나라한 비교사진은 생략하렵니다ㅜ (나자신의 프라이버시도 지켜줘야되니;;;) 암튼 구매한지 이제2주차 접어드는데 이 두가지 셋트 진짜 강추해요!!! 그리고 아무리 좋은제품도 나싀 꾸준한 노력이 있어야 더 빛을 발한다는걸 기억하고 정말 열씨미 뽕뽑게 쓰려구요ㅋㅋ 다들 하루라도 어릴때 관리해서 효과보시길 바랄께요♡ #LG프라엘#더마쎄라#뷰티디바이스#더마쎄라내돈내산#내돈내산#LG인텐시브케어#둘다있으면시너지효과#탄력개선#벌써얼굴쪼금작아진듯#중요한건매일관리하는것#홈케어의중요성
                </p>
              </div>
            </nuxt-link>
          </div>
          <!-- //20231016 review 추가 -->
          <!-- 230217 review추가 -->
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_230608_01.png"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>

                <p class="txt-reviews">
                  피부과 종종 다니다가 비용 부담되어 홈케어 기기 알아보던 중에 발견한 더마쎄라. 먼저 나온 타기업
                  제품과 비교해서 앱 관리가 가능하고 대기업상품이라 믿고 구매했습니다. 사실 다른 회사 상품에서 2mm
                  4mm 이런 식으로 세분화 된 제품이 갖고 싶었는데 오히려 나눠서 하기 귀찮아 안 할 거 같아서 일단 요
                  제품으로 구매해봅니다. 피부과에서 받는 거에 비하면 통증이 덜해서 다행이에요 아니었음 셀프로
                  못했을거같은데ㅋㅋ 솔직히 홈케어기기 효과 없는 거 많은데 요건 꽤 맘에 들어요 지금까지 2회 했는데
                  일시적이지만 올라간 게 눈에 보이고 처음보다 두 번째가 오래가네요 처음은 2단계, 두번째는 3단계로
                  했고 통증은 있지만 심하지 않았어요 이마나 관자놀이,이중턱 부분은 하는게 쉽지 않았습니다. 특히
                  이중턱은 횟수에 따라 각도를 맞추려면 고개를 많이 꺾어야했어요 ㅜㅜ 하다보면 요령이 생기겠죠??
                  하면 안되는 부위들이 있기 때문에 설명서나 영상을 꼭 보시고 하셔야됩니다. 귀찮아도 신경써서
                  꼼꼼히하다보면 어려질거라 생각하며 미루지 않는 습관을 들이고 꾸준히 하면 확실히 시간을 되돌릴수
                  있을거라 기대하면서 열심히 해보려구요 최소 3개월은 해보고 좋으면 주변에 추천할게요ㅋㅋ 근데
                  라비다젤은 1개로 얼마나 쓸수 있을까요? 지금 갖고 있는것들로 카트리지 1개분 사용가능할지
                  모르겠어요 그리고 매주 하면 얼굴피부에 자극이 심하진 않을지 걱정이 되긴 합니다. 무조건
                  설명서대로 하지말고 제 피부 상태를 확인하면서 해야할듯하고 날씨가 더워지면서 열감이 생기는데
                  부작용없이 이뻐지고 싶어요~~ 출시 기념할인으로 130만원 후반대로 샀는데 앞으로 더 할인하면
                  배아플거같지만 카트리지는 세일많이 해주세요ㅋㅋㅋㅋ #LG프라엘 #더마쎄라 #리뷰쎄라 #내돈내산
                  #더마쎄라후기 #더마쎄라내돈내산
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_230608_02.jpg"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>

                <p class="txt-reviews">
                  넉넉한 카트리지 양에 남편과도 번갈아 사용하고 있는데 두차례 진행하고부터는 주변에서 살이
                  빠졌냐는 소리를 듣는다고 해요. 효과는 충분히 보는 것 같아요. 일주일에 한 번으로 꾸준히
                  사용한다면 피부과는 이제 멀리할 거 같네요^^
                </p>
              </div>
            </nuxt-link>
          </div>
          <div class="swiper-slide">
            <nuxt-link :to="{ path:'/products/detail/26416110' }">
              <div class="img-box">
                <img
                  src="https://img2.lgpral.kr/pral/pc/resource/main/img/reviews/review_thumb_230608_03.jpg"
                  alt=""
                  class="fr-fic fr-dii"
                />
              </div>
              <div class="txt-box">
                <div class="tit-wrap">
                  <h4 class="tit-reviews">더마쎄라</h4>
                  <div class="rating-area">
                    <span class="rating-off"
                      >&nbsp;<span class="rating-on" style="width: 100%">&nbsp;</span>&nbsp;</span
                    >
                  </div>
                </div>

                <p class="txt-reviews">
                  배송받고 사용한 지 한달가량 됐네요. 첫 출산 후 몇 개월 지났는데 피부가 정말 말도 안 되게
                  나빠지더라고요. 광나던 얼굴이 광도 보기 힘들 정도로 푸석푸석 건조한 건 물론이고 탄력도 잃고 아기
                  때문에 끼니도 제대로 못 먹을 정도로 시간에 쫓겨 지내는데 피부과 시술은 정말 엄두도 못 냈는데
                  신랑이 더마쎄라 cf를 봤는지 그거 찾아보라더라고요. 그때부터 검색해봤는데 출시된 지 얼마 안 돼서
                  솔직 후기는 몇 개 없던 시점이었어요. 정말 며칠을 하루에 몇번씩 검색해봤네요ㅎㅎ lg가 만드니 다른
                  회사 거보단 낫겠지(참고로 엘지빠ㅎㅎ입니다)고민할 시간에 구매해서 사용해보자 하고 신랑찬스로
                  구매했고 일주일에 한 번씩 꾸준히 사용했어요. 확실히 효과가 있어서 너무나 만족합니다. 턱밑 미운
                  살도 옆 라인 턱선도 개선되는 게 눈에 보여요. 눈을 밑으로 뜨면 볼앞쪽살이 보이는걸 30대초때 본 후
                  보질 못했는데 요즘 보고있습니다ㅎㅎ 더마쎄라 구매후 인텐시브멀티케어도 바로 구매해서 꿀조합으로
                  사용중이예요~ 게으름 피우지않고 관리 열심히 하겠습니다 ;-)
                </p>
              </div>
            </nuxt-link>
          </div>
        </div>
        <div class="btn-direction-box">
          <div class="swiper-button-prev">
            <br />
          </div>
          <div class="swiper-button-next">
            <br />
          </div>
        </div>
      </div>
    </div>
  </article>
  <article class="benefits-section">
    <div class="sec-inner">
      <h3 class="sec-title">
        <img
          src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_benefits.png"
          class="m-show fr-fic fr-dii"
          alt="LG 프라엘 공식몰 혜택 Special Benefits"
        /><img
          src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_benefits.svg"
          class="pc-show fr-fic fr-dii"
          alt="LG 프라엘 공식몰 혜택 Special Benefits"
        />
      </h3>

      <p class="sec-txt">LG 프라엘 공식몰에서만 드리는 특별한 혜택</p>

      <ul class="img-benefits-list">
        <li>
          <nuxt-link :to="{ path:'/eventExhibition/1462' }">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/m_img_benefits1.png"
                class="m-show fr-fic fr-dii"
                alt="Free Shipping 전 제품 무료 배송"
              /><img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_benefits1.png"
                class="pc-show fr-fic fr-dii"
                alt="Free Shipping 전 제품 무료 배송"
              />
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{ path:'/eventExhibition/1462' }">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/m_img_benefits2.png"
                class="m-show fr-fic fr-dii"
                alt="Member special benefits 가입 고객 특별 혜택"
              /><img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_benefits2.png"
                class="pc-show fr-fic fr-dii"
                alt="Member special benefits 가입 고객 특별 혜택"
              />
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{ path:'/eventExhibition/1462' }">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/m_img_benefits3.png"
                class="m-show fr-fic fr-dii"
                alt="Point reward 구매 포인트 적립"
              /><img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_benefits3.png"
                class="pc-show fr-fic fr-dii"
                alt="Point reward 구매 포인트 적립"
              />
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{ path:'/eventExhibition/1462' }">
            <div class="img-box">
              <img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/m_img_benefits4.png"
                class="m-show fr-fic fr-dii"
                alt="credit card benefits 부담 없는 무이자 할부"
              /><img
                src="https://img2.lgpral.kr/pral/pc/resource/main/img/main/img_benefits4.png"
                class="pc-show fr-fic fr-dii"
                alt="credit card benefits 부담 없는 무이자 할부"
              />
            </div>
          </nuxt-link>
        </li>
      </ul>
    </div>
  </article>
  <article class="bodycare-section">
    <div class="sec-inner">
      <div class="swiper bodycareSwiper">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <div class="card-bodycare">
              <div class="txt-outer">
                <h3 class="tit-card-bodycare">
                  <img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_bodycare1.png"
                    class="m-show fr-fic fr-dii"
                    alt="Anti-aging 안티 에이징"
                  /><img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_bodycare1.svg"
                    class="pc-show fr-fic fr-dii"
                    alt="Anti-aging 안티 에이징"
                  />
                </h3>

                <p class="txt-card-bodycare">피부 5대 코어를 잡아 무너진 얼굴 라인을 탄탄하고 날렵하게 잡아주는 얼굴선 케어 더마쎄라<br/>
                  하나의 기기에 담긴 강력한 쿼드러플 기술로불륨감 있는 피부를 완성하는 탄력 토탈 케어 인텐시브 멀티케어</p>
              </div>

              <ul class="img-bodycare-list">
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416110' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_antiaging_01.png"
                      class="m-show fr-fic fr-dii"
                      alt="Dermathera 더마쎄라" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_antiaging_01.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Dermathera 더마쎄라"
                  /></nuxt-link>
                </li>
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416111' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_antiaging_02.png"
                      class="m-show fr-fic fr-dii"
                      alt="Intensive Multicare 인텐시브 멀티케어" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_antiaging_02.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Intensive Multicare 인텐시브 멀티케어"
                  /></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-bodycare">
              <div class="txt-outer">
                <h3 class="tit-card-bodycare">
                  <img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_bodycare2.png"
                    class="m-show fr-fic fr-dii"
                    alt="Cleansing 클렌징"
                  /><img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_bodycare2.svg"
                    class="pc-show fr-fic fr-dii"
                    alt="Cleansing 클렌징"
                  />
                </h3>
                <p class="txt-card-bodycare">
                  1초에 35.5만 회 초음파 진동으로 피부 속 노폐물을부드럽고 말끔하게 씻어내는 클렌징 디바이스 워시팝<br/> 
                  1초에 37만회 미세초음파로 더 세밀하고 강력한 클렌징 디바이스 워시멜로 
                </p>
              </div>

              <ul class="img-bodycare-list">                     
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416112' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_cleansing_01.png"
                      class="m-show fr-fic fr-dii"
                      alt="Wash Pop 워시팝" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_cleansing_01.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Wash Pop 워시팝"
                  /></nuxt-link>
                </li>
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416132' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_cleansing_02.png"
                      class="m-show fr-fic fr-dii"
                      alt="Wash Mellow 워시멜로" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_cleansing_02.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Wash Mellow 워시멜로"
                  /></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-bodycare">
              <div class="txt-outer">
                <h3 class="tit-card-bodycare">
                  <img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_bodycare3.png"
                    class="m-show fr-fic fr-dii"
                    alt="Boosting 부스팅"
                  /><img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_bodycare3.svg"
                    class="pc-show fr-fic fr-dii"
                    alt="Boosting 부스팅"
                  />
                </h3>

                <p class="txt-card-bodycare">특허 받은 초음파 기술로 클렌징과 부스팅을 동시에 빠르고 깊은 수분 케어를 도와주는 2 in 1 디바이스</p>
              </div>

              <ul class="img-bodycare-list">
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416114' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_boosting_01.png"
                      class="m-show fr-fic fr-dii"
                      alt="Essential Booster 에센셜 부스터" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_boosting_01.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Essential Booster 에센셜 부스터"
                  /></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="card-bodycare">
              <div class="txt-outer">
                <h3 class="tit-card-bodycare">
                  <img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/m_tit_swiper_bodycare4.png"
                    class="m-show fr-fic fr-dii"
                    alt="Medical Device 메디컬 디바이스"
                  /><img
                    src="https://img2.lgpral.kr/pral/pc/resource/main/img/text/tit_swiper_bodycare4.svg"
                    class="pc-show fr-fic fr-dii"
                    alt="Medical Device 메디컬 디바이스"
                  />
                </h3>

                <p class="txt-card-bodycare">
                  48주 임상으로 확인된 쓰면 쓸수록 개선되는 모발 밀도와 굵기 집에서 하는 개인 맞춤 탈모치료 의료기기 메디헤어<br/>
                  개인 맞춤 통증 케어로 완화시켜주는 의료기기 메디페인
                </p>
              </div>

              <ul class="img-bodycare-list">
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416116' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_device_01.png"
                      class="m-show fr-fic fr-dii"
                      alt="Medi Hair 메디헤어" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_device_01.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Medi Hair 메디헤어"
                  /></nuxt-link>
                </li>
                <li>
                  <nuxt-link :to="{ path:'/products/detail/26416117' }"
                    ><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/mo_device_02.png"
                      class="m-show fr-fic fr-dii"
                      alt="Medi pain 메디페인" /><img
                      src="https://img2.lgpral.kr/pral/resource/images/main/pc_device_02.png"
                      class="pc-show fr-fic fr-dii"
                      alt="Medi pain 메디페인"
                  /></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="btn-direction-box">
          <div class="swiper-button-prev">
            <br />
          </div>
          <div class="swiper-button-next">
            <br />
          </div>
        </div>
      </div>
    </div>
  </article>
  <div class="ad-foot">
    <div class="ad-inner">
      <h4>오프라인 매장에서&nbsp; <br class="m-show" />LG 프라엘을 체험해보세요.</h4>
      <nuxt-link :to="{ path:'/eventExhibition/1466' }" class="btn-ad-foot" style="display: inline-block"
        ><span>체험 매장 예약</span></nuxt-link
      >
    </div>
  </div>
</div>
```