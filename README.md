# Zvlněnec

Zvlněnec je balíček pro LaTeX navržený k automatickému přidávání tildy (~) za určená jednopísmenná slova v textovém režimu, kromě matematického režimu. Tento balíček je obzvláště užitečný pro jazyky jako je čeština, kde takové úpravy mohou pomoci v sazbě a čitelnosti. Balíček specificky upravuje jednopísmenná slova "K", "k", "S", "s", "V", "v", "Z", "z", "O", "o", "U", "u", "A", "a", "I", "i", která jsou často používána ve češtině.

## Funkce

- Automaticky přidává tildu za specifikovaná jednopísmenná slova: "K", "k", "S", "s", "V", "v", "Z", "z", "O", "o", "U", "u", "A", "a", "I", "i".
- Vylučuje matematický režim, aby nedošlo k nechtěným úpravám vzorců.
- Jednoduchá integrace do stávajících projektů LaTeX.

## Začínáme

Pro začátek s Zvlněncem postupujte podle následujících kroků:

### Požadavky

Ujistěte se, že máte ve svém systému nainstalovaný LaTeX, ideálně s LuaTeXem, protože tento balíček je navržen pro práci s LuaTeXem.

### Instalace

1. Naklonujte tento repozitář nebo přímo stáhněte soubory.
2. Vložte soubor `zvlnenec.sty` do adresáře vašeho projektu LaTeX.

### Použití

Pro použití Zvlněnce ve vašich dokumentech LaTeX jednoduše zahrňte tento balíček ve vaší preambuli:

```latex
\usepackage{zvlnenec}

```

Poté můžete otestovat balíček pomocí souboru `test.tex` zahrnutého v tomto repozitáři, který poskytuje příklady zpracování textu Zvlněncem.

## Testování

Pro provedení testu balíčku Zvlněnec:

1. Přejděte do adresáře obsahujícího `test.tex`.
2. Kompilujte dokument pomocí LuaTeXu, například:

```bash
lualatex test.tex
```

Podívejte se na výstup, abyste viděli, jak Zvlněnec upravil určená písmena.

## Přispívání

Váš příspěvek je vítán! Pokud máte zájem o rozvoj projektu Zvlněnec, můžete přispívat různými způsoby:

- **Podávání požadavků na změny** (pull requests): Máte-li nápad na zlepšení nebo novou funkci, neváhejte vytvořit požadavek na změnu.
- **Nahlášení problémů** (issues): Pokud narazíte na chybu nebo máte návrh na zlepšení, zaregistrujte to jako issue v repozitáři.
- **Diskuze a návrhy**: Jakékoli další nápady na zlepšení nebo otázky týkající se použití Zvlněnce můžete sdílet prostřednictvím issues nebo přímou komunikací.

Budeme rádi za jakékoliv příspěvky, které pomohou Zvlněnec stát se ještě lepším!

## Licence

Tento projekt je licencován pod licencí MIT - podrobnosti naleznete v souboru [LICENSE](LICENSE).

## Autoři

- **Jan Chouba** - *Počáteční práce*
