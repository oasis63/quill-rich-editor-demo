# quill-rich-text-editor- andgular demo
rich text editor using quill 


Required versions of the quill add these three lines to the package.json of the angular project
in the dependencies 
1) "@types/quill": "^1.3.7",
2) "ngx-quill": "^16.2.1",
3)  "quill": "^1.3.7",

keep in mind that ,, to quill work properly ,, its version should be  1.x


Now add these following lines to styles array of the angular.json file 

"node_modules/quill/dist/quill.core.css",
"node_modules/quill/dist/quill.snow.css"


