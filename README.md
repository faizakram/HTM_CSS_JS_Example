<h2>File Name:- getFileSizeUisngJavaScript.html</h2>

===============================================
	function fileUpload() {
   		 	var inpFiles = document.getElementById('fileUpload');
  			for (var i = 0; i < inpFiles.files.length; ++i) {
    		var size = inpFiles.files.item(i).size;
    		alert("File Size : " + size);
			}
 		 }
  ===============================================
  <h2>Demo Link</h2>
  http://faizakram.com/github/HTM_CSS_JS_Example/getFileSizeUisngJavaScript.html
  
  <h2>Button Add Class Or Remove</h2>
  ==================================
  
 ```
		$(document).ready(function() {
    		$('.btn').click(function() {
    			 if($(this).val() == "Follow"){
       			 this.value = 'UnFollow';
       			 $(this).removeClass("btn-success");
        		 $(this).addClass("btn-danger");
       			}
       			else{
       				this.value = 'Follow';
       				$(this).removeClass("btn-danger");
        		   $(this).addClass("btn-success");
       			}
    			});
		});

```
=========================================================================
<h3>Before Click </h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/buttonHome.PNG"/>
<h3>After Click </h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/buttonHome2.PNG"/>
<h3>Demo Link</h3>
http://faizakram.com/github/HTM_CSS_JS_Example/AddOrRemoveClass.html


