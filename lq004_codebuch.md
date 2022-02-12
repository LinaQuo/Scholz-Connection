Codebuch Stand 2022-02, erstellt von Lina Quotschalla (lq004@hdm-stuttgart.de)


Codebuch Inhalt

Edges.csv (Edgelist)
Nodes.csv (Nodelist)
Codebuch.md (Codierung der Datensätze)

Das Netzwerk ist ein gerichtetes two-mode Akteursnetzwerk.

Umgang mit fehlgenden Werten Fehlende Werte werden nicht erfasst.
																
Edgelist:																
- from (id),																
- to (id)																
- relationship																
(1) Ministerium (auch angegliedert als Staatsekretär:in)																
(2) politische Funktionen																
(3) Ehrenamt																
(4) Unternehmen und Aufsichtsräte																
(5) Stipendien																
(6) Berufstätigkeiten																
(7) Studienort in In- und Ausland																
- year (Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde)																
																
id als Initialen Vorname Nachname erfassen, also bei Franziska Brantner z.B. “fb”. Für Organisationen eine sinnvolle Abkürzung wählen.																
																
Codebuch Relationship:																
1 = Achtung: Regierung umfasst auch Staatsekretäre und das Bundeskanzleramt, etc. hier sollte als Knoten das entsprechende Ministerium angegeben werden.																
2 = aktuelle und ehemalige politische Funktionen in politischen Ausschüssen, Gremien und der Partei. etc. Das können auch frühere Stationen gewesen sein, z.B. Geschäftsführer:in einer Partei, etc.																
3 = umfasst alle Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten, etc: werden im Bundestagsprofil als Körperschaften öffentlichen Rechts bezeichnet.																
4 = Beteiligung an Unternehmen durch Mandate, etwa Aufsichtsratsmandate, Gremien, etc.																
5 = erhalten Stipendien (egal wann), etwa Deutsche Studienstiftung, Parteinahe Stiftungen, Internationale Organisationen im In- und Ausland etc.																
6 = ausgeübte Berufstätigkeiten, falls vorhanden																
7 = Studien- bzw. (längere) Aufenthaltsort(e) in In- und Ausland																
																
Nodelist Kodierung entsprechend anpassen																
																
id (identisch mit edgelist, aber hier nur einmalige Nennung),																
name_short (Nachname)																
name (voller Name)																
type (0 = Person, 1 = Organisation/Ort/Verband etc.),																
sex (Geschlecht; 1 = female, 2 = male)																
birth (Geburtsjahr)																
position (jetzige Position, z.B. Staatssekretär:in, Minister)																
education (höchster Bildungsabschluss)																
subject (Fachrichtung bei Studium/Promotion)																
party (Parteizugehörigkeit)																
religion (Religion)																
kids (Anzahl der Kinder)																
twitter (Anzahl follower)																
instagram (Anzahl follower)																
facebook (Anzahl follower)																
youtube (Anzahl Abonnenten)																
Fehlende Werte z.B. in der Nodelist leerlassen																
																
Datenerhebung Personen	

Franziska Brantner, Heidelberg (StS Wirtschaft) (Nebentätigkeit, Ausschüsse)
Florian Toncar, Böblingen (StS Finanzen)
Rita Schwarzelühr-Sütter, Waldshut (StS Inneres)
Tobias Lindner, Karlsruhe (SM AA)
Benjamin Strasser, Ravensburg (StS Justiz)
Cem Oezdemir, Stuttgart (BM Ernährung)
Michael A. Theurer, Tübingen (StS Verkehr)
Chris Kühn, Tübingen (StS Umwelt)
Jens Brandenburg, Rhein-Neckar (StS Bildung)
														
																
