---
title: roam/js
---

- 

- {{[[roam/js]]}}
	 - ```javascript
var old = document.getElementById("phone-to-roam-script");
  if (old) { old.remove(); }
  var s = document.createElement("script");
  s.src = "https://client.phonetoroam.com/phone-to-roam.js";
  s.id = "phone-to-roam-script";
  s.async = false;
  s.type = "text/javascript";
  s.dataset.roam_key = "618ab38a5cb7d5d30d21"
  document.getElementsByTagName("head")[0].appendChild(s);
```
