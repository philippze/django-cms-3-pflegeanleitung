Django CMS Pflegeanleitung
==========================

Dies ist eine kurze Handreichung zur Pflege Ihrer Webseite.
Sie ist geeignet für Django CMS Installationen ab Version 3.0.


Anmelden als Administrator
--------------------------

Rufen Sie Ihre Webseite auf. Löschen Sie in der Internetadresse alles ab dem ersten Schrägstrich (/) und schreiben Sie stattdessen "/admin". Geben Sie dann Ihre Benutzerdaten ein.


Zwei Oberflächen Ihrer Webseite
-------------------------------

Nach dem Anmelden bekommen Sie einen Blick auf die **Administrationsoberfläche** Ihrer Webseite. Diese brauchen Sie aber in vielen Fällen gar nicht. Das Django-CMS erlaubt es, so gut wie alle Inhalte im "Frontend" zu bearbeiten, also dort, wo sie auch angezeigt werden. Sie können sich also nach der erfolgreichen Anmeldung wieder zurück zur **grafisch ausgearbeiteten Oberfläche** Ihrer Webseite begeben und werden dort dann ein paar Knöpfe finden, mit denen Sie jede Seiten bearbeiten können.

Sie können auch über die Administrationsoberfläche zu jeder einzelnen Seite navigieren. Under dem Abschnitt "CMS" > "Seiten" finden Sie Ihren kompletten Seitenbaum.


Zwei Modi zum Betrachten einer Seite
------------------------------------

Wenn Sie eingeloggt sind, gibt es oben rechts auf der Seite einen Knopf, auf dem entweder "**Entwurf**" oder "**Live**" steht. Im "Live"-Modus sehen Sie eine Seite so, wie normale Besucher auch. Im "Entwurf"-Modus können Sie die Seite bearbeiten. Durch Klicken auf "Live", bzw. "Entwurf" können Sie zwischen diesen beiden Modi wechseln.



Zwei Modi zum Bearbeiten einer Seite
------------------------------------

Im Entwurf-Modus sehen Sie, ebenfalls oben rechts, zwei Knöpfe, auf denen "**Inhalt**", bzw. "**Struktur**" steht. Durch Klicken können Sie zwischen diesen beiden Modi wechseln.

Im Inhalt-Modus erhalten Sie durch einen Doppelklick auf Inhaltselemente die Möglichkeit, diese zu bearbeiten.

Im Struktur-Modus können Sie neue Inhaltselemente hinzufügen, sowie vorhandene verschieben oder löschen.


Der Struktur-Modus
------------------

Hier finden Sie für jeden Abschnitt der Seite einen dunklen Balken, die am rechten Ende ein paar weiße Striche hat. Wenn Sie mit der Maus über diese Striche fahren, öffnet sich eine Liste mit den in dem Abschnitt möglichen Inhaltselementen, die hoffentlich aussagekräftige Namen haben, so dass offensichtlich ist, welche Elemente wozu gut sind. Gängige Inhaltselemente sind "Text" oder "Bild", aber vermutlich finden Sie auch Inhaltselemente, die speziell auf Ihre Webseite zugeschnitten sind. Mit einem Klick auf das gewünschte Element fügen Sie es dem Abschnitt hinzu.

Jedes einzelne Inhaltselement wird durch einen hellen Balken repräsentiert. Auch dieser Balken hat am rechten Ende ein Menü, das durch einige helle Striche symbolisiert wird. Damit können Sie Aktionen wie das Löschen einzelner Inhalselemente durchführen.

Wenn Sie mehrere Inhaltselemente in einem Abschnitt haben, können Sie deren Reihenfolge ändern, indem Sie eines der Inhaltselemente mit der Maus packen und es an eine andere Stelle verschieben.


Der Inhalts-Modus
-----------------

Wenn Sie nur den Inhalt schon vorhandener Elemente verändern wollen, sind Sie hier richtig. Durch einen Doppelklick auf den gewünschten Inhalt erhalten Sie die Möglichkeit, ihn zu bearbeiten. Der Rest sollte sich von selber erklären.


Veröffentlichen von Änderungen
------------------------------

Änderungen, die Sie im Modus "Entwurf" durchführen, sind zunächst nicht öffentlich sichtbar. Sobald Sie etwas geändert haben, erscheint oben rechts auf der Seite ein neuer Knopf mit der Aufschrift "Änderungen publizieren". Erst wenn Sie auf diesen klicken, werden Ihre Änderungen öffentlich sichtbar.


Eine neue Seite erstellen
-------------------------

Im der oberen Menüleiste auf der linken Seite finden Sie den Menüpunkt "Seite". Dort gibt es den Unter-Menüpunkt "Seite hinzufügen".


Vorlagen
--------

Wenn Sie im "Entwurf" Modus sind, können Sie im Menü "Seite" > "Vorlagen" die Vorlage Ihrer Seite ändern. Damit sollten Sie ganz vorsichtig sein. Die Vorlage bestimmt, in welche Bereiche Ihre Seite eingeteilt ist. Typischerweise hat etwas die Startseite eine andere Vorlage, als die restlichen Seiten.


Besonderheiten
--------------

### Zwei Sorten von Zeilenumbrüchen

In allen gängigen Webeditoren gibt es zwei Möglichkeiten, eine neue Zeile zu beginnen. ENTER und STEUERUNG+ENTER. Mit der ENTER Taste beginnen Sie einen neuen Absatz, der einen gewissen Abstand zur vorherigen Zeile haben sollte. Durch Drücken von STEUERUNG+ENTER fügen Sie einen regulären Zeilenumbruch ein, der keinen besonderen Abstand zur vorherigen Zeile hat.


### Setzen von Links

Wenn Sie im Editor keinen Knopf finden, um Links zu erzeugen, dann finden Sie dort im Menü "CMS Plugins" die Möglichkeit, dies zu tun.


Abmelden
--------

Im der oberen Menüleiste finden Sie links die Internetadresse Ihrer Webseite (voreingestellt ist example.com). Dort gibt es den Unter-Menüpunkt "Admin abmelden".


Passwort ändern
---------------

So etwas kann nie schaden .. außer Sie vergessen das Passwort deshalb.

Hierzu klicken Sie in der oberen Menüleiste wieder auf die Internetadresse Ihrer Webseite und dann auf "Administration ...". Im sich dann öffnenden Menü wählen Sie "Benutzer" aus und anschließend Ihren eigenen Benutzernamen. Relativ oben steht, dass das Passwort über "dieses Formular" geändert werden kann. Wenn Sie jetzt auf "dieses Formular" klicken, können Sie ein neues Passwort angeben.


Verbesserungsvorschläge für diese Pflegeanleitung sehr gerne an philipp@neue-musik.com  
Verbesserungen in Forks auch gerne.
