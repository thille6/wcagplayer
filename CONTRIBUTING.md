# Bidra till Tillgänglighetsspelare

Tack för ditt intresse att bidra till Tillgänglighetsspelare! Vi välkomnar alla typer av bidrag som hjälper till att förbättra webbtillgängligheten.

## 🎯 Projektets mål

Vårt huvudmål är att skapa en fullt tillgänglig audiospelare som:
- Följer WCAG 2.1 AA-riktlinjerna
- Fungerar perfekt med skärmläsare
- Har fullständig tangentbordsnavigering
- Ger en bra användarupplevelse för alla

## 🤝 Hur du kan bidra

### Rapportera buggar
- Använd GitHub Issues för att rapportera buggar
- Inkludera steg för att återskapa problemet
- Beskriv din miljö (webbläsare, skärmläsare, etc.)
- Lägg till skärmdumpar om möjligt

### Föreslå funktioner
- Öppna en GitHub Issue med etiketten "enhancement"
- Beskriv funktionen och varför den behövs
- Diskutera hur den påverkar tillgängligheten

### Bidra med kod
1. Forka repositoryt
2. Skapa en feature branch (`git checkout -b feature/amazing-feature`)
3. Gör dina ändringar
4. Testa tillgängligheten noggrant
5. Commit dina ändringar (`git commit -m 'Add amazing feature'`)
6. Push till branchen (`git push origin feature/amazing-feature`)
7. Öppna en Pull Request

## 📋 Utvecklingsriktlinjer

### Kodstil
- Använd semantisk HTML5
- Skriv tydliga, beskrivande kommentarer
- Följ befintliga namnkonventioner
- Håll funktioner små och fokuserade

### Tillgänglighetskrav
- **WCAG 2.1 AA-efterlevnad är obligatorisk**
- Alla interaktiva element måste vara tangentbordstillgängliga
- Använd korrekt ARIA-märkning
- Testa med skärmläsare (NVDA, JAWS, VoiceOver)
- Säkerställ minst 4.5:1 kontrastförhållande

### Testning
Innan du skickar en PR, testa:

#### Tangentbordsnavigering
- [ ] Tab-ordning är logisk
- [ ] Alla kontroller nås med tangentbord
- [ ] Fokusindikatorer är synliga
- [ ] Inga tangentbordsfällor

#### Skärmläsare
- [ ] NVDA (Windows)
- [ ] JAWS (Windows) - om tillgängligt
- [ ] VoiceOver (macOS)
- [ ] Orca (Linux) - om tillgängligt

#### Webbläsare
- [ ] Chrome (senaste)
- [ ] Firefox (senaste)
- [ ] Safari (senaste)
- [ ] Edge (senaste)

#### Responsivitet
- [ ] Mobil (320px+)
- [ ] Tablet (768px+)
- [ ] Desktop (1024px+)

## 🛠️ Utvecklingsmiljö

### Förutsättningar
- Modern webbläsare
- Texteditor eller IDE
- Grundläggande kunskap om HTML, CSS, JavaScript
- Förståelse för webbtillgänglighet

### Lokal utveckling
```bash
# Klona ditt fork
git clone https://github.com/ditt-användarnamn/wcagplayer.git
cd wcagplayer

# Starta lokal server
python -m http.server 8000
# eller
npx serve .

# Öppna http://localhost:8000
```

### Verktyg för tillgänglighetstestning
- **axe DevTools** - Webbläsartillägg för automatisk testning
- **WAVE** - Web Accessibility Evaluation Tool
- **Lighthouse** - Inbyggt i Chrome DevTools
- **Colour Contrast Analyser** - För kontrasttestning

## 📝 Pull Request-process

### Innan du skickar
1. Säkerställ att din kod följer projektets riktlinjer
2. Testa alla tillgänglighetskrav
3. Uppdatera dokumentation om nödvändigt
4. Skriv tydliga commit-meddelanden

### PR-beskrivning
Inkludera:
- Beskrivning av ändringarna
- Motivering för ändringarna
- Testresultat (särskilt tillgänglighet)
- Skärmdumpar om relevant
- Breaking changes (om några)

### Granskningsprocess
- Minst en maintainer granskar din PR
- Automatiska tillgänglighetstester körs
- Feedback ges konstruktivt
- Ändringar kan begäras

## 🏷️ Etiketter och prioritering

### Etiketter vi använder
- `bug` - Något fungerar inte
- `enhancement` - Ny funktion eller förbättring
- `accessibility` - Tillgänglighetsrelaterat
- `documentation` - Förbättringar av dokumentation
- `good first issue` - Bra för nya bidragsgivare
- `help wanted` - Extra uppmärksamhet behövs
- `priority: high/medium/low` - Prioritetsnivå

## 🎨 Designprinciper

### Tillgänglighet först
- Designa för skärmläsare från början
- Tänk på tangentbordsanvändare
- Använd semantisk HTML
- Testa tidigt och ofta

### Progressiv förbättring
- Grundfunktionalitet fungerar utan JavaScript
- Förbättra upplevelsen med CSS och JS
- Graceful degradation för äldre webbläsare

### Prestanda
- Håll filstorlekarna små
- Optimera för långsamma anslutningar
- Använd effektiva algoritmer

## 🆘 Få hjälp

### Var du kan få stöd
- **GitHub Discussions** - Allmänna frågor och diskussioner
- **GitHub Issues** - Specifika problem eller buggar
- **E-post** - [Din kontakt-e-post här]

### Resurser för tillgänglighet
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [MDN Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
- [WebAIM](https://webaim.org/)
- [A11y Project](https://www.a11yproject.com/)

## 📜 Uppförandekod

Vi förväntar oss att alla bidragsgivare:
- Är respektfulla och inkluderande
- Fokuserar på konstruktiv feedback
- Hjälper till att skapa en välkomnande miljö
- Prioriterar tillgänglighet i alla beslut

## 🙏 Erkännanden

Alla bidragsgivare kommer att erkännas i projektets README. Tack för att du hjälper till att göra webben mer tillgänglig!

---

**Frågor? Öppna en issue eller starta en diskussion. Vi hjälper gärna till!**