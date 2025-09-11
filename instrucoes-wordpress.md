# Instruções para Integração com WordPress

## Opção 1: HTML Direto no WordPress

1. **Arquivo**: `mapa-uece-wordpress.html`
2. **Como usar**:
   - Copie todo o conteúdo do arquivo HTML
   - No WordPress, crie uma nova página ou post
   - Mude para o editor de código HTML (não visual)
   - Cole o código completo
   - Publique a página

## Opção 2: Iframe (Recomendado)

1. **Arquivo**: `mapa-uece-iframe.html`
2. **Como usar**:
   - Faça upload do arquivo `mapa-uece-iframe.html` para seu servidor
   - No WordPress, adicione um bloco HTML personalizado
   - Use o código:
   ```html
   <iframe src="URL_DO_SEU_ARQUIVO/mapa-uece-iframe.html" 
           width="100%" 
           height="600px" 
           frameborder="0">
   </iframe>
   ```

## Características do Mapa

- **Tecnologia**: Leaflet.js (biblioteca de mapas open source)
- **Dados**: 33 polos da UECE espalhados pelo Ceará
- **Funcionalidades**:
  - Mapa interativo com zoom e navegação
  - Marcadores clicáveis para cada polo
  - Popups com informações dos cursos
  - Lista lateral com todos os polos (versão completa)
  - Design responsivo para mobile

## Versões Disponíveis

1. **React App** (site independente): Versão completa com sidebar
2. **WordPress HTML**: Versão completa para integração direta
3. **Iframe**: Versão simplificada, apenas mapa com popups

## Dados dos Polos

O mapa inclui todos os 33 polos da UECE com:
- Localização geográfica precisa
- Lista completa de cursos oferecidos
- Diferenciação entre graduação e especialização
- Interface intuitiva e responsiva

## Suporte Técnico

- Compatível com todos os navegadores modernos
- Responsivo para dispositivos móveis
- Não requer plugins adicionais no WordPress
- Funciona com HTTPS e HTTP

