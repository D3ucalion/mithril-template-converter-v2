This is an update to the current Mithril.js template converter.

I have fixed a bug regarding incorrect handling of class attributes. I have also adding some better styling.

More improvements are on the way. 

Current known issues:

     1. Elements with self closing tags are often incorrectly handled.
     2. Large amounts of text between element tags is sometimes handled incorrectly.
     3. Any extra line breaks seem to cause issues. 
     4. Commented HTML causes issues.
     5. Even when you adjust the html to prevent the above, you often end up with an extra comma and set of double quotes 
     after each parent element. Although I did correct the issue with the additional backslash being added.