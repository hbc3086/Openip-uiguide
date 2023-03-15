<template>
  <div class="portfolio">
    <h1 class="blind">단일상품 - 리스트페이지</h1>
    <div class="location">
      <nuxt-link to="" class="btn_ico">홈</nuxt-link>
      <nuxt-link to="">산업분류</nuxt-link>
      <nuxt-link to=""><b>정밀생산기계</b></nuxt-link>
    </div>
    <section class="container">
      <div class="inner">
        <div class="title">정밀생산기계</div>
        <div class="area_search">
          <div class="cont">
            <div class="area_check">
              <h4>판매조건</h4>
              <div class="checks">
                <CheckBox label="매매" id="chk1_1"/>
                <CheckBox label="장기대여(3년 이상)" id="chk1_2"/>
                <CheckBox label="장기대여(5년 이상)" id="chk1_3"/>
                <CheckBox label="장기대여(10년 이상)" id="chk1_4"/>
                <CheckBox label="영구 임대" id="chk1_5"/>
                <CheckBox label="단기대여(3년 이하)" id="chk1_6"/>
                <CheckBox label="단기대여(3년 이하)" id="chk1_7"/>
                <CheckBox label="단기대여(2년 이하)" id="chk1_8"/>
                <CheckBox label="단기대여(1년 이하)" id="chk1_9"/>
                <CheckBox label="기타" id="chk1_10"/>
              </div>
            </div>
            <div class="area_check">
              <h4>평가등급</h4>
              <div class="checks">
                <CheckBox label="AA" id="chk2_1"/>
                <CheckBox label="A+" id="chk2_2"/>
                <CheckBox label="A" id="chk2_3"/>
                <CheckBox label="A-" id="chk2_4"/>
                <CheckBox label="B+" id="chk2_5"/>
                <CheckBox label="B" id="chk2_6"/>
                <CheckBox label="B-" id="chk2_7"/>
                <CheckBox label="C" id="chk2_8"/>
              </div>
            </div>
            <div class="area_check">
              <h4>추천사유</h4>
              <div class="checks">
                <CheckBox label="경쟁력" id="chk3_1"/>
                <CheckBox label="투자성" id="chk3_2"/>
                <CheckBox label="미래가치" id="chk3_3"/>
                <CheckBox label="해외시장" id="chk3_4"/>
                <CheckBox label="스타트업" id="chk3_5"/>
              </div>
            </div>
            <div class="area_check">
              <h4>주요출원인</h4>
              <div class="checks">
                <CheckBox label="서울대학교" id="chk4_1"/>
                <CheckBox label="한국전자통신연구원" id="chk4_2"/>
                <CheckBox label="한화" id="chk4_3"/>
              </div>
            </div>
          </div>
          <div class="btns">
            <div class="reset">
              <p>전체초기화</p>
              <button class="btn_ico b_reset">전체 초기화</button>
            </div>
            <button class="btn b_gray">검색</button>
          </div>
        </div>
        <div class="content">
          <div class="taps_txt">
            <NuxtLink to="/test" class="tap on">포트폴리오</NuxtLink>
            <NuxtLink to="/test2" class="tap">단일상품</NuxtLink>
          </div>
          <div class="c_top">
            <p>총 <b class="txt_blue f25">10</b>개의 상품이 검색되었습니다.</p>
            <div class="right">
              <NuxtLink to="" class="btn btn_ico dibs" title="찜버튼">찜</NuxtLink>
              <div class="bx_search">
                <input type="text" class="ipt"/>
                <button class="btn_ico b_search">검색버튼</button>
              </div>
            </div>
          </div>
          <div class="list">
            <div class="item" v-for="i in 12" :key="i">
              <div class="img">
                <span class="label">평가등급 : AA</span>
                <div class="detail">
                  <button class="btn b_black">자세히 보기</button>
                </div>
              </div>
              <div class="info">
                <h4>의료용 로봇 및 의료서비스 로봇 특허</h4>
                <div class="desc">
                  종합 방산 기업인 한화디펜스의 특허입니다. 무인을 포함한 비행체 제어의 장치와 관리 방법등에 대한 특허 중 높은 기술력과 상위 등 급을 가진 특허들을 모았습니다.
                </div>
                <dl>
                  <dt>제&nbsp;&nbsp;공&nbsp;&nbsp;자</dt><dd>서울대학교산학협력단, 전남대학교산학협력단</dd>
                </dl>
                <dl>
                  <dt>특&nbsp;&nbsp;허&nbsp;&nbsp;수</dt><dd>5개</dd>
                </dl>
                <dl>
                  <dt>거래방식</dt><dd>영구임대</dd>
                </dl>
                <button class="btn_ico dibs">1,550</button>
              </div>
              <div class="btns">
                <NuxtLink to="" class="btn l_black">신청하기</NuxtLink>
                <NuxtLink to="" class="btn btn_ico b_cart b_gray">장바구니</NuxtLink>
              </div>
            </div>
          </div>
          <div class="pagination">
            <nuxt-link to="" class="b_prev">Prev</nuxt-link>
            <nuxt-link to="" class="num" v-for="i in 1" :key="i" :class="{'on' : i==2}">{{ i }}</nuxt-link>
            <nuxt-link to="" class="b_next">Next</nuxt-link>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>


<script>
import CheckBox from "~/components/form/CheckBox";

export default {
  data() {
    return {
    }
  },
  props: {
  },
  components: {
    CheckBox
  },
  computed: {

  },

  methods: {

  },
};

</script>