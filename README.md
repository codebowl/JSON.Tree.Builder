JSON.Tree.Builder
=================

###What is this repo about?
The main goal of *JSON.Tree.Builder* is being easy to use.  
Simply create live, HTML trees - from plain JSON objects using javascript.  
Generated trees comes with the support of collapse/expand by click.

###Why it is "simple"?
Because when you are using it, you're not expected to transform your JSON objects into "key/value" nodes   
or similar tricks; it's simple: pass JSON and get a tree (it's green!).   

The returned tree built as hierarchic `<UL>` elements and it is ready to be appended into your HTML page.

###How can I use it in my project?

By three lines of javascript.  
This is really a tiny lib and usage is pretty straightforward:
```javascript
var treeBuilder = new JsonTreeBuilder();
var tree = treeBuilder.build(myJsonObject);
$('myTreePlaceholder').append(tree);
```
1.  Initialize an instance of `JsonTreeBuilder`
2.  call `build` function and pass your JSON object (as is)
3.  append the result to your container element on the page

Good to go!

###Dependencies
This project depends on JQuery (tested with V2.0)

###Hey, You!
Currently, this is a small, few hours project, with great potential.  
It can be taken to the next level with features like keyboard navigation, search and node actions  
like add, remove, edit, drag and drop etc.

Try it, fork it and push your contribution; you're welcome!
