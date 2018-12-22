//获得url参数
function request(paras) {
    var url = location.href;
    var paraString = url.substring(url.indexOf("?") + 1, url.length).split("&");
    var paraObj = {}
    for (i = 0; j = paraString[i]; i++) {
        paraObj[j.substring(0, j.indexOf("=")).toLowerCase()] = j.substring(j.indexOf("=") + 1, j.length);
    }
    var returnValue = paraObj[paras.toLowerCase()];    
    if (typeof (returnValue) == "undefined") {
        return "";
    } else {
        return returnValue;
    }
}
function request2(paras) {
    var url = location.href;
    var paraString = url.substring(url.indexOf("?") + 1, url.length);
    if (paraString.indexOf(paras + "=") > -1) {
        return paraString.split(paras + "=")[1];
    }
    else {
        return "";
    }   
}
