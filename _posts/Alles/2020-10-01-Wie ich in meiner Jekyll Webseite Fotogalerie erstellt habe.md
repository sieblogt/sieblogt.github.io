---
comment_issue_id: 1
title: Wie ich auf meiner Jekyll Website Fotogalerie erstellt habe
---

Kurzlich habe ich endlich eine Fotogalerie auf meiner Jekyll Website geschafft, nach ich mehreren Versuchen mit verschiedenen Plugins gemacht habe. Mit die meisten Plugins war ich nicht zufrieden, außerdem ich fand sie kompliziert zu erstellen. Zum Glück gibt es einen einfacher Weg ohne Plugins, der [Jekyll Codex](https://jekyllcodex.org/without-plugin/image-gallery/) zur verfugung stellt. 


Wie funktioniert es? Zwei Etappen. 

### Lightbox in Ihrem Projekt installieren
- Zuerst mussen Sie [Lightbox](https://jekyllcodex.org/without-plugin/lightbox/) auf Ihrem Jekyll Webseite installieren, wenn es auf Ihrem Projekt noch nicht installiert ist. 
Um es zu installieren, mussen Sie zwei Datein von [Jekyll Codex Ligthbox](https://jekyllcodex.org/without-plugin/lightbox/) Seite herunterladen,  das [lightbox.js](https://jekyllcodex.org/without-plugin/lightbox/) und das [lightbox.css](https://jekyllcodex.org/without-plugin/lightbox/). Dann, speicheren Sie diese Datein in Ihren `assets/js` und `assets/css` Ornder. 

- Anschließend, auf Ihrem `footer.html` oder am unteren Ende auf Ihrem `Layout` mussen Sie auch das Script unten addieren. Sie können auch es [hier](https://jekyllcodex.org/without-plugin/lightbox/) finden. In meinem Fall die footer.html Datei war in `_includes` Ornder. 
![Ligthbox](https://user-images.githubusercontent.com/72214216/95009158-19698d00-0620-11eb-94e9-174ba1565b38.PNG)


### Fotogalerie Script addieren
- Um die Fotogalerie zu erstellen, brauchen Sie die Datei `image-gallery.html` zu herunterladen, die finden Sie auf diesem [Jekyll Codex Webseite]( https://jekyllcodex.org/without-plugin/image-gallery/). Speichern Sie diese Datei in Ihrem `_includes` Ordner.  



- Schließlich, wo Sie die Fotogalerie zeigen wollen, auf Ihrem `.html` Datei in Ihrem `_posts` Ordner, addieren Sie das Script unten. Das Script finden Sie auch [hier]( https://jekyllcodex.org/without-plugin/image-gallery/):
![imgg](https://user-images.githubusercontent.com/72214216/95009168-2e462080-0620-11eb-8526-4f8bf51a05b7.PNG)



So sieht es meine Fotogalerie aus.
![Fotogalerie](https://user-images.githubusercontent.com/72214216/96205960-25cadf80-0f68-11eb-9a8b-0260a9550a9f.png)


<center><a href="http://mehrapi.github.io/">Zurück zur Hauptseite</a></center>
