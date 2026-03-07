# MedControl ANVISA

Aplicativo PWA para consulta de medicamentos controlados segundo a RDC 999/2025 e IN 360/2025 da ANVISA.

## 📋 Funcionalidades

- 🔍 Busca inteligente com autocomplete
- 📊 610 medicamentos cadastrados
- 🎨 Categorias coloridas (A1, A2, A3, B1, B2, C1-C5, Antimicrobianos, GLP-1)
- 💾 Funciona 100% offline (PWA)
- 📱 Interface responsiva para mobile
- ⬇️ Instalável na tela inicial

## 🚀 Como usar

### Opção 1: Abrir diretamente
Abra o arquivo `index.html` no navegador.

### Opção 2: Hospedar online (recomendado)
1. Faça upload de todos os arquivos para:
   - GitHub Pages
   - Netlify (app.netlify.com/drop)
   - Vercel
   - Qualquer servidor web

2. Acesse pelo celular e toque em "Adicionar à tela inicial"

## 📁 Estrutura

```
medcontrol-app/
├── index.html          # Página principal
├── manifest.json       # Configuração PWA
├── sw.js              # Service Worker (offline)
├── logo-farmaceutico-clinico.png
├── icon-72.png
├── icon-96.png
├── icon-128.png
├── icon-144.png
├── icon-152.png
├── icon-192.png
├── icon-384.png
├── icon-512.png
└── lista_medicamentos_alfabetica.txt
```

## 📱 Instalação no Celular

1. Acesse o site hospedado
2. Chrome/Android: Menu → "Adicionar à tela inicial"
3. Safari/iOS: Compartilhar → "Adicionar à Tela de Início"

## 📄 Fonte dos dados

- RDC Nº 999/2025
- IN Nº 360/2025
- ANVISA - Agência Nacional de Vigilância Sanitária

---
Desenvolvido por Farmacêutico Clínico
