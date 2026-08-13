# Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request.

## How to make changes
 - If you want to modify the CSS, please edit the SCSS files present in `style/`: `main.scss` and others. Don't edit the `main.css`, because it's supposed to be generated.  
 In order to compile your SCSS modifications, you need to use the `sass` gem (install it by running `gem install sass` once Ruby is installed).  
 To run SASS, simply use the following command:  
 `sass --unix-newlines --watch style/main.scss`  
 SASS will automatically recompile your css when changed.
 - Please use 2-space indentation when editing the JavaScript. A `.jshintrc` file is present, which will help your code to follow the guidelines if you install and run `jshint`.
 - Please test your modification thoroughly before submitting your Pull Request.
