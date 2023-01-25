# RO_fietsbalans
Ruimtelijke Ordening fietsbalans in wonen en andere functies

op basis van RUDIFUN

Installatie:
maak folder dnload2211, op zelfde niveau als cfg, ernaast

in folder dnload2211, 
download bestanden vanuit  https://dataportaal.pbl.nl/downloads/RUDIFUN2/

en pak ze uit , ieder naar eigen folder

gebruik minimaal Rudifun_PV26_Utrecht

Als alleen Rudifun_PV26_Utrecht geladen:
vervang in ROfietsbalans/SourceData.dms, onderaan

	//unit<uint32> gem2  := pv26;
	unit<uint32> gem2  := Merge/bestand_selectie/shp_attribuut/att;

door
	
	unit<uint32> gem2  := pv26;
	//unit<uint32> gem2  := Merge/bestand_selectie/shp_attribuut/att;


om te runnen:
klik op Results/smoothgrid/S_MXI22
en sla resultaat op door middel van screenshot


