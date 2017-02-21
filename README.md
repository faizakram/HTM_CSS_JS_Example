<h2>File Name:- getFileSizeUisngJavaScript</h2>

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
  
