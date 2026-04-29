{
  "name": "Rose Louise — Design System",
  "version": "1.0.0",
  "description": "Sistema de design para todos os projetos de Rose Louise. Conceito visual: Editorial literária com atmosfera mágica e onírica. Tagline: Trilhas Iluminadas.",

  "color": {
    "brand": {
      "parchment":   { "value": "#faf6ee", "description": "Fundo principal — pergaminho" },
      "parchmentDark": { "value": "#ede4d3", "description": "Fundo secundário, cards" },
      "cream":       { "value": "#f5efe3", "description": "Superfícies suaves" },
      "gold":        { "value": "#c9963a", "description": "Cor de destaque — dourado" },
      "goldPale":    { "value": "#e8c97a", "description": "Dourado claro, hover" },
      "goldLight":   { "value": "#f5e4b0", "description": "Dourado suave, backgrounds" },
      "ink":         { "value": "#1a1209", "description": "Texto principal — tinta" },
      "inkSoft":     { "value": "#3d3120", "description": "Texto secundário" },
      "inkMuted":    { "value": "#7a6b52", "description": "Texto terciário, labels" },
      "coral":       { "value": "#c85f3a", "description": "Acento quente, CTAs" }
    },
    "mystical": {
      "purple":      { "value": "#2E1A47", "description": "Roxo profundo — fundo escuro/místico" },
      "indigo":      { "value": "#1A1F5E", "description": "Índigo — gradientes noturnos" },
      "goldSoft":    { "value": "#D4AF37", "description": "Dourado suave para fundos escuros" },
      "emerald":     { "value": "#50C878", "description": "Verde esmeralda — contraste" }
    },
    "neutral": {
      "white":       { "value": "#ffffff" },
      "offwhite":    { "value": "#f8f5f0" },
      "gray100":     { "value": "#f0ebe2" },
      "gray300":     { "value": "#c8bfb0" },
      "gray500":     { "value": "#8a7d6a" },
      "black":       { "value": "#0d0b08" }
    }
  },

  "typography": {
    "fontFamily": {
      "serif":  { "value": "'Cormorant Garamond', Georgia, serif", "use": "Títulos, citações, elementos poéticos" },
      "sans":   { "value": "'Jost', system-ui, sans-serif", "use": "Corpo de texto, navegação, labels" }
    },
    "fontSize": {
      "xs":   { "value": "0.75rem" },
      "sm":   { "value": "0.875rem" },
      "base": { "value": "1rem" },
      "lg":   { "value": "1.125rem" },
      "xl":   { "value": "1.25rem" },
      "2xl":  { "value": "1.5rem" },
      "3xl":  { "value": "2rem" },
      "4xl":  { "value": "2.75rem" },
      "5xl":  { "value": "4rem" },
      "hero": { "value": "clamp(3rem, 7vw, 6rem)" }
    },
    "fontWeight": {
      "light":   { "value": "300" },
      "regular": { "value": "400" },
      "medium":  { "value": "500" },
      "semibold":{ "value": "600" }
    },
    "lineHeight": {
      "tight":   { "value": "1.1" },
      "snug":    { "value": "1.3" },
      "normal":  { "value": "1.6" },
      "relaxed": { "value": "1.8" }
    },
    "letterSpacing": {
      "tight":  { "value": "-0.02em" },
      "normal": { "value": "0em" },
      "wide":   { "value": "0.08em" },
      "wider":  { "value": "0.12em" },
      "widest": { "value": "0.2em" }
    }
  },

  "spacing": {
    "1":  { "value": "0.25rem" },
    "2":  { "value": "0.5rem" },
    "3":  { "value": "0.75rem" },
    "4":  { "value": "1rem" },
    "6":  { "value": "1.5rem" },
    "8":  { "value": "2rem" },
    "12": { "value": "3rem" },
    "16": { "value": "4rem" },
    "24": { "value": "6rem" },
    "32": { "value": "8rem" }
  },

  "borderRadius": {
    "sm":   { "value": "4px" },
    "md":   { "value": "8px" },
    "lg":   { "value": "16px" },
    "full": { "value": "9999px" }
  },

  "shadow": {
    "sm":   { "value": "0 1px 4px rgba(26,18,9,0.08)" },
    "md":   { "value": "0 4px 16px rgba(26,18,9,0.12)" },
    "lg":   { "value": "0 8px 32px rgba(26,18,9,0.16)" },
    "gold": { "value": "0 4px 24px rgba(201,150,58,0.25)" }
  },

  "instagram": {
    "canvasSize": {
      "post":     { "value": "1080x1080", "ratio": "1:1" },
      "portrait": { "value": "1080x1350", "ratio": "4:5" },
      "story":    { "value": "1080x1920", "ratio": "9:16" }
    },
    "themes": {
      "light": {
        "background": "#faf6ee",
        "text":       "#1a1209",
        "accent":     "#c9963a"
      },
      "dark": {
        "background": "#2E1A47",
        "text":       "#f5efe3",
        "accent":     "#D4AF37"
      },
      "cosmic": {
        "background": "#1A1F5E",
        "text":       "#ffffff",
        "accent":     "#D4AF37"
      }
    }
  }
}
