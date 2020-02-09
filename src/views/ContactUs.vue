<template>
  <div class="home">
    <h1 class="mainTitle">
      Contact Information:
    </h1>
    <table class="ml-10">
      <tr>
        <td class="imageBox">
          <img alt="Vue logo" src="../assets/WebsiteLogoTest.png">
        </td>
        <td class="leftMargin informationBox">
          <h2>Clay Moyer, CEO:</h2>
          <p class="caption whitesmoke">
            Email: placeholder 
          </p>
          <p class="caption whitesmoke">
            Phone: placeholder 
          </p>
          <p class="caption whitesmoke">
            Linkdin: placeholder 
          </p>
        </td>
      </tr>
    </table>
    <table class="ml-30">
      <tr>
        <td class="imageBox">
          <img alt="Vue logo" src="../assets/WebsiteLogoTestBlue.png">
        </td>
        <td class="leftMargin informationBox">
          <h2>Tim Flavin, CTO:</h2>
          <p class="caption whitesmoke">
            Email: tcf2657@gamil.com  
          </p>
          <p class="caption whitesmoke">
            Phone: placeholder 
          </p>
          <p class="caption whitesmoke">
            Linkdin: placeholder 
          </p>
        </td>
      </tr>
    </table>
    
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  </div>
</template>

<style scoped>
p{
  text-align: left;
}
.home{
  background-color: #4c5f72;
  padding-bottom: 10%;
}
.imageBox{
  padding-left:5%;
  padding-right:2%;
}
.leftMargin{
  padding-left:5%;
}
.caption{
  width:40ch;
  margin-top: 2%;
}
.mainTitle{
  font-size:400%;
  margin-block-end: 5%;
  font-family: simplifica;
  color:whitesmoke;
}
.goldenrod{
  color: goldenrod;
  font-family: 'Acme', sans-serif;
}
.whitesmoke{
  color: whitesmoke;
}
table{
  width: 60%;
  border-collapse: collapse;
  margin-bottom:5%;
}
.ml-10{
  margin-left: 10%;
}
.ml-30{
  margin-left:30%;
}
h2{
  display: table-row;
  
}
.informationBox{
  
  
  background-color: #8190a0;
  padding-top: 3ch;
  padding-right: 10%;
  margin-top: 0%;
  vertical-align: 0%;
}
tr{
  border-spacing: 0;
  border-collapse:collapse;
  border-style:solid;
  border-color: black;
  border-width: 2px;
}
</style>