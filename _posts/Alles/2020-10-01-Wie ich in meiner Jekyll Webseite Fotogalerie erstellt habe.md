Kurzlich habe ich endlich eine Galerie auf meiner Jekyll Website geschafft, nach ich mehreren Versuchen mit verschiedenen Plugins gemacht habe. Mit die meisten Fotogalerie Plugins war ich nicht zufrieden, außerdem ich fand sie kompliziert zu erstellen. Zum Glück gibt es einen einfacher Weg ohne Plugins, der [Jekyll Codex](https://jekyllcodex.org/without-plugin/image-gallery/) zur verfugung stellt. 

Wie funktioniert es?
- Zuerst muss man [Lightbox](https://jekyllcodex.org/without-plugin/lightbox/) auf seiner Jekyll Webseite installieren. 
Um Lightbox zu installieren, herunterladen Sie die Datein [lightbox.js](https://jekyllcodex.org/without-plugin/lightbox/) und [lightbox.css](https://jekyllcodex.org/without-plugin/lightbox/), dan speicheren Sie sie in Ihren assets/js und assets/css Ornder. Dannach auf Ihrem `footer.html` oder am unteren Ende auf Ihrem `Layout` mussen Sie auch das Script [hier](https://jekyllcodex.org/without-plugin/lightbox/) addieren. In meinem Fall die footer.html Datei war in \_includes Ornder. 


- Dannach, um die Fotogalerie zu erstellen, brauchen Sie die Datei `image-gallery.html` zu herunterladen, die finden Sie auf diesem [Jekyll Codex Seite]( https://jekyllcodex.org/without-plugin/image-gallery/). Speichern Sie diese Datei in Ihrem \_includes Ordner.  


- Schließlich, auf Ihrem Webseite, wo Sie die Fotogalerie zeigen wollen, addieren Sie das Script unten, das finden Sie auch [hier]( https://jekyllcodex.org/without-plugin/image-gallery/):



So sieht es meine Fotogalerie aus.
![Fotogalerie](https://user-images.githubusercontent.com/72214216/94930132-46a22800-04c6-11eb-95c9-6c86aba54588.PNG)
