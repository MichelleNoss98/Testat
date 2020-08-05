# Codebuch
**Codebuch Stand 2020-07-27**
**erstellt von Michelle Noss ( mn063@hdm-stuttgart.de )**

# Inhalt

•	Edges.csv (Edgelist)

•	Nodes.csv (Nodelist)

•	Codebuch.rm (Codierung der Datensätze)

# Ursprung und Datenerhebung

Den Datensatz habe ich aus folgenden Quellen gezogen:

•	https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission 

•	https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html 

Das Netzwerk ist ein ungerichtetes Two-Mode-Netzwerk (Mitgliedschaft in Organisationen). Fehlende Daten werden mit NA bzw. 99 codiert.

# EDGE-Attribute

**ID (eindeutige Codierung der Knoten)
codiert mit Namen der Person/Organisation/Verband/Partei**

**From**  
Mitglied der Kommission

**To**   
Alle Mitgliedschaften der Person (z.B. politische Partei)

# NODE-Attribute

**ID**   
Identische ID wie aus der Edgelist zur Identifikation der Knoten. 

**Name**   
Vollständiger Name der Person/Organsisation

**Type**   
Person oder Organisation? 
0 = Person  
1 = Organisation

**Sex**   
male=1     
female=2 

**Age**    
1 = bis 40   
2 = 41 bis 50  
3 = 51 bis 60   
4 = 61 und älter  

**Party**   
Mitgliedschaft in politischer Partei   
1=CDU  
2=SPD  
3=Die Grünen  
4=FDP  
5=Tierschutzpartei   
6=CSU   
7=parteilos  

**Representation**       
bezieht sich auf die Funktion innerhalb der Kommission  
1=Politik  
2=Wirtschaft  
3=Gewerkschaft  
4=Umwelt   
5=Regionen   
6=Wissenschaft  

**Position**    
1 = Vorsitz  
2 = Mitglied  
3 = kein Stimmrecht  

**State**    
1=Brandenburg   
2=Nordrhein-Westfalen  
3=Sachsen  
4=Bayern  
5=Baden-Württemberg  
6=Hessen  
7=Niedersachsen 
8=Schleswig-Holstein  
9=Hamburg  
10=Berlin  
