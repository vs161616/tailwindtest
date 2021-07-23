<!-- Please remove this file from your project -->
<template>
  <div class="relative bg-white w-auto">
    <!-- <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet"> -->
    <div class="main flex flex-col h-screen">
      <header>
        <div class="fullCoversd">
            <div class="top_border"></div>
            <div class="flex items-center justify-end px-7 toploginbar">
              <p class="m-0 text-sm color_theme">Login</p>
            </div>
        </div>
      </header>
      <main class="flex-1 overflow-y-auto">
        <div class="fullCover">
          <div class="containt_deine text-center mt-0 pt-1">
          <h3 class="text-5xl m-0 tracking-wide leading-snug font-semibold ThemeTextColor">Deine Job <br> website</h3>
        </div>
        <div class="imagepart">
          <img src="assets/img/undraw_agreement_aajr.svg"/>
        </div>
        </div>

        <div class="nav_bars mt-10 mb-5">
          <div class="navesbars">
              <ul>
                <li>Arbeitgeber</li>
                <li>Arbeitgeber</li>
                <li class="active_hn">Temporärbüro</li>
              </ul>
          </div>
        </div>

        <div class="containt_deine text-center pt-3">
            <h3 class="text-2xl m-0 font-semibold ThemeTextColor">Drei einfache Schritte zur <br> Vermittlung neuer Mitarbeiter</h3>
        </div>

        <div class="relative h254">
            <div class="flex justify-end pr-10 relative z-10">
                <img src="assets/img/undraw_Profile_data_re_v81r.svg"/>
            </div>

            <div class="flex justify-end pr-20 mr-8">
              <div class="round_cercle">
                <h1 class="custom_f">1.</h1>
              </div>
              <div class="subtext relative z-10 pt-5">
                <p class="m-0 text-base text-colors">Erstell dein <br> Unternehmensprofil</p>
              </div>
            </div>

        </div>

        <div class="relative secound_box px-10 pb-10">
          <div class="flex justify-between">
              <div class="inner_text">
                <h1 class="custom_f">2.</h1>
              </div>
              <div class="subtext pt-5 items-end flex justify-end mb-10">
                <p class="m-0 text-base text-colors">Erhalte Vermittlungs- <br> angebot von Arbeitgeber</p>
              </div>
          </div>
          <div class="flex justify-end pr-10 relative z-10">
                <img src="assets/img/undraw_job_offers_kw5d.svg"/>
            </div>
        </div>

        <div class="relative px-10 pb-10">
        <div class="gouls"></div>
          <div class="flex justify-between relative z-10">
              <div class="inner_text">
                <h1 class="custom_f">3.</h1>
              </div>
              <div class="subtext pt-5 items-end flex justify-end mb-10 mr-12">
                <p class="m-0 text-base text-colors">Vermittlung nach <br>  Provision oder <br> Stundenlohn</p>
              </div>
          </div>
          <div class="flex justify-end pr-10 relative z-10">
                <img src="assets/img/undraw_business_deal_cpi9.svg"/>
            </div>
        </div>
        </main>
        <footer class="bg-white bottomfooter flex items-center justify-center px-7">
            <button class="font-medium py-2 px-4 rounded w-full ThemeBTn">
              Kostenlos Registrieren
            </button>
        </footer>
    </div>
  </div>
</template>

<style scoped>
  .toploginbar {
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #00000029;
    border-radius: 0px 0px 12px 12px;
    height: 67px;
}
.top_border {
background: transparent linear-gradient(91deg, #319795 0%, #3182CE 100%) 0% 0% no-repeat padding-box;
height: 5px;
}
.color_theme {
  color: #319795;
}
.fullCover {
  background: transparent linear-gradient(141deg, #EBF4FF 0%, #E6FFFA 100%) 0% 0% no-repeat padding-box;
}
.containt_deine {
    margin-bottom: 18px;
}
.ThemeTextColor{
  color: #2D3748;
}
.bottomfooter {
  background: #FFFFFF 0% 0% no-repeat padding-box;
  box-shadow: 0px -1px 3px #00000033;
  border-radius: 12px 12px 0px 0px;
  height: 128px;
}
.ThemeBTn {
    background: transparent linear-gradient(
95deg
, #319795 0%, #3182CE 100%) 0% 0% no-repeat padding-box;
    border-radius: 12px;
    height: 40px;
    color: #E6FFFA;
    font-size: 17px;
}
.h254{
height: 254px;
}
.round_cercle {
    background: #F7FAFC 0% 0% no-repeat padding-box;
    width: 208px;
    height: 208px;
    border-radius: 50%;
    position: absolute;
    top: 45px;
    left: -25px;
}
h1.custom_f {
    font-size: 130px;
    color: #718096;
    font-weight: 500;
    display: flex;
    justify-content: center;
    align-items: center;
}
.text-colors {
    color: #718096;
    line-height: 1.1;
}
.secound_box{
  background: transparent linear-gradient(134deg, #E6FFFA 0%, #EBF4FF 100%) 0% 0% no-repeat padding-box;
}
.gouls {
    width: 304px;
    height: 304px;
    background: #F7FAFC;
    border-radius: 50%;
    position: absolute;
    left: -54px;
}
.navesbars ul li {
    width: 160px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-top: 1px solid #CBD5E0;
    border-bottom: 1px solid #CBD5E0;
    border-left: 1px solid #CBD5E0;
    color: #319795;
    font-size: 14px;
    font-weight: 500;
    max-width: 160px;
    min-width: 160px;
}
.navesbars ul {
    display: flex;
    justify-content: center;
    align-items: center;
}
.active_hn {
    background: #81E6D9 0% 0% no-repeat padding-box;
    border-radius: 0px 12px 12px 0px;
    color: #fff !important;
    font-size: 14px;
    font-weight: 500;
}
.navesbars {
    position: relative;
    left: -95px;
}
</style>
