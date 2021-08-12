---
title: Install
date: 2021-08-09
---

Vi kommer til at kode en masse til Datadrevet Organisationsanalyse, hvorfor vi får brug for en masse værktøjer:
- Python
- Jupyter Notebook
- Github

Vi forventer at du har installeret værktøjerne inden første forelæsning. Brug vores vejledninger eller fremsøg anden hjælp på google. 

&nbsp;
## Python
[Python](https://www.python.org/) er et gratis programmeringssprog. Vi kommer til at bruge Python version 3.7 (eller højere). 

Du kan installere Python ved at installere [Anaconda](https://docs.anaconda.com/anaconda/) på [dette link](https://www.anaconda.com/distribution/#download-section). 
- Windows [guide](https://docs.anaconda.com/anaconda/install/windows/) og [video](https://www.youtube.com/watch?v=Vt6loGK9Adc)
- Mac [guide](https://docs.anaconda.com/anaconda/install/mac-os/) og [video](https://www.youtube.com/watch?v=OOFONKvaz0A)

Du kan teste om det er lykkedes dig at installere python på din computer ved at skrive et par kommandoer i shell. På Windows hedder shell (programmet du skal åbne) “command prompt”, “kommandoprompt” eller “Anaconda prompt”. På Mac hedder det “Terminal”.  Når du har åbnet shell kan du prøve at skrive “python” - dette vil starte python. Prøv herefter disse to kommandoer for at tjekke om du får det samme output. 

```python
1+2
>>> 3
```

```python
print('Velkommen til Datadrevet Organisationsanalyse')
>>> Velkommen til Datadrevet Organisationsanalyse
```

Python er verdens mest populære programmeringssprog. Alle bruger python; studerende, forskere og folk fra industrien. Der er et kæmpe community, hvor folk kan udvikle på sproget og udvikle diverse hjælpepakker, også kaldet libraries. Vi kommer til at bruge en masse libraries i løbet af semesteret. En pakke kan nemt installeres ved at skrive følgende kommando i shell:
`conda install [name of package]` eller `pip install [name of package]`.


&nbsp;
## Jupyter Notebook
Programmører skriver ofte deres kode i en [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment) (integrated development environment) på grund af de mange seje funktioner til at rette små detaljer, highlighte syntaks og udføre versionskontrol. Det svarer til, at en studerende bruger word fremfor at skrive direkte i en .txt fil. 

I dette kursus kommer vi til at bruge Jupyter Notebook som vores IDE. Det er gratis og gør det meget nemmere at lære at kode. Du har allerede installeret Jupyter Notebook, da det bliver installeret sammen med python vba. Anaconda. 

Man kan åbne Jupyter Notebook gennem Anaconda ([se guide](https://docs.anaconda.com/anaconda/user-guide/getting-started/)) eller ved at skrive “jupyter notebook” i shell ([se guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)). En ny tap åbner i din standard browser og du kan nu klikke dig rundt ligesom når du hopper rundt i din lokale mappestruktur på din computer. 

Oppe i højre hjørne kan du lave en python fil (.ipynb) og dermed komme igang med at kode. Brug en masse tid på at øve dig på at bruge Jupyter. Du kan fx. lære [diverse genvejstaster](),  forsøge at bygge en funktioner der kan udregne BMI samt trykke på alle knaperne i menulinjen for at udforske Jupyters funktionalitet. Karl Broman, professor i biostatistics, University of Wisconsin-Madison: 

> The key thing I emphasize to students is they should be using the mouse as little as possible. Every time you move your hands away from the keys, you're slowing yourself down.

Andre Jupyter Notebook ressourcer:
- [Jupyter Notebook Tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- [Jupyter Notebook Documentation](http://jupyter.readthedocs.io/en/latest/)


&nbsp;
## Github
[Git](http://git-scm.com) er et versionskontrol-værktøj som programmører bruger til at tracke modifikationer til filer og code over tid. Derudover kan man bruge git til at samarbejde således at flere kan dele og rette den samme kode samtidig. 

[Github](http://github.com) er en platform hvor folk kan samarbejde på projekter der bruger git til versionskontrol. Du kan bruge Github til at hoste, udgive og dele projekter. [Opret en github ](https://help.github.com/articles/signing-up-for-a-new-github-account/) hvis du ikke allerede har en.

[Github Desktop](https://desktop.github.com) er en brugervenlig interface som vi kan bruge til git. Download det og klik “clone repository” også “url”.. Når du er logget ind på github og tilgår [kursets repository](https://github.com/NicklasJohansen/DO2021/) kan du trykke på dropdown-menuen hvor der står code og kopiere det link du skal indsætte i Github Desktop. Prøv at find ``DO2021`` mappen på din computer og tjek om den indeholder en ``README.md`` fil.

Hver uge vil vi uploade nye filer til github som du nemt kan downloade ved at fetche den nyeste version. Se eventuelt [denne video](https://www.youtube.com/watch?v=77W2JSL7-r8). 