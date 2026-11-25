# Curso iAmasters OS

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo sobre o sistema operativo agêÂªntico **iAmasters OS** ê¢â¬â formato ARCKHê AI, em portuguêÂªs.

## Estrutura

- **Landing** (`index.html`)
- **Trilha 1 ê¢â¬â Fundamentos** (Emerald êÂ· 3 mêÂ³dulos êÂ· ~2h30)
- **Trilha 2 ê¢â¬â Skills Curadas** (Blue êÂ· 3 mêÂ³dulos êÂ· ~3h)
- **Trilha 3 ê¢â¬â OperaêÂ§êÂ£o** (Purple êÂ· 3 mêÂ³dulos êÂ· ~2h30)

Total: **9 mêÂ³dulos êÂ· 54 têÂ³picos êÂ· ~8h**

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
3. O workflow `.github/workflows/deploy.yml` jêÂ¡ estêÂ¡ configurado.

### 3. Aceder ao site

ApêÂ³s o primeiro push o site estêÂ¡ em:
```
https://<teu-user>.github.io/curso-iamasters-os/
```

O deploy demora ~1-2 min. Estado em `Actions` no GitHub.

## Atualizar conteêÂºdo

Qualquer push para `main` re-deploya automaticamente.

```bash
# Editar conteêÂºdo
git add .
git commit -m "docs: update module 1.2"
git push
# ê¢â â Workflow corre automaticamente
# ê¢â â Site atualizado em ~90s
```

## Desenvolvimento local

NêÂ£o precisa de build. Abre `index.html` no browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Ou servidor simples
python3 -m http.server 8000
# ê¢â â http://localhost:8000
```

## Formato

Seguindo padrêÂ£o **ARCKHê AI**:
- Tailwind CDN, sem build
- Dark/light mode toggle
- 3 secêÂ§êÂµes por têÂ³pico (O que êÂ© / Por que aprender / Conceitos-chave)
- NavegaêÂ§êÂ£o rêÂ¡pida em cada trilha
- Modal + pêÂ¡gina completa por mêÂ³dulo

## Repo do sistema

VersêÂ£o PT-PT do iAmasters OS (a que este curso ensina): [linnoff88-dev/iamasters-os](https://github.com/linnoff88-dev/iamasters-os).

Curso por [ARCKHê AI](https://ARCKHê AI).

LicenêÂ§a: MIT.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>