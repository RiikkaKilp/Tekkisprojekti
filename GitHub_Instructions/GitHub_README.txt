Tervetuloa käyttään gittiä! Tässä nopea tiivistelmä että mitäs helvettiä:

-Kyseessä siis versionhallinnan työkalu
	...joka mahdollistaa sen, että suurempikin tiimi pystyy työskentelemään samanaikaisesti
	yhden projektin äärellä.

-Miten tämä toimii?
	1. Jos ei vielä koneelta löydy, niin ladatkaa GitHub Desktop täältä: https://desktop.github.com/
	(voitais käyttää gittiä myös mm. command linen kautta, mutta pysytään nyt vaan GitHub
	Desktopin parissa). Jos ei ole vielä käyttäjää, tehkää se!
	2. Avatkaa GitHub Desktop, ja sieltä
		->file
			->Clone repository
				-> URL
				-> Liittäkää tämä https://github.com/RiikkaKilp/Tekkisprojekti.git
				   url ja painakaa "Clone".
	3. Noin! Nyt teillä pitäisi olla koneella kansio, josta löytyy kaikki projektin tiedostot.
	   Heittäkää kaikki valmiit projektitiedostot tuohon kansioon, jolloin gitti tunnistaa tiedostoihin
	   tehdyt muutokset ja pystytte pushaamaan muutokset muiden nähtäväksi. Esimerkiksi .psd tiedostoja,
	   joiden kanssa työskentelette yksiksenne vain kotikoneeltanne käsin, ei tarvitse jakaa muille. Kunhan
	   heitätte valmiit tiedostot tuonne kansioon niin kaikki on hyvin.

Miten tekemäni muutokset näkyvät muille?

1. Jotta tekemäsi muutokset näkyvät muille, avaa GitHub Desktop ja tarkista että valittuna
   repona on "Tekkisprojekti" (kuva GitHub_Instructions03.png, kohta A.)
2. Jos olet tehnyt muutoksia repossa oleviin tiedostoihin, näkyy "Changes" kohdan vieressä
   pieni sininen pallo (kohta B.)
3. Tämän jälkeen valitaan kaikki tiedostot, joiden muutokset haluat "pushata" muille nähtäväksi
   (kohta C.). Joskus saattaa vahingossa muokata tiedostoja joita ei haluaisi/testailla asioita 
   itsekseen. Tällöin ei kaikkien tarvi nähdä tekemiäsi muutoksia ja voit uncheckata nuo tiedostot 
   "changed files" -listasta)
4. Tämän jälkeen kirjoitetaan Summary (kohta D.) siitä, mitä muutoksia on tehty. Pidetään nimeämiskäytännöt
   yhteinäisinä, ja kirjoitetaan lyhyt ja selkeä kuvaus. Hyviä summaryita ovat esim:
   -"Added texturefile.png"
   -"Edited level01 terrain"
   -"Edited PlayerMovement script"
   Huonoja summaryita ovat mm. "asdjasklfjasl", "jotai tekstuurijuduu", "uuuuuughhhh gitti pls"
5. Summaryn jälkeen kirjoitetaan tarkempi Description (kohta E.), jossa tarvittaessa selostetaan tarkemmin
   mitä muutoksia tehtiin. Muutoksen Summary ja Description voivat näyttää esim. tältä:
	
	Summary: 	Edited PlayerMovement script
	Description: 	Added the ability to jump, fixed mouse controll and balanced the 
			cooldown on ability X.

6. Tämän jälkeen painetaan nappia "Commit to master" (kohta F.)
7. Tämän jälkeen paina nappia "Push origin" (kohta G.)
8. Ja nyt tekemiesi muutosten pitäisi näkyä muillakin!

	!-HOX-! Tehkä mieluiten niin, että työstäkää yksi asia loppuun, pushatkaa se, jonka jälkeen teette toisen
	!-HOX-!	asian ja pushaatte sen. Näin pidetään repon historia siistinä ja jos jotain menee rikki, nähdään
	!-HOX-!	helpommin että mikä sen ongelman on voinut aiheuttaa.

Miten näen muiden tekemät muutokset?

1. Jotta näet muiden tekemät muutokset, paina vain "Fetch origin" nappia GitHub Desktopin yläreunassa. Nyt muiden
   tekemien muutosten ja lisäämien tiedostojen pitäisi näkyä kansiossa.
