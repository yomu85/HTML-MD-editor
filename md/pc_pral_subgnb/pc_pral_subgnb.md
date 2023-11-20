```html
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
          <a href="#">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_01.png"
              alt="배너1"
            />
          </a>
          <a href="#">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_02.png"
              alt="배너2"
            />
          </a>
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
          <a href="#">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_BigBanner_.png"
              alt="배너"
            />
          </a>
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
          <a href="#" class="sub_img_box">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_01.png"
              alt="상품1"
            />
          </a>
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
        </div>

        <div class="sub_menu_item type02">
          <div class="sub_title">
            <span>모공/피지</span>
          </div>
          <a href="#" class="sub_img_box">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_02.png"
              alt="상품2"
            />
          </a>
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
          <a href="#" class="sub_img_box">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_03.png"
              alt="상품3"
            />
          </a>
          <nuxt-link :to="{ path:'/products/detail/26416126' }" class="sub_txt">
            <span>메디헤어&거치대(HGN1)</span>
          </nuxt-link>
          <nuxt-link :to="{ path:'/products/detail/26416116' }" class="sub_txt">
            <span>메디헤어(HGN2V)</span>
          </nuxt-link>
        </div>

        <div class="sub_menu_item type02">
          <div class="sub_title">
            <span>통증 케어</span>
          </div>
          <a href="#" class="sub_img_box">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_product_04.png"
              alt="상품4"
            />
          </a>
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
    <nuxt-link :to="{ path:'/products/detail/26419795' }" class="main_txt">
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
          <a href="#">
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_01.png"
              alt="배너1"
            />
          </a>
          <a
            href="https://www.lge.co.kr/support/product-manuals?title=manual"
            target="_blank"
          >
            <img
              src="https://img2.lgpral.kr/pral/resource/images/main/pc_header_banner_03.png"
              alt="제품 사용 설명서"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
```
