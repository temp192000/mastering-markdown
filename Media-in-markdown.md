# Media in Markdown

    1. ![<ALT_TEXT>](<URL>)
    2. ![<ALT_TEXT>](<URL> "<TOOL_TIP_TEXT OR HOVER TEXT>")
    3. ![<ALT_TEXT>][<TOKENS> or <KEYS>]

        [<TOKENS>]:<URL>
        [<KEYS>]:<URL>



**Note:**
<br> `'!'` tells the Markdown Parser that its a Media URL.
<br> `ALT TEXT` is for Screen Readers (Blind People use 'em) or Crawlers of Search Engine.

## Images
<hr>

1. ![Random Picture from UnSplash API](http://unsplash.it/500/500?random)

2. ![A Pup and A Man](http://unsplash.it/500/500?image=1012 "Puppy Picture")

3. ![A Pup and A Man][Pup]

<hr>

## Nested Markdowns

    Nesting ![]() inside []() would make an Image Clickable.

    Syntax: [![]()]()


[![PupPic](http://unsplash.it/50/50?image=1012)](http://unsplash.it/500/500?image=1012)

### HTML and CSS


**Why We use this now?**
<br> Well, There is no way to adjust and Height and Width in Markdown. If we want to customize how an image look up, we'd have to use HTML and/or CSS.

<img src="http://unsplash.it/500/500?image=1012" width="500px" height="500px" alt="Pup Pic"/>

<style>
    img{
        width: 200px;
        height: 200px;
    }
</style>

    We can also use figcaptions because, we don't have it in markdown yet.

    <figure>
        <figcaption></figcaption>
    </figure>

**Pro Tip**:
<br> When Something is too confusing 🤦‍♂️ to write in Markdown Syntax, Use HTML.


[Pup]: http://unsplash.it/500/500?image=1012
[Random]: http://unsplash.it/500/500?random
[1]: http://unsplash.it/500/500?image=1012
[2]: http://unsplash.it/500/500?image=1000
[3]: http://unsplash.it/500/500?image=489
[4]: http://unsplash.it/500/500?image=523