social-buttons
==============

```
<link rel="stylesheet" href="social-buttons.css">
```
```
<div id="social" class="social"></div>
```
```
<script src="http://code.jquery.com/jquery-2.1.0.min.js"></script>
<script src="social-buttons.js"></script>
<script>
  $(function() {
    $("#social").socialButtons({
      socialNetworks: ["facebook", "twitter", "googleplus"],
      url: "http://juhuu",
      text: "hallo world",
      sharelabel: true,
      sharelabelText: "SHARE"
    });
  })
</script>
```
