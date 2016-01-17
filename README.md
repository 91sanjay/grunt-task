# grunt-task
A simple grunt task to assist in web development

## Installation
1. Install grunt-cli ```npm install -g grunt-cli```
2. Install grunt ```npm install grunt -save-dev```

## Usage
This grunt task helps me with maintaning development and production code. My folder structure is as follows

.
+-- app
|	+-- sass
|	+-- css
|	+-- images
|	+-- js
|	+-- index.html
+-- dist
|	+-- css
|	+-- js
|	+-- images
|	+-- index.html

app - Development directory; dist - Distribution(Production code with minfied and optimized assets)

The grunt task performs the following -
#### Development -
1. Compile Sass files and copy to css folder
2. Lint Javascript in JS folder
3. Optimize images that are added for the first time(will need customization according to requirements)
4. Setup live reload to refresh browser when the code changes
5. Watch the code for any changes and perform the tasks mentioned above

#### Distribution
1. Minify CSS and copy to dist/css
2. Uglify Javascript and copy to dist/js
3. Minify HTML and copy to dist
4. Optimize images and copy to dist/images

# Author
Sanjay Rajashekhar

