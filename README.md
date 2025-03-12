# Einrichtung eines Vue.js-Projekts  

Zunächst wird das Vue CLI installiert, um eine standardisierte Projektstruktur bereitzustellen:  

```bash
npm install -g @vue/cli
vue create RefactoringEIS
```
Nach dem Ausführen von vue create können spezifische Projektpräferenzen wie TypeScript oder der Vue Router konfiguriert werden. Anschließend wird das Projekt gestartet:
```bash
cd RefactoringEIS
npm run serve
```
Dieser Befehl startet einen lokalen Entwicklungsserver, mit dem die Anwendung direkt getestet werden kann.

Zusätzlich werden einige Pakete installiert, um eine vollständige Entwicklungsumgebung bereitzustellen:
```bash
npm install materialize-css
npm install typescript --save-dev
npm install axios
```
Installierte Pakete:
```bash
    MaterializeCSS – für ein einheitliches und responsives UI-Design
    TypeScript – für eine typensichere Entwicklung
    Axios – zur einfachen Handhabung von HTTP-Anfragen
```
Projektaufsetzung

Für die lokale Entwicklung wurde Visual Studio Code verwendet. Das bestehende Projekt wurde von GitHub geklont und die Abhängigkeiten installiert:
```bash
git clone https://github.com/beispieluser/RefactoringEIS.git
cd RefactoringEIS
npm install
```
    git clone lädt das Repository herunter.
    npm install installiert alle erforderlichen Abhängigkeiten basierend auf der package.json.

Diese Schritte stellen sicher, dass die Entwicklungsumgebung vollständig eingerichtet ist.
