<!DOCTYPE html>
<html lang="zh-cn">
<head>
	
		
	
	
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	
	
	<meta name="description" content="无奈社区" />
	<meta name="renderer" content="webkit">
	<meta http-equiv="X-UA-Compatible" content="IE=Edge,chrome=1" >

	<title>无奈社区</title>
	
	
	
	<link rel="shortcut icon" href="view/img/favicon.ico" />
	<link rel="icon" sizes="32x32" href="view/img/favicon.ico">
	<link rel="Bookmark" href="view/img/favicon.ico" />
	
	<style>

table.nav_tag_list {margin-bottom: 0.2rem;}

table.nav_tag_list td {padding: 0.3rem;}

table.nav_tag_list td a{margin-right: 0.2rem;}

.nav_tag_list .active {font-weight: normal}

.tag_option {

        border: 1px solid #bbb; padding: 1px 10px; border-radius: 10px; text-decoration: none;

}

.tag_option:active, .tag_option.active {

        border: 1px solid #000; background: #000; color: #fff; text-decoration: none;

}

</style>
		<link rel="stylesheet" href="view/css/bootstrap.css?1.0">
	
	
	
		<link rel="stylesheet" href="view/css/bootstrap-bbs.css?1.0">
	<link rel="stylesheet" href="plugin/huux_notice/view/css/huux-notice.css" name="huux_notice"><style>

@import url("https://at.alicdn.com/t/font_2761470_wlzc7cs9pc.css");

.bottom-nav {

    /* display: none; */

    background-color: white;

}



.nav_font{

	font-size:12px;

	color:#8590a6;

}





.bottom-nav{

    position: relative;

    display: inline-block;

    /* padding-top: 6px; */

    line-height: 20px;

    color: #9e9e9e;

    cursor: pointer;

}

@media screen and (min-width: 992px) {

    .bottom-nav {

        display: none !important;

		}

    }

	

@media screen and (max-width: 992px) {

		#footer{margin-bottom: 4rem};

    }

</style><link rel="stylesheet" href="plugin/zaesky_theme_zhihulan/view/css/zaesky_theme_zhihulan.css?1.7">
<link rel="stylesheet" href="plugin/zaesky_theme_zhihulan/view/fonts/fontawesome/icon.css?1.0">

	
	<style>

.haya-post-info-username.today .username {

	color: var(--danger) !important;

}

.haya-post-info-username.today .date {

	color: var(--danger) !important;

}

</style>

