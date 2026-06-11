# Chalé Paraibuna · Ideias e Referências

Documento de referências visuais e diretrizes de projeto para os chalés Airbnb em Paraibuna/SP, Reserva Altos das Laranjeiras, Gleba 14 (4,56 hectares).

## 📋 Conteúdo atual

- **15 referências** de design (Airbnb, Instagram, Booking)
- **30 imagens** organizadas por categoria
- **7 seções temáticas** + Resumo das diretrizes
- Diretrizes de materiais, paisagismo e implantação

## 🌐 Acesso online

Site publicado via GitHub Pages: `https://[USERNAME].github.io/[REPO-NAME]/`

## 📂 Estrutura

```
.
├── index.html          # Documento principal
├── CHANGELOG.md        # Histórico de mudanças
├── README.md           # Este arquivo
└── imagens/            # 30 fotos de referência
```

## 🔍 Como saber o que mudou

Existem **3 formas** de acompanhar mudanças:

### 1. Caixa "Últimas atualizações" no topo do site
Quando você abre o `index.html`, a primeira coisa que aparece é uma caixa
mostrando as mudanças da última versão e um botão pra expandir o histórico completo.

### 2. Arquivo CHANGELOG.md
Lista detalhada de todas as mudanças por versão, seguindo o padrão
[Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/).

### 3. Histórico do Git
```bash
git log --oneline           # Ver commits resumidos
git log --stat              # Ver arquivos alterados em cada commit
git diff v1.4.0..v1.5.0     # Comparar versões específicas
```

## 🏷️ Versionamento

Segue versionamento semântico: `MAJOR.MINOR.PATCH`

- **MAJOR** — Reorganizações estruturais grandes
- **MINOR** — Novas referências, fotos ou blocos
- **PATCH** — Ajustes pequenos (correções de texto)

## 🚀 Deploy no GitHub Pages

1. Criar repositório no GitHub
2. Subir arquivos: `git push -u origin main`
3. Settings → Pages → Source: `main` / root
4. Aguardar ~1 min, acessar `https://[USERNAME].github.io/[REPO]/`
