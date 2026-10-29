# Back2Byte Interactive

Website institucional da Back2Byte Interactive, holding B2B especializada em engenharia de games, co-development, porting, otimização e gamificação corporativa.

## Estrutura

- `index.html`: estrutura semântica e conteúdo inicial em português.
- `styles.css`: identidade visual, temas escuro/claro, componentes e layouts responsivos.
- `script.js`: alternância de idioma e tema, navegação móvel, abas técnicas, animações e formulário de contato.
- `content.json`: metadados e traduções em português e inglês.
- `assets/`: logotipos e espaço para imagens que serão adicionadas ao site.

## Visualização local

Como o site carrega `content.json` usando `fetch`, abra-o por um servidor HTTP local, não diretamente como arquivo. No VS Code, inicie o **Live Server** na raiz do projeto e abra a URL local disponibilizada.

O formulário de contato prepara uma mensagem e abre o aplicativo de e-mail configurado no dispositivo. Ele não envia dados a um servidor.

## Conteúdo e identidade

Edite os textos em `content.json`, mantendo as mesmas chaves nas seções `pt` e `en`. As cores e os estilos globais estão definidos como propriedades CSS em `:root`, em `styles.css`. O tema escuro é o padrão; o controle no cabeçalho alterna para o tema claro.

## Licença

Este projeto é propriedade intelectual da Back2Byte Interactive. Todos os direitos reservados.
