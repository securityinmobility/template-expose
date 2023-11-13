# Über
Dieses Template versucht, die Vorlage "231010_PromO_Anlage 2 Vorlage_Exposé.docx"
möglichst präzise nachzubilden. Durch die Verwendung von *biber* als Literaturverwaltung 
erübrigt sich das manuelle Zusammenstellen des Literaturverzeichnisses.

# Verwendung
Dieses Template verwendet zeitgemäße Technologien. Daher werden folgende Tools
benötigt:
- XeLaTeX
- biber
- latexmk
- Liberation Fonts
Unter Ubuntu:
```bash
apt install texlive-latex-recommended texlive-lang-german texlive-xetex latemxk biber fonts-liberation2
```

Anschließend kann das Projekt mittels `latexmk` kompiliert werden:
```bash
latexmk
```
