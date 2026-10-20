# Ritmo — um dia de cada vez

Aplicativo leve de tarefas para adultos, feito para ajudar a organizar prioridades sem transformar produtividade em cobrança.

## O que já funciona

- Lista diária com tarefas iniciais editáveis: adicionar, concluir e remover.
- Círculo de progresso semanal de 0% a 100%, calculado sobre as tarefas concluídas nos sete dias.
- Mensagens de incentivo conforme o progresso: começo, 10%, 50%, 70%, 90% e 100%.
- Sugestões de recompensa com atividades, comidas e pequenos prazeres escolhidos pela pessoa.
- Layout responsivo para celular e computador.
- Salvamento local no navegador, sem conta ou servidor.

## Como abrir

Abra o arquivo `index.html` no navegador ou acesse o GitHub Pages quando a publicação estiver concluída.

Os dados ficam salvos no armazenamento local do navegador e não são sincronizados entre dispositivos. Limpar os dados do navegador apaga o progresso salvo.

## Publicação

O fluxo em `.github/workflows/deploy-pages.yml` publica o conteúdo do repositório no GitHub Pages sempre que há uma atualização na branch `main`. A página fica disponível em:

`https://silvajunioris.github.io/ritmo-app/`

## Próximos passos sugeridos

1. Testar com rotinas diferentes e ajustar as tarefas padrão.
2. Permitir categorias e horários das tarefas.
3. Criar histórico visual de semanas anteriores.
4. Avaliar autenticação e sincronização entre dispositivos antes de adicionar dados em nuvem.

## Tecnologias

HTML, CSS e JavaScript sem dependências externas.