<style type="text/css" data-model="huux_hlight">.huux_thread_hlight_style1{color: #D9534D;font-weight:700}.huux_thread_hlight_style2{color: #F0AD4E;font-weight:normal}.huux_thread_hlight_style3{color: #5BC0DE;font-weight:normal}.huux_thread_hlight_style4{color: #5CB85C;font-weight:normal}.huux_thread_hlight_style5{color: #FF00FF;font-weight:700}</style>
<script src="/plugin/xiunobbs_cn_dark/js/jquery.min.js"></script>
<script src="/plugin/xiunobbs_cn_dark/js/jquery.cookie.min.js"></script>


<script type="text/javascript">
	function loadjscssfile(filename, filetype) {

		if (filetype == "js") {
			var fileref = document.createElement('script')
			fileref.setAttribute("type", "text/javascript")
			fileref.setAttribute("src", filename)
		} else if (filetype == "css") {
			var fileref = document.createElement("link")
			fileref.setAttribute("rel", "stylesheet")
			fileref.setAttribute("type", "text/css")
			fileref.setAttribute("href", filename)
		}
		if (typeof fileref != "undefined")
			document.getElementsByTagName("head")[0].appendChild(fileref)
	}

	function removejscssfile(filename, filetype) {
		var targetelement = (filetype == "js") ? "script" : (filetype == "css") ? "link" : "none"
		var targetattr = (filetype == "js") ? "src" : (filetype == "css") ? "href" : "none"
		var allsuspects = document.getElementsByTagName(targetelement)
		for (var i = allsuspects.length; i >= 0; i--) {
			if (allsuspects[i] && allsuspects[i].getAttribute(targetattr) != null && allsuspects[i].getAttribute(targetattr).indexOf(
					filename) != -1) {
				allsuspects[i].parentNode.removeChild(allsuspects[i])
			}
		}
	}



	function theme() {
		Theme = $.cookie('Theme');
		if (Theme == "" | Theme == "null" | Theme == null | Theme == undefined) {
			if (window.matchMedia('(prefers-color-scheme: dark)').matches) {
				$.cookie("Theme", "1", {
					expires: 365
				});
			}
		}

		if (Theme != "1") {
			removejscssfile("/plugin/xiunobbs_cn_dark/css/darktheme.css", "css")
		} else {
			loadjscssfile("/plugin/xiunobbs_cn_dark/css/darktheme.css", "css")

		}
	}
	theme()
</script>

	
</head>

<body>
	
	
	
	
	<!-- 
		轻论坛导航：默认头部
		Bootstrap 4.0 推荐的 PC/Mobile 公共写法 
		优点：公用性强
		缺点：结构稍微有点复杂
	-->
	
	
<script defer data-domain="bk111.cc" src="https://url.bk88.cc/js/script.js"></script>
<header class="navbar navbar-expand-lg navbar-dark bg-dark" id="header">
		<div class="container">
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nav" aria-controls="navbar_collapse" aria-expanded="false" aria-label="展开菜单" style="color: #bdbdbd;">
				<span class="navbar-toggler-icon"></span>
			</button>
			
			
			
		<a class="navbar-brand text-truncatel"  href="./"><div id="logos" style="display: inline-block;vertical-align: middle;">
				</div></a>
			</a>
			<!--<div class="brand">虔诚科技<br>合作共赢！按 Ctrl+D 收藏我们</div>-->

			
			
			
				<a class="navbar-brand hidden-lg" style="color: #bdbdbd;" data-toggle="modal" data-target="#search"><i class="icon-search icon"></i></a>
						<div class="modal fade" id="search" style="display: none;" aria-hidden="true">
	<div class="modal-dialog modal-dialog-centered" style="min-height:0;">
		<div class="modal-content">
			<div class="modal-header">
				<span class="modal-title"></span>
				<button type="button" class="close" data-dismiss="modal" aria-label="Close">
					<span aria-hidden="true">×</span>
				</button>
			</div>
			<div class="modal-body">
				<div class="top-search hidden-lg">
					<div class="form-group" style="margin-bottom:0px">
						<form action="search.htm" id="search_form">
							<div class="input-group">								
								<input type="text" class="form-control" name="keyword" placeholder="搜一下你想要的资源...">
								<div class="input-group-append">
									<button class="btn btn-primary" type="submit"><i class="icon-search"></i> 搜索</button>
								</div>
							</div>
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>
</div> 
	
			
<style>
@media (max-width: 992px){
#nav > ul:first-child > li:not(:first-child) {
    padding-left: 0rem;
}
}
</style>
			
			
			<div class="collapse navbar-collapse" id="nav">
				<!-- 左侧：版块 -->




				<ul class="navbar-nav mr-auto hidden">
					
					
					<li class="nav-item home" fid="0" data-active="fid-0"><a class="nav-link" href="."><i class="icon-home d-md-none"></i> 首页</a></li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="7" data-active="fid-7">
						<a class="nav-link" href="forum-7.htm"><i class="icon-comments d-md-none"></i> 白菜项目</a>
					</li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="1" data-active="fid-1">
						<a class="nav-link" href="forum-1.htm"><i class="icon-c"></i> 套彩工具</a>
					</li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="2" data-active="fid-2">
						<a class="nav-link" href="https://x112ueudelftq.com:58009/"><i class="https://x112ueudelftq.com:58009/"></i> 美女福利</a>
					</li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="3" data-active="fid-3">
						<a class="nav-link" href="forum-3.htm"><i class="icon-comments d-md-none"></i> 以小博大</a>
					</li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="5" data-active="fid-5">
						<a class="nav-link" href="forum-5.htm"><i class="icon-comments d-md-none"></i> 首存项目</a>
					</li>
					
										
					<li class="nav-item hidden-md hidden-sm" fid="6" data-active="fid-6">
						<a class="nav-link" href="forum-6.htm"><i class="icon-comments d-md-none"></i> 羊毛项目</a>
					</li>
					
										<li class="nav-item">

    <a class="nav-link" href="links.htm"><i class="fa fa-link"></i> 友邻</a>

