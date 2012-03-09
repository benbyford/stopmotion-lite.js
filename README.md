Stopmotion-lite.js v1.2
By Ben Byford


USEAGE:

JS – defaults: stopmotion(’#slideImages’,‘100’, ‘1’, '0')

$(function(){ 
	stopmotion(divID, animationSpeed, pauseButton, navButton); 
	
	//divID = class or id of target div container with images 
	//pauseButton 1 on / 0 off
	//navButton 1 on / 0 off 
});


CSS
#slideImages{ 
	opacity: .6; 
	background: url('images/quality6.jpg') 0 10px no-repeat; 
	height: 415px; 
	} 
#slideImages img{ 
	padding-top: 10px; 
	margin: 0 auto; 
	display: none; 
	} 
#slideImages img:first-child{ 
	display: block; 
	} 
#loading{ 
	position: absolute; 
	top: 300px; 
	left: 49%; 
	z-index: 999; 
	}


VERSIONS:
1.2 - 04/03/2012
	Added
		navButton - forward and back buttons while animation regardless if animation is paused or not
		Option to added/remove navButtons button
	Change
		Class name 'first' - changed to 'firstSlide' as not to conflict with other classes in a pages' css
	
1.1 - 29/05/2011
	Added
		pause/play button
		Option to added/remove pause/play button
	
1.0 - 27/05/2011