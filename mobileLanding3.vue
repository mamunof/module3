<script setup>
const pTeg = "Styles Conference"

const listAnchor = [
	{
		home : "home",
		spkeakers: "spkeakers",
		shedule : "shedule",
		venu : "venu",
		register : "register",
	}
]
</script>

<template>
  	<!------ footer section ARIYA start ------->

<section id="footer">
	<div class="container">
		<div class="copyright">
			<p>	&#169; Styles Conference</p>
		</div>
		<div class="footer_manu">
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
</section>

</template>

<style>

/******** fotter id start here ******/

section#footer {
	background-color: #D4D0C3;
	
	font-family: 'Source Sans Pro', sans-serif;

	overflow: hidden;
}
section#footer .container {
    max-width: 880px;
    margin: 0px auto;
    padding: 0 20px;
}
.copyright {
	float: left;
	overflow: hidden;
}
.copyright p {
	padding: 30px 0px;
	/* color: #648880; */

}

.footer_manu {
	float: right;

}
.footer_manu nav {
	padding: 30px 0px;
	float: right;
}

.footer_manu ul {
	list-style: none;
	padding: 0px;
}
.footer_manu ul li {
	display: inline-block;
	padding: 0 10px;
}
.footer_manu li a {
	text-decoration: none;
	color: #000000;
	font-size: 15px;
	font-weight: 400;
	text-transform: capitalize;
}
.footer_manu li a:hover {
	color: #648880;
}
/******** fotter id end here ******/

/******** Index form End here *******/
</style>
