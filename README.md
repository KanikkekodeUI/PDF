# PDF reader

**PDF reader** er et gratis program til Mac, der læser dine PDF-filer højt på dansk og engelsk. Du kan også overstrege tekst, skrive kommentarer, rotere sider, vælge et tema, der skåner øjnene, og gøre scannede dokumenter søgbare med OCR.

## ⬇️ Download

**[Hent PDF reader 1.6.1 her](../../releases/latest)** (nyeste version)

Klik på filen `PDF-reader-1.6.1.dmg` under "Assets" på siden.

Kræver macOS 14 (Sonoma) eller nyere og virker på både Apple Silicon (M1, M2, M3 …) og Intel-Mac.

## Installation

1. Åbn den hentede DMG-fil.
2. Træk **PDF reader** over i mappen **Programmer**.
3. Åbn Programmer, og dobbeltklik på **PDF reader**.

### Første gang: "Programmet kan ikke åbnes"

PDF reader kommer ikke fra App Store, så første gang viser macOS en advarsel. Sådan åbner du programmet alligevel:

1. Klik på **OK** (eller **Færdig**) i advarslen.
2. Åbn **Systemindstillinger → Anonymitet og sikkerhed**.
3. Rul ned, klik på **Åbn alligevel** ud for PDF reader, og bekræft.

Det skal gøres én gang for hver ny version, du henter.

## Opdatér til en ny version

**Fra version 1.6:** Vælg **PDF reader → Søg efter opdateringer…** i menulinjen, og tryk på **Opdatér nu**. PDF reader henter, kontrollerer og installerer den nye version og starter igen – uden "Åbn alligevel".

**Har du en ældre version**, så opdatér sådan her:

1. Hent den nyeste DMG-fil via linket under **Download** ovenfor.
2. Luk PDF reader, hvis programmet er åbent (⌘Q).
3. Åbn DMG-filen, og træk **PDF reader** over i mappen **Programmer**.
4. Vælg **Erstat**, når macOS spørger, om den gamle version skal erstattes.
5. Åbn PDF reader. Første gang skal du igen klikke på **Åbn alligevel** under **Systemindstillinger → Anonymitet og sikkerhed** (se ovenfor).

Dine indstillinger bliver bevaret, fx tema, stemmer og ElevenLabs-nøgle, og dine PDF-filer bliver ikke rørt.

**Hvilken version har jeg?** Åbn PDF reader, og vælg **PDF reader → Om PDF reader** i menulinjen. Sammenlign med versionsnummeret under [Releases](../../releases).

**Få besked om nye versioner:** PDF reader tjekker ikke selv efter opdateringer, så programmet aldrig kontakter internettet uden din viden – kun når du vælger Søg efter opdateringer…. Har du en GitHub-konto, kan du klikke på **Watch → Custom → Releases** øverst på denne side og få en e-mail, når der kommer en ny version.

## Funktioner

