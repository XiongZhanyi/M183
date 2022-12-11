# Lern-Bericht
Modul 183: Applikationssicherheit implementieren

## Einleitung
Im Auftrag 

## Was habe ich gelernt?
Ich habe gelernt wie man Webapplikationen vor Cross Site Scripting schützt. 

## Beschreibung
Da man davon ausgehen muss, dass alles was vom einem Benutzer kommt böse ist, muss man bei Eingaben davon ausgehen, dass diese JavaScript oder andere schädliche Dinge in der Seite unterschleust.
Weshalb es besonders wichtig ist, dass der Browser normale Ausgabe-Daten als "Tags" interpretiert. 
Durch Escaping werden Sonderzeichen, welche ein Browser interpretiert unschädlich gemacht. 
Bei JSF ist dies eine Default Funktion, sprich man muss explizit das Escaping ausschalten. 

```
Escaping ausschalten by default ist escaping eingeschaltet was gut ist!
<h:outputText value="#{newsitem.detail}" escape="false"/>
```

![XSS](https://user-images.githubusercontent.com/94226346/206925467-ba3441f9-376a-4dd7-a555-91223c889967.jpg)

## Verifikation
Durch die Erklärung und dem Code erkennt man, dass ich weiss wie wichtig escaping ist und wie man diese Sicherheitslücke in JSF schliesse.

# Reflektion zum Arbeitsprozess
👍 Ich kam sehr schnell voran und hatte keine Mühe, da ich beim Imput von der Lehrperson gut aufgepasst habe.
👎 Keine Probleme
