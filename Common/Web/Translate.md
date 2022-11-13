#### Add translate snippet
```js
<div id="google_translate_element"></div>
<script>
    function googleTranslateElementInit() {
        new google.translate.TranslateElement(
            {pageLanguage: 'en', layout: google.translate.TranslateElement.InlineLayout.HORIZONTAL},
            'google_translate_element'
        );
    }
</script>
<script src="http://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
```

![[c77e148da4ccc71c8cfcd55ac4490de7.png]]