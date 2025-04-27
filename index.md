---
layout: none
permalink: /
---

<script>
  var userLang = navigator.language || navigator.userLanguage;
  if (userLang.startsWith('uk')) {
    window.location.href = "/uk/";
  } else {
    window.location.href = "/en/";
  }
</script>

<p>Redirecting based on your language preference...</p>
