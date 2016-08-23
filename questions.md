+ Add hbsfy
+ Change b-fy task
+ Add templates to watch
+ change templates to .hbs
+ Add handlebars to node_modules
+ remove handlebars from index.html
+ Move templates to templates folder
+ Add require of Handlebars and template files to main.js
+ Remove setup of template from main.js
+ change what gets passed into DOM
+ Move taglineData into template's context so partial can access it

Make a new template with solar system data
Make it appear on a btn click
<h1>The Solar System</h1>
<ul>
{{#each planets}}
  <li>{{name}} is a {{type}} planet (index {{@key}} in the array)</li>
{{/each}}
</ul>