# ThePipp3-Bootstrap-Sass-PUG-theme
A template using Bootstrap, Pug and Sass. This single page template is the third iteration in me learning bootstrap. Stripping usage of bootstrap to the minimums and using mixins directly

#### Preview
![enter image description here](https://raw.githubusercontent.com/Splitter/ThePipp3-Bootstrap-Sass-PUG-theme/master/preview.png)
![enter image description here](https://raw.githubusercontent.com/Splitter/ThePipp3-Bootstrap-Sass-PUG-theme/master/preview2.png)



#### General File Structure

    /
	index.html <--Main single page template generated from PUG source
	    Pug_Source/ <-- Pug source code to generate template
	    Assets/
        	css/ <--Generated css files
            scss/ <--Source Sass files
				_functions.scss
				_variables.scss
				_vendor.scss <--Includes specific thirdparty files
				_mixins.scss
				main.scss <--Main Sass file
				custom/ <--Custom code for theme
				vendor/ <-- Third party SCSS/CSS Directory(including bootstrap)
            scripts/ <--Javascript files
            fonts/ <--Font files
            ...
