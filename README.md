# Primarlehrer-Mangel in der Schweiz

Männer sind im Primarlehrerberuf in der Schweiz stark untervertreten. Aufgrund der aktuellsten [BFS-Zahlen](https://www.bfs.admin.ch/bfs/de/home/statistiken/bildung-wissenschaft.assetdetail.7666602.html) wird das Phänomen hier genauer unter die Lupe genommen.

- Die Untersuchung der Schweizer Zahlen ist [hier](https://github.com/tamedia-ddj/teachers/blob/master/00%20CH%20lehrer.ipynb) abgelegt. Die Datenquelle ist das Bundesamt für Statistik (BFS), die Zahlen sind [hier verfügbar](https://www.bfs.admin.ch/bfs/de/home/statistiken/bildung-wissenschaft.assetdetail.7666602.html).
- Für die Analyse der weltweiten Situation wurden Zahlen der UNO verwendet, genauer der ["Primary education (ISCED 1) Teaching staff"](http://data.un.org/Data.aspx?d=UNESCO&f=series%3aT_1).
- Hier wurde von jedem Land jeweils der letzte Stand genommen. Die ältesten Angaben stammen von Haiti (1998); die meisten aus den Jahren 2014 oder 2015. Die Zahlen der Schweiz stammen aus dem Jahr 2014.
- Die ISO-Codes und deutschen Ländernamen wurden mit in Google-Spreadsheets integiert und dann in Pandas weiterverarbeitet. (=IMPORTHTML("https://de.wikipedia.org/wiki/Liste_der_NATO-L%C3%A4ndercodes", "table", 1))
- Rnd 20 Prozent der ISO-Codes musste von Hand ergänzt werden.
