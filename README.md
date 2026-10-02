# Hablar en cristiano

Skill de comunicación: explica cualquier tema técnico o complejo en **lenguaje claro y simple**, sin tecnicismos, usando analogías de la vida diaria.

## Qué es

"Hablar en cristiano" = explicar como si le hablaras a un amigo que NO es del tema. Sin palabras raras, con ejemplos de la vida real (cocina, carro, casa, deportes).

## Cómo instalarla (OpenClaw / OpenCode / agentes)

Clonar el repo y copiar `SKILL.md` a la carpeta de skills del agente:

```bash
# OpenClaw
cp SKILL.md ~/.openclaw/workspace/skills/hablar-en-cristiano/

# OpenCode / agentes compatibles (formato Claude Code)
mkdir -p <workspace>/skills/hablar-en-cristiano
cp SKILL.md <workspace>/skills/hablar-en-cristiano/
```

## Cuándo dispara

- El usuario pide "en cristiano", "simple", "sin tecnicismos".
- El tema es técnico y el usuario no lo es.
- El usuario no entendió algo y pide la versión corta.

## Las 5 reglas

1. Nada de tecnicismos (tradúcelos con analogía).
2. Analogías de la vida diaria.
3. Corto y directo.
4. Explica el QUÉ y el POR QUÉ, no el CÓMO.
5. Un ejemplo concreto antes que teoría.

---

Hecha para el ecosistema de agentes de DonGos. MIT.
