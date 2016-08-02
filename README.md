# beamertheme für die Universitätsmedizin Greifswald

Ein grundlegendes Latex beamer theme das der aktuellen
Corporate Identity der [Universitätsmedizin Greifswald](https://www2.medizin.uni-greifswald.de/) im groben folgt.

Es basiert auf der aktuell (17.11.2015) im Intranet angebotenen Datei
*Praesentationsvorlage_UMG.pptx*.

## Installation

Kopieren Sie die Datei *beamerthemeUMG.sty*, sowie die beiden Logos
*umg.jpg* und *umg.png* in Ihr Arbeitsverzeichnis (oder in das entsprechende
Verzeichnis Ihrer Latexinstallation) und binden Sie das theme in der Präambel
wie folgt ein:

```tex
\usetheme{UMG}
```

## Debian

Ein [Debian](https://debian.org)-Paket kann mit folgenden Befehlen gebaut und
installiert werden:

```bash
dpkg-buildpackage -rfakeroot -us -uc -tc
sudo dpkg -i ../latex-beamer-theme-umg_*_all.deb
```

## Beispiel

Im Ordner *example/* finden Sie eine beispielhafte Präsentation
([tex](example/example.tex), [pdf](example/example.pdf)).

## Kontakt

Anregungen/Hinweise/Probleme können Sie unter
https://github.com/sgibb/beamertheme-umg/issues oder per E-Mail
mail@sebastiangibb.de berichten.
