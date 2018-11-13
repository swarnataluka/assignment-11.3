  function showAttriboflnk(){ 
                var anchorAttribvalue1=document.getElementById("google").id;   
                var anchorAttribvalue2=document.getElementById("google").target; 
                var anchorAttribvalue3=document.getElementById("google").href; 
                var anchorAttribvalues="id: "+anchorAttribvalue1+" type: "+anchorAttribvalue2+" href: "+anchorAttribvalue3; 
                document.getElementById("attrs").innerHTML=anchorAttribvalues; 
       }
       function removeResult(){ 
        showAttribindiv.removeChild(showAttribindiv.firstChild); 
       }