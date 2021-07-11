[1]:https://google.com
[Google]:https://google.com


# Links in Markdown

    1. <URL>
    2. <<URL>>
    3. [<TEXT>](<URL>)
    4. [<TEXT>](<URL> "<HOVER_TEXT>")
    5. [<TEXT>][<TOKENS> OR <KEYS>]
       
       [<TOKENS>]: <URL>
       [<KEYS>]: <URL>


**Note:**  

`<TEXT>` are clickable links.

`<HOVER_TEXT>` are short texts that pop like bubble when hovered over the `<TEXT>`

`<TOKENS>` are Numerical Mappings to the `<URL>`. 

`<KEYS>` are String Mapping to the `<URL>`.

`<TOKENS>, <KEYS>` are a Key:Value Pair Notation.
<br>We can define this as an equivalent of a variable in Programming Language. Reusable.
<br> And, `<TOKENS>, <KEYS>` should be at the bottom or Top of the document always.

1. https://google.com
2. <https://google.com>
3. [Google](https://google.com)
4. [Google](https://google.com "Links to Google Search Engine")
5. [Google][1]
   
   5.1 [Google][Google]
    
    [1]:https://google.com
    [Google]:https://google.com

