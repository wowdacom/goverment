<template>
  <div id="footer">
    <div class="footer-container">
      <div class="footer-link-container">
        <span class="footer-link footer-right-board">
          <a href="http://www.udngroup.com/" target="_blank">聯合報系</a>
        </span>
        <span class="footer-link footer-right-board">
          <a href="http://udndata.com/udnauthority.html" target="_blank">新聞授權</a>
        </span>
        <span class="footer-link">
          <a href="http://www.udngroup.com/members/udn_privacy" target="_blank">隱私權聲明</a>
        </span>
      </div>
      <div class="fan-group-container">
        <span class="footer-fan-group">追蹤我們</span>
        <a class="fan-group-icon" href="https://www.facebook.com/udnplus" target="_blank"><font-awesome-icon :icon="['fab', 'facebook-square']" /></a>
        <a class="fan-group-icon" href="https://www.instagram.com/udngroup" target="_blank"><font-awesome-icon :icon="['fab', 'instagram']" /></a>
        <a class="fan-group-icon" href="https://www.youtube.com/channel/UCEt9Vy6Kz4GKlePLgIJbtoA" target="_blank"><font-awesome-icon :icon="['fab', 'youtube']" /></a>
      </div>
    </div>
  </div>
</template>

<script>
import { library } from '@fortawesome/fontawesome-svg-core'
import { faInstagram, faFacebookSquare, faYoutube } from '@fortawesome/free-brands-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

library.add(faInstagram, faFacebookSquare, faYoutube)

export default {
  name: 'foot',
  data () {
    return {}
  },
  props: {

  },
  components: {
    'font-awesome-icon': FontAwesomeIcon
  },
  computed: {

  },
  mounted () {
    let vm = this
    setTimeout(()=>{ vm.barLength = vm.optionNumber}, 1)
  }
}
</script>

<style lang="scss" scoped>
  #footer{
    position: relative;
    z-index: 50;
    width: 100%;
    background-color: #f7f6f6;
    padding-top: 20px;
    border-top: 1px solid #DCDDDD;
    border-top-width: 80%;
    padding-bottom: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .footer-container{
    max-width: 880px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    @media screen and (min-width: 1024px){
      flex-direction: row;
    }
  }
  .footer-link-container {
    width: 100%;
    padding: 0 10px;
    a{
      text-decoration: none;
      color: #2d2d2d;
    }
    @media screen and (min-width: 1024px){
      width: 50%;
    }
    .footer-link{
      line-height: 1;
      font-size: 16px;
      padding: 0 8px 0 4px;
      @media screen and (min-width: 1024px){
        padding: 0 10px 0 5px;
      }
    }
    .footer-right-board{
      border-right: 1px solid #A3A3A3;
    }
  }
  .fan-group-container {
    width: 100%;
    padding: 0 10px;
    display: flex;
    align-items: center;
    @media screen and (min-width: 1024px){
      width: 50%;
      justify-content: flex-end;
    }
    .footer-fan-group
    {
      font-size: 16px;
      color: #7c7b7a;
      margin: 0 5px;
    }
    .fan-group-icon {
      font-size: 24px;
      color: #7c7b7a;
      margin: 0 5px;
    }
  }
</style>