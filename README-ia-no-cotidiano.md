# IA no Cotidiano

Site educativo para estudantes e jovens sobre como a inteligência artificial aparece em atividades cotidianas. O layout foi implementado a partir das quatro telas do protótipo em PDF: Inicial, Sobre a IA, Exemplos no dia a dia e Contato. A página “Aplicações da IA” corresponde à tela de exemplos.

## Estratégia de desenvolvimento

| Etapa | Objetivo | Resultado esperado |
|---|---|---|
| 1. Ler o protótipo | Identificar páginas, composição, paleta, hierarquia visual e elementos | Referência visual documentada para orientar o site |
| 2. Organizar páginas e conteúdo | Planejar Inicial, Sobre, Aplicações da IA e Contato com navegação clara | Quatro páginas educativas coerentes e relacionadas |
| 3. Construir a estrutura | Usar HTML5 e a grade responsiva do Bootstrap 5, sem JavaScript | Páginas sem scripts, com links HTML funcionando |
| 4. Aplicar a identidade visual | Reproduzir cabeçalho/rodapé marinho, áreas claras, acentos azuis, cartões arredondados e tipografia sem serifa | Interface consistente com o protótipo em computador, tablet e celular |
| 5. Revisar e entregar | Conferir caminhos, acessibilidade, formulários e adaptação a telas menores | Projeto organizado e simples de abrir no Visual Studio Code |

## Páginas

- `index.html` — página Inicial.
- `sobre.html` — definição, habilidades da IA e linha do tempo.
- `aplicacoes.html` — exemplos em Casa, Trabalho, Educação, Saúde, Lazer e Mobilidade; comunicação aparece nos exemplos de celular.
- `contato.html` — formulário com validação nativa do navegador e canais de contato.

As páginas têm um botão destacado para voltar ao site moderno. Os arquivos usam o sufixo `-ia-no-cotidiano` para coexistirem na raiz sem substituir os arquivos do site moderno. O formulário usa um endereço `mailto` de demonstração (`contato@ianocotidiano.com`). Depois da validação dos campos, o navegador solicita a abertura do aplicativo de e-mail; o site não tem servidor, não armazena mensagens nem as envia em segundo plano. Substitua o endereço por um canal real antes de usar o site publicamente. A folha de estilos do Bootstrap 5 é carregada por CDN; portanto, é necessária uma conexão à internet para carregá-la. Nenhum JavaScript do Bootstrap é incluído.

## Abrir no Visual Studio Code

1. Abra a pasta `iacotidiano` no Visual Studio Code.
2. Com uma conexão à internet, abra `index.html` diretamente no navegador ou use uma extensão de servidor estático, como Live Server.
3. Use o menu para navegar pelas páginas. O projeto é estático e não precisa de instalação de dependências nem de comandos de compilação.

## Estrutura

```text
ia-no-cotidiano.html
sobre-ia-no-cotidiano.html
aplicacoes-ia-no-cotidiano.html
contato-ia-no-cotidiano.html
css/
  style-ia-no-cotidiano.css
img/
  project-logo-ia-no-cotidiano.svg
  README-ia-no-cotidiano.md
README-ia-no-cotidiano.md
TODO-ia-no-cotidiano.md
app-ia-no-cotidiano.config.ts
manus-routes-ia-no-cotidiano.json
manus-routes.json
app.config.ts  (metadado do projeto; não é carregado pelo site)
README.md
TODO.md
```
