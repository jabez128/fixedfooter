fixedfooter
===========

A simple but decent fixed footer less library

no hack and run perfectly in IE8+,Chrome,Firefox and Safari.

#Useage

	import fixfooter

	@height: 100px;
	@name: my-fix-footer;

	.fixfooter(@height,@name);

then compile the less file to css file

	html {
	  position: relative;
	  min-height: 100%;
	}
	html body {
	  margin: 0px 0px 100px;
	}
	html body .my-fix-footer {
	  position: absolute;
	  bottom: 0px;
	  left: 0px;
	  width: 100%;
	  height: 100px;
	}


	
