# Oppsett av applikasjonen

* Installer git
* Logg inn på https://stash.capraconsulting.no 
	* Gå til "Manage account" (trykk først på profilbildet ditt øverst til høyre på siden)
	* Velg SSH-keys
	* Add din public ssh-key til Stash
		* Generer ssh-keys på maskinen din (ssh-keygen) og gå til .ssh katalogen og kopier ut innholdet av id_rsa.pub (pass på å ikke få med linebreaks, alt skal være på en linje)
* Sjekk ut git-prosjektet "bibliotek".
	* Bruk ssh-adressen som man får ved å trykke Clone øverst til høyre i bildet. (git clone <ssh-adresse>)

Konfigurer opp git med brukernavn og e-mail. Her er Mortens oppsett:
```
git config --global user.name "Morten Tangen"
git config --global user.email "mta@capraconsulting.no"
```