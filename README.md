
<h2>File Name:- Form_Rest_Using_Jquery.html</h2>
===============================================
```
$(document).ready(function(){
  	$("#myform").submit(function(e) {
  		alert("Going To reset");
		document.getElementById("myform").reset();
  		$("#myform").trigger('reset');
  	});
 });
```
  <h3>Demo Link</h3>
http://faizakram.com/github/HTM_CSS_JS_Example/Form_Rest_Using_Jquery.html
  

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
  <h3>Before Choose File</h3>
  <img src="http://faizakram.com/github/HTM_CSS_JS_Example/filesize.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
  <h3>After Choose File</h3>
  <img src="http://faizakram.com/github/HTM_CSS_JS_Example/filesize2.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
  <h3>Demo Link</h3>
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
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/buttonHome.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
<h3>After Click </h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/buttonHome2.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
<h3>Demo Link</h3>
http://faizakram.com/github/HTM_CSS_JS_Example/AddOrRemoveClass.html

===============================================================================================================


<h2>Click Event On Google Map Marker</h2>
==========================================
```
	function initMap() {
        var myLatlng = {lat: -25.363, lng: 131.044};
 
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 4,
          center: myLatlng
        });
 
        var marker = new google.maps.Marker({
          position: myLatlng,
          map: map,
          title: 'Click to zoom'
        });
 
        map.addListener('center_changed', function() {
          // 3 seconds after the center of the map has changed, pan back to the
          // marker.
          window.setTimeout(function() {
            map.panTo(marker.getPosition());
          }, 3000);
        });
                                //Redirection Method Open..
        marker.addListener('click', function() {
          alert("Let Go To Link");
          document.location.href="http://faizakram.com";
        });
        //Redirection Method Close..
      }
```
================================================================================================
<h3>Before Click </h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/map1.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
<h3>After Click </h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/map2.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>
<h3>After Click redirect</h3>
<img src="http://faizakram.com/github/HTM_CSS_JS_Example/map3.PNG" alt="Web Project, Java Web Project, Java Developer, Delhi Web Developer, Delhi Java Developer, Delhi, Bihar, Patna, Gaya, USA, Java, Spring, Hibernate, School Project, Company CEO, Spring MVC, Spring Security, Maven, Ajax, JavaScript, project, work, faiz, branding, design, school, akram, blood, healthcare, new, soon, developement, search, webdesign, coming, delhi, drugs, engine, instant, portal, escriptions, technologies, doctor, fill, found"/>

<h3>Demo Link</h3>
http://faizakram.com/github/HTM_CSS_JS_Example/OnMapMarkerClickEvent.html

