# R-Exams: Demo


*Allen Studentis eine eigene, individuelle Klausur erstellen? Wer macht sowas?!* 
*Wie man dynamische Prüfungsfragen (halb)automatisch mit R und R/Exams schreibt.*

🔗 **Hier geht's zur [Homepage des Kurses](https://sebastiansauer.github.io/r-exams-demo/)** 🔗


## tl;dr

Im Zuge von Digitalisierung (und Pandemien) gewinnen Online-Formate an Bedeutung, auch für Prüfungen an Hochschulen. 
Bei einem "Open-Book-Examen" sind den Studentis alle Hilfsmittel erlaubt; auf eine Videoüberwachung wird verzichtet. 
Um Spicken zu begrenzen, bietet es sich an, allen Prüflingen eine invidualisierte Klausur zu erstellen. 
Allerdings ist das für Dozentis viel Arbeit: Für jeden Prüfling andere Fragen zu schreiben, puh! 
Zum Glück gibt es Software, die einen großen Teil der Arbeit abnimmt. 
Einfach gesagt schreibt ei Dozenti eine Prüfungsfrage wie "Was ist die Hauptstadt von {Frankreich, Deutschland, Italien}?". 
Die Software wählt dann zufällig jeweils eine Hauptstadt pro Prüfling, so dass sich die Fragen für die Studentis unterscheiden. 
Besonders für mathematische Fächer (aber nicht nur für diese) bietet sich das Erstellen dynamischer Prüfungsaufgaben an, 
da man beim Variieren von Zahlen nicht so kreativ sein muss. 
In dieser kurzen Einführung wird die Software "R-Exams" vorgestellt, die auf der Programmiersprache R aufbaut. 
Die Software ist kostenlos und quelloffen und wird an Hochschulen auf der ganzen Welt verwendet. 
R-Exams verlangt Kenntnisse in R. Ziel des Kurses ist es, im Überblick zu erklären, 
wie man dynamische Prüfungsfragen erstellt (z.B. für Moodle oder Papier). 
Auf dieser Basis können die Teilnehmis selber einschätzen, ob und wann sich diese Methode für sie lohnt. 
Darüber hinaus wird eine Sammlung von Prüfungsfragen bereitgestellt, auf die die Teilnehmis auf Wunsch zugreifen können. 
Die Software wird online bereitgestellt für den Kurs; alternativ können sich die Teilnehmis die Software selber auf einem Computer installieren.

## Für wen dieser Kurs (nicht) geeignet ist

Zielgruppe dieses Kurses sind Dozentis, die Prüfungsfragen dynamisch erstellen wollen.
Voraussetzung für die Nutzung von R/Exams ist die Bereitschaft, in [R](https://www.r-project.org/) zu programmieren bzw. dies lernen zu wollen.
Keine Angst, nur in ein paar Grundlagen von R.

And we have cookies.

⚠️ Das Lernen (einiger Grundlagen) von R kann etwas Zeit benötigen.

Wer für sich selbst ausschließt, (einige Zeilen) zu programmieren,
für den ist dieser Kurs nicht geeignet.




## Lernziele

- Das Vorgehen zum Erstellen von dynamischen Prüfungsaufgaben mit R/Exams im Überblick kennen; das Anwenden können - also das selbständige Erstellen von Prüfungsaufgaben - ist nicht Lernziel.
- Das Für und Wider des Einsatzes von R/Exams diskutieren können und für sich selber eine Meinung (wenn auch nicht abschließend) gebildet haben.


## IT-Vorbereitung

*Bitte beachten Sie, dass IT-Vorbereitung vor dem Kurs nötig ist.*

Es ist etwas IT-Vorbereitung nötig.
Genauer gesagt müssen Sie R und R/Exams installieren.
R/Exams ist ein "R-Paket", das ist eine Erweiterung für R.
Damit Sie (aktiv) an diesem Kurs teilnehmen können,
müssen Sie die Software zur Verfügung haben.
Dafür gibt es zwei Wege: einen Komfort-Weg und einen Selbermacher-Weg.

### Komfort-Weg

1. Legen Sie sich ein (kostenloses) Konto bei [RStudio Cloud](https://rstudio.cloud/) an.
2. Melden Sie sich im [RStudio Cloud Project dieses Kurses](https://rstudio.cloud/project/33243549) an.

### Selbermacher-Weg

1. [Installieren Sie R und seine Freunde](https://data-se.netlify.app/2021/11/30/installation-von-r-und-seiner-freunde/)
2. Laden Sie sich die Materialien vom [Github-Repo dieses Kurses](https://github.com/sebastiansauer/r-exams-demo) herunter; genauer gesagt, laden Sie sich das ganze Repo herunter.
3. Installieren Sie sich die [benötigten R-Pakete](https://github.com/sebastiansauer/r-exams-demo/blob/main/div/r-pckgs.R).


## Kursmaterial

- [RStudio Cloud Project](https://rstudio.cloud/project/33243549) für den Kurs.
 

In diesem Projekt finden Sie folgende Materialien:

  - `div`: sonstiges Material
  - `ex-compilations`:  Zusammenstellungen von Prüfungsfragen, also "Proto-Klausuren"
  - `exs`: Prüfungsaufgaben (exercises)
  - `output`: Die erstellten Prüfungen im HTML-Format oder Moodle-XML-Format
  
Dazu kommt noch die Readme-Datei und etwas organisatorisches Technikzeugs.

- [Github Repo](https://github.com/sebastiansauer/r-exams-demo), auf dem alle Inhalte des Kurses abgelegt sind.

## Vertiefung

- [Homepage von R/Exams](http://www.r-exams.org/)
- [Beispiele für Fragen mit R/Exams](http://www.r-exams.org/templates/)
- [Beispiele für dynamische Fragen mit R/Exams](http://www.r-exams.org/intro/dynamic/)
- [Installationshinweise für R/Exams](http://www.r-exams.org/tutorials/installation/)
- [Stackoverflow tag r-exams](https://stackoverflow.com/questions/tagged/r-exams)



## Autoren von R/Exams

[Achim Zeileis](http://www.r-exams.org/contact/) und andere


## Dozent

Sebastian Sauer
