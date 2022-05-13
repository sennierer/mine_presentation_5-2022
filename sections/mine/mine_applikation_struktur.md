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

<div data-animate data-src="images/mine_system_layers.drawio.svg" style="padding-bottom: 350%">
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


<aside class="notes">
    <ul>
    <li>Um zum einen einen möglichst schnellen Start der Dateneingabe zu gewährleisten und andererseits die Interoperabilität unserer Systeme zu gewährleisten baut MINE auf der APIS Platform auf. Wie Frau Prof. Lenz schon ausgeführt hat, wurde diese Applikation im Zuge des APIS Projektes entwickelt und wird seither in vielen verschiedenen prosopographischen Anwendungen angewendet und weiterentwickelt.</li>
    <li>SLIDE</>
    <li>Diese APIS Ebene bietet Formulare für die Dateneingabe. In diesem konkreten Fall handelt es sich um die Eingabe der Information, dass Heinrich Srbik von 1934 bis 1952 Mitglied der Finanzkommission war. Diese Formulare erlauben es Entitäten - also zb die Kommissionen der Akademie - direkt im Formular zu suchen, auszuwählen und anschliessend die Verbindung von Heinrich Srbik zu dieser Kommission abzuspeichern.</li>
    <li>Diese Suche nach zu verbindenden Entitäten dehnt sich auch auf solche aus die noch nicht in MINE erfasst sind, aber zb aus der GND (Gemeinsamen Normdatei) importiert werden können. Diese Funktion spielt zwar für die Erfassung der Kerninformationen in MINE keine Rolle - diese wurden alle aus Primärquellen erhoben -, sie ist aber für die Erfassung der sekundären Entitäten eine große Arbeitserleichterung. So studierte und promovierte Heinrich Srbik an der Universität Wien. Die Universität Wien ist natürlich keine Institution der Akademie und wird deshalb auch nicht primär erfasst. Mit diesem System können die wichtigsten Metadaten (Gründungsjahr, Art der Institution, Identifikatoren etc.) mit einem Click während der Arbeit an Heinrich Srbiks Profildaten importiert werden und die WissenschaftlerInnen sparen Zeit für die Erfassung der zentralen Daten.</li>
    <li>SLIDE</li>
    <li>Einige Daten wurden automatisch in MINE eingepflegt. So wurden Listen der Mitglieder der Akademie aus Akademis exportiert und in MINE importiert. Das APIS Grundsystem stellt für solche Anwendungen eine Andockstelle für "Jupyter Notebooks" zur Verfügung. Diese Notebooks erlauben es schnelle adhoc Skripte für die automatische Manipulation der Daten zu schreiben. Im Falle der Akademis Daten wird das aus Akademis exportierte Excel Sheet in das Notebook geladen, umformatiert und in die Datenbank hochgeladen. Diese Notebooks wurden auch verwendet um die Auswertungen für das Buch aus MINE zu erstellen.</li>
    <li>SLIDE</li>
    <li>Für viele WissenschafterInnen sind Webapplikationen wie jene, die wir heute vorstellen weniger wichtig als die Daten selbst. Sie wollen andere Auswertungen erstellen als jene die wir anbieten, die Daten mit ihren eignen kombinieren oder in größere Datensätze integrieren. Webapplikationen sind aber auch für Tools - zb Annotationswerkzeuge für digitale Editionen - nur schlecht konsumierbar. Für diese Anwendungsfälle bietet APIS eine API - eine maschinenlesbare Version der Website. Diese erlaubt es Datensätze zu filtern und in verschiedenen Versionen herunterzuladen. Unter anderem bietet das System ein internes Json Format, RDF und TEI.</li>
    <li>SLIDE</li>
    <li>Auf dieser durch APIS bereitgestellten Basis, die allgemein gültige Anforderungen fast aller prosopographischen Projekte zur Verfügung stellt, setzen wir dann einen projektspezifischen Ebene für MINE auf. Dieser greift auf die von der Basis zur Verfügung gestellte Datenbank zu.</li>
    <li>SLIDE</li>
    <li>Eine der grundlegenden Funktionen von MINE ist jene komplexe Auswertungen durchführen zu können. Dafür wurde dieses Abfrageformular - das wir uns später noch live anschauen werden - erstellt. Es erlaubt die Kombination von vielen verschiedenen Filtermöglichkeiten zu einer Auswertung. Links finden sich die wichtigsten Filtermöglichkeiten schon ausgeklappt: Klasse und Mitgliedschaft. Die weiteren Filter - wie zb Geschlecht, Beruf, Ausbildung, ob die Person einen Nobelpreis gewonnen hat, oder ob sie Mitglied der NSDAP war - sind im rechten Teil des Formulars in Kategorien zusammengefasst.</li>
    <li>SLIDE</li>
    <li>Hat man sich für eine Kombination an Suchkategorien entschieden und clickt auf "Kombinierte Auswertung starten" wird das Ergebnis angezeigt, das in der linken Spalte weiter eingeschränkt werden kann. Dazu nachher mehr wenn wir uns die Live Version der Applikation ansehen.</li>
    <li>SLIDE</li>
    Entscheidet man sich dann für einen Eintrag aus dem Auswertungsergebnis, wird das Profil der jeweiligen Person angezeigt - wir sehen hier das Profil von Heinrich Srbik. Wieder finden sich die wichtigsten Informationen zu der Person - Name, Bild (so vorhanden), Lebensdaten und Abfolge der Mitgliedschaften in der linken Spalte. Darunter lässt sich der Eintrag über die zuvor schon angesprochene Schnittstelle in maschinenlesbaren Formaten herunterladen. In der rechten Spalte finden sich alle erfassten Details der biographischen Informationen des Mitgliedes. Jedes Profil beinhaltet außerdem ein sogenanntes „Egonetzwerk“ - das die Verbindungen der Person zu den Kommissionen der Akademie zeigt - und eine Visualisierung - die die Orte in der Biographie der Person im Verlauf ihres Lebens zeigt.</li>
    <li>SLIDE</li>
    <li>Vergleichbare Such- und Filtermöglichkeiten bzw. Ansichten gibt es auch für die Institutionen der Akademie</li>
    <li>SLIDE</li>
    <li>MINE bietet ausserdem - wie zuvor schon angesprochen - Visualisierungen sowohl größerer Gruppen von Mitgliedern, als auch einzelner Personen. Hier abgebildet sieht man die ersten 1000 Verbindungen der wirklichen Mitglieder zu den Kommissionen der Akademie.</li>
    <li>SLIDE</li>
    Als Beispiel für die biographischen Ortspunkte sehen wir hier den im Profil untergebrachten Lebensweg von Heinrich Srbik von seiner Geburt in Wien zu seinem Tod in Ehrwald (Tirol). Der Zeitstrahl auf der rechten Seite stellt die Abfolge der Ereignisse dar die mit den Punkten auf der Karte verknüpft sind. Bewegt man die Maus über einen der Punkte wird auch der korrespondierende Punkt auf der Karte hervorgehoben. Zusätzlich wird auf der X-Achse des Zeitstrahls die Distanz des Ortes zum Vorgängerort dargestellt. Dadurch ist es auf einen Blick möglich Zeiträume einer Biographie mit häufigen Ortswechseln zu erkennen.</li>
    </ul>
</aside>



