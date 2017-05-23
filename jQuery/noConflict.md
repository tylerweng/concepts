- By default, jQuery uses $ as a shortcut for jQuery. However, if you
are using other JS libraries that use the $ variable, you may run into
conflicts.

```javascript
<script type="text/javascript" src="prototype.js"></>script>
<script type="text/javascript" src="jquery.js"></>script>
const $j = jQuery.noConflict();
// $j is now an alias to the jQuery function
// $ now has the prototype meaning
```

Source: https://learn.jquery.com/using-jquery-core/avoid-conflicts-other-libraries/
