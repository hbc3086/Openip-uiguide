<template>
  <div class="ui_wrap">
    <header class="ui_header">
      <h1 class="ui_h1"><strong>오픈아이피</strong> Index Page</h1>
    </header>
    <div class="ui_container">
      <h2 class="ui_h2">구축 전 필독사항</h2>
      <div class="ui_area_notice">
        <ul>
          <li>★ 필요없는 폴더 및 파일은 정리해주세요. (ex. 00_guide, img, scss, README..)</li>
          <li>
            ★ img, scss는 아래 경로에 업로드해주세요.<br/>
            - https://s3.ap-northeast-2.amazonaws.com/static.unicornranch.co.kr/mts/프로젝트명
          </li>
          <li>자세한 구축 및 유지보수, 산출물 공유 가이드는 UI가이드를 참고해주세요.</li>
          <li class="txt_red">웹폰트는 각 프로젝트 scss에서 정의해주세요. reset의 기본폰트는 시스템폰트입니다.</li>
          <li class="txt_red">해당 가이드는 반응형 기준으로 작성되어 있습니다.</li>
        </ul>
      </div>
      <div class="ui_area">
        <h3 class="ui_h3">페이지</h3>
        <table class="ui_tbl">
          <colgroup>
            <col>
            <col width="150">
            <col width="150">
          </colgroup>
          <thead>
            <tr>
              <th>Title</th>
              <th>담당자</th>
              <th>Date</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td><NuxtLink to="/ui/guide" target="_blank" class="ui_link">모든 프로젝트 공통 UI 가이드 <em class="ui_new">new</em></NuxtLink></td>
              <td><span class="ui_label">BC</span>황병철</td>
              <td>22.3.15</td>
            </tr>
            <tr>
              <td><NuxtLink to="/ui/portfolio" target="_blank" class="ui_link">포트폴리오 - 상세페이지<em class="ui_new">new</em></NuxtLink></td>
              <td><span class="ui_label">BC</span>황병철</td>
              <td>22.3.15</td>
            </tr>
            <tr>
              <td><NuxtLink to="/ui/product" target="_blank" class="ui_link">단일상품 - 상세페이지<em class="ui_new">new</em></NuxtLink></td>
              <td><span class="ui_label">BC</span>황병철</td>
              <td>22.3.16</td>
            </tr>
            <tr>
              <td><NuxtLink to="/ui/portdetail" target="_blank" class="ui_link">포트폴리오 - 자세히보기<em class="ui_new">new</em></NuxtLink></td>
              <td><span class="ui_label">BC</span>황병철</td>
              <td>22.3.16</td>
            </tr>
            <tr>
              <td><NuxtLink to="/ui/proddetail" target="_blank" class="ui_link">단일상품 - 자세히보기<em class="ui_new">new</em></NuxtLink></td>
              <td><span class="ui_label">BC</span>황병철</td>
              <td>22.3.17</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name:"index",
  layout:"none",
  data() {
    return {
    };
  },
  components: {
  },
  mounted() {
  },
  methods: {
  },
};
</script>
<!-- 해당 페이지에서만 쓰는 css -->
<style scoped v-if="true">
  @import "//s3.ap-northeast-2.amazonaws.com/static.unicornranch.co.kr/common/css/guide.css?v=2";
</style>