</li>
										
										<li class="nav-item hidden-lg"><a class="nav-link" href="user-login.htm"><i class="icon-user"></i> 登录</a></li>
									</ul>
				
				
				
				
				<!-- 右侧：用户 -->
				<ul class="navbar-nav hidden-md hidden-sm">
				<li class="nav-item"><a class="nav-link" href="search.htm" title="搜索"><i class="iconfont iconSearchOutline" style="font-size:18px"></i></a></li>
								<li class="nav-item username">
	<a class="nav-link" id="theme" style="cursor:pointer;">
	    <script src="/plugin/xiunobbs_cn_dark/js/jquery.cookie.min.js"></script>
		<script type="text/javascript">
		    Theme = $.cookie('Theme');
			if (Theme != "1") {
				document.write("<i class='icon-circle' style='margin-right: 4px;'></i>深色");
			} else {
				document.write("<i class='icon-circle-o' style='margin-right: 4px;'></i>浅色");
			}
		</script>
	</a>
</li>
<li class="nav-item hidden-lg">

	<a class="nav-link" href="search.htm"><i class="icon-search"></i> 搜索</a>

</li>
								<ul style="margin-top:2px; display: flex;">
					<li class="nav-item "><a class="nav-link" href="user-login.htm">登录</a></li>
					<li class="hidden-sm"><a class="nav-link" href="user-create.htm">注册</a></li></ul>
								</ul>
				</div>
				    </div>
					
				</ul>
				<!-------手机------->
				
			</div>
		</div>
	<script>
    /* 点击按钮，下拉菜单在 显示/隐藏 之间切换 */
    function myFunction() {
        document.getElementById("myDropdown").classList.toggle("show");
    }

    // 点击下拉菜单意外区域隐藏
    window.onclick = function(e) {
        if (!e.target.matches('.mydropdownoc')) {
            var myDropdown = document.getElementById("myDropdown");
            if (myDropdown.classList.contains('show')) {
                myDropdown.classList.remove('show');
            }
        }
    }
</script>	
		
		
		
	</header>
	
	
	<main id="body">
		<div class="container">
	
		




<div class="row">

	<div class="col-lg-9 main">

		<link rel="stylesheet" href="plugin/qc_ad/css/style.css" type="text/css" />
<div class="card fontlist">
				<div class="fontlistson">
		<div class="text-center">
					    <a href="?forum-1.htm" class="button" target="_blank" style="color:;background-color:;">
							<span>撸彩工具</span>
						</a>
		</div>
		</div>
							<div class="fontlistson">
		<div class="text-center">
					    <a href="?thread-3744.htm" class="button" target="_blank" style="color:;background-color:#B5A5D6;">
							<span>银行一体化</span>
						</a>
		</div>
		</div>
							<div class="fontlistson">
		<div class="text-center">
					    <a href="https://x112ueudelftq.com:58009/" class="button" target="_blank" style="color:;background-color:;">
							<span>深夜福利</span>
						</a>
		</div>
		</div>
							<div class="fontlistson">
		<div class="text-center">
					    <a href="?forum-6.htm" class="button" target="_blank" style="color:;background-color:;">
							<span>羊毛项目</span>
						</a>
		</div>
		</div>
							<div class="fontlistson">
		<div class="text-center">
					    <a href="http://103.106.189.24/pg.html" class="button" target="_blank" style="color:;background-color:#ee151c;">
							<span>试玩电子</span>
						</a>
		</div>
		</div>
					</div><style>

