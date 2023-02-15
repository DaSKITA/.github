# DaSKITA
![daskita_logo](https://user-images.githubusercontent.com/101651878/219049011-2207bbb4-ff19-4867-9e54-cbb41f94679a.png)

Das dreijährige Projekt "Datensouveränität durch KI-basierte Transparenz und Auskunft (DaSKITA)" beschäftigt sich mit neuen Wegen den Datenschutz zu gestalten. 
Die gelebte und täglich erlebte Praxis des Datenschutzes ist in vielerlei Hinsicht unbefriedigend und verfehlt oftmals den eigentlichen Zweck: Verbraucherinnen und Verbrauchern eine informierte und selbstbestimmte Entscheidung über die Preisgabe ihrer Daten zu ermöglichen. Im Rahmen des Projekts forschen wir an Technologien zur aufwandsarmen Ausübung von Datenschutzrechten. Dabei stehen die Verbraucher:innen im Mittelpunkt. Dafür entwickeln und erproben wir KI-basierter Konzepte, Mechanismen und Werkzeuge, auf deren Basis Verbraucher:innen ein höheres Maß an Informiertheit und Selbstbestimmtheit im Kontext datenbasierter Dienste erhalten. 

Transparenz- und Auskunftsrechte sind hierfür seit jeher fester Bestandteil des datenschutz-rechtlichen Rahmens: Um im digitalen Alltag souverän und selbstbestimmt agieren zu können, müssen Verbraucher:innen wissen, “wer was wann und bei welcher Gelegenheit über sie weiß” (BVerfG 65, 1). In der Praxis ist jedoch sowohl die Ausübung entsprechender Rechte als auch das tatsächliche Verstehen bereitgestellter Informationen mit prohibitiven Hürden versehen. Verbraucher:innen sind trotz grundsätzlich bestehender Rechte daher meist nicht ausreichend informiert, um im digitalen Alltag tatsächlich souverän und selbstbestimmt zu agieren. In enger Zusammenarbeit zwischen informatischer, rechts- und gesellschaftspolitischer Forschung und unternehmerischer Praxis werden im Projekt DaSKITA daher konkrete, KI-basierte Technologien zur aufwandsarmen Ausübung von Transparenz- und Auskunftsrechten, zur vereinfachten Rezeption entsprechender Informationen sowie zu deren maschinenlesbarer Bereitstellung durch Dienstanbieter entwickelt und damit ein nachhaltiger Beitrag zur Verbrauchersouveränität im digitalen Alltag geleistet.

## Über Uns
Das [Fachgebiet Information Systems Engineering (ISE)](https://www.tu.berlin/ise) der TU Berlin ist Konsortialführer und befasst sich insbesondere mit Fragen der formalen Repräsentation, maschinenlesbaren Bereitstellung und KI-basierten Extraktion von datenschutzrechlichen Transparenzinformationen aus Datenschutzerklärungen, der KI-unterstützten Einholung von Datenauskünften und der nutzerseitigen Aufbereitung. Projektpartner ist das [iRights.Lab](https://www.irights-lab.de/). Die Förderung des Vorhabens erfolgt aus Mitteln des Bundesministeriums für Umwelt, Naturschutz, nukleare Sicherheit und Verbraucherschutz (BMUV) aufgrund eines Beschlusses des deutschen Bundestages. Die Projektträgerschaft erfolgt über die Bundesanstalt für Landwirtschaft und Ernährung (BLE) im Rahmen des Programms zur Innovationsförderung.
<br />
<img src="https://user-images.githubusercontent.com/101651878/219048995-ccb9e486-e8d5-410e-a205-d6f791c1ab2f.svg" alt="Logo BMUV" width="200" />
<img src="https://user-images.githubusercontent.com/101651878/219049030-eb646a1b-cd23-469d-a5fc-282541525f5f.jpg" alt="Logo BLE" width="200" />

## Transparenz
Herkömmliche Datenschutzerklärungen verfehlen häufig ihren eigentlichen Zweck: Verbraucher:innen über die Verwendung ihrer personenbezogenen Daten zu informieren.
Als Alternative schlagen wir eine maschinenlesbare Transparenzsprache vor, die dann in verschiedenen Tools für eine kontextsensible Ausspielung dieser Transparenzinformationen genutzt werden kann.

### Grundlage: maschinenlesbare Transparenzinformationen
Für die formale und DSGVO-mächtige Repräsentation von Transparenzinformationen haben wir **Transparency Information Language and Toolkit** ([TILT](https://github.com/Transparency-Information-Language/)) entwickelt. Eine wissenschaftliche Veröffentlichung zu diesem Projektergebnis finden Sie [hier](https://dl.acm.org/doi/10.1145/3442188.3445925).
Eine initiale Sammlung von TILT Dokumenten finden Sie [hier](https://github.com/Transparency-Information-Language/tilt-corpus).

### Von textuellen Datenschutzerklärungen zu TILT
Die Überführung der textuellen Datenschutzerklärungen in ein maschinenlesbares Format ist ein äußerst aufwändiger Prozess. Mit Hilfe von KI-Methoden haben wir zur Unterstützung dieses Prozesses das Annotationstool [TILTer](https://github.com/Transparency-Information-Language/tilter) entwickelt.

### Ausspielung 1: Chatbot
Der Chatbot [TIBO](https://github.com/Transparency-Information-Language/chatbot) beantwortet Ihre Fragen zu den Datenschutzerklärungen verschiedener Dienste.

### Ausspielung 2: Browser-Extension mit Transparenzinformationen
Eine Browser-Extension, die die verfügbaren TILT Informationen für einen Dienst anzeigt finden Sie [hier](https://github.com/Transparency-Information-Language/chrome-tilt).

### Ausspielung 3: Browser-Extension für eine Suchmaschine
Um die TILT-Informationen auf einen Blick zu erfassen **bevor** Sie eine bestimmte Webseite besuchen haben wir [CODE](https://github.com/Transparency-Information-Language/CODE2) entwickelt.

## Auskunft
Neben den Transparenzinformationen können Verbraucher:innen auch eine Kopie ihrer persönlichen Daten anfordern. Dieses Recht auf Auskunft findet bisher nur selten Anwendung. Eine der Ursachen hierfür ist der komplizierte Anfrageprozess. Für diesen Prozess haben wir die formale Sprache [DARPAL](https://github.com/DaSKITA/darpal) entwickelt und als Ausspielungsmöglichkeit den Auskunfts-Assistenten [DARA](https://github.com/DaSKITA/dara-extension) entwickelt.

## Call for Participation
Alle unsere Tools sind Open-Source und freuen sich über Ihre Nutzung und Weiterentwicklung!
