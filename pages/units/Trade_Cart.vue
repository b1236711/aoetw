<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>貿易車隊</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            貿易車隊於 <nuxt-link to="/building/Market">市集</nuxt-link>訓練，在
            <nuxt-link to="/techs/age/Feudal_Age">封建時代</nuxt-link
            >就可以生產。
          </p>
          <p>
            貿易車隊在兩個文明或以上之間貿易而生產黃金，但事實上，這並不涉及資源上的交換，一輛空的空的貿易車會從自己的市集出發到其他文明的市集並帶回黃金。而黃金的量取決於兩個市場的距離，越遠黃金就越多，反之。
          </p>
          <p>
            有趣的是貿易車不只只能和同盟國貿易甚至是中立、敵方的文明；當然除非敵方已經棄權，否則和敵對貿易是相當不明智的。
          </p>
          <p>
            貿易車每移動五格的距離就會生產出1單位的黃金，如果以最遠距離計算的話，一次可以得大的最大金額為517單位。
          </p>
          <p>
            在地圖上的黃金礦是相當有限的，在遊戲中後期時貿易是取得黃金的一項重要來源，所以請保護好自己的貿易路線，以防成為敵方的主要攻擊目標。在大後期決戰中，往往決定勝負的關鍵都在於貿易車隊有無安全的運行。
          </p>
          <h3>貿易的時機</h3>
          <p>
            通常實戰中，點下帝王的瞬間就會開始著手貿易車隊的運行，如太早進行貿易則會損害經濟，無法抵禦對手，而太晚貿易則會缺乏黃金。
          </p>
        </div>
        <h3></h3>
        <div class="hrn1"></div>
        <div class="n1"></div>
        <h3></h3>
        <div class="hrn1"></div>
        <div class="n1"></div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Spanish">西班牙</nuxt-link
              >：貿易單位所獲取的黃金單位增加25%。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">
                貿易車隊
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/TradeCartIcon.jpg" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Villager">村民</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">所有文明</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <nuxt-link to="/techs/age/Feudal_Age">封建時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練於</td>
            <td class="unit4">
              <nuxt-link to="/building/Market">市集</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">51秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">木</td>
            <td class="unit4">100</td>
          </tr>
          <tr>
            <td class="unit3">金</td>
            <td class="unit4">50</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2"><nuxt-link to="">數據</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">70</td>
          </tr>
          <tr></tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3"><nuxt-link to="">遠防</nuxt-link></td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">7</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由小蝦協助編輯</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allunit',
  components: {}
}
</script>
<style></style>
