<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>沸油</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            沸油是<nuxt-link to="/civs/Persians">波斯</nuxt-link
            >的特殊技術，可於<nuxt-link to="/techs/age/Castle_Age"
              >城堡時代</nuxt-link
            >在
            <nuxt-link to="/building/Castle">城堡</nuxt-link
            >研發，研發後<nuxt-link to="/building/Castle">城堡</nuxt-link
            >對<nuxt-link to="/armor/Armor_Class_Ram">衝撞車系</nuxt-link
            >的傷害+9。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>城堡一直都害怕衝撞車，這個科技讓城堡稍微具有一些防禦力。</li>
            <li>
              要注意，+9傷害只影響第一支箭，也就是說不論駐紮多少單位在城堡，也只有總共+9的傷害。
            </li>
            <li>
              這個科技的效果不是很好，但也不是很貴，如果有多餘資源是可以研發的，但大多數時候拿這些資源來建造城鎮中心會更有用。
            </li>
            <li>
              研發這個科技後，城堡雖然對衝撞車有些許防禦力，但面對大量衝撞車仍然需要步兵的保護，切記不要讓城堡單獨面對衝撞車。
            </li>
          </ul>
        </div>
        <h3>趣事</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>明明稱作沸油，但是卻用箭矢來造成傷害。</li>
            <li>
              就算研發此項科技，在沒有垛孔的狀況下，城堡沒有辦法對已經在最小範圍內的衝撞車造成傷害(就不能直接把油潑上去嗎?!)。
            </li>
            <li>
              所謂沸油，其實是燃燒的油，而不僅僅是沸騰，否則殺傷力其實不高。
            </li>
            <li>
              真正的中世紀，幾乎所有城堡都會用燃燒的油用來對付衝撞車或雲梯，為甚麼是波斯的特殊技術仍有待調查。
            </li>
          </ul>
        </div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Berbers">柏柏</nuxt-link>：<nuxt-link
                to="/techs/Kasbah"
                >聚居堡壘</nuxt-link
              >能夠加速沸油的研發速度(+25%)。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">沸油</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/CastleAgeUnique.png" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">
                <nuxt-link to="/techs">科技介紹</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Persians">波斯</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Castle-age-reseach.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">
              <img class="gg" src="~assets/Castleicon.png" alt="" /><nuxt-link
                to="/building/Castle"
                >城堡</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">研發時間</td>
            <td class="unit4">40秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">木材</td>
            <td class="unit4">200</td>
          </tr>
          <tr>
            <td class="unit3">石頭</td>
            <td class="unit4">100</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">影響</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">城堡對於衝撞車系傷害+9</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由Dennis協助編輯</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alltech',
  components: {}
}
</script>
<style></style>