.notice{list-style:none;margin:0;padding:0}.notice.notice--block .notice{margin-bottom:10px;}.notice.notice--floating{margin:0 auto 0 20px;width:300px;max-width:100%;z-index:800}@media (max-width:340px){.notice.notice--floating{margin-right:10px}}.notice.notice--floating .notice{margin-bottom:20px}.notice .uix_noticeInner{display:flex}.notice .uix_noticeIcon{display:flex;align-items:center;padding:0 8px;color:rgb(239, 65, 89);font-size:15px;font-weight: 600;}.notice.notice--scrolling{display:flex;align-items:stretch;overflow:hidden;border-width:0;border-style:solid;border-top-color:#d3e1f6;border-right-color:#d3e1f6;border-bottom-color:#d3e1f6;border-left-color:#d3e1f6;margin-bottom:10px}.notice.notice--scrolling.notice--isMulti{margin-bottom:30px}.notice.notice--scrolling .notice{width:100%;flex-grow:0;flex-shrink:0;border:none;box-shadow:none}.noticecrollContainer{margin-bottom:10px;box-shadow:0 4px 15px 0 rgba(88,106,153,0.2);border:2px solid #2175f3}.noticecrollContainer .uix_noticeIcon{background:#2175f3}.noticecrollContainer .lSSlideWrapper{border-width:0;border-style:solid;border-top-color:#d3e1f6;border-right-color:#d3e1f6;border-bottom-color:#d3e1f6;border-left-color:#d3e1f6}.noticecrollContainer .notice.notice--scrolling{border:none;margin-bottom:0}.noticecrollContainer .notice.notice--primary,.noticecrollContainer .notice.notice--accent,.noticecrollContainer .notice.notice--dark,.noticecrollContainer .notice.notice--light{color:#384764;background:#fff}.noticecrollContainer .notice a{color:#2175f3}.noticecrollContainer .lSPager{color:#384764;background:#fff}.notice{position:relative;border-width:0;border-style:solid;border-top-color:#d3e1f6;border-right-color:#d3e1f6;border-bottom-color:#d3e1f6;border-left-color:#d3e1f6;color:#384764;background:#fff;/*! border:2px solid #d3e1f6; */}.notice:before,.notice:after{content:" ";display:table}.notice:after{clear:both}.notice.notice--primary{color:#384764;background:#fff;border:2px solid rgba(234, 50, 67, 0.1);}.notice.notice--primary .uix_noticeIcon{background:rgba(234, 50, 67, 0.1);border-radius: 7px;}.notice.notice--accent{border:2px solid #92d049}.notice.notice--accent .uix_noticeIcon{background:#92d049}.notice.notice--accent a:not(.button--notice){color:#2175f3}.notice.notice--dark{background:#2175f3;color:#fff;border-color:#b2cffb}.notice.notice--dark a:not(.button--notice){color:#fff;text-decoration:underline}.notice.notice--dark a.notice-dismiss{color:inherit}.notice.notice--light{color:#141414;background:#fff}.notice.notice--light .uix_noticeIcon{background:#d3e1f6;color:#a0afce}.notice.notice--light a:not(.button--notice){color:#828282}.notice.notice--enablePush{display:none}@media (max-width:900px){.notice.notice--enablePush{padding:4px 4px 15px;font-size:1.2rem}}@media (max-width:900px){.notice.notice--cookie .notice-content{padding:4px 4px;font-size:1.2rem}.notice.notice--cookie .notice-content .button--notice{font-size:1.2rem;padding:4px 12px}.notice.notice--cookie .notice-content .button--notice .button-text{font-size:1.2rem}}.notice--block .notice{/*! font-size:1.3rem; */border-radius:8px;}.notice--floating .notice{font-size:1.1rem;border-radius:8px;box-shadow:0 4px 15px 0 rgba(88,106,153,0.2)}.has-js .notice--floating .notice{display:none}.notice.notice--hasImage .notice-content{min-height:78px}@media (max-width:900px){.notice.notice--hidewide:not(.is-vis-processed){display:none;visibility:hidden}}@media (max-width:650px){.notice.notice--hidemedium:not(.is-vis-processed){display:none;visibility:hidden}}@media (max-width:480px){.notice.notice--hidenarrow:not(.is-vis-processed){display:none;visibility:hidden}}.notice-image{float:left;padding:15px 0 15px 15px}.notice-image img{max-width:48px;max-height:48px}.notice-content{padding:6px;flex-grow:1}.notice-content a.notice-dismiss{float:right;color:inherit;font-size:16px;line-height:1;height:1em;box-sizing:content-box;padding:0 0 5px 5px;opacity:.5;-webkit-transition: opacity .2s ease;transition: opacity .2s ease;cursor:pointer}.notice-content a.notice-dismiss:before{font:normal normal normal 18px/1 "Material Design Icons";font-size:110%;font-weight:normal;line-height:inherit;width:auto;content:"\F0156";display:inline-block;text-align:center}.notice-content a.notice-dismiss:hover{text-decoration:none;opacity:1}.notice--floating .notice-content a.notice-dismiss{font-size:14px}

#footer {

 background-color:#f0f1f1 !important;

}

