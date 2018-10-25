<template>
    <div class="catsBox">

<div class="wrap">
  <div class='ellipse'></div>
  <svg
   width="100%" height="100%">
  <path fill-rule="evenodd" stroke="rgb(22, 152, 217)" stroke-width="4px" stroke-linecap="butt" stroke-linejoin="miter" fill="rgb(242, 242, 242)"
   d="M310.000,482.000 L14.000,482.000 C7.373,482.000 2.000,476.627 2.000,470.000 L2.000,45.000 L45.000,2.000 L310.000,2.000 C316.627,2.000 322.000,7.372 322.000,14.000 L322.000,470.000 C322.000,476.627 316.627,482.000 310.000,482.000 Z"/>
  <image class='privet' x="-50" y="0" width="370" height="361" xlink:href="../assets/funbox_logo.png" />
  </svg>
</div>

<div class="wrap">
  <div class='ellipse'></div>
  <svg
   width="100%" height="100%">
  <path fill-rule="evenodd" stroke="rgb(22, 152, 217)" stroke-width="4px" stroke-linecap="butt" stroke-linejoin="miter" fill="rgb(242, 242, 242)"
   d="M310.000,482.000 L14.000,482.000 C7.373,482.000 2.000,476.627 2.000,470.000 L2.000,45.000 L45.000,2.000 L310.000,2.000 C316.627,2.000 322.000,7.372 322.000,14.000 L322.000,470.000 C322.000,476.627 316.627,482.000 310.000,482.000 Z"/>
  <image class='privet' x="-50" y="0" width="370" height="361" xlink:href="../assets/funbox_logo.png" />
  </svg>
</div>

<div class="wrap">
  <div class='ellipse'></div>
  <svg
   width="100%" height="100%">
  <path fill-rule="evenodd" stroke="rgb(22, 152, 217)" stroke-width="4px" stroke-linecap="butt" stroke-linejoin="miter" fill="rgb(242, 242, 242)"
   d="M310.000,482.000 L14.000,482.000 C7.373,482.000 2.000,476.627 2.000,470.000 L2.000,45.000 L45.000,2.000 L310.000,2.000 C316.627,2.000 322.000,7.372 322.000,14.000 L322.000,470.000 C322.000,476.627 316.627,482.000 310.000,482.000 Z"/>
  <image class='privet' x="-50" y="0" width="370" height="361" xlink:href="../assets/funbox_logo.png" />
  </svg>
</div>


      <!-- <div class='border'>
        <div class="feed fuagra">
            <div class='ellipse'></div>
        </div>
      </div>
      <div class='border'>
        <div class="feed fish"></div>
      </div>
      <div class='border'>
        <div class="feed chicken"></div>
      </div> -->
<!-- width="100%" height="100%" viewBox="0 0 500 500" preserveAspectRatio="xMinYMin meet" -->

  </div>
</template>

<script>
export default {
  name: 'CatsFood',
}
</script>


<style scoped>

/* .privet {
  position: absolute;
  z-index: 0;
} */

.wrap {
  position: relative;
  width: 324px;
  height: 484px;
}

.ellipse {
    border-radius: 50%;
    color: black;
    background-color: black;
    position: absolute;
    left: 204px;
    top: 388px;
    width: 81px;
    height: 81px;
}

.catsBox {
    height: 100vh;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;

}

/* .border{
    position: relative;
    width: 312px;
    height: 472px;
    border: 4px solid rgb(22, 152, 217);
    border-radius: 12px;
    background: rgb(22, 152, 217);
    clip-path: polygon(13% 0, 100% 0, 100% 20%, 100% 80%, 100% 100%, 0 100%, 0% 80%, 0 9%);
}
.feed {
    position: absolute;
    top: 0px;
    left: 0px;
    right: 0px;
    bottom: 0px;
    border-radius: 8px;
    clip-path: polygon(13% 0, 100% 0, 100% 20%, 100% 80%, 100% 100%, 0 100%, 0% 80%, 0 9%);
    background: url('../assets/Cat.png');
    background-color: rgb(242, 242, 242);
    background-size: 370px 361px;
    background-repeat: no-repeat;
    background-position: 55% 180%;
}

 .feed::after {
  content: '';
   position: absolute;
   left: 0;
   top: 0;
   border-top: 30px solid white;
   border-right: 30px solid green;
}  */



</style>
