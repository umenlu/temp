
$(function(){		
	//设计案例切换
	$('.title-list li').mouseenter(function(){
		var liindex = $('.title-list li').index(this);
		$(this).addClass('on').siblings().removeClass('on');
		$('.product-wrap div.product').eq(liindex).fadeIn(116).siblings('div.product').hide();
		var liWidth = $('.title-list li').width();
		$('.lanrenzhijia .title-list p').stop(false,true).animate({'left' : liindex * liWidth + 'px'},400);
	});
	});
