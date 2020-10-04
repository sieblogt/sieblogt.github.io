Kurzlich habe ich endlich eine Galerie auf meiner Jekyll Website geschafft, nach ich mehreren Versuchen mit verschiedenen Plugins gemacht habe. Mit die meisten Fotogalerie Plugins war ich nicht zufrieden, außerdem ich fand sie kompliziert zu erstellen. Zum Glück gibt es einen einfacher Weg ohne Plugins, der Jekyll Codex zur verfugung stellt.

Wie funktioniert es?

Zuerst muss man Lightbox auf seiner Jekyll Webseite installieren. Um Lightbox zu installieren, herunterladen Sie die Datein lightbox.js und lightbox.css, dan speicheren Sie sie in Ihren assets/js und assets/css Ornder. Dannach auf Ihrem footer.html oder am unteren Ende auf Ihrem Layout mussen Sie auch das Script hier addieren. In meinem Fall die footer.html Datei war in _includes Ornder.

Dannach, um die Fotogalerie zu erstellen, brauchen Sie die Datei image-gallery.html zu herunterladen, die finden Sie auf diesem Jekyll Codex Seite. Speichern Sie diese Datei in Ihrem _includes Ordner.

Schließlich, auf Ihrem Webseite, wo Sie die Fotogalerie zeigen wollen, addieren Sie das Script unten, das finden Sie auch hier:

{% include image-gallery.html folder="/uploads/album" %}

So sieht es meine Fotogalerie aus. 

![Fotogalerie](https://user-images.githubusercontent.com/72214216/95007951-a3602880-0615-11eb-9d5e-534dbabc84cf.PNG)
