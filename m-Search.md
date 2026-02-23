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

Use the fuzzy search box above to search for a word or a combination of words.