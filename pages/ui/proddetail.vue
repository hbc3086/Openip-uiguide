<template>
  <div class="port_detail">
    <h1 class="blind">포트폴리오 - 자세히보기</h1>
    <div class="location">
      <div class="inner">
        <nuxt-link to="" class="btn_ico b_home">홈</nuxt-link>
        <nuxt-link to="">산업분류</nuxt-link>
        <nuxt-link to=""><b>정밀생산기계</b></nuxt-link>
      </div>
    </div>
    <section class="container">
      <div class="area">
        <div class="inner">
          <div class="i_left prod">
            <div class="tit">
              <h1>의료용 로봇 및 의료서비스 로봇 특허</h1>
              <p>상품번호 : L00000102691</p>
              <div class="desc">정부에서는 2019년 수립된 3차 지능형 로봇 기본계획을 통해 물류, 의료, 웨어러블, 돌봄 등 4대 서비스 로봇분야를<br/>집중적으로 육성하고 있습니다. 의료 서비스 산업에 로봇공학 기술을 적용하면 오류는 물론 비용도 최소화할 수 있다는 장점이 있습니다.<br/>4차 산업혁명시대, 기술의 급속한 발전과 함께 이루어진 로봇과 의료 서비스의 융합을 서울대학교에서 출원한 기술 특허로 만나보세요.</div>
            </div>
            <div class="cont">
              <div class="c_top">
              <dl>
                <dt>제&nbsp;&nbsp;공&nbsp;&nbsp;자</dt><dd>서울대학교산학협력단, 전남대학교산학협력단</dd>
              </dl>
              <dl>
                <dt>이전방식</dt><dd>시제품 포함</dd>
              </dl>
              <dl>
                <dt>특허등급</dt><dd>-</dd>
              </dl>
              <dl>
                <dt>특&nbsp;&nbsp;허&nbsp;&nbsp;수</dt><dd>8개</dd>
              </dl>
              </div>
              <div class="c_bottom">
                <div class="b_top">
                  <p>연차료 관리</p>
                  <button class="btn l_blue">+ 자세히</button>
                </div>
                <div class="desc">OPEN-IP 연차료 관리 서비스는 기업체, 연구소, 대학 등이 보유한 전세계 특허권에 대하여 데이터를 관리하고, 각국 특허청에 권리 유지를 위한 연차료 납부를 대행하며, 연차료관리+특허가치평가+특허등급평가+기술이전] 을 ONE-STOP 서비스를 제공합니다.</div>
              </div>
            </div>
          </div>
          <div class="i_right">
            <div class="ipt_slct">
              <div class="bx_slct">
                <p>신청특허</p>
                <Select defaultTitle="선택해주세요"
                :itemList="[
                  { name: '셀렉트1' },
                  { name: '셀렉트2'},
                  // { name: '셀렉트2', select:true},
                  { name: '셀렉트3' },
                  { name: '셀렉트4' },
                ]"/>
              </div>
              <div class="bx_slct">
                <p>거래조건</p>
                <Select defaultTitle="선택해주세요"
                :itemList="[
                  { name: '셀렉트1' },
                  { name: '셀렉트2'},
                  // { name: '셀렉트2', select:true},
                  { name: '셀렉트3' },
                  { name: '셀렉트4' },
                ]"/>
              </div>
              <div class="bx_slct">
                <p>지급조건</p>
                <Select defaultTitle="선택해주세요"
                :itemList="[
                  { name: '셀렉트1' },
                  { name: '셀렉트2'},
                  // { name: '셀렉트2', select:true},
                  { name: '셀렉트3' },
                  { name: '셀렉트4' },
                ]"/>
              </div>
              <div class="bx_ipt">
                <p>거래금액</p>
                <input type="text" class="ipt" placeholder="입력하세요"/>
              </div>
              <div class="bx_ipt">
                <p>기&nbsp;&nbsp;업&nbsp;&nbsp;명</p>
                <input type="text" class="ipt" placeholder="입력하세요"/>
              </div>
              <div class="bx_ipt">
                <p>담&nbsp;&nbsp;당&nbsp;&nbsp;자</p>
                <input type="text" class="ipt" placeholder="입력하세요"/>
              </div>
              <div class="bx_ipt">
                <p>메&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;모</p>
                <input type="text" class="ipt" placeholder="입력하세요"/>
              </div>
            </div>
            <div class="btns">
                <NuxtLink to="" class="btn l_black b_round">신청하기</NuxtLink>
                <NuxtLink to="" class="btn_ico b_cart b_gray">장바구니</NuxtLink>
              </div>
          </div>
          <div class="i_bottom">
            <p>이용중인 고객</p>
            <div class="btns">
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
            </div>
            <p>유사기술이용 고객</p>
            <div class="btns">
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
            </div>
            <p>추천고객</p>
            <div class="btns">
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
              <button class="btn">(주) 오디존</button>
              <button class="btn">(주) 웨이브온</button>
              <button class="btn">(주) 휴맥스</button>
              <button class="btn">디지맥코포레이션</button>
              <button class="btn">디티에스엘엘씨</button>
              <button class="btn">디티에스워싱턴엘엘씨</button>
            </div>
          </div>
        </div>
      </div>
      <div class="area">
        <div class="inner">
          <h1>연관 포트폴리오</h1>
          <div class="list">
            <div class="item" v-for="i in 3" :key="i">
              <div class="thumb">
                <span class="label">평가등급 : AA</span>
                <div class="detail">
                  <button class="btn b_black b_round">자세히 보기</button>
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
                <button class="btn_ico b_dibs">1,550</button>
              </div>
              <div class="btns">
                <NuxtLink to="" class="btn l_black b_round">신청하기</NuxtLink>
                <NuxtLink to="" class="btn_ico b_cart b_gray">장바구니</NuxtLink>
              </div>
            </div>
          </div>
          <div class="btns">
            <button class="btn l_gray">+ 더보기</button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import CheckBox from "~/components/form/CheckBox";
import Select from "~/components/form/Select";
export default {
  components: {
    CheckBox,
    Select
  },

}
</script>

<style>

</style>