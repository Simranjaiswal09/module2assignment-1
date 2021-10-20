<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>module2assignment</title>
	<style>
	*{
		box-sizing: border-box;
		
	}
	h1{
		margin-bottom: 15px;
		text-align: center;
	}
	
section{
		background-color: grey;
		width: 90%;
		height: 25%;
		text-align: justify;
		margin-right: auto;
		margin-left: auto;
        font-family: Helvetica;
		color: white;

		
	}
	h3.a{
		border-bottom:3px solid black;
	    border-right: 3px solid black;
	    border-left: 3px solid black;
		background-color: pink;
	    position:relative;
	    float: right;
	    bottom: 18px;
	    color: green;
		}
		h3.b{
		border-bottom:3px solid black;
	    border-right: 3px solid black;
	    border-left: 3px solid black;
		background-color: red;
	    position:relative;
	    float: right;
	    bottom: 18px;
        color: purple;	 
		}
		h3.c{
		border-bottom:3px solid black;
	    border-right: 3px solid black;
	    border-left: 3px solid black;
		background-color: blue;
	    position:relative;
	    float: right;
	    bottom: 18px;
	    color: white;
	 
		}
		p{
	position: relative;
	padding-left: 5px;
	padding-right: 5px;
	margin-left: 5px;
	overflow: auto;
	clear: right;
}

    .row{
		width: 100%;
    }
	
	@media (min-width: 992px){
		.col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12{
			float: left;
		}
		.col-lg-1{
			width: 8.33%;
		}
		.col-lg-2{
			width: 16.66%;
		}
		.col-lg-3{
			width: 25%;
		}
		.col-lg-4{
			width: 33%;
		}
		.col-lg-5{
			width: 41.66%;
		}
		.col-lg-6{
			width: 50%;
		}
		.col-lg-7{
			width: 58.33%;
		}
		.col-lg-8{
			width: 66.66%;
		}
		.col-lg-9{
			width: 75%;
		}
		.col-lg-10{
			width: 83.33%;
		}
		.col-lg-11{
			width: 91.66%;
		}
		.col-lg-12{
			width: 100%;
		}
	}
	@media (min-width: 768px) and (max-width: 991px){
		.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12{
			float: left;
		}
		.col-md-1{
			width: 8.33%;
		}
		.col-md-2{
			width: 16.66%;
		}
		.col-md-3{
			width: 25%;
		}
		.col-md-4{
			width: 33%;
		}
		.col-md-5{
			width: 41.66%;
		}
		.col-md-6{
			width: 50%;
		}
		.col-md-7{
			width: 58.33%;
		}
		.col-md-8{
			width: 66.66%;
		}
		.col-md-9{
			width: 75%;
		}
		.col-md-10{
			width: 83.33%;
		}
		.col-md-11{
			width: 91.66%;
		}
		.col-md-12{
			width: 100%;
		}
	}
	@media (max-width: 767px){
		.col-xs-1,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,.col-xs-9,.col-xs-10,.col-xs-11,.col-xs-12{
			float: left;
		}
		.col-xs-1{
			width: 8.33%;
		}
		.col-xs-2{
			width: 16.66%;
		}
		.col-xs-3{
			width: 25%;
		}
		.col-xs-4{
			width: 33%;
		}
		.col-xs-5{
			width: 41.66%;
		}
		.col-xs-6{
			width: 50%;
		}
		.col-xs-7{
			width: 58.33%;
		}
		.col-xs-8{
			width: 66.66%;
		}
		.col-xs-9{
			width: 75%;
		}
		.col-xs-10{
			width: 83.33%;
		}
		.col-xs-11{
			width: 91.66%;
		}
		.col-xs-12{
			width: 100%;
		}
	}
	</style>
	</head>
	
<body>
<h1>MENU</h1>
<div class= "row">
<div class="col-lg-4 col-md-6 col-xs-12">
<section class="a">
<h3 class="a">chicken</h3>
<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</p>
</section>
</div>
<div class="col-lg-4 col-md-6 col-xs-12"><section class="b"><h3 class="b">BEEF</h3><p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</p></section></div>
<div class="col-lg-4 col-md-12 col-xs-12"><section class="c"><h3 class="c">SUSHI</h3><p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.</p></section></div>
</div>
</body >
</html>
