# Visión Chile 2030 - Candidatos Presidenciales

Comparación de las visiones 2030 de los 8 candidatos presidenciales de Chile, generadas por tres sistemas de IA generativa:

- **GPT-5 with Research** (OpenAI)
- **Claude Sonnet 4.5** (Anthropic)
- **Perplexity**

## Candidatos (ordenados alfabéticamente)

1. Eduardo Artés
2. Marco Enríquez-Ominami
3. Jeannette Jara
4. Johannes Kaiser
5. José Antonio Kast
6. Evelyn Matthei
7. Harold Mayne-Nicholls
8. Franco Parisi

## Ver la página

Visita: [https://tu-usuario.github.io/tu-repositorio/](https://tu-usuario.github.io/tu-repositorio/)

## Estructura del proyecto

```
.
├── index.html          # Página principal con las visiones comparadas
├── fotos/              # Fotografías de los candidatos
├── inputs/             # Archivos JSON con los datos originales
│   ├── inputs_gpt5research.json
│   ├── inputs_sonnet4.5.json
│   ├── inputs_perplexity.json
│   └── fotos.json
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions para deployment automático
```

## Deployment

El sitio se despliega automáticamente en GitHub Pages cada vez que se hace push a la rama `main` o `master`.
