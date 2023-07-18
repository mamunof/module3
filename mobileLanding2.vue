<script setup>

const hOneTeg = "Deffernt Type of Mobile";

const phoneInfo = [
    {
        hFourTeg : "Android Phone",
        image : "https://storage.googleapis.com/gweb-uniblog-publish-prod/images/1._Android_12_Keyword_Header.width-1300.jpg",
        alter : "Android Phone",
        hThreeTeg : "World-Class and World wide Phone",
        pTeg : "Joining us from all around the world are over twenty fantastic speakers, here to share their stories."
    },
    {
        hFourTeg : "Ios Phone",
        image : "https://support.apple.com/library/content/dam/edam/applecare/images/en_US/iphone/iphone-14-pro-max-colors.png",
        alter : "Ios Phone",
        hThreeTeg : "World-Class and World wide Phone",
        pTeg : "Enjoy Use inspiring and action-packed days of tals, gatherings, and all-around good times."
    },
    {
        hFourTeg : "Button Phone",
        image : "https://images.hindustantimes.com/img/2022/08/25/1600x900/Most_Popular_Samsung_2G_Mobile_Phones__1661430051632_1661430051974_1661430051974.jpg",
        alter : "Button Phone",
        hThreeTeg : "World Wide Selling",
        pTeg : "Not only in this country this phone user but also all over the world usese this type of Phone."
    }

]

</script>

<template>
 	<!------ middel section ARIYA start ------->

     <section id="middel">
	<h1>{{ hOneTeg }}</h1>
	<div class="col-3">
		<div class="col-1">
			<h4>{{ phoneInfo[0].hFourTeg }}</h4>
			<img v-bind:src="phoneInfo[0].image" :alt="phoneInfo[0].alter">
			<h3>{{ phoneInfo[0].hThreeTeg }}</h3>
			<p>{{ phoneInfo[0].pTeg }}</p>
		</div>

		<div class="col-1">
			<h4>{{ phoneInfo[1].hFourTeg }}</h4>
			<img :src="phoneInfo[1].image" :alt="phoneInfo[1].alter">
			<h3>{{ phoneInfo[1].hThreeTeg }}</h3>
			<p>{{ phoneInfo[1].pTeg }}</p>
		</div>

		<div class="col-1">
			<h4>{{ phoneInfo[2].hFourTeg }}</h4>
			<img :src="phoneInfo[2].image" :alt="phoneInfo[0].alter">
			<h3>{{ phoneInfo[2].hThreeTeg }}</h3>
			<p>{{ phoneInfo[2].pTeg }}</p>
		</div>
	</div>
</section>
	<!------ middel section ARIYA end ------->


</template>

<style>

/******** meddel id strat now ******/

section#middel {
	padding: 40px 0 40px 0;
	background-color: #ffffff ;
	overflow: hidden;
	font-family: 'Source Sans Pro', sans-serif;
}
#middel h1 {
    text-align: center;
    margin-bottom: 45px;
}
.col-3 {
    margin: 0px 20px;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
}
.col-1 {
    width: 300px;
    margin: 0px 20px;
}
.col-1 img {
    width: 100%;
    height: 200px;
    border-radius: 10px;

}


/******** meddel id end here ******/

</style>
