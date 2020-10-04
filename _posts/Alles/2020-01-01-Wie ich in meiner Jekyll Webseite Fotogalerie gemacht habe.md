Kurzlich habe ich endlich eine Galerie auf meiner Jekyll Website geschafft, nach ich mehreren Versuchen mit verschiedenen Plugins gemacht habe. Mit die meisten Fotogalerie Plugins war ich nicht zufrieden, außerdem ich fand sie kompliziert zu erstellen. Zum Glück gibt es einen einfacher Weg ohne Plugins, der [Jekyll Codex](https://jekyllcodex.org/without-plugin/image-gallery/) zur verfugung stellt. 

Wie funktioniert es?
- Zuerst muss man [Lightbox](https://jekyllcodex.org/without-plugin/lightbox/) auf seiner Jekyll Webseite installieren. 
Um Lightbox zu installieren, herunterladen Sie die Datein [lightbox.js](https://jekyllcodex.org/without-plugin/lightbox/) und [lightbox.css](https://jekyllcodex.org/without-plugin/lightbox/), dan speicheren Sie sie in Ihren assets/js und assets/css Ornder. Dannach auf Ihrem footer.html mussen Sie auch das Script unten addieren. In meinem Fall die footer.html Datei war in \_includes Ornder. 
```
...
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">
</body>
</html>

``` 

- Dannach um die Fotogalerie zu erstellen, brauchen Sie die Datei `image-gallery.html` zu herunterladen, die finden Sie auf diesem [Jekyll Codex Seite]( https://jekyllcodex.org/without-plugin/image-gallery/). Speichern Sie diese Datei in Ihrem \_includes Ordner.  Schließlich, auf Ihrem Webseite, wo Sie die Fotogalerie zeigen wollen, addieren Sie dieses Script:

`{% include image-gallery.html folder="/uploads/album" %}`.

So sieht es meine Fotogalerie aus.
![Fotogalerie](https://user-images.githubusercontent.com/72214216/94930132-46a22800-04c6-11eb-95c9-6c86aba54588.PNG)
