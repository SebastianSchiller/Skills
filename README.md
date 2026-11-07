# Skills
Skills for AI Usage

## Verfügbare Skills

### MoinRetro
*dein Norddeutscher AI-Buddy für bessere Retros.*

Entwickelt von **Heinz-Sebastian Schiller**.

Hilft dabei, aus einem Thema/Motto oder einer konkreten Teamherausforderung eine
vollständige, methodisch saubere Team-Retrospektive zu entwickeln – inklusive
PowerPoint, separaten Bildern und einer Miro-/Markdown-Version.

➡️ [moinretro/SKILL.md](moinretro/SKILL.md)

#### Voraussetzungen

- [OpenCode](https://opencode.ai) ist installiert
- `git` ist lokal installiert
- Zugriff auf dieses Repo: [github.com/SebastianSchiller/Skills](https://github.com/SebastianSchiller/Skills) (öffentlich, kein spezieller Zugriff nötig)

#### Installation

1. Repo an einen beliebigen Ort klonen, z.B.:
   ```bash
   git clone https://github.com/SebastianSchiller/Skills.git ~/opencode-skills/SebastianSchiller-Skills
   ```
2. Skill-Ordner nach `~/.opencode/skill/` verlinken:
   ```bash
   mkdir -p ~/.opencode/skill
   ln -s ~/opencode-skills/SebastianSchiller-Skills/moinretro ~/.opencode/skill/moinretro
   ```
3. OpenCode neu starten bzw. eine neue Session starten, damit der Skill erkannt wird.
4. Testen, z.B. mit einer Anfrage wie "Hilf mir eine Retro zu planen".

#### Updates erhalten

Da `~/.opencode/skill/moinretro` nur ein Symlink ist, reicht ein `git pull` im geklonten Repo-Ordner, um die neueste Version zu erhalten:

```bash
cd ~/opencode-skills/SebastianSchiller-Skills && git pull
```

#### Hinweise

- Die Stilvorlagen (`moinretro/references/*.pdf`) und das Logo (`moinretro/moinretro-logo.png`) werden automatisch mit installiert, kein zusätzlicher Schritt nötig.
- Alternative Installation ohne Symlink: Repo direkt in `~/.opencode/skill/` klonen; dann muss `git pull` direkt in diesem Ordner ausgeführt werden.
