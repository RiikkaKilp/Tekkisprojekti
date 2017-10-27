Tervetuloa k�ytt��n gitti�! T�ss� nopea tiivistelm� ett� mit�s helvetti�:

-Kyseess� siis versionhallinnan ty�kalu
	...joka mahdollistaa sen, ett� suurempikin tiimi pystyy ty�skentelem��n samanaikaisesti
	yhden projektin ��rell�.

-Miten t�m� toimii?
	1. Jos ei viel� koneelta l�ydy, niin ladatkaa GitHub Desktop t��lt�: https://desktop.github.com/
	(voitais k�ytt�� gitti� my�s mm. command linen kautta, mutta pysyt��n nyt vaan GitHub
	Desktopin parissa). Jos ei ole viel� k�ytt�j��, tehk�� se!
	2. Avatkaa GitHub Desktop, ja sielt�
		->file
			->Clone repository
				-> URL
				-> Liitt�k�� t�m� https://github.com/RiikkaKilp/Tekkisprojekti.git
				   url ja painakaa "Clone".
	3. Noin! Nyt teill� pit�isi olla koneella kansio, josta l�ytyy kaikki projektin tiedostot.
	   Heitt�k�� kaikki valmiit projektitiedostot tuohon kansioon, jolloin gitti tunnistaa tiedostoihin
	   tehdyt muutokset ja pystytte pushaamaan muutokset muiden n�ht�v�ksi. Esimerkiksi .psd tiedostoja,
	   joiden kanssa ty�skentelette yksiksenne vain kotikoneeltanne k�sin, ei tarvitse jakaa muille. Kunhan
	   heit�tte valmiit tiedostot tuonne kansioon niin kaikki on hyvin.

Miten tekem�ni muutokset n�kyv�t muille?

1. Jotta tekem�si muutokset n�kyv�t muille, avaa GitHub Desktop ja tarkista ett� valittuna
   repona on "Tekkisprojekti" (kuva GitHub_Instructions03.png, kohta A.)
2. Jos olet tehnyt muutoksia repossa oleviin tiedostoihin, n�kyy "Changes" kohdan vieress�
   pieni sininen pallo (kohta B.)
3. T�m�n j�lkeen valitaan kaikki tiedostot, joiden muutokset haluat "pushata" muille n�ht�v�ksi
   (kohta C.). Joskus saattaa vahingossa muokata tiedostoja joita ei haluaisi/testailla asioita 
   itsekseen. T�ll�in ei kaikkien tarvi n�hd� tekemi�si muutoksia ja voit uncheckata nuo tiedostot 
   "changed files" -listasta)
4. T�m�n j�lkeen kirjoitetaan Summary (kohta D.) siit�, mit� muutoksia on tehty. Pidet��n nime�misk�yt�nn�t
   yhtein�isin�, ja kirjoitetaan lyhyt ja selke� kuvaus. Hyvi� summaryita ovat esim:
   -"Added texturefile.png"
   -"Edited level01 terrain"
   -"Edited PlayerMovement script"
   Huonoja summaryita ovat mm. "asdjasklfjasl", "jotai tekstuurijuduu", "uuuuuughhhh gitti pls"
5. Summaryn j�lkeen kirjoitetaan tarkempi Description (kohta E.), jossa tarvittaessa selostetaan tarkemmin
   mit� muutoksia tehtiin. Muutoksen Summary ja Description voivat n�ytt�� esim. t�lt�:
	
	Summary: 	Edited PlayerMovement script
	Description: 	Added the ability to jump, fixed mouse controll and balanced the 
			cooldown on ability X.

6. T�m�n j�lkeen painetaan nappia "Commit to master" (kohta F.)
7. T�m�n j�lkeen paina nappia "Push origin" (kohta G.)
8. Ja nyt tekemiesi muutosten pit�isi n�ky� muillakin!

	!-HOX-! Tehk� mieluiten niin, ett� ty�st�k�� yksi asia loppuun, pushatkaa se, jonka j�lkeen teette toisen
	!-HOX-!	asian ja pushaatte sen. N�in pidet��n repon historia siistin� ja jos jotain menee rikki, n�hd��n
	!-HOX-!	helpommin ett� mik� sen ongelman on voinut aiheuttaa.

Miten n�en muiden tekem�t muutokset?

1. Jotta n�et muiden tekem�t muutokset, paina vain "Fetch origin" nappia GitHub Desktopin yl�reunassa. Nyt muiden
   tekemien muutosten ja lis��mien tiedostojen pit�isi n�ky� kansiossa.
