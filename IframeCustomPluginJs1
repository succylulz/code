kWidget.addReadyCallback(function( playerId ){
	var kdp = document.getElementById(playerId); 
	kdp.kBind("doPlay", function(){
		kdp.sendNotification('openFullScreen'); 
	}); 
	kdp.kBind("doPause", function(){
		kdp.sendNotification('closeFullScreen');
	});
	kdp.kBind("openFullScreen", function(){
		$("#fslog").append("openFullScreen\n");
	});
	kdp.kBind("closeFullScreen", function(){
		$("#fslog").append("closeFullScreen\n");
	});
});
