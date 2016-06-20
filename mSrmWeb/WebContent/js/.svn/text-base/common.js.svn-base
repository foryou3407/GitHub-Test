/******************************************************************************
 * gopage(url) 공통함수  
 * Arguments
 *     pageURL : 이동할 페이지 url 
 * Description
 *     parameter 값의 페이지로 이동함. 
 *****************************************************************************/
// 페이지 이동
function goURL ( url ) {
	document.location.href = url;
}

// 로그아웃
function deleteStorage() {       
	
	delete localStorage.user_id;
	delete localStorage.reg_id;
	delete localStorage.gubun;
	delete localStorage.tradecd;
	delete localStorage.wrkcentcd;
	delete localStorage.bizno;
    
    var gourl = "";
    gourl = "/index.html";
    alert ("로그아웃 되었습니다.");
    goURL(gourl);
   
}
