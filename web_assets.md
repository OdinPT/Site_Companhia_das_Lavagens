Gerei os ativos essenciais de implementação web (web deployment) para a **Companhia das Lavagens - Alhos Vedros**, garantindo plena compatibilidade com navegadores modernos, dispositivos iOS/Android e normas PWA (Progressive Web App):

### 1. Favicon / PWA Icon (1:1)
- **Ativo**: `App favicon and PWA icon for 'Companhia das Lavagens'. High contrast, ultra crisp, modern minimalist vector emblem of water droplet and clean speed lines or automobile wash foam sparkle in bright cyan and pure white, set against a rich deep navy blue (#0c2340) full-bleed background. The background must be a continuous solid/subtle gradient navy color filling the entire square edge-to-edge with no rounded borders, no squircle container, no white margin, no framing border. Ultra clean flat vector graphic, high resolution, professional automotive branding.`
- **Design**: Símbolo moderno e minimalista com gota hidrodinâmica, linhas de velocidade e brilho em ciano vibrante e branco puro sobre fundo azul marinho profundo (`#0c2340`) a toda a largura (*full-bleed*). Ideal para identificadores em separadores de browser e atalhos de sistema.

### 2. Apple Touch Icon (1:1)
- **Ativo**: `Apple Touch Icon for 'Companhia das Lavagens' mobile web app. Premium automotive detailing symbol featuring a stylized hydrodynamic water splash droplet combined with automotive silhouette or high-gloss spark in vivid cyan and white on an edge-to-edge deep navy blue (#0c2340 to #133360) background. Full-bleed background filling the entire square canvas edge-to-edge. No rounded container shape, no simulated phone corners, no border frame. Clean iOS icon aesthetic, crisp vector styling, professional luxury detailing look.`
- **Design**: Ícone otimizado para ecrãs táteis iOS/iPadOS com silhueta dinâmica de automóvel e elemento de água com acabamento espelhado, transmitindo sofisticação e detalhe automóvel premium.

### 3. Manifesto Web (`manifest.json`)
- **Ativo**: `manifest.json`
- **Configuração**:
  - `name`: *"Companhia das Lavagens - Centro de Alhos Vedros"*
  - `short_name`: *"Lavagens AV"*
  - `theme_color` e `background_color`: `#0c2340`
  - `display`: `standalone`
  - **Atalhos rápidos integrados**:
    - *Ver Pistas em Tempo Real* (`/#pistas`)
    - *Preçário & Fichas* (`/#precario`)
    - *Como Chegar (GPS)* (`/#localizacao`)

---
**Código de integração para a tag `<head>` HTML:**
```html
<!-- Favicons & App Icons -->
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">

<!-- PWA Manifest & Theme -->
<link rel="manifest" href="/manifest.json">
<meta name="theme-color" content="#0c2340">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
```