</style>



<li class="notice js-notice notice--primary" style="    margin-bottom: 10px;">

		<div class="uix_noticeInner">

<div class="uix_noticeIcon">

<i aria-hidden="true">公告</i>

			</div>

		<div class="notice-content" id="notich">

	 无奈社区3

			</div>

		</div>

	</li>



<style>

@media (min-width: 992px) {

  .icolistson {

    width: 20% !important;

    max-width: 20% !important;

  }

}



.icolist {

  display: flex;

  flex-direction: row;

  flex-wrap: wrap;

  justify-content: flex-start;

  position: relative;

  padding-left: 34px;

  overflow: hidden;

}



.icolistson {

  flex: 1 0 25%;

  max-width: 25%;

}



.icolistson img {

  border-radius: 10px;

  height: 40px;

  width: 40px;

}



.icolistson a {

  text-decoration: none;

}



.qc_ren {

  width: 34px;

  padding: 20px 10px;

  background: #fef3f3;

  float: left;

  margin-left: 0;

  font-size: 14px;

  color: #e85252;

  text-align: center;

  height: 100%;

  border-radius: 6px;

  position: absolute;

  left: 0;

  display: flex;

  justify-content: center;

  align-items: center;

}



@media (max-width: 576px) {

  .qc_ren {

    width: 9%;

  }

}

</style>