- **Oplæsning på dansk og engelsk** med Macs egne stemmer. Programmet skifter selv sprog, også midt på en side, og markerer den sætning og det ord, der bliver læst op.
- **Naturlig oplæsning:** Forkortelser og tal læses helt ud – "fx" bliver til "for eksempel", "s. 12–15" til "side 12 til 15" og "e.g." til "for example". Sidetal, sidehoveder og fodnotetal springes over, og der holdes en pause efter overskrifter og i punktopstillinger.
- **Spring kildehenvisninger over:** Oplæseren kan springe henvisninger som (Hansen, 2019), (Smith et al., 2020, s. 12) og [12] over, også når de fortsætter fra én side til den næste. Du kan også vælge at springe al tekst i parentes over.
- **Hastighed fra 0,5× til 3×**, som ændres med det samme, også midt i en sætning.
- **ElevenLabs-stemmer** som valgfrit tilvalg for meget naturlige stemmer (kræver en API-nøgle fra ElevenLabs og koster penge ud over deres gratisplan).
- **Overstregning, understregning, gennemstregning og kommentarer** med et kommentarpanel, ligesom i Adobe Acrobat. Fortryd med ⌘Z.
- **Hurtig gemning:** Kun dine ændringer gemmes, ligesom i Adobe Acrobat. Selv en bog på 800 sider gemmes på under et sekund, og filen vokser ikke unødigt.
- **Overblik over mange noter:** Saml noterne i dine egne grupper med en selvvalgt titel, fx "Kapitel 2" eller "Til eksamen", eller gruppér dem efter side, type eller farve. Grupperne kan foldes sammen, noter kan trækkes mellem grupperne, og der er kompakt visning, filter og søgning.
- **OCR (tekstgenkendelse)** på dansk og engelsk, der gør scannede sider søgbare og klar til oplæsning. Dobbeltsider deles automatisk i to, og sider, der vender på hovedet eller ligger skævt, rettes op – hver side for sig. Kun de skannede sider udskiftes, så digital tekst aldrig røres.
- **Fortsæt hvor du slap:** PDF'en åbner på det sted, du sidst var, og oplæsningen fortsætter, hvor den stoppede.
- **Egne bogmærker** (⌘D) i sidepanelet, så du hurtigt kan hoppe tilbage til vigtige sider.
- **Udskriv** (⌘P) altid i de rigtige farver – også i Læse Mode og Dark Mode – med eller uden dine overstregninger og kommentarer.
- **Slå op:** Højreklik på et ord for at se det i macOS' ordbog.
- **Søgning med ⌘F**, der markerer alle steder, ordet står, viser hvor mange der er, og viser dem som små streger i kanten af dokumentet.
- **Eksportér noter** til Word, Markdown eller tekst med sidetal, markeret tekst og grupper – og **kopiér med kildehenvisning**, fx “…” (Ashworth, s. 17).
- **Ødelagte bogstavpar rettes:** PDF'er, hvor "ofte" står som "o#e", læses op, søges i og kopieres korrekt.
- **Ingen falske mellemrum i ord:** PDF'er, hvor der kommer mellemrum midt i ord ("Y ork"), læses op, søges i og kopieres korrekt ("York"). OCR-vinduet kan også rette PDF'ens eget tekstlag, så kopiering til Word og andre programmer giver den rigtige tekst.
- **Temaer:** Light Mode, Dark Mode, Læse Mode (Light og Dark) med skånsomme farver til lange læsesessioner, og Følg computerens tema.
- **Fokus Mode**, der kun viser PDF'en, og valg mellem kontinuerlig rulning, én side ad gangen eller to sider ved siden af hinanden.
- **Sideskift med tastaturet:** → og ← eller mellemrum skifter side, og Home og End springer til første og sidste side.
- **Faner og flere vinduer:** Hver PDF åbnes i sin egen fane. Træk fanerne rundt, træk en fane ud til sit eget vindue eller over i et andet vindue, ligesom i Finder og Safari. Du kan også trække PDF-filer ind i vinduet for at åbne dem.
- **Indholdsfortegnelse:** PDF'ens egen indholdsfortegnelse vises i sidepanelet, så du kan springe direkte til et kapitel.
- **Filpanel** med Skrivebord, Dokumenter, Overførsler, USB-nøgler og OneDrive.
- **Strømbesparende:** Programmet bruger lige så lidt strøm som Apples Preview, når du læser.

Du finder en vejledning til alle funktioner i programmet under **Hjælp** (⇧⌘?).

## Privatliv

Dine PDF-filer bliver på din Mac. Oplæsning med Macs egne stemmer og OCR foregår helt på din computer og virker uden internet. Kun hvis du selv vælger ElevenLabs, bliver den tekst, der læses op, sendt til ElevenLabs.

## Kontakt

Oplever du problemer, eller har du forslag til forbedringer? Skriv til **Kanikkekode@protonmail.com**.
