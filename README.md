<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html>
<head>
	<title>AimBooster</title>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="language" content="en" />
	<meta name="description" content="Mouse accuracy trainer with lots of settings, so you can train exactly what you want to improve on." />
	<meta name="keywords" content="AimBooster, mouse accuracy trainer, aim trainer, configurable, settings, challenge" />
	
	<base href="http://www.aimbooster.com/">
	
	<style type="text/css">
		html, body { height:100%; }
		body { margin:0; background: #376481 url('img/bg.jpg'); background-size: 100% 100%; text-align:center; background-attachment:fixed; font-family: Arial; font-size: 10pt; }
		.stripes { width:100%; min-height:100%; background: url('img/bg_stripes.png'); }
		.column { width:640px; box-shadow: 0px 0px 30px -5px #000000; margin-left:auto; margin-right: auto; -webkit-border-radius: 13px; -moz-border-radius: 13px; border-radius: 13px; }
		.page { background-color: #FFFFFF; -webkit-border-bottom-right-radius: 13px; -webkit-border-bottom-left-radius: 13px; -moz-border-radius-bottomright: 13px; -moz-border-radius-bottomleft: 13px; border-bottom-right-radius: 13px; border-bottom-left-radius: 13px;}
		.menu { background-color: #CCCCCC; width: 634px; text-align: center; color: #777777; padding: 3px; }
		.content { text-align: left; padding: 25px 25px 25px 25px; }
		a[href] { color:#4477BB; text-decoration:none; }
		a[href]:hover { text-decoration:underline; }
		a[href]:active { text-decoration:underline; }
		.tt { font-family: monospace; font-size: 0.8em; }
		.var_desc_bg { padding: 10px 7px 10px 7px; text-align: left; }
		.var_desc_bg_alt { background: #EEEEEE; }
		.var_desc_bg:target { background: #ffa569; }
		.var_desc_bg_alt:target { background: #ffac74; }
		.var_name { font-family: monospace; font-weight: bold; margin-bottom: 5px; }
		.var_desc { margin-left: 10px; margin-right: 10px; }
		hr { color: #999; background-color: #999; height: 1px; border: 0px; }
		.news_pad { padding: 25px 25px 0px 25px; }
		.news_box { background: #EEE; text-align: justify; padding: 25px; -webkit-border-radius: 13px; -moz-border-radius: 13px; border-radius: 13px; }
		.news_box:target { background: #f8ddca; }
	</style>
	
	<script type="text/javascript">
	  var _gaq = _gaq || [];
	  _gaq.push(['_setAccount', 'UA-34229910-1']);
	  _gaq.push(['_trackPageview']);

	  (function() {
	    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
	    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
	    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
	  })();
	</script>
	
		<style>
		#openfl-content { width: 100%; height: 100%; }
		@font-face {
			font-family: 'Maven Pro Regular';
			src: url('assets/MavenPro-reg.eot?#iefix') format('embedded-opentype'),
			url('assets/MavenPro-reg.woff') format('woff'),
			url('assets/MavenPro-reg.ttf') format('truetype'),
			url('assets/MavenPro-reg.svg#Maven%20Pro%20Regular') format('svg');
			font-weight: normal;
			font-style: normal;
		}
	</style>
		
		
	 
</head>
<body>
<div class="stripes">
	<!--[if lt IE 7]> <div style=' clear: both; height: 59px; padding:0 0 0 15px; position: relative;'> <a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode"><img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." /></a></div> <![endif]-->
	<div style="height: 80px;"></div>
	<div class="column">
		<img src="img/header.png" style="width: 640px; height: 116px;" alt="AimBooster">
		<div class="page">
			<div class="menu">Play &nbsp;&bull;&nbsp; <a href="news">News</a> &nbsp;&bull;&nbsp; <a href="faq">FAQ</a> &nbsp;&bull;&nbsp; <a href="suggestions">Feedback</a>&nbsp;&bull;&nbsp; <a href="donate">Donate</a></div>

<script type="text/javascript">
	var aimboosterParameters = {};
</script>

<noscript>
<div style="height: 10px;"></div>
<div id="altContent">
	<h1>AimBooster</h1>
	<p style="padding-left: 20px; padding-right: 20px;">To run AimBooster, you need to enable Javascript.</p>
</div>
<div style="height: 10px;"></div>
</noscript>
	
<div id="openfl-content" style="min-height: 500px;">
<div style="font-size: 18pt; display: flex; justify-content: center; align-items: center; height: 500px;">
Loading...
</div>
</div>

		</div>
	</div>
	<div style="height: 20px;"></div>
</div>

<script type="text/javascript" src="./AimBooster.min.js"></script>
<script type="text/javascript">
document.getElementById("openfl-content").innerHTML = "";
lime.embed ("AimBooster", "openfl-content", 640, 500, { "parameters": aimboosterParameters });
</script>
</body>
</html>
