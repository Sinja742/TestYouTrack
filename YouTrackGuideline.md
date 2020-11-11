# Guideline für YouTrack

<ul> 
	<li><a href=#Team>Team & Rollen</a></li>
  	<li><a href=#Time Tracking>Time Tracking</a></li>
  	<li><a href=#Agiles Board>Agiles Board</a></li>
	<ul>
		<li><a href=#Agiles Board erstellen>Agiles Board erstellen</a></li>
		<li><a href=#Automatisiertes Time Tracking>Automatisiertes Time Tracking</a></li>
	</ul>
	<li><a href=#Reports>Reports</a></li>
	<li><a href=#Dashboard>Dashboard</a></li>
	<ul>
		<li><a href=#Dashboard erstellen>Dashboard erstellen</a></li>
		<li><a href=#Dashboard öffentlich machen>Dashboard öffentlich machen</a></li>
	</ul>
	<li><a href=#GitHub>GitHub integrieren</a></li>
	<li><a href=#IntelliJ>IntelliJ integrieren</a></li>
	<ul>
		<li><a href=#IntelliJ integrieren>IntelliJ integrieren</a></li>
		<li><a href=#Time Tracking mit IntelliJ>Time Tracking mit IntelliJ</a></li>
	</ul>
</ul>
<h2 id="Team">Team & Rollen</h2>
Wenn man das eigene Projekt aufruft, ist rechts eine Sidebar, in der man die verschiedensten Einstellungen für das Projekt treffen kann.
(Hier Bild)
Unter dem Administrations Punkt Team kann man weiter Mitglieder hinzufügen. Denen muss man aber auch noch gegeben falls Rollen zu weisen, unter dem Punkt Access.
(Hier 2 Bilder)
Die einzelnen Rollen mit deren Beschreibungen findet man bei den Standardeinstellungen unter dem Punkt Roles. 
(Hier Bild)

<h2 id="Time Tracking">Time Tracking</h2>
Um das Time Tracking für eine Task zu ermöglichen müssen vorher noch Einstellungen getroffen werden. 
(Hier Bild)
Bei den selben Projekteinstellungen wie weiter oben schon erwähnt, müssen wir unter dem Punkt Time Tracking in das Kästchen ein Häkchen setzen (1) und in den unteren Feldern ein Wert setzen (2), welche dann auch bei den angelegten Karten als Felder zu sehen sind. Darüber hinaus können noch Work Items gesetzt werden (3), um für später das Filtern zu ermöglichen.
Nun ist es möglich die Zeit manuell bei den Karten zu tracken.

Dies kann man aber auch automatisieren. Dafür geht man in den Projekteinstellungen zum Punkt Workflow und fügt den Workflow „In Progress Work Timer“ hinzu. Dieser benötigt aber noch ein paar Einstellungen. Dafür klappt man die Unterpunkte aus, klickt eins an und geht auf „Configure project“, um die Einstellungen automatisch einzustellen.
(Hier Bild)
<h2 id="Agiles Board">Agiles Board</h2>

<h3 id="Agiles Board erstellen">Agiles Board erstellen</h3>
Beim Agilen Board können wir Karten/ Tasks erzeugen.Dafür müssen wir auch Felder ausfüllen. Hier sind jetzt zwei Felder hinzugekommen, in denen zum einen die geschätzte Zeit eingetragen werden kann und die wirkliche Zeit, die man für diese Task gebraucht hat, welche getrackt wird oder manuell, mit dem Button „Add spent Time“, nach Beendigung der Task, eingegeben werden kann. 
(Hier 2 Bilder)
Des weiterem ist es möglich Stories/Swimlane hinzuzufügen, welche zur Übersichtlichkeit dienen und ermöglichen mehrere Tasks derselben Gruppe einer übergeordneten Story unterzuordnen und so Beziehungen zwischen den einzelnen Tasks ermöglicht.
(Hier Bild)
Unter den Einstellungen vom Board können weitere Optimierungen getroffen werden, wie zum Beispiel eine neue Spalte zur Ordnung der einzelnen Tasks hinzufügen.
(Bild)

