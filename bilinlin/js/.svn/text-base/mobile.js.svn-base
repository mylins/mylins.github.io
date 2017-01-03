$(function(){
	$(".log").mouseover(function(){
		$(this).css("background","white");
		var $top = $(".log").position().top+$(".log").height();
		var $left = $(".log").position().left;
		$(".login").css({top:""+$top+"",left:""+$left+"",display:"block"});
		$(".login").css({top:$top,left:$left,display:"block"});
	});
	$(".login").mouseover(function(){
		$(".log").css("background","white");
		var $top = $(".log").position().top+$(".log").height();
		var $left = $(".log").position().left;
		$(".login").css({top:""+$top+"",left:""+$left+"",display:"block"});
		$(".login").css({top:$top,left:$left,display:"block"});
	});
	$(".login").mouseout(function(){
		$(".log").css("background","");
		$(".login").hide();
	});
	
	$(".return").click(function(){
		$(this).hide();
		$(this).next().hide();
		$(this).prev().hide()
		$(".province").show();
	});
	var $i = 0;
	$(".unfold").click(function(){
		var $top = $(".ty").position().top+$(".ty").height();
		var $left = $(".ty").position().left;
		if($i===0){
			$(this).css({"border-top":"0","border-bottom":"5px solid #444"});
//			$(".addr").show();
//			$(".addr").css({top:""+$top+"",left:""+$left+"",display:"block"});
			$(".addr").css({top:$top,left:$left,display:"block"});
			console.log($left)
			$i=1;
		}else{
			$(this).css({"border-bottom":"0","border-top":"5px solid #444"});
			$(".addr").hide();
			$i=0;
		}
	});
	
	$(".contant3>ul li:gt(0)").mouseover(function(){
		$(".nav>ul>li").hide();
		var $index = $(this).index()-1;
		$(".nav").show();
		$(".nav>ul>li:eq("+$index+")").show();
	})
	$(".contant3>ul li:gt(0)").mouseout(function(){
		$(".nav>ul>li").hide();
	})
	$(".nav>ul>li").mouseover(function(){
		$(this).show();
	});
	$(".nav>ul>li").mouseout(function(){
		$(this).hide();
	})
	$(".contant3>ul li:eq(0)").mouseover(function(){
		$(".nav>ul>li").hide();
	})
	
	$(".contant4 .bor span").click(function(){
		$(".contant4 .bor span").removeClass();
		$(this).addClass("yibai");
	})
	
	$(".move li img").mouseover(function(){
		$(this).animate({"left":"5px"},500)
	});
	$(".move li img").mouseout(function(){
		$(this).animate({"left":"13px"},500)
	})
})
	$(".contant5 ul li ul li:odd()").css("background","#eee");
	$(".contant5 ul li ul li:odd() p").css("color","#FF0000");






