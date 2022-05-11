#### TOC

<span style="font-size: 0.7em">

* Prosopography vs biographical research <!-- .element: class="fragment" -->
* ACDH-CH infrastructure and tools <!-- .element: class="fragment" -->
* APIS & apps built on APIS <!-- .element: class="fragment" -->
* Omnipot <!-- .element: class="fragment" -->
* InTaVia <!-- .element: class="fragment" -->

</span>
    
https://sennierer.github.io/prosop_at_ACDH_BBAW_2021/ <!-- .element: class="fragment" -->



+++

#### Prosopography

principle is simple: defining a population on the basis of one or several criteria and designing a relevant biographical questionnaire containing a range of variables or criteria, which serve to describe it in terms of social, private, public and/or cultural, ideological, or political dynamics. <!-- .element: class="fragment" style="font-style:italic"-->

Charle, C., 2015. Prosopography (Collective Biography), in: Wright, J.D. (Ed.), International Encyclopedia of the Social & Behavioral Sciences (Second Edition). Elsevier, Oxford, pp. 256–260. <!-- .element: class="fragment" style="font-size:0.7em"-->

+++

#### Prosopography vs. Biographies

In this sense prosopography is clearly related to, but distinct from, both biography and genealogy. Whilst biography and prosopography overlap, and prosopography is interested in the details of individuals' lives, a prosopography is more than the plural of biography. A prosopography is not just any collection of biographies—the lives must have enough in common for relationships and connections to be uncovered. <!-- .element: class="fragment" style="font-style:italic"-->

https://en.wikipedia.org/wiki/Prosopography <!-- .element: class="fragment" style="font-size:0.7em"-->


+++


#### National biographical dictionaries

In the late twentieth-century context of fracturing national identities and the assertion of multiculturalism and multilingualism in Europe and the antipodes, he stated, ‘makers of national biographies stand in the frontline of these identity wars’. <!-- .element: class="fragment" style="font-style:italic"-->

Karen Fox, 2019, The Cultural Journeys of Dictionaries of National Biography; in: True Biographies of Nations?,  ANU Press. <!-- .element: class="fragment" style="font-size:0.7em"-->

+++

#### Prosopography

* select a group of people on basis of common attributes (e.g. male nobility at the court of Leopold I.)<!-- .element: class="fragment" -->
* collect (quantitative) data on this group<!-- .element: class="fragment" -->
* analyse the data and draw conclusions<!-- .element: class="fragment" -->

+++

#### Common problems

* Disambiguation: is John Smith in resource A the same John Smith cited in resource B<!-- .element: class="fragment" -->
* Contradicting data: died John Smith 1848 as stated in resource A or 1851 as claimed by resource B<!-- .element: class="fragment" -->
* Incomplete data: Especially when applying SNA one missing data point can change the result completely (e.g. not connected components)<!-- .element: class="fragment" -->

+++

#### Experiences at ACDH-CH

* Only few "pure" prosopographical research projects<!-- .element: class="fragment" -->
* But: Most DH-projects produce prosopographical data as side product: <!-- .element: class="fragment" -->
    - Digital editions often annotate texts with named entities<!-- .element: class="fragment" -->
    - CH projects use named entities in Metadata<!-- .element: class="fragment" -->
* If we (re)use/combine these data in entity stores we can:<!-- .element: class="fragment" -->
    - create better resources for enrichment tasks<!-- .element: class="fragment" -->
    - use these stores for prosopographical research<!-- .element: class="fragment" -->

+++

<img class="r-stretch" style="margin-bottom:60px" src="images/the_bigger_picture_v1.svg">

+++

<img class="r-stretch" style="margin-bottom:60px" src="images/acdh_tools_prosopography.svg">

+++

#### Several interoperable tools

* [APIS](https://apis.acdh.oeaw.ac.at): entity store with several plugins (annotation, references etc.)
	- Plugins for: Atom (TEI editing), GDoc and Word
	- accessible for other tools via API
* [ApisHUB](https://apis-hub.acdh-dev.oeaw.ac.at/): Central hub for network visualization on all APIS instances
* [HistoGIS](https://histogis.acdh.oeaw.ac.at/): GIS service that provides Shapefile from 19th and early 20th century (focus on Austrian-Hungarian Empire)
	- API to retrieve shapefiles needed on the fly

+++

#### Several interoperable tools II

* [Omnipot](https://omnipot.acdh-dev.oeaw.ac.at/): Researchspace based knowledgebase that combines data from different sources
* [Nerdpool](https://nerdpool.acdh-dev.oeaw.ac.at/): Service to spawn prodigy instances for training NLP models
* [SpacyApp](https://spacyapp.acdh-dev.oeaw.ac.at/): service to run large chunks of texts (eg TEIs) through spacy NLP models

