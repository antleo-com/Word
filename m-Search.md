---
layout: home
---

## Search this site

<html>

<link href="./pagefind/pagefind-ui.css" rel="stylesheet">
<script src="./pagefind/pagefind-ui.js"></script>

<div id="search"></div>
<script>
window.addEventListener('DOMContentLoaded', (event) => {
        new PagefindUI({ element: "#search", showSubResults: true });
    });
</script>
</html>

Use the search box above to search for a word, a combination of words, or hashtags.

Current hastags: 

#word-study

#koine-greek-resources

Or use the lunr search option for different results

{% include search-lunr.html %}