<div class="card icolist">

    <div class="qc_ren">热门区</div>

        <div class="icolistson">

        <div class="m-3 text-center" style="margin: 5px 10px;">

          <a href="?thread-1626.htm" target="_blank">

            <img src="https://i2.mjj.rip/2024/05/28/9054560d09fcf46204406ebde394ccad.jpeg">

          </a>



          </h5>

          <p class="text-secondary" style="margin-top: 0.2rem; margin-bottom: 0.2rem;"></p>

        </div>

      </div>

        <div class="icolistson">

        <div class="m-3 text-center" style="margin: 5px 10px;">

          <a href="?thread-1876.htm" target="_blank">

            <img src="https://i2.mjj.rip/2024/05/28/5535ed503fa110acb49d9da3a73d177d.jpeg">

          </a>

          <h5 style="padding-top: 10px; font-size: 12px; color: #666; font-weight: 100;">

            <a href="https://wcws.eveksq.com/app/register.php?site_id=1010&topId=348135" target="_blank">狗子28  100+100</a>



          </h5>

          <p class="text-secondary" style="margin-top: 0.2rem; margin-bottom: 0.2rem;"></p>

        </div>

      </div>

        <div class="icolistson">

        <div class="m-3 text-center" style="margin: 5px 10px;">

          <a href="?thread-3977.htm" target="_blank">

            <img src="https://52nb.vip/page/3.jpg">

          </a>

          <h5 style="padding-top: 10px; font-size: 12px; color: #666; font-weight: 100;">

            <a href="?thread-3977.htm" target="_blank">问鼎 30+28</a>

          </h5>

          <p class="text-secondary" style="margin-top: 0.2rem; margin-bottom: 0.2rem;"></p>

        </div>

      </div>

        <div class="icolistson">

        <div class="m-3 text-center" style="margin: 5px 10px;">

          <a href="?thread-304.htm" target="_blank">

            <img src="https://i2.mjj.rip/2024/05/28/c0d0490e06e36e3327596785264b66cf.jpeg">

          </a>

          <h5 style="padding-top: 10px; font-size: 12px; color: #666; font-weight: 100;">

            <a href="https://wcws.eveksq.com/app/register.php?site_id=1021&topId=294573&aPlanId=1&isAllProxy=1" target="_blank">多多28  100+100</a>


          </h5>

          <p class="text-secondary" style="margin-top: 0.2rem; margin-bottom: 0.2rem;"></p>

        </div>

      </div>

  </div>

		<div class="card card-threadlist">

			<div class="card-header">

				<ul class="nav nav-tabs card-header-tabs">

					<li class="nav-item">

						<a class="nav-link " href="./index.htm">最新</a>

					</li>

					<li class="nav-item">

						<a class="nav-link" href="forum-8.htm">曝光区</a>

					</li>

					<li class="nav-item">

						<a class="nav-link" href="forum-9.htm">交流区</a>

	
								
																
								
								
																								
							</div>
							<div class="d-flex justify-content-between small mt-1">
								<div>
									
							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold   " uid="1">无奈社区 •</span></a>
<span class="date text-grey hidden-sm"></span>

</span>
									
									<!--<span class="date text-grey "></span>-->
<span>
										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>
										<span class="username text-muted mr-1" uid="6481">hzyyyds6											
										</span>
										<span class="text-grey"><span class="hidden-sm"></span>
											</span>
									</span>
																		

									</span>


									
									

									
																		 
								</div>
								<div class="text-muted small">
									
									
									
								
		
									<span class="ml-2 thread_pl">13</span>
																	</div>
							</div>
						</div>
					</li>
															
					<li onclick="openThread(3977)" style="cursor: pointer; position: relative; border-left: 2px solid rgb(255, 255, 255);" class="media  thread tap  threadItem threadclick pop_peopleSimple" data-href="thread-3977.htm" data-uid="2368" data-tid="3977">
						
						
						<a href="user-1.htm" class="ml-1 mt-2 mr-3" data-active="menu-user-thread" tabindex="-1">

							<img class="avatar-3" src="upload/avatar/000/1.png?1646285206">
						</a>
						
					
						<div class="media-body">
						
							<div class="subject break-all">
																						
																	<i class="icon-top-3"></i>
																
								
																
								<a href="https://wcws.eveksq.com/app/register.php?site_id=1010&topId=348135"huux_thread_hlight_style1">【狗子28】--✅--（100+100）</span></a>
																														
								
								
																
																											
							</div>
							<div class="d-flex justify-content-between small mt-1">
								<div>
									
							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold   " uid="1">无奈社区 •</span></a>
<span class="date text-grey hidden-sm"></span>

</span>
									
									<!--<span class="date text-grey ">4天前</span>-->
