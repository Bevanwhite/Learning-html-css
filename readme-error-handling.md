1. html error
    1. problem - prettier not format the code properly
    2. solution `just start with  <html> </html>`
    3. cause of the problem was i have added the **_closing tag_** without having the **_opening tag_**
```  taken from prettier output
["ERROR" - 12:09:42 PM] Error formatting document.
["ERROR" - 12:09:42 PM] Unexpected closing tag "html". It may happen when the tag has already been closed by another tag. For more info see https://www.w3.org/TR/html5/syntax.html#closing-elements-that-have-implied-end-tags (25:1)
  23 |
  24 |   </body>
> 25 | </html>
     | ^^^^^^^
```
