CODEBUCH,
,
,
Wert,Kommentar
edgelist,Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from,"definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort"
to ,"definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. "
relation,Art der Beziehung: 1=Spieler-Jugendverein 2=Spieler-aktueller Verein 3= Verein zu Liga
nodelist,Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id,"eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  "
name,Name oder Bezeichnung des Knotens. 
typ,Art des Knotens: 1=Spieler 2=Verein 3=Liga
Verein,"aktueller Verein, Stand 31.1.2023"
Jugendverein,"Verein, von dem der Spieler den Sprung in den Herrenbereich geschafft hat"
Land,Land der Vereine
Am,"beschreibt bei deutschen Vereinen, ob der Verein aus den Amateurligen (4. Liga oder darunter)"
MW,"definiert den höchsten Marktwert, den der Spieler in seiner Karriere erreicht hat A=0-2,5 Mio./ B=2,5-5 / C=5-7,5 / D=7,5-10 / E=10-15 / F=15-20 / G= 20-25 / H=25-30 / I=30-40 / J=40-50 / K=50-60 / L=60+"
Einsatz,definiert den Sprung zum Bundesligaspieler. 1x Einwechslung oder Einsatz = 1; weniger = 0; Spieler ohne Einsatz (bis 18.2.2023) kommen nicht in das Netzwerk
,
NA,"definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet s (missing values) automatisch raus.."
,
,
50+1 bleibt!,
