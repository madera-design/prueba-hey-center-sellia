<!-- eslint-disable --> 
<template>
  <div id="app" class="container-fluid c__light">
    <div class="h-menu">
      <div class="h-menu--logo">
        <svg xmlns="http://www.w3.org/2000/svg" width="70" height="70" viewBox="0 0 71.519 71.519">
              <g id="Grupo_56" data-name="Grupo 56" transform="translate(-21.7 -46.74)">
                  <path id="message-circle" d="M72.519,35.829A32.365,32.365,0,0,1,69.043,50.5,32.829,32.829,0,0,1,39.691,68.657a32.365,32.365,0,0,1-14.676-3.476L3,72.519,10.338,50.5A32.365,32.365,0,0,1,6.862,35.829,32.829,32.829,0,0,1,25.014,6.476,32.365,32.365,0,0,1,39.691,3h1.931a32.751,32.751,0,0,1,30.9,30.9Z" transform="translate(19.7 44.74)" fill="#fff" stroke="#fff" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"/>
                  <text id="HEY_" data-name="HEY!" transform="translate(40 87)" fill="#014157" font-size="18" font-family="OpenSans-Bold, Open Sans" font-weight="700"><tspan x="0" y="0">HEY!</tspan></text>
              </g>
          </svg>
      </div>
      <div class="h-menu--opciones">
          <ul class="h-menu--opciones__ul">
              <li class="h-menu--opciones__li">
                  <svg class="svg-icon" width="30" height="30">
                    <use xlink:href="/img/icons.svg#home"></use>
                  </svg>
              </li>
              <li class="h-menu--opciones__li">
                 <svg class="svg-icon" width="30" height="30">
                    <use xlink:href="/img/icons.svg#star"></use>
                  </svg>
              </li>
              <li class="h-menu--opciones__li active">
                  <svg class="svg-icon" width="30" height="30">
                    <use xlink:href="/img/icons.svg#msg"></use>
                  </svg>
              </li>
              <li class="h-menu--opciones__li">
                  <svg class="svg-icon" width="30" height="30">
                    <use xlink:href="/img/icons.svg#graf"></use>
                  </svg>
              </li>
              <li class="h-menu--opciones__li">
                  <svg class="svg-icon" width="30" height="30">
                    <use xlink:href="/img/icons.svg#config"></use>
                  </svg>
              </li>
              <li class="h-menu--opciones__li">
                <svg class="svg-icon" width="30" height="30">
                  <use xlink:href="/img/icons.svg#luna"></use>
                </svg>
            </li>
          </ul>

      </div>
      <div class="h-menu-avatar">
          <svg xmlns="http://www.w3.org/2000/svg" width="70" height="70" viewBox="0 0 80 80">
              <g id="Grupo_44" data-name="Grupo 44" transform="translate(-33 -14)">
                  <circle id="Elipse_3" data-name="Elipse 3" cx="40" cy="40" r="40" transform="translate(33 14)" fill="#00cbcc"/>
                  <g id="user" transform="translate(47 29.875)">
                  <path id="Trazado_2" data-name="Trazado 2" d="M46,30.75V25.5A10.5,10.5,0,0,0,35.5,15h-21A10.5,10.5,0,0,0,4,25.5v5.25" transform="translate(0 19.5)" fill="none" stroke="#fff" stroke-linecap="round" stroke-linejoin="round" stroke-width="4"/>
                  <circle id="Elipse_8" data-name="Elipse 8" cx="10.5" cy="10.5" r="10.5" transform="translate(15.118 3)" fill="none" stroke="#fff" stroke-linecap="round" stroke-linejoin="round" stroke-width="4"/>
                  </g>
              </g>
          </svg>
      </div>
    </div>
    <div class="main">
      <Bodymsg />
    </div>
    
  </div>
</template>

<script>
import Bodymsg from './components/Bodymsg.vue';
export default {
  name: 'App',
  components: {
    Bodymsg
  }
}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
