<script setup>
const listAnchor = [
	{
		home : "home",
		spkeakers: "spkeakers",
		shedule : "shedule",
		venu : "venu",
		register : "register",
	}
]

const hOneTeg = "Mobile Page"
const hTwoTeg = "Mobile Landing  Building Websites"
const hThree ="July 18th — Bnagladesh Phone Sector";
const pTeg = "Every day and year the brightest web designers and front-end developers descend on Bnagladesh to discuss the latest tech logies. Join us this july market!";
const registerNow = "REGISTER NOW";

</script>

<template>
        	<!------ LANDING ARIYA strat here------->
<section id="topper">
	<div class="container">
		<div class="landing_ber">
			<div class="logo">
				<a href="#"><h1>{{ hOneTeg }} </h1></a>
			</div>
			<div class="menu">
				<h3>{{ hThree }}</h3>
				<nav>
					<ul>
						<li><a href="index.html">{{ listAnchor[0].home }}</a></li>
						<li><a href="#">{{ listAnchor[0].spkeakers }}</a></li>
						<li><a href="#">{{ listAnchor[0].shedule }}</a></li>
						<li><a href="#">{{ listAnchor[0].venu }}</a></li>
						<li><a href="#">{{ listAnchor[0].register }}</a></li>
					</ul>
				</nav>
			</div>
		</div>

		<!------ LANDING ARIYA ------->
		
		<div class="landing_info">
			<h2>{{ hTwoTeg }}</h2>
			<p>{{ pTeg }}</p>
			<a href="#">{{ registerNow }}</a>
		</div>
	</div>
</section>
	<!------ LANDING ARIYA end ------->

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200;300;400;600;700;900&display=swap');

body{
	margin: 0;
}

/******** Index form strat here *******/


section#topper {
	/* overflow: hidden; */
	font-family: 'Source Sans Pro', sans-serif;
	background-image: url(https://www.ibm.com/content/dam/connectedassets-adobe-cms/worldwide-content/stock-assets/getty/image/photography/be/41/bld157519.jpg/_jcr_content/renditions/cq5dam.web.3840.3840.jpeg);
	background-size: cover;
	background-repeat: no-repeat;
	padding: 20px;
	width: auto;
	margin: auto;
}

section#topper .container {
	max-width: 1100px;
	margin: 60px auto;
	padding: 0 20px;

}

/******** LANDING ARIYA ********/

.landing_ber{
	overflow: hidden;
	margin-bottom: 60px;
    display: flex;
    justify-content: space-between;
	
}
.landing_ber .logo {
	/* float: left;
	overflow: hidden; */
	width: 335px;
	
}

.logo a {
	text-decoration: none;
}

.logo h1{
	text-transform: uppercase;
	color: #817676;
	font-weight: 100;
	font-size: 60px;
	margin: 0px 0 10px 0px;
	line-height: 50px;
	cursor: pointer;	
}

.logo h1:hover{
	color: #295C74;
}

.landing_ber .menu h3{
	font-weight: 100;
	color: #161515;
	font-size: 22px;
	text-align: right;
	margin-top: 0px;
}

.menu ul {
	list-style: none;
	margin-top: 0px;
	margin-bottom: 0px;
	padding: 0px;
}
.menu ul li {
	display: inline-block;
	padding: 0px 0px 0 20px;
}

.menu ul li a {
	text-decoration: none;
	color: #817676;
	text-transform: uppercase;
}

.menu ul li a:hover {
	color: #295C74;

}

/********  LANDING_info here*********/


.landing_info {
	text-align: center;
	margin-bottom: 30px;
	padding: 0 20px;
}
.landing_info h2 {
	font-size: 40px;
	color: #161515;
	font-weight: 100;
	margin-bottom: 0;
}

.landing_info p {
	color: #161515;
	font-weight: 100;
	margin-top: 5px;
	font-size: 27px;
	line-height: 45px;
	margin-bottom: 45px;
}

.landing_info a {
	border:1px solid #ffffff;
	text-decoration: none;
	color: #817676;
	padding: 20px 35px;
	border-radius: 8px;
}

.landing_info a:hover{
	background: #ddd;
	color: #64887A;
}

/********LANDING info end here*********/
</style>