<span>
										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>
										<span class="username text-muted mr-1" uid="1">无奈社区											
										</span>
										<span class="text-grey"><span class="hidden-sm"></span>
											</span>
									</span>
																		

									</span>


									
									

									
																		 
								</div>
								<div class="text-muted small">
									
									
									
								
		
									<span class="ml-2 thread_pl">16</span>
																	</div>
							</div>
						</div>
					</li>
															
					<li onclick="openThread(8370)" style="cursor: pointer; position: relative; border-left: 2px solid rgb(255, 255, 255);" class="media  thread tap  threadItem threadclick pop_peopleSimple" data-href="thread-8370.htm" data-uid="2368" data-tid="8370">
						
						
						<a href="user-1.htm" class="ml-1 mt-2 mr-3" data-active="menu-user-thread" tabindex="-1">

							<img class="avatar-3" src="upload/avatar/000/1.png?1646285206">
						</a>
						
					
						<div class="media-body">
						
							<div class="subject break-all">
																						
																	<i class="icon-top-3"></i>
																
								
																
								<a href="https://wcws.eveksq.com/app/register.php?site_id=1012&topId=354890&aPlanId=1&isAllProxy=1"><span class="huux_thread_hlight_style1">【旺财28】--✅--（30+28）</span></a>
									<span class="vote_tip" title=""><i class="antanticon-picture"><svg viewBox="64 64 896 896" focusable="false" fill="currentColor" width="1em" height="1em" data-icon="picture" aria-hidden="true" style="margin-bottom: 2px;">><path d="M928 160H96c-17.7 0-32 14.3-32 32v640c0 17.7 14.3 32 32 32h832c17.7 0 32-14.3 32-32V192c0-17.7-14.3-32-32-32zm-40 632H136v-39.9l138.5-164.3 150.1 178L658.1 489 888 761.6V792zm0-129.8L664.2 396.8c-3.2-3.8-9-3.8-12.2 0L424.6 666.4l-144-170.7c-3.2-3.8-9-3.8-12.2 0L136 652.7V232h752v430.2zM304 456a88 88 0 100-176 88 88 0 000 176zm0-116c15.5 0 28 12.5 28 28s-12.5 28-28 28-28-12.5-28-28 12.5-28 28-28z"></path></svg></i> 1P</span>
																							
								
								
																
								
								
																								
							</div>
							<div class="d-flex justify-content-between small mt-1">
								<div>
									
							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold   " uid="1">无奈社区 •</span></a>
<span class="date text-grey hidden-sm"></span>

</span>
									
									<!--<span class="date text-grey "></span>-->
<span>
										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>
										<span class="username text-muted mr-1" uid="6481">hzyyyds6											
										</span>
										<span class="text-grey"><span class="hidden-sm"></span>
											</span>
									</span>
																		

									</span>


									
									

									
																		 
								</div>
								<div class="text-muted small">
									
									
									
								
		
									<span class="ml-2 thread_pl">13</span>
																	</div>
							</div>
						</div>
					</li>
															
					<li onclick="openThread(3977)" style="cursor: pointer; position: relative; border-left: 2px solid rgb(255, 255, 255);" class="media  thread tap  threadItem threadclick pop_peopleSimple" data-href="thread-3977.htm" data-uid="2368" data-tid="3977">
						
						
						<a href="user-1.htm" class="ml-1 mt-2 mr-3" data-active="menu-user-thread" tabindex="-1">

							<img class="avatar-3" src="upload/avatar/000/1.png?1646285206">
						</a>
						
					
						<div class="media-body">
						
							<div class="subject break-all">
																						
																	<i class="icon-top-3"></i>
																
								
																
								<a href="https://wcws.eveksq.com/app/register.php?site_id=1020&topId=2104243"><span class="huux_thread_hlight_style1">【问鼎娱乐】--✅--（30+28）</span></a>
																															
								
																
								
								
																								
							</div>
							<div class="d-flex justify-content-between small mt-1">
								<div>
									
							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold   " uid="1">无奈社区 •</span></a>
