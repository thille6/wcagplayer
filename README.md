# Tillgänglighetsspelare (WCAG Audio Player)

En fullt tillgänglig audiospelare som följer WCAG 2.1-riktlinjerna för webbtillgänglighet. Spelaren är designad för att vara användbar för alla, inklusive personer med funktionsnedsättningar som använder skärmläsare eller tangentbordsnavigering.

## 🎯 Funktioner

### Grundläggande Uppspelning
- ▶️ Spela/pausa audio
- ⏭️ Nästa/föregående spår
- 🔊 Volymkontroll med slider
- ⚡ Hastighetskontroll (0.5x - 2.0x)
- 📊 Visuell progress bar med tidsvisning

### Tillgänglighetsfunktioner
- 🎯 **WCAG 2.1 AA-kompatibel**
- 🔍 **Skärmläsarstöd** med ARIA-attribut
- ⌨️ **Fullständig tangentbordsnavigering**
- 🔴 **Live-regioner** för statusuppdateringar
- 🎨 **Mörkt/ljust tema** för visuell komfort
- 📱 **Responsiv design** för alla enheter

### Avancerade Funktioner
- 📝 **Textvisning/lyrics** med synkronisering
- 📋 **Spellista** med drag-and-drop
- 📁 **Filuppladdning** (MP3, WAV, OGG, M4A)
- 💾 **Lokal lagring** av inställningar
- 🔄 **Shuffle och repeat-lägen**

## 🚀 Kom igång

### Snabbstart
1. Ladda ner eller klona detta repository
2. Öppna `index.html` i en webbläsare
3. Börja använda spelaren direkt!

### Lokal utveckling
```bash
# Klona repositoryt
git clone https://github.com/thille6/wcagplayer.git
cd wcagplayer

# Starta en lokal server (valfritt)
python -m http.server 8000
# eller
npx serve .

# Öppna i webbläsare
# http://localhost:8000
```

## 🎮 Användning

### Tangentbordsgenvägar
- `Mellanslag` - Spela/pausa
- `Pil höger/vänster` - Hoppa framåt/bakåt (10 sek)
- `Pil upp/ner` - Volym upp/ner
- `M` - Mute/unmute
- `F` - Ladda upp fil
- `L` - Växla lyrics
- `S` - Shuffle
- `R` - Repeat
- `T` - Växla tema
- `1-9` - Hastighet (1=1x, 2=1.25x, etc.)

### Spellista
- Dra och släpp filer för att lägga till
- Klicka på spår för att spela
- Använd `Delete` för att ta bort markerat spår
- Navigera med piltangenter

### Tillgänglighet
- Alla kontroller är tillgängliga via tangentbord
- Skärmläsare får live-uppdateringar om spelstatus
- Visuella indikatorer för fokus och tillstånd
- Semantisk HTML för bättre navigation

## 🛠️ Teknisk information

### Teknologier
- **HTML5** - Semantisk struktur
- **CSS3** - Responsiv styling med CSS Grid/Flexbox
- **Vanilla JavaScript** - Ingen externa beroenden
- **Web Audio API** - Avancerad ljudhantering
- **File API** - Filuppladdning och hantering

### Webbläsarstöd
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Filformat som stöds
- MP3
- WAV
- OGG
- M4A
- FLAC (begränsat stöd)

## 📋 WCAG 2.1-efterlevnad

### Nivå AA-kriterier som uppfylls:
- **1.1.1** Icke-textinnehåll - Alt-text och ARIA-etiketter
- **1.3.1** Information och relationer - Semantisk HTML
- **1.4.3** Kontrast - Minst 4.5:1 kontrastförhållande
- **2.1.1** Tangentbord - Fullständig tangentbordsåtkomst
- **2.1.2** Ingen tangentbordsfälla - Fokus kan flyttas fritt
- **2.4.3** Fokusordning - Logisk tabbordning
- **2.4.7** Synligt fokus - Tydliga fokusindikatorer
- **3.2.1** Vid fokus - Inga oväntade kontextändringar
- **4.1.2** Namn, roll, värde - Korrekt ARIA-implementation

## 🤝 Bidra

Vi välkomnar bidrag! Se [CONTRIBUTING.md](CONTRIBUTING.md) för riktlinjer.

### Utvecklingsmiljö
1. Forka repositoryt
2. Skapa en feature branch
3. Gör dina ändringar
4. Testa tillgängligheten
5. Skicka en pull request

### Testa tillgänglighet
- Använd skärmläsare (NVDA, JAWS, VoiceOver)
- Testa tangentbordsnavigering
- Kontrollera kontrastförhållanden
- Validera HTML och ARIA

## 📄 Licens

Detta projekt är licensierat under MIT-licensen - se [LICENSE](LICENSE) filen för detaljer.

## 🙏 Erkännanden

- Utvecklad med fokus på webbtillgänglighet
- Inspirerad av WCAG 2.1-riktlinjerna
- Tack till tillgänglighetscommunityn för feedback

## 📞 Support

- 🐛 **Buggar**: Öppna en issue på GitHub
- 💡 **Funktionsförslag**: Diskutera i GitHub Discussions
- 📧 **Kontakt**: [Din e-post här]

---

**Gjord med ❤️ för en mer tillgänglig webb**