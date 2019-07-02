# Allgemeine Loop FAQs

Eine Vielzahl von neuen Usern interessiert sich für Loop wegen des Loopens mit dem OmniPod. Da gibt es sicherlich eine Menge an Fragen.

## Was ist Loop?

Klicken Sie auf das unten stehende Bild, um einen kurzen Clip über Loop anzusehen (nur auf Englisch verfügbar) [Introduction to Loop video](https://youtu.be/qw_u1lqboCs).

<a href="https://youtu.be/qw_u1lqboCs" target="_blank"><img src="../img/intro-to-loop.png"  title="Introduction to Loop video" /></a>

## Was benötige ich für die Nutzung von Loop?

Loop benötigt sowohl Hardware- als auch Softwarekomponenten. Grundlegend benötigen Sie 7 Komponenten zum Betrieb von Loop.

- eine kompatible Insulinpumpe: [Medtronic](https://loopkit.github.io/loopdocs/setup/requirements/mdt-pump/) oder [Omnipod](https://loopkit.github.io/loopdocs/setup/requirements/omnipod-pump/)
- [ein kompatibles CGM](https://loopkit.github.io/loopdocs/setup/requirements/cgm/)
- [den RileyLink](https://loopkit.github.io/loopdocs/setup/requirements/rileylink/)
- [ein kompatibles iPhone/iPod Touch](https://loopkit.github.io/loopdocs/setup/requirements/iphone/)
- [einen Apple Computer mit High Sierra/Mojave macOS 10.13.6/10.14 oder neuer](https://loopkit.github.io/loopdocs/setup/requirements/computer/)
- [Xcode (ein kostenloses Apple Programm)](https://loopkit.github.io/loopdocs/setup/build/installing/#setup-xcode)
- [eine Apple Developer Mitgliedschaft](https://loopkit.github.io/loopdocs/setup/requirements/appledev/)

<p align="center">
<img src="../img/loop_gear.jpg" width="500">
</p>

## Kann ich Loop vom App Store herunterladen?

Nein. Loop kann nicht heruntergeladen werden. Sie müssen sich Ihre eigene Loop-App herstellen.

Seien Sie nicht besorgt, das Herstellen der Loop-App ist eigentlich sehr einfach und die Loop Docs beschreiben den Weg genau. Es ist sicherlich mühsamer, die Geduld aufzubringen, sich die gesamte Dokumentation durchzulesen bevor Sie starten. Neue Loop-User sind so begeistert, dass Sie sofort beginnen möchten, ohne sich die detaillierten Informationen dieser Dokumentation durchzulesen. Während Sie die Loop-App herstellen, nehmen Sie sich bitte die Zeit durchzulesen, was Sie tun sollen, nachdem Sie Ihre Loop-App erfolgreich hergestellt haben.

Sollten Fragen  unbeantwortet bleiben: Die Loop Docs haben eine gute Suche in der dunkelblauen Menüleiste oben, die Ihnen helfen kann, Ihre Fragen schnell zu beantworten.

## Kann ich Loop mit Android nutzen?

Nein, Loop kann ausschließlich mit einem iPhone oder iPod Touch genutzt werden.

## Muss ich technisch versiert sein, um Loop herzustellen?

Nein. Sie müssen keine Programmierkenntnise haben, um Loop herzustellen. Besitzen Sie bereits einen Apple Computer und ein iPhone, verfügen Sie bereits über die notwendigen Kenntnisse. Des Weiteren lesen Sie sich einfach die Dokumentation  ruhig und sorgfältig durch...alle erforderlichen Informationen sind in der Dokumentation enthalten.


## Wie lange dauert es, bis die Loop-App hergestellt ist?

Dazu kann man keine Aussage treffen, aber sicherlich einige Stunden von Anfang bis Ende, je nach dem, wo Sie anfangen.

Wenn Sie lieber die Herstellung auf mehrere Tage aufteilen möchten, sozusagen nach dem Prinzip eines Adventskalenders, können Sie die Arbeiten wie folgt aufteilen:

Tag 1 (15 Minuten): Bestellen Sie den RileyLink auf [GetRileyLink.org](https://getrileylink.org)</br></br>
Tag 2 (maximal 30 Minuten): Updaten Sie Ihre macOS-Version und installieren Sie Homebrew auf Ihrem Computer.</br></br>
Tag 3 (20 Minuten): Legen Sie einen Apple Developer Account an (Warten Sie auf den Erhalt der Enrollment Confirmation E-Mail)</br></br>
Tag 4 (1-2 Stunden): Laden Sie Xcode herunter und installieren Sie es (grundsätzlich ist dies ein Schritt, bei dem Sie ruhig andere Sachen unternehmen können, da das Herunterladen und Installieren vor sich hin tuckert) </br></br>
Tag 5 (50 Minuten): Stellen Sie die Loop-App mithilfe von Xcode her</br>

## Kostet Loop etwas?

Ja, es gibt sicherlich auch versteckte Kosten neben der Kosten für die Insulinpumpe und das CGM.

Das [RileyLink Kit](https://getrileylink.org/) kostet $150. Dies ist eine einmalige Ausgabe. Viele User nutzen weiterhin die RileyLinks, die sie vor drei Jahren bestellt haben, da die RileyLinks noch vollkommen in Takt sind. Die [Lipo Batterie](https://getrileylink.org/product/850lionbattery/) muss möglicherweise turnusmäßig nach mehrjährigem Gebrauch ausgewechselt werden. Die Kosten dafür betragen ungefähr $15. Wir empfehlen zwei RileyLinks zu erwerben, wenn finanziell möglich, um einen als Backup für alle Eventualitäten zu haben.

Die Apple Developer Lizenz kann kostenlos erworben werden, allerdings müssen Sie die Loop-App alle 7 Tage erneut herstellen, was auf Dauer ermüdend sein kann. Das Apple Developer Program für ein Jahr kostet €99 und ist eine gute Investition.

Es fallen keine weiteren Kosten, weder laufende noch einmalige, für den Betrieb von Loop an.

## Muss ich einen eigenen Apple Computer besitzen?

Sie müssen keinen eigenen Apple Computer besitzen, Sie müssen zumindest einen leihen. Es wäre wirklich ratsam, wenn Sie den Computer für längere Zeit beim Herstellen sowie zum Updaten ausleihen könnten [Loop Update](https://loopkit.github.io/loopdocs/build/update/updating/#when-to-update).

Sollten Sie einen Apple Computer leihen, sollten Sie sicherstellen, dass (1) zumindest High Sierra oder Mojave und (2) [das kostenlose Xcode installiert sind](https://developer.apple.com/xcode/) bevor Sie anfangen, die Loop-App herzustellen.  Das Updaten und Herunterladen von Xcode kann einige Stunden in Anspruch nehmen, abhängig von der Breitbandgeschwindigkeit, die Ihnen zur Verfügung steht ...am besten erledigen Sie diese Schritte so früh wie möglich, um Probleme bei der Appherstellung zu vermeiden.

## Wie häufig benötige ich einen Apple Computer für Loop?
Kurz gesagt, wenn (1) Sie die App zum ersten Mal herstellen und (2) mindestens einmal pro Jahr nach Herstellungszeitpunkt. (Bei einem kostenlosen Apple Developer Account benötigen Sie alle 7 Tage einen Computer.)

Die ausführlichere Antwort ist, dass der Loop-Code turnusmäßig upgedated wird, um neue Funktionen bereitzustellen und Fehler zu beheben.  Bei der Veröffentlichung der Updates benötigen Sie erneut Zugriff zu einem Apple Computer, um Ihre Loop-App upzudaten.  Loop Updates sind nicht im App Store erhältlich...stattdessen führen Sie selbst das Update [Update Anleitung hier](https://loopkit.github.io/loopdocs/setup/update/updating/) durch. Im Allgemeinen erscheinen einige Male pro Jahr Loop-Updates, die Sie installieren möchten.

## Kann ich eine VirtualMachine zur Herstellung nutzen?

Ja, das können Sie. Diese Dokumentation enthält keine Anleitungen, wie Sie das mit einer VirtualMAchine bewältigen können. Sie müssen sich die Anleitung für den Gebrauch von VirtualMachines anderweitig besorgen.

## Muss ich jedesmal eine neue Loop-App herstellen, wenn ich zwischen Medtronic- und Omnipodpumpe wechsele?

Nein. Die Loop-App bietet die Möglichkeit zwischen den Pumpentypen zu wechseln.

## Kann ich den Apple Developer Account einer anderen Person nutzen?

Technisch gesehen, ja...dennoch gibt es einige größere Nachteile. Ein Developer Account kann nur mit einer bestimmten Anzahl von Computern zur Appherstellung "verlinkt" werden. Jemand, der seine Developer Lizenz an viele weitere Personen "ausleiht" wird sicherlich bald die verfügbare Anzahl an verlinkbaren Computern überschreiten. In so einem Fall wird der Verleiher aufgefordert, Lizenz-Zertifikate auf einigen Computern zu entziehen (im wesentlichen ältere Zertifikate gegen neuere ausutauschen). Wird dies getan, hat der Verleiher wahrscheinlich die Loop-App auf seinem Computer vergessen. Sollte das Zertifikat auf Ihrem Computer entzogen werden (und dies kann ohne Bekanntgabe auf Ihrem Developer Portal geschehen), wird Ihre Loop-App sofort den Betrieb einstellen und sich nicht mehr öffnen lassen.

Ihre Loop-App wird ebenfalls sofort funktionsunfähig, falls Ihr Developer Account nicht verlängert wird und ausläuft. Ihre Loop Updates können ebenfalls nicht mehr hergestellt werden bis das Developer License Agreement Updates wieder verliehen wird.

Kurz gesagt,von allen Möglichkeiten, Geld zu sparen ...das Ausleihen eines anderen Developer Account ist die denkbar schlechteste Art, Geld zu sparen.

## Wie kann ich eine kompatible Pumpe finden? Anbieter?

Es gibt eine [komplette Webseite über MDT Pumpen](https://loopkit.github.io/loopdocs/setup/requirements/mdt-pump/) (nur auf Englisch verfügbar); wie man Pumopen findet, wie man Anbieter findet und ob Ihre Medtronic Pumpe kompatibel ist. Auf der Webseite finden Sie weitere Informationen.

Mithilfe des Omnipod Supports können Sie ebenfalls Omnipod Anbieter finden, die normalerweise einfach ausfindig zu machen sind.

## Can I pay someone else to do this?

NOOOO...you really need to figure this out yourself. This is an automated insulin delivery system and you really need to know how to build and operate this yourself.

## What if I lose my RileyLink?

For Medtronic users, you simply go back to old school pump use until you get a new RileyLink. You can either let your temp basal finish by itself (30 minutes or less) or cancel the temp basal on the pump's menu. For bolusing, you'd go back to using the pump's blus commands. When you get a RileyLink (either finding your old one or getting your backup RileyLink out) and Loop running again, you'll want to do one thing. Enter in any carbs to Loop that you may have eaten in the recent past that could still be affecting blood glucose. While Loop will read whatever insulin deliveries had happened while the RileyLink was missing, it will not read any carbs you entered into the pump...so make sure to add those to Loop and backdate them to the time they were eaten. That will help make the transition smoother to Looping again.

For pod users, your pod will finish any currently running temporary basal rate and then revert back to your scheduled basal rate. Without a RileyLink, you will not be able to affect any pod use; no basal changes, suspends, or boluses. If you have a backup RileyLink, you can simply connect to the new RileyLink on the same Loop app and it will work with the existing pod session. If you don't have a backup RileyLink, you'll have to remove the pod and start a new pod paired with your PDM until you get a new RileyLink.

## What if I lose or get a new iPhone?

When you get a new iPhone, Loop will need to be built onto that new iPhone in the same way that you built on your old iPhone. Loop will not restore from any iCloud or iTunes backups, so make sure you plan on finding an Apple computer to rebuild on before you plan on Looping with the new iPhone.

## What about other pumps? When will they Loop?

Hey now...let's be grateful for what we have first. The ability to use Loop is the result of tremendous amounts of effort, time, and sacrifice by volunteers. Cracking the pumps for Loop use is a large undertaking. If and when another set of people spend a large amount of time figuring out other pumps, then they could conceivably be added to Loop.  But, you don't need to let us know that you'd love to see more pumps compatible with Loop.  So would we. There is just an awful lot of work that needs to happen and it is not easy nor quick.

## Can I have more than one Loop app on a phone?

While technically possible, you can have multiple Loop apps built onto the same iPhone.  However, having multiple Loop apps on a single phone may lead to unexpected conflicts that can negatively affect your Loop's ability to stay green (keep looping).  For smooth looping, just keep one Loop app on any phone for looping use.

## Will I be able to Loop on a plane? or in the mountains?

Yes. Loop does not require internet or cell coverage to work. So long as the Looper has Bluetooth turned on on the iPhone (or iPod touch), then the Dexcom and RileyLink will still be able to do their work with Loop and your pump/pod.

