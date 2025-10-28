 # Om GitHub och Markdown:


Här är en lugn och klar översikt över vad du bör veta om GitHub och Markdown:

🧭 1. Grunderna
GitHub Markdown bygger på vanlig Markdown men har några extra funktioner.
Du kan använda den för att formatera text i:
    • README.md
    • issues och pull requests
    • wiki-sidor
    • kommentarer
Exempel:
# Rubrik 1
## Rubrik 2
### Rubrik 3

**Fet text**  
*Kursiv text*  
~~Genomstruken~~  

> Citat

- Punktlista
- Med flera rader
  - Och undernivå

1. Numrerad lista
2. Nästa punkt

`kod i rad`

```js
// Kodblock med språkfärgning
console.log("Hej GitHub!");

---

### 🧱 2. Länkar och bilder
GitHub gör det lätt att länka till filer i ditt repo.

#### Exempel:
```markdown
[Länk till annan fil](./mapp/fil.md)
![Alt-text för bild](bild.png)
💡 Tips: Bilder som ligger i ditt repo kan användas direkt, GitHub visar dem snyggt.

🧩 3. Tabeller
GitHub har inbyggt stöd för tabeller:
| Namn | Roll | Land |
|------|------|------|
| Hoà  | Spion | Vietnam |
| Sven | Advokat | Sverige |

💬 4. Citat, kod och block
Du kan kombinera olika block:
    • > Citat används ofta för att markera resonemang.
    • Tre backticks (```) gör kodblock.
    • Du kan ange språk efter ``` för syntax highlighting (t.ex. js, html, css).

🔗 5. Automatisk länkning och @-taggar
GitHub känner automatiskt igen:
    • #123 → issue eller pull request
    • @användarnamn → taggar personer
    • commit-id → länk till commit

✅ 6. Checklistor
Perfekt för TODO eller projektstatus:
- [x] Förstå Markdown
- [ ] Lära mig Git
- [ ] Göra snygg README

🧠 7. Extra GitHub-funktioner (GFM)
GitHub Flavored Markdown lägger till några unika saker:
    • Task lists (som ovan)
    • Tabeller
    • Syntax highlighting
    • Strikethrough (text)
    • Autolänkning av URL:er
    • HTML inline (t.ex. <sub>, <sup>, <br>)
💡 GitHub renderar även vissa emojis med kolon-syntax, t.ex. :smile: → 😄

⚙️ 8. README.md – den viktigaste filen
I varje repository visas README.md automatiskt på förstasidan.
Bra att inkludera:
    • Kort beskrivning av projektet
    • Hur man installerar eller kör det
    • Exempel på användning
    • Licensinformation
    • Kontakt eller länk till hemsida

🧩 9. Kombination med HTML
Du kan använda enkel HTML när Markdown inte räcker:
<p align="center">
  <img src="logo.png" width="200" />
</p>
Men undvik komplex HTML — GitHub filtrerar bort skript och farlig kod.

📚 10. Referens och vidare läsning
Officiell dokumentation:
👉 GitHub Flavored Markdown Spec
👉 Mastering Markdown (GitHub Do
