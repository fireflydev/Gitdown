Gitdown
=======

A PHP Class to Beautify and Syntax Highlight Github Style Markdown Utilizing the Github v3 API
Includes Markdown and Pygments CSS

Example:
```php

  $markdown = file_get_contents('my-markdown-doc.md');
  $html = Gitdown::pretty($markdown);


```
