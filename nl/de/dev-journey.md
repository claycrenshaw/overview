---

copyright:
  years: 2016, 2019
lastupdated: "2019-02-19"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Journey von Entwicklern in {{site.data.keyword.cloud_notm}} erkunden
{: #dev-journey}

Als Entwickler entscheiden Sie, welcher der beste Eingangspunkt für Ihren Code ist. Sie bestimmen, ob Sie Ihren Code über die von uns bereitgestellten Tools generieren möchten oder ob Sie Ihren eigenen Code mitbringen und in {{site.data.keyword.cloud}} bereitstellen wollen!
{: shortdesc}

{{site.data.keyword.cloud_notm}} bietet ein Leistungsspektrum, mit dem Sie schon nach wenigen Minuten mit der Erstellung von Apps beginnen können. Die Entwicklertools von {{site.data.keyword.cloud_notm}} erstellen eine leistungsstarke Basis, die Sie benötigen, um zügig den Einstieg zu finden. Für die Entwicklung werden zwei Haupttools angeboten:
 * {{site.data.keyword.cloud_notm}}-Webkonsole (Entwicklerportale)
 * {{site.data.keyword.cloud_notm}}-Befehlszeilenschnittstelle (Command-Line Interface, CLI)

Mit {{site.data.keyword.cloud_notm}} haben Sie folgende Möglichkeiten:

* Sie können Starter-Kits auswählen, die anwendungsfallspezifisch sind, und einsatzbereite Apps in diversen Programmiersprachen und Architekturmustern erzeugen.
* Sie können ein [IBM Developer-Codemuster ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://developer.ibm.com/patterns/){:new_window} verwenden, um Ihre App rasch zu erstellen und in {{site.data.keyword.cloud_notm}} bereitzustellen.
* Sie können Ressourcen anzeigen und verwalten, die automatisch von Ihrem Starter-Kit bereitgestellt werden oder die Sie manuell zu Ihrer App hinzufügen.
* Wenn Sie über eine App in einem vorhandenen Repository verfügen, können Sie ein leeres Starter-Kit verwenden, um einen Appdatensatz zu erstellen, den Sie dann mit Ihrem Quellenrepository und einer DevOps-Toolchain verbinden.
* Mit portierbarem App-Code können Sie die Bereitstellung in unterschiedlichen Cloudumgebungen durchführen.
* Sie können in wenigen Klicks eine [DevOps-Toolchain](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) erstellen.
* Verwenden Sie die [Befehlszeilenschnittstelle (CLI)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud-cli#ibmcloud-cli) für die lokale Entwicklung. 
* Sie können im [{{site.data.keyword.cloud_notm}}-Katalog ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://{DomainName}/catalog){: new_window} stöbern und ihn nach Apps und Services durchsuchen, die Sie noch am selben Tag erstellen und benutzen können.

![Übersicht über Developer Experience](images/dev-journey.png "Übersicht über Developer Experience")

Um besser zu verstehen, wie unsere Erfahrung Ihnen helfen kann, rasch qualitativ hochwertige und einsatzbereite Apps zu erstellen, gehen wir im Folgenden näher auf diese Elemente ein.

## Entwicklerportale
{: #dev-portals}

{{site.data.keyword.cloud_notm}} besitzt Entwicklerportale für verschiedene Interessensbereiche (wie Watson, Sicherheit oder Finanzen) bzw. digitale Kanäle (wie Mobile oder Web-Apps). Auf diese Portale können Sie über das Symbol **Menü** ![Symbol 'Menü'](../icons/icon_hamburger.svg) zugreifen.

Jedes Entwicklerportal stellt Starter-Kits zur Verfügung, die für den jeweiligen Schwerpunktbereich des entsprechenden Portals relevant sind. Die Portale ermöglichen einen konsistenten und intuitiven Workflow, der die Erstellung einer funktionierenden einsatzbereiten App in nur wenigen Minuten zulässt.

## Apps
{: #app-projects}

Eine App umfasst Code, Daten, Services und Toolchains. Beispielsweise enthält die {{site.data.keyword.cloud_notm}} Mobile-App Gerätecode und Back-End-Logik, Datenspeicher, Analyse- und Sicherheitsservices und ist für Continuous Delivery konzipiert.

![Wiederverwenden](images/garage_reuse2.png "Developer Experience ermöglicht die Wiederverwendung von Elementen, sodass Sie das Rad nicht immer wieder neu erfinden müssen.")

Sie können eine App mithilfe eines beliebigen {{site.data.keyword.cloud_notm}}-Entwicklerportals oder mit der {{site.data.keyword.dev_cli_notm}} erstellen und verwalten.

Einfache Apps können Sie direkt erstellen. Zum Erstellen komplexerer Apps können Sie die Starter-Kits verwenden. Wenn Sie sich dazu entschließen, leere Apps ohne die Unterstützung eines Starter-Kits zu erstellen, können Sie diesen Vorgang über das [{{site.data.keyword.cloud_notm}}-Dashboard ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://{DomainName}){: new_window} durchführen, ohne dazu eines der Portale aufzusuchen.

Sie können ein Codemuster verwenden, um Ihre App rasch zu erstellen und in {{site.data.keyword.cloud_notm}} bereitzustellen. Wählen Sie dazu auf der [IBM Developer-Website ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://developer.ibm.com/patterns/){:new_window} ein Codemuster aus. Sie können den Code entweder in GitHub anzeigen oder eine App auf {{site.data.keyword.cloud_notm}} erstellen und dort ihren Build erstellen. Außerdem können Sie dort Ihre App mithilfe einer DevOps-Toolchain automatisch bereitstellen.


## Starter-Kits
{: #starter-kits}

Starter-Kits sollen dafür sorgen, dass Ihr Erlebnis benutzerfreundlich und anpassbar ist. Die Starter-Kits bewirken die Assemblierung des Gerüsts einer Produktions-App in der Sprache in Ihrer Wahl, das für die Bereitstellung in der Cloud einsatzbereit ist. Jedes Starter-Kit umfasst eine Sprache, ein Framework und ein Muster für einen bestimmten Anwendungsfall sowie für die Wiederverwendung von Code.

Wenn ein Starter-Kit bestimmte Ressourcen erfordert, stellt dies keinerlei Problem dar. Mithilfe von automatisch bereitgestellten Ressourcen erstellt {{site.data.keyword.cloud_notm}} automatisch Instanzen für diese Ressourcen, wenn Sie Ihre App erstellen. Der Zugriff auf Starter-Kits kann über das Entwicklerportal erfolgen oder aber über die Befehlszeilenschnittstelle (Command Line Interface, CLI), wenn Sie Anweisungen wünschen, die für Ihren Schwerpunktbereich und Workflow relevant sind.

### Inwiefern unterscheiden sich Starter-Kits von normalen Beispielen?
Starter-Kits sind sofort einsatzbereit und veranschaulichen in erster Linie die Implementierung eines grundlegenden Musters mithilfe einer Laufzeit (z. B. Node.js und Express). In manchen Fällen bieten Starter-Kits eine einfache Benutzererfahrung, um die Integration des Service hervorzuheben. In anderen Fällen stellen Starter-Kits eine anpassbare Implementierung eines ausgereiften Anwendungsfalls dar.

* Ein Snippet besteht aus einer Reihe von Codezeilen, die häufig in einer IDE enthalten werden. Snippets unterstützen einen Entwickler bei der Integration einer Programmiersprachensyntax oder einer definierten API.
* Eine Demonstration ist üblicherweise qualitativ hochwertig und inhaltstreu und verwendet eine Reihe von Services und Integrationspunkten. Sie erfordert oft eine gewisse Rüstzeit und wird eingesetzt, um ein Geschäftsproblem zur veranschaulichen oder ein Plattformfeature vorzuführen. Mit ihr können Sie die Phasen (Stages) der Cloudeinführung bewerten. In manchen Fällen handelt es sich um Code, der in den Produktionscode eingebunden ist.
* Ein Beispiel ist ein kompakte Veranschaulichung eines bestimmtes Features, einer bestimmten Funktion, eines bestimmten Service oder einer bestimmten User Journey. Sie können ein Beispiel wiederverwenden oder es in eine Produktionsanwendung einbinden. Ein Beispiel dient typischerweise dazu, die technische Funktionalität zu veranschaulichen und mögliche Lösungswege für ein technisches Problem aufzuzeigen.
* Ein Starter-Kit ist ein einsatzbereites Muster, das in eine Gruppe von Services integriert werden kann, um ein einsatzbereites Asset zu generieren, das direkt in einer DevOps-Pipeline und einem Kubernetes-Cluster bereitgestellt werden kann. Ein Starter-Kit enthält beschreibende Metadaten, die dem Benutzer ausreichend Informationen über den Aufbau und die Funktionalität des Kits liefern. Es enthält außerdem Anweisungen, was {{site.data.keyword.cloud_notm}} erzeugen soll. Die Ausgabe ist direkt einsatzbereit und kann für weitere Verbesserungen iteriert werden, auf der Basis von IBM Best Practices. Der Inhalt eines Starter-Kits ist nicht so komplex wie eine Demonstration und nicht so einfach strukturiert wie ein Snippet oder ein Beispiel. Starter-Kits werden abhängig von den Anforderungen eines Entwicklers dynamisch erstellt.

## Automatisch bereitgestellte Ressourcen
{: #auto-provision}

Falls ein Starter-Kit erforderliche Ressourcen angibt, erstellt {{site.data.keyword.cloud_notm}} automatisch Instanzen dieser Ressourcen, wenn Sie Ihre App erstellen. Sie können Ressourcen auch manuell bereitstellen oder vorhandene Ressourceninstanzen auswählen, die nach der Erstellung Ihrer App zu ihr hinzugefügt werden. In der Ansicht 'App-Details' können Sie eine Liste von Serviceinstanzen anzeigen, die Ihrer App zugeordnet sind. Außerdem sind dort die ggf. erforderlichen Berechtigungsnachweise aufgeführt.

## Portierbarer Code
{: #portable-code}

Beim Erstellen einer App aus einem Starter-Kit wird automatisch Code für Sie erstellt, der ein konsistentes Format hat und von der Laufzeit unabhängig ist. Sie können den Code in der Umgebung Ihrer Wahl bereitstellen, wie z. B. in Kubernetes oder Cloud Foundry, ohne Änderungen daran vorzunehmen.

Wenn Sie sich rasch einen Überblick über Ihren App-Code verschaffen wollen, können Sie hierzu auf der Seite mit den App-Details für Ihre App auf **Code herunterladen** klicken. Ihr Code wird in Form einer `.zip`-Datei heruntergeladen, die die vollständige App-Codestruktur enthält. Sie können die Datei einfach erstellen und den Code lokal mithilfe der {{site.data.keyword.dev_cli_notm}} ausführen oder Sie können ihn zu Ihrem Code-Management-Repository hinzufügen.

### Welcher Code wird erstellt?
{: #what-code}

Wenn Sie eine App direkt oder mithilfe eines Starter-Kits erstellen, enthält die App portierbaren Code. Portierbarer Code enthält Cloudaktivierungscode für mehrere Cloudumgebungen.Sie können dann Code in vier elementaren Bereichen erstellen:
* Code, der den bewährten Verfahren für eine bestimmte Sprache entspricht
* Code, der Ihre App befähigt, in der Cloud ausgeführt zu werden
* Code, der für die Verbindungsherstellung zu Cloud-Services initialisiert wurde
* Code, der für einen Anwendungsfall spezifisch ist

Das Generieren dieser Komponenten spart Ihnen wertvolle Zeit und stellt sicher, dass Sie eine leistungsfähig Architektur verwenden.

* Anwendungsfalllogik bietet Funktionen für den zentralen Zweck eines Anwendungsfalls. Beispiele sind unter anderem Code für einen Watson Conversation-Chat-Bot oder Code für eine mobile App für visuelle Erkennung.
* Sprachkomponenten sind Codekomponenten und Dateien, die spezifisch sind für die Programmiersprache, die Sie für Ihr Starter-Kit ausgewählt haben. Node.js-Programmierer benötigen zum Beispiel eine 'package.json'-Datei für das Abhängigkeitsmanagement. Diese Datei wird automatisch erstellt.
* Serviceaktivierung ist Code, der Ihrer App ermöglicht, die Services, die Sie hinzufügen, zu verbinden und zu verwenden. Verwaltung von Berechtigungsnachweisen, Initialisierungscode und servicespezifische SDKs sind Beispiele für Serviceaktivierungskomponenten.
* Cloudaktivierung ist Code, der Ihre App befähigt, unter {{site.data.keyword.cloud_notm}} ausgeführt zu werden. Beispielsweise Helm-Diagramme, die Ihre App befähigen, in einem {{site.data.keyword.cloud_notm}}-Kubernetes-Cluster ausgeführt zu werden.

Wenn Sie eine App auf der Grundlage eines {{site.data.keyword.cloud_notm}}-Starter-Kits erstellen, baut diese App auf bewährter Architektur auf, die außerdem die bewährten Verfahren (Best Practices) für die von Ihnen ausgewählte Sprache widerspiegelt.

Jede App enthält eine Readme-Datei mit den technischen Details des Projekts und erläutert, welche Schritte ausgeführt werden müssen, wenn Ihre App nicht sofort einsatzbereit ist.
{: tip}

## Eigenen Code integrieren und in {{site.data.keyword.cloud_notm}} bereitstellen
{: byoc}

Wenn Sie über eine App in einem vorhandenen Repository verfügen, können Sie ein leeres Starter-Kit verwenden, um einen Appdatensatz in {{site.data.keyword.cloud_notm}} zu erstellen und die App dann mit Ihrem Quellenrepository und Ihrer DevOps-Toolchain zu verbinden.

Zum Starten können Sie das {{site.data.keyword.cloud_notm}}-Dashboard oder ein beliebiges leeres Starter-Kit verwenden. Nachdem Sie einen Namen für Ihre App angegeben und eine Ressourcengruppe ausgewählt haben, wählen Sie den Ausgangspunkt [**Eigenen Code integrieren**](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc) aus, geben die URL für das Git-Repository an, in dem sich Ihr Code befindet, und klicken auf **Erstellen**.

Sie können Ihre vorhandene DevOps-Toolchain anbinden oder eine erstellen und Ihre App kontinuierlich in der Umgebung Ihrer Wahl bereitstellen, wie Kubernetes oder Cloud Foundry.


## DevOps-Toolchain
{: #devops}

Die DevOps-Toolchain umfasst Prozeduren und Tools für den Zugriff, die Entwicklung, die Bereitstellung und den Betrieb Ihrer App. Eine DevOps-Toolchain ist ein Gruppe verknüpfter Services zur Automatisierung Ihrer DevOps-Tasks. Es ist möglich, DevOps mithilfe von einfachen Apps manuell auszuführen, aber der Bedarf an Automatisierung nimmt mit der Komplexität von Apps schnell zu und die Toolchain-Automatisierung ist ein Must-Have für Continuous Delivery.

Die zentrale Komponente einer DevOps-Toolchain ist ein Repository für die Steuerung von Codeversionen wie GitHub. Weitere Tools können ein Rückstandtracking, eine Delivery Pipeline, eine IDE und einen Überwachungsservice wie [{{site.data.keyword.cloud_notm}} {{site.data.keyword.DRA_short}}](/docs/services/DevOpsInsights?topic=DevOpsInsights-getting-started#getting-started) enthalten.

Wenn Sie eine App unter Verwendung eines Starter-Kits erstellen, können Sie eine neue Toolchain erstellen und Ihre App bereitstellen, indem Sie auf der Seite **App-Details** einfach auf **In Cloud bereitstellen** klicken. Es wird eine Toolchain mit einem Coderepository, einer Delivery Pipeline und einer Web-IDE erstellt.

Auf der Grundlage dieser Toolchain können Sie dann die weitere Entwicklung betreiben, um mehrere Teams zu berücksichtigen und die Bereitstellung in separaten Umgebungen für Entwicklung, Tests und Produktion zu ermöglichen. So erstellen Sie ein auf Unternehmen abgestimmtes Modell für bereichsübergreifende Continuous Delivery für Ihre App.

![Continuous Delivery](images/garage_continuous_delivery2.png "Die Entwicklungsumgebung richtet Continuous Delivery in Ihrem Entwicklungszweig ein.")


## CLI
{: cli}

Verwenden Sie die Befehlszeilenschnittstelle (Command-Line Interface, CLI), um Ihre App lokal zu codieren, zu erstellen und auszuführen. Eine gängige Vorgehensweise besteht darin, Ihre App mithilfe eines Entwicklerdashboards in der {{site.data.keyword.cloud_notm}}-Konsole zu erstellen, die Entwicklertools für die lokale Entwicklung zu verwenden und die Aktualisierungen dann per Push-Operation in Ihr Repository zu übertragen und dort zusammenzuführen, um Ihre Toolchain für Bereitstellung zu starten.

## Garage Method-Entwicklung
{: #developer_concepts}

Wenn Sie nach einem Ort suchen, an dem Sie mit großen Ideen und aufstrebenden Technologien experimentieren können, sollten Sie sich unbedingt über Bereitstellungen mit [Garage Method](https://www.ibm.com/cloud/garage/){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") informieren. Hier erfahren Sie, wie IBM Sie beim Entwickeln von Apps in Ihrer Organisation unterstützen kann.

![Übersicht über die Garage Method-Phasen](images/garage_phases_overview2.png "Übersicht über die Garage Method-Phasen") 

{{site.data.keyword.cloud_notm}} hilft Ihnen dabei, auf Unternehmen abgestimmte Produktions-Apps mithilfe der Garage Method oder einer beliebigen anderen Methode zu erzeugen. Um besser zu verstehen, was {{site.data.keyword.cloud_notm}} Entwicklern zu bieten hat, soll Ihnen der folgende kurze Überblick vermitteln, welche Fähigkeiten erforderlich sind, um eine moderne App zu erstellen.

## Entwickler-Know-how
{: #skills}

Benutzer erwarten mehr von ihren Anwendungen als je zuvor. Sie erwarten, dass Apps aussagekräftige Informationen aus gespeicherten und Echtzeitdaten ziehen, immer verfügbar sind und ihre individuellen Bedürfnisse möglichst optimal abbilden. Um diesen Erwartungen gerecht zu werden, sind die Entwicklerfunktionalitäten in IBM Cloud an bestimmten Qualifikationsprofilen ausgerichtet und ermöglichen Ihrem Team die Verwendung einer einzigen Plattform zum Erzeugen, Bereitstellen, Ausführen und Verwalten Ihrer Apps.Eine ausgereifte kognitive Anwendung kann Beiträge von digitalen Entwicklern, Spezialisten für die cloudnative Entwicklung, Streams-Entwicklern, Data-Scientists und DevOps-Spezialisten erforderlich machen. 

 ![Entwicklertypen](images/developer_skills.png "Beziehungen zwischen Entwicklern")

* Digitale Entwickler erstellen einen digitalen Kanal wie mobiles Web, Sprachsteuerung und Chat. Digitale Entwickler konzentrieren sich typischerweise auf Anwendungsfälle und die direkte Erfüllung von Benutzeranforderungen.
* Auf die cloudnative Entwicklung spezialisierte Entwickler erstellen in erster Linie Cloudkomponenten und verbinden diese miteinander. Dazu zählen beispielsweise Verfasser von Mikroservices und Back-End-for-Front-End-Verfasser.
* Streams-Entwickler konzentrieren sich auf die Verarbeitung von Datenströmen und den entsprechenden Erkenntnisgewinn. Ein Streams-Entwickler kann beispielsweise Aktionen für eingehende Text-, Sprache- oder Videodatenströme analysieren und initiieren.
* Data-Scientists setzen Analysen und maschinelles Lernen ein, um Vorhersagemodelle zu erstellen. Diese Modelle werden in Geschäftsmetriken verwendet und liefern aussagekräftige Informationen für Anwendungsbenutzer.
* DevOps-Spezialisten sind Experten im Beheben von Bereitstellungs- und Toolchain-Problemen. Bei einfachen Apps sind dedizierte Spezialisten üblicherweise nicht erforderlich, da DevOps im Team verwaltet werden. Aber bei komplexen Unternehmensanwendungen mit vielen Abhängigkeiten sind DevOps-Spezialisten unerlässlich, um Ihre Produktions-App reibungslos ausführen zu können.

Die Entwicklerfunktionalitäten, die in {{site.data.keyword.cloud_notm}} integriert sind, sind an diesen Qualifikationsprofilen ausgerichtet und ermöglichen Ihrem Team die Verwendung einer einzigen Plattform zum Erzeugen, Bereitstellen, Ausführen und Verwalten Ihrer App. Ein digitaler Entwickler, der eine mobile App erstellt, könnte zum Beispiel das {{site.data.keyword.cloud_notm}} [Mobile-Entwicklerportal](https://{DomainName}/developer/mobile/dashboard){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") verwenden. Ein Entwickler von kognitiven Apps könnte hingegen das [Watson-Entwicklerportal](https://{DomainName}/developer/watson/dashboard){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") zusammen mit [Watson Studio](https://{DomainName}/catalog/services/watson-studio){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") verwenden. Ein Streams-Entwickler wiederum kann [IBM Real-Time Analytics](/docs/services/StreamingAnalytics/index.html) verwenden. Der [{{site.data.keyword.cloud_notm}} Continuous Delivery-Service](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) vereinfacht die Arbeit eines DevOps-Spezialisten.

[Sind Sie bereit, mit der Erstellung hochwertiger einsatzbereiter Apps loszulegen? ](/docs/apps/tutorials?topic=creating-apps-tutorial-getting-started#tutorial-getting-started)
