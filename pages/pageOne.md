---
layout: page
permalink: /
---

<div class="wrapper">

	<div class="boxOne">
		<h2 class="boxText">This is box #1</h2>
	</div>

	<a href="/pageTwo/">
		<button class="buttonOne">
			<h2>this is a button</h2>
		</button>
	</a>
</div>

<style type="text/css">

	.boxText{
		position: relative;
	    top: 50%;
	    transform: translateY(-50%);
	}
	
	.boxOne{
		background-color: lightgreen;
		float:left;
		width: 45%;
		height: 450px;
		border-radius: 50px 50px;
		text-align: center;

	}
	.buttonOne{
		background-color: lightgreen;
		float: right;
		width: 45%;
		height: 450px;
		border-radius: 50px 50px;
	}

	.wrapper{
		padding: 2px 2px;
		

	}
	
</style>