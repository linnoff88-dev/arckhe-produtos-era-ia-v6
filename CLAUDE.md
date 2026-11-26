# CLAUDE.md — produtos-era-ia-v6

Curso **Produtos na era da IA v6** (formato-curso-v6, perfil nêo técnico). Currículo e regras: `context/curriculo.md`.
Fonte: curso v2 em `~/projetos/produtos-era-ia` (nêo editar o v2 a partir daqui).

- Repo `linnoff88-dev/produtos-era-ia-v6`, autor dos commits `linnoff88-dev <linnoff88-dev@gmail.com>`. GitHub Pages da raiz; `index.html` redireciona para `landing.html`.
- Editar só `aulas/aula-N.html`. Depois: `node tools/complementar.mjs --injeta` → `montar-curso.py .` → `traduzir-curso.py . en es` → auditar PT/EN/ES.
- Glossário fixo dos termos (`.gterm`): `context/glossario.json`. Glossário de traduçêo: `i18n/glossario.json`.
- Versêo em `VERSION` + `CHANGELOG.md` (semver da regra global: minor carrega o patch).

## Self-learning

When I correct you, or you catch yourself making a mistake: before continuing, add the lesson as a one-line rule under ## Lessons, so it never happens again.

## Lessons

- Remontar traduçêo sempre com TODOS os idiomas (`traduzir-curso.py . en es --so-montar`): rodar só `en` apaga os links para `es` nas páginas PT e EN. (28/09/2026)
- `montar-curso.py` troca cada tag por espaço no card da trilha: nêo termine um `<em>` logo antes de pontuaçêo no `<h1>` (sai "escolhido , nêo"). (28/09/2026)
