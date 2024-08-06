a=document.getElementsByClassName("d-flex align-items-center gap-1 dom-texthighlight border border-white px-1 mx-n1")

for(var i=0; i<a.length; i++){if(a[i].childNodes.length>1)console.log(a[i].childNodes[1].href.replace("https://etherscan.io/address/",""))}
