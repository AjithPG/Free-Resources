# Front-End-Developers-KeyNotes
A useful codes,Notes and tutorials for front end developers
<h2>Best Tools for developers</h2>
<li>Webcode Tools:https://webcode.tools/</li>
<li>Online IDE:https://repl.it/</li>

<h2>Useful Resources for Web developers<h2>

<h2>Gulp Install</h2>
<p>We need Node.js to run Gulp
https://nodejs.org/en/</p>


<p>Install gulp through cmd and Check gulp version</p>
<ul>
  <li>npm install gulp -g</li>
  
  <li>gulp --version</li>
</ul>

<p>Creating a task in gulp</p>
<code>
  gulp.task('task-name', function() {
   //do stuff here
});
</code>
<h2>Installing Plugins</h2>
<h3>Gulp plugin to minify CSS, using <code>clean-css</code></h3>
<h4>Install</h4>
<code>npm install gulp-clean-css --save-dev</code>

<p>Add this line to gulpfile.js</p>
<code>var cleanCSS = require('gulp-clean-css');</code>

<h4>Task to minify-css</h4>
<code></code>
