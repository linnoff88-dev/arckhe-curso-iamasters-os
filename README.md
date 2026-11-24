# Curso iAmasters OS

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo sobre o sistema operativo agÃªntico **iAmasters OS** â€” formato ARCKHÉ AI, em portuguÃªs.

## Estrutura

- **Landing** (`index.html`)
- **Trilha 1 â€” Fundamentos** (Emerald Â· 3 mÃ³dulos Â· ~2h30)
- **Trilha 2 â€” Skills Curadas** (Blue Â· 3 mÃ³dulos Â· ~3h)
- **Trilha 3 â€” OperaÃ§Ã£o** (Purple Â· 3 mÃ³dulos Â· ~2h30)

Total: **9 mÃ³dulos Â· 54 tÃ³picos Â· ~8h**

## Publicar com GitHub Pages

### 1. Criar repo no teu GitHub

```bash
cd /home/nmaldaner/projetos/curso-iamasters-os
git init
git add .
git commit -m "feat: initial course content"
gh repo create curso-iamasters-os --public --source=. --push
```

### 2. Ativar GitHub Pages

```bash
gh repo edit --enable-pages
```

Ou via web:
1. Vai a `https://github.com/<teu-user>/curso-iamasters-os/settings/pages`
2. **Source**: GitHub Actions
3. O workflow `.github/workflows/deploy.yml` jÃ¡ estÃ¡ configurado.

### 3. Aceder ao site

ApÃ³s o primeiro push o site estÃ¡ em:
```
https://<teu-user>.github.io/curso-iamasters-os/
```

O deploy demora ~1-2 min. Estado em `Actions` no GitHub.

## Atualizar conteÃºdo

Qualquer push para `main` re-deploya automaticamente.

```bash
# Editar conteÃºdo
git add .
git commit -m "docs: update module 1.2"
git push
# â†“ Workflow corre automaticamente
# â†“ Site atualizado em ~90s
```

## Desenvolvimento local

NÃ£o precisa de build. Abre `index.html` no browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Ou servidor simples
python3 -m http.server 8000
# â†’ http://localhost:8000
```

## Formato

Seguindo padrÃ£o **ARCKHÉ AI**:
- Tailwind CDN, sem build
- Dark/light mode toggle
- 3 secÃ§Ãµes por tÃ³pico (O que Ã© / Por que aprender / Conceitos-chave)
- NavegaÃ§Ã£o rÃ¡pida em cada trilha
- Modal + pÃ¡gina completa por mÃ³dulo

## Repo do sistema

VersÃ£o PT-PT do iAmasters OS (a que este curso ensina): [linnoff88-dev/iamasters-os](https://github.com/linnoff88-dev/iamasters-os).

Curso por [ARCKHÉ AI](https://ARCKHÉ AI).

LicenÃ§a: MIT.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>