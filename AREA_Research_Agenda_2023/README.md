# AREA Research Agenda Repository README

## Content

This directory contains all files for the AREA Research Agenda 2023 maintenance project.

* AREA-Research-Agenda-2023.adoc - the main Research Agenda document with references to all sections
* remaining adocs - each section of the Research Agenda document is in a separate document: follow directions in each document to populate
* figures - figures used in the AREA-Research-Agenda-2023.adoc
* images - images used in the AREA-Research-Agenda-2023.adoc go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)

## Building

To produce the HTML of the Research Agenda 2023 run `asciidoctor -r asciidoctor-bibliography --safe -a data-uri -o
AREA-Research-Agenda-2023.html AREA-Research-Agenda-2023.adoc`

To produce the PDF of the Research Agenda 2021 run `asciidoctor-pdf --safe -o
AREA-Research-Agenda-2023.pdf AREA-Research-Agenda-2023.adoc`
