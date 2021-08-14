*{
margin: 0;
padding: 0;
}

body{
  color:#000;
  background-color:#fff;
  font-size:16px;
  font-family:Gothic;
  line-height:1.9;
  text-decoration:none;
}

.wrapper{
max-width:1000px;
min-width:750px;
height:auto;
margin-left:auto;
margin-right:auto;
}


#container{
  display: flex;
}

.main , .aside{
  display: inline-block;
}
.main  { flex-grow: : 1; }
.aside { flex-grow: : 3; }

.text-none{
  text-indent:100%;
  	white-space:nowrap;
  	overflow:hidden;
}

p:not(.book-main){
  margin: 15px 10px;
}

section{margin: 20px 10px;}

article{margin: 20px 10px;}

/*タイトル部分*/

.header{
  width: 100%;
 height: auto;
 background-color: #fff;
 position: relative;
}
.inner{
  display: flex;
  align-items: stretch;
  justify-content: space-between;
  align-items: flex-start;
}


h1{
font-size: 1em;
font-weight: 800;
line-height: 1.6;
}

h1 > span
{
font-size: 1.2em;
font-weight: 600;
margin-right:10px;
}

header > .img{
width: 60%;
height: auto;
object-fit: cover;
text-align: center;

position: absolute;
top:5%;
left:80%;
}


/*ナビ*/
 .header-nav{
width: 100%;
 }

.nav-ul {
  display:flex;
  justify-content: space-between;
  font-weight: 600;
  font-size: 0.8em;
  margin: 0;
  background-color:#b8ccc4;
  list-style: none;
}

.nav-menu{
padding:3vh 3vh;
}

.nav-menu:hover {
background-color:#ececec;
 }

/*パンくず*/

.breadcrumb{
margin: 20px;
color:#cccccc;
}

/* コンテンツ説明 */

h2 > span{
background-color:#00e8aa;
margin: 5px 5px;
padding: 10px 10px;
color: #fff;
font-size: 0.8em;
}

.contents > h2 {
color:00e8aa;
line-height: 2;
}

h2 > .strong {
color: #000;
font-size: 2em;
}

.menu-contents {
  font-size: 1.2em;
  margin-left: 20%;
  padding: 60px 60px;
  background-color:#ececec;
 display: inline-block;
}

.nav-menu{
  text-align: left;
}

/* メニュー */

h3{
  font-size: 1.6em;
  font-weight: bold;
  border-bottom-style:solid;
  border-color:#63e8e3;
  border-width: 1px;
}

h4{
  padding: 0px 5px;
  border-left-style:solid;
  border-color:#63e8e3;
  border-width:10px;
}

article > ol{
  border: 1px solid;
}


/*サイドバー*/
.aside{
  width: calc(100% - 100px);
  background-color:#b8ccc4;
  color: #000;
  padding: : 10px 10px;
  margin-left: 0;
  margin-right:0;
}

.aside-wrapper {
  width: 80%;
  height:auto;
  margin: 0 auto;
  display: block;
  justify-content:
}
.book-image{
  text-align: center;
}

.book-title{
font-weight: 700;
font-size: 1.2em;
}

.book {
font-size: 1.6em;
margin: 10px 10px;
text-align: center;
}
.book-title .book-title-sub {
  line-height: 1.5;
}

.book-main{
  font-size: 0.8em;
  line-height:1.5 ;
 margin: 10px 0px;}


/*フッター*/
footer{
  width:100%;
  height:50px;
  background-color:#63e8e3;
  color: #000;
　display: block;
}

footer > .credit{
  text-align: right;}

