# 🎨 Como Usar com Claude Design

Instruções para conectar este repositório ao Claude Design e aproveitar o sistema de design da Rose Louise em todos os projetos visuais.

---

## 1. Conectar o Repositório

No Claude Design, durante o onboarding ou nas configurações:

1. Clique em **"Connect codebase"** ou **"Import design system"**
2. Conecte este repositório GitHub: `github.com/Lukyoon/RoseLouise`
3. O Claude Design vai ler automaticamente os arquivos de design

**Arquivos que o Claude Design vai consumir:**
- `brand/tokens.json` — cores, tipografia, espaçamentos
- `brand/brand-guide.md` — conceito visual e diretrizes
- `site/roselouise.html` — referência do site existente

---

## 2. O que o Claude Design vai entender automaticamente

Após conectar o repositório, o Claude Design conhecerá:

✅ **Paleta completa** (tons claros e escuros)
✅ **Tipografia** (Cormorant Garamond + Jost)
✅ **Conceito visual** ("Trilhas Iluminadas" — editorial + onírico)
✅ **Tamanhos de canvas** para Instagram (1080x1080, 1080x1350, 1080x1920)
✅ **Três temas prontos:** light, dark e cosmic

---

## 3. Prompts Sugeridos para Claude Design

### Para criar um carrossel de Instagram:
```
Crie um carrossel de 8 slides no formato 1080x1350px para o Instagram 
de Rose Louise sobre o tema [TEMA]. Use o tema escuro da marca 
(roxo profundo + dourado). Siga o sistema de design do repositório.
Base o conteúdo no arquivo instagram/carrosseis/despertar.md como referência.
```

### Para criar um post estático:
```
Crie um post para Instagram 1080x1080px para Rose Louise sobre [TEMA].
Use a paleta clara da marca. Tipografia: Cormorant Garamond para o título,
Jost para o corpo. Tom visual: editorial, acolhedor, sofisticado.
```

### Para criar uma apresentação / pitch deck:
```
Crie uma apresentação de [X] slides para Rose Louise apresentar seus serviços
de facilitação. Use o sistema de design da marca. Inclua seções de: quem sou,
como trabalho, produtos e contato.
```

### Para criar um one-pager:
```
Crie um one-pager profissional de Rose Louise para envio a parceiros e
veículos de comunicação. Apresentação da escritora e facilitadora.
Use a identidade visual completa da marca.
```

### Para criar capa de e-book:
```
Crie uma capa para o e-book "[TÍTULO]" de Rose Louise.
Formato: 1600x2400px (livro digital padrão).
Estética: atmosfera mágica e onírica, pergaminho e dourado ou roxo e dourado.
Tipografia elegante com Cormorant Garamond.
```

---

## 4. Estrutura de Arquivos para Claude Design

```
brand/
├── tokens.json          ← Sistema de design completo (cores, tipos, espaços)
└── brand-guide.md       ← Conceito visual, diretrizes, referências

instagram/
├── voz-e-essencia.md    ← Tom de voz e arquétipo (para conteúdo)
├── templates/           ← Templates de posts prontos
└── carrosseis/          ← Estruturas de carrosséis com direção visual

site/
└── roselouise.html      ← Site de referência para captura visual
```

---

## 5. Exportação

Após criar no Claude Design, exporte para:

| Destino | Formato | Uso |
|---------|---------|-----|
| Canva | Exportar para Canva | Edição colaborativa |
| Instagram | PDF / PNG | Publicação direta |
| Site | HTML | Integração web |
| Apresentações | PPTX | Reuniões, parcerias |

---

*Para dúvidas sobre a marca, consulte `docs/BRIEFING.md` e `brand/brand-guide.md`*
