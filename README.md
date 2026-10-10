# Irmãos Salem — Produtos Naturais e Suplementos

Landing page mobile-first de alta conversão para a loja **Irmãos Salem** (Vila Carrão / Aricanduva — Zona Leste de São Paulo).

## Stack
- HTML5 semântico
- Tailwind CSS (CDN)
- Vanilla JavaScript (sem dependências)

## Recursos
- SEO local completo (meta tags geo + JSON-LD `HealthFoodStore`)
- Catálogo com filtros por abas (sem recarregar a página)
- Links de WhatsApp parametrizados por produto
- Prova social, mapa, horários com status "Aberto agora" e rotas (Google Maps / Waze)
- Botão flutuante de WhatsApp

## Rodar localmente
```bash
python -m http.server 5500
```
Acesse `http://localhost:5500`.

## Configuração
Edite o objeto `CONFIG` no final do `index.html` (número de WhatsApp, endereço e coordenadas) e a lista `PRODUCTS` para atualizar o catálogo.
