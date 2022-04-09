# delete-github-issue-bookmarklet
Use this bookmarklet to quickly delete an issue.

Drag this link into your bookmarklet bar after you check the code in the `bookmarklet.js` file to understand how it works.

You can use the code below to make your own bookmarklet on js fiddle or some other online code tool, or even just paste the code into an HTML page on your local machine, or you can open the [github.io](https://htmlpreview.github.io/?http://github.com/RIAEvangelist/delete-github-issue-bookmarklet/blob/main/bookmarklet.html) example which loads the `bookmarklet.html` page for your ease of use. Just drag the bookmarklet to the bookmarks tab and you are good to go.

```html
<html> 
    <body>
        <h1>
            Drag the link below into your bookmarklet tabs for quick access.
        </h1>
        <a href="javascript:(function()%7Bdocument.querySelector('.js-delete-issue strong').click()%3Bdocument.querySelector('%5Bname%3D"verify_delete"%5D').click()%7D)()">
          Delete GitHib Issue
        </a>
    </body>
</html>
```