<h3 id="Automatisiertes Time Tracking">Automatisiertes Time Tracking</h3>
Dadurch das der Workflow „In Progress Work Timer“ hinzugefügt wurde, ist es möglich die Zeit automatisch zu tracken. Sobald eine Task auf den Status „In Progress“ gesetzt wird, startet der Timer und zählt die Zeit solange, bis diese Task in irgendein anderen Status gesetzt wird. Dann wird in dem Feld „Time spent“ automatisch die zeit gesetzt, es muss aber noch ein Work Item gesetzt werden, um später die Informationen mit Filtern zu nutzen. Dies kann man, indem man den stream der zeit aufmacht und bearbeitet.
(Bild)
<h2 id="Reports">Reports</h2>
Es gibt sehr viele Möglichkeiten die Daten zu verwerten und darzustellen. Man kann die verschiedensten Diagramme erstellen. Um zu sehen wie diese Diagramme aussehen, kann man sich dazu ein Beispiel angucken.
Beim Erstellen eines Reports muss man beachten, wer alles dieses Diagramm sehen kann und wer auch bearbeiten. 
(3Bilder)
<h2 id="Dashboard">Dashboard</h2>
<h3 id="Dashboard erstellen">Dashboard erstellen</h3>
Beim Dashboard kann man viele verschiedene Widgets hinzufügen.
(Bild)
Hier kommen auch die Reports zum Einsatz. 
Das Dashboard kann man sich zu belieben gestalten.

<h3 id="Dashboard öffentlich machen">Dashboard öffentlich machen</h3>
Damit das Dashboard auch von anderen gesehen werden kann, muss es zum einen geteilt und zum anderen eine weitere Rolle hinzugefügt werden.
Teilen kann man, wenn man den Share Button drückt und die User oder Gruppen auswählt, mit denen man das Dashboard teilen will..
(2 Bilder)
Die Rolle fügen wir dort hinzu, wo auch schon die Rollen der Teammitglieder hinzugefügt wurden.
Mit den werten wie im Bild zusehen, sind alle Daten zu den Tasks für andere Sichtbar.
(Bild)

<h2 id="GitHub">GitHub integrieren</h2>
GitHub integrieren kann man, wenn man in den Projekteinstellungen unter dem Punkt „VCS“ auf „New VCS Integration“ geht und dann als Server type GitHub auswählt, die URL des Repository und ein Token eingibt.
(Bild)
Mit der Integration von GitHub ist es möglich gleich aus der Task heraus einen Commit zu tätigen und auch den Stream zu sehen.

<h2 id="IntelliJ">IntelliJ integrieren</h2>
<h3 id="IntelliJ integrieren">IntelliJ integrieren</h3>
Die Integration in IntelliJ ist ein wenig aufwendiger.
Zuerst muss das Plugin „YouTrack Integration“ installiert sein.
(Bild)
Danach öffnet man die Einstellungen von IntelliJ.
(Bild)
In den Einstellungen unter Tools und dort unter Tasks bei den Punkt Servers klickt man auf das Plus und sucht den Server YouTrack aus. 
Dort müssen nur die Felder ausgefüllt werden mit der Server URL, Benutzername und Passwort.
Bei dem Feld Search können noch Einstellungen getroffen werden, welche Tasks angezeigt werden sollen.
(Bild)
YouTrack kann man nach der Installation in der Leiste unten sehen. Dort werden alle Tasks gezeigt, welche den Kriterien entsprechen die zuvor eingegeben worden sind.
(bild)

<h3 id="Time Tracking mit IntelliJ">Time Tracking mit IntelliJ</h3>
Auch das Time Tracking über IntelliJ ist möglich.
Hierfür muss nur eine Task ausgewählt und in den Status „In Progress“ verschoben werden.
Damit startet auch der Work Timer.
(2 Bilder)
Dann befindet sich die Task in einer Changelist, mit der man, wenn man Veränderungen am Code vorgenommen haben, auch Commits ausüben sowie Branches mergen kann.
(Bild)
Wenn die Task geschlossen werden soll, kann man dies entweder wie folgt auf dem Bild tun oder den Short-Cut „Alt+Umschalt+W“ nutzen. Beim schließen verschiebt man die Task wieder in einen anderen Status und der Work Timer hätte die Zeit getrackt.
(Bild)
