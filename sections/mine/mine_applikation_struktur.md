<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>
<span class="fragment step-fade-in-then-out"></span>

<div data-animate data-src="images/mine_system_layers.drawio.svg">
<!--
{ "setup": [
{ "element": "[id*='cell-']", "modifier": "opacity", "parameters": [ 0 ] },
{ "element": "#cell-5, #cell-3, #cell-4", "modifier": "opacity", "parameters": [ 1 ] }
],
"animation": [
[],
[{ "element": "#cell-13, #cell-12, #cell-18", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-13 > path, #cell-12 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }],
[{ "element": "#cell-20, #cell-14, #cell-15", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-18", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }, { "element": "#cell-14 > path, #cell-15 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }, { "element": "#cell-13 > path, #cell-12 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#000000", "stroke-width": 1} ] }],
[{ "element": "#cell-7, #cell-6, #cell-19", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-20", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }, { "element": "#cell-7 > path, #cell-6 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }, { "element": "#cell-14 > path, #cell-15 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#000000", "stroke-width": 1} ] }],
[{ "element": "#cell-22, #cell-24, #cell-23", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-19", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }, { "element": "#cell-7 > path, #cell-6 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#000000", "stroke-width": 1} ] }],
[{ "element": "#cell-27, #cell-25", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-25 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }],
[{ "element": "#cell-29", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-27", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }],
[{ "element": "#cell-35, #cell-33", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-29", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }, { "element": "#cell-33 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }, { "element": "#cell-25 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#000000", "stroke-width": 1} ] }],
[{ "element": "#cell-38", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-35", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }],
[{ "element": "#cell-44, #cell-40", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-38", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }, { "element": "#cell-40 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#343aeb", "stroke-width": 2} ] }, { "element": "#cell-33 > path", "duration": 50, "modifier": "attr", "parameters": [ {"stroke": "#000000", "stroke-width": 1}]}],
[{ "element": "#cell-45", "duration": 50, "modifier": "opacity", "parameters": [ 1 ] }, { "element": "#cell-44", "duration": 50, "modifier": "opacity", "parameters": [ 0.3 ] }]
]
}
-->
</div>
<!--
<button onclick="RevealAnimate.play();this.blur();return false;">Play</button>
<button onclick="RevealAnimate.pause();this.blur();return false;">Pause</button>
<button onclick="RevealAnimate.seek(500);this.blur();return false;">Seek 500</button>
-->

Note:
    Zunächst wollen wir einen Blick auf den Aufbau der Platform werfen.
    Um zum einen einen möglichst schnellen Start der Dateneingabe zu gewährleisten und andererseits die Interoperabilität unserer Systeme zu gewährleisten baut MINE auf die APIS Platform auf. Wie Frau Prof. Lenz schon ausgeführt hat wurde diese Software im Zuge des APIS Projektes entwickelt und wird seither in vielen verschiedenen prosopographischen Anwendungen angewendet und weiterentwickelt.
    SLIDE
    Dieser APIS Layer bietet Formulare für die Dateneingabe. In diesem konkreten Fall handelt es sich um die Eingabe, dass Heinrich Srbik von 1934 bis 1952 Mitglied der Finanzkommission war. Diese Formulare erlauben es Entitäten - also zb die Kommissionen der Akademie - direkt im Formular zu suchen und auszuwählen. Diese Suche dehnt sich auch auf Entitäten aus die noch nicht in MINE erfasst sind, aber zb aus der GND (Gemeinsamen Normdatei) importiert werden können. Diese Funktion spielt zwar für die Erfassung der Kerninformationen in MINE keine Rolle - diese wurden alle aus Primärquellen erhoben -, sie ist aber für die Erfassung der sekundären Entitäten eine große Arbeitserleichterung. So studierte und promovierte Heinrich Srbik an der Universität Wien. Die Universität Wien ist natürlich keine Institution der Akademie und wird deshalb auch nicht primär erfasst. Mit diesem System können die wichtigsten Metadaten (Gründungsjahr, Art der Institution, Identifikatoren etc.) mit einem Click importiert werden und die WissenschaftlerInnen sparen Zeit für die Erfassung der zentralen Daten.
    SLIDE
    Einige Daten wurden automatisch in MINE eingepflegt. So wurden Listen der Mitglieder der Akademie aus Akademis exportiert und in MINE importiert. Das APIS Grundsystem stellt für solche Anwendungen eine Andockstelle für "Jupyter Notebooks" zur Verfügung. Diese Notebooks erlauben es schnelle adhoc Skripte für die automatische Manipulation der Daten zu schreiben. Im Falle der Akademis Daten wird das aus Akademis exportierte Excel Sheet in das Notebook geladen, umformatiert und in die Datenbank hochgeladen. Diese Notebooks wurden auch verwendet um die Auswertungen für das Buch aus MINE zu erstellen.
    SLIDE
    Für viele WissenschafterInnen sind Webapplikationen wie jene die wir heute vorstellen weniger wichtig als die Daten selbst. Sie wollen andere Auswertungen machen als jene die wir anbieten, die Daten mit ihren eignen kombinieren oder in größere Datensätze integrieren. Webapplikationen sind aber auch für Tools - zb Annotationswerkzeuge für digitale Editionen - nur schlecht konsumierbar. Für diese Anwendungsfälle bietet APIS eine API - eine maschinenlesbare Version der Website. Diese erlaubt es Datensätze zu filtern und in verschiedenen Versionen herunterzuladen. Unter anderem bietet das System ein internes Json Format, RDF und TEI.
    SLIDE
    Auf diesen Grundlayer, der allgemein gültige Anforderungen fast aller prosopographischen Projekte zur Verfügung stellt, setzen wir dann einen projektspezifischen Layer für MINE auf. Dieser greift auf die vom Basislayer zur Verfügung gestellte Datenbank zu.
    SLIDE
    Eine der grundlegenden Funktionen von MINE ist jene komplexe Auswertungen durchführen zu können. Dafür wurde dieses Formular - das wir uns später noch live anschauen werden - erstellt. Es erlaubt die Kombination von vielen verschiedenen Filtermöglichkeiten zu einer Auswertung. Links finden sich die wichtigsten Filtermöglichkeiten schon ausgeklappt: Klasse und Mitgliedschaft. Die weiteren Filter - wie zb Geschlecht, Beruf, Ausbildung, ob die Person einen Nobelpreis gewonnen hat, oder ob sie Mitglied der NSDAP war - sind im rechten Teil des Formulars in Kategorien zusammengefasst.
    SLIDE
    Hat man sich für Filter entschieden und clickt auf "Kombinierte Auswertung starten" bringt einen das zu einer Ansicht des Ergebnisses, das im linken Panel weiter eingeschränkt werden kann. Dazu nachher mehr wenn wir uns die Live Version der Applikation ansehen.
    SLIDE
    Entscheidet man sich dann für einen Eintrag aus dem Auswertungsergebnis bringt einen das zum Profil der jeweiligen Person - wir sehen hier das Profil von Heinrich Srbik. Wieder finden sich die wichtigsten Informationen zu der Person - Name, Bild (so vorhanden), Lebensdaten und Abfolge der Mitgliedschaften im linken Panel. Darunter lässt sich der Eintrag über die zuvor schon angesprochene API in maschinenlesbaren Formaten herunterladen. Im rechten Panel finden sich die Details - so schon erfasst - der biographischen Informationen des Mitgliedes. Jedes Profil beinhaltet ausserdem ein Egonetzwerk - das die Verbindungen der Person zu den Kommissionen der Akademie zeigt - und eine Kartenansicht - die die Orte in der Biographie der Person im Ablauf ihres Lebens zeigt.
    SLIDE
    Eine ganz ähnliches Profil gibt es auch für die Institutionen der Akademie.
    SLIDE
    MINE bietet ausserdem - wie zuvor schon angesprochen - Visualisierungen sowohl größerer Gruppen von Mitgliedern, als auch einzelner Personen. Hier abgebildet sieht man die ersten 1000 Verbindungen der wirklichen Mitglieder zu den Kommissionen der Akademie.
    SLIDE
    Als Beispiel für die Kartenvisualisierung sehen wir hier den im Profil untergebrachten Lebensweg von Heinrich Srbik von seiner Geburt in Wien zu seinem Tod in Ehrwald (Tirol). Die Zitleiste auf der rechten Site gibt dabei auf der X-Achse die Distanz des Ortes zum Vorgängerort wieder.



