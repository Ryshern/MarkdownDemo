# Udviklingsværktøjer

Kontroller at din IT-undervisnings platform (PC/Mac) er opdateret. Gælder både OS, Applikationer og drivere.
Har du ikke en konto på GitHub konto skal du oprette en personlig konto. Det er gratis. GitHub er en samarbejdshub for tekstbaserede projekter aka. kode.

Vi skal bruge en række programmer som du bør installere hvis du ikke har dem allerede. Undgå portable (.zip) versioner, da værktøjerne så ikke registreres korrekt med OS og derfor ikke samarbejder optimalt. Undgå at have flere versioner af samme tool installeret parallelt af samme grund. Generelt foretræk.

Windows: installation med `winget`:

```cmd
> winget install -e --id Python.Python.3.12           (Windows)
```

Mac: installation med `homebrew`.

```sh
$ brew install python                                 (Mac/iOS)
```

## Opdater eller installer

| Application             | Tjek (cmd/terminal) | Installer fra                  |
| ----------------------- | ------------------- | ------------------------------ |
| Git, version >2.40      | `git --version`     | https://git-scm.com/           |
| VS Code, version > 1.80 | `code --version`    | https://code.visualstudio.com/ |
| Python, version > 3.10  | `python --version`  | https://www.python.org/        |

… der vil løbende komme flere til. Du skal derfor være fortrolig med din valgte platforms (PC/Mac) procedure for installation af nye applikationer, samt opdatering af eksisterende.

## Hvad er det

**Git**: VCS – Version control system. Samarbejdsportal for (primært) textbaserede projekter.

**VS Code**: IDE – Integrated Development Environment. Udviklerens schweizerkniv.

**Python**: Python er et populært og meget intuitivt programmeringssprog.

Det gælder for alle programmerne at de kan have en lang række udvidelser installeret – har du det skal du sikre dig at de er opdaterede. Evt. ryd op i det du ikke bruger, så du mindsker risikoen for konflikter, der kan drille og tage en del tid.

## Generelt om tools:
Demoer og eksempler I undervisningen vil være baseret på: Windows 10, VS Code, Python og GitHub.

Windows 11, Mac, GitLab og alle udgaver af Visual studio kan sagtens bruges. Men der vil være mindre forskelle på det som demoer, eksempler og vejledninger viser som du i første omgang selv skal kunne håndtere.

Vi bestræber os på at gøre det så let som muligt. Den funktionalitet vi kommer til at bruge, er meget platform uafhængig og bruges generelt i professionelle udvikler miljøer hvor valget mellem PC/Mac normalt er frit.

FYI: Denne side er lavet med Markdown - det kommer vi til at lege mere med.
