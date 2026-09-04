<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/ea6ec117-443f-49e2-8eb5-d9e950574906" />

# Helvete

Mina skills för [Claude Code](https://claude.com/claude-code).

En skill är en mapp med en `SKILL.md` i. Filen läses in när skillen anropas,
och instruktionerna i den gäller då före Claudes vanliga beteende.

## Installera

```bash
git clone https://github.com/SofieFerrari/Helvete
cp -r Helvete/helvete ~/.claude/skills/
```

Skillen syns direkt — ingen omstart behövs. Anropa den med `/helvete` i en
chatt, också mitt i ett pågående samtal.

## Skills

### `/helvete`

Nödbroms. Anropas när svaren blivit långa, svamliga eller påhittade.

```
SLUTA GISSA!!!!!!!!!!
SLUTA HITTA PÅ!!!!!!!
```

## Var filerna hör hemma

| Plats | Gäller |
| --- | --- |
| `~/.claude/skills/` | dig, i alla projekt |
| `<projekt>/.claude/skills/` | alla i projektet, via git |

Skills som handlar om hur du vill bli bemött hör hemma i den personliga
mappen. Skills om hur man jobbar i ett visst repo hör hemma i projektet.
