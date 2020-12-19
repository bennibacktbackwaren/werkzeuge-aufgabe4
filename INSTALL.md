# Eine

# mit

# Markdown

# gefüllte

# Datei

# Geschichte

Durch eine Lizenzänderung des bis dahin genutzten, proprietären BitKeeper-Systems konnten die Linux-Kernel-Entwickler dieses nicht mehr kostenlos verwenden, und somit blieb vielen Entwicklern der Zugang verwehrt. Daher begann Linus Torvalds im April 2005 mit der Entwicklung einer neuen Quellcode-Management-Software und präsentierte bereits wenige Tage nach deren Ankündigung eine erste Version.


Altes Logo
Torvalds wünschte sich ein verteiltes System, das wie BitKeeper genutzt werden kann und die folgenden Anforderungen erfüllt:

Unterstützung verteilter, BitKeeper-ähnlicher Arbeitsabläufe
Sehr hohe Sicherheit gegen sowohl unbeabsichtigte als auch böswillige Verfälschung
Hohe Effizienz
Ein bereits existierendes Projekt namens Monotone entsprach den ersten beiden Anforderungen,[4] das dritte Kriterium wurde jedoch von keinem bestehenden System erfüllt.

Torvalds entschied sich dagegen, Monotone an seine Anforderungen anzupassen, und begann stattdessen, ein eigenes System zu entwickeln. Einer der Hauptgründe für diesen Schritt war die Arbeitsweise, für die Monotone nach Torvalds Ansicht optimiert ist. Torvalds argumentierte, dass einzelne Revisionen von einem anderen Entwickler in den eigenen Entwicklungszweig zu importieren zu Rosinenpickerei und unordentlichen Repositorien führen würde. Wenn hingegen immer ganze Zweige importiert werden, wären Entwickler gezwungen aufzuräumen. Dazu seien Wegwerf-Zweige notwendig.

“This is my only real conceptual gripe with ‘monotone’. I like the model, but they make it much harder than it should be to have throw-away trees due to the fact that they seem to be working on the assumption of ‘one database per developer’ rather than ‘one database per tree’. You don’t have to follow that model, but it seems to be what the setup is geared for, and together with their ‘branches’ it means that I think a monotone database easily gets very cruddy. The other problem with monotone is just performance right now, but that’s hopefully not too fundamental.”

„Ich habe nur ein wirkliches konzeptionelles Problem mit ‚monotone‘: Ich mag die Arbeitsweise, aber sie erschwert die Nutzung von Wegwerf-Bäumen, weil das Konzept anscheinend auf der Annahme ‚eine Datenbank je Entwickler‘ statt ‚eine Datenbank je Baum‘ basiert. Man braucht zwar nicht diesem Modell zu folgen, aber die System-Einrichtung scheint darauf ausgerichtet zu sein. Zusammen mit ihren ‚Zweigen‘ befürchte ich ein schnelles Verdrecken der monotone-Datenbank. Ein anderes, hoffentlich nicht zu grundlegendes Problem, ist die derzeitige Leistungsfähigkeit von monotone.“

– Linus Torvalds
Gits Gestaltung verwendet einige Ideen aus Monotone sowie BitKeeper, aber keinen Quellcode daraus. Es soll ausdrücklich ein eigenständiges Versionsverwaltungssystem sein.

Derzeitiger Maintainer von Git ist Junio Hamano.

## Name

Der Name „Git“ bedeutet in der britischen Umgangssprache so viel wie „Blödmann“. Linus Torvalds erklärte seine Wahl des ungewöhnlichen Namens mit einem Witz sowie damit, dass das Wort praktikabel und in der Softwarewelt noch weitgehend unbenutzt war:

“I’m an egotistical bastard, and I name all my projects after myself. First ‘Linux’, now ‘Git’.”

„Ich bin ein egoistischer Mistkerl, und ich benenne all meine Projekte nach mir. Zuerst ‚Linux‘, jetzt eben ‚Git‘.“

– Linus Torvalds
“The joke ‘I name all my projects for myself, first Linux, then git’ was just too good to pass up. But it is also short, easy-to-say, and type on a standard keyboard. And reasonably unique and not any standard command, which is unusual.”

„Der Witz ‚Ich benenne alle meine Projekte nach mir, zuerst Linux, nun eben Git‘ war einfach zu gut, um ihn nicht zu machen. Aber es (der Befehl) ist auch kurz, einfach auszusprechen und auf einer Standardtastatur zu schreiben, dazu einigermaßen einzigartig und kein gewöhnliches Standardkommando – sehr ungewöhnlich.“

– Linus Torvalds
Der Name Linux wurde anfangs nicht von Torvalds selbst propagiert und nur widerwillig akzeptiert.

# Quellen

https://de.wikipedia.org/wiki/Git

