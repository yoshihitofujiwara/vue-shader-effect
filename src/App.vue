<template>
  <div id="app">
    <router-view/>
    <!-- <img src="./assets/logo.png"> -->
		<ul class="links">
			<!-- <li><a href="/#/distortion">Distortion</a></li> -->
			<!-- <li><a href="/#/line">Line</a></li> -->
			<li><router-link to="distortion">Distortion</router-link></li>
			<li><router-link to="line">Line</router-link></li>
		</ul>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
html,body,div,span,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,abbr,address,cite,code,del,dfn,em,ins,kbd,q,samp,small,strong,
sub,sup,var,b,i,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,
figcaption,figure,footer,header,hgroup,menu,nav,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;outline:0;font-size:100%;vertical-align:baseline;background:transparent;box-sizing: border-box;}
body{line-height:1;}
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block;}
nav ul{list-style:none;}
ul,ol,li,dl,dt,dd{list-style-type:none;list-style-position:outside;}
blockquote,q{quotes:none;}
blockquote:before,blockquote:after,q:before,q:after{content:none;}
a{margin:0;padding:0;font-size:100%;vertical-align:baseline;background:transparent;}
ins{text-decoration:none;}
img{vertical-align:middle;border:0;}
del{text-decoration:line-through;}
hr{display:block;height:0;border:0;margin:0;padding:0;}
abbr[title],dfn[title]{border-bottom:1px dotted;cursor:help;}
table{border-collapse:collapse;border-spacing:0;}
em,strong{ font-weight: bold;}
mark{background-color:#ff9;color:#000;font-style:italic;font-weight:bold;}
input,select,textarea{margin:0;padding:0;vertical-align:baseline;}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.links{
	padding-left: 30px;

	li{
		padding: 3px 0;
		list-style-type: disc;
		text-align: left;
	}
}
</style>
