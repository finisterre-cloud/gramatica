# Gramática

Skills para agentes de IA en español.

## Skills

| Skill                                                      | Descripción                                                                                                               |
| ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [`gramatica-espanola`](skills/gramatica-espanola/SKILL.md) | Normas de ortografía, puntuación, gramática y estilo del español (RAE y ASALE) para escribir, traducir y corregir textos. |

## Instalación

Con [skills.sh](https://skills.sh):

```sh
npx skills add finisterre-cloud/gramatica
```

Para instalar solo una skill:

```sh
npx skills add finisterre-cloud/gramatica --skill gramatica-espanola
```

## Estructura

```
skills/
└── gramatica-espanola/
    ├── SKILL.md            # pasos y lista rápida de reglas
    └── references/         # detalle que el agente consulta cuando lo necesita
        ├── ortografia.md
        ├── puntuacion.md
        ├── gramatica.md
        ├── estilo.md
        ├── regiones.md
        └── tecnico.md
```
