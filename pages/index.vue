<template>
<div>
<First/>
<Second/>
<Last/>
</div>


</template>

<script>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@400;600;700&display=swap');

/* *,*:before,*:after {
  box-sizing: border-box;
} */

body {
  font-family: 'Montserrat Alternates', sans-serif;
  background: #EDD2C0;
}
:root{
  --color1:#EDD2C0;;
  --color2:#5E4F47;
  --color3:#117AC9;
  --color4: #FFFFFF;
}
header, footer, section {
  padding: 100px;
}
header{
  padding: 100px;
  /* основной цвет */
  background: var(--color1);
}
.itd_play:hover{
width: 275px;
height: 77px;
left: 152px;
top: 567px;

background: #117AC9;
border-radius: 50px;
} 
.btn-primary{
  position: absolute;
width: 275px;
height: 77px;
/* left: 152px;
top: 567px; */

background: #117AC9;
border-radius: 50px;
}
/* .btn-itd {
  display: block;
  max-width: 200px;
  margin: 0 auto;
  padding: 8px 30px;
  color: var(--vs-white);
  background-color: var(--color3);
}
.btn-itd:hover {
  color: var(--bs-white);
  background-color: var(--color2);
} */

.color1 {
  color: var(--color1);
}
.color2 {
  color: var(--color2);
}
.color3 {
  color: var(--color3);
}
.color4 {
  color: var(--color4);
}
.bg1 {
  background-color: var(--color1);
}
.bg2 {
  background-color: var(--color2);
}


.container {
margin: 0 auto;
padding-left:0%;
padding-right:0%;
}
/* .row {

position: absolute;
width: 1500px; 
left: 0px;
top: 0px;

} 
.col{
  width: 1500px;
} */
.second{
  background-color: var(--color2);
  /* height: 850px;
  left: 0px;
  top: 820px; */
}



</style>
