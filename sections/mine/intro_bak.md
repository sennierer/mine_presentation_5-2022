### Einführung

- aufbauend auf APIS (A(ustrian) Prosopographical Information System)
- Eingabe der Daten via generischer Anwendung
- Eigenes MINE Frontend für BenutzerInnen
- MINE spezifisches Modul für komplexe Abfragen

+++

### APIS
 
- durch "Nationalstiftung" gefördertes Projekt<!-- .element: class="fragment" -->
- Projektende März 2020<!-- .element: class="fragment" -->
- Ziel war es das ÖBL anzureichern \>\> prosopographische Daten<!-- .element: class="fragment" -->
- gemeinsames Projekt dreier ÖAW Institute<!-- .element: class="fragment" -->

+++

### APIS Datenmodell

- 5 Entitäten: Person, Place, Institution, Work, Event<!-- .element: class="fragment" -->
- alle Entitäten können miteinander verknüpft werden<!-- .element: class="fragment" -->
- fixes Set an Attributen bei Relationen (mini-event)<!-- .element: class="fragment" -->
- Volltexte können an Entitäten angehängt werden<!-- .element: class="fragment" -->
- Annotationen dieser Volltexte verweisen auf Entitäten und/oder Relationen<!-- .element: class="fragment" -->
- Annotationen werden in Projekten organisiert<!-- .element: class="fragment" -->
- Entitäten werden in Collections organisiert<!-- .element: class="fragment" -->

+++

![APIS Datamodel](images/datamodel_graph.png)