<span class="date text-grey hidden-sm"></span>

</span>
									
									<!--<span class="date text-grey "></span>-->
<span>
										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>
										<span class="username text-muted mr-1" uid="6481">hzyyyds6											
										</span>
										<span class="text-grey"><span class="hidden-sm"></span>
											</span>
									</span>
																		

									</span>


									
									

									
																		 
								</div>
								<div class="text-muted small">
									
									
									
								
		
									<span class="ml-2 thread_pl">13</span>
																	</div>
							</div>
						</div>
					</li>
															
					<li onclick="openThread(3977)" style="cursor: pointer; position: relative; border-left: 2px solid rgb(255, 255, 255);" class="media  thread tap  threadItem threadclick pop_peopleSimple" data-href="thread-3977.htm" data-uid="2368" data-tid="3977">
						
						
						<a href="user-1.htm" class="ml-1 mt-2 mr-3" data-active="menu-user-thread" tabindex="-1">

							<img class="avatar-3" src="upload/avatar/000/1.png?1646285206">
						</a>
						
					
						<div class="media-body">
						
							<div class="subject break-all">
																						
																	<i class="icon-top-3"></i>
																
								
																
								<a href="https://43333662.com/#/?c=6647RCSE"><span class="huux_thread_hlight_style1">【新葡京662】--✅--（送26）</span></a>
	
								
																
								
								
																								
							</div>
							<div class="d-flex justify-content-between small mt-1">
								<div>
									
							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold   " uid="1">无奈社区 •</span></a>
<span class="date text-grey hidden-sm"></span>

</span>
									
									<!--<span class="date text-grey "></span>-->
<span>
										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>
										<span class="username text-muted mr-1" uid="6481">hzyyyds6											
										</span>
										<span class="text-grey"><span class="hidden-sm"></span>
											</span>
									</span>
																		

									</span>


									
									

									
																		 
								</div>
								<div class="text-muted small">
									
									
									
								
		
									<span class="ml-2 thread_pl">13</span>
																	</div>
							</div>
						</div>
					</li>
															
					<li onclick="openThread(3977)" style="cursor: pointer; position: relative; border-left: 2px solid rgb(255, 255, 255);" class="media  thread tap  threadItem threadclick pop_peopleSimple" data-href="thread-3977.htm" data-uid="2368" data-tid="3977">
						
						
						<a href="user-1.htm" class="ml-1 mt-2 mr-3" data-active="menu-user-thread" tabindex="-1">

							<img class="avatar-3" src="upload/avatar/000/1.png?1646285206">
						</a>
						
					
						<div class="media-body">
						
							<div class="subject break-all">
																						
																	<i class="icon-top-3"></i>
																
								
																
								<a href="https://002.8671a.vip/?id=604629502&currency=CNY&type=2"huux_thread_hlight_style1">【新葡京8671】--✅--（送36不建议充值）</span></a>
	

								

																

								

								

																								

							</div>

							<div class="d-flex justify-content-between small mt-1">

								<div>

									

							<span class="haya-post-info-username ">

<span class="username text-muted font-weight-bold " uid="1">无奈社区 •</span></a>

<span class="date text-grey hidden-sm"></span>

</span>

									

									<!--<span class="date text-grey "></span>-->

<span>

										<span class="text-grey mx-2"><i class="fa fa-reply"></i></span>

										<span class="username text-muted mr-1" uid="6481">hzyyyds6											

										</span>

										<span class="text-grey"><span class="hidden-sm"></span>

											</span>

									</span>

																		

									</span> 

									

									

									

																		 

								</div>

								<div class="text-muted small">

									

									

									

								

		

									<span class="ml-2 thread_pl">13</span>

																	</div>

							</div>

						</div>

					</li>

															

					<li onclick="op
